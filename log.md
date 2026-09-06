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

## [2026-08-13] sync | 브랜업 대시보드 동기화
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

## [2026-08-13] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 75건 (branup_db_wiki_sync.py)
- Slack 스캔: 15개 채널 스캔, 신규 활동 1개 채널 (브랜업-전체)
  - 브랜업-전체: 발주서 양식 예시 공유 ([브랜업] 발주서 예시.xlsx, 2026-08-12 17:54 KST)
  - 나머지(코스메틱-본부 카톤박스, KCL PDF)는 8/12 크론에서 이미 기록 — 중복 스킵
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh)
- 북마크: 0건
- 신규 문서 파일: 1건 ([브랜업] 발주서 예시.xlsx — 브랜업 → ㈜조인앤조이 발주 양식, 텍스트 추출 성공)
- Wiki 페이지 업데이트:
  - entities/join-n-joy.md 신규 생성 (조인앤조이 포장 부자재 협력사)
  - raw/articles/join-n-joy-po-form-20260608.md 신규 생성 (발주서 내용)
  - channels/브랜업-전체.md: 발주서 양식 공유 활동 추가
  - channels/코스메틱-본부.md: 발주서 양식(전사) 활동 추가
  - projects/에나지크_발주_시뮬레이터.md: 발주서 양식 활동 추가
- 네비게이션 갱신: index.md (조인앤조이 엔터티 추가, 총 42페이지), README.md 재생성, log.md

## [2026-08-14] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 76건 동기화 완료

## [2026-08-14] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 76건 (branup_db_wiki_sync.py, +1건: 75→76)
  - ai_ax_직원_교육: "AI/AX 도입 교육" 업무 마감일 연장 (8/13 → 8/20, 담당 이향석·전경표)
  - 신규 업무 1건 (프로젝트 미지정 68→69건)
- Slack 스캔: 15개 채널 스캔, 신규 활동 1개 채널 (코스메틱-본부)
  - 코스메틱-본부: 아모레퍼시픽 토탈뷰티북 스캔파일 공유 (토탈뷰티북 1-7.zip, 2026-08-13 18:20 KST)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 최신 8/11 — 신규 없음)
- 북마크: 0건
- 신규 파일(미처리): 토탈뷰티북 1-7.zip (ZIP 스캔본 — PDF/DOCX/PPTX/XLSX 아님, 텍스트 추출 대상 아님, 활동만 기록)
- Wiki 페이지 업데이트:
  - channels/코스메틱-본부.md: 토탈뷰티북 공유 활동 추가
  - channels/index.md: 코스메틱-본부 퀵뷰 갱신, 총 채널 수 11개 정정 (10→11)
  - index.md: 브랜업-온보딩 채널 누락 보완
- 네비게이션 갱신: index.md, README.md 재생성, log.md
- 버그 수정: branup_db_wiki_sync.py `---` 구분자 중복 누적 버그 수정 (정규식이 첫 `---`에서 중단하도록 변경)
  - projects/뷰티_bm_채용_프로젝트.md·시니어_마케터_채용_프로젝트.md·에나지크_발주_시뮬레이터.md의 누적 `---` 15~17줄 → 단일 구분자로 정리

## [2026-08-14] lint | 위키 전체 린트
- 콘텐츠 페이지 46개 / raw 원본 40개 대상 린트 실행, 요약 리포트 #wiki 채널 게시 완료
- P1 깨진 위키링크 4건:
  1. concepts/government-support-programs.md → [[branup-work-dashboard]] (대상 없음)
  2. entities/join-n-joy.md → [[channels/브랜업-전체]] (실제 파일명 branup-전체.md 불일치)
  3. channels/코스메틱-본부.md → [[raw/articles/branup-packaging-spec-usa-canada-20260728.pdf]] (실제 .md)
  4. raw/articles/weekly-strategy-2026-07-3w.md → [[통합주간전략 자동화]] (원본 불변, 수정 불가)
