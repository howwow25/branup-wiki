# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete

## [2026-07-15] rebuild | Wiki 전면 리빌드 (모델 변경 계기)

**리빌드 사유:** 모델 변경으로 기존 위키 구조·품질 개선 필요. llm-wiki 스킬 기반 표준 구성으로 전환.

**변경 사항 요약:**
- **SCHEMA.md 개선:** 디렉토리 레이아웃 명확화 (entities는 회사/인물/브랜드만, concepts에 회의록/제안서)
- **디렉토리 재구조화:** `_archive/` 하위에 entities/concepts/comparisons 서브디렉토리 생성
- **페이지 재분류:**
  - ✅ 유지 (entities): `aizel-contract.md`, `aizel-contract-review-request.md`
  - ➡️ 이동 (entities→concepts): `aizel-meeting-2026-07-14.md`, `aizel-proposal-lineup-2026-07-14.md`
  - ✅ 유지 (concepts): `integrated-weekly-strategy.md`, `slack-adoption.md`
- **신규 페이지 (8개):**
  - `entities/enagic-usa.md` — Enagic USA 북미 유통 파트너
  - `entities/branup-org-chart.md` — 브랜업 조직도
  - `concepts/government-support-programs.md` — 정부지원사업 모니터링
  - `concepts/export-voucher.md` — 수출바우처 상세
  - `concepts/product-liability-insurance.md` — PL보험
  - `concepts/branup-finance.md` — 브랜업 재무현황
  - `concepts/tsonax.md` — TSonaX 개발 현황
- **깨진 링크 수정:** slack-adoption.md의 `branup-dashboard` 링크 제거 및 대체
- **Wikilinks 교정:** 모든 페이지 한글 링크 → 영문 파일명 기반 `[[slug|표시명]]` 형식으로 통일
- **index.md 재작성:** 7페이지 → 14페이지, 섹션 구분 명확화
- **README.md 재작성:** 신규 구조 반영
- **백업:** `~/wiki-backup-20260715`에 기존 전체 위키 보관

## [2026-07-15] sync | 브랜업 대시보드 DB 동기화
- 프로젝트 7개 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-15 16:10

## [2026-07-16] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-16 08:07

## [2026-07-16] ingest | Slack 채널 배치 수집 (7/9~7/16)

### 새로 다운로드한 원본 파일 (6개)
- `raw/articles/hoiuirok_aijel_20260714.docx` (490KB) — 아이젤 미팅 회의록 상세
- `raw/articles/aijel_brandup_sin_gue_lineup_260714.pptx` (10,498KB) — 아이젤 신규 라인업 제안서
- `raw/articles/tonghap_jugan_junryak_7w3_20260714.pdf` (1,039KB) — 통합주간전략 7월 3주차
- `raw/articles/peachy_business_model_summary.pdf` (440KB) — Peachy 기업 분석
- `raw/articles/aijel_gyeyakgeomto_yoengseo.docx` (24KB) — 아이젤 계약검토 요청서
- `raw/articles/oeubu_gyeyakgeomto_yoengseo_pyojoonsik.docx` (20KB) — 외부 계약검토 표준양식

### 원본 마크다운 저장 (4개)
- `raw/articles/hoiuirok_aijel_20260714.md` — 회의록 텍스트 분석
- `raw/articles/aijel_lineup_proposal_260714.md` — 라인업 제안서 텍스트 분석
- `raw/articles/weekly-strategy-2026-07-3w-raw.md` — 주간전략 텍스트 분석
- `raw/articles/peachy_business_model_summary.md` — Peachy 텍스트 분석

