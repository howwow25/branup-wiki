# 📚 브랜업 위키 (Branup Wiki)

> 브랜업(주)의 업무 지식베이스 — Hermes AI 에이전트가 Karpathy LLM Wiki 패턴으로 운영합니다.
> Obsidian Vault 호환. Slack/Telegram 게이트웨이 연동 + 브랜업 대시보드 DB 자동 동기화.

---

### 📌 엔터티 (Entities)

- **[아이젤 계약검토 요청서 (2026-07-14)](entities/aizel-contract-review-request.md)**
- **[아이젤 제조위탁계약 (화장품 반제품)](entities/aizel-contract.md)**
- **[브랜업 조직도 (Branup Org Chart)](entities/branup-org-chart.md)**
- **[Dr.SANTE (닥터상떼)](entities/drsante.md)**
- **[Enagic USA — 미국 에나지크](entities/enagic-usa.md)**
- **[Peachy — 미국 보톡스 전문 체인점](entities/peachy.md)**
- **[AI/AX 직원 교육](entities/project-ai_ax_직원_교육.md)**
- **[브랜업 대시보드 개발](entities/project-브랜업_대시보드_개발.md)**
- **[소라살롱 공구 프로젝트](entities/project-소라살롱_공구_프로젝트.md)**
- **[시니어 마케터 채용 프로젝트](entities/project-시니어_마케터_채용_프로젝트.md)**
- **[에나지크 발주 시뮬레이터](entities/project-에나지크_발주_시뮬레이터.md)**

### 📌 채널 (Channels) — Slack 채널별 지식 허브

- **[branup-design-backup](channels/branup-design-backup.md)**
- **[채널 맵](channels/index.md)** — 전체 채널 목록 + 설명 + 퀵뷰
- **[뷰티-프로젝트](channels/뷰티-프로젝트.md)**
- **[브랜업-공지사항](channels/브랜업-공지사항.md)**
- **[브랜업-에듀](channels/브랜업-에듀.md)**
- **[아이젤-계약서](channels/아이젤-계약서.md)**
- **[업무에로사항](channels/업무에로사항.md)**
- **[코스메틱-본부](channels/코스메틱-본부.md)**

### 📌 개념 (Concepts)

- **[아이젤 미팅 회의록 (2026-07-14) — 상세](concepts/aizel-meeting-2026-07-14.md)**
- **[아이젤 신규 라인업 제안서 (2026-07-14) — 상세](concepts/aizel-proposal-lineup-2026-07-14.md)**
- **[브랜업 재무현황](concepts/branup-finance.md)**
- **[수출바우처 (Export Voucher)](concepts/export-voucher.md)**
- **[정부지원사업 모니터링](concepts/government-support-programs.md)**
- **[통합주간전략 (7월 3주차, 2026-07-14)](concepts/integrated-weekly-strategy.md)**
- **[PL보험 (Product Liability Insurance)](concepts/product-liability-insurance.md)**
- **[브랜업 대시보드 프로젝트 현황](concepts/project-status.md)**
- **[Slack 도입 및 내재화](concepts/slack-adoption.md)**
- **[브랜업 대시보드 업무 현황](concepts/task-status.md)**
- **[TSonaX — 실시간 차트 분석 시스템](concepts/tsonax.md)**

### 📌 비교 분석 (Comparisons)

*(비어 있음 — 계약서 조항 비교는 entity 페이지 내에 포함)*

### 📌 저장 질의 (Queries)

*(비어 있음)*

### 📌 일일 Slack 요약 (Daily Summaries)

- [2026-07-14 Slack 요약](raw/articles/slack-summary-2026-07-14.md)
- [2026-07-13 Slack 요약](raw/articles/slack-summary-2026-07-13.md)

---

## 🤖 업데이트 방식

| 정보공급처 | 방식 | 주기 |
|-----------|------|:----:|
| **Slack 채널** | 채널 대화 + 첨부 문서(DOCX/PPTX/PDF) 분석 → Wiki 저장 | 매일 05:00 KST |
| **Slack 채널 (채널 페이지)** | 각 채널 최근 활동 스캔 → `channels/채널명.md` 갱신 | 매일 05:00 KST |
| **Telegram** | 게이트웨이 메시지 감지 → Wiki 업데이트 | 실시간 |
| **브랜업 대시보드** | API(`toffer.co.kr:8800`) → projects/tasks 동기화 | 매일 05:00 KST |

### 실행 순서 (매일 05:00 크론)
1. `branup_db_wiki_sync.py` — 대시보드 DB 프로젝트/업무 데이터 → 위키
2. Slack API — 모든 채널 전날 대화 + 첨부파일 분석
3. **채널 페이지 갱신** — 각 `channels/채널명.md`의 최근 활동 요약 + 의사결정 업데이트
4. `wiki_readme_generator.py` — README.md 자동 갱신
5. GitHub 자동 push

### 정기 점검
- **매주 금요일 18:00** — 위키 lint (고아 페이지, 깨진 링크, 만료 콘텐츠)

---

*자동 생성: 2026-07-21 | 총 40페이지 (README.md·SCHEMA.md·log.md 제외)*