- P1 중복 프로젝트 페이지 5건: entities/project-*.md (구버전 스냅샷, projects/ 정식판과 중복) → 아카이브 대상
- P1 미아 페이지 4건: concepts/task-status.md(완전 무링크), concepts/tsonax.md, channels/브랜업-에듀.md, channels/브랜업-온보딩.md(인덱스에서만 링크)
- P2 index 누락 4건: entities/브랜업-신입직원-온보딩-매뉴얼.md, concepts/project-status.md, concepts/task-status.md, concepts/브랜업-대시보드-현황.md (헤더 카운트 42≠46)
- P2 프론트매터 누락 15건 (채널 페이지 12건 sources 누락 + 온보딩매뉴얼/대시보드현황/프로젝트현황/업무현황 created·updated·sources)
- P3 태그 스프롤: 비수용 태그 28종 30페이지 (dashboard·department·company·legal·government 등 + 한글 상태태그 계획/진행/완료/보류)
- P3 raw sha256 무결성: 40개 중 1개만 정상 (실제 미스매치 15, placeholder 18, 누락 6)
- P3 페이지 크기: entities/브랜업-신입직원-온보딩-매뉴얼.md 806줄 (분할 권장)
- 채널 커버리지: Slack 15개 중 11개 보유, 미보유 4개(헤르메스·브랜업-조직구성·브랜업-휴가·제품-기획-제작)

## [2026-08-15] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 77건 동기화 완료

## [2026-08-15] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 77건 (branup_db_wiki_sync.py, 전일 76 → +1)
  - 신규 업무(프로젝트 미지정): "태화 위험물 업체로 출고 부킹(캐나다 항공운송 화물)" — 강경철, 마감 8/18, 진행중 (8/14 14:38 등록)
  - 신규 업무(프로젝트 미지정): "아이젤에 질의서 전달" — 강경철, 마감 8/14, 진행중 (8/14 09:13 등록)
- Slack 스캔: 15개 채널 스캔, 최근 48시간 내 신규 사용자 메시지 0건
  - 코스메틱-본부 토탈뷰티북 zip(8/13 18:20) — 8/14 cron에서 이미 반영
  - wiki 채널: 봇 자체 린트 리포트(8/14 18:07) — 사용자 활동 아님
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음, DB 동기화만 반영)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-16] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 77건 동기화 완료

## [2026-08-17] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 77건 동기화 완료

## [2026-08-17] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 77건 (전일 대비 변동 없음 — 날짜만 갱신)
- Slack 스캔: 전체 채널 스캔, 최근 24시간 내 신규 사용자 메시지 0건
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건 (가장 최근 파일: 코스메틱-본부 토탈뷰티북 zip, 8/13 — 전일 반영 완료)
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음, DB 동기화만 반영)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-18] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 77건 동기화 완료

## [2026-08-18] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 77건 (전일 대비 변동 없음 — 날짜만 갱신)
- Slack 스캔: 전체 15개 채널 스캔, 최근 30시간 내 신규 사용자 메시지 0건
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건 (가장 최근 파일: 코스메틱-본부 토탈뷰티북 zip, 8/13 — 반영 완료)
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음, DB 동기화만 반영)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-19] sync | 브랜업 대시보드 동기화
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

## [2026-08-19] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 75건 (전일 77건 → 75건, -2건)
- Slack 스캔: 48h 윈도우, 신규 사용자 메시지 4건 (뷰티-프로젝트 2건, 브랜업-전체 2건 — 모두 8/18)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트:
  - channels/뷰티-프로젝트.md — 8월 발주분 사양 픽스 (오버캡 후가공, 스탭1 증정 삭제, 명판 개발, 단상자 9/15 제안)
  - channels/branup-전체.md — 정육공방 발주 진행 + 브랜드 소개서 일정
  - projects/에나지크_발주_시뮬레이터.md — 발주 사양 픽스 활동 추가
  - projects/소라살롱_공구_프로젝트.md — 정육공방 발주 활동 추가
  - entities/enagic-usa.md — 8월 발주분 사양 픽스 반영
  - channels/index.md — 퀵뷰 갱신
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-20] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 68건 동기화 완료

## [2026-08-20] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 68건 (전일 75건 → 68건, -7건)
- Slack 스캔: 48h 윈도우, 신규 사용자 메시지 1건 (코스메틱-본부 1건 — 8/19)
- Canvas 이벤트: 9건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트:
  - channels/코스메틱-본부.md — 샘플 구매 요청 2종 (마움 스킨 부스팅 크림 50g, 에스트라 아토베리어 365 캡슐 토너) 벤치마킹용
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-21] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 68건 동기화 완료