### 위키 페이지 업데이트 (4개)
- ✅ `concepts/aizel-meeting-2026-07-14.md` — 상세 업데이트 (65→220행): IDMO 디바이스 전략, 하이페리신 검토, 라비오 테스트, 샘플 계획, 제품 우선순위 표 추가
- ✅ `concepts/aizel-proposal-lineup-2026-07-14.md` — 상세 업데이트: 제품별 텍스처·키벤핏, 데일리 루틴, 에피탈론 펩타이드 설명
- ✅ `concepts/integrated-weekly-strategy.md` — 실제 PDF 데이터 반영: 대표 아젠다, 팀별 과제, 리스크 표, 우선순위, D+ 조기경보 원칙
- ✅ `entities/peachy.md` — 신규: Peachy 비즈니스 모델 분석 (정액제·반복매출·업셀 구조)

### 관련 DOCX 원본
- `raw/articles/aijel_gyeyakgeomto_yoengseo.docx` — 기존 aizel-contract-review-request.md 에 이미 상세 반영됨
- `raw/articles/oeubu_gyeyakgeomto_yoengseo_pyojoonsik.docx` — 표준양식 템플릿, 별도 wiki 페이지 미생성

## [2026-07-16] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-16 09:09

## [2026-07-16] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-16 09:14

## [2026-07-16] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-16 09:30

## [2026-07-16] ingest | Slack 채널 수집 + Enagic USA 패키지 업데이트

### Slack 수집 현황
- **코스메틱-본부:** 면접 일정 3건 (최미래 비대면, 안성식 대면, 남궁선 커피챗), JNJ 자석&명판 샘플 딜레이 (7/24 예상)
- **branup-design-backup:** [확정]미국-표지15300ea.ai, [확정]캐나다-표지5100ea-0714.ai 등 최종 디자인 파일 등록
- **아이젤-계약서:** 기존 분석 완료 파일 외 신규 분석 대상 없음
- **뷰티-프로젝트:** 제품 표지 이미지 JPG 파일 (텍스트 분석 불가)
- **업무에로사항:** 인쇄 검토 인원 확대 필요성 논의

### 위키 페이지 업데이트 (1개)
- ✅ `entities/enagic-usa.md` — 패키지 디자인 현황 7/15까지 업데이트 (JNJ 샘플 지연, 인쇄 검토 프로세스 강화, 최종 AI 파일 2건 등록)

## [2026-07-16] ingest | KANGEN BEAUTÉ 캐나다 라벨 분석

### 신규 원본 저장
- `raw/articles/kangen-beaute-canada-label-notice.md` — 캐나다 후면 고시사항 PDF 분석 (Timeless Radiance Collection)
- `raw/articles/branup-design-label-inspection-summary.md` — 미국/캐나다 표지 검수 PDF 요약

### 위키 페이지 업데이트 (1개)
- ✅ `entities/enagic-usa.md` — KANGEN BEAUTÉ Timeless Radiance Collection 3-Step 제품 정보 추가 (PDRN, PLLA, Milk/Salmon Exosomes 등)

### 미처리 파일
- `브랜업-미국-표지-검수.pdf` — 이미지 PDF (1p), "변경 사항: 동박 아래 글자 추가" 단일 문장만 존재
- `브랜업-캐나다-표지-검수.pdf` — 이미지 PDF (1p), 상동
- AI/IDML/JPG 파일 다수 — 디자인 원본, 텍스트 분석 불가

## [2026-07-17] cron | 일일 배치 업데이트

### STEP 1: DB 동기화
- ✅ `concepts/project-status.md` 업데이트 — 프로젝트 6개 현황
- ✅ `concepts/task-status.md` 업데이트 — 업무 47개 현황 (46 진행중, 1 지연)
- **신규 프로젝트 감지:** 「브랜업 홈페이지 기획안 작성」(이상원·전경표, 마감 7/31, 계획)
- **신규 긴급 업무:** #242 KCL 해외인증실증지원사업 수정사업계획서 작성

