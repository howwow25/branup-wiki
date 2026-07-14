# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete

## [2026-07-15] ingest | Slack 일일 요약 (2026-07-14)
- Created: `raw/articles/slack-summary-2026-07-14.md` — 5개 채널 27건 메시지 요약
- **#코스메틱-본부:** 아이젤 미팅(오전 10시), 신규 라인업 제안서 수령, 채용 일정(김봉재 면접, 이지혜 취소, 최미래 7/24 Google Meet), 통합주간전략 자동화 논의(이상원 대표 제안, 강경철 협의)
- **#branup-design-backup:** 캐나다 패키지 디자인 확정 (인쇄·후가공 최종사항, Enagic.CA 문안, 불어 병기)
- **#뷰티-프로젝트:** 미국/캐나다 표지 수정 최종사항 이미지
- **#아이젤-계약서:** 외부 법률 검토 요청서(표준양식 + 아이젤 적용본) 공유 (이향석)
- **#업무에로사항:** 채널명 변경 논의 (문제해결방/병목해결방)
- Updated: `entities/aizel-contract.md` — 진행 경과 섹션 추가 (7/14 미팅, 신규 라인업 제안, 외부 법률 검토)
- Created: `concepts/integrated-weekly-strategy.md` — 통합주간전략 자동화 개념 페이지
- Updated: `index.md` — total 3→4 (concepts에 integrated-weekly-strategy 추가)

## [2026-07-14] update | Slack 일일 요약 (2026-07-13) — 코스메틱본부·헤르메스 채널 추가
- Updated: `raw/articles/slack-summary-2026-07-13.md` — #코스메틱-본부 (이상원 대표 Slack 피드백 8건), #헤르메스 (프로젝트 생성 요청 2건) 추가
- Created: `concepts/slack-adoption.md` — Slack 도입 및 내재화 개념 페이지
- Updated: `index.md` — concepts 섹션에 slack-adoption 추가 (total 2→3)

## [2026-07-13] create | Slack 일일 요약 (2026-07-13)
- Created: `raw/articles/slack-summary-2026-07-13.md` — #branup-design-backup (미국/캐나다 패키지 변경, 문안 수정), #코스메틱-본부 (Slack 도입 피드백)
- 미국 패키지: Enagic.US 문안 추가, 후면 고시사항 변경
- 캐나다 패키지: 불어 병기, 캐나다 법령 적용, 미국과 동일한 레이아웃
- 문안: 6/26자 양산 반영, 7/10 변호사 신규 문안 → 다음 발주분 적용
- 슬랙 도입 피드백: 이상원 대표, 슬랙 가치 체감 필요성 논의
- Slack 채널의 조항별 비교표 파일 분석하여 위키에 정리
- Created: `entities/aizel-contract.md` — 아이젤 제조위탁계약 (화장품 반제품)
- Created: `raw/articles/aizel-contract-comparison-table.md` — 원본 비교표
- 주요 변경사항 11개 조항 상세 정리 (발주, 납기, 품질, 책임, 리콜, IP, 경업금지 등)
- 2차 검토 필요 사항: 지체보상률 0.3% 협의, 제20조의2 책임한도 예외 조문 확인

## [2026-07-08] create | Wiki initialized
- Domain: 브랜업(주) — 화장품 수출 중소기업 업무 지식베이스
- Structure: SCHEMA.md, index.md, log.md, raw/, entities/, concepts/, comparisons/, queries/, _archive/
- Gateway: Telegram + Slack 동시 연결 완료
- Language: 모든 페이지 본문은 한국어로 작성 (기술용어·고유명사는 영어 원문 사용 가능)

## [2026-07-10] lint | Wiki 정기 점검 (cron)
- 검사 범위: orphan pages, broken wikilinks, index completeness, tag audit, staleness, frontmatter
- 이슈 5건 발견 (critical 1, warning 4)
- Fixed: index.md wikilink `[[아이젤 제조위탁계약]]` → `[[aizel-contract|아이젤 제조위탁계약]]` (파일명 불일치 해소)
- 미해결: raw/ sha256 placeholder, orphan page (신규 위키에서 예상됨), 연관 페이지 3건 미생성
- Slack #wiki 채널 생성 및 리포트 게시 완료
