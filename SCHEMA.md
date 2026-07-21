# Wiki Schema

## Domain
브랜업(주) — 화장품 수출 전문 중소기업. 업무 지식, 정부지원사업, 수출/계약, 재무, 기술문서, 의사결정 기록.

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `export-contract-process.md`)
- **모든 페이지 본문은 한국어로 작성** (기술용어·고유명사는 영어 원문 사용 가능)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages (minimum 2 outbound links per page)
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`
- **Provenance markers:** On pages synthesizing 3+ sources, append `^[raw/articles/source-file.md]`
  at the end of paragraphs whose claims come from a specific source.
- **GitHub push:** 모든 변경사항은 commit 후 push

## 디렉토리 레이아웃 (3 Layer)

```
wiki/
├── SCHEMA.md           # 본 파일
├── index.md            # 섹션별 콘텐츠 카탈로그
├── log.md              # 변경 이력 (append-only, 500행 초과시 연간 로테이트)
├── README.md           # GitHub 레포 랜딩 페이지
├── raw/                # Layer 1: 불변 원본
│   ├── articles/       # 웹 클리핑, Slack 요약, 외부 참고자료
│   ├── papers/         # PDF 규제문서, 백서, 연구자료
│   ├── transcripts/    # 회의록 원본, 인터뷰, 미팅 기록
│   └── assets/         # 이미지, 다이어그램 (Obsidian ![[image.png]])
├── channels/           # Layer 2: Slack 채널별 지식 허브 (아래 상세)
│   └── index.md        #   채널 맵 — 전체 채널 목록 + 설명
├── entities/           # Layer 2: 엔터티 (거래처, 파트너사, 인물, 브랜드)
├── concepts/           # Layer 2: 개념/주제 (정부지원사업, 수출바우처, 규제 등)
├── comparisons/        # Layer 2: 비교 분석 (계약서 조항별, 업체별)
├── queries/            # Layer 2: 저장한 질의 결과
└── _archive/           # Layer 3: 아카이브
    ├── entities/
    ├── concepts/
    └── comparisons/
```

## Frontmatter
  ```yaml
  ---
  title: Page Title
  created: YYYY-MM-DD
  updated: YYYY-MM-DD
  type: entity | concept | comparison | query | summary
  tags: [from taxonomy below]
  sources: [raw/articles/source-name.md]
  confidence: high | medium | low
  contested: true
  contradictions: [other-page-slug]
  ---
  ```

### raw/ Frontmatter
  ```yaml
  ---
  source_url: https://example.com/article
  ingested: YYYY-MM-DD
  sha256: <hex digest of the raw content below the frontmatter>
  ---
  ```

## Tag Taxonomy
- **Business:** contract, export, partner, customer, finance, insurance, pl-insurance
- **Government:** support-program, export-voucher, subsidy, monitoring, certification
- **Product:** cosmetics, formulation, certification, packaging, regulation, fda, mocra
- **People:** team, role, contact, ceo, director
- **Process:** workflow, approval, reporting, meeting, decision
- **Tech:** developer, infra, project, system, code, automation
- **Market:** usa, canada, mexico, china, export-market
- **Meta:** comparison, timeline, decision, guideline, strategy

## Page Thresholds
- **Create page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create page** for passing mentions, minor details
- **Split page** when exceeds ~200 lines
- **Archive page** when content fully superseded — move to `_archive/`, remove from index
- **Entity page type**: reserve `entities/` for PEOPLE (회사 내 인물/직원), COMPANIES (거래처/파트너사), BRANDS. Not for meeting minutes, proposals, or documents — those go in `raw/transcripts/` or `raw/articles/`.
- **Concept page type**: `concepts/` for recurring topics (정부지원사업, 수출바우처, PL보험, Slack 도입 등)
- **Channel page type**: `channels/` for Slack 채널별 지식 허브. 각 채널은 프로젝트 단위 또는 사내 부서 단위.

## Channel Pages (채널별 지식 허브)

Slack 채널은 단순 대화방이 아니라 **프로젝트·부서 단위 지식 저장소**다.
`channels/채널명.md`는 해당 채널의 **아이덴티티·맥락·누적 지식**을 관리한다.

### 채널 페이지 생성 조건
- **Slack 채널 1개 = channels/ 페이지 1개** (1:1 매핑)
- 채널에 의미 있는 업무 대화가 5회 이상 오간 경우 생성
- 일회성/테스트 채널은 제외
- 채널이 닫히거나 프로젝트 종료 시 `status: archived`로 변경

### 채널 페이지 포맷
```yaml
---
title: "채널명"
type: channel
created: YYYY-MM-DD
updated: YYYY-MM-DD
tags: [channel, project|department, 관련태그]
slack_channel_id: Cxxxxxxx
status: active | archived | merged
related_entities: [entities/회사명]
related_concepts: [concepts/주제명]
---
```

### 채널 페이지 내용 구조
1. **채널 개요** — 목적, 참여자, Slack 링크
2. **최근 활동 요약** — 최근 7일간 주요 논의 (크론이 자동 갱신)
3. **주요 의사결정** — 날짜별 결정사항 (chronological)
4. **관련 위키 페이지** — `[[wikilinks]]`로 entities/·concepts/ 연결
5. **누적 지식 (Knowledge Base)** — 채널에서 반복 논의되는 노하우, 룰, 프로세스

### 업데이트 규칙
- **크론 실행 시:** 채널의 최근 메시지를 스캔하여 "최근 활동 요약" 갱신
- **새 의사결정 발생 시:** 수동 또는 자동으로 "주요 의사결정"에 추가
- **entities/·concepts/ 페이지 생성 시:** provenance에 `^[channels/채널명.md]` 추가

## Entity Pages
One page per notable entity (회사/인물/브랜드). Include:
- Overview / what it is
- Key facts and dates
- Relationships to other entities ([[wikilinks]])
- Source references

## Concept Pages
One page per concept or topic. Include:
- Definition / explanation
- Current state of knowledge
- Open questions or debates
- Related concepts ([[wikilinks]])

## Comparison Pages
Side-by-side analyses. Include:
- What is being compared and why
- Dimensions of comparison (table format preferred)
- Verdict or synthesis
- Sources

## Update Policy
When new information conflicts with existing content:
1. Check the dates — newer sources generally supersede older ones
2. If genuinely contradictory, note both positions with dates and sources
3. Mark the contradiction in frontmatter: `contradictions: [page-name]`
4. Flag for user review in the lint report