### STEP 2: Slack 채널 수집 (24시간)
- **채널:** #코스메틱-본부(11개 메시지), #업무에로사항(4개), #뷰티-프로젝트(1개)
- **신규 다운로드 파일:** 없음
- **주요 인사이트:**
  - 🇺🇸 **미국 1.5만세트 용기 CAPA 병목** — 제조사 생산 라인 Full CAPA로 일시 생산 불가
  - 💼 **채용 프로세스 표준화** — 서류→1차 면접(실무)→2차 면접(임원진)→최종합격
  - 👤 **최미래 면접 확정** — 7/22(수) 10:30 비대면
  - 👤 **남궁선 커피챗** — 정식 면접 아닌 회사·역할 소통 중심
  - 🔧 **에나지크 발주 시뮬레이션 툴 기획** — 다음주 시작 (강경철+지원)
  - 👥 **고문단 방 신설 제안** — 최교수·이영진박사 포함 논의

### 위키 페이지 업데이트
- ✅ `entities/enagic-usa.md` — 용기 생산 병목(Full CAPA) 섹션 추가
- ✅ `entities/branup-org-chart.md` — 채용 프로세스 표준화, 최미래 면접 7/22 확정, 안성식·남궁선 면접 현황, 강경철 역할 업데이트
- ✅ `index.md` — Last updated 갱신

### 오류
- 없음


## [2026-07-17] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-17 05:04

## [2026-07-17] lint | Wiki 정기 린트 — 44 issues, 8 warnings 발견
- **대상:** 21개 페이지, 10개 원본 파일
- **주요 이슈:**
  - 고아 페이지 8개 (inbound 링크 없음)
  - 깨진 위키링크 5개 (`concept:` 접두사 오류, 존재하지 않는 페이지)
  - index 누락 2개 (project-status.md, task-status.md)
  - frontmatter 누락 2개 (created 필드)
  - 태그 분류 오류 22건 (dashboard, legal, government 등 taxonomy 미등록 태그)
  - 저신뢰도 페이지 1개 (branup-finance)
  - 원본 해시 불일치 5건 (raw 파일 수정됨)
- **Slack 전송:** ✅ #wiki 채널에 리포트 게시
- **권장 조치:** `concept:` 접두사 정리, `dashboard` 태그 taxonomy 추가, 고아 페이지 링크 처리

## [2026-07-18] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-18 05:05

## [2026-07-19] daily | 일일 위키 업데이트
### DB 동기화
- `concepts/project-status.md`, `concepts/task-status.md` 갱신 (branup_db_wiki_sync.py)

### Slack 수집 (10개 파일, 18.2MB)
- **코스메틱-본부:** 회의록_20260714_아이젤.docx, 아이젤 신규 라인업 제안서_260714.pptx, 통합주간전략_7월3주차.pdf, Peachy_요약.pdf
- **branup-design-backup:** 미국/캐나다 표지 검수 PDF 5종, KANGEN BEAUTÉ 카탈로그 DOCX

### Wiki 페이지 업데이트
- `concepts/aizel-meeting-2026-07-14.md` — 진행상황 갱신, 새 소스 연결
- `concepts/aizel-proposal-lineup-2026-07-14.md` — 새 소스 연결
- `entities/enagic-usa.md` — KANGEN 카탈로그 분석 추가, 디자인백업 현황
- `index.md` — 날짜 갱신
- `README.md` — 자동 갱신 (wiki_readme_generator.py)

### GitHub push
- 18개 파일 (10개 신규 + 3개 수정 + README) commit (548ba65)
- push 완료

### 오류
- 없음 (branup-전체 채널 not_in_channel은 기존 사항, 봇 미참여)

### DB 동기화 (별도 실행)
- projects + tasks 페이지 업데이트 (branup_db_wiki_sync.py)
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-19 05:02
- Telegram 리포트 전송 완료

## [2026-07-20] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-20 05:11

## [2026-07-21] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-21 06:20

## [2026-07-21] ingest | Dr.SANTE 리서치 보고서
- 출처: Slack #코스메틱-본부 (PDF: DrSANTE_리서치 보고서.pdf, 3.4MB)
- 신규 파일: raw/articles/drsante-research-2026-07-21.md
- 신규 페이지: entities/drsante.md — 에스테틱 화장품 전문 기업 (23년, 8,000 거래처)
- 갱신: index.md — 페이지수 20, Projects 섹션 분리