## [2026-08-21] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 68건 (전일 68건 → 68건, 변화 없음)
- Slack 스캔: 48h 윈도우, 신규 비즈니스 메시지 1건 (코스메틱-본부 1건 — 8/20 강경철 라비오 제안서)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 2건 (라비오 COOLIN stay 제안서 PDF 23p + 브랜업 제안 제형 5종 ZIP)
- Wiki 페이지 업데이트:
  - entities/labio.md — 신규 생성. 화장품 원료 공급사 (주소·연락처·아이젤 3% 원료 공급)
  - concepts/coolin-stay-쿨링원료.md — 신규 생성. COOLIN stay 쿨링·항열노화 원료 (INCI·듀얼 TRP 메커니즘·시험 데이터)
  - channels/코스메틱-본부.md — 8/20 라비오 제안서 공유 활동 추가, related_entities/concepts 갱신
- 네비게이션 갱신: index.md (2페이지 추가, 42→44), README.md 재생성, log.md

## [2026-08-21] lint | Wiki 상태 점검
- 콘텐츠 페이지 48개, 전체 .md 95개
- 깨진 위키링크 3건: 코스메틱-본부(.pdf 확장자), government-support-programs(branup-work-dashboard), join-n-joy(channels/브랜업-전체 → 실제 branup-전체)
- 고아 페이지 9건: entities/project-* 5개(프로젝트 중복 오배치), 브랜업-에듀·브랜업-온보딩·task-status·tsonax
- 인덱스 누락 4건: project-status, task-status, 브랜업-대시보드-현황, 브랜업-신입직원-온보딩-매뉴얼
- 유령 링크 0건, stale 0건
- 미분류 태그 27개 (프로젝트 상태 계획/진행/보류/완료, company/people/org, dashboard/rnd/legal 등) → SCHEMA.md taxonomy 갱신 필요
- 프론트매터 누락 4건 (created 등)
- 과대 페이지 1건: entities/브랜업-신입직원-온보딩-매뉴얼 (806줄)
- raw sha256 33건 불일치 (16자리 절단·placeholder) — drift 감지 불능
- 결과 #wiki 채널에 리포트 게시 완료

## [2026-08-22] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 67건 동기화 완료

## [2026-08-22] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 67건 (전일 68건 → 67건, -1건)
- Slack 스캔: 72h 윈도우, 신규 비즈니스 메시지 0건 (8/19 샘플 구매 요청·8/20 라비오 제안서는 전일 처리 완료)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 신규 콘텐츠 없음 (DB 날짜 갱신만)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-23] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 68건 동기화 완료

## [2026-08-23] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 68건 (전일 67건 → 68건, +1건)
- Slack 스캔: 72h 윈도우, 신규 비즈니스 메시지 0건 (8/20 라비오 제안서·8/21 lint 리포트는 전일 처리 완료)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 신규 콘텐츠 없음 (DB 날짜 갱신 + 업무 1건 증가 반영)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-24] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 71건 동기화 완료

