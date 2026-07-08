# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete

## [2026-07-08] ingest | 아이젤 제조위탁계약서 비교표 (Slack #아이젤-계약서)
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
