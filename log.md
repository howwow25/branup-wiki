# Wiki Log

> Chronological record of all wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete
> When this file exceeds 500 entries, rotate: rename to log-YYYY.md, start fresh.

## [2026-08-05] rotate | Log rotation
- Previous log (663 lines, 2026-07-15 ~ 2026-08-04) archived to `log-2026.md`

## [2026-08-05] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 61건 (branup_db_wiki_sync.py)
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 메시지 0건
- Canvas 이벤트: 9건 (branup-design-backup 8, 브랜업-계약서 1 — 모두 USLACKBOT auto-refresh, 최신 7/28-29)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 활동 없음)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성, log rotation

## [2026-08-06] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 61건 동기화 완료

## [2026-08-06] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 61건 (branup_db_wiki_sync.py)
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 메시지 0건
- Canvas 이벤트: 9건 (branup-design-backup 8, 브랜업-계약서 1 — 모두 USLACKBOT auto-refresh, 최신 7/28-29)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 활동 없음)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성

## [2026-08-07] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 62건 (branup_db_wiki_sync.py, +1건 증가)
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 메시지 0건
- Canvas 이벤트: 9건 (branup-design-backup 8, 브랜업-계약서 1 — 모두 USLACKBOT auto-refresh, 최신 7/28-29)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (3일 연속 Slack 활동 없음)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성

## [2026-08-07] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 62건 동기화 완료

## [2026-08-07] lint | Wiki health check
- Orphans: 7 (5 project duplicates in entities/, concepts/task-status, concepts/tsonax)
- Broken wikilinks: 12 — fixed 7 (trailing backslashes in channels/아이젤-계약서, concept: prefix in export-voucher.government-support-programs). Remaining 5: raw/ article wikilinks with .md extension in channels (known pattern)
- Missing from index: 9 (channels/브랜업-온보딩, concepts/project-status, concepts/task-status, concepts/브랜업-대시보드-현황, entities/브랜업-신입직원-온보딩-매뉴얼, 4개 projects/)
- Frontmatter issues: 5 (missing 'created' or 'updated' fields in 4 pages)
- Unknown tags: 29 tags used but not in SCHEMA taxonomy (channel, design, education, hr, onboarding, rnd, task 등)
- Oversized: entities/브랜업-신입직원-온보딩-매뉴얼.md (806 lines)
- Stale: none
- Total: 63 issues. Posted to #wiki Slack channel.


## [2026-08-08] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 62건 동기화 완료

## [2026-08-08] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 62건 (branup_db_wiki_sync.py)
- Slack 스캔: 13개 채널 스캔, 최근 24시간 내 비즈니스 메시지 0건 (wiki 채널 lint 리포트만)
- Canvas 이벤트: 9건 (branup-design-backup 8, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh, 4일 연속 동일)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (4일 연속 Slack 활동 없음, 토요일)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성

## [2026-08-09] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 62건 동기화 완료

## [2026-08-09] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 62건 (branup_db_wiki_sync.py)
- Slack 스캔: 15개 채널 스캔, 최근 168시간 내 비즈니스 메시지 0건 (wiki 채널 린트 리포트만 — 8/7 게시)
- Canvas 이벤트: 9건 (branup-design-backup 8, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh, 5일 연속 동일)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (5일 연속 Slack 활동 없음, 일요일)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성 (85개 페이지)

## [2026-08-10] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 63건 동기화 완료

## [2026-08-10] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 63건 (branup_db_wiki_sync.py, +1건: 62→63)
- Slack 스캔: 15개 채널 스캔, 최근 168시간 내 비즈니스 메시지 0건
- Canvas 이벤트: 10건 (branup-design-backup 9, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh, 6일 연속 동일)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (6일 연속 Slack 활동 없음, 월요일)
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성 (85개 페이지)

## [2026-08-11] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 75건 동기화 완료

## [2026-08-11] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 75건 (branup_db_wiki_sync.py, +12건: 63→75)
- Slack 스캔: 15개 채널 스캔, 2개 채널 활동 감지
  - 브랜업-전체: 이미지 파일 4건 게시 (other-*.jpg, 텍스트 없음)
  - design-backup: USLACKBOT canvas auto-refresh 2건
- Canvas 이벤트: 11건 (design-backup 10, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: channels/branup-전체.md updated date, channels/branup-design-backup.md updated date, README.md 재생성 (85개 페이지)
- 대시보드 신규 업무 12건 반영 완료 (projects/ 디렉토리 자동 동기화)

## [2026-08-12] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 9개, 업무 74건 동기화 완료

## [2026-08-12] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 74건 (branup_db_wiki_sync.py, -1건: 75→74)
- Slack 스캔: 15개 채널 스캔, 3개 채널 활동 감지
  - 코스메틱-본부: 카톤박스 Ver.2 도면 공유 (JPG 7.6MB, 원단 KLB/3SK/D/W)
  - kcl-해외인증실증지원사업-202607: KCL 최종협약체결서류 PDF 등록 (11MB, 24페이지 스캔본, 2026-08-10 생성)
  - design-backup: USLACKBOT canvas auto-refresh 12건 (8/5~8/12, 7일 연속)
- Canvas 이벤트: 12건 (design-backup 11, 브랜업-계약서 1 — 모두 USLACKBOT auto-refresh)
- 북마크: 0건
- 신규 문서 파일: 1건 (KCL최종협약체결서류.pdf, 이미지 전용 PDF — 텍스트 추출 불가)
- Wiki 페이지 업데이트:
  - channels/kcl-해외인증실증지원사업-202607.md: KCL 협약서 등록 활동 추가
  - channels/코스메틱-본부.md: 카톤박스 Ver.2 도면 활동 추가
  - channels/branup-design-backup.md: Canvas 주간 활동 요약 추가
  - projects/kcl_sgs_안정성검사_사업_실행_12_31.md: KCL 협약 체결 단계 진입 기록
- 네비게이션 갱신: index.md, README.md 재생성, log.md
