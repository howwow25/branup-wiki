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