## [2026-07-21] restructure | Slack 채널별 지식 허브 (channels/) 도입

**변경 사유:** 직원 피드백 — 채널별로 쌓이는 지식의 아이덴티티와 맥락을 위키에서도 추적 가능해야 함.

### 신규 구조
- `channels/` 디렉토리 신설 — Slack 채널 1:1 매핑 지식 페이지

### 신규 생성 (7개 파일)
- `channels/index.md` — 채널 맵 (6개 채널, 유형별/퀵뷰 테이블)
- `channels/코스메틱-본부.md` — 화장품 본부: 제품 개발·샘플·원부자재
- `channels/아이젤-계약서.md` — 아이젤 제조위탁계약 검토 및 협상 *(delegate parallel)*
- `channels/branup-design-backup.md` — 디자인팀: AI/PDF 패키징, 인쇄 검수 *(delegate parallel)*
- `channels/뷰티-프로젝트.md` — KANGEN BEAUTÉ 제품·패키지·디자인
- `channels/업무에로사항.md` — 리스크·병목·이슈 트래킹
- `channels/브랜업-공지사항.md` — 전사 공지·회의록·정책

### SCHEMA.md 변경
- 디렉토리 레이아웃에 `channels/` 추가
- "Channel Pages" 섹션 신설 (생성 조건, 포맷, 내용 구조, 업데이트 규칙)

### 기존 페이지 채널 역링크 추가 (4개)
- `entities/enagic-usa.md` — + Source channels 표시
- `entities/branup-org-chart.md` — + Source channels 표시
- `concepts/aizel-meeting-2026-07-14.md` — + Source channels 표시
- `concepts/slack-adoption.md` — + Source channels 표시

### index.md 업데이트
- Channels 섹션 신설 (6개 채널 + 채널 맵 링크)
- 총 페이지 수: 20 → 26

## [2026-07-21] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-21 22:24

## [2026-07-22] cron | Wiki Daily Cron
- STEP 1: DB Sync — OK (project-status, task-status)
- STEP 2: Slack scan — 9 channels, 16 messages, 0 new files
- STEP 2b: Channel page updates:
  - `channels/코스메틱-본부.md` — 두코 박지 불일치, JNJ 샘플/금형 기준, 보라색 용기 디자인 컨펌, 캡 증착 일정
  - `channels/업무에로사항.md` — 두코 감리 사진 전환, 시안→샘플→양산 프로세스 경고 재강조
  - `channels/브랜업-에듀.md` — 신규 생성 (교육 채널, 비밀번호 공유)
- STEP 3: README.md — OK
- STEP 4: Git Push — OK (commit 04a521c)
- STEP 5: Telegram report — 전송 완료

## [2026-07-22] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-22 05:03

## [2026-07-22] cron | Wiki Daily Cron
- STEP 1: DB Sync - OK (project-status, task-status)
- STEP 2: Slack scan - 8 channels, 9 messages, 1 new file (encrypted PDF, text extraction skipped)
- STEP 2b: Channel updates:
  - channels/브랜업-에듀.md - 교육자료 PDF 등록 내역 추가
  - channels/코스메틱-본부.md - JNJ 샘플 진행상황 상세 보강
- STEP 3: README.md - OK
- STEP 4: Git Push - OK (commit 6b6c248)
- STEP 5: Telegram report - 전송 완료

## [2026-07-23] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-23 05:03

## [2026-07-23] cron | Wiki Daily Cron
|- STEP 1: DB Sync — OK
|- STEP 2: Slack scan — 9 ch, 178 msgs, 33 files dl
|- STEP 2b: Channel updates: 코스메틱-본부(감리완료), 업무에로사항(R&R), 뷰티-프로젝트(분할생산), 브랜업-에듀(교육4개), branup-design-backup(NEW CATALOG-C)
|- STEP 3: README.md — OK
|- STEP 4: Git Push — OK (commit 56d9e5a)
|- STEP 5: Telegram report — 전송