## [2026-08-24] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 71건 (전일 68건 → 71건, +3건)
- 신규 업무(8/23): TSonaX 체결 틱 유실 로그 분석·키움 xray 화면, 법인세 시뮬레이션 절세, 세무현명 자문계약, 아이젤 계약서 조영길이사 사전조율(지연), 미국 고객 만족도 조사, AI/AX 교육
- Slack 스캔: 15개 채널 스캔, 최근 72h 내 신규 비즈니스 메시지 0건 (wiki 채널 8/21 lint 리포트는 전일 처리 완료)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: concepts/tsonax.md 최근 작업 추가 (TSonaX 마일스톤#2 신규 업무 2건)
- 네비게이션 갱신: channels/index.md 날짜 갱신, README.md 재생성, log.md

## [2026-08-25] sync | 브랜업 대시보드 동기화
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
- 프로젝트 9개, 업무 73건 동기화 완료

## [2026-08-25] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 9개, 업무 73건 (전일 71건 → 73건, +2건)
- 신규 업무(8/24): [에나지크] 샘플/비매품 용기 문안 및 패키지 주의사항 리서치(강경철), 수축필름 업체 입고 일정 전달(강경철), 수민님 제품 받아서 바로 퀵(강경철)
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 1건 — 코스메틱-본부(노수민, 8/24) 에나지크 샘플·비매품 미팅 결과
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 최신 8/10-11 — 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트:
  - channels/코스메틱-본부.md — 최근 활동 + 주요 의사결정 추가 (에나지크 샘플·비매품)
  - projects/에나지크_발주_시뮬레이터.md — 최근 활동 추가
  - entities/enagic-usa.md — 샘플·비매품 미팅 섹션 추가
- 네비게이션 갱신: index.md 날짜 갱신, README.md 재생성, log.md

## [2026-08-26] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 10개, 업무 78건 동기화 완료

## [2026-08-26] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 10개 (+1), 업무 78건 (+5) — branup_db_wiki_sync.py
- 신규 프로젝트: 홈페이지 Hero 페이지 에셋 기획 및 제작 (담당 미지정, 종료 2026-09-02)
- 신규 업무(8/25): 소라살롱 협업 판매 raw 데이터시트 제작(김봉재), 미국 부자재·벌크 입고 위치 확인(강경철), svc 입주 방법 탐색 및 기획(김봉재), 정육공방 스스 셋팅 및 디자인 에셋 기획(김봉재), 칸겐 인스타 2차 브랜드 필름 기획·제작 총괄(김봉재), 보드 부착 고급 바퀴 찾기(강경철)
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 0건 (코스메틱-본부 8/24 메시지는 전일 처리 완료)
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 최신 8/10-11 — 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: index.md 프로젝트 섹션 정비 — 10개 프로젝트를 정확한 `projects/` slug로 교체 + 신규 홈페이지 Hero 프로젝트 추가 (기존 `project-` 접두사 깨진 링크 5건 수정)
- 네비게이션 갱신: index.md, README.md 재생성, log.md

## [2026-08-27] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 81건 동기화 완료

## [2026-08-27] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개 (+3), 업무 81건 (+3) — branup_db_wiki_sync.py
- 신규 프로젝트(3): 마케팅팀 노션 시범운영 & 협업플로우 셋팅(김봉재, ~9/30), 마케팅팀 노션 협업 스페이스 구축(미지정, ~9/4), 노션 워크스페이스 셋팅 & 마케팅팀 시범운영(미지정, ~10/21)
- 신규 업무(8/26): SVC 확장형 모집공고참여(김봉재,이향석), 검수하러 갈 때 준비물(강경철), 캐나다 해상운송 PACKING LIST·SHIPPING MARK 전달(강경철), 포장사양서 수정요청서 전달(강경철)
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 0건
- Canvas 이벤트: 12건 (모두 USLACKBOT auto-refresh, 최신 8/10-11 — 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: index.md 프로젝트 섹션에 신규 노션 프로젝트 3건 추가 (sync 스크립트 regex가 "## Projects (프로젝트)" 헤더를 매치 못해 누락된 것 수동 보완), Total pages 45→48
- 네비게이션 갱신: index.md, README.md 재생성, log.md

## [2026-08-28] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 82건 동기화 완료

## [2026-08-28] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 82건 (+1) — branup_db_wiki_sync.py
- 신규 업무(8/27): 브랜업 재무상태 실시간 관리 방안 연구(이상원·이향석, 높음), 셀러루트 보관+운송비 결제(강경철), 카톤박스 견적 요청(강경철), 충진처 카톤박스 포장 예정일 파악(강경철), 네이버스토어 위임장 재작성(강경철), 완제품 시험성적서 아이젤 문의(강경철)
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (design-backup 12, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh, 신규 1건 8/27)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: concepts/branup-finance.md — 재무상태 실시간 관리 방안 연구 업무 등록 반영
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-28] lint | Wiki 전체 린트 (orphan·broken link·index·tag audit)
- 6 orphan (중복본 5건 제외 시 실질 1건: concepts/task-status.md)
- 3 broken wikilink (코스메틱-본부 .pdf, join-n-joy 브랜업-전체, gov-support branup-work-dashboard)
- 9 index 누락 (중복본 5건 제외 실질 4건: project-status·task-status·브랜업-대시보드-현황·온보딩매뉴얼)
- 8 frontmatter 누락 (created/updated/tags)
- 58 tag 불일치 (SCHEMA taxonomy 미포함 태그: design·government·legal·dashboard·계획/진행/완료 등)
- 1 대형 페이지 (브랜업-신입직원-온보딩-매뉴얼 805줄)
- 1 confidence:low (branup-finance), 0 stale, 0 contested
- 중복 발견: entities/project-*.md 5건 = projects/*.md 낡은 중복 (type:entity, 7/15) → _archive/ 이동 권장
- 결과 #wiki 채널에 리포트 전송 완료 (ts 1787907862.246699)

## [2026-08-29] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 80건 동기화 완료

## [2026-08-29] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 80건 (-2) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 0건 (72h 윈도우)
- Canvas 이벤트: 13건 (design-backup 12, 아이젤-계약서 1 — 모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (주말, 신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성, log.md

## [2026-08-30] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 80건 동기화 완료

## [2026-08-31] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 78건 동기화 완료

## [2026-08-31] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 78건 (-2) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 2건 (코스메틱-본부: 콜마 샘플 팔로우업 + 샘플 사양 변경, 노수민)
- Canvas 이벤트: 13건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: channels/코스메틱-본부.md (최근 활동 + 주요 의사결정), entities/한국콜마.md 신규 생성
- 네비게이션 갱신: index.md (+1 엔터티, 49페이지), channels/index.md (퀵뷰 갱신), README.md 재생성

## [2026-09-01] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 80건 동기화 완료

## [2026-09-01] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 80건 (+2) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 신규 비즈니스 메시지 2건 (코스메틱-본부: 에나직 발주 QC 프로세스 점검 + 지원 패키지 불량/디자인 변경, 노수민)
- Canvas 이벤트: 13건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: channels/코스메틱-본부.md (최근 활동 + 주요 의사결정), projects/에나지크_발주_시뮬레이터.md (최근 활동), entities/enagic-usa.md (QC 일정 누락)
- 네비게이션 갱신: index.md (날짜 갱신), README.md 재생성

## [2026-09-02] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 77건 동기화 완료

## [2026-09-02] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 77건 (-3) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 스캔, 최근 24시간 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성

## [2026-09-03] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 81건 동기화 완료

## [2026-09-03] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 81건 (+4) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 스캔, 최근 24시간 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성

## [2026-09-04] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 81건 동기화 완료

## [2026-09-04] lint | 위키 헬스체크
- 깨진 링크 8건, 고아 페이지 6건, 인덱스 미등록 10건
- 미등록 태그 28종 (taxonomy 갱신 필요), 프론트매터 누락 6건
- 과대 페이지 2건 (온보딩-매뉴얼 806줄), raw sha256 무결성 이슈 34건
- 리포트 #wiki 채널 게시 완료 (ts 1788512627.908959)

## [2026-09-05] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 85건 동기화 완료

## [2026-09-05] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (+4) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 15개 스캔, 최근 24시간 신규 비즈니스 메시지 0건 (유일한 메시지는 #wiki 린트 리포트 자체 게시)
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- 신규 업무 5건 확인 (2026-09-04 생성): Intertec 견적서, 명판 가격 녹일 방안, 아웃패드 어디 업체로 보낼지, 일부 물량 월요일 오후 입고 가능 여부 확인, 아이젤 가격 협상 기초안
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성

## [2026-09-06] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 85건 동기화 완료

## [2026-09-06] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (변동 없음) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 15개 스캔, 최근 48시간 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 신규 없음 — 최신 8/27)
- 북마크: 0건
- 신규 파일: 0건
- 신규 업무: 0건
- Wiki 페이지 업데이트: 없음 (주말, 신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성

## [2026-09-07] sync | 브랜업 대시보드 동기화
- projects/브랜업_대시보드_개발.md
- projects/시니어_마케터_채용_프로젝트.md
- projects/소라살롱_공구_프로젝트.md
- projects/브랜업_홈페이지_기획안_작성.md
- projects/ai_ax_직원_교육.md
- projects/에나지크_발주_시뮬레이터.md
- projects/뷰티_bm_채용_프로젝트.md
- projects/kcl_sgs_안정성검사_사업_실행_12_31.md
- projects/칸겐뷰티_sns_운영.md
- projects/마케팅팀_노션_협업_스페이스_구축.md
- projects/노션_워크스페이스_셋팅___마케팅팀_시범운영.md
- projects/홈페이지_hero_페이지_에셋_기획_및_제작.md
- projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md
- projects/index.md
- concepts/브랜업-대시보드-현황.md
- index.md
- 프로젝트 13개, 업무 86건 동기화 완료

## [2026-09-07] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 86건 (+1 신규 업무, 진행중·프로젝트 미지정) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 14개 스캔, 최근 30시간 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성