## [2026-07-24] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-24 05:00

## [2026-07-24] cron | Wiki Daily Cron
- STEP 1: DB Sync — OK (concepts/project-status.md, concepts/task-status.md)
- STEP 2: Slack scan — 10 ch, 5 msgs, 4 files (all PDF)
- STEP 2b: Channel updates: 코스메틱-본부(인쇄감리일정), branup-design-backup(카탈로그 재등록)
- STEP 3: README.md — OK
- 카탈로그 PDF 분석: KANGEN BEAUTE Timeless Radiance Collection (US/CA), raw/articles/kangen-beaute-catalog-2026-07-23.md
- Errors: branup-전체(not_in_channel), kcl-해외인증실증지원사업-202607(not_in_channel)

## [2026-07-24] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-24 08:48

## [2026-07-24] cron | Wiki Daily Cron (2nd run)

### STEP 1: DB Sync
- concepts/project-status.md, concepts/task-status.md 업데이트 (branup_db_wiki_sync.py)

### STEP 2: Slack 채널 수집
- 5 active channels, 13 files, 9 analyzable PDFs
- **kcl-해외인증실증지원사업-202607** — 신규 채널 진입 (이전 not_in_channel 해소)
  - 수정사업계획서, 컨설팅 요청서, SGS 시나리오, 대면평가 발표자료, Q&A 대본 (5종 PDF 다운로드·분석 완료)
- **branup-전체** — 신규 채널 진입, 뷰티 BM 채용공고 등록 (원티드/잡플래닛/데모데이)
- 코스메틱-본부·branup-design-backup: 카탈로그 PDF 중복 (기 분석 완료, skip)

### STEP 2b: 채널 페이지 업데이트
- channels/kcl-해외인증실증지원사업-202607.md — **신규 생성** (KCL 지원사업 전용 채널)
- channels/branup-전체.md — **신규 생성** (전사 채용 공고 채널)
- channels/index.md — 채널 7→9개 갱신, kcl/branup-전체 추가

### 신규 Wiki 페이지
- concepts/kcl-overseas-certification-2026.md — KCL 해외인증실증지원사업 (2026) 상세
  - 사업개요, SGS 시험 시나리오 (총 69,052,500원), 3개 카테고리 5종 시험, KPI, 발표자료·Q&A
  - 출처: 5종 PDF 원본 및 raw/articles/

### 신규 원본 파일
- raw/articles/kcl-branup-plan-202607.md
- raw/articles/kcl-consulting-summary-202607.md
- raw/articles/kcl-sgs-scenario-20260722.md
- raw/articles/kcl-presentation-202607.md
- raw/articles/kcl-qa-script-202607.md

### navigation 업데이트
- index.md — channels 2개 + concepts 1개 추가, 총 페이지 28→31

## [2026-07-24] lint | Wiki health check
- Slack #wiki 채널에 리포트 게시 완료
- 총 123개 이슈 발견:
  - Orphan pages: 16 (채널 페이지 9개, 기타 7개) — inbound wikilinks 없음
  - Broken wikilinks: 8 (government-support-programs 3개, 아이젤-계약서 4개)
  - Index completeness: project-status, task-status 누락
  - Frontmatter: 11개 이슈 (9개 sources 누락, 2개 created 누락)
  - Unknown tags: 50개 (SCHEMA.md taxonomy 미포함)
  - Source drift: 25 raw 파일 (22 hash mismatch, 3 sha256 없음)
  - Low confidence: branup-finance
  - Single-source no confidence: 9개 페이지
  - Index mismatch: 디스크 33페이지, index.md claim 31
- Stale content: 0 (모두 90일 이내)
- Oversized pages: 0
- Contradictions: 0
- Log rotation: 326/500 (OK)

## [2026-07-25] sync | 브랜업 대시보드 DB 동기화
- projects + tasks 페이지 업데이트
- 출처: http://toffer.co.kr:8800/api
- 동기화 시각: 2026-07-25 05:01
