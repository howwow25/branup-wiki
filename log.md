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

## [2026-09-08] sync | 브랜업 대시보드 동기화
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

## [2026-09-08] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (전일 86건 → -1건, 진행중·프로젝트 미지정 1건 감소) — branup_db_wiki_sync.py
- Slack 스캔: 전체 비보관 채널 스캔, 최근 72시간 신규 비즈니스 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음, DB 변경은 업무 수 -1건뿐)
- 네비게이션 갱신: README.md 재생성

## [2026-09-09] sync | 브랜업 대시보드 동기화
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

## [2026-09-09] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (전일 85건 → 변동 없음) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 1건
- 신규 메시지: design-backup — 노수민(SueminNoh) "15ml 샘플 용기" + image.png (콜마 15ml 샘플 용기 디자인 이미지 공유)
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 최신 08-27, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건 (문서 PDF/DOCX/PPTX/XLSX 없음, image.png만)
- Wiki 페이지 업데이트: channels/branup-design-backup.md (15ml 샘플 용기 디자인 등록), entities/한국콜마.md (용기 디자인 진행 노트)
- 네비게이션 갱신: README.md 재생성

## [2026-09-10] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 87건 동기화 완료

## [2026-09-10] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 87건 (전일 85건 → +2건, 프로젝트 미지정 진행중 신규 2건) — branup_db_wiki_sync.py
- Slack 스캔: 13개 채널 스캔, 최근 24시간 내 신규 메시지 0건
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated auto-refresh, 최신 08-27, 신규 없음)
- 북마크: 0건
- 신규 파일: 0건 (문서 PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 업데이트: 없음 (신규 Slack 활동 없음)
- 네비게이션 갱신: README.md 재생성

## [2026-09-11] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 90건 동기화 완료

## [2026-09-11] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 90건 (전일 87건 → +3건) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 4건
- 신규 메시지:
  - 뷰티-프로젝트 — Ashton "260910 줄리어스 대표님 미팅 정리" (에나지크 글로벌 확장 전략·가격 마진·프로그램 구조·생산물류 협업 요청) + "캐나다 패키지 문안 Enagic.CAN→ENAGIC.CA"
  - 코스메틱-본부 — Ashton "미국 2~3차 파일럿 정리" (확정 13,417세트 9/19 부산, 세트박스 불량 1,874ea/12.25% 유형별 정리)
  - design-backup — 디자인팀 괄사 목업 3D 파일 등록 (KANGEN01.obj·KANGEN02.obj + image.png)
- Canvas 이벤트: 13건 (모두 USLACKBOT tabbed_canvas_updated, 최신 08-27, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음 — .obj 3D 모델 + image.png만)
- Wiki 페이지:
  - 신규: raw/transcripts/줄리어스-대표-미팅-20260910.md, concepts/줄리어스-대표-미팅-20260910.md
  - 갱신: channels/뷰티-프로젝트.md, channels/코스메틱-본부.md, channels/branup-design-backup.md, entities/enagic-usa.md, projects/에나지크_발주_시뮬레이터.md, index.md (총 50페이지)
- 네비게이션 갱신: README.md 재생성

## [2026-09-11] lint | Wiki health-check (Slack #wiki 보고)
- 깨진 링크 4건 (콘텐츠 페이지) — branup-work-dashboard 미생성, 통합주간전략 제목링크, 채널명 변경(브랜업-전체), PDF 링크
- 고립 페이지 6건 — concepts/task-status + entities/project-* 5건 (projects/로 대체된 구 미러)
- index 누락 9건, 태그 이탈 61건, 프론트매터 누락 6건, 초대형 페이지 4건, sha256 잘림(16자) 33건
- ghost 0 · stale 0 · 로그 78건(정상)
- 요약 보고: Slack #wiki 채널 게시 완료

## [2026-09-12] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-12] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일 90건 → -2건) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 1건
- 신규 메시지:
  - 코스메틱-본부 — SueminNoh "[줄리어스 대표님 9월 10 미팅] 표지 리뷰" (캐나다 카탈로그 표지 문안 Enagic.CAN → ENAGIC.CA 변경 요청)
- Canvas 이벤트: 14건 (모두 USLACKBOT tabbed_canvas_updated, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신:
  - channels/코스메틱-본부.md (표지 문안 변경 요청 + updated 09-12)
  - projects/에나지크_발주_시뮬레이터.md (📋 최근 활동 추가)
  - entities/enagic-usa.md (캐나다 표지 문안 변경 요청 + updated 09-12)
  - concepts/줄리어스-대표-미팅-20260910.md (후속 조치 + updated 09-12)
- 네비게이션 갱신: README.md 재생성

## [2026-09-13] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-13] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일 88건 → 변동 없음) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 0건
- Canvas 이벤트: 14건 (모두 USLACKBOT tabbed_canvas_updated, 최신 09-11, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신: 없음 (신규 활동 없음)
- 네비게이션 갱신: README.md 재생성 (날짜만 갱신)

## [2026-09-14] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-14] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일 88건 → 변동 없음) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 0건
- Canvas 이벤트: 14건 (모두 USLACKBOT tabbed_canvas_updated, 최신 09-11, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신: 없음 (신규 활동 없음)
- 네비게이션 갱신: README.md 재생성 (날짜만 갱신)

## [2026-09-15] sync | 브랜업 대시보드 동기화
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

## [2026-09-15] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 86건 (전일 88건 → 2건 감소) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 24시간 내 신규 비즈니스 메시지 0건
- Canvas 이벤트: 14건 (모두 USLACKBOT tabbed_canvas_updated, 최신 09-11, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신: 없음 (신규 활동 없음)
- 네비게이션 갱신: README.md 재생성 (날짜만 갱신)

## [2026-09-16] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-16] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (branup_db_wiki_sync.py)
- Slack 스캔: 15개 채널 스캔, 신규 메시지 1건 (뷰티-프로젝트, 줄리어스 대표 9/16 회의 안건 09-15 23:00)
- 이전 크론(09-15)이 누락한 09-14 22:11·22:33 줄리어스 대표 메시지 2건(파손 168개 상세·7개 사항 정리)도 함께 수집
- Canvas 이벤트: 14건 (모두 USLACKBOT tabbed_canvas_updated, 신규 없음)
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- 신규 raw: raw/transcripts/줄리어스-9월16일-회의안건-20260916.md
- Wiki 페이지 갱신:
  - channels/뷰티-프로젝트.md — 최근 활동(9/16 회의 안건·파손 168개·7개 사항), 주요 의사결정(FOC→FCA 정정)
  - entities/enagic-usa.md — 계약 조건 정정(FCA)·사전 논의·9/16 회의 안건 섹션 추가
  - concepts/줄리어스-대표-미팅-20260910.md — 후속 조치(2026-09-16) 추가
  - projects/에나지크_발주_시뮬레이터.md — 최근 활동(2026-09-15) 2건 추가
- 네비게이션 갱신: README.md 재생성

## [2026-09-17] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-18] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-18] lint | Wiki 정기 린트 (주간 헬스체크)
- 스캔: 콘텐츠 페이지 54개 (entities 15·concepts 15·channels 11·projects 13 + index 2), raw 소스 42개
- 깨진 위키링크 2건 → **수정 완료** (7월부터 반복 보고 항목)
  - `entities/join-n-joy`: `[[channels/브랜업-전체]]` → `[[channels/branup-전체|브랜업-전체]]` (파일명은 branup-전체)
  - `concepts/government-support-programs`: `[[branup-work-dashboard]]`(미존재) → `[[concepts/브랜업-대시보드-현황]]`
  - 두 페이지 `updated:` 2026-09-18로 갱신
- 고아 페이지 6건: `concepts/task-status`, `concepts/project-status`, `entities/project-*` 5건 (구 자동생성 미러, `projects/`가 대체) → `_archive/` 이동 권장
- index.md 미등록 9건 (고아 7건 + `entities/브랜업-신입직원-온보딩-매뉴얼` + `concepts/브랜업-대시보드-현황`), ghost 0건
  - 헤더 `Total pages: 50` vs 실제 콘텐츠 54개(등재 46건) — 정리 후 재계산 필요
- 태그 이탈 28종: 계획(9)·dashboard(8)·legal(4)·government(4)·rnd(4)·진행·완료·보류 등 → SCHEMA.md taxonomy 등재 또는 frontmatter `status:` 분리 권장
- 프론트매터 누락 9건: created 5건, updated/tags 1건, frontmatter 없음 1건(`channels/index`)
- 과대 페이지 2건: `entities/브랜업-신입직원-온보딩-매뉴얼` 777줄(분할 권장), `channels/코스메틱-본부` 221줄
- raw sha256 무결성: 64자 해시 보유 18건 중 3건 일치, 18건은 placeholder(`slack-advisory`·`<computed_on_ingest>`·`encrypted`) → 실제 드리프트가 아닌 해시 산출 규칙 불일치로 판단
- 정상: stale 0건(>90일), contested 0건, confidence low 1건(`concepts/branup-finance`), log 92건/1267줄(임계 미달)
- 리포트 #wiki 채널 게시 완료 (ts 1789722270.972339)

## [2026-09-18] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일과 동일) — branup_db_wiki_sync.py
- Slack 스캔: 15개 채널 스캔, 최근 72시간 내 신규 비즈니스 메시지 0건
  - 뷰티-프로젝트 09-15 23:00 메시지는 09-16 크론에서 이미 수집 완료
  - 헤르메스 채널: 게이트웨이 재시작 알림 3건 (봇 상태 메시지, 비업무)
- Canvas 이벤트: 1건 (아이젤-계약서, USLACKBOT tabbed_canvas_updated, 07-28 — 기존 보고분과 동일)
- 북마크: 0건
- 신규 문서 파일: 0건
- Wiki 페이지 갱신: 없음 (신규 활동 없음)
- 네비게이션 갱신: README.md 재생성 (날짜만 갱신)

## [2026-09-19] sync | 브랜업 대시보드 동기화
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

## [2026-09-19] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (전일 88건 → 3건 감소) — branup_db_wiki_sync.py
  - 지연(status=지연) 1건: "아이젤 계약서 조영길이사와 사전 조율" (담당 강경철·이상원·이향석, 마감 2026-08-27)
  - 진행중 84건 중 마감일 경과 73건 (7~8월 마감일 미갱신 항목 다수 — 대시보드 마감일 정비 필요)
  - 마감 임박(09-19~09-26) 4건: 멕시코 수출 가능여부 정리(강경철), 브랜업캠퍼스 신규 법인설립(강경철·이향석), 보드 바퀴 찾기(강경철), [Web] cosmetic-review 서비스 추가(이향석)
- Slack 스캔: 15개 채널 (비활성/미참여 제외) — 최근 96시간 신규 비즈니스 메시지 0건
  - 뷰티-프로젝트 09-15 23:00 줄리어스 대표 회의 안건 → 09-16 크론에서 기수집
  - 헤르메스: 게이트웨이 재시작 알림 3건 (09-17, 비업무)
  - wiki: 주간 린트 리포트 1건 (09-18 18:04, 자체 발행분)
  - design-backup: 최신 메시지 09-10 (괄사 목업 .obj·png) — 신규 없음
  - 제품-기획-제작(C0BL3S0BHV3): bot `not_in_channel` — 채널 초대 필요 (반복 항목)
- Canvas 이벤트: 13건 (design-backup 12·아이젤-계약서 1, 전부 USLACKBOT tabbed_canvas_updated) — 신규 없음
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신:
  - index.md — 미등재 페이지 2건 등재(entities/브랜업-신입직원-온보딩-매뉴얼, concepts/브랜업-대시보드-현황), Total pages 50 → 47(실등재 기준) 정정, "미등재(아카이브 대기)" 섹션 신설(린트 권장 7건 명시)
  - projects/ 13건 — DB sync 자동 갱신 (updated 날짜 및 업무 요약)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요): 린트 권장 고아 페이지 7건 `_archive/` 이동 — 파괴적 변경 아니나 3주째 반복 항목으로 사용자 승인 대기

## [2026-09-20] sync | 브랜업 대시보드 동기화
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

## [2026-09-20] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (전일과 동일) — branup_db_wiki_sync.py
  - 상태: 진행중 84건 · 지연 1건 ("아이젤 계약서 조영길이사와 사전 조율", 담당 강경철·이상원·이향석, 마감 2026-08-27)
  - 마감 임박(09-20~09-27) 4건 — 전부 09-25 마감: 브랜업캠퍼스 신규 법인설립(긴급, 강경철·이향석), 멕시코 수출 가능여부 정리(강경철), [Web] cosmetic-review 서비스 추가(이향석), 보드 부착용 바퀴 찾기(강경철)
  - 마감일 경과 74건 (7~8월 마감일 미갱신 항목 다수 — 대시보드 마감일 정비 필요, 전일 73건 → 1건 증가)
- Slack 스캔: 15개 채널 (아카이브 0건) — 최근 168시간(7일) 신규 비즈니스 메시지 0건
  - 뷰티-프로젝트: 최신 09-15 23:00 (줄리어스 9/16 미팅 안건) — 09-16 크론에서 기수집
  - 헤르메스: 09-17 게이트웨이 재시작 안내 3건 (비업무)
  - wiki: 09-18 18:04 주간 린트 리포트 (자체 발행분)
  - 코스메틱-본부: 대용량 응답 절단(JSONDecodeError) → curl 재조회로 검증, 최신 메시지 09-11 (신규 없음)
  - BOM 샘플 회신·콜마 샘플 사양(15ml·판매제품 확정)·미국 2~3차 파일럿(13,417세트/불량 1,874ea) 등 8~9월 논의는 기존 페이지에 반영 완료 상태
  - design-backup: 최신 09-10 (괄사 목업) — 신규 없음
  - 제품-기획-제작(C0BL3S0BHV3): bot `not_in_channel` — 채널 초대 필요 (반복 항목)
- Canvas 이벤트: 13건 (design-backup 12 · 아이젤-계약서 1, 전부 USLACKBOT tabbed_canvas_updated) — 최신 08-27 15:59 KST, 신규 없음
- 북마크: 0건
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신: projects/ 13건 · projects/index.md · concepts/브랜업-대시보드-현황.md · index.md (updated 날짜 및 업무 요약, DB sync 자동)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요): 린트 권장 고아 페이지 7건 `_archive/` 이동 — 사용자 승인 대기 (4주차)

## [2026-09-21] sync | 브랜업 대시보드 동기화
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

## [2026-09-21] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 85건 (전일과 동일) — branup_db_wiki_sync.py
  - 상태: 진행중 84건 · 지연 1건 ("아이젤 계약서 조영길이사와 사전 조율", 담당 강경철·이상원·이향석, 마감 2026-08-27)
  - 마감 임박(09-21~09-28) 4건 — 전부 09-25 마감: 브랜업캠퍼스 신규 법인설립(긴급, 강경철·이향석), 멕시코 수출 가능여부 정리(강경철), [Web] cosmetic-review 서비스 추가(이향석), 보드 부착용 바퀴 찾기(강경철)
  - 마감일 경과 74건 (전일과 동일) — 7~8월 마감일 미갱신 항목 다수, 대시보드 마감일 정비 필요
- Slack 스캔: 15개 채널 (아카이브 0건) — 최근 168시간(7일) 신규 비즈니스 메시지 0건
  - 뷰티-프로젝트: 최신 09-15 23:00 (줄리어스 9/16 미팅 안건) — 09-16 크론에서 기수집
  - 코스메틱-본부: 최신 09-11 09:21 / design-backup: 최신 09-10 09:12 — 신규 없음
  - 헤르메스: 09-17 게이트웨이 재시작 안내 3건 (비업무), wiki: 09-18 18:04 주간 린트 리포트 (자체 발행분)
  - 대용량 응답(뷰티-프로젝트·코스메틱-본부·design-backup·wiki)은 urllib IncompleteRead/JSON 절단 → curl 재조회로 검증 (아래 '수집 파이프라인 개선' 참조)
  - 제품-기획-제작(C0BL3S0BHV3): bot `not_in_channel` — 채널 초대 필요 (반복 항목)
- Canvas/북마크 스캐너 결함 수정: `~/.hermes/scripts/slack_bookmark_scanner.py`
  - 원인: urllib 대용량 응답 IncompleteRead → 실패를 조용히 삼켜 실행마다 결과가 달랐음(13건/1건/2건). 재시도 없음
  - 수정: curl 기반 호출 + 재시도(3회, 지수 백오프) + 실패 시 `errors` 필드·stderr 출력으로 표면화, `ALL_CHANNELS` 채널명 현행화(branup-전체→브랜업-전체, branup-design-backup→design-backup)
  - 검증: 3회 연속 실행 모두 canvas 14건 (design-backup 12 · 아이젤-계약서 1 · 뷰티-프로젝트 1), bookmarks 0건, errors 2건(제품-기획-제작 not_in_channel)로 동일
- Canvas 이벤트: 총 14건 — 최신 09-11 12:03 (뷰티-프로젝트 `tabbed_canvas_updated`). **직전 크론까지 13건으로 집계**되던 뷰티-프로젝트 Canvas 1건이 이번 정밀 스캔에서 확인됨 (스캐너 결함으로 누락). 09-20 05:00 이후 신규 이벤트 없음
- 북마크: 0건 (15개 채널 전부)
- 신규 문서 파일: 0건 (PDF/DOCX/PPTX/XLSX 없음)
- Wiki 페이지 갱신:
  - channels/뷰티-프로젝트.md — `slack_channel_id: C0BFE9KR23Z` 기입, 09-11 Canvas 갱신 항목 추가, updated 갱신
  - channels/코스메틱-본부.md — `slack_channel_id: C0BFSBWTNQM` 기입
  - channels/업무에로사항.md — `slack_channel_id: C0BH9QK226Q` 기입
  - channels/브랜업고문단-1억불만들기.md — `slack_channel_id: C0BXXXXXXXX` → `C0BLWN54UC8`
  - channels/브랜업-공지사항.md — ⚠️ Slack 활성 채널 목록에 미존재 경고 추가 (이름 변경/아카이브/비공개 여부 확인 필요)
  - channels/index.md — Slack 채널 ID 매핑표 신설(15개 채널 ↔ 위키 페이지), 퀵뷰 갱신, 날짜 갱신
  - projects/ 13건 · projects/index.md · concepts/브랜업-대시보드-현황.md · index.md — DB sync 자동 갱신
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 5주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기 (concepts/task-status·project-status·entities/project-* 5건)
- 미조치(신규): `channels/브랜업-공지사항.md` 의 Slack 채널 실체 확인 — 채널명 변경 추정, 대응 채널 확인 후 `status: archived` 또는 대상 갱신

## [2026-09-22] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-22] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일 85건 → +3) — branup_db_wiki_sync.py
  - 활성 업무 86건 (진행중 85 · 지연 1) — 지연: "아이젤 계약서 조영길이사와 사전 조율"(강경철·이상원·이향석, 마감 2026-08-27)
  - 마감일 경과 80건 (`due_at` < 2026-09-22, 활성 86건 기준) — 7~8월 마감일 미갱신 항목 다수, 대시보드 마감일 정비 필요
  - 마감 임박(09-22~09-29) 1건 — 09-25 "시간될 때 보드에 부착할 고급스러운 바퀴 찾기"(강경철)
  - 신규 등록(`created` ≥ 09-18) 0건
- Slack 스캔: 15개 채널 (아카이브 0, 봇 미참여 1) — 최근 168시간 신규 비즈니스 메시지 2건
  - 코스메틱-본부: 09-21 13:50 강경철 — **항공운송 단가 예상치** (캐나다-벤쿠버 50mL 11,000원·15mL 6,500원 / 미국-LA 50mL 14,000원·15mL 6,900원 per 세트)
  - design-backup: 09-21 21:39 노수민 — Photoshop 원본(PSD) 366MB 등록 (`exec-e7d57e4a….psd`, 문서 아님 → raw 수집 제외)
  - 뷰티-프로젝트: 최신 09-15 23:00(9/16 회의 안건, 기수집) / 헤르메스·wiki: 09-17~09-18 봇 알림·자체 린트 리포트(비업무)
  - 제품-기획-제작(C0BL3S0BHV3): bot `not_in_channel` — 채널 초대 필요 (반복)
  - 채널명 변경 이벤트 3건(7/27~7/29) 외 신규 없음
- Canvas 이벤트: 14건 (design-backup 12 · 브랜업-계약서 1 · 뷰티-프로젝트 1), 최신 09-11 12:03 — 신규 없음 / 북마크 0건
- Wiki 페이지 갱신:
  - channels/코스메틱-본부.md — 09-21 항공운송 단가 예상치 항목 추가, updated 갱신
  - channels/branup-design-backup.md — 09-21 PSD 등록 항목 추가, updated 갱신
  - channels/index.md — 퀵뷰 2건 갱신(코스메틱-본부·design-backup), 브랜업-공지사항 경고 재확인(09-22), 날짜 갱신
  - projects/에나지크_발주_시뮬레이터.md — 09-21 활동(항공운송 단가·선적 비용 기초자료) 추가
  - entities/enagic-usa.md — "항공운송 단가 예상치 (2026-09-21)" 섹션 추가(CA/US 단가 비교, FCA 부산 전제)
  - index.md — 총 페이지 47 → 54 정정(channels 11·entities 15·concepts 15·projects 13), 업무 88건 반영
  - projects/ 13건 · projects/index.md · concepts/브랜업-대시보드-현황.md (DB sync 자동 갱신)
- 스크립트 정비: `~/.hermes/scripts/slack_bookmark_scanner.py` ALL_CHANNELS 채널명 현행화 (`아이젤-계약서` → `브랜업-계약서`, C0BFZEZ360L)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 6주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(2주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-22 재확인 — 활성 채널 목록에 없음)

## [2026-09-23] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 89건 동기화 완료

## [2026-09-23] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 89건 (전일 88건 → +1) — branup_db_wiki_sync.py
  - 상태 분포: 진행중 88 · 지연 1 (완료 0 — `closed_at` 보유 업무 없음)
  - 지연 1건: "아이젤 계약서 조영길이사와 사전 조율"(강경철·이상원·이향석, 마감 2026-08-27, 27일 경과)
  - 마감일 경과 73건 (전일 80건 → 일부 마감일 재조정 반영)
  - 마감 임박(09-23~09-30) 11건 — 09-23 3건(`[TSonaX] 1차 배포`·`[Toffer] 익절/손절 시나리오 개선`·`공용정보 리스트업`, 모두 이향석), 09-25 5건(IR자료 디벨롭·`[Web] cosmetic-review`·멕시코 수출 검토·브랜업캠퍼스 법인설립·바퀴 찾기), 09-29 1건(오피스365 라이센스), 09-30 2건(BOM 정리·카톤 개선)
  - 신규 등록 5건 (`created_at` ≥ 09-21): 09-21 공용정보 리스트업 / `[TSonaX] 1차 배포`(13:34) / CDRI 14개국 인증 견적 확인, 09-22 ABTC 기업인여행카드 발급 / 윈도우 오피스365 라이센스 구입
  - ⚠️ 정정: 전일(09-22) 로그의 "신규 등록(created ≥ 09-18) 0건"은 오류 — 09-21 생성 3건이 누락되었음. 금일 `created_at` 기준 재집계로 확인
- Slack 스캔: 15개 채널(아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`) — **전일 크론(09-22 05:00) 이후 신규 메시지 0건**
  - 168h 창 내 6건은 모두 기수집: 코스메틱-본부(09-21 항공운송 단가), design-backup(09-21 PSD 366MB), 헤르메스(09-17 봇 알림), wiki(09-18 린트 리포트)
  - 신규 문서 파일 0건 / 채널명 변경 이벤트 신규 0건(7/27~7/29 기존 3건)
- Canvas 이벤트: 14건(design-backup 12 · 브랜업-계약서 1 · 뷰티-프로젝트 1), 최신 09-11 12:03 — 신규 없음 / 북마크 0건 (`slack_bookmark_scanner.py --all`)
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 09-23 기준 TSonaX/Toffer 활성 업무 5건 표, 1차 배포(마감 09-23)·익절/손절 시나리오 개선(09-23) 반영, 마감 경과 리스크 명시, updated 08-24 → 09-23
  - `channels/index.md` — 채널 ID 매핑표 09-23 재확인(Slack 활성 15개 전부 매핑 일치), 퀵뷰 공지사항 경고 7주차 갱신
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 7주차 갱신, updated 09-23
  - `index.md` — TSonaX 요약(1차 배포 진행·업무 5건), 대시보드 현황 업무 89건으로 갱신
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 7주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(3주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-23 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-24] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-24] cron | 일일 Slack + 대시보드 동기화
- DB sync: 프로젝트 13개, 업무 88건 (전일 89건 → −1, API 목록에서 1건 소멸) — branup_db_wiki_sync.py
  - 상태 분포: 진행중 87 · 지연 1 (완료 0 — `closed_at` 보유 업무 없음)
  - 지연 1건: "아이젤 계약서 조영길이사와 사전 조율"(강경철·이상원·이향석, 마감 2026-08-27, 28일 경과)
  - 마감 경과 75건 (전일 73건 → +2) — `due_at` ≤ 09-22 71건 + 09-23 마감 4건(공용정보 리스트업·`[TSonaX] 1차 배포`·`[Toffer] 익절/손절 시나리오 개선`·회계 현명 미지급금 출처 보완)이 경과로 편입. 전일 대비 2건은 마감일 재조정 반영
  - 마감 임박(09-25~09-30) 8건 — 09-25 5건(멕시코 수출 가능여부 정리·브랜업캠퍼스 신규 법인설립·바퀴 찾기·IR자료 디벨롭·`[Web] cosmetic-review`), 09-29 1건(윈도우 오피스365 라이센스), 09-30 2건(BOM 정리·카톤 개선)
  - 신규 등록: 09-23 "회계 현명 미지급금 출처 보완"(이향석) 1건
  - ⚠️ TSonaX 최우선 항목 `[TSonaX] 1차 배포`(마감 09-23)가 마감 경과 상태로 '진행중' — 완료/재조정 확인 필요
- Slack 스캔: 15개 채널(아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`) — **신규 메시지 4건, 전량 `코스메틱-본부`**(09-23 13:36~13:43, 노수민)
  - 09-23 13:36 `image.png`(2.6MB, image/png) — KANGEN BEAUTÉ 3-Step 세트(STEP I Luminous Peptide Elixir·STEP II Vital Rich Cream·STEP III Precision Ceramide Deep Concentrate) 네이비 트레이 삽입 상태 사진. 문서 아님 → raw 수집 제외, 비전 분석으로 내용 확인
  - 09-23 13:37 **세트 포장 세로 보관·충격 시 제품 중량 지지 불가**(2026-09-21 확인) — 정문갑 회장님 보강 작업 실행, 점검 물건 택배 발송
  - 09-23 13:43 **EU 수출 퀵 리서치 9개 항목** — 포장재 중금속 합계 100mg/kg·REACH SVHC 정보 전달 의무·PPWR 2030-01-01 등급제(A/B/C)·최소 포장·PE 계열 우선·투명 PET 본체+분리 PE·PP 캡·PETG 별도 취급·라벨/접착제 선별 방해 금지·종이상자 코팅 비추천
  - `conversations.replies`로 스레드 답글 확인 — 신규 0건 (4건이 전량)
  - 168h 창 내 나머지 6건은 기수집: 코스메틱-본부 항공운송 단가(09-21), design-backup PSD 366MB(09-21), 헤르메스 봇 알림(09-17), wiki 린트 리포트(09-18)
  - 신규 문서 파일 0건 / 채널명 변경 이벤트 신규 0건(7/27~7/29 기존 3건)
- Canvas 이벤트: 14건(design-backup 12 · 브랜업-계약서 1 · 뷰티-프로젝트 1), 최신 09-11 12:03 — 신규 없음 / 북마크 0건 (`slack_bookmark_scanner.py --all`)
- Wiki 페이지 갱신:
  - `concepts/eu-packaging-regulation.md` — **신규 생성**(EU 포장·재활용 규제, PPWR·REACH): 9개 항목 상세 + 브랜업 세트 구성별 적용 검토표 + 미해결/확인 필요 4건, provenance `^[channels/코스메틱-본부.md]`
  - `channels/코스메틱-본부.md` — 2026-09-23 활동 2건(트레이 보강·EU 리서치) 추가, 주요 의사결정 2건 추가, related_concepts에 신규 개념 연결, updated 09-22 → 09-24
  - `entities/enagic-usa.md` — "세트 포장 트레이 보강 및 EU 포장 규제 리서치 (2026-09-23)" 섹션 추가, tags에 `eu` 추가, updated 09-22 → 09-24
  - `concepts/줄리어스-대표-미팅-20260910.md` — "후속 조치 (2026-09-23)" 섹션 추가(국가별 규제 정리 과제의 첫 산출물), tags `eu`·sources에 채널 추가, updated 09-16 → 09-24
  - `projects/에나지크_발주_시뮬레이터.md` — 2026-09-23 활동 2건 추가(보강 작업·EU 규제 리서치)
  - `concepts/tsonax.md` — 09-24 기준 갱신, `[TSonaX] 1차 배포`·`[Toffer] 익절/손절 시나리오 개선` 마감 09-23 경과 리스크 명시
  - `SCHEMA.md` — Tag Taxonomy Market에 `eu` 추가(사용 전 등록 원칙)
  - `channels/index.md` — 퀵뷰 코스메틱-본부(트레이 보강·EU 리서치) 갱신, 채널 ID 매핑표 09-24 재확인(Slack 활성 15개 전부 매핑 일치), 공지사항 경고 8주차 갱신
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 8주차 갱신, updated 09-23 → 09-24
  - `index.md` — 총 페이지 54 → 55(concepts 16), `concepts/eu-packaging-regulation` 등재, TSonaX 요약(1차 배포 마감 경과)·업무 88건 갱신
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 8주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(4주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-24 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-25] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-25] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · 업무 88건 (상태: 진행중 87 · 지연 1) — **신규/변경 0건** (마지막 업무 갱신 09-23 12:49 `[Toffer] 익절/손절 시나리오 개선`)
  - 마감 경과 75건 유지(완료 처리 0건), **09-25 마감 5건**: 멕시코 수출 관련 가능 여부·고려사항 정리(강경철) / 브랜업캠퍼스 신규 법인설립(강경철·이향석, 긴급) / IR자료 디벨롭(강경철) / 시간될 때 보드 부착용 고급 바퀴 찾기(강경철) / [Web] cosmetic-review 서비스 추가(이향석) — 09-29 마감 1건: 윈도우 오피스365 라이센스 구입(이향석)
  - '지연' 상태 1건 유지: `아이젤 계약서 조영길이사와 사전 조율` (마감 08-27, 08-23 이후 갱신 없음)
  - TSonaX/Toffer 활성 5건 전건 마감 경과 — `[TSonaX] 1차 배포` 마감 09-23 → **2일 경과**
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 0건** (30h 창 = 09-23 23:00 KST 이후), **신규 첨부파일 0건**, 채널명 변경 이벤트 0건
  - 168h 창 내 3개 채널 7건(코스메틱-본부 5 · design-backup 1 · wiki 1)은 전량 기수집 (최신 09-23 13:43 EU 리서치)
  - 스캐너 2회 연속 실행 교차검증 — 카운트 동일 (파이프라인 정상)
- Canvas/북마크: Canvas 이벤트 14건(최신 09-11 12:03 뷰티-프로젝트), 북마크 0건 — **신규 없음**
- 채널 페이지 미생성 4개 채널 실체 확인 (`conversations.info` + `history`):
  - 브랜업-조직구성(C0BK1CQH6BZ) 참여 알림 5건뿐(2026-07-24) / 브랜업-휴가(C0BKWBME8AJ) 참여 알림 8건뿐(2026-07-27~30) → 업무 대화 없음, 페이지 생성 제외
  - 헤르메스(게이트웨이 알림 20건) / wiki(주간 린트 리포트 12건) → 자동 알림 채널, 페이지 생성 제외
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 09-25 기준 갱신: 마감 경과 일수 명시(+2/+2/+21/+35/+35일), 오늘 마감 개발 업무([Web] cosmetic-review·브랜업캠퍼스 신규 법인설립) 섹션 신설
  - `channels/index.md` — Slack 활성 15개 ID 매핑표 09-25 재확인(전량 일치), 미생성 채널 4건 사유 명시, 퀵뷰 코스메틱-본부 "9/24~9/25 신규 없음", 공지사항 경고 9주차
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 9주차 갱신, updated 09-24 → 09-25
  - `index.md` — TSonaX 요약 09-25 기준(마감 2일 경과·활성 5건 전건 경과) 갱신
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 린트 재점검 (콘텐츠 페이지 62개): 콘텐츠 페이지 깨진 링크 0건(raw/ 대상 링크는 스캔 제외 — 기존 목록은 false positive), 고아 7건(기존 미조치분), index 누락 7건(archive 대기분), 200줄 초과 2건(온보딩 매뉴얼 805줄 · 코스메틱-본부 237줄)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 9주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(5주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-25 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-25] lint | 주간 위키 린트 (W39, #wiki 게시)
- 스캔 범위: **콘텐츠 페이지 55개**(channels 11 · entities 15 · concepts 16 · projects 13) + raw 소스 42개 + nav 6개 (총 .md 103개). 링크 해석은 NFC 정규화 + raw/ 포함 slug 사전으로 수행(이전 크론의 "깨진 링크 9건"은 NFD/NFC 불일치 false positive였음).
- 깨진 위키링크 **1건 → 0건 수정 완료**
  - `channels/코스메틱-본부`: PDF를 가리키는 wikilink 1건 → 백틱 경로 표기(`raw/articles/branup-packaging-spec-usa-canada-20260728.pdf`)로 교체(PDF는 wikilink 대상 아님), `updated` 갱신
- 프론트매터 오류 **5건 → 0건 수정**
  - `concepts/task-status`·`concepts/project-status`·`concepts/브랜업-대시보드-현황`: 누락 `created:` 추가 (07-16 / 07-16 / 07-28)
  - `entities/브랜업-신입직원-온보딩-매뉴얼`: `created`·`updated`·`sources` 추가, `tags`를 taxonomy 태그로 정규화 + 한글 키워드는 `keywords:`로 이동
  - 지속성 확보: `branup_db_wiki_sync.py`가 `concepts/브랜업-대시보드-현황.md` 생성 시 `created: 2026-07-28`을 함께 기록하도록 생성기 수정
- 태그 이탈 **33종 → 0종 수정**: `SCHEMA.md` Tag Taxonomy에 실제 사용 태그 등재(legal·rnd·government·dashboard·market·product·competitor·b2b·korea·oem-odm·org·people·hr·risk·issue-tracking·onboarding·education·design·process·management·tech + 프로젝트 상태 자동 태그 계획·진행·보류·완료·취소)
- 고아 페이지 6건 / index 미등재 7건 — **10주차 미조치** (`_archive/` 이동 승인 대기). 각 페이지 상단에 대체 페이지 안내 배너 추가(비파괴). 대상: `concepts/task-status`, `concepts/project-status`, `entities/project-{ai_ax_직원_교육,브랜업_대시보드_개발,소라살롱_공구_프로젝트,시니어_마케터_채용_프로젝트,에나지크_발주_시뮬레이터}`
- 과대 페이지 3건: `entities/브랜업-신입직원-온보딩-매뉴얼` 805줄(분할 권장), `channels/코스메틱-본부` 237줄, `entities/enagic-usa` 206줄
- raw sha256 무결성: 64자 해시 18건 중 **3건 일치 / 15건 해시 산출 규칙 불일치**(placeholder 18건은 검증 불가). 15건 전부 단일 ingest 커밋만 존재(`git log` 확인) → **실제 소스 드리프트 아님**. 표준 규칙 = frontmatter 이후 본문에서 선행 개행 제거 후 sha256.
- 정상: stale(>90일) 0건 · ghost index 링크 0건 · contested 0건 · log 108건(임계 500 미달) · confidence low 1건(`concepts/branup-finance`)
- 참고(조치 불필요): `log.md` 내 과거 항목의 미해석 링크 6건(historical record)
- 네비게이션 갱신: `index.md` 미등재 섹션에 10주차 에스컬레이션 명시
- 리포트 #wiki 채널 게시 완료

## [2026-09-26] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-26] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · 업무 88건 (상태: 진행중 87 · 지연 1) — **신규/변경 0건** (최종 업무 갱신 09-23 12:49 `[Toffer] 익절/손절 시나리오 개선` 이후 3일 정지)
  - 마감 경과 **80건**(미완료 88건 중 `due_at` 있는 83건 기준, `due_at` 미입력 5건 별도) — 완료 처리 0건
  - **09-26 마감 0건** — 최근 마감: 09-25 5건(전량 경과), 09-29 1건(`윈도우 오피스365 라이센스 구입`, D-3), 09-30 2건(`BOM 정리 작업`·`카톤 개선 작업`, 강경철, D-4)
  - '지연' 상태 1건 유지: `아이젤 계약서 조영길이사와 사전 조율` (마감 08-27, 08-23 이후 갱신 없음)
  - TSonaX/Toffer 활성 5건 전건 마감 경과 — `[TSonaX] 1차 배포`·`[Toffer] 익절/손절 시나리오 개선` 마감 09-23 → **3일 경과**, 08-21·09-04 마감 3건 +36/+22일 경과
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 1건** (30h 창 = 09-24 23:00 KST 이후): `#wiki` 09-25 18:07 주간 린트 리포트(W39) — **주간 린트 크론 자체 산출물**로 위키 반영 완료(`log.md` W39 lint 항목)
  - **신규 첨부파일 0건**, 채널명 변경 이벤트 0건
  - 168h 창 내 3개 채널 7건(코스메틱-본부 5 · design-backup 1 · wiki 1)은 전량 기수집 (최신 09-23 13:43 EU 리서치). 업무 대화 신규 0건
  - 스캐너 2회 연속 실행 교차검증 — 카운트 동일(channels 4 · errors 1) = 파이프라인 정상
- Canvas/북마크: Canvas 이벤트 14건(최신 09-11 뷰티-프로젝트), 북마크 0건 — **신규 없음**
- 채널 맵 재검증: Slack 활성 15개 ↔ 위키 ID 매핑표 전량 일치(09-26 확인). 미생성 4개 채널 사유 유지(알림 전용/무활동 2 · 게이트웨이 알림 1(헤르메스) · 린트 리포트 1(wiki)), 봇 미참여 1(제품-기획-제작)
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 09-26 기준 갱신: 마감 경과 일수 재산정(+3·+3·+22·+36·+36일), 09-24~09-26 대시보드 갱신 0건 명시, 09-25 마감 개발 업무 2건(`[Web] cosmetic-review`, `브랜업캠퍼스 신규 법인설립`·긴급) **+1일 경과** 섹션 추가, 전사 마감 경과 80건 반영
  - `channels/index.md` — 헤더 09-26, ID 매핑표 09-26 재확인(15/15 일치, 봇 미참여 1 명시), 퀵뷰 코스메틱-본부 "9/24~9/26 신규 없음"·design-backup "9/22~9/26 신규 없음", 공지사항 경고 6주차(카운터 정규화)
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **6주차** 갱신 + 주차 카운터 정규화 주석 추가, 크론 재확인 항목(09-21~09-26) 신설, updated 09-25 → 09-26
  - `index.md` — 헤더 날짜(DB sync), TSonaX 요약 "마감 3일 경과·활성 5건 전건 경과" 갱신, 미등재 섹션에 09-26 일일 크론(10주차) 변동 없음 추가
  - `SCHEMA.md` — 채널 페이지 `sources:` 예외 규정 + 주차 카운터 통일 규칙 명문화(린트 false positive 재발 방지)
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- **주차 카운터 정규화(조치)**: 경고·에스컬레이션 주차가 일일 크론과 주간 린트에서 혼용되던 문제 정리 — 일일 크론 항목은 **일일 재확인 횟수** 기준으로 통일(공지사항 09-21 최초 → 09-26 6주차 / 고아·미등재 7건 → 10주차). `channels/브랜업-공지사항.md`에 혼용 사실과 통일 기준을 명시.
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 10주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(6주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-26 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-27] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-27] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · 업무 88건 (상태: 진행중 87 · 지연 1) — **신규/변경 0건** (최종 업무 갱신 09-23 12:49 `[Toffer] 익절/손절 시나리오 개선` — 4일 정지)
  - 마감 경과 **80건** 유지(완료 처리 0건), 09-27 마감 0건 — 09-29 마감 1건(`윈도우 오피스365 라이센스 구입`, 이향석, D-2), 09-30 2건(`BOM 정리 작업`·`카톤 개선 작업`, 강경철, D-3)
  - '지연' 상태 1건 유지: `아이젤 계약서 조영길이사와 사전 조율` (마감 08-27, 08-23 이후 갱신 없음)
  - TSonaX/Toffer 활성 5건 전건 마감 경과 — `[TSonaX] 1차 배포`·`[Toffer] 익절/손절 시나리오 개선` 마감 09-23 → **4일 경과**
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 1건** (30h 창 = 09-26 23:00 KST 이후): `#뷰티-프로젝트` 09-27 03:33 **줄리어스 대표 글로벌 물류·패키징 전략 5대 안건** (줄리어스/enagic.jkim) — 전량 신규 ingest
  - **신규 첨부파일 0건**, 채널명 변경 이벤트 0건
  - 168h 창 내 4개 채널 8건 중 1건(뷰티-프로젝트) 외 7건은 전량 기수집 (코스메틱-본부 5 · design-backup 1 · wiki 1 — 최신 09-23 13:43)
  - 스캐너 2회 연속 실행 교차검증 — 카운트 동일(channels 5 · errors 1) = 파이프라인 정상
- Canvas/북마크: Canvas 이벤트 14건(최신 09-11 12:03 뷰티-프로젝트), 북마크 0건 — **신규 없음**
- 신규 raw 원문: `raw/transcripts/줄리어스-9월27일-글로벌물류전략-안건-20260927.md` (sha256 `005bccc2…` 기록)
- Wiki 페이지 갱신:
  - `concepts/에나지크-글로벌-물류-패키징-전략.md` — **신규 생성**. 5대 안건 표(현지어 스티커 MOQ / 듀얼 언어 패키징 / 10월 물량 아시아 우회 수출 / 미국 168개 한국 역수출 / 일본 역수출 승인) + 시장·물량 구조 + 미해결 확인 항목 6건
  - `channels/뷰티-프로젝트.md` — 09-27 활동 요약 추가, 주요 의사결정 2건 신규(일본 역수출 최종 승인 / 아시아 우회 수출 논의 착수), related_concepts + 관련 페이지 갱신
  - `entities/enagic-usa.md` — 「글로벌 물류·패키징 전략 5대 안건 (2026-09-27)」 섹션 추가, 잔여 물량 처리 경로 3갈래 구체화 명시
  - `concepts/줄리어스-대표-미팅-20260910.md` — 후속 조치(09-27) 추가, 태국 로드맵 변화(09-10 로드맵 2028년 → 연내 진출 제안) 명시
  - `concepts/tsonax.md` — 09-27 기준 마감 경과 재산정(+4·+4·+23·+37·+37일), `[Web] cosmetic-review`·`브랜업캠퍼스` +2일 경과, 오피스365 D-2·BOM/카톤 D-3
  - `channels/index.md` — 헤더 09-27, ID 매핑표 09-27 재확인(15/15 일치·봇 미참여 1), 퀵뷰(뷰티-프로젝트 09-27 안건 / 코스메틱-본부 9/24~9/27 신규 없음 / design-backup 9/22~9/27 신규 없음), 공지사항 경고 7주차
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **7주차** 갱신, 재확인 구간 09-21~09-27, updated 09-26 → 09-27
  - `index.md` — Concepts 섹션에 신규 페이지 등재(총 56페이지 · concepts 17), TSonaX 요약 4일 경과, 미등재 섹션 11주차 변동 없음
  - `projects/에나지크_발주_시뮬레이터.md` — 09-27 활동 항목 추가(DB sync 자동 갱신 후 수동 보강)
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 링크 무결성: 변경 9개 파일 wikilink 전량 해석 OK (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 11주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(7주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-27 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-28] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 88건 동기화 완료

## [2026-09-28] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · 업무 88건 (상태: 진행중 87 · 지연 1) — **변경 7건: 09-27 16:05~16:08 KST 이향석 계정 일괄 갱신(마감일 재조정)**
  - `[TSonaX] 1차 배포` 마감 2026-09-23 → **2026-09-28(오늘, D-0)** · `[Toffer] 익절/손절 시나리오 개선` 09-23 → **09-30(D-2)**
  - 동반 재조정: `[Web] cosmetic-review 서비스 추가`·`브랜업캠퍼스 신규 법인설립` 09-25 → 10-02(D-4), `윈도우 오피스365 라이센스 구입` 09-29 → 10-02(D-4), `회계 현명 미지급금 출처 보완` → 09-29(D-1), `공용정보 리스트업` → 09-30(D-2)
  - 전사 **마감 경과 80건 → 74건**(6건이 경과 목록 이탈). 최종 업무 갱신 09-27 16:08:03 — 09-23~09-26 정지 구간 해소
  - 재조정 제외 3건은 경과 유지: `[TSonaX] 대표님 지표추가`·`[TSonaX] 새로운 DB에 2년치 기본 데이터`(+38일, 08-21) · `[TSonaX] 종목별 실시간 프로그램 순매수 수량/금액 처리`(+24일, 09-04)
  - '지연' 상태 1건 유지: `아이젤 계약서 조영길이사와 사전 조율` (마감 08-27, 08-23 이후 갱신 없음)
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 0건** (24h 창 = 09-27 05:00 이후). 168h 창 4개 채널 8건은 전량 기수집 (코스메틱-본부 5 · design-backup 1 · 뷰티-프로젝트 1(09-27 03:33) · wiki 1, 최신 09-27 03:33)
  - **신규 첨부파일 0건** — 168h 내 파일 2건(design-backup PSD 366MB 09-21 · 코스메틱-본부 image.png 09-23) 모두 기수집. 스레드 답글 0건, 채널명 변경 이벤트 0건
  - 스캐너 2회 연속 실행 교차검증 — 카운트 동일(channels 4 · messages 8 · files 2 · errors 1) = 파이프라인 정상
- Canvas/북마크: Canvas 이벤트 14건(최신 09-11 12:03 뷰티-프로젝트), 북마크 0건 — **신규 없음**
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 09-28 기준 전면 갱신: 마감일 재조정 반영(`[TSonaX] 1차 배포` D-0 · `[Toffer]` D-2), 경과 3건 재산정(+38·+38·+24일), 전사 마감 경과 74건, 최우선 항목 오늘 마감 경고 추가
  - `channels/index.md` — 헤더 09-28, ID 매핑표 09-28 재확인(15/15 일치 · 봇 미참여 1), 퀵뷰(코스메틱-본부 9/24~9/28 신규 없음 · design-backup 9/22~9/28 신규 없음 · 뷰티-프로젝트 9/28 신규 없음), 공지사항 경고 8주차
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **8주차** 갱신, 재확인 구간 09-21~09-28, updated 09-27 → 09-28
  - `index.md` — 헤더 날짜, TSonaX 요약(마감 09-28 D-0·재조정 이력), 미등재 섹션 12주차 변동 없음 추가
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 링크 무결성: 전체 106파일 373링크 검사 — 신규 broken 0건(잔여 11건은 log.md·SCHEMA.md·raw/ 기존 항목)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 12주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(8주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-28 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요

## [2026-09-29] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 92건 동기화 완료

## [2026-09-29] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · **업무 92건** (전일 88건 대비 +4, 상태: 진행중 91 · 지연 1 · `due_at` 미입력 5건)
  - **09-28 신규 등록 3건 확인** — `멕시코, 남미 시장 바로 가능 여부 리서치`(강경철, 마감 09-28 → **당일 경과**, Slack 코스메틱-본부 지시와 직결) · `브랜업 상표등록`(이향석, 마감 09-30, 특허고객번호 4-1-2026-5348950-98) · `브랜업 퇴직금 제도 조사`(이향석, 마감 10-09)
  - 잔여 +1건은 ID(`display_num`) 결번(#445)으로 개별 확인 불가 → 수치만 기록
  - 전사 **마감 경과 74건 → 76건** (+2). '지연' 상태 1건 유지: `아이젤 계약서 조영길이사와 사전 조율`(마감 08-27)
  - 마감 임박: D-0 2건(`ABTC 기업인여행카드 발급`, `회계 현명 미지급금 출처 보완`) / D-1 5건 / D-3 3건
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 5건**(24h 창 = 09-28 05:00 이후): 코스메틱-본부 1 · kcl 1 · design-backup 3. 뷰티-프로젝트 1건(09-28 16:08)은 이모지만 → 비실질 skip
  - 168h 창 총 6건(5건 신규 + 09-27 03:33 뷰티-프로젝트 기수집분), 첨부 **신규 5건** — 전량 다운로드·분석 완료
  - 스캐너 2회 연속 실행 교차검증 — 카운트 동일(channels 5 · messages 6 · files 7 · errors 0) = 파이프라인 정상
- Canvas/북마크: Canvas 이벤트 14건(최신 기존분과 동일) · 북마크 0건 — **신규 없음**
- 신규 파일 분석 (raw 원문 5건):
  - `raw/articles/kcl-sgs-quote-2026-09-04.md` — **SGS 최종 견적서**: 3개 제품, 소계 51,256,000원(VAT 별도) / **총 56,381,600원(VAT 포함)**, 18·50·80 working days, 환율 1,381.44원/USD. 07-22 시나리오(69,052,500원)에서 소비자 체험 설문조사 제외
  - `raw/articles/kcl-plan-change-letter-20260830.md` — KCL 사업계획 변경요청 공문(대표이사 이상원, 시행 08-30), 실증사업명 "북미/캐나다 수출 실증"
  - `raw/articles/kangen-3-products-ingredient-statement-20260928.md` — **KANGEN 3종 전성분표**(제조사 EYESEL, 100g 기준): Vital Rich Cream 104성분 · Crystal Ampoule Cream 63성분 · First Light Essence 93성분. XLSX 3시트 정밀 파싱(함량·CAS·기능 보존)
  - `raw/articles/sgs-test-contract-signed-20260922.md` — SGS 시험검사 위탁계약서 서명본(8p, 이미지 PDF → 텍스트 0byte, 파일명 근거)
  - design-backup `인쇄영역 데이터-타이름리런스 크림 15ml (STEP 2).pdf`(1p 이미지 PDF) + `목업용스티커.ai`(타입 외) → 채널 페이지에 맥락 기록
- Wiki 페이지 갱신:
  - `entities/eyesel.md` — **신규 생성**. KANGEN BEAUTÉ 3종 제조사(OEM), 담당 제품·제형 특징·SGS/KCL 자료 출처
  - `concepts/kcl-overseas-certification-2026.md` — 진행 현황 표(6단계, '시험 수행' 전환), SGS 최종 견적·계약 섹션, 시험 대상 제품 표, 추진 일정, sources 8건
  - `concepts/에나지크-글로벌-물류-패키징-전략.md` — 「후속 조치(09-28)」 실행 과제 5건 + 기한 표, 미해결 항목 상태 갱신, sources에 코스메틱-본부 추가
  - `concepts/tsonax.md` — 09-29 기준 갱신: `[TSonaX] 1차 배포` **마감 경과(+1일, 완료 미처리)** 복귀, Toffer D-1, 경과 3건 +39·+39·+25일, 전사 경과 76건, 신규 업무 3건
  - `channels/kcl-해외인증실증지원사업-202607.md` — 09-28 활동 4파일 + 결정 3건 + KB(사업계획 변경 공문 필수·시험 의뢰 제출자료), `updated` 08-12 → 09-29 (8주 만의 갱신)
  - `channels/코스메틱-본부.md` — 09-28 리서치 지시 5건(기한 포함) + 결정 + KB 「글로벌 진출 리서치 체크리스트」
  - `channels/branup-design-backup.md` — 09-28 인쇄영역 데이터·스티커 원본·정면 면적(20×50/25×63)
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **9주차** 갱신
  - `channels/index.md` — 헤더 09-29, ID 매핑표 09-29 재확인(**15/15 일치**), 퀵뷰 4행 갱신
  - `projects/kcl_sgs_안정성검사_사업_실행_12_31.md` — 「📋 최근 활동」 09-28 신설 + **대시보드 상태 불일치 경고**(상태 `계획` vs 실제 계약·시험 단계)
  - `projects/에나지크_발주_시뮬레이터.md` — 09-28 활동 2건 추가(리서치 지시·인쇄영역 데이터)
  - `index.md` — Total 57페이지(entities 16), Entities에 eyesel 등재, Concepts 4행 갱신, 미등재 13주차
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 링크 무결성: 신규·갱신 파일 wikilink 전량 해석 확인 (broken 0건 — 잔여 기존 항목은 log.md·SCHEMA.md·raw/ 내부)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 13주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(9주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-29 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(신규): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계와 불일치 — 상태 갱신 필요

## [2026-09-30] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 93건 동기화 완료

## [2026-09-30] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · **업무 93건** (전일 92건 대비 +1, 상태: 진행중 92 · 지연 1 · `due_at` 미입력 5건)
  - **09-29 신규 등록 4건** — `글로벌 화장품 인증·규제 가이드 정리`(#448, 강경철, 마감 09-30) · `CNF 문의 루트 파악 및 메일 작성`(#449, 강경철, 09-30) · `Plaud 미팅 노션 연동`(#450, 강경철, 10-02) · `원티드 80% 환급 요청`(#451, 전경표, 09-30 — `시니어 마케터 채용 프로젝트`에 연결된 유일한 신규 프로젝트 업무)
  - **⚠️ 목록 제거 3건 (09-29)** — `[TSonaX] 1차 배포`(#439, 마감 09-28) · `CDRI 14개국 인증 견적 확인`(#440, 09-22) · `ABTC 기업인여행카드 발급`(#441, 09-29). API가 완료/삭제를 구분해 주지 않음 → **`[TSonaX] 1차 배포`는 완료 처리 추정(사용자 확인 필요)**
  - 마감일 재조정 5건(09-29, 강경철 계정): `바퀴 찾기`·`IR자료 디벨롭`·`여유 수량 및 환율 제안 텍스트`(09-25→09-30), `멕시코·남미 리서치`(09-28→09-30), `카톤 개선 작업`(09-30→10-15)
  - 전사 **마감 경과 76건 → 71건**, **D-0 11건**(전일 2건). '지연' 1건 유지: `아이젤 계약서 조영길이사와 사전 조율`(마감 08-27)
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 2건 / 신규 파일 1건** (24h 창 = 09-29 05:00 이후) — 전량 `뷰티-프로젝트`
    - 09-29 07:22 줄리어스 대표 — **패키지 디자인 최종 승인**(Enagic Cosme + 법무팀) → 12월 크리스마스 이전 납품 일정 협조, 싸바리 박스·샘플 색상 조화. 첨부 캡 컬러 2안 이미지(image.png 42KB)
    - 09-30 03:23 줄리어스 대표 — **리콜 대응·제품 추적성 요건**(order batch 고유 시리얼 번호·세트 하단 표시·출하 서류 기재·Enagic Cosme Recall Procedure 수립·EYESEL SOP 사본 요청)
  - 168h 창 총 6건·파일 8건(신규 2건/1건) — 잔여 4건·7파일은 기수집분(코스메틱-본부 09-23 이미지, design-backup 09-28 2파일, kcl 09-28 4파일)
  - 스캐너 교차검증: channels 15 · activity 5 · messages_24h 2 · files_168h 8 · errors 0 (2회 실행 동일)
- Canvas/북마크: Canvas 이벤트 14건(최신 09-11 12:03 뷰티-프로젝트 — 신규 없음) · 북마크 0건
- 신규 파일 분석: `raw/assets/kangen-beaute-sabari-box-final-approval-20260929.png` (sha256 255a948d0af8…, 42,760 bytes) — 캡 컬러 2안 비교 캡처(좌: 암보라 + 기존 캡 컬러 / 우: 암보라 + 진한 토퍼 캡컬러), KANGEN BEAUTÉ First Light Essence(STEP1)·크림 용기
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 09-30 기준 갱신: **1차 배포 목록 제거 반영(완료 추정·확인 필요)**, Toffer **D-0**, 경과 3건 +40·+40·+26일, 전사 경과 71건·D-0 11건, 09-29 갱신 5건·신규 4건
  - `channels/뷰티-프로젝트.md` — 09-30 섹션 신설(디자인 최종 승인·리콜 추적성) + 의사결정 2건 + KB 「리콜 대응·제품 추적성(미국 수출 요건)」 추가, related_entities에 eyesel
  - `entities/enagic-usa.md` — 「패키지 디자인 최종 승인 및 리콜 추적성 요건(2026-09-29~30)」 섹션 + 이미지 임베드, updated 09-27 → 09-30
  - `concepts/에나지크-글로벌-물류-패키징-전략.md` — 「후속 조치(2026-09-29~30)」 표 추가(디자인 승인 / 리콜·추적성), sources에 이미지 추가
  - `projects/에나지크_발주_시뮬레이터.md` — 「📋 최근 활동」 09-30 신설(승인·리콜 추적성, 발주·선적 영향 명시)
  - `projects/시니어_마케터_채용_프로젝트.md` — 09-30 `원티드 80% 환급 요청` 활동 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **10주차** 갱신
  - `channels/index.md` — 헤더 09-30, ID 매핑표 09-30 재확인(15/15 일치), 퀵뷰 3행 갱신, 공지사항 10주차
  - `index.md` — TSonaX 요약 갱신(1차 배포 목록 제거·Toffer D-0), 미등재 섹션 14주차
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 14주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(10주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (09-30 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(신규): `[TSonaX] 1차 배포`(#439)가 09-29 대시보드 목록에서 제거 — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(기존): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계와 불일치 — 상태 갱신 필요

## [2026-10-01] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 98건 동기화 완료

## [2026-10-01] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- DB 동기화: 프로젝트 13개 · **업무 98건** (전일 93건 대비 **+5**, 상태: 진행중 97 · 지연 1 · `due_at` 미입력 5건)
  - **09-30 신규 등록 5건** — `여권재신청`(#453, 이향석, 마감 09-30) · `협력업체 가격 시나리오 기록 정리`(#454, 강경철, 10-02) · `브이엘-아이젤-브랜업 계약서 여부`(#455, 강경철, 10-02) · `김봉재님 퇴사 처리`(#456, 이향석, 10-01) · `[Web] 근태관리 페이지 추가`(#457, 이향석, 10-02). **5건 전부 프로젝트 미지정**
  - 목록 제거 **0건** (09-29 제거 3건 `#439`·`#440`·`#441`은 2회 연속 부재 유지). `#445`·`#452`는 display_num 결번
  - 마감 경과 71 → **77건** (+6 = 마감 09-30 도래분 일괄 경과: `[Toffer] 익절/손절`#431 · `공용정보 리스트업`#437 · `멕시코·남미 리서치`#444 · `브랜업 상표등록`#446 · `원티드 80% 환급`#451 · `여권재신청`#453)
  - **D-0 2건** (10-01) — `CNF 문의 루트 파악 및 메일 작성`(강경철 #449) · `김봉재님 퇴사 처리`(이향석 #456). '지연' 1건 유지: `아이젤 계약서 조영길이사와 사전 조율`(마감 08-27)
- Slack 스캔: 활성 15개 채널 전체 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 0건 / 신규 파일 0건** (24h 창 = 09-30 05:02 ~ 10-01 05:02 KST). 최신 메시지는 뷰티-프로젝트 09-30 03:23(리콜·시리얼 추적성 요건) — 전일 회차 수집분
  - 168h 창 누적 메시지 11건 · 스레드 답글 0건 · 파일 7건 — **전량 기수집분**(뷰티-프로젝트 4건/1파일, design-backup 3/2, 코스메틱-본부 1/0, kcl 1/4, wiki 1/0)
  - 스캐너 교차검증: channels 15 · activity 5 · messages_24h 0 · thread_replies 0 · files_168h 7 · errors 0 **(2회 실행 결과 동일)**
- Canvas/북마크: Canvas 이벤트 14건(신규 없음 — 최신 09-11 12:03 뷰티-프로젝트) · 북마크 0건 · 봇 미참여 채널 1건(제품-기획-제작)
- 신규 파일 분석: 없음 (신규 다운로드 0건 — 전일 수집분 재확인만)
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 10-01 갱신: Toffer **+1일 경과**, 나머지 3건 +27·+41·+41일, `1차 배포` 2회 연속 부재, 전사 경과 77건·D-0 2건, 09-30 신규 5건 연혁 추가, **김봉재 퇴사 인력 공백 리스크** 등재
  - `channels/아이젤-계약서.md` — 「채널 활동 요약」에 09-30 대시보드 연계 항목 신설(#455 브이엘-아이젤-브랜업 계약서 여부 / #454 협력업체 가격 시나리오)
  - `projects/칸겐뷰티_sns_운영.md` — 「📋 최근 활동」 10-01 신설(담당자 김봉재 퇴사 처리 → 인력 공백·재배정 필요)
  - `projects/마케팅팀_노션_시범운영___협업플로우_셋팅.md` — 「📋 최근 활동」 10-01 신설(담당자 이탈 + 예상 종료 09-30 경과·등록 업무 0건)
  - `entities/branup-org-chart.md` — 김봉재 행 갱신(2026-10-01 퇴사 처리 진행), updated 2026-07-17 → 10-01
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **11주차** 갱신
  - `channels/index.md` — 헤더 10-01, ID 매핑표 10-01 재확인(15/15 일치), 퀵뷰 3행 갱신 + **10-01 스캔 결과 노트**(신규 0건·교차검증), 공지사항 11주차
  - `index.md` — TSonaX 요약 갱신(1차 배포 2회 연속 부재·Toffer +1일·경과 77건), 미등재 섹션 15주차
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신)
- 링크 무결성: 신규·갱신 파일 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 15주차): 린트 권장 고아 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(11주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-01 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(3주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30·10-01 2회 연속 부재 — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(신규): `김봉재님 퇴사 처리`(#456) — 담당 프로젝트 `칸겐뷰티 SNS 운영`·`마케팅팀 노션 시범운영 & 협업플로우 셋팅` 담당 재배정 필요
- 미조치(기존): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계와 불일치 — 상태 갱신 필요
- 비고: 09-29·09-30 각 5건·4건 연속 신규 등록(2일 +9건)으로 대시보드 활성도 상승. 마감 10-02 업무 8건 집중 → **10-02 회차 우선 확인 대상**

## [2026-10-02] lint | 주간 위키 린트 (weekly-wiki-lint)
- 검사 범위: 콘텐츠 페이지 **57** (channels 11 · entities 16 · concepts 17 · projects 13) + 네비게이션 2 (`channels/index`, `projects/index`) + raw 소스 47
- 무결성:
  - broken wikilink **0건** (비-md 자산 `raw/assets/*.png` 링크까지 해석 — 0건 확인 후 자산 슬러그를 해석 사전에 포함)
  - ghost page(index 링크가 파일로 해석되지 않음) **0건**
  - frontmatter 결손 **0건** / 알 수 없는 `type` **0건**
  - inbound 링크 기준 **고아 6건** — `concepts/task-status`, `entities/project-ai_ax_직원_교육`, `entities/project-브랜업_대시보드_개발`, `entities/project-소라살롱_공구_프로젝트`, `entities/project-시니어_마케터_채용_프로젝트`, `entities/project-에나지크_발주_시뮬레이터`
  - index 미등재 **7건** — 위 6건 + `concepts/project-status`(타 페이지 유입 링크 有, index 미등재) → **09-18 린트 권장 목록과 동일, 변동 없음**
- 태그 감사: taxonomy 70종 / 사용 61종. 위반 **5종** — `channel`·`department`·`company`·`announcement`는 SCHEMA.md taxonomy에 **Structure 라인 신설 등재**, `task`는 `concepts/task-status`(아카이브 대기) 전용이라 미등재 유지
- stale(updated 90일 초과) **0건** / 과대 페이지(200줄 초과) **3건** — `entities/브랜업-신입직원-온보딩-매뉴얼` 802줄 · `channels/코스메틱-본부` 257줄 · `entities/enagic-usa` 225줄
- raw sha256 불일치 **19건** — `git log` 확인 결과 **전건 해당 ingest 커밋 1건뿐** → 소스 변경이 아니라 **해시 산출 규칙(본문 슬라이스/개행 처리) 불일치**. 드리프트 판정 불가 placeholder **18건**
- 파일 갱신:
  - `SCHEMA.md` — Tag Taxonomy에 Structure 4종 등재 + 2026-10-02 린트 노트
  - `index.md` — Last updated 10-02, 미등재 섹션 16주차 린트 노트
  - `log.md` — 본 항목
  - `README.md` — 재생성 (페이지 수 57 유지)
- log.md 항목 수: **120 → 121** (본 항목 추가 전/후 · 로테이션 임계 500 미만 — 유지)
- 미조치(사용자 판단 필요, 16주차): 고아·미등재 **7건** `_archive/` 이동 승인 대기 (`git mv` + index 정리 + inbound 링크 평문 전환, 승인 1건이면 즉시 실행)
- **특이사항(신규):** 2026-10-02 05:00 `daily-slack-wiki-summary`(790aed499b47) 크론 **실패** — `last_status=error`, 사유 `Provider has been unresponsive (no response received) for 5 consecutive stale attempts`. 부수적으로 전달 실패 `platform 'telegram' not configured/enabled`. → **당일 DB/Slack 동기화 미실행**(최신 커밋 10-01 05:09 기준 `477175c`). 재실행 또는 모델/세션 교체 확인 필요.

## [2026-10-03] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 99건 동기화 완료

## [2026-10-03] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- **회차 특이사항:** 2026-10-02 05:00 회차가 provider 무응답(`Provider has been unresponsive … 5 consecutive stale attempts`)으로 **실패**했으므로, 본 10-03 회차가 **10-01 05:02 ~ 10-03 05:00 (약 48시간)** 구간을 일괄 반영했다.
- DB 동기화: 프로젝트 13개 · **업무 99건** (10-01 98건 대비 **+1**, 상태: 진행중 98 · 지연 1 · `due_at` 미입력 5건)
  - **신규 등록 5건** — `[에나지크] 오더별 공유용 타임라인 및 폴더`(#458, 강경철, 마감 10-02 — **등록 즉시 경과**) · `[KCL] 10월 정기보고서 제출`(#459, 이향석, 10-09) · `[OTC] 미국 선크림 인증 절차 조사`(#460, 이향석, 10-16) · `그랜터 -> Clobe 로 재무 서비스 이전`(#461, 이향석, 10-06) · `교수님이 준 엑셀 자료 검토`(#462, 강경철, 10-06). **5건 전부 프로젝트 미지정**
  - **⚠️ 목록 제거 4건** — `공용정보 리스트업`(#437, 마감 09-30) · `여권재신청`(#453, 09-30) · `김봉재님 퇴사 처리`(#456, 10-01) · `[Web] 근태관리 페이지 추가`(#457, 10-02). API가 완료/삭제를 구분해 주지 않음 → **완료 추정**(특히 #456 김봉재 퇴사·#457 근태관리 페이지는 마감 도래 후 제거)
  - 마감일 재조정 **6건**(전건 연기): `브랜업캠퍼스 신규 법인설립`·`[Web] cosmetic-review 서비스 추가`·`브랜업 상표등록`(→10-09), `[Toffer] 익절/손절 시나리오 개선`(09-30→10-02), `윈도우 오피스365 라이센스 구입`(→10-06, 담당 이향석→이향석·전경표), `회계 현명 미지급금 출처 보완`(09-29→10-07)
  - 마감 경과 77 → **80건**(+3), **D-0 0건**(10-03), D-3 이내 3건(마감 10-06). '지연' 1건 유지: `아이젤 계약서 조영길이사와 사전 조율`(마감 08-27)
  - `#439`(`[TSonaX] 1차 배포`)·`#440`·`#441`은 09-29 제거 후 **3회 연속 부재 유지**
- Slack 스캔: 활성 15개 채널 전량 조회 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 4건 / 신규 파일 1건** (48h 창 = 10-01 05:02 이후)
    - 10-01 09:49 `브랜업-전체` 전경표 — **소라살롱 공동구매 캠페인 최종 수수료 정산서 업로드**: 매출 35,804,000원 · 판매수수료 제한 입금액 34,299,438원(네이버 스마트스토어 수수료 4.2%) · **최종 수수료 지급액(22%) 7,876,880원**
    - 10-01 09:50 `브랜업-전체` USLACKBOT — **Canvas 탭 업데이트**(본문 없는 이벤트)
    - 10-01 16:47 `뷰티-프로젝트` 줄리어스 대표 — **`Market Expansion Plan 2026.10.01.xlsx`**(29,507 bytes) 공유. "**각 국가별 언어 버전을 5,000개 MOQ로 별도 제작하는 것은 현실적으로 어려워, 부득이하게 스티커 또는 오버레이 방식을 적용**" + 법무팀 협의안(파일 마지막 시트) 검토 요청
    - 10-02 18:04 `wiki` Hermes — 주간 린트 리포트 W40 (봇 자체 산출물)
  - 168h 창 누적 메시지 13건 · 파일 8건 — 잔여분은 09-27~09-30 기수집분(뷰티-프로젝트 4·design-backup 3·코스메틱-본부 1·kcl 1)
  - 스레드 답글 0건 · 스캐너 errors 2(제품-기획-제작 `not_in_channel`만)
  - 채널 rename 이벤트 0건(누적 3건은 7월 이력) · 활성 15개 ID 15/15 일치
- Canvas/북마크: Canvas 이벤트 **15건**(직전 14건 + 10-01 09:50 `브랜업-전체` 신규 1건, `tabbed_canvas_updated`) · 북마크 0건
- 신규 파일 분석: **`Market Expansion Plan 2026.10.01.xlsx`** (sha256 85ffb379…, 4시트: Document / Market Expansion Plan / Future Order Plan / Overlay Requirement)
  - 진출 계획 25개국(언어·연간 수요), **Total Annual Demand 111,900세트**, **Planned Order 20,000세트 × 8회**(SEP26~NOV27)
  - 국가별 수요 추정 합계 **256,846세트**(미국 110,534 · 캐나다 48,678 · 독일 36,850 · 호주 11,254 · 홍콩 8,704 · 이탈리아 7,944 · 프랑스 6,610 · 포르투갈/스페인 4,698 · 태국 4,052 · 일본 3,504 …)
  - **Overlay Requirement 25개국 요건표** — 사전 인쇄 불가(규제 번호 의존) **9개국**: TH·PH·TW·KH·ID·TR·AE·IN·BR / 사전 인쇄 가능 9개국: MX·HK·SG·MY·KR·GB·AU·NZ·RU(DoC 후) / EU 6개국(DE·IT·FR·ES·RO·PT)은 **EU RP 1인 주소로 공통 커버**
  - 원본요약 저장: `raw/articles/enagic-market-expansion-plan-20261001.md`, 원본 XLSX `raw/articles/slack_뷰티-프로젝트_F0C6RBS36GG_market-expansion-plan-20261001.xlsx`
- Wiki 페이지 갱신:
  - `raw/articles/enagic-market-expansion-plan-20261001.md` **신규** — XLSX 4시트 전문 요약 + 오버레이 요건표 + 시사점 (raw frontmatter sha256 포함)
  - `channels/뷰티-프로젝트.md` — 「최근 활동 요약」 10-01 섹션 신설(Market Expansion Plan), 「주요 의사결정」 10-01 오버레이 확정 추가, KB 「국가별 오버레이(스티커) 방식 — 25개국 요건」 신설, updated 09-30 → 10-03
  - `channels/branup-전체.md` — 10-01 섹션 신설(소라살롱 최종 정산 + Canvas 업데이트), updated 08-19 → 10-03
  - `concepts/에나지크-글로벌-물류-패키징-전략.md` — 「후속 조치 (2026-10-01) — 오버레이 방식 확정」 섹션 신설(물량 계획·오버레이 실행 제약), 「미해결」의 안건 ①을 **해소 처리**, sources에 신규 원본요약 추가, updated 09-30 → 10-03
  - `entities/enagic-usa.md` — 「시장 확대 계획 및 오버레이 요건 (2026-10-01)」 섹션 추가, sources·updated 갱신
  - `projects/에나지크_발주_시뮬레이터.md` — 「📋 최근 활동」 10-01 신설(오버레이 전환 → 발주·부착 공정 신규 변수) + 연계 업무 #458
  - `projects/소라살롱_공구_프로젝트.md` — 「📋 최근 활동」 10-01 신설(최종 수수료 정산 완료) + 담당(김봉재) 재배정 필요 명시
  - `concepts/tsonax.md` — 10-03 기준 전면 갱신: Toffer **마감 10-02 연기 후 +1일 경과**, 나머지 3건 +29·+43·+43일, `1차 배포` 3회 연속 부재, 전사 경과 80건·D-0 0건, 10-01~10-02 연혁 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **12주차** 갱신, updated 10-03
  - `channels/index.md` — 헤더 10-03, ID 매핑표 10-03 재확인(15/15), 퀵뷰 3행 갱신(뷰티-프로젝트·브랜업-전체·공지사항), 10-03 스캔 결과 노트 + 10-02 크론 실패 노트
  - `index.md` — Last updated 10-03, TSonaX 요약 갱신(1차 배포 3회 연속 부재·Toffer D-1·경과 80건), 에나지크 전략 요약 갱신(10-01 오버레이 확정), 대시보드 현황 99건, 미등재 섹션 17주차
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 99건)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 17주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(12주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-03 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(4주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30·10-01·10-03 3회 연속 부재 — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(신규): 경과 최다 업무 상위 — `[TSonaX] 대표님 지표추가(차트포함)`·`[TSonaX] 새로운 DB에 2년치 기본 데이터 넣기`(+43일), `[TSonaX] 종목별 실시간 프로그램 순매수 수량/금액 처리`(+29일) — 마감 재조정 또는 완료 처리 필요
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 줄리어스 대표가 09-29(디자인 승인) → 09-30(리콜·추적성) → 10-01(시장확대·오버레이) **3일 연속 실행 요건을 공유** 중이며, 브랜업 측 대응 업무는 `[에나지크] 오더별 공유용 타임라인 및 폴더`(#458) 1건뿐이고 그것도 마감이 경과했다. **국가별 오버레이 방식 검토 회신이 다음 병목**.

## [2026-10-04] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 99건 동기화 완료

## [2026-10-04] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- **회차 특이사항:** 주말(토) 구간 — **Slack 신규 메시지 0건 · 신규 파일 0건**, DB 변동 0건. 실질 갱신은 날짜 롤링(마감 경과 일수)과 미조치 카운터뿐.
- DB 동기화: 프로젝트 13개 · **업무 99건 (변동 없음)** — 10-03 99건 대비 신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0
  - 상태: 진행중 98 · 지연 1(`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27)
  - 마감 경과 **80건 유지**(10-03과 동일 — 마감 10-03 업무가 0건이었으므로 증가분 없음), **D-0 0건**, D-3 이내 4건(10-06 ×3 · 10-07 ×1), `due_at` 미입력 5건
  - TSonaX/Toffer 4건 전건 갱신 없음 — `[Toffer] 익절/손절 시나리오 개선` 마감 10-02 **+2일 경과**, `[TSonaX] 종목별 실시간 프로그램 순매수 수량/금액 처리` +30일, `[TSonaX] 대표님 지표추가(차트포함)`·`[TSonaX] 새로운 DB에 2년치 기본 데이터 넣기` +44일
- Slack 스캔: 활성 15개 채널 전량 조회 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **신규 메시지 0건 / 신규 파일 0건** (창 = 10-03 05:09 이후 26시간)
  - 채널별 최신 메시지: `wiki` 10-02 18:04(주간 린트 봇 리포트) · 업무 대화 최신 `뷰티-프로젝트` 10-01 16:47(에나지크 시장확대 XLSX)
  - 168시간 창 누적 메시지 12건 · 파일 8건 — 전량 09-28~10-02 기수집분 / 스레드 답글 0건 / errors 2(`not_in_channel`만)
  - 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치 재확인
- Canvas/북마크: Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 0건
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 10-04 기준 전면 갱신(Toffer +2일 경과, 1차 배포 **4회 연속 부재**, 경과 3건 +30~+44일, 전사 경과 80건 유지, 연혁 10-04 항목 추가)
  - `channels/index.md` — 헤더 10-04, ID 매핑표 10-04 재확인(15/15), 브랜업-공지사항 경고 **13주차**, 10-04 스캔 결과 노트 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **13주차** 갱신, updated 10-04
  - `index.md` — TSonaX 요약 갱신(4회 연속 부재·Toffer D-2·경과 80건 유지), 미등재 섹션 18주차 노트
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 99건 — 날짜 롤링만)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 18주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(13주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-04 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(5주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30·10-01·10-03·10-04 **4회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 에나지크 국가별 오버레이 방식(10-01 확정) 관련 브랜업 측 회신 상태 변동 없음 — 대응 업무 `[에나지크] 오더별 공유용 타임라인 및 폴더`(#458, 강경철, 마감 10-02)가 **D-2 경과**로 미착수. **국가별 오버레이 검토 회신이 여전히 다음 병목**.

## [2026-10-05] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 99건 동기화 완료

## [2026-10-05] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- **회차 특이사항:** 일요일 구간 — **Slack 업무 신규 메시지 0건 · 신규 파일 0건**, DB 변동 0건. 실질 갱신은 날짜 롤링(마감 경과 일수)과 미조치 카운터뿐. 유일한 신규 메시지는 `헤르메스` 채널의 봇 게이트웨이 재시작 알림 2건(비업무).
- DB 동기화: 프로젝트 13개 · **업무 99건 (변동 없음)** — 10-04 99건 대비 신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0 (git diff상 전 프로젝트 페이지는 날짜 라인만 변경)
  - 상태: 진행중 98 · 지연 1(`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, 39일 경과)
  - 마감 경과 **80건 유지**(10-03·10-04와 동일 — 마감 10-03·10-04 업무가 0건이었으므로 증가분 없음), **D-0 0건**, D-1 3건(10-06: `윈도우 오피스365 라이센스 구입`·`그랜터 -> Clobe 로 재무 서비스 이전`·`교수님이 준 엑셀 자료 검토`), D-2 1건(10-07 `회계 현명 미지급금 출처 보완`), `due_at` 미입력 5건
  - TSonaX/Toffer 4건 전건 갱신 없음 — `[Toffer] 익절/손절 시나리오 개선` 마감 10-02 **+3일 경과**, `[TSonaX] 종목별 실시간 프로그램 순매수 수량/금액 처리` +31일, `[TSonaX] 대표님 지표추가(차트포함)`·`[TSonaX] 새로운 DB에 2년치 기본 데이터 넣기` +45일
- Slack 스캔: 활성 15개 채널 전량 조회 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **업무 신규 메시지 0건 / 신규 파일 0건** (창 = 10-04 05:00 이후 28시간)
  - 채널별 최신: `헤르메스` 10-04 23:47(봇 게이트웨이 알림 2건, 비업무) · `wiki` 10-02 18:04(주간 린트 봇 리포트) · 업무 대화 최신 `뷰티-프로젝트` 10-01 16:47(에나지크 시장확대 XLSX)
  - 168시간 창 누적 메시지 15건 · 파일 8건 — 전량 09-28~10-02 기수집분 / 스레드 답글 0건 / errors 2(`not_in_channel`만)
  - 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치 재확인
- Canvas/북마크: Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 0건
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 10-05 기준 전면 갱신(Toffer +3일 경과, 1차 배포 **5회 연속 부재**, 경과 3건 +31~+45일, 전사 경과 80건 유지, 연혁 10-05 항목 추가)
  - `channels/index.md` — 헤더 10-05, ID 매핑표 10-05 재확인(15/15), 브랜업-공지사항 경고 **14주차**, 10-05 스캔 결과 노트 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **14주차** 갱신, updated 10-05
  - `index.md` — TSonaX 요약 갱신(5회 연속 부재·Toffer D-3·경과 80건 유지), 미등재 섹션 19주차 노트
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 99건 — 날짜 롤링만)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 19주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(14주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-05 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(6주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30·10-01·10-03·10-04·10-05 **5회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(신규): D-1 임박 3건(10-06) — `윈도우 오피스365 라이센스 구입`(#442)·`그랜터 -> Clobe 로 재무 서비스 이전`(#461)·`교수님이 준 엑셀 자료 검토`(#462). D-2 1건(10-07 `회계 현명 미지급금 출처 보완` #443)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 10-02 마감 7건(`IR자료 디벨롭`·`[Toffer] 익절/손절 시나리오 개선`·`글로벌 화장품 인증·규제 가이드 정리`·`Plaud 미팅 노션 연동`·`협력업체 가격 시나리오 기록 정리`·`브이엘-아이젤-브랜업 계약서 여부`·`[에나지크] 오더별 공유용 타임라인 및 폴더`)이 **전건 미착수 상태로 D-3 경과**. 에나지크 국가별 오버레이 회신 병목도 변동 없음 — 주간(10-06 월) 착수 시급.

## [2026-10-06] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 98건 동기화 완료

## [2026-10-06] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- **회차 특이사항:** 월요일 구간 — **Slack 업무 신규 메시지 0건 · 신규 파일 0건**(28시간 창 = 10-05 05:00 이후). 실질 변동은 DB(-1건 + 마감일 1건 재조정)뿐이며, Slack 업무 대화는 10-01 이후 5일째 정지 상태.
- DB 동기화: 프로젝트 13개 · **업무 98건**(10-05 99건 대비 **-1**) — 진행중 97(98→-1) · 지연 1 · 프로젝트 미지정 93(94→-1). 목록 제거 1건은 프로젝트 미지정 '진행중' 업무(완료/삭제 구분 불가, API 목록에서 항목명 소실).
  - **마감 재조정 1건:** `[Toffer] 익절/손절 시나리오 개선` 마감 **10-02 → 10-07**(09-27 이후 첫 갱신) → 경과 목록 탈출, D-1로 이동
  - 상태: 진행중 97 · 지연 1(`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **40일 경과**)
  - 마감 경과 **78건**(10-05 80건 대비 **-2** = Toffer 재조정 1 + 미지정 업무 제거 1), **D-0 3건**(10-06: `윈도우 오피스365 라이센스 구입`·`그랜터 -> Clobe 로 재무 서비스 이전`·`교수님이 준 엑셀 자료 검토`), D-1 2건(10-07: Toffer · `회계 현명 미지급금 출처 보완`), D-2 0건, `due_at` 미입력 5건
  - TSonaX/Toffer 4건 — Toffer만 마감 재조정, 나머지 3건 갱신 없음(+32·+46·+46일 경과)
- Slack 스캔: 활성 15개 채널 전량 조회 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **업무 신규 메시지 0건 / 신규 파일 0건** (28시간 창 = 10-05 05:00 이후, 월요일 무활동)
  - 168시간 창 누적 메시지 15건 · 파일 8건 — 전량 09-28~10-02 기수집분 / 스레드 답글 0건 / errors 2(`not_in_channel`만)
  - 채널별 최신: `헤르메스` 10-04 23:47(봇 게이트웨이 알림, 비업무) · 업무 대화 최신 `뷰티-프로젝트` 10-01 16:47(에나지크 시장확대 XLSX) — 5일째 변동 없음
  - 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치
- Canvas/북마크: Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50)** · 북마크 0건
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 10-06 기준 전면 갱신(Toffer 10-02 → 10-07 재조정·경과 탈출, `[TSonaX] 1차 배포` **6회 연속 부재**, 경과 3건 +32~+46일, 전사 경과 78건, 연혁 10-06 항목 추가)
  - `channels/index.md` — 헤더 10-06, ID 매핑표 10-06 재확인(15/15), 브랜업-공지사항 경고 **15주차**, 10-06 스캔 결과 노트 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **15주차** 갱신, updated 10-06
  - `index.md` — TSonaX 요약 갱신(6회 연속 부재·Toffer D-1·경과 78건·업무 98건), 미등재 섹션 20주차 노트
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 98건 — 날짜 롤링 + -1건 반영)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 20주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(15주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-06 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(7주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-06 **6회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요
- 미조치(신규): **D-0 임박 3건(10-06 오늘 마감)** — `윈도우 오피스365 라이센스 구입`·`그랜터 -> Clobe 로 재무 서비스 이전`·`교수님이 준 엑셀 자료 검토`. D-1 2건(10-07) — `[Toffer] 익절/손절 시나리오 개선`·`회계 현명 미지급금 출처 보완`
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 10-02 마감 6건(`IR자료 디벨롭`·`글로벌 화장품 인증·규제 가이드 정리`·`Plaud 미팅 노션 연동`·`협력업체 가격 시나리오 기록 정리`·`브이엘-아이젤-브랜업 계약서 여부`·`[에나지크] 오더별 공유용 타임라인 및 폴더`)이 **D-4 경과·전건 미착수**. 에나지크 국가별 오버레이 회신 병목도 변동 없음. Slack 업무 대화 5일 무활동 — 주간 착수 여부 점검이 필요하다.


## [2026-10-07] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료

## [2026-10-07] ingest | Daily Slack + Dashboard Wiki 요약 (크론)
- **회차 특이사항:** 화요일 구간 — **Slack 업무 신규 메시지 0건 · 신규 파일 0건**(28시간 창 = 10-06 01:01 이후). 실질 변동은 DB(+2건 · 마감 재조정 4건)뿐이며, **Slack 업무 대화는 10-01 이후 6일째 정지** 상태. DB 신규 3건 중 1건은 보안 테스트용 레코드(`test_escalate_probe_20261006`).
- DB 동기화: 프로젝트 13개 · **업무 100건**(10-06 98건 대비 **+2**) — 진행중 99(97→+2) · 지연 1 · 프로젝트 미지정 95(93→+2). 전 건 미지정.
  - **신규 3건:** `미술관 멤버쉽 조사`(이향석, 마감 10-06 — 등록 즉시 경과) · `카니발 법인승계 스왑처리`(이상원·이향석, 마감 10-16) · `test_escalate_probe_20261006`(전경표, due 없음, 본문 "security test record - will be deleted")
  - **목록 제거 1건:** `윈도우 오피스365 라이센스 구입`(10-06 마감, 완료/삭제 구분 불가)
  - **마감 재조정 4건(전건 연기):** `브랜업 상표등록`(10-09 → 10-16) · `브랜업 퇴직금 제도 조사`·`[Web] cosmetic-review 서비스 추가`·`브랜업캠퍼스 신규 법인설립`(10-09 → 10-30)
  - 상태: 진행중 99 · 지연 1(`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **41일 경과**)
  - 마감 경과 **81건**(10-06 78건 대비 **+3** = 10-06 도래 잔여 2건 + 신규 10-06 마감 1건), **D-0 2건**(10-07: `[Toffer] 익절/손절 시나리오 개선`·`회계 현명 미지급금 출처 보완`), **D-1 0건**, D-2 1건(10-09 `[KCL] 10월 정기보고서 제출`), D-3 2건(10-10 `BOM 정리 작업`·`보드 바퀴 찾기`), `due_at` 미입력 6건
  - TSonaX/Toffer 4건 — Toffer **D-0(오늘 마감)**, 나머지 3건 갱신 없음(+33·+47·+47일 경과)
- Slack 스캔: 활성 15개 채널 `conversations.history` 전량 조회 (아카이브 0, 봇 미참여 1 — 제품-기획-제작 `not_in_channel`)
  - **업무 신규 메시지 0건 / 신규 파일 0건** (28시간 창 = 10-06 01:01 KST 이후)
  - 168시간 창 누적 메시지 **6건**·파일 1건 — 전량 09-30~10-04 기수집분(`뷰티-프로젝트` 09-30 03:23·10-01 16:47 · `브랜업-전체` 10-01 09:49·09:50 · `wiki` 10-02 18:04 · `헤르메스` 10-04 23:47×2)
  - 업무 대화 기준 최신 `뷰티-프로젝트` 10-01 16:47(에나지크 시장확대 XLSX) — **6일째 변동 없음**. 스레드 답글 0건. API errors 0
  - 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치(전량 실측 재확인)
- Canvas/북마크: Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 0건
- Wiki 페이지 갱신:
  - `concepts/tsonax.md` — 10-07 기준 전면 갱신(Toffer D-0, `[TSonaX] 1차 배포` **7회 연속 부재**, 경과 3건 +33~+47일, 전사 경과 81건, 신규 3·제거 1·재조정 4건, 연혁 10-07 항목 추가, 테스트 레코드 주의 항목 신설)
  - `channels/index.md` — 헤더 10-07, ID 매핑표 10-07 재확인(15/15), 브랜업-공지사항 경고 **16주차**, 10-07 스캔 결과 노트 추가
  - `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **16주차** 갱신, updated 10-07
  - `index.md` — TSonaX 요약 갱신(7회 연속 부재·Toffer D-0·경과 81건·업무 100건), 미등재 섹션 21주차 노트
  - `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 100건 — 날짜 롤링 + 신규 3·제거 1)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)
- 네비게이션 갱신: README.md 재생성
- 미조치(사용자 판단 필요, 21주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(16주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-07 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(8주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-07 **7회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2 항목)
- 미조치(신규): **D-0 오늘 마감 2건(10-07)** — `[Toffer] 익절/손절 시나리오 개선`·`회계 현명 미지급금 출처 보완`(전건 이향석). D-2 1건(10-09 `[KCL] 10월 정기보고서 제출`)
- 미조치(신규): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 실 업무 집계(100건)에 포함 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 10-02 마감 6건(`IR자료 디벨롭`·`글로벌 화장품 인증·규제 가이드 정리`·`Plaud 미팅 노션 연동`·`협력업체 가격 시나리오 기록 정리`·`브이엘-아이젤-브랜업 계약서 여부`·`[에나지크] 오더별 공유용 타임라인 및 폴더`)이 **D-5 경과·전건 미착수**. 신규 경과 3건(10-06 마감)도 미착수. 에나지크 국가별 오버레이 회신 병목 변동 없음. **Slack 업무 대화 6일 정지 — 10월 둘째 주 착수 여부 점검 필요.**

## [2026-10-08] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 99건 동기화 완료

## [2026-10-08] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **99건** (10-07 100건 → **-1**)
- 상태별: 진행중 98 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, 42일 경과)
- **신규 1건**: `칸젠 민감 피부자극테스트` (강경철·이향석·최유미, 마감 2026-10-23, 10-07 14:23 등록)
- **목록 제거 2건**: `미술관 멤버쉽 조사` (10-06 등록 → 다음 날 제거) · `그랜터 -> Clobe 로 재무 서비스 이전` (전건 10-06 마감, 완료/삭제 구분 불가)
- 마감 재조정·상태 변경·담당자 변경: **0건**
- 전사 마감 경과 **81건 유지** (10-07 도래 2건 유입 +2 · 제거 2건 -2 = 순변동 0) · **D-0 0건** · D-1 1건(`[KCL] 10월 정기보고서 제출`, 10-09) · D-2 2건(10-10 `BOM 정리 작업`·`시간될 때 보드에 부착할 고급스러운 바퀴 찾기`)
- `[TSonaX] 1차 배포` **8회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` 마감 10-07 도래 후 **미착수 → +1일 경과**

### STEP 2 — Slack 채널 스캔 (활성 15개, 28시간 창 = 10-07 01:02 이후)
- **업무 신규 메시지 2건 / 신규 파일 3건** — **6일 정지 후 재개**
- `코스메틱-본부` 10-07 09:44 — **구매확인서 3건 공유**(브랜업 ↔ 브랜업코러스 영세율 적용 서류): P42EK261000018(미국 수출건 13,427 EA, 구매일 09-30, USD 537,080, 확인일 10-06) · P42EK260900025(캐나다 4,282 EA, 08-27, USD 171,280) · P42EK260900018(캐나다 512 EA, 08-19, USD 20,480). 합계 **18,221 EA / USD 728,840** (단가 USD 40/EA, (주)신한은행 용인동백지점, 대외무역법 제18조)
  - PDF 2건 모두 **텍스트 레이어 없음**(벡터 렌더링, 폰트·텍스트 연산자 0) → 140dpi 렌더 이미지 판독으로 값 기록 (수량·금액 재확인 권장)
- `design-backup` 10-07 21:34 — **`ir.ai`** (IR 자료 일러스트레이터 원본, 20.7MB) / 텍스트 없음, 등록 사실만 기록
- 168시간 창 누적 메시지 8건·파일 3건 — 잔여분은 10-01~10-04 기수록. 스레드 답글 0건. API errors 0
- 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치(전량 실측 재확인) · 봇 미참여 1건(`제품-기획-제작`)

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 0건 · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-07** 섹션 추가: 구매확인서 3건(영세율 서류) + 발주 관점 해석(미국 13,427 EA vs 09-10 확정 13,417세트 = 동일 건 단정 보류). Source channels: [[channels/코스메틱-본부]]

### STEP 3 — Wiki 페이지 생성·갱신
- **신규**: `entities/브랜업코러스.md` — (유)브랜업코러스 (경기 용인 기흥구 동백중앙로 191 디811, 최기남, 4018161096) / 구매확인서 3건 표 / 영세율 구조 해석(`confidence: medium`, 관계사 역할 미확정 명시)
- **신규 raw**: `raw/articles/branup-corus-purchase-confirmations-20261007.md` (+ PDF 2건 동봉, sha256 `dcb917c2…`) — lint 해시 규칙 재계산 일치 확인
- `channels/코스메틱-본부.md` — 2026-10-07 활동·의사결정 추가, related_entities에 브랜업코러스, updated 10-08
- `channels/branup-design-backup.md` — 2026-10-07 `ir.ai` 등록 추가, updated 10-08
- `channels/브랜업-공지사항.md` — 채널 미확인 경고 **17주차** 갱신
- `concepts/tsonax.md` — 10-08 기준 전면 갱신(1차 배포 8회 연속 부재, Toffer +1일 경과, 08-21·09-04 3건 +34~+48일, 경과 81건·D-0 0건, 업무 99건, 연혁 10-08 항목 추가)
- `concepts/branup-finance.md` — 2026-10-07 영세율 서류 항목 추가 + 브랜업코러스 링크 (updated 08-28 → 10-08)
- `channels/index.md` — 헤더 10-08, ID 매핑표 10-08 재확인(15/15), 퀵뷰 2행 갱신(코스메틱-본부·design-backup), 브랜업-공지사항 경고 17주차, 10-08 스캔 결과 노트
- `index.md` — 브랜업코러스 등재(entity 17), TSonaX 요약 갱신(8회 부재·Toffer +1일·경과 81건·업무 99건), 총 페이지 57 → **58**, 미등재 섹션 22주차 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 99건)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- **신규(22주차)**: `entities/브랜업코러스` — 브랜업과의 지분·역할 관계(관계사/수출 대행 여부) 및 미국 수출건 13,427 EA ↔ 13,417세트 동일 여부 확인 필요
- 미조치(22주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(17주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-08 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(9주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-08 **8회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2 항목)
- 미조치(신규): `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(+1일). 착수 또는 마감 재조정 필요
- 미조치(신규): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(99건)에 잔존 → **삭제 필요**(실질 업무 98건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 10-02 마감 6건 **D-6 경과·전건 미착수**. 10-06 마감 `교수님이 준 엑셀 자료 검토` 미착수. 에나지크 국가별 오버레이 회신 병목 변동 없음. **Slack 업무 대화는 10-07 재개**(구매확인서·ir.ai) — 다만 신규 업무 등록은 1건뿐.

## [2026-10-09] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료

## [2026-10-09] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **100건** (10-08 99건 → **+1**)
- 상태별: 진행중 99 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **43일** 경과)
- **신규 3건** (전건 10-08 등록·강경철): `CDRI 계약서 확인`(10-08 09:37, 마감 10-08) · `미국 물량 스페인어 병기 여부 확인`(10-08 10:02, 마감 10-08) · `BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것`(10-08 16:59, 마감 10-15)
- **목록 제거 2건 — 전건 '완료' 실측 확인(`closed_at` 10-08 09:38)**: `CNF 문의 루트 파악 및 메일 작성`(10-01 마감, **7일 지연 후 완료**) · `교수님이 준 엑셀 자료 검토`(10-06 마감, 2일 지연 후 완료)
- **마감 재조정 4건(전건 연기·10-02 마감분 후속)**: `IR자료 디벨롭`(10-02 → 10-08) · `Plaud 미팅 노션 연동`(10-02 → 10-13) · `협력업체 가격 시나리오 기록 정리`·`[에나지크] 오더별 공유용 타임라인 및 폴더`(10-02 → 10-14). 담당자·상태 변경 0건
- 전사 마감 경과 **78건**(10-08 81건 → **-3** = 재조정 3건 경과 탈출 · 완료 2건 제거 · 신규 경과 2건 유입) · **D-0 1건**(`[KCL] 10월 정기보고서 제출`, 10-09) · D-1 2건(10-10 `BOM 정리 작업`·`시간될 때 보드에 부착할 고급스러운 바퀴 찾기`) · D-2·D-3 0건 · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **9회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` 마감 10-07 도래 후 **+2일 경과**

### STEP 2 — Slack 채널 스캔 (활성 15개, 28시간 창 = 10-08 01:00 이후)
- **업무 신규 메시지 2건 / 신규 파일 2건** — 전량 `design-backup`
- `design-backup` 10-08 09:33 — **에나지크 로고 인서트 PET 트레이 샘플 도면 3종**: `브랜업 [26-0140][샘플도면 3종]-게또바시.pdf` (1페이지 1.36MB, Illustrator 25.0(Windows) 벡터 도면, 파일 ID `F0C7LLNG058`). 판독 사양: 외형 **165.60 × 144.50 mm** · 높이 **40 / 65 / 53 mm** · 재질 **PET 0.5 T** · 경사 92° · 도면 작성일 2026-10-07. 중앙 포켓 **Enagic 로고** + 좌우 포켓 2개 + 하단 `Enagic`·`PET` 인서트 구조 — 발주·연출용 트레이(대상 제품·프로젝트 **미확정**). 원본·판독: `raw/articles/branup-enagic-pet-tray-drawings-20261007.md` (PDF·렌더 PNG 보관, sha256 `4f321b6b…`)
- `design-backup` 10-08 17:11 — **`ir.ai`** (IR 자료 일러스트레이터 원본, 20,885,762 bytes ≈ 20.7MB, 파일 ID `F0C7J8GNA9K`). `.ai` 텍스트 추출 불가 → 등록 사실만 기록
  - ⚠️ **10-08 회차 기록 정정:** 해당 회차는 `ir.ai`를 10-07 21:34 · 20,726,326 bytes로 기록했으나 실측은 **10-08 17:11 · 20,885,762 bytes**. 채널 이력(최근 20건)에 `ir.ai` 메시지는 1건뿐 → **회차 시각 환산 오류**로 보이나 용량 차이(159KB)로 동일 파일 여부는 단정 보류
- 168시간 창 누적 메시지 **6건**(`코스메틱-본부` 1 · `design-backup` 2 · `헤르메스` 2 · `wiki` 1) — 잔여분은 10-02~10-07 기수록. 스레드 답글 0건. API errors 0
- 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 15/15 일치(전량 실측 재확인) · 봇 미참여 1건(`제품-기획-제작`)

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 0건 · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-08** 섹션 추가: 에나지크 로고 인서트 PET 트레이 샘플 도면 3종(발주·연출용 트레이 사양 입력값, 대상 제품 미확정). Source channels: [[channels/branup-design-backup]]

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 raw**: `raw/articles/branup-enagic-pet-tray-drawings-20261007.md` (+ `slack_design-backup_F0C7LLNG058.pdf`, `raw/assets/branup-enagic-pet-tray-drawings-20261007.png`) — lint 해시 규칙 재계산 일치 확인
- `channels/branup-design-backup.md` — 2026-10-08 활동 2건 추가(트레이 도면·`ir.ai`) + 10-07 항목 정정 주석, updated 10-09
- `channels/브랜업-공지사항.md` — 채널 미확인 경고 **18주차** 갱신, updated 10-09
- `concepts/tsonax.md` — 10-09 기준 전면 갱신(1차 배포 9회 연속 부재, Toffer +2일 경과, 08-21·08-21·09-04 3건 +35~+49일, 경과 78건·D-0 1건, 업무 100건, 연혁 10-09 항목 추가)
- `channels/index.md` — 헤더 10-09, ID 매핑표 10-09 재확인(15/15), 퀵뷰 2행 갱신(design-backup·브랜업-공지사항), 10-09 스캔 결과 노트
- `index.md` — TSonaX 요약 갱신(9회 부재·Toffer +2일·경과 78건·업무 100건), 총 페이지 58 유지, 미등재 섹션 23주차 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 100건)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- **신규(23주차)**: `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정, 도면에 제품명 없음)
- **정정(23주차)**: 10-08 회차 `ir.ai` 기록 시각·용량 오류 → 10-08 17:11 · 20,885,762 bytes로 정정
- 미조치(23주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(18주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-09 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-09 **9회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2 항목)
- 미조치(신규): `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+2일**). 착수 또는 마감 재조정 필요
- 미조치(신규): `CDRI 계약서 확인`·`미국 물량 스페인어 병기 여부 확인` — 10-08 등록·마감 10-08로 **등록 즉시 경과**. 마감 재조정 필요
- 미조치(신규): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(100건)에 잔존 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 비고: 10-02 마감 6건 정리 — 재조정 4건(`IR자료 디벨롭`→10-08 · `Plaud 미팅 노션 연동`→10-13 · `협력업체 가격 시나리오 기록 정리`·`[에나지크] 오더별 공유용 타임라인`→10-14) · 완료 1건(`글로벌 화장품 인증·규제 가이드 정리`, 10-05) · 잔여 경과 1건(`브이엘-아이젤-브랜업 계약서 여부`, +7일). 10-06 마감 `교수님이 준 엑셀 자료 검토`는 10-08 완료. 에나지크 국가별 오버레이 회신 병목 변동 없음.

## [2026-10-09] lint | 2026-10-09 위키 린트 — broken 1 · orphan 6 · 미등재 7 · tag 위반 1(task 예외)
- 대상: ~/wiki · 콘텐츠 페이지 58 · 전체 .md 115 · raw .md 50 · taxonomy 태그 74종
- Broken wikilink 1건: raw/articles/weekly-strategy-2026-07-3w.md 본문의 "통합주간전략 자동화" 제목-링크(슬러그 concepts/integrated-weekly-strategy 아님) — raw 불변이므로 조치 보류
- 고아 6건 / index 미등재 7건 — 변동 없음(23주차, 일일 카운터 기준), _archive/ 이동 사용자 승인 대기. concepts/project-status는 inbound 링크 있어 고아 아님
- Ghost page 0 · frontmatter 결손 0 · stale(90일+) 0 · 태그 위반 1종(`task` — concepts/task-status 전용, 아카이브 이동 시 자동 해소)
- Oversized(200줄+) 3건: entities/브랜업-신입직원-온보딩-매뉴얼(802줄) · channels/코스메틱-본부(267줄) · entities/enagic-usa(234줄)
- log.md 135 entries (<500, 로테이션 불필요)
- raw sha256 불일치 19건 — 전량 "해시 산출 규칙 불일치"(소스 변경 아님): 4건 소스 바이너리(PDF/XLSX) 해시 규칙 · 15건 레거시 ingest 규칙(전건 단일 ingest 커밋 확인). 비-hex placeholder 18건(drift 감지 불가)
- Slack #wiki(C0BGCQS22BF) 리포트 게시 + GitHub push

## [2026-10-10] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료

## [2026-10-10] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **100건** (10-09 100건 → **변동 없음**)
- 상태별: 진행중 99 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **44일** 경과)
- **신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0** — 가장 최근 갱신은 10-08 16:59(`BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것`)
- 전사 마감 경과 **79건**(10-09 78건 → **+1** = 10-09 마감 `[KCL] 10월 정기보고서 제출` 도래 유입, 그 외 변동 0) · **D-0 2건**(10-10 `BOM 정리 작업`·`시간될 때 보드에 부착할 고급스러운 바퀴 찾기`, 전건 강경철) · D-1 0 · D-2 0 · D-3 1건(10-13 `Plaud 미팅 노션 연동`) · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **10회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` 마감 10-07 도래 후 **+3일 경과**
- ⚠️ 참고: API `/api/tasks/list`의 마감 필드는 `due_at`(ISO datetime) — 10-09 스냅샷(`due`)과 키가 달라 단순 비교 시 전건 '마감 미정'으로 오판되므로 키 정규화 후 비교함

### STEP 2 — Slack 채널 스캔 (활성 15개, 28시간 창 = 10-08 22:00 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**(금요일 무활동)
- 28시간 창 내 유일한 신규 메시지는 `wiki` 10-09 18:01 자체 발행 린트 리포트(봇 산출·비업무) 1건
- **업무 대화 기준 최신 = `design-backup` 10-08 17:11**(`ir.ai`)로 1일째 변동 없음 (그 직전 10-08 09:33 트레이 샘플 도면)
- 168시간 창 누적 메시지 **6건**(`코스메틱-본부` 1 · `design-backup` 2 · `헤르메스` 2 · `wiki` 1 — 전량 10-02~10-08 기수록분)
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → 프로젝트 페이지에 추가할 활동 없음 (`projects/` 13건은 DB sync로 자동 갱신)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 58 유지)
- `concepts/tsonax.md` — 10-10 기준 갱신(1차 배포 **10회 연속 부재**, Toffer **+3일**, 경과 79건, D-0 2건, 업무 100건 변동 없음, 지연 1건 44일 경과)
- `channels/index.md` — 헤더 10-10, ID 매핑표 10-10 재확인(15/15), 10-10 스캔 결과 노트 추가, 퀵뷰 브랜업-공지사항 19주차
- `channels/브랜업-공지사항.md` — 채널 미확인 경고 **19주차** 갱신, updated 10-10
- `index.md` — TSonaX 요약 갱신(10회 부재·Toffer +3일·경과 79건·업무 100건 변동 없음), 브랜업-대시보드-현황 업무 100건(10-10), 총 페이지 58 유지, 미등재 섹션 24주차 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 100건)
- 링크 무결성: 신규·갱신 페이지 wikilink 전량 해석 확인 (broken 0건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(24주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(19주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-10 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-10 **10회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2)
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+3일**). 착수 또는 마감 재조정 필요
- 미조치: `CDRI 계약서 확인`·`미국 물량 스페인어 병기 여부 확인` — 10-08 등록·마감 10-08로 **등록 즉시 경과**. 마감 재조정 필요
- 미조치: 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(100건)에 잔존 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정, 도면에 제품명 없음)
- 비고: 업무 대화가 10-08 이후 2일간 정지 상태(주말 진입). 10-02 마감 정리분(재조정 4·완료 1) 및 10-08 등록 3건 중 2건의 등록 즉시 경과가 미해소로 남아 있음.

## [2026-10-11] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료

## [2026-10-11] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **100건** (10-10 100건 → **변동 없음**)
- 상태별: 진행중 99 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **45일** 경과)
- **신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0** — 가장 최근 갱신은 여전히 10-08 16:59(`BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것`)로 **3일째 정지**
- 전사 마감 경과 **81건**(10-10 79건 → **+2** = 10-10 마감 `BOM 정리 작업`·`시간될 때 보드에 부착할 고급스러운 바퀴 찾기` 도래 유입, 그 외 변동 0) · **D-0 0건** · D-1 0 · **D-2 1건**(10-13 `Plaud 미팅 노션 연동`) · **D-3 2건**(10-14 `협력업체 가격 시나리오 기록 정리`·`[에나지크] 오더별 공유용 타임라인 및 폴더`) · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **11회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` 마감 10-07 도래 후 **+4일 경과**
- ⚠️ 참고: 10-10 스냅샷이 API raw 스키마(`due_at` 키)로 저장돼 단순 비교 시 전건 '마감 미정'으로 오판 → 키 정규화(`due_at`/`due`) 후 비교함

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-10 03:01 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**(토요일 무활동) — 26시간 창 내 신규 메시지 자체가 0건
- **업무 대화 기준 최신 = `design-backup` 10-08 17:11**(`ir.ai`)로 **3일째 변동 없음** (그 직전 10-08 09:33 트레이 샘플 도면)
- 168시간 창 누적 메시지 **6건**(`코스메틱-본부` 1 · `design-backup` 2 · `헤르메스` 2 · `wiki` 1 — 전량 10-02~10-08 기수록분, 신규 0)
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → 프로젝트 페이지에 추가할 활동 없음 (`projects/` 13건은 DB sync로 자동 갱신)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 58 유지)
- `concepts/tsonax.md` — 10-11 기준 갱신(1차 배포 **11회 연속 부재**, Toffer **+4일**, 경과 81건, D-0 0건·D-2 1건·D-3 2건, 업무 100건 변동 없음, 지연 1건 45일 경과)
- `channels/index.md` — 헤더 10-11, ID 매핑표 10-11 재확인(15/15), 10-11 스캔 결과 노트 추가, 퀵뷰 브랜업-공지사항 20주차
- `channels/브랜업-공지사항.md` — 채널 미확인 경고 **20주차** 갱신, updated 10-11
- `index.md` — TSonaX 요약 갱신(11회 부재·Toffer +4일·경과 81건·업무 100건 변동 없음), 브랜업-대시보드-현황 업무 100건(10-11), 총 페이지 58 유지, 미등재 섹션 25주차 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 100건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(25주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(20주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-11 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-11 **11회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2)
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+4일**). 착수 또는 마감 재조정 필요
- 미조치: `CDRI 계약서 확인`·`미국 물량 스페인어 병기 여부 확인` — 10-08 등록·마감 10-08로 **등록 즉시 경과**. 마감 재조정 필요
- 미조치: 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(100건)에 잔존 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정, 도면에 제품명 없음)
- 비고: 업무 대화가 10-08 이후 **3일간 정지**(주말). DB도 10-08 16:59 이후 갱신 0건 — 10-08 등록 3건 중 2건의 등록 즉시 경과가 미해소로 남아 있음.

## [2026-10-12] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료


## [2026-10-12] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **100건** (10-11 100건 → **변동 없음**)
- 상태별: 진행중 99 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **46일** 경과)
- **신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0** — 최근 갱신은 여전히 10-08 16:59(`BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것`)로 **4일째 정지**
- 전사 마감 경과 **81건 유지**(10-11 81건 → 변동 없음: 10-11 도래분 0건) · **D-0 0건** · D-1 1건(10-13 `Plaud 미팅 노션 연동`) · D-2 2건(10-14) · D-3 2건(10-15 `카톤 개선 작업`·`BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것`) · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **12회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` 마감 10-07 도래 후 **+5일 경과** / TSonaX 브랜치 신규 커밋 **10-03 이후 0건**(최신 `1bd3acc` 10-02 — `git fetch origin` 후 실측)

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-11 03:03 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**(일요일 무활동)
- 업무 대화 기준 최신 = `design-backup` 10-08 17:11(`ir.ai`)로 **4일째 변동 없음**
- 168시간 창 누적 메시지 **4건**(`코스메틱-본부` 1 · `design-backup` 2 · `wiki` 1 — 전량 10-07~10-09 기수록, 신규 0). 창 슬라이드로 `헤르메스` 10-04 23:47 봇 알림 2건이 창 밖 이탈(6 → 4건)
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → 프로젝트 페이지에 추가할 활동 없음 (`projects/` 13건은 DB sync로 자동 갱신, `## 📋 최근 활동` 섹션 보존 확인)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 58 유지)
- `concepts/tsonax.md` — 10-12 기준 갱신(1차 배포 **12회 연속 부재**, Toffer **+5일**, 경과 81건 유지, D-0 0건·D-1 1건·D-2 2건·D-3 2건, 업무 100건 변동 없음, 지연 1건 46일 경과, 개발 브랜치 신규 커밋 0건). 리스크 섹션의 "GitHub 저장소 접근 불가 → 커밋 이력 미추적" 서술을 **bare 클론 실측 추적** 방식으로 정정
- `channels/index.md` — 헤더 10-12, ID 매핑표 10-12 재확인(15/15), 10-12 스캔 결과 노트 추가, 퀵뷰 브랜업-공지사항 21주차
- `channels/브랜업-공지사항.md` — 채널 미확인 경고 **21주차** 갱신, updated 10-12
- `index.md` — TSonaX 요약 갱신(12회 부재 · Toffer +5일 · 경과 81건 · 업무 100건 변동 없음 · 브랜치 커밋 0), 총 페이지 58 유지, 미등재 섹션 **26주차** 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 100건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(26주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(21주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-12 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-12 **12회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2)
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+5일**). 착수 또는 마감 재조정 필요
- 미조치: `CDRI 계약서 확인`·`미국 물량 스페인어 병기 여부 확인` — 10-08 등록·마감 10-08로 **등록 즉시 경과(4일)**. 마감 재조정 필요
- 미조치: 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(100건)에 잔존 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정, 도면에 제품명 없음)
- 비고: 업무 대화가 10-08 이후 **4일간 정지**(10-09~10-12). DB도 10-08 16:59 이후 갱신 0건 — 10-08 등록 3건 중 2건의 등록 즉시 경과가 미해소로 남아 있음.

## [2026-10-13] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 100건 동기화 완료

## [2026-10-13] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **100건** (10-12와 총계 동일, **내용 변동 7건**)
- **신규 2건**(전건 강경철): `바코드 준비`(10-12 등록, 마감 10-15) · `CDRI 계약서 검토 및 진행`(10-08 등록, 마감 10-15 — 목록 반영은 10-13)
- **목록 제거 2건**: `CDRI 계약서 확인`(마감 10-08) · `미국 물량 스페인어 병기 여부 확인`(마감 10-08) — 전건 **등록 즉시 경과 상태로 제거, 완료/삭제 구분 불가**(후속 `CDRI 계약서 검토 및 진행` 신규 등록 → 맥락상 재등록 추정, 단정 보류)
- **마감 재조정 3건**: `[KCL] 10월 정기보고서 제출`(10-09 → 10-13) · `BOM 정리 작업`(10-10 → 10-15) · `IR자료 디벨롭`(10-08 → 10-12). 담당자·상태 변경 0건
- 최근 갱신 **10-12 13:49**(`브랜업 상표등록`) — 10-08 16:59 이후 **4일 정지 해제**
- 상태별: 진행중 99 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **47일** 경과)
- 전사 마감 경과 81 → **77건**(-4 = 목록 제거 2건 + 재조정 2건의 경과 탈출) · **D-0 2건**(10-13 `Plaud 미팅 노션 연동`·`[KCL] 10월 정기보고서 제출`) · D-1 2건(10-14) · D-2 5건(10-15) · D-3 3건(10-16) · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **13회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` **+6일 경과** / 개발 브랜치(`feat/minichart-tf-series-reconnect`) 신규 커밋 **10-03 이후 0건**(최신 `1bd3acc` 2026-10-02 22:44 — `git fetch origin <branch>` 후 `FETCH_HEAD` 실측)

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-12 03:00 KST 이후)
- **업무 신규 메시지 3건 / 신규 파일 2건** — 전건 `design-backup`(10-08 이후 **4일 정지 후 재개**)
  - 10-12 10:16 **`0720-2.jpg`** — KANGEN BEAUTÉ 3-Step 제품 비주얼(2717×2339 / 300 dpi / 5.4MB). `First Light Essence`(STEP I)·`Vital Rich Cream`(STEP II)·`Crystal Ampoule Cream`(STEP III) 50ml — **라벨 STEP 표기·설명문 확정 반영**
  - 10-12 11:27 **`[JNJ] [명판 2차] 수령일 10월 12일`** — JNJ 자석&명판 후가공 **2차 샘플 수령**(7월 '샘플 지연' 이후 진전)
  - 10-12 11:39 **`ir-백업.ai`** — 브랜업 IR 덱(20,582,638 bytes, 실체 **PDF 9p/960×540pt**). **텍스트 레이어 정상 → 내용 판독 성공**: p3 팀(CEO 이상원·CSO 최유미·이사 이영진·한상훈) · p4 기업개요(설립 2025-06-24, 자본금 1천만원)·연혁·**누적 재무 30억 / 총이익 9억 / 30%** · p6 시장기회 차트 4종(한국 화장품 수출 CAGR 12.0%, K뷰티 수출국 172개국(2024)→202개국(2025), 퍼스널케어 위탁제조 CAGR 8.4%) · p7 포지셔닝(브랜드 매출총이익률 69%). **`03 BUSINESS MODEL` 섹션 본문 미작성(디바이더만)·p9 공백 → 작업 중 버전**
- 168시간 창 누적 메시지 **7건**(`코스메틱-본부` 1 · `design-backup` 5 · `wiki` 1 — 잔여분은 10-07~10-09 기수록) · 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 신규 채널 0건 · rename 이벤트 0건 · ID 매핑 **15/15 일치**

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-12 활동 2건 추가**: JNJ 자석&명판 2차 샘플 수령(발주·후가공 리드타임 입력값) · KANGEN BEAUTÉ 3-Step 제품 비주얼(라벨·문안 대조 기준)
- KANGEN BEAUTÉ 제품 비주얼은 SNS/마케팅 소재로 보이나 **대상 프로젝트 미확정** → `projects/칸겐뷰티_sns_운영.md` 연결은 **보류**(사용자 확인 항목 등재)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 1건**: `concepts/브랜업-ir-202610.md` — 브랜업 IR 자료(2026.10) 정리(덱 구성·핵심 수치·포지셔닝·진행 이력·미비점). index 등재 완료 → 콘텐츠 페이지 수 58 → **59**
- **신규 raw 원본 1건**: `raw/articles/branup-ir-deck-20261012.md` — IR 덱 9p 페이지별 판독 + 원문 수치 표 + 본문 `sha256`(스킬 규칙 `split('---',2)[2].lstrip('\n')` 준수, 재계산 검증 완료)
- `entities/branup-org-chart.md` — IR 덱 기준 경영진 보강: CSO **최유미** · 이사 **이영진** 박사 · 이사 **한상훈** 박사 추가, 이상원 대표 이력(前 LS증권)
- `concepts/branup-finance.md` — IR 덱 누적 재무(30억/9억/30%) 표에 추가 + `ir` 태그 (추정치 주의 명시)
- `entities/join-n-joy.md` — **자석&명판 2차 샘플 수령(10-12)** 항목 추가
- `channels/branup-design-backup.md` — 2026-10-12 활동 3건(IR 덱·제품 비주얼·명판 2차) + 관련 위키 섹션·frontmatter 갱신
- `concepts/tsonax.md` — 10-13 기준 전면 갱신(13회 부재 · Toffer +6일 · 경과 77건 · D-0 2건 · 정지 해제 · 브랜치 커밋 0건 · 경과 탈출 2건)
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **22주차** 갱신
- `SCHEMA.md` — Tag Taxonomy에 **`ir`** 등재

### STEP 4 — 네비게이션
- `index.md`(총 59페이지 · TSonaX 요약 갱신 · IR 페이지 등재 · 미등재 섹션 27주차 노트)
- `channels/index.md`(헤더 10-13 · ID 매핑 15/15 재확인 · 퀵뷰 design-backup/공지사항 갱신 · 10-13 스캔 결과 노트)
- `projects/index.md` (DB sync 자동 갱신) · `README.md` 재생성(`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(27주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(22주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-13 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-13 **13회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2)
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+6일**). 착수 또는 마감 재조정 필요
- **미조치(신규): `IR자료 디벨롭`(강경철, 마감 10-12)** — 10-12 IR 덱 백업본 업로드로 **작업 진행 정황**이 확인됐으나 대시보드 업무는 여전히 '진행중'·경과(+1일). 완료 처리 또는 후속(`03 BUSINESS MODEL` 작성) 등록 판단 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(100건)에 잔존 → **삭제 필요**(실질 업무 99건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요
- **미조치(신규): IR 덱 편집 오류 2건** — p4 연혁 `2025.5 캐나다 수출 확대 계약`이 설립일(2025-06-24)보다 앞선 시점으로 표기 · p1 표지 `A/B/C/D` 템플릿 미치환 → 디자인팀 원본 수정 필요
- **미조치(신규): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼** — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: DB·Slack 활동이 **10-12 재개**(4일 정지 해제). Slack 업무 대화 최신 = 10-12 11:39(`ir-백업.ai`).

## [2026-10-14] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 101건 동기화 완료

## [2026-10-14] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **101건** (10-13 100건 대비 **+1**)
- **신규 2건**(전건 강경철·10-13 등록): `CDRI 멤버십 미팅 조율`(10-13 16:55, 마감 10-14 — 등록 익일 도래) · `PLAUD 지출증빙 확인`(10-13 18:21, 마감 10-16)
- **목록 제거 1건**: `IR자료 디벨롭`(강경철, 마감 10-12) — 10-12 IR 덱(`ir-백업.ai`) 업로드 정황과 맞물려 **완료 추정**이나 `closed_at` 미확인 → 완료/삭제 구분 불가
- **마감 재조정 1건**: `Plaud 미팅 노션 연동`(10-13 → **10-20**, 경과 진입 차단). 담당자·상태 변경 0건
- 최근 갱신 **10-13 18:21**(`Plaud 미팅 노션 연동`) — 10-12 재개 흐름 유지, 10-13에도 신규 2건 등록(전건 강경철)
- 상태별: 진행중 100 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **48일** 경과)
- 전사 마감 경과 **77건 유지**(+1 = 10-13 도래 `[KCL] 10월 정기보고서 제출` 경과 유입 · -1 = `IR자료 디벨롭` 목록 제거) · **D-0 3건**(10-14 `협력업체 가격 시나리오 기록 정리`·`[에나지크] 오더별 공유용 타임라인 및 폴더`·`CDRI 멤버십 미팅 조율`) · D-1 5건(10-15) · D-2 4건(10-16) · D-3 0건(10-17) · `due_at` 미입력 6건
- `[TSonaX] 1차 배포` **14회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` **+7일 경과** / 개발 브랜치(`feat/minichart-tf-series-reconnect`) 신규 커밋 **10-03 이후 0건**(최신 `1bd3acc` 2026-10-02 22:44 — `git fetch --all` rc=0 실측)

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-13 03:03 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건** (화요일 무활동 — `design-backup` 재개 다음 날 다시 정지)
- 업무 대화 기준 최신 = `design-backup` 10-12 11:39(`ir-백업.ai`)로 **2일째 변동 없음**
- 168시간 창 누적 메시지 **7건**(`코스메틱-본부` 1 · `design-backup` 5 · `wiki` 1) — **7건 전량 개별 확인, 전부 10-07~10-12 기수록분(신규 0)**
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → 프로젝트 페이지에 추가할 활동 없음 (`projects/` 13건은 DB sync로 자동 갱신, `## 📋 최근 활동` 섹션 보존 확인)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 **59 유지**)
- `concepts/tsonax.md` — 10-14 기준 갱신(14회 부재 · Toffer +7일 · 경과 77건 유지 · D-0 3건 · 업무 101건 · 지연 1건 48일 경과 · 개발 브랜치 신규 커밋 0건)
- `concepts/브랜업-ir-202610.md` — `IR자료 디벨롭` **10-14 대시보드 목록 제거(완료 추정)** 본문·진행 이력에 반영
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **23주차** 갱신, updated 10-14
- `channels/index.md` — 헤더 10-14 · ID 매핑표 10-14 재확인(15/15) · 10-14 스캔 결과 노트 추가 · 퀵뷰 공지사항 23주차
- `index.md` — TSonaX 요약 갱신(14회 부재 · Toffer +7일 · 경과 77건 유지 · 업무 101건) · IR 요약에 목록 제거 반영 · 총 페이지 59 유지 · 미등재 섹션 **28주차** 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 101건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(28주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(23주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-14 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-14 **14회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2)
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+7일**). 착수 또는 마감 재조정 필요
- **미조치(갱신): `IR자료 디벨롭`(강경철, 마감 10-12)** — 10-14 대시보드 목록에서 **제거**(완료 추정). `03 BUSINESS MODEL` 섹션 작성 등 **후속 업무 등록 여부 판단 필요**
- **미조치(신규): `[KCL] 10월 정기보고서 제출`(이향석, 마감 10-13)** — 10-13 도래 후 미완료, 10-14 경과 유입. 완료 처리 또는 마감 재조정 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(101건)에 잔존 → **삭제 필요**(실질 업무 100건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정, 도면에 제품명 없음)
- 미조치: IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치: `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 10-13은 **DB에서만 활동**(신규 2건 등록·갱신 2건)하고 Slack 업무 대화는 0건. 업무 대화 최신은 10-12 11:39(`ir-백업.ai`).

## [2026-10-15] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 103건 동기화 완료

## [2026-10-15] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **103건** (10-14 101건 대비 **+2**)
- **신규 4건**(전건 10-14 등록): `투권인 카드 비용 -> 브랜업 비용`(이향석, 마감 10-14 — 등록 당일 도래) · `향료 5KG 발주`(강경철, 마감 10-14) · `투권인 급여 -> 대표님 채무 상환 처리`(이향석, 마감 10-15) · `[SKILL] 클로드용 IR pdf 검수리포트 스킬 개발`(이향석, 마감 10-15)
- **목록 제거 2건**(전건 경과 상태였음): `회계 현명 미지급금 출처 보완`(이향석, 마감 10-07) · `[KCL] 10월 정기보고서 제출`(이향석, 마감 10-13 — **전일 미조치 항목 → 완료 처리 추정**, `closed_at` 미확인)
- **마감 재조정 1건**: `[에나지크] 오더별 공유용 타임라인 및 폴더`(10-14 → 10-15). 담당자·상태 변경 0건
- 최근 갱신 **10-14 19:54**(`투권인 카드 비용 -> 브랜업 비용`) — 10-14 하루 동안 **신규 4건 등록·5건 갱신**
- 상태별: 진행중 102 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **49일** 경과)
- 전사 마감 경과 77 → **79건**(+4 = 10-14 도래 잔여 2건(`협력업체 가격 시나리오 기록 정리`·`CDRI 멤버십 미팅 조율`) + 신규 등록 당일 경과 2건(`투권인 카드 비용`·`향료 5KG 발주`) · -2 = 목록 제거 2건) · **D-0 8건**(10-15) · D-1 4건(10-16) · D-2·D-3 0건 · `due_at` 미입력 6건 · **60일 이상 경과 43건**
- ⚠️ 경과 카운트 정합: 10-14 회차 로그의 '77건'은 as-of 10-14, 스냅샷(`dash_tasks_20261014.json`)을 as-of 10-14로 재계산해도 77건으로 일치함(10-15 기준 재계산 시 80건 → 제거 2건 반영 79건).
- `[TSonaX] 1차 배포` **15회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` **+8일 경과** / ✅ **개발 브랜치 신규 커밋 1건** — `c6041cd`(2026-10-14 12:47, 33 files · +3,101/−63), **10-03~10-13 11일 공백 종료**(로컬 bare 클론 `~/.hermes/cache/scratch/tsonax.git`에서 `git ls-remote origin`·`git fetch origin feat/minichart-tf-series-reconnect` 실측)

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-14 03:00 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건** (수요일 무활동 — 10-13에 이어 **2일 연속 0건**)
- 업무 대화 기준 최신 = `design-backup` 10-12 11:39(`ir-백업.ai`)로 **3일째 변동 없음**
- 168시간 창 누적 메시지 **6건**(`design-backup` 5 · `wiki` 1) — **6건 전량 개별 타임스탬프 확인, 전부 기수록분(신규 0)**: 트레이 도면(10-08 09:33)·`ir.ai`(10-08 17:11)·`0720-2.jpg`(10-12 10:16)·JNJ 명판 2차(10-12 11:27)·`ir-백업.ai`(10-12 11:39)·wiki 린트 리포트(10-09 18:01). ※ 창이 하루 밀리며 `코스메틱-본부` 10-07 구매확인서 1건이 168h 밖으로 이탈(7 → 6건)
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → 프로젝트 페이지에 추가할 활동 없음 (`projects/` 13건은 DB sync로 자동 갱신, `## 📋 최근 활동` 섹션 보유 7건 보존 확인)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 **59 유지**)
- `concepts/tsonax.md` — 10-15 기준 전면 갱신(**개발 브랜치 커밋 재개 `c6041cd`** · 15회 부재 · Toffer +8일 · 경과 79건 · D-0 8건 · 업무 103건 · 지연 1건 49일 · 60일 이상 경과 43건)
- `concepts/브랜업-ir-202610.md` — 10-14 신규 업무 `[SKILL] 클로드용 IR pdf 검수리포트 스킬 개발`을 진행 이력·재확인 항목에 반영, updated 10-15
- `concepts/branup-finance.md` — 10-14 재무·정산 신규 업무 2건(`투권인 카드 비용 -> 브랜업 비용`·`투권인 급여 -> 대표님 채무 상환 처리`) + `향료 5KG 발주` 기록, updated 10-15
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **24주차** 갱신
- `channels/index.md` — 헤더 10-15 · ID 매핑표 10-15 재확인(15/15) · 10-15 스캔 결과 노트 추가 · 퀵뷰 공지사항 24주차
- `index.md` — TSonaX 요약 갱신(커밋 재개 · 15회 부재 · Toffer +8일 · 경과 79건 · 업무 103건) · IR 요약에 신규 스킬 업무 반영 · 대시보드 현황 업무 103건 · 총 페이지 59 유지 · 미등재 섹션 **29주차** 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 103건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(29주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(24주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-15 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-15 **15회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2). ※ 개발 커밋은 10-14 재개됨
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+8일**). 착수 또는 마감 재조정 필요
- **미조치 해소: `[KCL] 10월 정기보고서 제출`(이향석, 마감 10-13)** — 10-15 대시보드 목록에서 제거(**완료 추정**)
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(103건)에 잔존 → **삭제 필요**(실질 업무 102건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정)
- 미조치: IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- **미조치(신규): 재무 관련 업무 2건(`투권인 카드 비용`·`투권인 급여`) — 제목 외 내용 확인 불가, 처리 방향(장부 반영·채무 상환) 확인 필요**
- 미조치: `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: **10-14는 DB 활동만 활발**(신규 4건 등록·5건 갱신), Slack 업무 대화는 10-12 11:39 이후 **3일째 0건**. DB 103건 중 경과 79건·60일 이상 경과 43건으로 적체가 지속되는 가운데, 최우선 항목(TSonaX 마일스톤 #2)에서 **11일 만의 개발 커밋**이 확인됨.

## [2026-10-16] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-10-16] daily | 브랜업 일일 크론 (DB + Slack + Wiki)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행: 프로젝트 **13개** · 업무 **102건** (10-15 103건 대비 **-1**)
- **신규 등록 0건** (10-09 이후 첫 신규 0건 회차 — 10-13·10-14·10-15는 연속 신규 등록이 있었다)
- **목록 제거 1건**: `향료 5KG 발주`(강경철, 마감 10-14, 최종 갱신 10-14 17:22) — **완료/삭제 구분 불가**(`closed_at` 미확인)
- **마감 재조정 3건**(전건 경과 탈출): `CDRI 멤버십 미팅 조율`(10-14 → 10-15) · `바코드 준비`(10-15 → **10-16**, D-0으로 이동) · `카톤 개선 작업`(10-15 → **10-30**)
- **담당자 표기 정리 5건**: `협력업체들 계약서 정리 안된업체 늦어도 주초까진 마무리`·`[에나지크] 캐나다 라벨 리뷰 방안`·`신규 라인업 기획서`·`카탈로그 감리`·`packing list 줄리어스 대표님꼐 전달` — 담당 `미정` → 공백 처리
- 최근 갱신 **10-15 09:55**(`카톤 개선 작업`) — 10-15 하루 동안 재조정 3건·담당자 표기 정리 5건
- 상태별: 진행중 101 · 지연 1 (`아이젤 계약서 조영길이사와 사전 조율`, 마감 08-27, **50일** 경과)
- 전사 마감 경과 **84건**(as-of 10-16. 10-15 스냅샷을 as-of 10-16으로 재계산하면 87건 → **경과 해소 3건 · 신규 유입 0건**) · **D-0 5건**(10-16 `카니발 법인승계 스왑처리`·`브랜업 상표등록`·`[OTC] 미국 선크림 인증 절차 조사`·`바코드 준비`·`PLAUD 지출증빙 확인`) · D-1·D-2·D-3 **0건**(10-17~10-19) · `due_at` 미입력 6건 · **60일 이상 경과 43건**
- 프로젝트 미지정(orphan) 업무 **97건** / 102건
- `[TSonaX] 1차 배포` **16회 연속 부재** / `[Toffer] 익절/손절 시나리오 개선` **+9일 경과** / 개발 브랜치(`feat/minichart-tf-series-reconnect`) **신규 커밋 0건** — tip `c6041cd`(2026-10-14 12:47, 33 files · +3,101/−63) 유지, **재개 후 2일째**(`git ls-remote origin` + `git fetch origin <branch>` 실측, master tip `e42d7c9`)
- ⚠️ 스냅샷 키 정합: 10-15 스냅샷은 정규화형(`due`/`created`/`updated`), 10-16 수집분은 API raw(`due_at`/`created_at`)여서 **정규화 후 비교**함(단순 비교 시 전건 '마감 미정' 오판). 정규화본을 `dash_tasks_20261016.json`으로 저장.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-09 05:00 KST 이후 / 26시간 보고 창 = 10-15 03:00 KST 이후)
- **업무 신규 메시지 1건 / 신규 파일 1건** — `design-backup` **10-15 22:32 `인쇄문안 변경의 건.pdf`**(디자인팀 `U0BFDSSR9PZ`, 857,907 bytes, 파일 ID `F0C9BFTMMMH`, 메시지 텍스트 없음) → **3일 정지 후 재개**
- 파일 분석(다운로드·전량 추출): 실체 **PDF 1.6 · 4페이지 · 842×595 pt(A4 가로) · `Adobe Illustrator 30.8 (Macintosh)`**, 문서 생성 10-15 20:35 · 수정 21:29. 텍스트 레이어 **910자 전량 추출** + 130 dpi 렌더 육안 확인. 내용 = **KANGEN BEAUTÉ TIMELESS RADIANCE 3-Step 용기 라벨 「인쇄문안」 검수본** — p1 미국(라벨 평면) · p2 캐나다(라벨 평면) · p3 미국(용기 입체) · p4 캐나다(용기 입체). 문안: STEP I `First Light Essence / pH-Balanced Hydration / Essence Éclat Premier · Hydratation au pH équilibré` · STEP II `Vital Rich Cream`(캐나다판 `Crème Riche Vitale`) · STEP III `Crystal Ampoule Cream / Precious Barrier Seal / Crème Ampoule Cristalline · Précieux voile protecteur`. **캐나다판은 스텝 표기에 `ÉTAPE I·II·III` 병기**, 미국판에도 STEP I·III 불어 제품명 병기
- ⚠️ **변경 전/후 diff 불가** — 활성 15개 채널 이력 200건을 `인쇄문안·문안·인쇄·라벨`로 검색했으나 본 파일이 **유일한 인쇄문안 본**(직전 버전 없음). **미국판 불어 병기가 이번 변경분인지 사용자 확인 필요**
- 168시간 창 누적 메시지 **5건**(`design-backup` 4 · `wiki` 1) — 잔여 4건(10-12 `0720-2.jpg`·JNJ 명판 2차·`ir-백업.ai`, 10-09 wiki 린트 리포트)은 전량 기수록분(신규 0). ※ 창이 하루 밀려 `코스메틱-본부` 10-07 구매확인서가 168h 밖
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(전량 실측 재확인) · 아카이브 0개

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **15건(신규 0건, 최신 10-01 09:50 `tabbed_canvas_updated`)** · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-15 활동 추가**: 「인쇄문안 변경의 건」 검수본 등록(발주 관점 = 인쇄 직전 문안 검수 입력값, 07-15 대표 지시에 따른 **변경 확정 전 인쇄 전송 보류 리스크**) + 연계 DB 변동(`카톤 개선 작업` 10-30 연기 · `바코드 준비` 10-16 연기 · `향료 5KG 발주` 목록 제거)
- 그 외 프로젝트 페이지 — 신규 Slack 대화·파일 없음 (`projects/` 13건은 DB sync로 자동 갱신, `## 📋 최근 활동` 섹션 보존 확인)

### STEP 3 — Wiki 페이지 생성·갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 1건** (콘텐츠 페이지 수 **59 유지**)
- `raw/articles/branup-enagic-print-copy-change-20261015.md` — **신규 판독 노트**(4p 페이지 구성·스텝별 문안표·변경 판단 주의). raw frontmatter `sha256: 8312687b97a561db4ead5abc591b97197094233a11dafbc82bfa60d3398c27bf`(본문 기준, 재계산 일치 확인)
- `channels/branup-design-backup.md` — 10-15 활동 섹션 신규(파일 상세·3스텝 문안·diff 불가 경고), 관련 위키 페이지에 판독 노트 링크 추가, updated 10-16
- `projects/에나지크_발주_시뮬레이터.md` — 10-15 활동 섹션 추가
- `concepts/에나지크-글로벌-물류-패키징-전략.md` — 「후속 조치 (2026-10-15) — 용기 인쇄문안 변경 검수본」 섹션 추가(국가별 스텝 표기·불어 병기 표), 미해결 항목에 diff 불가 추가, sources·updated 갱신
- `entities/enagic-usa.md` — 「용기 인쇄문안 변경 검수본 (2026-10-15)」 하위 섹션 추가, sources·updated 갱신
- `concepts/tsonax.md` — 10-16 기준 전면 갱신(**신규 등록 0건** · 경과 84건 · D-0 5건 · 업무 102건 · 지연 1건 50일 경과 · 60일 이상 43건 · 개발 커밋 재개 후 2일째 0건 · 16회 부재 · Toffer +9일)
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **25주차** 갱신
- `channels/index.md` — 헤더 10-16 · 퀵뷰 design-backup 행 갱신 · 공지사항 25주차 · ID 매핑 10-16 재확인(15/15) · 10-16 스캔 결과 노트 추가
- `index.md` — TSonaX 요약 갱신(개발 커밋 2일째 0건 · 16회 부재 · Toffer +9일 · 경과 84건 · 업무 102건) · 미등재 섹션 **30주차** 노트
- `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` (DB sync 자동 갱신, 업무 102건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(30주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(25주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-16 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-16 **16회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2). ※ 개발 커밋은 10-14 재개 후 10-15·10-16 **2일째 신규 0건**
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+9일**). 착수 또는 마감 재조정 필요
- **미조치(신규): `인쇄문안 변경의 건`(10-15, design-backup) — 직전 버전 부재로 변경점 확정 불가.** ① 미국판 불어 제품명 병기가 이번 변경분인지 ② 인쇄 전송 일정이 어디까지 진행됐는지(07-15 대표 지시: 문안 변경 시 후가공 사양·감리 일정·원본 파일 다수 수정) 확인 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(102건)에 잔존 → **삭제 필요**(실질 업무 101건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 표기 `미정`/공백 혼재 5건 — 담당 배정 필요
- 미조치(23주차): `design-backup` 트레이 샘플 도면 3종 — 대상 제품·프로젝트 확인 필요(에나지크 연출 트레이 추정)
- 미조치: IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치: 재무 관련 업무 2건(`투권인 카드 비용`·`투권인 급여`) — 제목 외 내용 확인 불가, 처리 방향 확인 필요
- 미조치: `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 10-15는 **Slack(파일 1건) + DB(재조정 3·담당자 정리 5)** 양쪽에 활동이 있었고, **10-16 DB는 신규 등록 0건으로 전환**됐다. 경과 84건·60일 이상 경과 43건 적체가 지속되며, TSonaX 개발은 10-14 재개(`c6041cd`) 후 2일째 신규 커밋이 없다.

## [2026-10-16] lint | 2026-10-16 위키 린트 (주간 헬스체크, #wiki 게시)
- 대상: ~/wiki · 콘텐츠 페이지 **59** · 전체 .md **118**(raw 52) · taxonomy 태그 74종
- Broken wikilink: 콘텐츠/인덱스 범위 **0건**. raw/ 1건(`raw/articles/weekly-strategy-2026-07-3w` → 「통합주간전략 자동화」, 슬러그 아님 · raw 불변 → 조치 보류, 10-09분과 동일) · log.md 이력 서술 3건은 실제 링크 아님(backtick 표기 권장)
- 고아 **6건** / index 미등재 **7건** — 변동 없음(**30주차**, 일일 카운터 기준), `_archive/` 이동 사용자 승인 대기. `concepts/project-status`는 inbound 링크 있어 고아 아님
- Ghost page 0 · frontmatter 결손 0(채널 페이지 `sources` 예외 규칙 적용) · 태그 위반 1종(`task` — `concepts/task-status` 전용, 아카이브 시 자동 해소)
- **stale(90일+) 7건 신규 발생**(10-09 0건): `concepts/slack-adoption`(7/14, 94일) · `concepts/product-liability-insurance`·`concepts/export-voucher`·`entities/aizel-contract`·`entities/aizel-contract-review-request`(7/15, 93일) · `concepts/integrated-weekly-strategy`·`entities/peachy`(7/16, 92일)
- Oversized(200줄+) **4건**(10-09 3건 → +1): 브랜업-신입직원-온보딩-매뉴얼 802줄 · 코스메틱-본부 267줄 · enagic-usa 240줄 · **branup-design-backup 205줄(신규** — 10-15 인쇄문안 활동 추가분)
- log.md 150 entries / 2,826줄 (<500, 로테이션 불필요)
- raw sha256: 소스 바이너리(PDF/XLSX) 해시 규칙 4건(정상) · 레거시 ingest 규칙 15건(`git log` 실측 **전건 단일 ingest 커밋** 확인 → 소스 변경 아님, 해시 산출 규칙 불일치) · 비-hex placeholder 18건(drift 감지 불가)
- type 감사: entity 16 · concept 18 · channel 11 · project 13 · summary 1 — `entities/aizel-contract-review-request`가 `type: summary`(entities/ 배치 재검토 권장)
- index.md 「Total pages: 59」 = 실제 59 일치 · 채널맵 11개 페이지 / Slack 활성 15개 · 채널 ID 매핑 15/15
- 자동 수정 0건 · 사용자 판단 대기 3건(고아·미등재 아카이브 승인 · raw 레거시 해시 규칙 · 7월 페이지 stale 재확인)
- Slack #wiki(C0BGCQS22BF) 리포트 게시 + GitHub push

## [2026-10-17] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-10-17] daily | 브랜업 일일 위키 동기화 (31주차, 일일 카운터 기준)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행 → 프로젝트 **13개** · 업무 **102건** · 17개 파일 갱신(projects/ 13 + projects/index.md + concepts/브랜업-대시보드-현황.md + index.md). `## 📋 최근 활동` 섹션 보존 확인.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-10 05:00 KST 이후 / 26시간 보고 창 = 10-16 03:00 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건** (금요일 무활동 — 10-16 하루 업무 대화 없음)
- 26시간 창 신규 **2건**: ① `design-backup` **10-16 09:38 Canvas 탭 갱신**(`USLACKBOT`, `tabbed_canvas_updated`, 텍스트·파일 없음) ② `wiki` 10-16 18:02 린트 리포트(봇 자체 산출, 비업무)
- 168시간 창 누적 메시지 **6건** — `design-backup` 5(10-15 22:32 인쇄문안 PDF · 10-16 09:38 Canvas · 10-12 `0720-2.jpg`·JNJ 명판 2차·`ir-백업.ai`) · `wiki` 1(10-16 린트). 10-16 신규 2건 외 **전량 기수록분**. ※ 창이 하루 밀리며 10-09 wiki 린트 리포트가 168h 밖으로 이탈
- 업무 대화 기준 최신 = `design-backup` **10-15 22:32**(`인쇄문안 변경의 건.pdf`) — 10-17 기준 1일째 변동 없음
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건 · 신규 채널 0건 · 아카이브 0개 · ID 매핑 **15/15 일치**
- ⚠️ 직전 인쇄문안 본 부재로 diff 확정 불가 항목(10-15 등록분)은 **미조치 유지**

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **16건**(10-16 15건 → **신규 1건** = `design-backup` 10-16 09:38:38) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)
- 채널별 Canvas 누적: design-backup 13(최신 10-16 09:38, 채널 내 직전 08-27 15:59 → 약 50일 만) · 뷰티-프로젝트 1(09-11) · 브랜업-전체 1(10-01) · 브랜업-계약서 1(07-29)

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-16 활동 추가**: design-backup Canvas 갱신 + 연계 DB 변동(`[에나지크] 오더별 공유용 타임라인 및 폴더` 10-15 → **10-30** 재조정, `BOM 정리 작업` 10-15 → 10-20) — 오더 공유 타임라인 문서 정리가 문안 확정 이후로 이동한 국면으로 정리
- 그 외 프로젝트 페이지 — 신규 Slack 대화·파일 없음(`projects/` 13건은 DB sync로 자동 갱신, `## 📋 최근 활동` 보존 확인)

### STEP 3 — Wiki 페이지 갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 **59 유지**)
- `channels/branup-design-backup.md` — 10-16 Canvas 갱신 섹션 신규(누적 13건·직전 08-27, 인쇄 검수 이력 무영향), updated 10-17
- `projects/에나지크_발주_시뮬레이터.md` — 10-16 활동 섹션 추가
- `concepts/tsonax.md` — 10-17 기준 전면 갱신(**신규 5건** · 경과 **81건** · D-0·D-1 0건 · 업무 102건 · 지연 1건 51일 경과 · 60일 이상 43건 · 개발 커밋 재개 후 **3일째 0건** · **17회 부재** · Toffer **+10일**)
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **26주차** 갱신
- `channels/index.md` — 헤더 10-17 · ID 매핑 10-17 재확인(15/15) · 퀵뷰 design-backup 행(10-16 Canvas 갱신) · 공지사항 26주차 · 10-17 스캔 결과 노트 추가
- `index.md` — TSonaX 요약 갱신(재개 후 3일째 0건 · 17회 부재 · Toffer +10일 · 경과 81건 · 업무 102건) · 미등재 섹션 **31주차** 노트
- `concepts/브랜업-대시보드-현황.md` · `projects/` 13건 · `projects/index.md` — DB sync 자동 갱신(업무 102건)

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(31주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(26주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-17 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(10주차): `[TSonaX] 1차 배포`(#439) 09-29 제거 후 09-30~10-17 **17회 연속 부재** — 완료(배포 성공) 또는 삭제 여부 확인 필요 (최우선 마일스톤 #2). ※ 개발 커밋은 10-14 재개(`c6041cd`) 후 10-15·10-16·10-17 **3일째 신규 0건**
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+10일**). 착수 또는 마감 재조정 필요
- 미조치(계속): `인쇄문안 변경의 건`(10-15, design-backup) — 직전 버전 부재로 변경점 확정 불가. ① 미국판 불어 제품명 병기가 이번 변경분인지 ② 인쇄 전송 일정 진행 여부 확인 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(102건)에 잔존 → **삭제 필요**(실질 업무 101건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 표기 `미정`/공백 혼재 5건 — 담당 배정 필요
- 미조치(계속): IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- **신규 미조치: 10-16 신규 업무 5건 전량 강경철 계정 단독 등록 · 그중 2건이 등록 당일(10-16) 도래** — 마감이 이미 임박·경과한 항목의 등록 패턴이 10-15에 이어 반복 → **등록 시점 마감 설정 관행 점검 필요**
- **신규 미조치: 10-30으로 밀린 3건**(`[에나지크] 오더별 공유용 타임라인 및 폴더`·`BOM 정리 완료 & 라비오 작업 후…`·`카톤 개선 작업`) — 연말 발주·법인 트랙과 일정 충돌 가능성 검토 필요
- 비고: 10-16은 **DB에서 변동 15건**(신규 5·제거 5·재조정 7·우선순위 3)이 발생한 반면 **Slack 업무 대화는 0건**이었다. 경과 81건·60일 이상 경과 43건 적체는 완만히 개선 중이나, TSonaX 개발은 재개 후 3일째 신규 커밋이 없다.

## [2026-10-18] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-10-18] daily | 브랜업 일일 위키 동기화 (32주차, 일일 카운터 기준)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행 → 프로젝트 **13개** · 업무 **102건** · 17개 파일 갱신(`projects/` 13 + `projects/index.md` + `concepts/브랜업-대시보드-현황.md` + `index.md`). `## 📋 최근 활동` 섹션 보존 확인.
- API 실측 변동 **0건**: 신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0. 최근 갱신 **10-16 17:07**(`줄리어스 대표님께 쇼핑백 수량 1/2 확인`) → **2일째 정지**(10-17·10-18 주말).
- 전사 마감 경과 **81건 유지**(10-17·10-18 도래 0건) · D-0 0건(10-18) · D-1 2건(10-19) · D-2 3건(10-20) · `due_at` 미입력 6건 · **60일 이상 경과 44건**(+1 = `에듀코스 계약서 초안 다시 작성`, 마감 08-19 도달) · '지연' 1건(`아이젤 계약서 조영길이사와 사전 조율`, **52일** 경과).

### STEP 1b — ✅ `[TSonaX] 1차 배포` 상태 확정 (본 회차 신규 발견)
- `branup.db` `tasks` 테이블 직접 조회 결과: `[TSonaX] 1차 배포`(이향석, 마감 09-28) = **`status='완료'` · `closed_at=2026-09-29T12:39`**.
- 09-30~10-17 **18회 연속 목록 부재는 완료 처리에 따른 것**(삭제 아님)으로 확인 → 10주차부터 이어진 **미조치 항목 해소**, 최우선 마일스톤 #2 종료.
- ⚠️ 부수 발견: `branup.db` 다운로드본 최근 갱신 **10-15 09:54** vs API **10-16 17:07** → **DB 파일이 API보다 지연**. `branup_tasks_dump.py`(주간보고서)가 이 파일을 사용 → 데이터 지연 위험(신규 미조치 등재).

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-11 05:00 KST 이후 / 26시간 보고 창 = 10-17 03:00 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건** (토요일 무활동 — 26시간 창 0건, 10-17·10-18 이틀 연속)
- 168시간 창 누적 메시지 **6건** — `design-backup` 5(10-15 22:32 `인쇄문안 변경의 건.pdf` · 10-16 09:38 Canvas 갱신 · 10-12 `0720-2.jpg`·JNJ 명판 2차·`ir-백업.ai`) · `wiki` 1(10-16 18:02 린트 리포트) — **전량 기수록분**
- 업무 대화 기준 최신 = `design-backup` **10-15 22:32** → **3일째 변동 없음**
- 스레드 답글 0건 · API errors 0(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건 · 신규 채널 0건 · 아카이브 0개 · ID 매핑 **15/15 일치**

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **16건**(신규 0건) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → **수동 활동 추가 0건**. `projects/` 13건은 DB sync로 자동 갱신(`## 📋 최근 활동` 보존 확인).

### STEP 3 — Wiki 페이지 갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 **59 유지**)
- `concepts/tsonax.md` — 10-18 기준 전면 갱신: 1차 배포 **완료 확정**(헤더·개요·표·연혁·리스크) / 개발 4일째 0건 / Toffer **+11일** / 경과 81건 / 60일+ 44건 / `branup.db` 지연 경고 신규
- `concepts/브랜업-대시보드-현황.md` · `projects/` 13건 · `projects/index.md` — DB sync 자동 갱신(업무 102건)
- `channels/index.md` — 헤더 10-18 · 공지사항 27주차 · 10-18 스캔 결과 노트
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **27주차** 갱신
- `index.md` — TSonaX 요약 갱신(1차 배포 완료 확정) · 미등재 섹션 **32주차** 노트

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(32주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(27주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-18 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- ✅ **해소(32주차): `[TSonaX] 1차 배포` 완료 확정** (DB `closed_at` 2026-09-29 12:39) — 10주차 등재 이후 추적 종료. 09-29 목록 제거는 완료 처리였고 삭제가 아님.
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+11일**). 착수 또는 마감 재조정 필요
- 미조치(계속): `인쇄문안 변경의 건`(10-15, design-backup) — 직전 버전 부재로 변경점 확정 불가. ① 미국판 불어 제품명 병기가 이번 변경분인지 ② 인쇄 전송 일정 진행 여부 확인 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(102건)에 잔존 → **삭제 필요**(실질 업무 101건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 표기 `미정`/공백 혼재 6건 — 담당 배정 필요
- 미조치(계속): IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- **신규 미조치: `branup.db` 다운로드본 지연** (DB 최근 갱신 10-15 09:54 vs API 10-16 17:07) — `branup_tasks_dump.py` 기반 **주간보고서 데이터 정합성 점검 필요**
- 비고: 10-17·10-18은 **DB 변동 0 · Slack 업무 대화 0**의 완전 정지 구간(주말). 경과 81건·60일 이상 44건 적체는 그대로이며, 10-19(월) 재개 여부를 확인한다.

## [2026-10-19] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-10-19] daily | 브랜업 일일 위키 동기화 (33주차, 일일 카운터 기준)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행 → 프로젝트 **13개** · 업무 **102건** · 17개 파일 갱신(`projects/` 13 + `projects/index.md` + `concepts/브랜업-대시보드-현황.md` + `index.md`). `## 📋 최근 활동` 섹션 보존 확인.
- API(`/api/tasks/list`) 실측 변동 **0건**: 신규 0 · 목록 제거 0 · 마감일 변경 0 · 담당자 변경 0 · 상태 변경 0. 최근 갱신 **10-16 17:07**(`줄리어스 대표님께 쇼핑백 수량 1/2 확인`) → **3일째 정지**(10-17·10-18 주말 + 10-19 05:00까지).
- `branup.db`(다운로드 380,928 bytes, mtime 10-19 05:00) **전량 428건 diff**: 신규 0 · 하드삭제 0 · 상태 변경 0 · 마감일/담당자/우선순위 변경 0 → **API 변동 0건과 교차 확인**.
- 전사 마감 경과 **81건 유지**(주말 도래 0건) · **D-0 2건**(10-19 `책임판매업자 등록 요건 및 해야하는 일 정리`·`법인인감증명서 8부 발급`, 전건 강경철) · **D-1 3건**(10-20 `BOM 정리 작업`·`Plaud 미팅 노션 연동`·`CDRI 라벨 검토 의뢰 및 회신 대기`) · `due_at` 미입력 6건 · **60일 이상 경과 44건** · '지연' 1건(`아이젤 계약서 조영길이사와 사전 조율`, **53일** 경과) · 담당자 공백 5건.

### STEP 1b — ⚠️ `branup.db` 지연 격차 확대 (계속 미조치)
- DB 최근 갱신 **10-15 09:54** vs API **10-16 17:07** — 파일은 매일 05:00 새로 내려받지만 **내용은 10-15 상태로 고정**.
- 결과: **DB 활성 109건 vs API 102건**(10-15 이후 완료 처리 7건이 DB 미반영). `branup_tasks_dump.py` 기반 주간보고서가 이 파일을 쓰므로 데이터 지연 위험 지속. 완료/삭제 판별에는 유효, 최신 집계는 API 사용.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-12 05:00 KST 이후 / 26시간 보고 창 = 10-18 03:00 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건** (일요일·월요일 새벽 무활동 — 10-16 이후 **4일 연속 0건**)
- 168시간 창 누적 메시지 **6건** — `design-backup` 5(10-15 22:32 `인쇄문안 변경의 건.pdf` · 10-16 09:38 Canvas 갱신 · 10-12 `0720-2.jpg`·JNJ 명판 2차·`ir-백업.ai`) · `wiki` 1(10-16 18:02 린트 리포트) — **전량 기수록분**
- 168시간 창 파일 **3건** — `인쇄문안 변경의 건.pdf`(857,907 bytes) · `ir-백업.ai`(20,582,638 bytes) · `0720-2.jpg`(5,465,873 bytes) — **전량 기수록분, 신규 0**
- 업무 대화 기준 최신 = `design-backup` **10-15 22:32** → **4일째 변동 없음**
- 스레드 답글 0건 · API errors 1(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건 · 신규 채널 0건 · 아카이브 0개 · ID 매핑 **15/15 일치**

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **16건**(신규 0건) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만)

### STEP 2c — 프로젝트 페이지 활동
- 신규 Slack 대화·파일 0건 → **수동 활동 추가 0건**. `projects/` 13건은 DB sync로 자동 갱신(`## 📋 최근 활동` 보존 확인).

### STEP 3 — Wiki 페이지 갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** (콘텐츠 페이지 수 **59 유지**)
- `concepts/tsonax.md` — 10-19 기준 갱신: 개발 **5일째 0건**(tip `c6041cd` 10-14 12:47 · master `e42d7c9` 09-02) / `[Toffer] 익절/손절` **+12일** / 나머지 3건 +45·+59·+59일 / 경과 81건 · D-0 2건 · 60일+ 44건 / DB 지연 격차(활성 109 vs API 102) 명시
- `concepts/브랜업-대시보드-현황.md` · `projects/` 13건 · `projects/index.md` — DB sync 자동 갱신(업무 102건)
- `channels/index.md` — 헤더 10-19 · 공지사항 28주차 · ID 매핑 10-19 재확인 · 10-19 스캔 결과 노트 추가
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **28주차** 갱신
- `index.md` — TSonaX 요약 갱신 · 미등재 섹션 **33주차** 노트

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`)

### 미조치 (사용자 판단 필요)
- 미조치(33주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(28주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-19 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+12일**). 착수 또는 마감 재조정 필요
- 미조치(계속): `인쇄문안 변경의 건`(10-15, design-backup) — 직전 버전 부재로 변경점 확정 불가. ① 미국판 불어 제품명 병기가 이번 변경분인지 ② 인쇄 전송 일정 진행 여부 확인 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(102건)에 잔존 → **삭제 필요**(실질 업무 101건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 표기 `미정`/공백 혼재 6건 — 담당 배정 필요
- 미조치(계속): IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 미조치(계속): `branup.db` 다운로드본 지연 — DB 10-15 09:54 vs API 10-16 17:07, 활성 109 vs 102. `branup_tasks_dump.py` 기반 **주간보고서 데이터 정합성 점검 필요**
- 비고: 10-17~10-19는 **DB 변동 0 · Slack 업무 대화 0**의 정지 구간(주말 + 월요일 새벽). 10-16 하루 변동 15건 이후 **3일 연속 무변동**이며, 월요일 근무시간대(10-19 09:00 이후) 재개 여부를 확인한다. 경과 81건·60일 이상 44건 적체는 그대로.

## [2026-10-20] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 112건 동기화 완료

## [2026-10-20] daily | 브랜업 일일 위키 동기화 (34주차, 일일 카운터 기준)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행 → 프로젝트 **13개** · 업무 **112건** · 17개 파일 갱신(`projects/` 13 + `projects/index.md` + `concepts/브랜업-대시보드-현황.md` + `index.md`). `## 📋 최근 활동` 섹션 보존 확인.
- API(`/api/tasks/list`) 변동: **신규 10건** · **목록 제거 0건** · **마감 재조정 4건** · 담당자/상태/우선순위 변경 0건. 최근 갱신 **10-20 05:00**(10-16 17:07 이후 **3일 정지 해제**).
- 신규 10건: `[주간업무전략]` **10월 3주(10-19)·10월 4주(10-26)·11월 1주(11-02)·2주(11-09)·3주(11-16)** 5주치 선등록(담당 5인 공통, 10-19 10:44 / 11월 3주만 10-20 05:00) · `1세트 발송 (줄대표님 요청)`(강경철, 10-19) · `세무법인 솔로문, 더원 참고 자료준비`(이향석, 10-19) · `AI 에이전트 업무자동화(AX) 리포트`(이향석, 10-21) · `업무정리 및 AI AX 정리 회의`(5인, 10-21) · `바뀐 용기 문안 포맷 괜찮으면 다른 언어로 번역해서 검토 요청`(강경철, **10-26**).
- 마감 재조정 4건(전건 연기): `줄대표님께 납기 관련 상황 설명 및 확인`·`줄리어스 대표님께 쇼핑백 수량 1/2 확인`(10-16 → 10-19) · `바코드 준비`·`CDRI 멤버십 미팅 조율`(10-16 → 10-20).
- 전사 마감 경과 81 → **84건** · **D-0 5건**(10-20, 전건 강경철: `BOM 정리 작업`·`Plaud 미팅 노션 연동`·`바코드 준비`·`CDRI 멤버십 미팅 조율`·`CDRI 라벨 검토 의뢰 및 회신 대기`) · D-1 2건(10-21 AX 리포트·AX 회의) · D-2 0건 · D-3 4건(10-23) · `due_at` 미입력 6건 · 담당자 공백 5건 · **60일 이상 경과 46건**(+2) · '지연' 1건(`아이젤 계약서 조영길이사와 사전 조율`, **54일**).

### STEP 1b — ✅ `branup.db` 지연 격차 개선
- DB 최근 갱신이 **10-15 09:54 → 10-19 10:40**으로 전진(4일 고정 해소). tasks 총 **439건**(전일 428), 활성 115건(진행중 107·지연 1·보류 7 — API는 보류 미반환).
- 다만 API 대비 **8건 미반영**(10-19 10:44 이후 등록분: 주간업무전략 8건 중 5건·세무법인·AX 리포트·AX 회의) → **약 1일 지연**. `branup_tasks_dump.py`(주간보고서) 사용 시 유의 항목은 유지.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-13 05:00 KST 이후 / 26시간 보고 창 = 10-19 03:00 KST 이후)
- **업무 신규 메시지 1건 / 신규 파일 1건** (10-16 이후 **4일 정지 해제**): `design-backup` **10-19 18:38 `00.261016용기 후면 최신 (3).indd`** — 디자인팀(`U0BFDSSR9PZ`), 7,143,424 bytes, 파일 ID `F0CA8E6RZL6`, 텍스트·스레드 없음.
- 168시간 창 누적 **5건**: `design-backup` 4(10-19 18:38 INDD · 10-19 18:42 Canvas · 10-16 09:38 Canvas · 10-15 22:32 인쇄문안 변경의 건.pdf) · `wiki` 1(10-16 18:02 린트) — **신규 1건 외 전량 기수록분**.
- 스레드 답글 0건 · API errors 1(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **17건**(전일 16건 → **신규 1건** = design-backup 10-19 18:42) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만).

### STEP 2c — 프로젝트 페이지 활동
- `projects/ai_ax_직원_교육.md` — "## 📋 최근 활동" 신설: AX 관련 신규 업무 2건(AX 리포트·AX 회의, 마감 10-21)과 `[주간업무전략]` 5주치 선등록 사실 기록. 두 업무 모두 `project_id` 미지정 → 프로젝트 연결 미완으로 명시.
- 나머지 12개 프로젝트 페이지는 DB sync로 자동 갱신(Slack 신규 대화가 해당 프로젝트에 직접 매핑되는 건 없음).

### STEP 3 — Wiki 페이지 갱신
- **신규 raw 원본 1건**: `raw/articles/branup-용기-후면-문안-indd-20261019.md` (sha256 `58b7e5f0…5874bb6`, 본문 기준 계산·검증 완료. INDD 7.1MB 원본은 git 비대화 방지로 **미보관** — Slack `F0CA8E6RZL6`에서 재취득 가능).
- **신규 콘텐츠 페이지 0건** — 콘텐츠 페이지 수 **59 유지**.
- `channels/branup-design-backup.md` — 10-19 섹션(INDD + Canvas), 디자인 원본 파일 표에 INDD 행 추가, 관련 페이지에 판독 노트 링크. `updated: 2026-10-20`.
- `concepts/에나지크-글로벌-물류-패키징-전략.md` — "후속 조치 (2026-10-19)" 신설(10-15 PDF → 10-19 업무 → INDD 3단 연결), 미해결 항목에 "후면 문안 포맷 확정 → 25개국 번역 검토(10-26)" 추가, sources에 raw 노트 등재.
- `concepts/tsonax.md` — 10-20 기준 갱신: 개발 **6일째 0건**, `[Toffer] 익절/손절` **+13일**, 나머지 +46·+60·+60일, 경과 84건 · D-0 5건 · 60일+ 46건, DB 지연 개선(10-19 10:40) 명시.
- `concepts/브랜업-대시보드-현황.md` · `projects/` 13건 · `projects/index.md` — DB sync 자동 갱신(업무 112건).
- `channels/index.md` — 헤더 10-20 · 공지사항 29주차 · ID 매핑 10-20 재확인 · design-backup 퀵뷰 갱신 · 10-20 스캔 노트 추가.
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **29주차** 갱신.
- `index.md` — TSonaX 요약 갱신 · 미등재 섹션 **34주차** 노트.

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- 미조치(34주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(29주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-20 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+13일**). 착수 또는 마감 재조정 필요
- **신규 미조치**: `00.261016용기 후면 최신 (3).indd` — INDD는 위키에서 판독 불가. ① 10-15 `인쇄문안 변경의 건.pdf`의 수정 반영본인지 ② "후면"이 용기 후면인지 단상자 후면인지 ③ **확정 문안 검토용 PDF 출력 요청** 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(112건)에 잔존 → **삭제 필요**(실질 업무 111건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`·`신규 라인업 기획서`·`카탈로그 감리`·`packing list 줄리어스 대표님꼐 전달`) — 담당 배정 필요
- 미조치(계속): IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 미조치(개선·경감): `branup.db` 다운로드본 지연 — 10-15 09:54 → **10-19 10:40**으로 전진(4일 고정 해소). API 대비 8건 미반영(약 1일 지연) → `branup_tasks_dump.py` 기반 주간보고서는 여전히 API 교차 확인 필요
- 비고: 10-16 이후 4일 정지했던 업무 대화가 10-19 저녁 재개됐고, 같은 시점 DB에 신규 10건(+10)과 주간업무전략 5주치 선등록이 몰렸다. 경과 84건·60일 이상 46건 적체는 오히려 증가 — 마감 재조정 또는 완료 처리가 필요하다.

## [2026-10-21] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 105건 동기화 완료

## [2026-10-21] daily | 브랜업 일일 위키 동기화 (35주차, 일일 카운터 기준)

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` 실행 → 프로젝트 **13개** · 업무 **105건** · 17개 파일 갱신(`projects/` 13 + `projects/index.md` + `concepts/브랜업-대시보드-현황.md` + `index.md`). `## 📋 최근 활동` 섹션 보존 확인.
- API(`/api/tasks/list`) 변동 (vs 10-20 스냅샷 112건): **신규 1건** · **목록 제거 8건** · **마감 재조정 5건** · 담당자/상태/우선순위 변경 0건. 최근 갱신 **10-20 12:34**.
- 신규 1건: `라비오 개발 의뢰`(#497, 강경철, 요약 "3종 개발 의뢰 - mass 버전 / 동일 버전", **마감 10-20 = 등록 당일 도래**, 10-20 12:34 등록, `project_id` 미지정).
- 목록 제거 8건 — **전건 완료/삭제 구분 불가**(`branup.db` 최근 갱신 10-19 10:40 고정 → 7건은 DB상 '진행중', `[주간업무전략] 10월 3주`는 10-19 10:44 등록으로 DB 미수록): `협력업체 가격 시나리오 기록 정리`(강경철, 10-14) · `PLAUD 지출증빙 확인`(강경철, 10-16) · `줄대표님께 납기 관련 상황 설명 및 확인`(강경철, 10-19) · `법인인감증명서 8부 발급`(강경철, 10-19) · `줄리어스 대표님께 쇼핑백 수량 1/2 확인`(강경철, 10-19) · **`[주간업무전략] 10월 3주`**(5인, 10-19 — 기간 종료 추정) · `(추석) 법인 영업/마케팅 효율적으로 아웃소싱 할 방법 리서치`(전경표, 마감 미정, 06-15 이후 방치) · `제이엠솔루션-안목고수 구조 연구분석 및 브랜업의 도입 방안 검토`(전경표, 마감 미정, 05-29 이후 방치).
- 마감 재조정 5건(전건 연기): `1세트 발송 (줄대표님 요청)`(10-19 → **10-20**, 경과 유지) · `책임판매업자 등록 요건 및 해야하는 일 정리`·`CDRI 라벨 검토 의뢰 및 회신 대기`(10-19·10-20 → **10-21**) · `BOM 정리 작업`·`Plaud 미팅 노션 연동`(10-20 → **10-23**).
- 전사 마감 경과 84 → **80건**(as-of 10-21; 10-20 스냅샷 재계산 89건 → 경과 해소 10 = 제거 6 + 재조정 4 · 신규 유입 6 = 10-20 도래 5 + 등록 당일 경과 1) · **D-0 4건**(10-21 `책임판매업자…`·`CDRI 라벨…`·`AI 에이전트 업무자동화(AX) 리포트`·`업무정리 및 AI AX 정리 회의`) · D-1 0건 · **D-2 6건**(10-23) · `due_at` 미입력 4건 · 담당자 공백 5건 · **60일 이상 경과 47건**(+1) · '지연' 1건(`아이젤 계약서 조영길이사와 사전 조율`, **55일**).

### STEP 1b — `branup.db` 재고정 (미조치)
- DB 최근 갱신 **10-19 10:40**(10-20과 동일, **2일째 고정**) → API(10-20 12:34) 대비 약 1.1일 지연. tasks 총 **439건**(전일 428 → +11), 상태 분포 진행중 107 · 완료 324 · 보류 7 · 지연 1.
- 10-20 이후 제거 8건·재조정 5건이 DB 미반영 → `closed_at` 기반 완료/삭제 판별 불가. `branup_tasks_dump.py`(주간보고서) 사용 시 API 교차 확인 필요(미조치 유지).

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-14 05:00 KST 이후 / 26시간 보고 창 = 10-20 03:00 KST 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 메시지 **1건** = `헤르메스` 10-20 17:01 봇 종료 알림(`Hermes is shutting down`) — **비업무**.
- 168시간 창 누적 **6건**: `design-backup` 4(10-19 18:38 INDD · 10-19 18:42 Canvas · 10-16 09:38 Canvas · 10-15 22:32 인쇄문안 PDF) · `wiki` 1(10-16 18:02 린트) · `헤르메스` 1(10-20 17:01) — **신규 0**, 전량 기수록·비업무. 업무 대화 기준 최신은 `design-backup` 10-19 18:38로 **2일째 변동 없음**.
- 스레드 답글 0건 · API errors 1(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **17건**(전일 17건 → **신규 0건**) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만).

### STEP 2c — 프로젝트 페이지 활동
- `projects/ai_ax_직원_교육.md` — "## 📋 최근 활동"에 **2026-10-21** 신설: AX 추진 2건이 오늘 D-0 도래(전사 D-0 4건 중 2건)했으나 **여전히 `project_id` 미지정** → 프로젝트 연결 필요. 대시보드 112 → 105건 감소(신규 1·제거 8) 사실 기록.
- 나머지 12개 프로젝트 페이지는 DB sync로 자동 갱신(Slack 신규 대화 없음).

### STEP 3 — Wiki 페이지 갱신
- **신규 콘텐츠 페이지 0건 · 신규 raw 원본 0건** — 콘텐츠 페이지 수 **59 유지**.
- `concepts/tsonax.md` — 10-21 기준 전면 갱신: 헤더(개발 **7일째** 0건·`[Toffer]` **+14일**·나머지 +47·+61·+61일), 업무 표 경과일, **연혁 10-21 항목 신설**(신규 1·제거 8·재조정 5·경과 80·D-0 4·D-2 6 상세), 리스크 6개 불릿 갱신(경과 80 / 활동 재개 / DB 재고정 / probe 105건→실질 104 / orphan 100 / git 7일째), sources 푸터.
- `concepts/브랜업-대시보드-현황.md` · `projects/` 13건 · `projects/index.md` — DB sync 자동 갱신(업무 105건).
- `channels/index.md` — 헤더 10-21 · ID 매핑 10-21 재확인(15/15) · 공지사항 30주차 · **10-21 스캔 노트 추가**.
- `channels/브랜업-공지사항.md` — 채널 실체 미확인 경고 **30주차** 갱신(`updated: 2026-10-21`).
- `index.md` — TSonaX 요약 갱신 · 미등재 섹션 **35주차** 노트 추가.

### STEP 4 — 네비게이션
- README.md 재생성 (`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- 미조치(35주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(30주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-21 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치: `[Toffer] 익절/손절 시나리오 개선` — 10-07 마감 도래 후 미착수(**+14일**). 착수 또는 마감 재조정 필요
- **신규 미조치**: 목록 제거 8건의 **완료/삭제 판별 불가**(DB 10-19 10:40 고정) — 6건은 10-14~10-19 경과분이라 완료 처리로 보이나, `[주간업무전략] 10월 3주`는 기간 종료, 전경표 2건(추석 아웃소싱 리서치·제이엠솔루션 분석)은 장기 방치 후 정리로 추정. 대시보드에서 실제 상태 확인 필요
- **신규 미조치**: `라비오 개발 의뢰`(#497) — **등록 당일(10-20) 마감**으로 등록 즉시 경과. 마감일 재설정 + `project_id` 연결 필요
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(105건)에 잔존 → **삭제 필요**(실질 업무 104건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 대시보드 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`·`신규 라인업 기획서`·`카탈로그 감리`·`packing list 줄리어스 대표님꼐 전달`) — 담당 배정 필요
- 미조치(계속): IR 덱 편집 오류 2건 (p4 `2025.5 캐나다 수출 확대 계약` 설립일 이전 표기 · p1 `A/B/C/D` 템플릿 미치환) → 디자인팀 원본 수정 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 3-Step 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가. 확정 문안 검토용 PDF 출력 요청 필요
- 비고: 10-20 저녁 이후 업무 대화가 다시 끊겼고(26시간 창 업무 메시지 0건), 대시보드는 **오히려 7건 감소**했다. 경과 80건·60일 이상 47건 적체는 소폭 줄었으나 10-23에 6건이 동시 도래한다(D-2). AX 추진 2건이 오늘 마감(D-0)이므로 결과 확인이 필요하다.

## [2026-10-22] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-10-22] update | 일일 동기화 — Slack 업무 4건(홍콩 스티커·UPC 바코드) · DB 102건(마감일 삭제 10건) · TSonaX 백로그 재편
- 실행: 05:00 KST 크론. 36주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **102건** (전일 105 → **-3**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **신규 8건**: `메타 광고 세팅 (광고계정 연결)`(#498, 전경표, 마감 10-22) · `마케터 채용공고 올리기`(#500, 전경표, 10-22) · `헤어 디바이스 상품제안서 검토`(#499, 전경표, 10-23) · `홍콩 스티커 입고일 및 제품 출고일 안내`(#506, 강경철, 10-23) · **`정부지원사업 매주 확인` 4건**(#501·#502·#503·#504, 전경표, 10-23·10-28·11-04·11-11 — 주 1회 반복 업무 4주치 선등록).
- **목록 제거 11건** — `branup.db` 대조로 **완료 1건 / 미완료 10건** 판별: ① `업무정리 및 AI AX 정리 회의`(10-21) **완료 확정**(`status=완료`, `closed_at=2026-10-21T09:11`) ② 나머지 10건은 DB상 여전히 '진행중'·`closed_at` 없음 → **완료 처리가 아닌 목록 제거**: `신규 직원 직무교육 메뉴얼 작성`(07-30)·`브랜업 메뉴얼 만들기 1주차`(07-31)·`에듀코스 계약서 초안 다시 작성`(08-19)·`[TSonaX] 새로운 DB에 2년치 기본 데이터 넣기`(08-21)·`OEM 협력업체 + 브이엘 세금계산서 요청`(08-28)·`[TSonaX] 종목별 실시간 프로그램 순매수 수량 / 금액 처리`(09-04)·`세무법인 솔로문, 더원 참고 자료준비`(10-19)·`바코드 준비`(10-20)·`1세트 발송 (줄대표님 요청)`(10-20)·`라비오 개발 의뢰`(10-20).
- **필드 변경 12건** — ⚠️ **마감일 삭제 10건**(`due_at → null`): 아이젤 조영길 조율·신우 태평양 자문계획·대표님 에이전트 재설정·**TSonaX 지표추가**·세무현명 자문계약·법인세 시뮬레이션·반기 매출/영업이익·구글시트 발주 챗봇·에나지크 OEM 대금주기·**Toffer 익절/손절**. 연기 2건: `책임판매업자 등록 요건`·`CDRI 라벨 검토 의뢰`(10-21 → 10-23).
- 통계: 마감 경과 80 → **61건**, D-0 **2건**(10-22)·D-1 **11건**(10-23)·D-2/D-3 0건, 60일 이상 47 → **40건**, `due_at` 미입력 4 → **14건**, 담당자 공백 5건, `project_id` 미지정 **97/102**. 최근 갱신 **10-21 18:21**.
- `branup.db`: 최근 갱신 **10-21 09:37**(10-19 10:40 → 전진, **약 1일 지연**), tasks **448건**(전일 439 → +9), 진행중 110 · 완료 330 · 보류 7 · 지연 1. 10-21 09:37 이후 변경분은 미반영.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-15 05:00 이후 / 26시간 보고 창 = 10-21 03:00 이후)
- **업무 신규 메시지 4건 / 신규 파일 3건** — 10-19 이후 2일 정지 해제, **전건 `#코스메틱-본부` 강경철**:
  - 11:33 **`02.바코드.zip`**(512,784 bytes) — 세트박스 **UPC-A 4종**: 50ml US `00884400941015` · 15ml US `00884400732637` · 50ml CA `00884400318831` · 15ml CA `00884400606921` (GS1 US 접두 `0088440`). EPS 4 + PNG 4 + GS1 'My Products & Barcodes' PDF 4 = 16 엔트리.
  - 15:54 **`00_홍콩_스티커문안_261021.pdf`**(4p, 911,637 bytes, PPT→PDF) — STEP 1·2·3 + 세트박스(205×35 mm). **영문 + 번체중문**, `DISTRIBUTED BY Enagic Hong Kong Co., Ltd.`(침사추이 Mira Place Tower A, 132 Nathan Road / +852 2154-0077 / WWW.ENAGIC-ASIA.COM), `MADE IN KOREA`, EXP·LOT 별도, 제조 후 2년·개봉 후 1년. 메시지 "**미국향 1,583세트에 홍콩 스티커 부착**". 텍스트 레이어 추출 성공.
  - 15:59 **수량 정리**(`image.png` 806×386, `뷰티-프로젝트` 크로스포스트) — 미국 오더 15,000 / 출고 **13,417**(전량 해상) / 부족 **1,583** · 캐나다 오더 5,000 / 출고 **4,794**(항공 312·해상 4,282) / 부족 **206** / 샘플 50(9월 10+10월 40) / 잔여 **156** · 미국 **Damaged 168**(샘플 50 차감 시 118). **최종 배정: 홍콩 1,583 · 캐나다 206 · 미국 damage 118**.
  - 16:03 **제품명 통일안** — `브랜드명 + 내용물명 + 스탭 + 국가 + 용량`, 12개 조합(3제품 × US/CA × 50/15ml).
- 168시간 창 누적 메시지 **11건**(코스메틱-본부 4 · 뷰티-프로젝트 1 · 브랜업-전체 1 · design-backup 4 · wiki 1 · 헤르메스 1 — 잔여 7건은 10-15~10-20 기수록·비업무). 스레드 답글 0건 · errors 1(`제품-기획-제작` `not_in_channel` 스킵) · rename 0 · 신규 채널 0 · ID 매핑 **15/15**.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 17 → **신규 1건** = `브랜업-전체` 10-21 17:54 `tabbed_canvas_updated`, USLACKBOT·본문 없음) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c/3 — 프로젝트·채널·엔터티 페이지 갱신
- **신규 콘텐츠 페이지 1건**: `concepts/kangen-뷰티-문안-바코드-표준` — 제품명 규칙 · UPC-A 4종 · 국가별 라벨 문안 세트 · 타임라인 · 미해결 5건. 콘텐츠 페이지 59 → **60**.
- **신규 raw 원본 2건**: `raw/articles/branup-hongkong-sticker-copy-20261021.md`(sha256 `97d25ab8…`) · `raw/articles/branup-upc-barcodes-usa-canada-20261021.md`(sha256 `e6eb7851…`).
- `channels/코스메틱-본부.md` — 2026-10-21 활동 4건 신설, **주요 의사결정 3건**(제품명 규칙·물량 배정·UPC 발급) 추가, **누적 지식 "문안·바코드 관리"** 섹션 신설, 관련 페이지 1건 추가.
- `channels/뷰티-프로젝트.md` — 2026-10-21 수량 정리·홍콩향 전환 기록.
- `channels/branup-전체.md` — 10-21 Canvas 갱신(약 20일 만).
- `projects/에나지크_발주_시뮬레이터.md` — 10-21 잔여 물량 배정·스티커·바코드·제품명 규칙을 발주 관점에서 정리(+연계 DB 변동).
- `entities/enagic-usa.md` — **`Enagic Hong Kong Co., Ltd.` 법인 정보**·홍콩 스티커 문안·UPC 4종 추가.
- `concepts/에나지크-글로벌-물류-패키징-전략.md` — **"실행 1호 — 홍콩 스티커(2026-10-21)"** 섹션 신설(물량표·문안·전략적 의미), 미해결 항목 3건 갱신(업무 등록 해소·홍콩 일정·damaged 처리).
- `concepts/tsonax.md` — 10-22 전면 갱신: 활성 업무 4 → **2건**(마감일 삭제), 목록 제거 2건(완료 미확인), 연혁 10-22 항목 신설, 리스크 8개 불릿 갱신(경과 61건·'기한 없는 진행중'·DB 지연·probe·orphan 97).
- `concepts/브랜업-대시보드-현황.md`·`projects/` 13건 — DB sync 자동 갱신(업무 102건).

### STEP 4 — 네비게이션
- `index.md` 헤더(60페이지) · Concepts 항목 추가 · TSonaX 요약 갱신 · 미등재 섹션 **36주차** 노트.
- `channels/index.md` — 헤더 10-22 · ID 매핑 10-22 재확인(15/15) · 퀵뷰 2건 갱신 · 10-22 스캔 노트.
- `channels/브랜업-공지사항.md` — 실체 미확인 **31주차** 갱신.
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- 미조치(36주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(31주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-22 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- **신규 미조치**: **목록 제거 11건 중 10건이 DB상 '진행중'** — 완료 처리 없이 목록에서만 사라졌다(`[TSonaX]` 2건·`바코드 준비` 포함). 완료 여부 확인 후 상태 정리 필요
- **신규 미조치**: **마감일 일괄 삭제 10건**(TSonaX 2건 포함) — 경과 적체는 줄었으나 **기한 없는 '진행중'** 으로 남았다. 마감 재설정 또는 보류/완료 처리 결정 필요
- **신규 미조치**: `라비오 개발 의뢰`(#497) — 10-20 등록·당일 마감 → **10-22 목록 제거**. 후속 업무 재등록 여부 확인
- 미조치(계속): 대시보드 `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(102건)에 잔존 → **삭제 필요**(실질 업무 101건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`·`신규 라인업 기획서`·`카탈로그 감리`·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가. 확정 문안 검토용 PDF 출력 요청 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- **신규 확인**: `정부지원사업 매주 확인` 4건이 4주치 선등록됨(전경표) — 반복 업무는 시리즈로 관리하는 편이 나은지 검토
- 비고: 이번 회차는 **실물 산출물이 나온 날**이다. 10-01 확정된 "스티커/오버레이 방식"이 홍콩 스티커·UPC 4종·제품명 통일안으로 **실행 단계에 진입**했고, 미국 부족 1,583세트가 홍콩향으로 전환됐다. 반면 대시보드는 마감일 10건 삭제·목록 11건 제거로 경과 건수를 80 → 61건으로 줄였는데, 실질 적체(60일 이상 40건)와 TSonaX 개발 정지(8일째)는 그대로다. 10-23에 11건이 동시 도래한다.

## [2026-10-23] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 101건 동기화 완료

## [2026-10-23] update | 일일 동기화 — 아세안 5개국 규제 신고자료 요청(신규 concept) · DB 101건 · TSonaX 9일째 정지
- 실행: 05:00 KST 크론. 37주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **101건**(전일 102 → **-1**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **신규 1건**: `[컨설팅] 재무/회계 정부지원(80%)`(이향석, **마감 10-28**, `project_id` 미지정).
- **목록 제거 2건 — 완료/삭제 판별 불가**(`branup.db` 최근 갱신 **10-21 09:37** 고정 → 10-22 이후 변경분 미반영): ① `AI 에이전트 업무자동화(AX) 리포트`(이향석, 마감 10-21, 10-19 등록) ② `메타 광고 세팅 (광고계정 연결)`(전경표, 마감 10-22, 10-21 등록). DB상 두 건 모두 `status='진행중'`·`closed_at` 없음.
- **필드 변경 1건**: `마케터 채용공고 올리기`(전경표) 마감 **10-22 → 10-23**(연기).
- 통계: 마감 경과 61 → **60건**, **D-0 12건**(10-23 — 전일 D-1 11건 + 연기 1), D-1·D-2 0건, 60일 이상 **40건 유지**, `due_at` 미입력 14건, 담당자 공백 5건, `project_id` 미지정 **96/101**. 최근 갱신 **10-22 18:14**.
- `branup.db`: 최근 갱신 **10-21 09:37**(10-22와 동일, **2일째 고정**), tasks **448건** 동일, 진행중 110 · 완료 330 · 보류 7 · 지연 1. API 대비 약 1.7일 지연.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-16 05:00 이후 / 26시간 보고 창 = 10-22 03:00 이후)
- **업무 신규 메시지 4건 / 신규 파일 1건** — 전건 `#뷰티-프로젝트` **줄리어스 대표(Julius, U0BGXFND5GQ)**, 10-23 01:56~01:57:
  - **도입문** — "Kangen Beauté의 홍콩·말레이시아·싱가포르·필리핀·태국 시장 진출을 준비… 제조사·원료 공급사와 협의해 자료 보유 여부·제공 가능 범위·확보 일정 회신 요청". 전제: "모든 자료가 각국 신고·통관 시 일괄 제출되는 것은 아니며 최종 범위는 현지 규제 담당자와 확인".
  - **`image.png`**(130,473 bytes) — 「1. 제품별 공통 확보자료」 표 **9행**: 제품 기본정보(공식 제품명·SKU·제형·용도·사용부위·사용방법·내용량·제조국) / **전체 처방(INCI+함량% 정량·복합원료 구성·처방번호·버전)** / 제조사 정보(법인명·실제 제조소, 제조·충전·포장 분리 시 각각) / 포장·라벨(최종 아트워크+수정 가능 원본) / 제조·품질(GMP·공정 개요·규격·시험방법·COA) / 안전성·보존(안전성·미생물·보존력·포장 적합성+사용기간 설정 근거) / **안전성 평가(서명 보고서+평가자 자격)** / **효능 근거** / **PIF**. 마지막 행 `수권 관련 자료`는 이미지 우측 절단.
  - **전성분·정량 처방 분리 요청 + 기밀 처리** — "라벨용 전성분표와 함량 포함 정량 처방은 구분해 확보", "처방 등 기밀자료는 NDA 체결 후 지정된 현지 책임업체·평가자에게 직접 제공하는 방식도 협의".
  - **국가별 우선 확인사항(01:57)** — ①홍콩(우선): 사전 등록이 아닌 **수입자 측 안전성·표시 적합성 검토**(라벨·설명서·전성분·제조사 정보·규격/시험자료·중국어/영어 경고문안·효능 근거) ②말레이시아: 신고+현지 컨설턴트(정량 처방·라벨·제조사 주소 + PIF·안전성평가·GMP·**CNH 수권서**) ③싱가포르: **HSA 신고**(제품정보·전체 처방·제한성분·영어 라벨·PIF) ④필리핀: **CPN+PIF**(서명 안전성평가·수권서, FDA LTO는 현지 파트너) ⑤태국: 신고+**태국어 라벨**+선적별 **LPI**(처방·제조사·수권서·태국어 아트워크). **회신 5항목**: 보유자료·버전 / 제공 가능 여부·방식 / 미비자료·추가 시험 / 업체별 담당자 / 확보 일정·추가 비용.
- 168시간 창 누적 **15건**(뷰티-프로젝트 5 · 코스메틱-본부 4 · design-backup 3 · 브랜업-전체 1 · 헤르메스 1 · wiki 1) — 신규 4건 외 11건은 10-16~10-21 기수록. **스레드 답글 0건**(전건 reply_count 0) · errors 1(`제품-기획-제작` `not_in_channel` 스킵) · 채널 rename 0건(누적 3건은 7월 이력) · 신규 채널 0건 · ID 매핑 **15/15 일치**.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — "## 📋 최근 활동"에 **2026-10-23** 신설: 5개국 규제 요청을 **발주·선적 문서 정합성** 관점으로 정리(제품명·SKU·내용량이 신고자료·라벨·LPI에서 일치해야 함 / 현지 책임업체 미정 → 라벨 확정 전 발주 잠금 / EYESEL 회신이 크리티컬 패스). 연계 DB 변동(D-0 12건) 기록.
- 나머지 12개 프로젝트 페이지는 DB sync 자동 갱신(Slack 신규 대화 없음).

### STEP 3 — Wiki 페이지 갱신
- **신규 콘텐츠 페이지 1건**: `concepts/칸겐보떼-아세안-규제-신고-자료` — 요청 구조 3부 · 공통 9종 표(위키 기록 기준 보유 상태 병기) · 국가별 요구 5개국(10-01 오버레이 분류 대조) · 회신 5항목 · 쟁점/리스크 6건 · 다음 액션 5건 · 미해결 4건. 콘텐츠 페이지 60 → **61**.
- **신규 raw 원본 1건**: `raw/articles/branup-kangenbeaute-asean-regulatory-request-20261023.md`(sha256 `1aaa51e3…`) · **신규 raw asset 1건**: `raw/assets/kangen-asean-regulatory-checklist-20261023.png`(130,473 bytes).
- `channels/뷰티-프로젝트.md` — 2026-10-23 활동 신설(3부 요약·의미), `related_concepts`에 신규 페이지 추가, `updated` 갱신.
- `concepts/에나지크-글로벌-물류-패키징-전략.md` — **"실행 2호 — 5개국 규제 신고자료 요청 (2026-10-23)"** 신설(오버레이는 라벨 비용만 줄였고 인허가 서류 부담은 그대로 / "사전 인쇄 가능"≠"자료 제출 불필요"). 미해결 항목 갱신.
- `concepts/kangen-뷰티-문안-바코드-표준.md` — **§6 5개국 진출 라벨 함의** 신설(국가별 라벨 갭 표: HK 충족 추정 / MY·SG·PH 책임업체 미정 / TH 태국어 아트워크 미제작).
- `entities/enagic-usa.md` — 아세안 5개국 규제 요청 섹션 추가(요청 주체·공통 9종·국가별 요구).
- `concepts/tsonax.md` — 10-23 전면 갱신: 대시보드 101건, 신규 1·제거 2·변경 1, 연혁 10-23 항목, 리스크 갱신(경과 60·D-0 12·60일 40·orphan 96·probe 18일째·DB 2일째 고정), 개발 **9일째 정지**.
- `concepts/브랜업-대시보드-현황.md`·`projects/` 13건 — DB sync 자동 갱신(업무 101건).

### STEP 4 — 네비게이션
- `index.md` 헤더(61페이지 · concepts 20) · Concepts 항목 추가 · TSonaX 요약 갱신 · 미등재 섹션 **37주차** 노트.
- `channels/index.md` — 헤더 10-23 · ID 매핑 10-23 재확인(15/15, 누적 rename 3건 명시) · 퀵뷰 뷰티-프로젝트 갱신 · **10-23 스캔 노트** 추가.
- `channels/브랜업-공지사항.md` — 실체 미확인 **32주차** 갱신.
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- 미조치(37주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(32주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-23 재확인 — 활성 15개 목록에 없음)
- 미조치(2주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- **신규 미조치**: **아세안 5개국 규제자료 요청에 회신 기한이 없다** — 홍콩 우선 출시 일정에서 역산해 마감을 정해야 한다. 대시보드에 대응 업무도 미등록(요청 접수 사실만 위키에 기록)
- **신규 미조치**: **목록 제거 2건 완료 여부 불명** — `AI 에이전트 업무자동화(AX) 리포트`(마감 10-21)·`메타 광고 세팅 (광고계정 연결)`(마감 10-22). `branup.db`가 10-21 09:37에 고정돼 `closed_at` 판별 불가 → 대시보드에서 직접 확인 필요
- **신규 미조치**: **정량 처방·PIF·안전성 평가보고서·GMP 증빙·COA·효능 근거** — 5개국 모두에서 요구되나 위키 기록상 **보유 근거 없음**. EYESEL(제조사) 측 제공 가능 범위 회신이 전체 일정의 크리티컬 패스
- **신규 미조치**: **현지 책임업체(CNH/RP/수입자) 미정** — 말레이시아·싱가포르·필리핀·태국 라벨에 반영할 법인명·주소가 없어 라벨 원본 확정 불가
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) — 보안 테스트 레코드가 집계(101건)에 잔존 → **삭제 필요**(실질 업무 100건)
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(`계획`)이 실제 진행 단계(시험 수행)와 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(133일)·`신규 라인업 기획서`(91일)·`카탈로그 감리`(86일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가. 확정 문안 검토용 PDF 출력 요청 필요
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- **신규 검토**: 대시보드에 **시장진출/인허가 프로젝트가 없다** — 5개국 규제 대응이 반복 업무로 굳어질 가능성이 크므로 프로젝트 신설 + `project_id` 연결 권장
- 비고: 이번 회차의 핵심은 **"라벨은 실행됐고 서류는 시작됐다"** 이다. 10-21 홍콩 스티커 1,583세트로 오버레이 전략의 첫 실행이 확인됐지만, 10-23 요청서는 오버레이로 해결되지 않는 층(정량 처방·PIF·안전성 평가·GMP·수권서)을 드러냈다. 대시보드는 101건으로 소폭 감소했으나 경과 60건·60일 이상 40건은 그대로이고, 오늘 12건이 동시 도래한다. TSonaX 개발은 9일째 정지.

## [2026-10-23] lint | 주간 위키 린트 (37주차, #wiki 게시)
- 대상: ~/wiki · 콘텐츠 페이지 **61**(10-16 59 → +2: `concepts/kangen-뷰티-문안-바코드-표준` 10-22 · `concepts/칸겐보떼-아세안-규제-신고-자료` 10-23) · 전체 .md **124**(raw 56) · taxonomy 태그 63종 사용
- **Broken wikilink 0건**(10-16 0건 유지) — short-name 링크는 resolver로 정상 해소, raw/ 원본 링크도 실존 확인. index ghost 0건
- **고아 6건 / index 미등재 7건** — 변동 없음(37주차, 일일 카운터 기준), `_archive/` 이동 사용자 승인 대기. `concepts/project-status`는 inbound 링크 있어 고아 아님
- Frontmatter 결손 **0건**(채널 페이지 `sources` 예외 규칙 적용, `channels/index`·`projects/index`는 네비게이션 파일로 검사 제외) · 태그 위반 **1종**(`task` — `concepts/task-status` 전용, 아카이브 시 자동 해소)
- **stale(90일+) 7 → 11건(+4)**: `concepts/slack-adoption`(7/14, 101일) · `concepts/product-liability-insurance`·`concepts/export-voucher`·`entities/aizel-contract`·`entities/aizel-contract-review-request`(7/15, 100일) · `concepts/integrated-weekly-strategy`·`entities/peachy`(7/16, 99일) · **신규** `concepts/aizel-meeting-2026-07-14`·`concepts/aizel-proposal-lineup-2026-07-14`(7/19, 96일) · **신규** `entities/drsante`·`channels/브랜업-에듀`(7/23, 92일)
- Oversized(200줄+) **4건 유지**(줄수 증가): 브랜업-신입직원-온보딩-매뉴얼 802 · 코스메틱-본부 267→**288** · enagic-usa 240→**256** · design-backup 205→**219**
- raw sha256: **불일치 19건**(10-16 15건 → +4) — 전건 `git log` **단일 ingest 커밋** 확인 → 소스 변경 아님, ingest 시 해시 산출 규칙 불일치 · placeholder 18건 · `sha256` 필드 없음 6건
- type 감사: entity 16 · concept 20 · channel 11 · project 13 · summary 1(`entities/aizel-contract-review-request` — 10-16 권고 유지)
- 채널 매핑: Slack 활성 **15개** / 채널 페이지 **11개**(ID 실매칭 10/11). `channels/브랜업-공지사항` `slack_channel_id: (unknown)` — Slack 목록에 실체 없음(**32주차**). `아이젤-계약서` 페이지 ↔ 현 채널명 `브랜업-계약서`(rename 규칙대로 파일명 유지·라벨 갱신) 정상
- 채널 페이지 미생성 Slack 채널 **5개**: `wiki` · `브랜업-조직구성` · `브랜업-휴가` · `제품-기획-제작` · `헤르메스`
- log.md **165 entries / 3,343줄** (<500 → 로테이션 불필요)
- **자동 수정 1건**: `index.md` `브랜업-대시보드-현황` 요약 수치 103건(10-15 기준) → **101건(10-23 기준)** 정정
- 사용자 판단 대기: ① 고아·미등재 7건 `_archive/` 이동 승인 ② raw 레거시 해시 규칙 19건 재산출 여부 ③ 7월 페이지 stale 11건 재확인 ④ `브랜업-공지사항` 채널 실체 확인/페이지 아카이브 ⑤ 채널 페이지 미생성 5개 중 `wiki`·`제품-기획-제작` 생성 여부
- Slack #wiki(C0BGCQS22BF) 리포트 게시 + GitHub push

## [2026-10-24] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 111건 동기화 완료

## [2026-10-24] update | 일일 동기화 — 대시보드 111건(+10 · 신규 12) · 프로젝트 11개 일괄 보류(진행중 0개) · branup.db 403 · TSonaX 10일째 정지
- 실행: 05:00 KST 크론. 38주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **111건**(10-23 101 → **+10**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **신규 12건**(`id` 기준 diff — 10-23 10:24 ~ 10-24 05:00 등록): ① `JNM 코리아 컨택 및 미팅 잡기`(강경철, 10-26) ② `11/4에 CDRI랑 CNM 미팅 잡기`(강경철, 10-26) ③~⑥ **`[재무보고]` 4주치**(10월 4주 10-26 · 11월 1주 11-02 · 2주 11-09 · 3주 11-16, 이상원·이향석, 10-23 18:13 일괄) ⑦ `스티커 업체한테 일정 변경 공유하기`(강경철, 10-26) ⑧ `12월 내 도착 기준으로 부자재 입고일 픽스`(강경철, 10-26) ⑨ `1573세트 태국 OR 미국 확인`(강경철, 10-27) ⑩ `카톤 교통정리`(강경철, 10-27) ⑪ `제품명 바꿔서 재등록`(강경철, 10-30) ⑫ `정부지원사업 매주 확인`(전경표, 11-18 — 05:00 생성, **주간 반복 업무 롤오버**).
- **목록 제거 2건**: ① `홍콩 스티커 입고일 및 제품 출고일 안내`(강경철, 마감 10-23 — **D-0 당일 제거, 완료 추정**) ② `정부지원사업 매주 확인`(**10-23 인스턴스** — 동일 제목 4건 중 최고(最古) 소거 + 11-18 신규 = 4주 롤링 유지).
- **레코드 변경 8건**: 마감 재조정 7건(전건 10-23 D-0 → 연기: `헤어 디바이스 상품제안서 검토`·`마케터 채용공고 올리기` → 10-26 / `책임판매업자 등록 요건…` → 10-27 / `카니발 법인승계 스왑처리`·`BOM 정리 작업`·`Plaud 미팅 노션 연동`·`브랜업캠퍼스 신규 법인설립` → 10-30) + **마감일 삭제 1건** `[OTC] 미국 선크림 인증 절차 조사`(10-23 → null). **제목·단계 변경 1건**: `브랜업캠퍼스 신규 법인설립` → `…인증대기중 -> 인감카드신청`(법인설립 완료 → 인감카드 단계).
- **D-0 12건(10-23) 처리 결과: 연기 7 · 제거 1 · 마감 삭제 1 · 롤오버 1 · 제목 변경 1 · 그대로 경과 2**(`칸젠 민감 피부자극테스트`·`CDRI 라벨 검토 의뢰 및 회신 대기`). **완료 확인 0건**(DB 403).
- **✅ 프로젝트 11개 일괄 '보류' 전환(10-23 18:31:28 ~ 18:32:38, `updated_at` 실측 — 70초 구간에 순차 처리)** — `시니어 마케터 채용`·`소라살롱 공구`·`브랜업 홈페이지 기획안`·`AI/AX 직원 교육`·`뷰티 BM 채용`·`KCL SGS`·`칸겐뷰티 SNS`·`마케팅팀 노션 협업`·`노션 워크스페이스`·`홈페이지 Hero`·`마케팅팀 노션 시범운영` + 기존 보류 `에나지크 발주 시뮬레이터` → **보류 12 · 완료 1(브랜업 대시보드 개발) · 진행중 0개**. index.md 프로젝트 라벨 11건(계획/진행 → 보류) 자동 정정.
- 통계: 마감 경과 60 → **62건**, **D-0·D-1 0건**, **D-2 9건**(10-26 월요일), D-3 3건(10-27), D-4~7 13건, **60일 이상 41건**(+1 = `소라살롱 협업 판매 raw 데이터시트 제작` 08-25 마감 60일 도달), `due_at` 미입력 **15건**, 담당자 공백 5건, `project_id` 미지정 **106/111**. 최근 갱신 **10-24 05:00**.
- ⛔ **`branup.db` 다운로드 403 Forbidden(신규 장애)** — `branup.db`·`.sqlite`·`.bak` 전부 403(UA·Referer 무관), API는 정상. `closed_at` 판별 불가 → 제거 2건 완료/삭제 구분 불가. **`branup_tasks_dump.py`(주간보고서)가 같은 URL 사용** → 빈 결과 위험.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-17 05:01 / 26시간 보고 창 = 10-23 03:01 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**(토요일). 26시간 창 신규는 `#wiki` **10-23 18:03 주간 린트 리포트**(봇 자체 발행, 비업무) **1건**뿐.
- 업무 대화 기준 최신은 여전히 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **1일째 변동 없음**.
- 168시간 창 누적 **14건 / 파일 6건** — 뷰티-프로젝트 5 · 코스메틱-본부 4 · design-backup 2 · 브랜업-전체 1 · 헤르메스 1 · wiki 1, **전량 10-17~10-23 기수록분**. 스레드 답글 0건. errors 0(`제품-기획-제작` `not_in_channel` 스킵). 채널 rename 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c — 프로젝트 페이지 활동
- `projects/에나지크_발주_시뮬레이터.md` — **2026-10-24** 신설: 스티커·부자재·수량 트랙이 업무 5건으로 분화, **수량 불일치(1,583 vs 1,573)**, `홍콩 스티커 입고일…` 제거(완료 추정), `12월 내 도착` 역산 기준점 등장.
- `projects/시니어_마케터_채용_프로젝트.md`·`projects/뷰티_bm_채용_프로젝트.md` — 채용공고 **3회 연속 연기**(10-22 → 10-23 → 10-26) 기록.
- `projects/kcl_sgs_안정성검사_사업_실행_12_31.md` — `칸젠 민감 피부자극테스트` 마감 10-23 **경과 1일**(D-0 잔존 2건 중 하나).
- 나머지 9개 프로젝트 페이지는 DB sync 자동 갱신(Slack 신규 대화 없음).

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 10-24 전면 갱신: 대시보드 111건, 신규 12·제거 2·변경 8, D-0 12건 처리 결과표, 연혁 10-24 항목, 리스크 갱신(경과 62 · D-2 9 · 60일 41 · orphan 106/111 · **프로젝트 계층 비활성** · **branup.db 403** · probe 19일째), 개발 **10일째 정지**.
- `concepts/에나지크-글로벌-물류-패키징-전략.md` — **"실행 3호 — 물량 재배정·부자재 역산 (2026-10-24)"** 신설(업무 5건 표 + 해석: 오버레이 전략은 라벨 비용 대신 물량 배정 유연성을 요구).
- `concepts/칸겐보떼-아세안-규제-신고-자료.md` — §6에 **"대시보드 대응 업무 (2026-10-24 기준)"** 추가: 직접 대응은 3건만 등록(책임판매업자·제품명 재등록·1573세트), **정량 처방·PIF·안전성평가·GMP·COA·효능 근거 확보와 국가별 회신은 미등록**, 회신 기한 없음 이틀째.
- `concepts/브랜업-대시보드-현황.md`·`projects/` 13건 — DB sync 자동 갱신(업무 111건 · 보류 12).

### STEP 4 — 네비게이션
- `index.md` — TSonaX 요약(111건·경과 62·D-2 9·10일째 정지·프로젝트 12/13 보류) · `브랜업-대시보드-현황` 요약(보류 12·완료 1, 진행중 0) · 프로젝트 라벨 11건 정정 · 미등재 섹션 **38주차** 노트 추가. 총 페이지 **61 유지**.
- `channels/index.md` — **10-24 스캔 노트** 추가(ID 매핑 15/15, 신규 0·신규 채널 0).
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차)**: **`branup.db` 다운로드 403** — 원인 확인 필요. 주간보고서(`branup_tasks_dump.py`)가 동일 URL을 쓰므로 **주간 크론 산출물 신뢰성 위험**.
- **신규(1일차)**: **프로젝트 13개 중 12개 보류·진행중 0개** — 10-23 18:31 일괄 전환. 진행 중 업무는 111건인데 프로젝트 계층이 비활성 → 재개/신설 여부 결정 필요.
- **신규(1일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — 오탈자/실물량 차감 확인 필요(에나지크 배정 관련).
- **신규(1일차)**: **아세안 5개국 규제자료 요청 대응 업무 미등록** — 정량 처방·PIF·안전성평가·GMP·COA·효능 근거, 국가별 회신 기한 없음(10-23 등재 유지).
- 미조치(38주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(33주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-24 재확인 — 활성 15개 목록에 없음)
- 미조치(3주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **19일째**, 실질 업무 110건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(134일)·`신규 라인업 기획서`(92일)·`카탈로그 감리`(87일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가(확정 문안 검토용 PDF 출력 요청)
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 이번 회차의 핵심은 **"프로젝트는 전부 멈췄는데 업무는 12건 늘었다"** 이다. 10-23 저녁 18:31에 11개 프로젝트가 일괄 보류로 내려가 '진행중' 프로젝트가 0개가 됐지만, 같은 날 17:16~19:17에 에나지크 실행 업무 5건과 재무보고 4주치가 등록됐다. D-0 12건은 대부분 연기로 흩어져 경과는 60 → 62건으로 오히려 늘었고, 60일 이상 적체(41건, 66%)는 그대로다. TSonaX는 10일째 커밋이 없고, `branup.db`가 403으로 막혀 완료/삭제 판별 수단까지 하나 줄었다.

## [2026-10-25] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 111건 동기화 완료

## [2026-10-25] update | 일일 동기화 — 대시보드 111건 완전 정지(신규 0·제거 0·변경 0) · Slack 업무 0건 2일째 · branup.db 403 이틀째 · TSonaX 11일째 정지
- 실행: 05:00 KST 크론. 39주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **111건**(10-24와 동일). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 diff 전건 0건** (id·제목·담당·마감·상태·project_id 전 필드 비교, `branup_snapshot_20261024.json` 대비): **신규 0 · 목록 제거 0 · 레코드 변경 0**. 최근 갱신 `2026-10-24 05:00:17`은 주간 반복 업무 `정부지원사업 매주 확인`(due 11-18) **자동 생성분** → **사람이 손댄 최종 갱신은 10-23 19:19**(`12월 내 도착 기준으로 부자재 입고일 픽스`). 즉 10-24(토)·10-25(일) **이틀간 대시보드 이벤트 0건**.
- 통계: 마감 경과 **62건 유지**, **60일 이상 41건 유지**(66%), **D-0 0건 · D-1 9건(10-26 월요일)**, D-2 3건(10-27), D-3 2건(10-28), D-4~7 11건, `due_at` 미입력 **15건**, 담당자 공백 5건, `project_id` 미지정 **106/111**. 상태 분포 진행중 110 · 지연 1.
- ⛔ **`branup.db` 다운로드 403 이틀째** — `branup.db`·`.sqlite`·`.db.bak`·`branup-watcher.db` **4개 경로 전량 403**(User-Agent·Referer 지정 무관, urllib 재프로브). 10-23까지 정상 → **2일째 미복구**. `closed_at` 판별 수단 부재 지속, **`branup_tasks_dump.py`(주간보고서) 빈 결과 위험 미해소**.
- 프로젝트 상태 변동 0건: **보류 12 · 완료 1(브랜업 대시보드 개발) · 진행중 0** (10-23 18:31 일괄 전환 이후 그대로).

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-18 05:00 / 26시간 창 = 10-24 03:00 이후)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 메시지 **0건**(금요일 밤~토요일 무활동).
- 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **2일째 변동 없음**.
- 168시간 창 누적 **14건 / 파일 6건** — 뷰티-프로젝트 5 · 코스메틱-본부 4 · design-backup 2 · 브랜업-전체 1 · 헤르메스 1 · wiki 1, **전량 10-19~10-23 기수록분**. 스레드 답글 0건. errors 0(`제품-기획-제작` `not_in_channel` 스킵). 채널 rename 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(10개 페이지 ID 전건 실매칭).
- 채널 페이지 신규 생성 0건(의미 있는 활동 있는 미등재 채널 없음). 미생성 5개(`wiki`·`브랜업-조직구성`·`브랜업-휴가`·`제품-기획-제작`·`헤르메스`) 유지.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c — 프로젝트 페이지 활동
- **신규 활동 없음 → 프로젝트 페이지 수동 추가 0건**. Slack 신규 대화 0건·DB diff 0건이라 10-24에 기록한 활동(에나지크 수량·부자재 역산, 채용공고 3회 연속 연기, KCL 자극테스트 경과)이 그대로 유효하다. 13개 프로젝트 페이지는 DB sync 자동 갱신분만 반영(보류 12·완료 1).

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 10-25 전면 갱신: 대시보드 **111건 변동 없음**(이틀 연속 완전 정지), 연혁 10-25 항목, D-0/D-1 라인 as-of 10-25(D-1 9건 = 10-26), 리스크 갱신(경과 62 유지 · 60일 41 유지 · **branup.db 403 이틀째 4경로 재프로브** · probe 20일째 · orphan 106/111 · 프로젝트 계층 비활성), 개발 **11일째 정지**(10-14 12:47 `c6041cd` → `git ls-remote origin`·`git fetch origin <branch>` 실측, master `e42d7c9` 무변동).
- `concepts/브랜업-대시보드-현황.md`·`projects/` 13건 — DB sync 자동 갱신(업무 111건 · 보류 12).
- 신규 concept/entity/comparison 페이지 **0건**(Page Threshold 미충족 — 신규 소스 없음) · 신규 raw 원본 **0건**.

### STEP 4 — 네비게이션
- `index.md` — 헤더 10-25 · TSonaX 요약 갱신(111건 변동 0 · D-1 9건 · 11일째 정지) · 미등재 섹션 **39주차** 노트 추가. 총 페이지 **61 유지**(channels 11 · entities 17 · concepts 20 · projects 13).
- `channels/index.md` — 헤더 10-25 · ID 매핑 확인일 10-25 · **10-25 스캔 노트** 추가.
- `channels/브랜업-공지사항.md` — 실체 미확인 **33주차** 갱신(`updated` 10-25).
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(2일차)**: **`branup.db` 403 이틀째** — 4개 경로 전량 403. 주간보고서(`branup_tasks_dump.py`)가 동일 URL 사용 → **이번 주 주간 산출물 신뢰성 확인 필요**.
- **신규(1일차)**: **프로젝트 13개 중 12개 보류·진행중 0개** — 진행 중 업무는 111건. 재개/신설 결정 필요.
- **신규(1일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — 오탈자/실물량 차감 확인 필요.
- **신규(1일차)**: **아세안 5개국 규제자료 요청 대응 업무 미등록** — 회신 기한 없음 **3일째**(10-23 접수). 정량 처방·PIF·안전성평가·GMP·COA·효능 근거 확보 주체 미정.
- 미조치(39주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(33주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-25 재확인 — 활성 15개 목록에 없음)
- 미조치(3주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **20일째**, 실질 업무 110건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(135일)·`신규 라인업 기획서`(93일)·`카탈로그 감리`(88일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가(확정 문안 검토용 PDF 출력 요청)
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 이번 회차의 핵심은 **"주말 이틀, 대시보드도 Slack도 완전히 멈췄다"** 이다. 111건이 신규·제거·변경 0건으로 이틀 연속 얼어붙었고(사람 손 최종 갱신 10-23 19:19), Slack 업무 대화도 10-23 01:57 이후 2일째 없다. 그 사이 10-26(월요일) D-1 9건이 그대로 도래를 기다리고, 경과 62건·60일 이상 41건은 손대지 않은 채 유지된다. `branup.db` 403은 이틀째로 완료/삭제 판별 수단이 계속 막혀 있고, TSonaX는 11일째 커밋이 없다.

## [2026-10-26] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 111건 동기화 완료


## [2026-10-26] update | 일일 동기화 — 대시보드 111건 3일째 정지 · D-0 9건 전량 미처리 도래 · Slack 3일 연속 0건 · branup.db 403 3일째 · TSonaX 12일째 정지
- 실행: 05:00 KST 크론. 40주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **111건**(10-25와 동일). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 필드 diff 0건**(id·제목·담당·마감·상태·project_id 전 필드 비교, `branup_snapshot_20261025.json` 대비): **신규 0 · 목록 제거 0 · 레코드 변경 0** → **3일째 정지**. 다만 `updated_at`만 전진한 레코드 **1건**: **`[주간업무전략] 10월 4주`**(#490, 5인 공동, due 10-26) `updated_at = 2026-10-26T00:12:10`. 필드 변경이 없어 **보드 조작/열람 흔적으로 추정**하며, 사람이 업무 내용을 바꾼 최종 갱신은 여전히 **10-23 19:19**(`12월 내 도착 기준으로 부자재 입고일 픽스`).
- 통계: 마감 경과 **62건 유지**, **60일 이상 41건 유지**(66%), **D-0 9건(10-26 당일 도래) · D-1 3건(10-27) · D-2 2건(10-28) · D-3 0건 · D-4~7 13건**, `due_at` 미입력 **15건**, 담당자 공백 5건, `project_id` 미지정 **106/111**. 상태 분포 진행중 110 · 지연 1. 프로젝트 **보류 12 · 완료 1 · 진행중 0**(10-23 일괄 전환 이후 그대로).
- **D-0 9건 전량 미처리 도래** — 전일(10-25) D-1 9건이 오늘 그대로 도래했고, 전일 대비 **연기 0 · 완료 0 · 제거 0**이다. 10-23 D-0 12건이 당일 92%(11/12) 정리된 것과 대조적: `바뀐 용기 문안 포맷…번역 검토`·`[주간업무전략] 10월 4주`·`JNM 코리아 컨택 및 미팅`·`11/4 CDRI·CNM 미팅`·`[재무보고] 10월 4주`·`스티커 업체 일정 변경 공유`·`12월 도착 기준 부자재 입고일 픽스`(강경철 / 이상원·이향석) + `헤어 디바이스 상품제안서 검토`·`마케터 채용공고 올리기`(전경표).
- ⛔ **`branup.db` 다운로드 403 3일째** — `branup.db`·`.sqlite`·`.db.bak`·`branup-watcher.db` **4개 경로 전량 403**(10-26 재프로브, User-Agent 지정 무관). 10-23까지 정상 → **3일째 미복구**. `closed_at` 판별 수단 부재 지속, **`branup_tasks_dump.py`(주간보고서) 빈 결과 위험 미해소**.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-19 05:00 / 26시간 창 = 10-25 03:00 KST)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 메시지 **0건** → **10-24·10-25·10-26 3일 연속 0건**(일요일 하루 Slack 이벤트 없음).
- 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **3일째 변동 없음**.
- 168시간 창 누적 **14건 / 파일 6건** — 뷰티-프로젝트 5 · 코스메틱-본부 4 · design-backup 2 · 브랜업-전체 1 · 헤르메스 1 · wiki 1, **전량 10-19~10-23 기수록분**. ※ 창이 하루 밀리며 10-15~10-18 항목이 창 밖으로 이탈, 10-19 INDD·Canvas는 유지. 스레드 답글 0건(전건 reply_count 0). errors 0(`제품-기획-제작` `not_in_channel` 스킵). 채널 rename 이벤트 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**(페이지 10개 ID 전건 실매칭).
- 채널 페이지 신규 생성 0건(의미 있는 활동이 있는 미등재 채널 없음). 미생성 5개(`wiki`·`브랜업-조직구성`·`브랜업-휴가`·`제품-기획-제작`·`헤르메스`) 유지.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c — 프로젝트 페이지 활동
- **신규 활동 없음 → 프로젝트 페이지 수동 추가 0건**. Slack 신규 대화 0건·DB 필드 diff 0건이라 10-24 기록(에나지크 수량·부자재 역산, 채용공고 연기, KCL 자극테스트 경과)이 그대로 유효. 13개 프로젝트 페이지는 DB sync 자동 갱신분만 반영(보류 12·완료 1).

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 10-26 전면 갱신: 대시보드 **111건 · 필드 diff 0(3일째)**, `updated_at` 단독 갱신 1건(`[주간업무전략] 10월 4주` 10-26 00:12:10) 명시, 연혁 10-26 항목 추가, D-0 9건 전량 미처리 도래 사실과 D-1 3건 라인 as-of 10-26, 리스크 갱신(경과 62 유지 · 60일 41 유지 · **branup.db 403 3일째 4경로 재프로브** · probe 레코드 21일째 · orphan 106/111 3일째 · 프로젝트 계층 비활성), 개발 **12일째 정지**(tip `c6041cd` 10-14 12:47, `git ls-remote origin` 실측 — master `e42d7c9` 무변동).
- `concepts/브랜업-대시보드-현황.md`·`projects/` 13건 — DB sync 자동 갱신(업무 111건 · 보류 12).
- 신규 concept/entity/comparison 페이지 **0건**(Page Threshold 미충족 — 신규 소스 없음) · 신규 raw 원본 **0건**.

### STEP 4 — 네비게이션
- `index.md` — TSonaX 요약 갱신(111건 3일째 정지 · D-0 9건 · 12일째 정지) · 미등재 섹션 **40주차** 노트 추가. 총 페이지 **61 유지**(channels 11 · entities 17 · concepts 20 · projects 13).
- `channels/index.md` — 헤더 10-26 · ID 매핑 확인일 10-26 · 퀵뷰 `브랜업-공지사항` **34주차** · **10-26 스캔 노트** 추가.
- `channels/브랜업-공지사항.md` — 실체 미확인 **34주차** 갱신(`updated` 10-26).
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차)**: **D-0 9건 전량 미처리** — 오늘 도래분 중 연기·완료 0건. 그중 `마케터 채용공고 올리기`는 10-22 → 10-23 → 10-26으로 이미 2회 연기된 항목.
- **신규(1일차)**: `[주간업무전략] 10월 4주`가 10-26 00:12 필드 변경 없이 `updated_at`만 갱신 — 보드 조작 흔적이라면 주간전략 회의(5인) 착수 여부 확인 필요.
- **신규(3일차)**: **`branup.db` 403 3일째** — 4개 경로 전량 403. 주간보고서(`branup_tasks_dump.py`)가 동일 URL 사용 → **이번 주 주간 산출물 신뢰성 확인 필요**.
- **신규(2일차)**: 프로젝트 13개 중 **12개 보류·진행중 0개** — 진행 중 업무는 111건. 재개/신설 결정 필요.
- **신규(2일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — 오탈자/실물량 차감 확인 필요.
- **신규(2일차)**: **아세안 5개국 규제자료 요청 대응 업무 미등록** — 회신 기한 없음 **4일째**(10-23 접수). 정량 처방·PIF·안전성평가·GMP·COA·효능 근거 확보 주체 미정.
- 미조치(40주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(34주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-26 재확인 — 활성 15개 목록에 없음)
- 미조치(4주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **21일째**, 실질 업무 110건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(136일)·`신규 라인업 기획서`(94일)·`카탈로그 감리`(89일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가(확정 문안 검토용 PDF 출력 요청)
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 이번 회차의 핵심은 **"3일 정지 후 월요일, 9건이 그대로 도래했다"** 이다. 대시보드는 필드 변경 0건으로 3일째 얼어붙었고(사람 손 최종 갱신 10-23 19:19), Slack 업무 대화도 10-23 01:57 이후 3일째 없다. 그 사이 10-26 도래 9건은 연기·완료·제거 어느 쪽으로도 처리되지 않았고, 경과 62건·60일 이상 41건도 그대로다. `branup.db` 403은 3일째로 완료/삭제 판별 수단이 계속 막혀 있고, TSonaX는 12일째 커밋이 없다. D-0 9건의 처리 결과는 내일(10-27) 회차에서 diff로 드러난다.

## [2026-10-27] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 116건 동기화 완료

## [2026-10-27] update | 일일 동기화 — 3일 정지 해제(신규 8·완료 8) · `branup.db` 403 우회 경로 발견(`/api/tasks/completed`) · TSonaX 백로그 2건 완료로 정정 · Slack 4일 연속 0건
- 실행: 05:00 KST 크론. 41주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **116건**(10-26 111건 대비 **+5**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 필드 diff**(`branup_snapshot_20261026.json` 대비): **신규 10 · 목록 제거 5 · 레코드 변경 3** → **3일 정지 해제**.
- **신규 10건** — 실등록 8건(전건 **10-26 생성**, 월요일 낮~저녁 집중): ① `태국 문안 정리`(강경철, **10-27**, 16:48) ② `태국 인증 절차 리서치`(강경철, **10-27**, 16:48) ③ `15ml 세트박스(슬리브) 발주`(강경철, **10-27**, 17:46) ④ `스패츌라 발주`(강경철, **10-27**, 18:31) ⑤ `전성분(Mink Oil) 변경 여부 확인`(강경철, 10-28, 16:50) ⑥ `세트박스 문안 검토(영어,불어,전성분)`(강경철, 10-29, 16:22) ⑦ `본품 씰링 스티커 vs 수축필름 비용 비교 및 회의`(강경철, 10-30, 10:37) ⑧ `[SVC] 입주기업 신규 가능성 > 맴버쉽 공고 or 외부 공고`(이상원·이향석, 11-06, 10:11) + **주간 자동생성 2건**(`[주간업무전략] 11월 4주`·`[재무보고] 11월 4주`, 10-27 05:00:20 생성, 마감 11-23).
- **목록 제거 5건 = 전건 '완료' 실측 확인**(`/api/tasks/completed`): `CDRI 라벨 검토 의뢰 및 회신 대기`(강경철, **10-26 09:13:43**) · `마케터 채용공고 올리기`(전경표, **10:51:50**) · `스티커 업체한테 일정 변경 공유하기`(강경철, **16:50:58**) · `1573세트 태국 OR 미국 확인`(강경철, **18:49:01**) · `12월 내 도착 기준으로 부자재 입고일 픽스`(강경철, **18:49:34**) — **삭제 0건**.
- **레코드 변경 3건**: ① `11/4에 CDRI랑 CNM 미팅 잡기` → `11/4에 CDRI랑 JNM 미팅 잡기`(**오타 CNM→JNM 수정**) ② `세무현명 자문계약 처리` → `[세무] 세무법인 결정 : 현명, 삼덕회계, 대형법인, 솔로몬` + **마감 10-30 신규 부여** ③ `바뀐 용기 문안 포맷 괜찮으면 다른 언어로 번역해서 검토 요청` 마감 **10-26 → 10-30**(연기).
- **10-26 하루 완료 8건**(위 5건 + `전성분 관련 문의` 16:50:30 · `[AMPM글로벌 컨설팅 교육] 메타광고 초기 세팅 & 운영 효율화 교육` 17:19:58 · `(이사님 요청) 정부지원사업 검토` 19:19:25). 즉 **어제 D-0 9건 중 4건이 완료·1건 연기(10-30)·4건 미처리**(`[주간업무전략] 10월 4주`·`JNM 코리아 컨택`·`11/4 CDRI·JNM 미팅`·`헤어 디바이스 상품제안서 검토`).
- 통계: 마감 경과 62 → **66건**(+4), **60일 이상 42건**(66%, +1), **D-0 6건**(10-27 — `책임판매업자 등록 요건…`·`카톤 교통정리` + **신규 4건이 당일 도래**, 전건 강경철) · **D-1 3건**(10-28) · **D-2 1건**(10-29) · **D-3 14건**(10-30) · D-4~7 2건, `due_at` 미입력 **14건**, 담당자 공백 5건, `project_id` 미지정 **111/116**. 상태 분포 진행중 115 · 지연 1. 프로젝트 **보류 12 · 완료 1 · 진행중 0**(10-23 일괄 전환 이후 무변동).
- 🔑 **`branup.db` 403 4일째(4경로 전량 403, urllib 재프로브)** 이지만 **`GET /api/tasks/completed`가 완료 이력 356건 + `closed_at`을 반환**함을 발견 → **완료/삭제 판별 수단 확보**. `closed_at` 범위 2026-05-29 ~ 2026-10-26 19:19.

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-20 05:00 / 26시간 창 = 10-26 03:00 KST)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 **0건** → **10-24·25·26·27 4일 연속 0건**(월요일 하루 Slack 대화 전무).
- 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **4일째 변동 없음**.
- 168시간 창 누적 **12건 / 파일 5건** — 뷰티-프로젝트 5 · 코스메틱-본부 4 · 브랜업-전체 1 · 헤르메스 1 · wiki 1, **전량 10-20~10-23 기수록분**. ※ 창 이동으로 `design-backup` 10-19 INDD·Canvas가 168시간 밖으로 이탈(14→12건, 6→5파일). 스레드 답글 0건. errors 0(`제품-기획-제작` `not_in_channel` 스킵). 채널 rename 최근 **0건**(스캔에 잡힌 3건은 7/27~7/29 이력) · 신규 채널 0건 · ID 매핑 **15/15 일치**. 채널 페이지 신규 생성 0건(의미 있는 활동 있는 미등재 채널 없음). 미생성 5개(`wiki`·`브랜업-조직구성`·`브랜업-휴가`·`제품-기획-제작`·`헤르메스`) 유지.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만 `not_in_channel`).

### STEP 2c — 프로젝트 페이지 활동
- **수동 추가 0건.** 10-26 신규 업무 8건 전건 `project_id=None`(프로젝트 12/13이 보류 상태라 계층 비활성) → 특정 프로젝트 페이지에 귀속할 근거 없음. 신규 작업의 실질 내용은 concept 페이지 2건으로 반영(아래 STEP 3). 13개 프로젝트 페이지는 DB sync 자동 갱신분만 반영.

### STEP 3 — Wiki 페이지 갱신
- **신규 concept 1건: `concepts/브랜업-업무-완료-판별.md`** — `/api/tasks/completed` 판별 절차·응답 필드·소급 검증 표(10-08~10-24 제거분 전건 '완료')·`branup.db` 403 관계·주의사항(완료 이력 시작 2026-05-29).
- `concepts/tsonax.md` — **10-27 전면 갱신 + 오판 정정**: ① `#394`·`#202`를 "10-22 목록 제거(완료 미확인)" → **✅ 완료(10-21 10:07:30 / 10:09:59)** 로 수정 ② 헤더에 10-21 대량 완료 백로그 정리 사실과 오판 원인(`branup.db` 10-21 09:37 고정 + 403) 명시 ③ 최근 작업 표 2행 ✅ 처리 ④ 연혁 10-27 항목 추가 ⑤ 개발 **13일째 정지**(tip `c6041cd` 10-14 12:47, master `e42d7c9` 무변동 — `git ls-remote origin` 실측).
- `concepts/칸겐보떼-아세안-규제-신고-자료.md` — "대시보드 대응 업무"를 **10-27 기준**으로 갱신: **10-26 태국 라인 첫 등록**(`태국 문안 정리`·`태국 인증 절차 리서치`, 전건 10-27 마감) + `1573세트 태국 OR 미국 확인` **10-26 18:49 완료 = '태국' 확정** → **태국이 5개국 중 첫 착수 국가**. 정량 처방·PIF·GMP·COA·효능 근거·국가별 회신은 **여전히 미등록(4일째)**.
- `concepts/kangen-뷰티-문안-바코드-표준.md` — **§7 신설(2026-10-26 후속)**: 세트박스·발주 라인 4건(`15ml 세트박스(슬리브) 발주`·`스패츌라 발주`·`세트박스 문안 검토(영어,불어,전성분)`·`본품 씰링 스티커 vs 수축필름 비용 비교 및 회의`) + `전성분(Mink Oil) 변경 여부 확인`을 **신규 변수**로 표기 + 번역 검토 마감 10-30 연기 반영.
- 신규 entity/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).

### STEP 4 — 네비게이션
- `index.md` — 헤더 **10-27 · 총 62페이지**(concepts 20 → 21) · TSonaX 요약 갱신(백로그 2건 완료 확인·13일째 정지·경과 66건·D-0 6건·116건) · `브랜업-대시보드-현황` 116건으로 수치 정정 · 신규 페이지 등재 · 미등재 섹션 **41주차** 노트 추가.
- `channels/index.md` — 헤더 10-27 · ID 매핑 확인일 10-27 · 퀵뷰 `브랜업-공지사항` **35주차** · **10-27 스캔 노트** 추가(Slack 4일 조용 vs 대시보드 8건 등록 주석).
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차)**: **D-0 6건 중 4건이 "어제 등록·오늘 마감"** — `태국 문안 정리`·`태국 인증 절차 리서치`·`15ml 세트박스(슬리브) 발주`·`스패츌라 발주`(전건 강경철). 등록 시점에 이미 마감이 걸려 있어 **연기 여부를 오늘 중 판단**해야 한다(10-23 D-0 12건은 당일 92% 정리된 전례).
- **신규(1일차)**: **`전성분(Mink Oil) 변경 여부 확인`(10-28)** — 원료 변경 시 라벨 전성분·UPC·국가별 문안 재검토 필요. 변경 확정 여부가 세트박스 문안 검토(10-29)의 입력값.
- **신규(1일차)**: **`본품 씰링 스티커 vs 수축필름` 결정 미정(10-30)** — 밀봉 방식이 정해져야 부자재 발주·원가 확정.
- **신규(1일차)**: `세무현명 자문계약 처리`가 `[세무] 세무법인 결정 : 현명, 삼덕회계, 대형법인, 솔로몬`으로 확장되며 **마감 10-30 신규 부여** — 세무법인 선정 의사결정 필요.
- **신규(2일차~)**: 프로젝트 13개 중 **12개 보류·진행중 0개** 유지 — 진행 중 업무는 116건. 재개/신설 결정 필요.
- **신규(3일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — `1573세트 태국 OR 미국 확인`은 10-26 완료됐으나 **수량 표기 불일치 자체는 미해소**.
- **신규(5일차)**: **아세안 5개국 규제자료 요청** — 태국 라인은 착수됐으나 **홍콩·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음.
- **해소(10-27)**: `branup.db` 403으로 인한 **완료/삭제 판별 불가 상태 종료** — `/api/tasks/completed`로 대체. `branup_tasks_dump.py`(주간보고서)도 동일 엔드포인트로 교체 권장.
- 미조치(41주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(35주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-27 재확인 — 활성 15개 목록에 없음)
- 미조치(5주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **22일째**, 실질 업무 115건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(137일)·`신규 라인업 기획서`(95일)·`카탈로그 감리`(90일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가(확정 문안 검토용 PDF 출력 요청)
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 이번 회차의 핵심은 두 가지다. 첫째 **3일 얼어붙었던 대시보드가 월요일에 움직였다** — 신규 8건·완료 8건, 그리고 D-0 9건 중 4건이 실제로 처리됐다. 둘째 **`branup.db` 403(4일째)을 우회할 길을 찾았다**. `/api/tasks/completed`가 완료 이력 356건과 `closed_at`을 그대로 준다. 이걸로 10-08 이후 "판별 불가"로 쌓아둔 목록 제거 항목을 전건 재조회했더니 **예외 없이 '완료'**였고, 10-22 회차에 "완료가 아니라 목록 정리"라고 단정한 10건도 전부 10-21 오전 일괄 완료였다. 그 오판의 파급이 **TSonaX 백로그 2건**(`종목별 순매수` 10-21 10:07 · `2년치 DB 적재` 10-21 10:09)이었고, 5일 만에 정정했다. 다만 개발 자체는 13일째 커밋이 없다(`c6041cd`, 10-14 12:47). 남은 활성 업무는 `[Toffer] 익절/손절`·`대표님 지표추가` 2건이며 둘 다 마감이 없다.

## [2026-10-28] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 110건 동기화 완료

## [2026-10-28] sync | 일일 동기화 — Slack 5일 연속 0건 · 대시보드 신규 7·완료 13(삭제 0) · 노수민 담당 8건 1분 내 일괄 종결 · TSonaX 14일째 정지
- 실행: 05:00 KST 크론. 42주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **110건**(10-27 116건 대비 **−6**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 필드 diff**(`branup_snapshot_20261027.json` 대비): **신규 7 · 목록 제거 13 · 레코드 변경 1**.
- **신규 7건 — 전건 10-27 생성, 7건 중 5건이 포장·부자재·문안 라인**: ① `쇼핑백(1만개) 발주서 전달 및 지원 발주 품목 수량 정리 / 카톤 수지판비도 넣어야하고, 단가도 그냥 4082원으로 하면 됨`(강경철, 10-27) ② `태국 수출 라벨링 리서치/검토 작업`(**전경표**, 10-27) ③ `원티드 채용공고 - 임상현 지원자 검토`(전경표, 10-28) ④ `씰링 스티커도 다국어야 하나`(강경철, 10-28) ⑤ `동국 발주서 작성`(강경철, 10-28) ⑥ `CDRI 쇼핑백 및 씰링 스티커 관련 문의`(강경철, 10-28) ⑦ `오전까지 샘플 세트박스 글자/카탈로그 기재 시 안써도 되는거 규정`(강경철, 10-28).
- **목록 제거 13건 = 전건 '완료' 실측**(`/api/tasks/completed` 356 → **369건**), **삭제 0건**: `스패츌라 발주`(10-27 18:16:34) · `태국 인증 절차 리서치`(18:16:31) · **노수민 담당 8건**(15:04:34~15:05:09 **1분 내 일괄** — `칸젠 인스타`(07-10)·`칸젠인스타`(07-28)·`보라색 샘플 준비`(07-28)·`에나지크 브랜드 기획`(07-28)·`정육공방 슬리브 인쇄 파일 수정`(08-11)·`[정육공방] 기타 부자재발주`(08-12)·`용기 문안정리`(08-12)·`최유미교수님 명함 오인쇄 소통`(08-14)) · `[재무보고] 10월 4주`·`[주간업무전략] 10월 4주`(14:53) · `카톤 교통정리`(09:02).
- **레코드 변경 1건**: `[컨설팅] 재무/회계 정부지원(80%)` → **`[컨설팅] 11/4 ~ 11/6 재무/회계 정부지원(80%)`** + **마감 10-28 → 11-04**(10-27 13:57, 담당 이향석) — 컨설팅 실제 일정 확정.
- 통계: 마감 경과 66 → **61건**(−5), **60일 이상 42 → 34건**(−8, 노수민 60일+ 8건 일괄 종결 효과), **D-0 7건**(10-28 — 강경철 5 · 전경표 2) · **D-1 1건**(10-29) · **D-2 14건**(10-30) · D-5 2건 · D-7 2건, `due_at` 미입력 **14건**, 담당자 공백 5건, `project_id` 미지정 **105/110**, 상태 진행중 109 · 지연 1. 프로젝트 **보류 12 · 완료 1 · 진행중 0**(10-23 일괄 전환 이후 무변동).
- ℹ️ 전일 스냅샷(9필드)과 API(전체 필드)의 스키마 차이로 `priority`가 전건 '변경'으로 잡히는 노이즈 확인 → 금일 스냅샷부터 **전체 필드 저장**으로 교체(익일 diff 정확도 개선).

### STEP 2 — Slack 채널 스캔 (활성 15개, 168시간 창 = 10-21 05:00 / 26시간 창 = 10-27 03:00 KST)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 **0건** → **10-24~10-28 5일 연속 0건**(화요일 하루도 Slack 대화 전무).
- 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **5일째 변동 없음**.
- 168시간 창 누적 **11건 / 파일 5건** — 뷰티-프로젝트 5 · 코스메틱-본부 4 · 브랜업-전체 1 · wiki 1, **전량 10-21~10-23 기수록분**. ※ 창 이동으로 `헤르메스` 10-20 17:01 종료 알림이 이탈(12→11건). 스레드 답글 0건. errors 0(`제품-기획-제작` `not_in_channel` 스킵). rename 최근 0건 · 신규 채널 0건 · ID 매핑 **15/15 일치**. 채널 페이지 신규 생성 0건(의미 있는 활동 있는 미등재 채널 없음).

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작`만).

### STEP 2c — 프로젝트 페이지 활동
- **수동 추가 2건**: ① `projects/시니어_마케터_채용_프로젝트` — `마케터 채용공고 올리기` **10-26 10:51:50 완료**(3회 연기 끝) → `원티드 채용공고 - 임상현 지원자 검토`(10-28)로 **지원자 스크리닝 단계 이동**, 프로젝트 상태는 여전히 '보류' ② `projects/칸겐뷰티_sns_운영` — 노수민 담당 `칸젠 인스타`·`칸젠인스타` 2건 **10-27 15:04~15:05 일괄 종결**, 산출물 미확인·담당 재편 미정.
- 나머지 신규 업무 전건 `project_id=None` → 귀속 근거 없음. `정육공방` 관련 완료 2건은 소라살롱 공구 프로젝트와의 동일성 판단 불가로 **귀속 보류**. 13개 프로젝트 페이지는 DB sync 자동 갱신분 반영.

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 연혁 **10-28 항목 추가**(신규 7·완료 13·변경 1·통계 전량), 헤더 **14일째 정지**·마감 없는 진행중 **7일째**, `branup.db` 403 **5일째(판별 수단은 `/api/tasks/completed`로 확보)**, 담당자 공백·orphan 수치(105/110) 정정, Source 라인 갱신. 개발 브랜치 `git ls-remote origin` 실측: tip `c6041cd`(10-14 12:47)·master `e42d7c9`(09-02) 무변동.
- `concepts/칸겐보떼-아세안-규제-신고-자료.md` — '대시보드 대응 업무'를 **10-28 기준**으로 갱신: `태국 인증 절차 리서치` **10-27 18:16:31 완료**, `태국 수출 라벨링 리서치/검토 작업`(전경표) 신규 → **태국 라인 2인 분업**. 정량 처방·PIF·안전성 평가·GMP·COA·효능 근거 미등록 **5일째**.
- `concepts/kangen-뷰티-문안-바코드-표준.md` — **§8 신설(10-27 후속)**: 쇼핑백 1만개 **단가 4,082원 확정**·카톤 수지판비, `동국` 신규 공급사 발주서, CDRI 쇼핑백·씰링 스티커 동시 문의, `씰링 스티커 다국어 여부`, **샘플 세트박스 표기 면제 규정**. ⚠️ 밀봉 방식(스티커 vs 수축필름, 10-30) **미정 상태에서 다국어 판단(10-28)이 먼저 도래하는 순서 충돌** 지적.
- 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).

### STEP 4 — 네비게이션
- `index.md` — 헤더 **10-28 · 총 62페이지** · TSonaX 요약(14일째 정지·경과 61건·D-0 7건·110건) · `브랜업-대시보드-현황` 110건 · `업무-완료-판별` 369건/지연완료 193건(52%) · 아세안(태국 2인 분업) · 문안 표준(§8) 갱신 · **10-28 크론 노트** 추가.
- `channels/index.md` — 헤더 10-28 · **10-28 스캔 노트** 추가(Slack 5일 조용 vs 대시보드 신규 7·완료 13 주석).
- README.md 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차)**: **노수민 담당 8건이 10-27 15:04~15:05 1분 내 일괄 완료** — 마감이 07-10~08-14로 2~3개월 경과한 항목들이다. 개별 완료인지 **퇴사·업무 이관에 따른 일괄 정리**인지 확인 필요(잔여 노수민 업무 3건 + 주간업무전략 4건 + 프로젝트 담당 표기 유지).
- **신규(1일차)**: **D-0 7건 중 5건이 강경철·포장/부자재 라인** — `전성분(Mink Oil) 변경 여부 확인`·`씰링 스티커도 다국어야 하나`·`동국 발주서 작성`·`CDRI 쇼핑백·씰링 스티커 문의`·`샘플 세트박스 표기 면제 규정`. 특히 **씰링 스티커 다국어 판단은 밀봉 방식(10-30) 미정 상태에서 먼저 도래** → 조건부 판단 또는 순서 조정 필요.
- **신규(1일차)**: **쇼핑백 1만개 단가 4,082원**이 업무 제목/요약에만 있고 발주서·견적 원본이 위키에 없다 — 확정 단가·수량·납기 근거 문서 확보 권장.
- **신규(1일차)**: **`[컨설팅] 11/4~11/6 재무·회계 정부지원(80%)`로 일정 확정**(마감 11-04) — 11월 첫 주 D-7에 2건(`카니발 법인승계 스왑처리`·본 건)이 겹친다.
- **신규(2일차)**: `15ml 세트박스(슬리브) 발주`(10-27 마감) **경과 1일 미완** — 10-26 등록분 중 유일하게 남은 발주 건.
- **신규(2일차)**: 프로젝트 13개 중 **12개 보류·진행중 0개** 유지 — 실제 활동(채용·SNS·포장)이 재개된 프로젝트도 상태값이 '보류'로 남아 **상태 필드가 실상을 반영하지 않는다**(시니어 마케터 채용이 대표 사례).
- **신규(6일차)**: **아세안 5개국 규제자료 요청** — 태국 라인만 2인 분업으로 진행, **홍콩·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음.
- **신규(3일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — `1573세트 태국 OR 미국 확인`은 10-26 완료됐으나 표기 불일치 자체는 미해소.
- 미조치(41주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(35주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-28 재확인 — 활성 15개 목록에 없음)
- 미조치(5주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **22일째**, 실질 업무 109건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 5건 (`협력업체들 계약서 정리…`·`[에나지크] 캐나다 라벨 리뷰 방안`(138일)·`신규 라인업 기획서`(96일)·`카탈로그 감리`(91일)·`packing list 줄리어스 대표님꼐 전달`)
- 미조치(계속): IR 덱 편집 오류 2건 (p4 설립일 이전 표기 · p1 `A/B/C/D` 미치환)
- 미조치(계속): `00.261016용기 후면 최신 (3).indd` — INDD 위키 판독 불가(확정 문안 검토용 PDF 출력 요청)
- 미조치(계속): `0720-2.jpg` KANGEN BEAUTÉ 제품 비주얼 — 대상 프로젝트(SNS·홈페이지·IR) 확인 필요
- 비고: 오늘 숫자는 좋아 보인다 — 경과 66→61건, 60일 이상 42→34건. 그러나 **줄어든 8건 전부가 노수민 담당의 1분짜리 일괄 종결**이다. 즉 적체가 해소된 게 아니라 **한 사람의 오래된 업무 묶음이 한 번에 정리된 것**이고, 나머지 구조(담당자 공백 5건·마감 없는 진행중·`project_id` 미지정 105/110)는 그대로다. 반대로 실제 진척이 보이는 곳은 **포장·부자재 라인**이다 — 쇼핑백 1만개 단가 확정(4,082원), 동국 발주서, CDRI 견적 문의로 12월 양산분 부자재가 구체화됐고, 태국 규제 라인은 전경표가 합류해 2인 분업이 됐다. 다만 **씰링 스티커 다국어 판단이 밀봉 방식 결정보다 먼저 도래**하는 순서 충돌은 오늘 안에 정리돼야 한다. TSonaX는 코드·대시보드 양쪽에서 14일째 조용하고, Slack은 5일째 아무 말도 없다 — 업무가 Slack이 아닌 대시보드 직접 등록으로만 흐르는 구조가 이제 일주일째 굳어졌다.

## [2026-10-29] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 115건 동기화 완료

## [2026-10-29] sync | 일일 동기화 — Slack 6일 연속 0건 · 대시보드 신규 9·완료 4(삭제 0) · 이향석 계정 32분간 6건 집중 등록 · TSonaX 15일째 정지
- 실행: 05:00 KST 크론. 43주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **115건**(10-28 110건 대비 **+5**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 필드 diff**(`branup_snapshot_20261028.json` 전체 필드 대비): **신규 9 · 목록 제거 4 · 레코드 변경 10**.
- **신규 9건** — ① `[칸겐뷰트] 샘플 봉합 실링 스티커 규제 리서치`(전경표, 마감 **10-28**, 10-28 10:56:43) ② `[칸겐뷰트] 종이 쇼핑백 규제 리서치`(전경표, **10-28**, 10:57:04) ③ `카페24 보증보험 사전연장 여부 검토`(**담당 공백**, 11-28, 17:20:39) ④ `인쇄물 관리 기준마련`(이향석, 11-02, 17:27:45) ⑤ `[폴스타] 보험갱신 자료 준비`(이향석, 10-30, 17:30:28 — 번호판·주행거리 계기판·블랙박스 사진 요건 = 법인 차량 보험) ⑥ `[SVC] 11/05 재무관리 교육`(이향석, 11-05, 17:31:36) ⑦ `[SVC] 엡버서더 미팅`(이상원·이향석, 11-06, 17:34:47 — 11/06 16:00 사무실, 서울대 국제대학원 중국인 취업준비 구독자 인터뷰) ⑧ `더마테스트 견적서 요청`(이향석, **10-28**, 17:51:07 — `dermatest.com` 문의처·`korea@dermatest.com`) ⑨ **주간 자동생성** `정부지원사업 매주 확인`(전경표, 11-25, 10-29 05:00:16). → **⑥건이 10-28 17:20~17:51 32분간 이향석 계정에서 연속 등록**(전일까지 강경철·전경표 주도였던 등록 주체가 하루 만에 이동).
- **목록 제거 4건 = 전건 '완료' 실측**(`/api/tasks/completed` 369 → **374건**, **삭제 0건**): `태국 수출 라벨링 리서치/검토 작업`(전경표, **10-28 10:56:08**) · `원티드 채용공고 - 이상빈 지원자 검토 / 면접일정 조율`(전경표, **15:59:35** — 전일 등록 제목은 '임상현', 완료 레코드 지원자명이 '이상빈'으로 교체) · `오전까지 샘플 세트박스 글자/카탈로그 기재 시 안써도 되는거 규정`(강경철, **16:45:08**) · **`[Web] cosmetic-review 서비스 추가`(이향석, 17:28:27 — 마감 10-30보다 2일 조기, 09-25 등록 후 5주 만에 종결)**. 별도로 목록에 없던 `[대표님 요청] 이은오 면접일정 조율`(전경표)도 **15:56:35 완료** → 실제 10-28 완료 **5건**.
- **레코드 변경 10건** = 마감 연기 7 · 마감 삭제 1 · 제목 변경 2: `JNM 코리아 컨택 및 미팅 잡기`(10-26 → **10-29**) · `11/4에 CDRI랑 JNM 미팅 잡기`(10-26 → **10-29**) · `15ml 세트박스(슬리브) 발주`(10-27 → **10-29**, **발주 미완 상태로 2일 연기**) · `쇼핑백(1만개) 발주서 전달…`(10-27 → **10-29**) · `책임판매업자 등록 요건…`(10-27 → **10-30**) · `태국 문안 정리`(10-27 → **10-31**) · `[세무] 세무법인 결정…`(10-30 → **11-05**) · `브랜업 퇴직금 제도 조사` **마감 삭제**(10-30 → null) · **`브랜업캠퍼스 신규 법인설립 인증대기중` → `… 법인설립 완료 → 사업자등록증 신청 → 인감카드신청`**(10-24 '인증대기중' → **4일 만에 법인설립 완료**) · `[컨설팅] 11/4 ~ 11/6` → `11/04 ~ 11/06`(표기 정규화).
- 통계: 마감 경과 61 → **62건**(+1), **60일 이상 34건 유지**(55%), **D-0 5건**(10-29 — JNM·CDRI 미팅·세트박스 문안 검토·15ml 슬리브·쇼핑백 발주서, **전건 강경철**) · **D-1 13건**(10-30) · D-2 1건(10-31) · D-4 3건 · D-6 2건 · D-7 2건 · D-8 2건, `due_at` 미입력 **15건**, 담당자 공백 **6건**(+1 `카페24 보증보험`), `project_id` 미지정 **110/115**, 상태 진행중 114 · 지연 1, 프로젝트 **보류 12 · 완료 1 · 진행중 0**. 담당자별 경과: **강경철 30** · 전경표 11 · 김봉재 9 · 공백 4 · 노수민 2 · 이상원 계열 4 · 최유미 2 · 이향석 1.
- ℹ️ `/api/projects` 응답의 프로젝트명 필드는 `name`이 아니라 **`title`** — diff 스크립트에 name 사용 시 전건 None으로 나온다(금일 확인).

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-28 03:00 KST / 168시간 창 = 10-22 05:00 KST)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 **0건** → **10-24~10-29 6일 연속 0건**.
- 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **6일째 변동 없음**.
- 168시간 창 누적 **5건 / 파일 1건** — 뷰티-프로젝트 4 · wiki 1, **전량 10-23 기수록분**. 창 이동으로 `코스메틱-본부` 10-21분·`브랜업-전체` Canvas가 이탈(11 → 5건). 스레드 답글 0건. errors 0(`제품-기획-제작` `not_in_channel` 스킵). rename 최근 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 신규 생성 0건(`헤르메스`·`브랜업-조직구성`·`브랜업-휴가`는 168시간 활동 0).
- 수집 방식: `curl` subprocess(urllib 대용량 truncation 회피) + 시간필터 없이 `limit:50` 후 스크립트 내 비교. 2회 실행 시 동일 카운트 확인.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel`만).

### STEP 2c — 프로젝트 페이지 활동
- **수동 추가 1건**: `projects/시니어_마케터_채용_프로젝트` — `[대표님 요청] 이은오 면접일정 조율` **10-28 15:56:35 완료** · `원티드 채용공고 - 이상빈 지원자 검토 / 면접일정 조율` **15:59:35 완료** → **지원자 최소 2~3명 동시 스크리닝(임상현 → 이상빈·이은오)**, 면접일정 조율 단계 진입. 프로젝트 상태는 여전히 '보류'(불일치 6일째).
- 나머지 신규 9건 전건 `project_id=None` → 귀속 근거 없음. 이향석 계정 6건(더마테스트·폴스타 보험·인쇄물 기준·SVC 2건·카페24)은 **어느 프로젝트에도 매핑되지 않는 관리·행정 라인**으로 판단해 프로젝트 페이지 귀속 보류 — 대시보드 현황·index에만 반영.
- 13개 프로젝트 페이지는 DB sync 자동 갱신분 반영.

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 연혁 **10-29 항목 추가**, 헤더 **15일째 정지**·기한 없는 진행중 **8일째**, **`[Web] cosmetic-review 서비스 추가` 10-28 17:28 완료**(09-25 등록 후 5주 만, 마감 2일 조기) 항목 신설, 표 캡션 10-29 기준 갱신. 개발 브랜치 `git ls-remote origin` 실측: tip `c6041cd`(10-14 12:47)·master `e42d7c9`(09-02) 무변동.
- `concepts/칸겐보떼-아세안-규제-신고-자료.md` — '대시보드 대응 업무'를 **10-29 기준**으로 갱신: `태국 수출 라벨링 리서치/검토 작업` **10-28 10:56:08 완료** → **포장재(실링 스티커·종이 쇼핑백) 규제 리서치 2건 신규**(전경표)로 **태국 라인 3단계 확장**. 두 신규 건은 **등록 즉시 경과**(마감 10-28) + `[칸겐뷰트]` 오타. 홍콩(1순위)은 **6일째 업무 등록 0건**.
- `concepts/kangen-뷰티-문안-바코드-표준.md` — **§9 신설(10-29 후속)**: ① 샘플 세트박스 표기 면제 규정 **10-28 16:45 완료**(단 산출물·확정 내용 위키에 없음) ② 쇼핑백 1만개·15ml 슬리브 **10-27 → 10-29 2일 연기**(D-0, 발주 미완) ③ 전경표 포장재 규제 리서치 2건 ④ `씰링 스티커도 다국어야 하나`(10-28) **경과 1일 미판단** vs 밀봉 방식 회의(10-30) **판단 순서 충돌 지속** ⑤ 태국 문안 정리 → 10-31.
- 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).

### STEP 4 — 네비게이션
- `index.md` — 헤더 **10-29 · 총 62페이지** · TSonaX 요약(15일째 정지·경과 62건·D-0 5건·115건·cosmetic-review 완료) · `브랜업-대시보드-현황` 115건 · `업무-완료-판별` **374건/지연완료 194건(52%)** · 아세안(태국 3단계 확장·홍콩 6일 0건) · 문안 표준(§9) 갱신 · **10-29 크론 노트** 추가.
- `channels/index.md` — 헤더 10-29 · **10-29 스캔 노트** 추가(Slack 6일 조용 vs 대시보드 신규 9건 — 등록 주체 이동 주석).
- README.md 재생성 예정(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차)**: **쇼핑백 1만개·15ml 세트박스 슬리브 발주가 2일 연속 연기돼 오늘(10-29)이 재마감** — 단가 4,082원은 확정됐으나 발주서·견적 원본이 위키에 없다. 12월 미국 20,000세트 양산 리드타임 감안 시 **이번 주 발주서 발송이 마지노선**.
- **신규(1일차)**: **`씰링 스티커도 다국어야 하나`(10-28) 경과 1일 미판단** vs **밀봉 방식(스티커 vs 수축필름) 10-30 회의** — 순서 충돌이 이틀째. 10-30 회의에서 ① 밀봉 방식 → ② 다국어 범위 순으로 정리 필요.
- **신규(1일차)**: **원티드 지원자명 불일치** — 전일 등록 제목 `임상현`, 완료 레코드 `이상빈`. 동일 업무 지원자 교체인지 별건인지 확인 필요(제목 변경 이력 미기록).
- **신규(1일차)**: **`[칸겐뷰트]` 오타 2건**(→ `[칸겐뷰티]`) — 대시보드 업무 제목 수정 권장.
- **신규(1일차)**: **`카페24 보증보험 사전연장 여부 검토`(11-28) 담당자 공백** — 담당자 공백 6건으로 증가.
- **신규(1일차)**: **이향석 계정에서 10-28 17:20~17:51 6건 연속 등록** — 더마테스트 견적·폴스타 차량보험·인쇄물 기준·SVC 2건·카페24. 전부 `project_id` 미지정·프로젝트 무관 관리 라인이라 **프로젝트 페이지에 반영할 근거가 없다**. 향후 유지보수 라인을 프로젝트로 묶을지 판단 필요.
- **신규(1일차)**: **샘플 세트박스 표기 면제 규정이 10-28 완료됐으나 규정 내용(문서·메시지)이 위키·Slack 어디에도 없다** — 확정 규정 전문 확보 후 §3 예외 조항으로 명문화 필요.
- **신규(2일차)**: `[컨설팅] 11/04~11/06 재무·회계 정부지원(80%)` + `[SVC] 11/05 재무관리 교육` + `[세무] 세무법인 결정`(11-05) + `카니발 법인승계 스왑처리`(10-30) — **11월 첫 주에 재무·세무 일정 4건 집중**.
- 미조치(2일차): 프로젝트 13개 중 **12개 보류·진행중 0개** 유지 — 실제 활동(채용·SNS·포장)이 재개된 프로젝트도 상태값 '보류' 그대로.
- 미조치(7일차): **아세안 5개국 규제자료 요청** — 태국 라인만 3단계 확장, **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음(6일째).
- 미조치(4일차): **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- 미조치(42주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(36주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-29 재확인 — 활성 15개 목록에 없음)
- 미조치(6주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **23일째**, 실질 업무 114건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·자극테스트 경과)과 불일치
- 미조치(계속): 담당자 공백 6건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'등록 주체의 이동'**이다. Slack은 6일째 완전히 조용하고, 대시보드에는 이향석 계정으로 32분간 6건이 연속 등록됐다 — 강경철(포장/문안)·전경표(채용/규제) 라인이 주던 등록 흐름이 하루 만에 개발·관리 라인으로 넘어왔다. 내용도 성격이 다르다: 더마테스트 견적, 법인 차량(폴스타) 보험 갱신, 인쇄물 기록물 관리 기준, SVC 교육·엡버서더 인터뷰, 카페24 보증보험 — **제품·수출 라인이 아니라 회사 운영·유지보수 라인**이다. 완료 쪽에서는 **`[Web] cosmetic-review 서비스 추가`가 5주 만에 종결**(마감 2일 조기)됐고, 태국 라벨링 리서치도 1일 늦게 완료되며 태국 트랙이 '문안 → 라벨 → 포장재 규제'로 계단식 확장 중이다. 반면 **부자재 발주(쇼핑백 1만개·15ml 슬리브)는 이틀 연속 연기**돼 오늘이 재마감이고, **씰링 스티커 다국어 판단은 밀봉 방식 결정보다 먼저 도래한 채 경과**했다 — 12월 양산 일정과 직결되는 두 건이 오늘·내일 안에 정리돼야 한다. TSonaX는 코드 15일째·대시보드 8일째 정지다.

## [2026-10-30] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 119건 동기화 완료

## [2026-10-30] sync | 일일 동기화 — Slack 7일 연속 0건 · 대시보드 신규 8·완료 5(삭제 0) · 업무대시보드 정리회의가 마감 7건 재조정 · 부자재 발주 3번째 마감 미준수
- 실행: 05:00 KST 크론. 44주차(일일 카운터 기준).

### STEP 1 — DB 동기화
- `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **119건**(10-29 115건 대비 **+4**). 17개 파일 자동 갱신(projects/ 13 · projects/index · concepts/브랜업-대시보드-현황 · index).
- **전일 대비 필드 diff**(`branup_snapshot_20261029.json` 대비): **신규 8 · 목록 제거 4 · 레코드 변경 7**.
- **신규 8건 전건 10-29 생성**(07:05~16:42) — ① **`업무대시보드 정리회의`**(강경철·노수민·이상원·이향석·전경표 5인, 마감 10-29, 07:05:33 생성·09:34 갱신) ② `본계약 기준 문안 정리해서, 국가별 언어 번역 부탁드리자(에나지크한테)`(강경철, 10-30, 11:32) ③ `JNM코리아에게 전성분 및 라벨 전달`(강경철, 10-30, 12:35) ④ `태국 화장품시설등록 관련 가이드 작성`(강경철, **10-29**, 12:40 — **등록 즉시 경과**) ⑤ `FEDEX 물류비 관련 알아보기`(강경철, 10-29, 12:41) ⑥ `[칸겐뷰티] 타 브랜드 / 트래픽 높은 광고소재 데이터 취합`(전경표, 10-29, 13:11) ⑦ `더마브랜드 퍼널구조 설계`(전경표, 11-07, 13:12) ⑧ **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`**(이향석, 11-02, 16:42).
- **목록 제거 4건 = 전건 '완료' 실측**(`/api/tasks/completed` 374 → **379건**, **삭제 0건**): `동국 발주서 작성`(강경철, **09:08:02**) · `정부지원사업 매주 확인`(전경표, **11:02:45**) · `전성분(Mink Oil) 변경 여부 확인`(강경철, **12:27:43**) · `헤어 디바이스 상품제안서 검토`(**제목 변경 후** `… - 완료/보고 대기`, 전경표, **18:20:02**, 마감 10-26 → 3일 늦음). 별도로 목록 미경유 `[대표님 요청] 단체티 제작`(전경표, 13:02:43) → **10-29 실제 완료 5건**.
- **레코드 변경 7건** = 마감 연기 5 + 마감 신규 부여 1 + 제목 변경 2(중복 3건은 제목+마감 동시): `씰링 스티커도 다국어야 하나`(10-28 → **10-30**, 09:07) · `CDRI 쇼핑백 및 씰링 스티커 관련 문의`(10-28 → **10-30**, 09:08) · `칸젠 민감 피부자극테스트` → **`더마프로 민감 피부자극테스트 -> 최종리포트 대기중`**(10-23 → **10-30**, 08:57) · `더마테스트 견적서 요청` → **`[보류] … -> 최유미교수님과 테스트 결정`**(10-28 → 10-29, 09:59) · `[칸겐뷰트] 샘플 봉합 실링 스티커 규제 리서치`(10-28 → **11-04**, 13:07) · `[칸겐뷰트] 종이 쇼핑백 규제 리서치`(10-28 → **11-04**, 13:07) · `브랜업 반기 분기 년예상 프로젝트 별 매출/영업이익`(**마감 없음 → 11-09**, 10:10 — 10-21 마감 삭제 이후 첫 기한 재부여).
- ⏱ **패턴: 회의(07:05) → 08:57~10:10 마감 일괄 재조정 → 11:32~16:42 신규 5건 등록.** 즉 10-29는 `업무대시보드 정리회의`가 보드 정리를 실제로 실행한 날이며, **재조정은 전부 09~10시대에 집중**됐다.
- 통계: 마감 경과 **62건**(전일 62 → 동일), **60일 이상 35건**(+1, 56%), **D-0 18건**(10-30) · **D-1 1건**(10-31 태국 문안) · **D-2 0건** · **D-3 4건**(11-02) · D-4~7 8건, `due_at` 미입력 **14건**, 담당자 공백 **6건**, `project_id` 미지정 **114/119**(96%), 상태 진행중 118 · 지연 1, 프로젝트 **보류 12 · 완료 1 · 진행중 0**. 담당자별 경과: **강경철 33** · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 이상원 계열 4 · 최유미 1 · 이향석 1. 완료 이력 통계: **379건 중 지연완료 198건(53%)** · 정시 173 · due/closed 없음 8.
- ℹ️ 10-29 스냅샷 파일은 dict가 아닌 **list** 형태로 저장돼 있었다(diff 스크립트가 `old.items()`에서 실패 → dict/list 양쪽 처리로 수정). 향후 스냅샷 로더는 두 형태를 모두 지원해야 한다.

### STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-29 03:00 KST / 168시간 창 = 10-23 05:00 KST)
- **업무 신규 메시지 0건 / 신규 파일 0건**. 26시간 창 신규 **0건** → **10-24~10-30 7일 연속 0건**.
- 168시간 창 누적 **1건**(`#wiki` 10-23 18:03 자체 발행 주간 린트 리포트) — 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **7일째 변동 없음**.
- 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · rename 최근 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 신규 생성 0건(`헤르메스`·`브랜업-조직구성`·`브랜업-휴가`는 168시간 활동 0).
- 수집 방식: `curl` subprocess(urllib 대용량 truncation 회피) + 시간필터 없이 `limit:60` 후 스크립트 내 비교.

### STEP 2b — 북마크 + Canvas 스캔
- Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel` — bookmarks.list·conversations.history 각 1건).

### STEP 2c — 프로젝트 페이지 활동
- `projects/kcl_sgs_안정성검사_사업_실행_12_31` — **10-30 항목 신설**: ① `칸젠 민감 피부자극테스트` → **`더마프로 … 최종리포트 대기중`**(시험기관 더마프로 확정, 10-23 → 10-30) ② `더마테스트 견적서 요청` **보류 처리**(최유미 교수 라인으로 별도 결정) ③ **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`**(11-02, 2차 사업계획 변경) ④ 상태값 '보류' 불일치 지적.
- `projects/칸겐뷰티_sns_운영` — **10-30 항목 신설**: 전경표가 `[칸겐뷰티] 광고소재 데이터 취합`·`더마브랜드 퍼널구조 설계` 2건을 신규 등록 → **김봉재 퇴사 이후 공백 라인에 전경표 진입 신호**. 단 `project_id` 미지정·담당자(김봉재) 미변경 상태라 귀속은 미확정.
- 나머지 신규 8건은 `project_id=None` → 프로젝트 귀속 근거 없음(문안·라벨·태국·물류·마케팅·KCL 라인은 concepts/ 페이지에서 추적).

### STEP 3 — Wiki 페이지 갱신
- `concepts/tsonax.md` — 연혁 **10-30 항목 추가**, 헤더 **16일째 정지**·기한 없는 진행중 **9일째**, 표 캡션 10-30 기준, 소스 푸터 갱신(119건 / 379건). 개발 브랜치 `git ls-remote origin` 실측: tip `c6041cd`(10-14 12:47)·master `e42d7c9`(09-02) 무변동.
- `concepts/kangen-뷰티-문안-바코드-표준.md` — **§10 신설(10-30 후속)**: ① **부자재 발주 2건 3번째 마감 미준수**(10-27 → 10-29 → 경과 1일, 발주서 미발송) ② `세트박스 문안 검토` 경과 ③ `전성분(Mink Oil)`·`동국 발주서` 완료 ④ 씰링 다국어·CDRI 문의·밀봉방식 회의 **3건 10-30 동시 도래** ⑤ **문안 트랙이 '검토' → '확정본 외부 이관(에나지크 번역 요청·JNM 전달)'으로 이동**, 확정본 문서 부재 ⑥ 포장재 규제 리서치 2건 11-04 연기.
- `concepts/칸겐보떼-아세안-규제-신고-자료.md` — **태국 4단계 확장**(`태국 화장품시설등록 관련 가이드 작성` 신규, 등록 즉시 경과), `태국 문안 정리` 10-31 D-1, 포장재 규제 11-04 연기, **홍콩(1순위) 7일째 업무 0건**, 회신 기한 부재 7일째.
- 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).

### STEP 4 — 네비게이션
- `index.md` — 헤더 10-30 · 총 62페이지 · TSonaX 요약(16일째 정지·D-0 18건·119건·완료 5건) · `브랜업-대시보드-현황` 119건 · `업무-완료-판별` **379건 / 지연완료 198건(53%)** + 담당자별 지연완료 · 아세안(태국 4단계·홍콩 7일) · 문안 표준 **§10** · **10-30 크론 노트** 추가.
- `channels/index.md` — 헤더 10-30 · **10-30 재확인(ID 15/15·매핑 10/11)** + **10-30 스캔 노트**(7일 연속 0건) 추가.
- `README.md` 재생성(`wiki_readme_generator.py`).

### 미조치 (사용자 판단 필요)
- **신규(1일차) 🔴 최우선**: **부자재 발주 2건(쇼핑백 1만개·15ml 세트박스 슬리브)이 10-27 → 10-29 → 경과로 3번째 마감을 넘겼다** — 10-29 `업무대시보드 정리회의`에서도 재조정 대상에서 빠졌고, 단가(4,082원)만 확정된 채 발주서·견적 원본이 위키에 없다. 12월 미국 20,000세트 양산 리드타임상 **오늘(10-30) 발주서 발송이 마지노선**.
- **신규(1일차)**: **`업무대시보드 정리회의`(10-29, 5인)의 결정·회의록이 위키·Slack 어디에도 없다** — 마감 7건 재조정과 더마테스트 보류가 이 회의 결과로 보이나 근거 문서 부재. 회의록 확보 후 결정사항을 채널/프로젝트 페이지에 명문화 필요.
- **신규(1일차)**: **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(11-02)** — 서베이 수행사가 바뀐 사유·새 회사명이 위키에 없다. 09-28 1차 사업계획 변경 이후 **2차 변경**이므로 KCL 협의 필요 여부 확인.
- **신규(1일차)**: **"본계약 기준 문안" 확정본 부재** — 에나지크에 국가별 번역을 요청한다는 업무(10-30)가 등록됐지만 기준 문서가 위키에 없어 어떤 문안이 번역 기준인지 추적 불가(§5 `세트박스 문안 확정본 부재`와 동일 공백 반복).
- **신규(1일차)**: **`태국 화장품시설등록 관련 가이드 작성`** — 마감(10-29)이 등록 시각(12:40)보다 앞서 **등록 즉시 경과**로 출발. 전경표 규제 리서치 2건과 동일 패턴이 **3회째** → 업무 등록 시 마감일 검증 규칙 필요.
- **신규(1일차)**: `더마프로 민감 피부자극테스트 -> 최종리포트 대기중`(10-30) — **최종 리포트 수령 여부·시험 결과(판정)** 가 위키에 없다. 리포트 확보 시 `projects/kcl_sgs_안정성검사_사업_실행_12_31`에 결과 요약 등재 필요.
- **신규(1일차)**: **전경표 마케팅 라인 진입**(`광고소재 데이터 취합`·`퍼널구조 설계`) — `칸겐뷰티 SNS 운영` 프로젝트 담당자가 여전히 김봉재(퇴사)로 남아 있어 **담당 재배정 결정**이 필요(재배정 시 이후 활동이 자동 귀속).
- **신규(1일차)**: 10-29 스냅샷 파일이 **list 형태**로 저장돼 diff 스크립트가 실패했다 — 스냅샷 저장 포맷(dict)을 고정하거나 로더에서 양쪽 지원 필요.
- 미조치(2일차): **`씰링 스티커도 다국어야 하나` vs `본품 씰링 스티커 vs 수축필름` 3일째** — 이제 같은 날(10-30) 도래. **① 밀봉 방식 → ② 다국어 범위** 순서로 하루 안에 결론 필요.
- 미조치(3일차): 프로젝트 13개 중 **12개 보류·진행중 0개** 유지 — 실제 활동(KCL 시험·마케팅·포장)이 재개된 프로젝트도 상태값 '보류' 그대로.
- 미조치(8일차): **아세안 5개국 규제자료 요청** — 태국만 4단계 확장, **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음(7일째).
- 미조치(5일차): **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- 미조치(43주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(37주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-30 재확인 — 활성 15개 목록에 없음)
- 미조치(7주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **24일째**, 실질 업무 118건
- 미조치(계속): `projects/kcl_sgs_안정성검사_사업_실행_12_31` 대시보드 상태값(보류)이 실제 진행(시험 수행·리포트 대기·사업계획 변경)과 불일치 — 이제 격차가 더 벌어짐
- 미조치(계속): 담당자 공백 6건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'보드 정리 이후의 공백'**이다. 10-29 아침 5인이 `업무대시보드 정리회의`를 열고 09~10시에 마감 7건을 재조정했지만, **가장 시급한 부자재 발주 2건은 그 손질에서 빠져 3번째 마감을 넘겼다** — 회의가 '기한을 미루는 정리'에 집중하고 '결제·발주 집행'은 건드리지 못한 셈이다. 대신 새로 등록된 5건의 방향은 분명하다: 본계약 문안을 에나지크에 넘겨 국가별 번역을 붙이고, JNM에 전성분·라벨을 전달하고, 태국은 시설등록까지 내려간다 — **문안·규제 트랙이 내부 검토에서 외부 제출 단계로 넘어간 것**이다. 리스크는 그 산출물의 원본이 위키에 없다는 점(확정 문안·회의록·서베이 변경 사유 모두 부재)이고, KCL은 시험기관이 더마프로로 확정돼 리포트만 남았는데 대시보드 상태는 여전히 '보류'다. Slack은 7일째 완전히 조용하고 TSonaX 코드는 16일째 멈춰 있다 — 업무의 유일한 유입 경로가 대시보드 직접 등록이라는 구조가 이제 **8일째** 굳어졌다.

## [2026-10-30] lint | 74 issues found (치명 0 · 경고 13 · 주의 1 · 정보 60)
- 점검 범위: 62 콘텐츠 페이지(channels 11 · entities 17 · concepts 21 · projects 13) + raw 56 md · log 180 엔트리
- **깨진 위키링크 0건** — 대신 `channels/index.md` 2건의 렌더링 결함 수정: 뷰티-프로젝트 행의 `concepts/에나지크-글로벌-물류-패키징-전략` 별칭 링크와 kcl-해외인증실증지원사업 행의 `concepts/kcl-overseas-certification-2026` 별칭 링크에서 **파이프 앞 백슬래시 4개 → 1개**(테이블 이스케이프 정상형)로 교정. 이 링크들은 resolver가 백슬래시를 제거해 '정상'으로 통과시켰으므로 렌더링 기준으로 별도 점검했다.
- 고아 6건 / index 미등재 7건 — `concepts/task-status`(고아 아님·미등재), `concepts/project-status`, `entities/project-*` 5건(ai_ax_직원_교육·브랜업_대시보드_개발·소라살롱_공구_프로젝트·시니어_마케터_채용_프로젝트·에나지크_발주_시뮬레이터). `entities/project-*` 5건은 `projects/` 동명 페이지(26~28줄 vs 34~147줄)의 **2026-09-25 스냅샷 중복** → `_archive/` 이동 후보(사용자 승인 대기, 5주차).
- index 정합: 선언 62 = 실측 62(내비 2개 제외) 일치 · ghost 0 · frontmatter 누락 0 · `contested: true` 0
- 태그 감사: 미등재 1종(`task` = `concepts/task-status` 전용, SCHEMA.md 2026-10-02 린트에 등재 보류 명시) → **예상된 예외**, 아카이브 시 자동 해소
- stale(90일+) 14건 — aizel 5건(07-14~07-19) · drsante·peachy·slack-adoption·export-voucher·product-liability-insurance·integrated-weekly-strategy·project-status·task-status · `channels/브랜업-온보딩`(92일)·`channels/브랜업-에듀`(99일)
- 200줄 초과 5건 — `entities/브랜업-신입직원-온보딩-매뉴얼`(802) · `channels/코스메틱-본부`(288) · `entities/enagic-usa`(256) · `channels/branup-design-backup`(219) · `concepts/에나지크-글로벌-물류-패키징-전략`(205)
- raw sha256: 불일치 15(전건 단일 ingest 커밋 → **해시 산출 규칙 불일치, 소스 drift 아님**) · source_file 바이너리 해시 4(정상 규약) · placeholder 18(drift 판정 불가) · sha256 필드 없음 4
- log.md 180 엔트리(로테이션 기준 500 미만) · confidence medium/low 25건(단일 출처 다수) · `sources:` 누락 0
- 파일 변경: `channels/index.md`(링크 2건 수정), `log.md`(본 엔트리)

## [2026-10-31] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 120건 동기화 완료

## [2026-10-31] ingest | 일일 Slack + 대시보드 동기화 (45주차)
- 범위: 활성 Slack 15채널 전량 · Canvas/북마크 스캔 · 대시보드 API(활성 120건 / 완료 382건 / 프로젝트 13개) · 프로젝트별 전일 diff
- **STEP 1 — 대시보드 동기화:** 프로젝트 13개 · 업무 **120건**(10-30 119건 대비 **+1** = 신규 4 − 목록 제거 3, **레코드 변경 3**). `projects/` 13건 + `projects/index.md` + `concepts/브랜업-대시보드-현황` 자동 갱신(최근 활동 섹션 보존).
- **신규 4건 전건 10-30 생성 — 전부 이향석·최유미 라인**: ① `에너지크 스케줄`(최유미, 10-30 = **등록 즉시 경과**, "에너지크 R&D sku 제품 기획서 심플하게 + 스케줄표") ② `장재욱 건강보험 가족 피부양자 추가`(이향석, 11-02) ③ `테슬라 사이버트럭 리스 계약 준비중...`(이향석, 11-03 — 사업자등록증·법인인감증명서·법인등기부등본·주주명부·2개년 표준재무제표 등 **15종 서류 체크리스트**) ④ **`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`**(이향석, 11-06 — 생성/완료/드랍/삭제 시 담당자 알림 = **대시보드 기능 개선 요청**).
- **목록 제거 3건 전건 '완료' 실측**(`/api/tasks/completed` 379 → **382건**, 삭제 0건) — **10-30 17:37~17:39 3분 내 일괄 종결**: `[보류] 더마테스트 견적서 요청`(17:37:48) · `업무대시보드 정리회의`(17:37:57, 5인) · **`더마프로 민감 피부자극테스트 -> 최종리포트 받음.`**(17:39:25 — 제목 '대기중'→'받음' 변경 후 완료, 10-23 등록 후 **7일 만에 종결**).
- **레코드 변경 3건 = 전건 마감 연기**: `[폴스타] 보험갱신`(10-30 → 11-03, 제목 '준비완료 -> 갱신 신청하기') · `브랜업캠퍼스 신규 법인설립…`(10-30 → 11-04, 제목 '인감카드, 사업자등록신청 완료') · `카니발 법인승계 스왑처리`(10-30 → 11-06). `test_escalate_probe_20261006` 잔존 → 실질 업무 119건.
- **통계:** 마감 경과 **62 → 75건(+13)** · **60일 이상 37건**(+2, 49%) · **D-0 1건**(10-31 `태국 문안 정리`) · D-1 0건 · **D-2 5건**(11-02) · D-3 2건(11-03) · D-4~7 12건 · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 **115/120**(96%) · 상태 진행중 119 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**. 담당자별 경과: **강경철 47**(63%) · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 최유미 2 · 이상원 계열 3. 완료 **382건 중 지연완료 200건(53.5%)** · 정시 174 · due/closed 없음 8.
- ℹ️ 오늘 diff 스크립트가 `priority` 필드를 비교 대상에 추가했으나 전일 스냅샷에 해당 키가 없어 **116건이 '변경'으로 오탐**됐다 → 필드 존재 여부를 먼저 확인하는 방식으로 재계산해 **실제 변경 3건**으로 정정.
- **STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-30 03:00 KST / 168시간 창 = 10-24 05:00 KST)**
  - **업무 신규 메시지 0건 / 신규 파일 0건.** 26시간 창 신규는 `#wiki` **10-30 18:02 자체 발행 주간 린트 리포트 1건**(비업무) → **10-24~10-31 8일 연속 0건**.
  - 168시간 창 누적 **1건** — 창이 하루 밀리며 10-23 `뷰티-프로젝트` 4건·`코스메틱-본부`·`브랜업-전체` Canvas가 168시간 밖으로 이탈(5 → 1건). 업무 대화 기준 최신은 `#뷰티-프로젝트` **10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **8일째 변동 없음**.
  - 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · rename 최근 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 신규 생성 0건.
  - 수집 방식: `curl` subprocess(urllib 대용량 truncation 회피) + 시간필터 없이 `limit:60` 후 스크립트 내 비교.
- **STEP 2b — 북마크 + Canvas 스캔:** Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel` — bookmarks.list·conversations.history 각 1건).
- **STEP 2c — 프로젝트 페이지 활동:** `projects/kcl_sgs_안정성검사_사업_실행_12_31` — **10-31 항목 신설**: ① **더마프로 민감 피부자극테스트 '최종리포트 받음.' 10-30 17:39:25 완료**(10-30 회차 미조치 '리포트 수령 여부 판정불가' 종결 — 단 **리포트 원문·판정 결과는 여전히 미확보**) ② `[보류] 더마테스트 견적서 요청` 10-30 17:37:48 완료(최유미 교수 라인 일원화) ③ `업무대시보드 정리회의` 10-30 17:37:57 완료(회의록은 부재 유지) ④ `[KCL] 수정사업계획서` 11-02 D-2 ⑤ 프로젝트 상태값 '보류' 유지 — 실제 진행과 격차 확대. 나머지 신규 4건은 `project_id=None` → 프로젝트 귀속 근거 없음(재무·차량·보험 라인은 concepts/ 페이지에서 추적).
- **STEP 3 — Wiki 페이지 갱신**
  - `concepts/tsonax.md` — 연혁 **10-31 항목 추가**, 헤더 **17일째 정지**·기한 없는 진행중 **10일째**, 표 캡션 10-31 기준, 소스 푸터 갱신(120건 / 382건). 개발 브랜치 `git ls-remote origin` 실측: tip `c6041cd`(10-14 12:47)·master `e42d7c9`(09-02) 무변동.
  - `concepts/kangen-뷰티-문안-바코드-표준.md` — **§11 신설(10-31 후속)**: ① **부자재 발주 2건 4번째 마감(10-29 → 경과 2일, 발주서·견적 원본 부재)** ② `세트박스 문안 검토` 경과 2일 ③ `태국 문안 정리` **10-31 D-0(5일째 미완)** ④ `태국 화장품시설등록 가이드` 경과 2일(등록 즉시 경과 3회째) ⑤ **10-30 하루 문안·포장 라인 마감 재조정 0건** — 신규 4건 전부 재무·차량·보험·사내 알림 ⑥ **"본계약 기준 문안" 확정본 공백 3일째**(번역·전달 업무 둘 다 경과 1일).
  - `concepts/칸겐보떼-아세안-규제-신고-자료.md` — **10-31 현황 추가**: 태국 문안 D-0(5일째 미완), 시설등록 가이드 경과 2일, 포장재 규제 11-04 D-4, **홍콩(1순위) 8일째 업무 0건**, 회신 기한 부재 8일째, 10-30 재조정·완료 0건.
  - 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).
- **STEP 4 — 네비게이션:** `index.md`(헤더 10-31 · 총 62페이지 · TSonaX 요약 17일째 정지·경과 75건·D-0 1건·120건 · KCL 프로젝트 더마프로 리포트 수령 · 문안 §11 · 아세안 10-31 · 대시보드 120건 · **10-31 크론 노트**), `channels/index.md`(헤더 10-31 + **10-31 스캔 노트** — 8일 연속 0건), `README.md` 재생성(`wiki_readme_generator.py`).
- **미조치 (사용자 판단 필요)**
- **신규(1일차) 🔴 최우선**: **부자재 발주 2건(쇼핑백 1만개·15ml 세트박스 슬리브)이 10-27 → 10-29 → 경과 2일로 4번째 마감을 넘겼다** — 10-30에는 마감 재조정조차 없었고 단가(4,082원)만 확정된 채 **발주서·견적 원본이 위키에 없다**. 12월 미국 20,000세트 양산 리드타임상 **발주 집행이 이미 늦은 상태**.
- **신규(1일차)**: **10-30 D-0 18건 중 15건이 그대로 경과 편입** → 전사 마감 경과 **62 → 75건(+13)**, 그중 **강경철 47건(63%)**. 마감일 연기만 반복되고 집행이 없는 구조가 이틀 연속 확인.
- **신규(1일차)**: **`더마프로 민감 피부자극테스트` 최종 리포트 원문·판정 결과가 위키에 없다** — 업무는 '리포트 받음'으로 종결됐으나(PDF·판정 미확보) KCL 사업 산출물로 등재 불가. 파일 확보 필요.
- **신규(1일차)**: **`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`(이향석, 11-06)** — 대시보드 자체 기능 개선 요청이 업무로 편입. 브랜업-watcher/API 연동 범위와 중복 여부 확인 필요.
- **신규(1일차)**: `테슬라 사이버트럭 리스 계약 준비`(이향석, 11-03) — 법인 명의 리스로 보이나 **차량 용도·계정 귀속(브랜업/브랜업캠퍼스) 미기재**, 15종 서류 체크리스트만 요약에 있음.
- 미조치(2일차): **`업무대시보드 정리회의`는 10-30 17:37 완료 처리됐지만 회의록·결정 산출물이 여전히 없다** — 마감 7건 재조정·더마테스트 보류 결정의 근거 문서 부재.
- 미조치(2일차): **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(11-02 D-2)** — 서베이 수행사 변경 사유·새 회사명 미확인, 09-28 1차 변경에 이은 2차 변경.
- 미조치(3일차): **"본계약 기준 문안" 확정본 부재** — 에나지크 국가별 번역·JNM 전달의 기준 문서가 위키에 없어 산출물 추적 불가.
- 미조치(2일차): **`태국 화장품시설등록 관련 가이드 작성` 등록 즉시 경과 패턴 3회째** — 업무 등록 시 마감일 검증 규칙 필요(`에너지크 스케줄`도 10-30 13:18 등록·마감 10-30으로 4회째).
- 미조치(2일차): 전경표 마케팅 라인 진입(`광고소재 데이터 취합`·`퍼널구조 설계`) — `칸겐뷰티 SNS 운영` 담당자가 여전히 김봉재(퇴사)로 남아 **담당 재배정 결정** 필요.
- 미조치(3일차): `씰링 스티커도 다국어야 하나`·`본품 씰링 스티커 vs 수축필름` **둘 다 경과 1일** — 밀봉 방식 → 다국어 범위 순서로 결론 필요.
- 미조치(4일차): 프로젝트 13개 중 **12개 보류·진행중 0개** 유지 — 실제 활동(KCL 리포트 수령·마케팅·포장)이 있는 프로젝트도 상태값 '보류' 그대로.
- 미조치(9일차): **아세안 5개국 규제자료 요청** — 태국만 4단계 확장, **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음(8일째).
- 미조치(6일차): **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- 미조치(44주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(38주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (10-31 재확인 — 활성 15개 목록에 없음)
- 미조치(8주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **25일째**, 실질 업무 119건
- 미조치(계속): 담당자 공백 6건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'종결 3건과 정체 2건의 대비'**다. 10-30 17:37~17:39 3분 사이에 7~10일 묵은 항목 3건(더마프로 리포트·더마테스트 보류·보드 정리회의)이 한꺼번에 종결됐다 — 특히 더마프로는 10-23 등록 후 7일 만에 **'리포트 받음'**으로 끝나 KCL 사업의 시험 단계가 실질 종료됐다. 반면 같은 날 포장·문안 라인은 **재조정 0건·신규 0건**으로 완전히 멈췄고, 그 결과 10-30 D-0 18건 중 15건이 그대로 경과로 넘어가 **전사 경과가 하루에 13건 늘었다(62→75)**. 신규 4건도 전부 재무·차량·보험·사내 알림이라 **사업 본선(발주·문안·규제)과 무관한 라인**이다. 구조적으로는 **'마감일을 미루는 조정'이 집행을 대체**하는 패턴이 굳어졌고(강경철 47건 경과, 전체의 63%), 동시에 **'산출물 원본이 위키에 없다'**는 공백이 세 갈래로 반복된다 — 더마프로 리포트 PDF, 본계약 기준 문안 확정본, 보드 정리회의 회의록. Slack은 8일째 완전히 조용하고 TSonaX 코드는 17일째 멈춰 있어, 업무 유입 경로는 **대시보드 직접 등록 단일 경로**로 9일째 고정됐다.
- 파일 변경: `concepts/tsonax.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`)

## [2026-11-01] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 120건 동기화 완료

## [2026-11-01] ingest | 일일 Slack + 대시보드 동기화 (46주차)
- 범위: 활성 Slack 15채널 전량 · Canvas/북마크 스캔 · 대시보드 API(활성 120건 / 완료 382건 / 프로젝트 13개) · 전일 diff
- **STEP 1 — 대시보드 동기화:** 프로젝트 13개 · 업무 **120건 — 전일(10-31)과 완전 동일**(신규 **0** · 목록 제거 **0** · 레코드 변경 **0**). `title/assignee/due/status/project_id/priority` 6개 필드 전량 대조에서 diff 0건. **사람이 손댄 최근 갱신은 여전히 10-30 17:47:49**(`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`)로 **2일째 정지** — 10-31(토)·11-01(일) 이틀간 대시보드 이벤트가 0건이다. `/api/tasks/completed` **382건 무변동** = **10-31·11-01 완료 0건**(마지막 완료는 10-30 17:39:25 더마프로 리포트). `projects/` 13건 + `projects/index.md` + `concepts/브랜업-대시보드-현황` 자동 갱신(최근 활동 섹션 보존).
- **통계:** 마감 경과 **75 → 76건(+1)** — 유일한 유입은 전일 D-0였던 `태국 문안 정리`(강경철, 마감 10-31)가 **미완으로 경과 편입**(-1일)된 것. **60일 이상 37건**(49%) 유지 · **D-0 0건**(11-01) · **D-1 5건**(11-02: `[주간업무전략] 11월 1주`·`[재무보고] 11월 1주`·`인쇄물 관리 기준마련`·`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`·`장재욱 건강보험 가족 피부양자 추가`) · **D-2 2건**(11-03 `[폴스타] 보험갱신`·`테슬라 사이버트럭 리스`) · **D-3 5건**(11-04) · D-4~7 7건 · `due_at` 미입력 **14건** · 담당자 공백 **6건** · `project_id` 미지정 **115/120**(96%) · 상태 진행중 119 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(10-23 보류 전환 이후 **10일째**). 담당자별 경과: **강경철 48**(63%) · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 최유미 2 · 강경철·이상원 2 · 이상원 1. 완료 **382건 중 지연완료 200건(53.5%)** · 정시 174 · due/closed 없음 8. ⚠️ 전일 diff 스크립트의 `priority` 오탐 문제는 이번 회차에 **필드 존재 여부 선확인 가드**를 넣어 재발하지 않았다(diff 0건 정상 산출).
- **STEP 2 — Slack 채널 스캔 (활성 15개, 26시간 창 = 10-30 18:00 UTC / 168시간 창 = 10-25 05:00 KST)**
  - **업무 신규 메시지 0건 / 신규 파일 0건.** 26시간 창 신규 **0건** — **업무 대화 기준 9일 연속 0건**. 168시간 창 누적 **1건**은 `#wiki` 10-30 18:02 자체 발행 주간 린트 리포트(비업무)뿐이며, **업무 대화 기준 최신은 `#뷰티-프로젝트` 10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **9일째 변동 없음**.
  - 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · rename 최근 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 **신규 생성 0건**(`헤르메스`·`브랜업-조직구성`·`브랜업-휴가` 168시간 활동 0).
  - 수집 방식: `curl` subprocess(urllib 대용량 truncation 회피) + 시간필터 없이 `limit:60` 후 스크립트 내 비교.
- **STEP 2b — 북마크 + Canvas 스캔:** Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel` — bookmarks.list·conversations.history 각 1건).
- **STEP 2c — 프로젝트 페이지 활동:** `projects/kcl_sgs_안정성검사_사업_실행_12_31` — **11-01 항목 신설**: ① 🔴 **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(이향석) 내일(11-02) 마감 D-1** — 10-30 17:43 이후 변동 없고 **서베이 수행사 변경 사유·새 회사명은 여전히 미확인** ② 10-31·11-01 이틀 연속 KCL 라인 이벤트 0건 ③ **더마프로 리포트 원문(PDF)·판정 결과 미확보 3일째** ④ 프로젝트 상태값 '보류' **10일째** — 내일 마감 업무가 살아 있는데도 보류 유지(상태값·실적 괴리). 나머지 프로젝트는 대시보드 변동 0·Slack 대화 0으로 귀속 근거 없음.
- **STEP 3 — Wiki 페이지 갱신**
  - `concepts/tsonax.md` — 연혁 **11-01 항목 추가**(120건 전일 동일·경과 76건·D-0 0건·완료 382 무변동), 헤더 **기한 없는 진행중 11일째**·**커밋 18일째**(전일 헤더가 '16일째·10-30 실측'으로 남아 있던 stale 표기 정정), 표 캡션 11-01 기준, #431 `updated_at` 10-21 10:07:42 · #201 10-21 10:09:47 실측 기재, 소스 푸터 갱신.
  - `concepts/kangen-뷰티-문안-바코드-표준.md` — **§12 신설(11-01 후속)**: ① 🔴 **부자재 발주 2건(쇼핑백 1만개·15ml 세트박스 슬리브) 10-29 마감 → 경과 3일**(10-27 → 10-29 → 경과 3일로 **사실상 4번째 마감 미준수**, 발주서·견적 원본 부재) ② 🟡 **`태국 문안 정리` 10-31 D-0 미완 → 경과 1일**(10-27 등록 후 6일째) ③ `세트박스 문안 검토`·`태국 화장품시설등록 가이드` **경과 3일** ④ `본계약 기준 문안 → 에나지크 국가별 번역 요청`·`JNM 전성분·라벨 전달` **경과 2일**(**확정본 공백 5일째**) ⑤ **씰링·수축필름·CDRI 문의·바뀐 용기 문안 번역 4건 동시 경과 2일** — 밀봉 방식 미정이 다국어 범위 판단을 계속 차단 ⑥ **10-31·11-01 이틀간 대시보드 이벤트 0건 = 문안·포장 라인 3일째 재조정·집행 0건**.
  - `concepts/칸겐보떼-아세안-규제-신고-자료.md` — **11-01 현황 추가**: 태국 문안 정리 **경과 1일**(D-0 미완), 시설등록 가이드 **경과 3일**, 포장재 규제 리서치 11-04 D-3 유지, **홍콩(1순위) 9일째 업무 0건**, **회신 기한 부재 9일째**, 태국 라인 3일째 정체.
  - 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).
- **STEP 4 — 네비게이션:** `index.md`(헤더 11-01 · 총 62페이지 · TSonaX 요약 18일째 정지·경과 76건·D-0 0건 · KCL D-1 · 문안 §12 · 아세안 9일째 · 대시보드 120건 이틀째 정지 · **11-01 크론 노트**), `channels/index.md`(헤더 11-01 + **11-01 스캔 노트** — 9일 연속 0건), `README.md` 재생성(`wiki_readme_generator.py`).
- **미조치 (사용자 판단 필요)**
- **미조치(2일차) 🔴 최우선**: **부자재 발주 2건(쇼핑백 1만개·15ml 세트박스 슬리브)이 10-27 → 10-29 → 경과 3일로 4번째 마감을 넘긴 채 주말을 지났다** — 단가(4,082원)·카톤 수지판비 포함 조건만 확정이고 **발주서·견적 원본이 위키에 없다**. 12월 미국 20,000세트 양산 리드타임상 **발주 집행이 이미 지연 구간**이며, 10-31·11-01 대시보드 이벤트가 0건이라 **주말 동안 아무 조치도 없었다**.
- **미조치(2일차)**: **`태국 문안 정리`가 10-31 D-0를 넘겨 경과 1일** — 아세안 5개국 중 첫 착수 국가의 첫 산출물이 **6일째 미완**이다. 마감일을 하루 미루는 재조정도 없이 그대로 경과로 넘어간 점이 전일 패턴과 다르다(전일까지는 '연기'로 처리).
- **미조치(2일차)**: **`더마프로 민감 피부자극테스트` 최종 리포트 원문·판정 결과가 위키에 없다**(3일째) — 업무는 10-30 '리포트 받음'으로 종결됐으나 PDF·판정 미확보로 KCL 사업 산출물로 등재 불가.
- **미조치(3일차)**: **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(11-02 D-1)** — 서베이 수행사 변경 사유·새 회사명 미확인 상태로 **마감 도래**, 09-28 1차 변경에 이은 2차 변경.
- **미조치(2일차)**: **`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`(이향석, 11-06)** — 대시보드 자체 기능 개선 요청이 업무로 편입. 브랜업-watcher/API 연동 범위와 중복 여부 확인 필요.
- **미조치(2일차)**: `테슬라 사이버트럭 리스 계약 준비`(이향석, 11-03 D-2) — 법인 명의 리스로 보이나 **차량 용도·계정 귀속(브랜업/브랜업캠퍼스) 미기재**, 15종 서류 체크리스트만 요약에 있음.
- **미조치(3일차)**: **`업무대시보드 정리회의`는 10-30 17:37 완료 처리됐지만 회의록·결정 산출물이 여전히 없다** — 마감 7건 재조정·더마테스트 보류 결정의 근거 문서 부재.
- **미조치(4일차)**: **"본계약 기준 문안" 확정본 부재** — 에나지크 국가별 번역·JNM 전달의 기준 문서가 위키에 없어 산출물 추적 불가(번역·전달 업무 둘 다 경과 2일).
- **미조치(3일차)**: **`태국 화장품시설등록 관련 가이드 작성` 등록 즉시 경과 패턴 3회째** — 업무 등록 시 마감일 검증 규칙 필요(`에너지크 스케줄`도 10-30 13:18 등록·마감 10-30으로 4회째).
- **미조치(3일차)**: 전경표 마케팅 라인 진입(`광고소재 데이터 취합`·`퍼널구조 설계`) — `칸겐뷰티 SNS 운영` 담당자가 여전히 김봉재(퇴사)로 남아 **담당 재배정 결정** 필요.
- **미조치(4일차)**: `씰링 스티커도 다국어야 하나`·`본품 씰링 스티커 vs 수축필름` **둘 다 경과 2일** — 밀봉 방식 → 다국어 범위 순서로 결론 필요(관련 4건 동시 경과).
- **미조치(5일차)**: 프로젝트 13개 중 **12개 보류·진행중 0개**(10일째) — 내일 마감인 KCL 사업계획서 업무가 살아 있는데도 KCL 프로젝트는 '보류' 그대로.
- **미조치(10일차)**: **아세안 5개국 규제자료 요청** — 태국만 4단계 확장, **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음(9일째).
- **미조치(7일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- **미조치(45주차)**: 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- **미조치(39주차)**: `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (11-01 재확인 — 활성 15개 목록에 없음)
- **미조치(9주차)**: #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- **미조치(계속)**: `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **26일째**, 실질 업무 119건
- **미조치(계속)**: 담당자 공백 6건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'완전 정지'**다. 10-27 이후 업무 유입은 Slack이 아니라 **대시보드 직접 등록 단일 경로**였는데, 그 경로마저 **10-31·11-01 이틀 연속 이벤트 0건**으로 끊겼다(신규 0·완료 0·마감 재조정 0, 최근 사람 갱신 10-30 17:47). Slack도 **9일째 0건**이라, 이번 회차에 위키가 기록할 '새 사실'은 사실상 **`태국 문안 정리`가 10-31 D-0를 미완으로 넘겨 경과 1일로 편입된 것 하나**뿐이다. 그 결과 전사 경과는 75 → **76건**(+1)이고, 60일 이상 37건·강경철 48건(63%) 구조는 그대로다. 주목할 점은 **정체의 질**이다 — 10-30까지는 '마감일을 하루 미루는 재조정'이 집행을 대체하는 패턴이었는데, 주말에는 **그 재조정조차 없이 마감이 그대로 경과로 넘어갔다**. 사업 본선인 부자재 발주 2건은 **경과 3일**(4번째 마감)째 미집행이고, 내일은 **`[KCL] 수정사업계획서 제출`(D-1)**이 서베이 수행사 변경 사유·새 회사명 미확인 상태로 마감을 맞는다. 산출물 원본 공백도 세 갈래(더마프로 리포트 PDF 3일째, 본계약 기준 문안 확정본 5일째, 보드 정리회의 회의록 3일째)로 계속 미해소이고, TSonaX 코드는 **18일째** 멈춰 있다. 요약하면 **'입력(Slack·대시보드)이 모두 닫힌 상태에서 마감만 흘러가는 하루'**였다.
- 파일 변경: `concepts/tsonax.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`)

## [2026-11-02] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 111건 동기화 완료

## [2026-11-02] ingest | 일일 Slack + 대시보드 동기화 (47주차)
- 범위: 활성 Slack 15채널 전량 · Canvas/북마크 스캔 · 대시보드 API(활성 111건 / 완료 385건 / 프로젝트 13개) · 전일 diff
- **STEP 1 — 대시보드 동기화:** 프로젝트 13개 · 업무 **111건**(11-01 120건 대비 **-9** = 신규 **1** − 목록 제거 **10**, **레코드 변경 12**). **11-01(일) 17:14~20:25 '대정리' 세션**이 있었다 — ① **완료 3건, 3분 내 일괄**: `JNM 코리아 컨택 및 미팅 잡기`(**17:14:17**) · `세트박스 문안 검토(영어,불어,전성분)`(**17:14:27**) · `본계약 기준 문안 정리해서, 국가별 언어 번역 부탁드리자(에나지크한테)`(**17:16:41**) — 전건 강경철·전건 마감 경과분. ② **하드 삭제 7건(`closed_at` 0)**: `11/4에 CDRI랑 JNM 미팅 잡기` · **`15ml 세트박스(슬리브) 발주`** · `여유 수량 및 환율에 대한 제안 텍스트 정리` · `[에나지크] 오더별 공유용 타임라인 및 폴더` · `BOM 정리 완료 & 라비오 작업 후 기존 용기 다 빼버릴 것` · `CDRI 쇼핑백 및 씰링 스티커 관련 문의` · `태국 문안 정리`. ③ **마감 연기 12건(전건 경과분)**: +31일 `BOM 정리 작업`·`카톤 개선 작업`·`Plaud 미팅 노션 연동`(10-30 → **11-30**), +16일 `바뀐 용기 문안 포맷 → 다른 언어 번역 검토`·`본품 씰링 스티커 vs 수축필름 비용 비교 및 회의`( → **11-15**), +3~7일 7건(`쇼핑백 1만개 발주서`·`JNM코리아 전성분·라벨`·`태국 화장품시설등록 가이드`·`FEDEX 물류비` → **11-02**, `씰링 스티커 다국어`·`책임판매업자 등록 요건` → 11-05, `제품명 바꿔서 재등록` → 11-06). ④ **신규 1건**: `[리스] 사이버트럭 법인 리스 서류 준비`(이향석, **11-02**, 11-01 20:25:20 생성). 완료 이력 **382 → 385건**(+3). 프로젝트 13건 상태 **보류 12 · 완료 1 · 진행중 0**(11일째 무변동). `projects/` 13건 + `projects/index.md` + `concepts/브랜업-대시보드-현황` 자동 갱신(최근 활동 섹션 보존).
- **통계:** 마감 경과 **76 → 54건(-22)** — 감소분의 내역은 **완료 3 + 삭제 7 + 연기 12 = 22건**이며, **실제 집행으로 끝난 것은 3건뿐**이다. 전일 경과 76건 추적 결과: 여전히 경과 **54** · 완료 **3** · 삭제 **7** · 마감 연기 **12**(잔여 0). **60일 이상 경과 37 → 38건**(+1, 경과의 70%) · **D-0 10건**(11-02) · **D-1 2건**(11-03) · **D-2 5건**(11-04) · D-3~7 13건 · `due_at` 미입력 **14건** · 담당자 공백 **7건** · `project_id` 미지정 **106/111**(95%) · 상태 진행중 110 · 지연 1. 담당자별 경과: **강경철 26**(전일 48 → 22건 감소, 삭제·연기 효과) · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 최유미 2 · 강경철·이상원 2 · 이상원 1. 최근 사람 갱신 **11-01 20:25:30**(`[리스] 사이버트럭 법인 리스 서류 준비`).
- **STEP 2 — Slack 채널 스캔 (활성 15개, 시간필터 없이 `limit:60` 후 스크립트 내 비교)**
  - **업무 신규 메시지 0건 / 신규 파일 0건. 26시간 창 신규 0건 — 업무 대화 기준 10일 연속 0건.** 168시간 창 누적 **1건**은 `#wiki` 10-30 18:02 자체 발행 주간 린트 리포트(비업무)뿐이며, **업무 대화 기준 최신은 `#뷰티-프로젝트` 10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **10일째 변동 없음**.
  - 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · rename 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 **신규 생성 0건**(`헤르메스`·`브랜업-조직구성`·`브랜업-휴가` 168시간 활동 0).
  - 수집 방식: `curl` subprocess(urllib 대용량 truncation 회피).
- **STEP 2b — 북마크 + Canvas 스캔:** Canvas 이벤트 **18건**(전일 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel` — bookmarks.list·conversations.history 각 1건).
- **STEP 2c — 프로젝트 페이지 활동:** `projects/kcl_sgs_안정성검사_사업_실행_12_31` — **11-02 항목 신설**: ① 🔴 **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경` 오늘(11-02) D-0 도래**(10-29 등록, 이향석) — 11-01 대정리에서도 연기·완료·삭제 어느 쪽으로도 손대지 않았다 ② 🆕 **summary 필드에 `Cornerstone Asset service 계약서` 신규 등장** — 10-30까지 summary는 제목과 동일했고, 서베이 수행사 변경의 당사자일 가능성이 높으나 **계약서·변경 사유는 문서로 미확인**(`confidence: medium`) ③ 더마프로 최종 리포트 PDF·판정 **미확보 5일째** ④ 프로젝트 상태 '보류' **11일째**. 그 외 12개 프로젝트는 **project_id 연결 업무 5건 전건 무변동**(변경 0)·Slack 대화 0으로 활동 귀속 근거 없음.
- **STEP 3 — Wiki 페이지 갱신**
  - `concepts/tsonax.md` — 연혁 **11-02 항목 추가**(111건·경과 54건·D-0 10건·완료 385건·정리 세션 완료3/삭제7/연기12), 헤더 **기한 없는 진행중 12일째**·**커밋 19일째**(`git ls-remote origin` 11-02 실측 — tip `c6041cd` 10-14 12:47 · master `e42d7c9`), 소스 푸터 갱신.
  - `concepts/kangen-뷰티-문안-바코드-표준.md` — **§13 신설(11-02 후속)**: ① 문안 라인 3건 일요일 3분 내 일괄 완료 ② 🔴 **`15ml 세트박스(슬리브) 발주` 완료 이력 없이 삭제** — 잔존 활성 업무에서 `슬리브`·`세트박스` 키워드 **0건**으로 '다른 업무로 통합' 근거 없음 → 발주 취소/합산/실수 삭제 **판별 불가** ③ `CDRI 쇼핑백·씰링 스티커 문의`·`태국 문안 정리` 삭제 ④ **'본계약 기준 문안' 확정본 공백은 완료 처리 후에도 지속** ⑤ 연기 12건 표(+31일 3건·+16일 2건) ⑥ 오늘 D-0: 쇼핑백 발주서(7일째)·JNM 전성분·라벨.
  - `concepts/칸겐보떼-아세안-규제-신고-자료.md` — **11-02 현황 추가**: 태국 문안 정리 **삭제**(6일 미완 후, 같은 17:16 완료 건과 중복 정리 가능성은 있으나 단정 보류) → **태국 첫 산출물이 사라져 진척 추적 수단 소실**, 시설등록 가이드 **10-29 → 11-02(+4일) 연기로 D-0**, 포장재 규제 리서치 11-04 D-2, **홍콩 10일째 업무 0건·회신 기한 부재 10일째**.
  - `concepts/브랜업-업무-완료-판별.md` — **§7 신설(하드 삭제 실측)**: 11-01 제거 10건 = **완료 3 + 삭제 7**. 완료 이력 **385건 `status` 전건 `완료`**, **`삭제` 상태 레코드 0건** → **삭제는 감사 추적이 없고, 전일 스냅샷 diff가 유일한 판별 수단**. §4의 종전 결론 "10-08 이후 목록 제거는 예외 없이 완료"에 **폐기 경고 블록 추가**(신규 사실이 기존 결론을 대체 — Update Policy 적용).
  - 신규 entity/concept/comparison/query 페이지 **0건** · 신규 raw 원본 **0건**(Slack 신규 파일 0건).
- **STEP 4 — 네비게이션:** `index.md`(헤더 11-02 · 총 62페이지 유지 · TSonaX 요약 19일째·경과 54건·D-0 10건·111건 · 문안 §13 · 아세안 10일째 · 대시보드 111건 · 완료판별 §7 · **11-02 크론 노트(47주차)**), `channels/index.md`(헤더 11-02 + **11-02 스캔 노트** — 10일 연속 0건), `README.md` 재생성(`wiki_readme_generator.py`).
- **미조치 (사용자 판단 필요)**
- **미조치(신규) 🔴 최우선**: **`15ml 세트박스(슬리브) 발주`가 완료 처리 없이 삭제됐다** — 10-27부터 `쇼핑백(1만개)` 발주와 함께 **부자재 발주 2건**으로 추적된 12월 미국 20,000세트 양산용 건. 활성 111건 전체에 `슬리브`·`세트박스` 키워드 **0건**이라 다른 업무로 합쳐졌다는 근거도 없다. **① 발주 취소 ② 쇼핑백 발주서(오늘 D-0)에 합산 ③ 정리 중 실수 삭제 — 셋 중 어느 것인지 확인 필요.** 같은 날 `CDRI 쇼핑백 및 씰링 스티커 관련 문의`도 삭제돼 문의 회신 여부를 추적할 수 없다.
- **미조치(신규) 🔴**: **`태국 문안 정리`가 6일 미완 후 삭제됐다** — 아세안 5개국 중 첫 착수 국가의 첫 산출물이 완료·산출물 없이 사라져 **태국 대응의 실제 진척을 위키에서 추적할 수단이 없다**. 17:16:41 `본계약 기준 문안 → 국가별 번역` 완료와 중복 정리일 가능성은 있으나 **확정 문안 파일도 없어 대조 불가**.
- **미조치(신규) ⚠️**: **경과 22건 감소는 '정리'의 결과다** — 완료 3 + 삭제 7 + 연기 12. 연기 12건 중 **3건은 +31일(11-30), 2건은 +16일(11-15)**로 밀려 **문안·포장 라인의 결론이 11월 중순 이후로 이동**했다. 경과 지표만 보면 개선으로 오독되므로 **완료/삭제/연기 분리 집계**가 필요하다.
- **미조치(당일) 🔴**: **오늘(11-02) D-0 10건** — `쇼핑백(1만개) 발주서 전달…`(10-27 등록, 7일째, 발주서 원본 0건) · `JNM코리아에게 전성분 및 라벨 전달` · `태국 화장품시설등록 관련 가이드 작성` · `FEDEX 물류비 관련 알아보기` · `[KCL] 수정사업계획서 제출 - 서베이 회사 변경` · `인쇄물 관리 기준마련` · `장재욱 건강보험 가족 피부양자 추가` · `[리스] 사이버트럭 법인 리스 서류 준비` · `[주간업무전략] 11월 1주` · `[재무보고] 11월 1주`.
- **미조치(신규·단서 확보)**: **`[KCL]` 서베이 수행사 변경** — summary에 **`Cornerstone Asset service 계약서`** 문구가 처음 등장(11-02 API). 변경 사유·계약 체결 여부·변경 일자는 여전히 문서로 미확인 → 계약서 원본 확보 필요.
- 미조치(2일차): **"본계약 기준 문안" 확정본 부재** — 업무는 11-01 17:16 완료됐으나 확정 문안 파일·버전이 위키·Slack에 없다. 오늘 D-0인 `JNM 전성분·라벨 전달`의 기준 문서가 확인되지 않는 상태.
- 미조치(6일차): **`더마프로 민감 피부자극테스트` 최종 리포트 원문·판정 결과 미확보** — 업무는 10-30 종결됐으나 KCL 사업 산출물로 등재 불가.
- 미조치(4일차): **`업무대시보드 정리회의`(10-30 17:37 완료) 회의록·결정 산출물 없음** — 11-01 대정리(완료3·삭제7·연기12)의 근거 문서도 함께 부재.
- 미조치(3일차): **`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`(이향석, 11-06)** — 대시보드 자체 기능 개선 요청. **이번 회차의 '삭제 감사 추적 부재' 문제와 직접 연결**되므로 우선순위 상향 검토 권장.
- 미조치(2일차): `테슬라 사이버트럭 리스 계약 준비중...`(이향석, 11-03) + **신규 `[리스] 사이버트럭 법인 리스 서류 준비`(11-02)** — 동일 건을 서류/계약으로 나눈 것으로 보이나 **차량 용도·계정 귀속(브랜업/브랜업캠퍼스) 미기재**는 그대로.
- 미조치(5일차): `태국 화장품시설등록 관련 가이드 작성` 등록 즉시 경과 패턴 4회째 — 업무 등록 시 마감일 검증 규칙 필요.
- 미조치(4일차): 전경표 마케팅 라인(`광고소재 데이터 취합`·`퍼널구조 설계`) — `칸겐뷰티 SNS 운영` 담당자가 여전히 김봉재(퇴사)로 남아 **담당 재배정 결정** 필요.
- 미조치(6일차): 프로젝트 13개 중 **12개 보류·진행중 0개**(11일째) — 오늘 D-0인 KCL 사업계획서 업무가 살아 있는데도 KCL 프로젝트는 '보류'.
- 미조치(11일차): **아세안 5개국 규제자료 요청** — 태국만 대응 중이고 **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 미등록**, 회신 기한 없음(10일째).
- 미조치(8일차): **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- 미조치(46주차): 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- 미조치(40주차): `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (11-02 재확인 — 활성 15개 목록에 없음)
- 미조치(10주차): #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- 미조치(계속): `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **27일째**, 실질 업무 110건
- 미조치(계속): 담당자 공백 7건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'경과 22건 감소라는 착시'**다. 사흘간 완전히 멈춰 있던 대시보드가 **11-01(일) 17:14~20:25 약 3시간** 움직였고, 그 결과 활성 업무가 120 → 111건, 마감 경과가 76 → 54건으로 줄었다. 그러나 내역을 열어보면 **집행으로 끝난 것은 3건**이고, **7건은 완료 이력 없는 하드 삭제**, **12건은 마감 연기**(최대 +31일)다. 즉 **'일을 끝낸 것이 아니라 보드에서 치운 것'**이며, 삭제된 7건 중에는 **12월 미국 20,000세트 양산용 `15ml 세트박스(슬리브) 발주`**와 **아세안 첫 산출물 `태국 문안 정리`**가 포함돼 있어 단순 정리로 보기 어렵다. 완료 3건은 전부 **17:14~17:16 3분 내** 처리된 경과분으로, 10-30 17:37~17:39의 '3분 일괄 종결' 패턴과 같은 형태다. 이와 함께 위키의 **완료/삭제 판별 규칙이 갱신**됐다 — 완료 이력 385건의 `status`가 **전건 `완료`**이고 삭제 레코드는 **0건**이므로, **삭제는 감사 추적이 남지 않으며 전일 스냅샷 diff만이 유일한 판별 수단**이다(§7). 입력 쪽은 여전히 닫혀 있다 — Slack **10일 연속 0건**, TSonaX 커밋 **19일째 0건**. 오늘은 **D-0 10건**이 몰려 있고 그중 4건(쇼핑백 발주서·JNM 전성분/라벨·태국 시설등록 가이드·`[KCL]` 사업계획서)이 **11-01 연기분과 10-29 등록분**이라, 이번 주가 **'밀린 집행이 실제로 나오는지'를 가르는 구간**이 된다.
- 파일 변경: `concepts/tsonax.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/브랜업-업무-완료-판별.md`, `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`)

## [2026-11-03] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 110건 동기화 완료

## [2026-11-03] ingest | 일일 Slack + 대시보드 동기화 (48주차)
- 범위: 활성 Slack 15채널 전량 · Canvas/북마크 스캔 · 대시보드 API(활성 110건 / 완료 391건 / 프로젝트 13개) · 전일 diff · TSonaX 브랜치 git 실측
- **STEP 1 — 대시보드 동기화:** 프로젝트 13개 · 업무 **110건**(11-02 111건 대비 **-1** = 신규 **11** − 목록 제거 **12**, **레코드 변경 3**). **11-02(월)은 4일 정지 후 첫 '집행일'**이다 — **완료 6건이 전건 정시 또는 조기**였고 **하드 삭제 0건**. ① **완료 6건**: `[주간업무전략] 11월 1주`(**10:45:13**, 5인) · **`태국 화장품시설등록 관련 가이드 작성`**(**10:52:35**, 마감 11-02 → **정시**, 10-29 등록 후 4일 만) · `JNM코리아에게 전성분 및 라벨 전달`(**13:22:38**, 정시) · `FEDEX 물류비 관련 알아보기`(**13:22:41**, 정시) · **`[칸겐뷰트] 종이 쇼핑백 규제 리서치 1차 (미국/캐나다)`**(**14:40:48**, 마감 11-04 → **2일 조기**) · **`[칸겐뷰트] 샘플 봉합 실링 스티커 규제 리서치`**(**19:17:31**, 마감 11-04 → **2일 조기**). ② **목록 제거 12건 = 완료 6 + 반복업무 시리즈 교체 6**(`[주간업무전략]`·`[재무보고]` 11월 2~4주 구버전 → 신버전 재생성) — **하드 삭제 0건**. ③ **신규 11건 = 반복 자동생성 8건**(11-02 06:30·06:33 주간 배치) + **실등록 3건**(전건 강경철): `Market Expansion 국가 인증 기초 리서치`(13:22, 11-03) · **`태국 상자 인쇄 가능 여부 확인`(15:31, 마감 11-02 = 등록 즉시 경과, 5회째)** · `카톤 진행 상황 확인(지원)`(**18:51**, 11-03). ④ **레코드 변경 3건**: `[칸겐뷰티] 타 브랜드 / 트래픽 높은 광고소재 데이터 취합` 마감 **10-29 → 11-03**(+5일, 전경표) · **`[리스] 사이버트럭 법인 리스 서류 준비` summary에 `오리스 -> 신차` / `010-5304-4751 -> 중고 프리미엄라인` 추가**(11-02 10:22 — **리스 조달 경로 2갈래** 첫 기재) · `[재무보고] 11월 1주` summary 정리.
- **통계:** 마감 경과 **54 → 60건(+6)** — 11-02 D-0 10건 중 **4건 정시 완료**했으나 미완 6건이 경과 편입 + `태국 상자 인쇄` 즉시 경과 − `광고소재 데이터 취합` 11-03 연기 이탈. **60일 이상 38 → 40건(67%)** · **D-0 5건**(11-03) · **D-1 3건**(11-04) · **D-2 4건**(11-05) · D-3~7 9건 · `due_at` 미입력 **14건** · 담당자 공백 **6건** · `project_id` 미지정 **105/110**(95%) · 상태 진행중 109 · 지연 1. 담당자별 경과: **강경철 28**(+2) · 김봉재 9 · 전경표 7(−1) · 공백 4 · **이향석 4(신규 진입)** · 노수민 2 · 최유미 2 · 강경철·이상원 2 · 이상원 1 · 이상원·이향석 1. 완료 이력 **385 → 391건**(+6), 누적 지연완료 **203/391(52%)**. 프로젝트 **보류 12 · 완료 1 · 진행중 0**(12일째). 최근 사람 갱신 **11-02 18:51:24**(`카톤 진행 상황 확인(지원)`).
- **STEP 2 — Slack 채널 스캔 (활성 15개, 시간필터 없이 `limit:80` 후 스크립트 내 비교, `curl` subprocess)**
  - **업무 신규 메시지 0건 / 신규 파일 0건. 26시간 창 신규 0건 — 업무 대화 기준 11일 연속 0건.** 168시간 창 누적 **1건**은 `#wiki` 10-30 18:02 자체 발행 주간 린트 리포트(비업무)뿐이며, **업무 대화 기준 최신은 `#뷰티-프로젝트` 10-23 01:57**(줄리어스 대표 — 아세안 5개국 규제자료 요청)로 **11일째 변동 없음**.
  - 스레드 답글 0건 · errors 0(`제품-기획-제작` `not_in_channel` 스킵) · rename 0건 · 신규 채널 0건 · **ID 매핑 15/15 일치**. 채널 페이지 **신규 생성 0건**(`헤르메스`·`브랜업-조직구성`·`브랜업-휴가` 168시간 활동 0).
- **STEP 2b — 북마크 + Canvas 스캔:** Canvas 이벤트 **18건**(11-02 18 → **신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · 북마크 **0건** · errors 2(`제품-기획-제작` `not_in_channel` — bookmarks.list·conversations.history 각 1건).
- **STEP 2c — 프로젝트 페이지 활동:** `projects/kcl_sgs_안정성검사_사업_실행_12_31` — **11-03 항목 신설**: ① 🔴 `[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(긴급) **11-02 D-0를 넘겨 경과 1일** — 11-02 완료 6건 어디에도 포함되지 않았다 ② 더마프로 최종 리포트 PDF·판정 **미확보 6일째** ③ 프로젝트 상태 '보류' **12일째**, 오늘 D-0 5건에도 KCL 업무 없음. 나머지 12개 프로젝트는 **project_id 연결 업무 5건 전건 무변동**·Slack 대화 0으로 활동 귀속 근거 없음(프로젝트 12/13 '보류' 12일째).
- **STEP 3 — Wiki 페이지 갱신**
  - `concepts/tsonax` — 연혁 **11-03 항목 추가**(110건·경과 60건·D-0 5건·완료 391건·완료 6/하드삭제 0), 헤더 **기한 없는 진행중 13일째**·**커밋 20일째**(`git ls-remote origin` 11-03 실측 — tip `c6041cd` 10-14 12:47 · master `e42d7c9`), '리스크/미갱신' 경과 수치 **60건**으로 갱신, 소스 푸터 갱신.
  - `concepts/칸겐보떼-아세안-규제-신고-자료` — **11-03 현황 추가**: 태국 라인 미완 3건 **전부 완료**(시설등록 가이드 정시 / 포장재 규제 리서치 2건 2일 조기) + `태국 상자 인쇄 가능 여부 확인`(5단계: 포장 인쇄)·`Market Expansion 국가 인증 기초 리서치` 신규 + **산출물 문서 0건** 경고 + 홍콩 11일째 업무 0건.
  - `concepts/kangen-뷰티-문안-바코드-표준` — **§14 신설(11-03 후속)**: 규제 리서치 2건·JNM 라벨 전달 완료 표 / 🔴 **쇼핑백 발주서 4번째 마감(10-29→10-30→11-02) 넘겨 경과 1일, 발주서 원본 0건** / **완료된 리서치의 결과 문서가 없어 `씰링 스티커 다국어`·`밀봉방식` 판단 근거 공백 지속** / 삭제 2건 2일째 판별 불가.
  - `concepts/브랜업-업무-완료-판별` — **§8 신설(제거 항목 3분류)**: 완료 6 + **반복업무 시리즈 교체 6** + 하드 삭제 0. `series_id`/`series_seq`로 반복 업무 식별, 판별 절차 3단계, 반복 업무 13/110건(12%). "11-01 제거 10건(하드 삭제 7)과 11-02 제거 12건(하드 삭제 0)은 건수는 비슷하나 성격이 정반대" 명시.
  - **신규 페이지 1건: `concepts/브랜업-법인행정-재무-라인`** — 이상원·이향석 계정의 법인 행정·차량·보험·재무 업무 13건 정리. 11-03 D-0 2건·D-1 2건·D-2 3건, **이향석 경과 4건 신규 발생**, 리스 2건 중복·차량 귀속 법인 미기재·세무법인 견적 비교 미결 등 **판단 대기 4건** 명시.
  - 신규 raw 원본 **0건**(Slack 신규 파일 0건).
- **STEP 4 — 네비게이션:** `index.md`(헤더 11-03 · 총 **63페이지**(concepts 21→22) · TSonaX 요약 20일째·경과 60건·D-0 5건·110건 · 문안 §14 · 아세안 11-03 · 대시보드 현황 110건 · 완료판별 §8 · **신규 페이지 등재** · **11-03 크론 노트(48주차)**), `channels/index.md`(헤더 11-03 + **11-03 스캔 노트** — 11일 연속 0건), `README.md` 재생성(`wiki_readme_generator.py`).
- **미조치 (사용자 판단 필요)**
- **미조치(신규) 🔴 최우선**: **완료됐지만 산출물이 없는 3건** — `태국 화장품시설등록 관련 가이드 작성`(11-02 10:52)·`종이 쇼핑백 규제 리서치 1차`(14:40)·`샘플 봉합 실링 스티커 규제 리서치`(19:17). 전부 완료 처리됐으나 **문서·요약이 위키·Slack에 0건**이다. 특히 두 규제 리서치는 `씰링 스티커도 다국어야 하나`(11-05)·`본품 씰링 스티커 vs 수축필름`(11-15) 판단의 **근거로 쓰려고 만든 업무**라, 산출물 미확보 시 **11월 중순 판단이 또 미뤄진다**.
- **미조치(신규) 🔴**: **`쇼핑백(1만개) 발주서 전달`이 4번째 마감을 넘겼다** — 10-27 등록, 마감 10-29 → 10-30 → 11-02, 현재 **경과 1일**. 단가 4,082원·카톤 수지판비 조건만 확정이고 **발주서·견적 원본 0건**. 12월 미국 20,000세트 양산 리드타임 역산 시 이미 지연 구간이며, 11-01 **하드 삭제된 `15ml 세트박스(슬리브) 발주`와 합산됐는지 여전히 미확인**(2일째).
- **미조치(신규) ⚠️**: **이향석 라인 경과 4건 신규 발생** — `[폴스타] 보험갱신`·`[리스] 사이버트럭 서류`·`장재욱 건강보험`·`[KCL] 수정사업계획서`(긴급). 4건 모두 **10-28~11-01 등록분**이고 **마감이 이미 '오늘/내일'**이었다. → **업무 등록 시 착수 여유(최소 D+2) 강제 규칙** 필요. 상세는 신규 [[concepts/브랜업-법인행정-재무-라인]].
- **미조치(2일차)**: **사이버트럭 리스 2건 중복** — `테슬라 사이버트럭 리스 계약 준비중...`(11-03 D-0, 15개 서류 체크리스트)과 `[리스] 사이버트럭 법인 리스 서류 준비`(11-02 경과)의 **관계·우선순위 미표기**. 11-02 summary에 추가된 **`오리스 -> 신차` / `010-5304-4751 -> 중고 프리미엄라인`**의 의미(조달 경로 변경인지, 서로 다른 2건인지) 확인 필요. 차량 **용도·계정 귀속(브랜업/브랜업캠퍼스) 미기재**는 그대로.
- **미조치(1일차) 🔴**: **`[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(긴급) 11-02 D-0 미완 → 경과 1일** — summary의 `Cornerstone Asset service 계약서` 외에 변경 사유·새 수행사명·계약 체결 여부는 여전히 문서 없음.
- **미조치(3일차)**: **"본계약 기준 문안" 확정본 부재** — 업무는 11-01 17:16 완료됐고 11-02 `JNM 전성분·라벨 전달`까지 완료됐지만 **확정 문안 파일·버전은 여전히 위키에 없다**. 전달의 기준 문서가 확인되지 않은 상태로 종결됐다.
- **미조치(7일차)**: **`더마프로 민감 피부자극테스트` 최종 리포트 원문·판정 결과 미확보** — KCL 사업 산출물로 등재 불가.
- **미조치(5일차)**: **`업무대시보드 정리회의`(10-30 17:37 완료) 회의록·결정 산출물 없음** — 11-01 대정리(완료3·삭제7·연기12)의 근거 문서도 함께 부재.
- **미조치(4일차)**: **`[대시보드] 업무 상태변경 시 텔레그램/카카오톡 알림`(이향석, 11-06 D-3)** — 이번 회차의 **'시리즈 교체 vs 삭제 오독'·'산출물 공백'** 문제와 직접 연결되므로 우선순위 상향 검토.
- **미조치(4일차)**: `브랜업캠퍼스 신규 법인설립`(11-04 D-1, 높음) — 5인 이사 중 3인 브랜업 지정·최유미 교수 지분참여 논의 중이나 **지분율·투자금액·정관 반영 여부 문서 없음**. D-1인데 산출물 0건.
- **미조치(3일차)**: `[컨설팅] 11/04~11/06 재무/회계 정부지원(80%)` **D-1** — 요구 4항(사업부별 재무제표·투자유치용 재무보고서·대표이사 차입금 관리·연구소 설립) 중 **사전 준비물 확보 여부 미확인**.
- **미조치(2일차)**: `[세무] 세무법인 결정`(11-05 D-2, 긴급) — 견적 비교만 있고 **선정 기준(기장 범위·세무조정·연구소 자문) 없음**. 08-23 등록 후 3주째 미결.
- **미조치(5일차)**: `태국 화장품시설등록 관련 가이드` 등록 즉시 경과 패턴 **5회째**(`태국 상자 인쇄 가능 여부 확인` 11-02 15:31 등록·마감 11-02) — 업무 등록 시 마감일 검증 규칙 필요.
- **미조치(5일차)**: 전경표 마케팅 라인(`광고소재 데이터 취합` 11-03 D-0 · `퍼널구조 설계` 11-07) — `칸겐뷰티 SNS 운영` 담당자가 여전히 김봉재(퇴사)로 남아 **담당 재배정 결정** 필요.
- **미조치(7일차)**: 프로젝트 13개 중 **12개 보류·진행중 0개**(12일째) — 오늘 D-0 5건이 모두 살아 있는데도 진행중 프로젝트가 없다.
- **미조치(12일차)**: **아세안 5개국 규제자료 요청** — 태국은 5단계(포장 인쇄)까지 진행됐으나 **홍콩(1순위)·말레이시아·싱가포르·필리핀 4개국 대응 업무 0건**, 회신 기한 부재 11일째.
- **미조치(9일차)**: **수량 불일치 `1,573` vs `1,583` 세트** — 표기 불일치 미해소.
- **미조치(47주차)**: 린트 권장 고아·미등재 페이지 7건 `_archive/` 이동 승인 대기
- **미조치(41주차)**: `channels/브랜업-공지사항.md` Slack 채널 실체 미확인 (11-03 재확인 — 활성 15개 목록에 없음)
- **미조치(11주차)**: #제품-기획-제작(C0BL3S0BHV3) 봇 미참여 — 채널 초대 필요
- **미조치(계속)**: `test_escalate_probe_20261006`(#a8f06ae2) 잔존 → **28일째**, 실질 업무 109건
- **미조치(계속)**: 담당자 공백 6건 · IR 덱 편집 오류 2건 · `00.261016용기 후면 최신 (3).indd` INDD 판독 불가 · `0720-2.jpg` 대상 프로젝트 미확인
- 비고: 오늘의 성격은 **'집행 재개, 그러나 속도가 마감 도래를 못 따라간 하루'**다. 10-30 이후 나흘간 신규·완료·재조정이 모두 0이던 대시보드가 11-02(월) 움직였고, 내용도 **완료 6건 전건이 정시 또는 조기**라는 점에서 질적으로 좋아졌다(11-01은 완료 3건이 전부 경과분의 3분 일괄 종결이었다). 특히 **태국 라인이 추적 3건을 모두 종결**하며 '대응 체계 구축' 단계를 통과했고, **하드 삭제는 0건**(전일 7건)이었다. 그럼에도 마감 경과는 **54 → 60건으로 오히려 늘었다** — 11-02 D-0 10건 중 처리된 것은 4건뿐이었고, 새로 등록된 3건 중 1건이 **등록 즉시 경과**로 출발했기 때문이다. 즉 **문제는 '일이 안 나오는 것'이 아니라 '마감이 착수 여력을 앞지르는 것'**이며, 이향석 라인 4건이 그 전형이다(10-28~11-01 등록, 마감 11-02~11-03). 두 번째 구조적 발견은 **'완료 = 산출물'이 아니라는 점**이다 — 이번에 완료된 6건 중 3건(태국 시설등록 가이드·규제 리서치 2건)은 **결과 문서가 위키에 없어** 후속 판단(씰링 스티커 다국어·밀봉 방식)의 근거로 쓸 수 없다. 세 번째는 **측정 규칙의 교정**이다 — 제거 12건 중 6건이 반복업무 시리즈 교체였고, 이를 삭제로 집계하면 "하루에 6건 삭제"라는 완전한 오보가 된다(§8 신설). 입력 쪽은 여전히 닫혀 있다 — **Slack 11일 연속 0건 · TSonaX 커밋 20일째 0건**. 요약하면 **'보드가 다시 움직였고 방향도 맞다. 다만 산출물을 남기지 않고, 마감을 벌리지 않는 한 경과는 계속 늘어난다'**.
- 파일 변경: `concepts/tsonax.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-법인행정-재무-라인.md`(**신규**), `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261103.json`

## [2026-11-04] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 107건 동기화 완료


## [2026-11-04] update | 일일 Slack + Dashboard Wiki 요약 (49주차)
- **Slack**: 활성 15개 채널 스캔 — 신규 메시지 **0건** · 신규 파일 **0건** (28시간 창 **12일 연속 0건**). 업무 대화 최신은 `#뷰티-프로젝트` 10-23 01:57(아세안 규제자료 요청)로 **12일째 변동 없음**. Canvas 18건(신규 0) · 북마크 0건 · errors 2(`제품-기획-제작` `not_in_channel`). 채널 rename 0 · 신규 채널 0 · 채널 페이지 신규 생성 0 → **채널 페이지 본문 갱신 없음**
- **DB 동기화**: `branup_db_wiki_sync.py` — 프로젝트 13개 · 업무 **107건** (17개 파일: `projects/` 13건 · `projects/index.md` · `concepts/브랜업-대시보드-현황.md` · `index.md`)
- **DB diff (11-03 → 11-04)**: 110 → **107건** = 신규 **4** − 제거 **7** · 레코드 변경 **2**
  - 신규 4 (전건 강경철·11-03 생성): `캐나다 3ea*50mL 1.69 fl. oz. 써도 되는지 확인`(#589, 마감 11-03 = 등록 즉시 경과) · `50ml 미국 캐나다 문안 규정 (전면만)`(#590, 11-03 = 등록 즉시 경과) · `JNJ 50% 결제`(#585, **11-04 D-0**) · `태국 스티커 최적화(부착 위치, 세트박스+용기 등) 리서치`(#586, **12-03**)
  - 제거 7 = **완료 6** + **하드 삭제 1**: 완료 `[재무보고] 11월 1주`(17:46:20) · `[KCL] 수정사업계획서 제출 - 서베이 회사 변경`(17:46:32) · `장재욱 건강보험 가족 피부양자 추가`(17:46:38) · `[리스] 사이버트럭 법인 리스 서류 준비`(17:48:28) · `[폴스타] 보험갱신 …갱신 신청하기`(18:03:49) · `테슬라 사이버트럭 리스 계약 → 승인거절, 차량소진`(18:04:16) / 삭제 `태국 상자 인쇄 가능 여부 확인`(완료 이력 0건)
  - 레코드 변경 2: `Market Expansion 국가 인증 기초 리서치` 마감 **11-03 → 12-03**(+30일) · `[SVC] 엡버서더 미팅` 제목에 `-> 11/6 10시 1층 5번` 추가
- **11-03 완료 총 9건**(완료 이력 391 → **400건**) — 정시·조기 5 · 1일 지연 4. 이향석 라인 6건이 **17:46~18:04 18분 내 일괄 종결**
- **통계(as-of 11-04 05:00 KST)**: 마감 경과 **60 → 59건**(재평가 브리지 65 → 59 = −7 완료·삭제 −1 연기 +2 신규 유입) · 60일 이상 **40건(68%)** · D-0 4건 · D-1 4건 · D-2 5건 · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 102/107(95%) · 진행중 106 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(13일째) · 누적 지연완료 207/400(51.7%)
- **한국어 위키 갱신 6건**: `concepts/tsonax.md`(연혁 11-04 · 21일째 정지 · 기한 없는 진행중 14일째 · 경과 리스크 절 갱신), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§15 신설**), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-04 현황), `concepts/브랜업-업무-완료-판별.md`(**§9 신설**), `concepts/브랜업-법인행정-재무-라인.md`(**§4 신설** + 표 상태 갱신), `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`(11-04 항목) + `channels/index.md` · `index.md` · `README.md`(재생성)
- **미조치(신규)**: ① `[KCL] 수정사업계획서` 완료됐으나 **변경 사유·새 수행사·`Cornerstone Asset service` 계약서 문서 0건** ② **사이버트럭 리스 승인거절·차량소진 종결 → 대체 차량 조달 업무 미등록** ③ `태국 상자 인쇄 가능 여부 확인` **하드 삭제**(11-01 7건 이후 2일 만의 재발) ④ 신규 4건 중 **2건이 등록 즉시 경과**(11-02 태국 상자 인쇄와 동일 패턴)
- **미조치(지속)**: 쇼핑백 1만개 발주서 **9일째 원본 0건** · 규제 리서치 2건(11-02 완료) **결과 문서 3일째 부재** → `씰링 스티커도 다국어야 하나`(11-05 D-1) 판단 근거 공백 · 더마프로 리포트 원문 7일째 · 홍콩(아세안 1순위) 12일째 업무 0건 · 세무법인 결정 74일째 미결(11-05 D-1·긴급) · `test_escalate_probe_20261006` 28일째 잔존 · 프로젝트 12/13 보류(진행중 0)
- **TSonaX**: 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 14일째**(`updated_at` 10-21 그대로) · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(21일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-04 실측)
- 파일 변경: `concepts/tsonax.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-법인행정-재무-라인.md`, `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261104.json` · `branup_completed_20261104.json`

## [2026-11-04] lint | 일일 점검 (경량)
- Slack 스캔 2회 실행 동일 결과(0/0) — 파이프라인 정상 · `conversations.list` 15개 · ID 매핑 15/15 일치 · 신규 채널·rename 0
- raw/ 신규 원본 0건 → sha256 재계산 대상 없음 · 미등재(아카이브 대기) 7건 변동 없음 · 콘텐츠 페이지 63 유지(신규 0)

## [2026-11-05] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 116건 동기화 완료


## [2026-11-05] update | 일일 Slack + Dashboard Wiki 요약 (50주차)
- **Slack**: `conversations.list` **16개**(전일 15 → **+1**) · 비아카이브 전량 `conversations.history` 스캔 — 신규 메시지 **0건** · 신규 파일 **0건** (28시간 창 **13일 연속 0건**). 업무 대화 최신은 `#뷰티-프로젝트` 10-23 01:57(아세안 규제자료 요청)로 **13일째 변동 없음**. Canvas 18건(신규 0) · 북마크 0건 · errors 2(`제품-기획-제작` + **신규 `브랜업-멤버십-슬랙-소통-채널`(C0CDVR5CHT7)**, 둘 다 `not_in_channel`). rename 0 · **신규 채널 1** · 채널 페이지 신규 생성 0 → **채널 페이지 본문 갱신 없음**
- **DB 동기화**: `branup_db_wiki_sync.py` — 프로젝트 13개 · 업무 **116건** (17개 파일)
- **DB diff (11-04 → 11-05)**: 107 → **116건** = 신규 **20** − 제거 **11** · 레코드 변경 **6**
  - 🔴 **신규 20건 중 12건이 동일 업무 중복 등록** — `[칸겐뷰트] 종이 쇼핑백 규제 리서치 2차 (미국/캐나다)`(전경표, #595~#606, 11:59:46~12:07:34, 전건 마감 11-04). summary 9건이 `ㅇㅇ`. **실등록은 8건**
  - 실등록 8 = `change your water… 불어 번역 여부`(강경철, 11-04) · `세무사 솔루션 분석`(이향석, 11-05·긴급) · `이카운트 생산/구매/재고 관리 시스템 구축`(강경철, 11-06) · **시리즈 5**(`[주간업무회의]` 11월 1~4주 #609~#612 + `정부지원사업 매주 확인` #608)
  - 제거 11 = **완료 3 + 시리즈 교체 8 + 하드 삭제 0** — 완료 `50ml 미국 캐나다 문안 규정 (전면만)`(09:36:18, 1일 지연)·`정부지원사업 매주 확인`(10:03:57 정시)·`JNJ 50% 결제`(19:30:04 정시) / 시리즈 교체 `[재무보고]` 2~5주·`[주간업무전략]` 2~5주 → **`[주간업무회의]`로 개명**. **제목 매칭만으로는 8건이 '삭제'로 오판되는 신규 실패 유형**
  - 변경 6: 쇼핑백 발주서 **11-02 → 11-05(5번째 마감)** · 카톤 진행 상황 확인 11-03 → 11-05 · 인쇄물 관리 기준마련 11-02 → 11-04(담당 이향석 → 이향석·전경표) · `[컨설팅]` 11-04 → 11-06 · 브랜업캠퍼스 제목 `사업자등록신청 완료` → `사업자등록 완료` · `[SVC] 엡버서더 미팅` 10시 → 9:30
- **11-04 완료 4건**(정시 3 · 1일 지연 1) → 완료 이력 400 → **404건**(누적 지연완료 208/404 = 52.5%)
- **통계(as-of 11-05 05:00 KST)**: 마감 경과 **59 → 70건(+11)** — 브리지 `유입 14 − 해소 3`. **유입 14 중 13건이 11-04 등록·마감 11-04(전건 등록 당일 마감)** → **중복 12건을 제외하면 실질 −1**. · 60일 이상 **40건(57%)** · **D-0 7건** · **D-1 8건** · D-2 1건 · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 111/116(96%) · 진행중 115 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(14일째) · 담당자별 경과 강경철 28 · **전경표 20(중복 12 영향)** · 김봉재 9 · 공백 4
- **한국어 위키 갱신 6건**: `concepts/브랜업-대시보드-입력-품질.md`(**신규** — 중복 등록·등록 당일 마감·summary 공백·롤링 구분), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§16 신설**), `concepts/브랜업-업무-완료-판별.md`(**§10 신설** — 시리즈 개명 오판 방지), `concepts/브랜업-법인행정-재무-라인.md`(**§5 신설** — 세무법인 후보 2곳 탈락), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-05 현황), `concepts/tsonax.md`(연혁 11-05·22일째 정지·15일째 기한 없는 진행중) + `channels/index.md`(신규 채널 ID 등재·11-05 스캔 노트) · `index.md`(총 64p·concepts 23) · `README.md`(재생성)
- **프로젝트 페이지 활동 추가 없음** — 금일 이벤트가 전부 `project_id` 미지정 업무(중복·문안·세무·ERP)라 특정 프로젝트에 귀속 불가
- **미조치(신규)**: ① **중복 12건 정리 필요**(#598~#606 등 11건 삭제, #595 유지) — 삭제 시 경과 −11은 '개선'이 아니라 **착시 정정** ② **신규 채널 `브랜업-멤버십-슬랙-소통-채널` 봇 초대 필요**(현재 `not_in_channel`) ③ **`[주간업무전략]` → `[주간업무회의]` 개명이 회의 체계 변경인지 확인**(담당 5인 → 1인 축소) ④ **`세무사 솔루션 분석` 탈락 사유(솔로몬·삼덕회계) 1줄 기록** — 잔여 후보 1곳뿐 ⑤ **`이카운트` ERP 도입은 신규 라인** — 소유자·범위·일정 미기재
- **미조치(지속)**: 쇼핑백 1만개 발주서 **10일째 원본 0건**(5번째 마감) · 규제 리서치 2건(11-02 완료) **결과 문서 5일째 부재** → `씰링 스티커도 다국어야 하나` **11-05 D-0인데 판단 근거 공백** · `50ml 전면 문안` 완료됐으나 **기준 문서 0건** · 더마프로 리포트 원문 8일째 · 홍콩 등 아세안 4개국 **13일째 업무 0건** · `[세무] 세무법인 결정` **74일째 미결** · 11-06 이향석 라인 7건 동시 도래 · `test_escalate_probe_20261006` 29일째 잔존 · 프로젝트 12/13 보류
- **TSonaX**: 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 15일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(22일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-05 실측)
- 파일 변경: `concepts/브랜업-대시보드-입력-품질.md`(**신규**), `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/tsonax.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261105.json` · `branup_completed_20261105.json`

## [2026-11-06] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 127건 동기화 완료

## [2026-11-06] update | 일일 Slack + Dashboard Wiki 요약 (50주차)

- **Slack**: `conversations.list` **16개**(전일과 동일) · 비아카이브 전량 `conversations.history` 스캔(시간필터 없이 limit 80 후 스크립트 비교) — 신규 메시지 **0건** · 신규 파일 **0건** (**26시간 창 0건 = 14일 연속**). 업무 대화 최신은 `#뷰티-프로젝트` 10-23 01:57(아세안 규제자료 요청)로 **14일째 변동 없음**. 168시간 누적 메시지 **1건**(`#wiki` 10-30 18:02 자체 린트 리포트 = 비업무) · 파일 0 · 스레드 답글 0. errors 2(`제품-기획-제작` + `브랜업-멤버십-슬랙-소통-채널`, 둘 다 `not_in_channel` — 이틀째 동일). **Canvas 18건(신규 0, 최신 10-21 17:54) · 북마크 0건**. rename 0 · 신규 채널 0 → **채널 페이지 본문 갱신 없음**
- **DB 동기화**: `branup_db_wiki_sync.py` — 프로젝트 13개 · 업무 **127건**(17개 파일)
- **DB diff (11-05 → 11-06)**: 116 → **127건** = 신규 **11** − 제거 **0** · 레코드 변경 **0**
  - 🔴 **신규 11건 중 8건이 동일 업무 중복 등록** — `저알레르기 주장 문구 관련 검토 요청`(강경철, #613~#620, 14:34:36~14:39:40 **5분 4초**, 전건 마감 11-05, summary 8건 전건 제목과 동일). **11-04 12건 중복의 익일 재발 = 이틀 연속 입력 사고**
  - 실등록 **4건**: ① 저알레르기(원본 1) ② `칸겐뷰티 타임리스 레디언스 컬렉션 출원 권고`(#621, 17:10, 마감 11-05) ③ `써티코스 회원가입 및 가이드 확인 후 노티(주간메일 수신자 정보 포함)`(#622, 18:56, **11-06 D-0**) ④ `사내근로복지기금 직원보너스 조사`(이향석, 21:24, 11-07)
  - 제거 **0건 · 완료 이력 404건 그대로 = 11-05 완료 0건**(첫 '무집행일')
- **브리지 검산**: 11-05 경과 70 + D-0 도래 7 + 신규 즉시 경과 9 = **86건** (실측 86과 정확히 일치). 중복 8건 제외 시 실질 **+8**
- **통계(as-of 11-06 05:00 KST)**: 마감 경과 **70 → 86건(+16)** · **60일 이상 40건(47%)** · **D-0 9건**(11-06) · D-1 2건(11-07) · D-2 **0건** · D-3 1건(11-09) · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 **122/127(96%)** · 진행중 126 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(14일째) · 담당자별 경과 **강경철 41 · 전경표 20 · 김봉재 9 · 공백 4 · 노수민 2 · 최유미 2 · 이향석 계열 5** · 최장 경과 `[에나지크] 캐나다 라벨 리뷰 방안` **147일**
- **11-06 D-0 9건**: 카니발 법인승계 스왑처리(116일째) · `[컨설팅] 11/04~11/06 재무/회계 정부지원(80%)` · 제품명 바꿔서 재등록 · `[SVC] 입주기업 신규 가능성`(높음) · `[SVC] 엡버서더 미팅(9:30)` · `[대시보드] 업무 상태변경 알림` · `[주간업무회의] 11월 1주` · 이카운트 생산/구매/재고 구축 · 써티코스 회원가입
- **한국어 위키 갱신 6건**: `concepts/브랜업-대시보드-입력-품질.md`(**§6 신설** — 두 번째 중복 사고 8건·누적 20건·자동 판정 규칙·`#572`에 중복 차단 포함 요구), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§17 신설** — 효능 주장(저알레르기) 축 최초 등장·컬렉션 출원 권고·써티코스), `concepts/브랜업-업무-완료-판별.md`(**§11 신설** — 11-05 완료 0·제거 0, 3단 브리지 검산), `concepts/브랜업-법인행정-재무-라인.md`(**§6 신설** — 11-06 이향석 6건 동시 도래·복지기금 신규 축·세무법인 75일째), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-06 현황·4개국 14일째 0건), `concepts/tsonax.md`(연혁 11-06·23일째 정지·기한 없는 진행중 16일째) + `channels/index.md`(11-06 스캔 노트) · `index.md`(6개 요약 라인 갱신, 총 64p) · `README.md`(재생성)
- **프로젝트 페이지 활동 추가 없음** — 금일 신규·변경 업무가 전부 `project_id` 미지정이고 Slack 신규 메시지도 0건이라 특정 프로젝트에 귀속 불가
- **미조치(신규)**: ① **중복 8건 정리 필요**(#614~#620 삭제, #613 유지) — 삭제 시 경과 −8은 '개선'이 아니라 **착시 정정** ② **`저알레르기` claim 문구의 입증·표시 기준 문서 0건** — 미국·캐나다 수출 전 확인 필요 ③ **`컬렉션 출원 권고`의 대상(상표/디자인)·주체·기한 미기재** — summary 1줄 확보 ④ **`써티코스`는 위키에 정의 없는 신규 외부 서비스** — 용도·계약 관계 확인 ⑤ **`사내근로복지기금`은 신규 제도 축** — 도입 여부·재원 구조 미확인
- **미조치(지속)**: 쇼핑백 1만개 발주서 **11일째 원본 0건**(**6번째 마감 경과**) · 규제 리서치 2건(11-02 완료) **결과 문서 5일째 부재** → `씰링 스티커 다국어` 판단 근거 없이 경과 · `50ml 전면 문안` 기준 문서 0건 · 더마프로 리포트 원문 9일째 · 아세안 4개국 **14일째 업무 0건** · `[세무] 세무법인 결정` **75일째 미결** · `test_escalate_probe_20261006` 30일째 잔존 · 프로젝트 12/13 보류
- **TSonaX**: 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 16일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(23일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-06 실측)
- 파일 변경: `concepts/브랜업-대시보드-입력-품질.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/tsonax.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261106.json` · `branup_snapshot_20261106_projects.json`

## [2026-11-06] lint | 위키 린트 (50주차, #wiki 게시) — 치명 0 · 경고 6 · 주의 1 · 정보 33
- 점검 범위: 콘텐츠 **64페이지**(channels 11 · entities 17 · concepts 23 · projects 13) + raw md 56 · log **196엔트리** (10-30 대비 +2페이지: `concepts/브랜업-업무-완료-판별`·`concepts/브랜업-대시보드-입력-품질`)
- **깨진 위키링크 0건**(콘텐츠 페이지) · ghost index link 0건 · 파이프 앞 백슬래시 2개+ 누적 0건(10-30 교정 유지) · index 선언 64 = 실측 64 · frontmatter 결손 0 · `contested: true` 0
- log.md 내 5건은 **과거 이슈를 서술한 이력 문장**(`branup-work-dashboard` ×2, `channels/브랜업-전체` ×2, `통합주간전략 자동화`) — append-only 이력 특성상 조치 대상 아님(콘텐츠 결함 아님)
- 고아 **6** / index 미등재 **7** — 10-02 이후 **변동 없음**: `entities/project-*` 5건(`projects/` 동명 페이지의 09-25 스냅샷 중복, `_archive/` 이동 5주째 승인 대기) · `concepts/task-status`(아카이브 대기) · `concepts/project-status`(미등재이나 README+미러 5건에서 inbound → 고아 아님)
- 태그 감사: taxonomy **75종**, 미등재 1종 `task`(`concepts/task-status` 전용, 2026-10-02 린트에서 등재 보류 명시한 예외)
- stale(90일+) **14건** — 최장 `concepts/slack-adoption` 115일 · aizel 계열 5건 110~114일 · `channels/브랜업-온보딩` 99일 · `channels/브랜업-에듀` 106일
- 200줄 초과 **6건** — `entities/브랜업-신입직원-온보딩-매뉴얼` 801 · **`concepts/kangen-뷰티-문안-바코드-표준` 324(10-30 302줄 → 증가, 분할 임계)** · `channels/코스메틱-본부` 287 · `entities/enagic-usa` 255 · `channels/branup-design-backup` 218 · `concepts/에나지크-글로벌-물류-패키징-전략` 204
- raw sha256: 불일치 **15**(전건 단일 ingest 커밋 → **해시 산출 규칙 불일치, 소스 drift 아님**) · source_file 바이너리 4(정상 규약) · placeholder 18(drift 판정 불가) · 필드 없음 6 · 정상 13
- 채널 `slack_channel_id` 미확정 1건(`channels/브랜업-공지사항` = unknown, Slack 실체 미확인 10-23부터) · outbound 2개 미만 12건(자동생성 프로젝트 페이지 8 + 미러/온보딩 4) · log 196엔트리(로테이션 기준 500 미만)
- 게시: `#wiki`(C0BGCQS22BF) ts `1793955802.665259` — readback으로 본문 1,991자 확인
- 파일 변경: `log.md`(본 엔트리)

## [2026-11-07] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-11-07] update | 일일 Slack + Dashboard Wiki 요약 (51주차)

- **Slack**: `conversations.list` **18개**(16 → **+2**) · 비아카이브 전량 `conversations.history` 스캔(시간필터 없이 limit 80 후 스크립트 비교) — 신규 메시지 **0건** · 신규 파일 **0건** (**26시간 창 0건 = 15일 연속**). 업무 대화 최신은 `#뷰티-프로젝트` 10-23 01:57(아세안 규제자료 요청)로 **15일째 변동 없음**. 168시간 누적 **1건**(`#wiki` 11-06 18:03 자체 린트 리포트 = 비업무) · 파일 0 · 스레드 답글 0. errors **4**(`제품-기획-제작` · `브랜업-멤버십-슬랙-소통-채널` · **`코스매틱-진행`(C0CG9DAJS9E)** · **`00코스매틱-진행`(C0CF9P6FUTX)** — 전부 `not_in_channel`). **Canvas 18건(신규 0, 최신 10-21 17:54) · 북마크 0건**(스캐너 15개 채널 기준, errors 2). rename 0 · **신규 채널 2건**: `코스매틱-진행`(11-06 **15:05** 생성) · `00코스매틱-진행`(11-06 **15:06** 생성) — **1분 간격·유사 명칭 = 사실상 중복 생성** → **어느 쪽이 정본인지 사용자 확인 필요**. 채널 페이지 신규 생성 0(봇 미참여로 내용 확인 불가) → **채널 페이지 본문 갱신 없음**
- **DB 동기화**: `branup_db_wiki_sync.py` — 프로젝트 13개 · 업무 **102건**(17개 파일)
- **DB diff (11-06 → 11-07)**: 127 → **102건** = 신규 **3** − 제거 **28** · 레코드 변경 **16**
  - **신규 3건**: `바뀐 원료 목록 공유 드리기 (줄리어스 대표님)`(강경철, due 11-06 → **즉시 경과**) · `오전에 카톤 관련 자료 받기`(강경철, 11-09) · `임차보증금 대출 방법 조사`(이향석·전경표, 11-10 · **KB은행·서울신용보증재단 = 금융 조달 신규 축**). **중복 0건**(2일 연속 사고 후 첫 정상 등록)
  - 🔴 **제거 28건 = 완료 6 + 하드 삭제 22** — 완료는 `/api/tasks/completed` **id 직접 매칭**만 인정. **제목 매칭으로는 24건이 '완료'로 4배 부풀려진다**(중복 배치 위장). 삭제 22 = **중복 배치 18**(`종이 쇼핑백 2차` 12건 → 완료 1(#597)·삭제 11 / `저알레르기` 8건 → 완료 1(#613)·삭제 7) + **단건 4**(`change your water 불어 번역` #593 · `책임판매업자 등록 요건` #478 · `씰링 스티커도 다국어야 하나` #545 · `카톤 진행 상황 확인` #584) → **단건 4건은 '판단 없는 종결'**(위키가 5회 이상 '결과 문서 0건' 지적하던 항목)
  - **11-06 완료 8건**(404 → **412**): 저알레르기(11:18:39·1일 지연) · 캐나다 3ea(11:19:29·3일) · 써티코스(14:58:28·정시) · 쇼핑백 2차(17:37:10·2일) · 광고소재 취합(17:55:24·3일) · 브랜업캠퍼스 사업자등록(18:31:55·2일) + 당일 등록·완료 2건(`샘플 인보이스 검토` 14:57:40 · `세트박스 문안 검토 요청` 17:54:30·정시)
- 🔑 **4항 브리지 검산(신규)**: 어제 스냅샷 as-of 오늘 **97** − 해소 **28** − **마감 연장 12** + 신규 즉시 경과 **1** = **58**(오차 0). 3항으로는 12건이 설명되지 않는다 → 판별 규칙에 **'마감 연장 항'** 추가. **11-06 D-0 9건 중 7건이 연장**, 1건 완료(써티코스), 1건만 그대로 경과(`[대시보드] 업무 상태변경 알림`)
- **통계(as-of 11-07 05:00 KST)**: 마감 경과 **86 → 58건(−28 — 실집행 6 · 삭제 22 · 연장 12)** · **60일 이상 40건(69%)** · **D-0 2건**(11-07: `더마브랜드 퍼널구조 설계`·`사내근로복지기금 직원보너스 조사`) · D-1 1건(11-08) · **D-2 7건**(11-09) · D-3 1건(11-10) · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 **97/102(95%)** · 진행중 101 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(15일째) · 담당자별 경과 **강경철 28 · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 최유미 2 · 강경철·이상원 2 · 이향석 2 · 이상원 1** · 최장 `[에나지크] 캐나다 라벨 리뷰 방안` **148일** · 누적 지연완료 **213/412(52%)**
- **한국어 위키 갱신 6건**: `concepts/브랜업-업무-완료-판별.md`(**§12 신설** — 완료 6 + 삭제 22 · 제목 매칭 4배 부풀림 규칙 · 단건 4건 '판단 없는 종결' · 4항 검산), `concepts/브랜업-대시보드-입력-품질.md`(**§7 신설** — 두 중복 배치 종결 20건 → 완료 2 + 삭제 18 · 정보 손실 없음 · 중복 차단 기능 여전히 미구현), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§18 신설** — 포장·문안 8건 정리 = 완료 4 + 삭제 4 · 쇼핑백 발주서 7번째 마감), `concepts/브랜업-법인행정-재무-라인.md`(**§7 신설** — 11-06 D-0 전량 연기 · 브랜업캠퍼스 완료 · 임차보증금 대출 신규 축), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-07 현황 · 4개국 15일째 0건), `concepts/tsonax.md`(연혁 11-07·11-06 보강 + 리스크/미갱신 최상단 교체) + `channels/index.md`(ID 표에 신규 채널 2건 등재 · 11-07 스캔 노트) · `index.md`(6개 요약 라인 갱신, 총 64p) · `README.md`(재생성)
- **프로젝트 페이지 활동 추가 없음** — Slack 신규 메시지 0건이고, 금일 신규·변경 업무 3건 전부 `project_id` 미지정 → 특정 프로젝트에 귀속 불가(project_id 지정 업무는 5건 그대로, 전건 장기 경과)
- **미조치(신규)**: ① **`코스매틱-진행` vs `00코스매틱-진행` 중복 생성 정리** — 11-06 15:05/15:06 1분 간격, 어느 쪽이 정본인지 확인 필요 ② **봇 초대 4개 채널**(`제품-기획-제작`·`브랜업-멤버십-슬랙-소통-채널`·`코스매틱-진행`·`00코스매틱-진행`) ③ **`[대시보드] 업무 상태변경 알림`(#572)이 11-06 D-0 미처리** — 중복 차단 기능과 같은 배포로 묶어야 재발 감지 가능 ④ **단건 삭제 4건의 판단 근거 기록**(특히 `씰링 스티커 다국어`·`책임판매업자 등록 요건`) — 삭제로만 종결되면 아세안/미국 등록 단계에서 재발 ⑤ **`임차보증금 대출 방법 조사`의 대상 물건·금액·기한 미기재** ⑥ **`바뀐 원료 목록 공유`가 즉시 경과** — 전성분·문안 표기와 연결 문서 필요
- **미조치(지속)**: 쇼핑백 1만개 발주서 **12일째 원본 0건**(**7번째 마감 11-09**) · 완료 4건(쇼핑백 2차·세트박스 문안·저알레르기·3ea) 전부 **산출물 문서 0건** · `50ml 전면 문안` 기준 문서 0건 · 더마프로 리포트 원문 10일째 · 아세안 4개국 **15일째 업무 0건** · `[세무] 세무법인 결정` **76일째 미결**(후보 사실상 1곳) · `test_escalate_probe_20261006` 31일째 잔존 · 프로젝트 12/13 보류(진행중 0)
- **TSonaX**: 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 17일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(24일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-07 실측)
- 파일 변경: `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/tsonax.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261107.json` · `branup_completed_20261107.json` · `branup_snapshot_20261107_projects.json`

## [2026-11-08] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 102건 동기화 완료

## [2026-11-08] daily | 11-07 완전 무변동일 — 신규·완료·제거·필드변경 전건 0, 경과 58건은 '이동'만 / Slack 16일 연속 0건

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **102건** · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교) → **업무 신규 메시지 0건 / 신규 파일 0건**. **26시간 창 0건 = 16일 연속**. 업무 대화 최신 `#뷰티-프로젝트` **10-23 01:57** → **16일째 무변동**. 168h 누적 **1건**(`wiki` 11-06 18:03 자체 린트 — 비업무) · 스레드 답글 0 · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, 3일째 동일)
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 스캔 · 북마크 **0건** · **Canvas 이벤트 18건(신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · errors 2(`제품-기획-제작`만)
- **채널:** rename 0 · 신규 채널 0 · **채널 페이지 신규 생성 0건**(봇 미참여 4개 채널은 내용 확인 불가 → **봇 초대 대기 4일째**) · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음)
- 🔴 **대시보드 11-07(토) = '완전 무변동일'** — 활성 **102 → 102건**, **신규 0 · 완료 0 · 목록 제거 0 · 필드 변경 0**(제목·담당·마감·상태·`project_id` 6필드 전건 diff 0). 완료 이력 **412건 그대로**(`closed_at` = 11-07 레코드 **0건**). **10-25 이후 두 번째 완전 무변동일**이며, **11-06 정리 세션 이후 첫 영업일이 통째로 비었다**
- 🔑 **경과 58건은 숫자가 같지만 구성이 이동** — 11-07 D-0 2건(`더마브랜드 퍼널구조 설계`(전경표) · `사내근로복지기금 직원보너스 조사`(이향석))이 **미처리로 경과 편입**. D-0 1건(11-08 `세무사 솔루션 분석`) · D-1 **7건**(11-09) · D-2 1건(11-10 임차보증금 대출) · D-3 3건(11-11)
- 🔑 **4항 브리지 검산(오차 0):** 어제 스냅샷 as-of 오늘 **58** − 해소(완료 0 + 삭제 0) − **연장 0** + 신규 즉시경과 **0** = **58** | 실측 **58**. 무변동일에는 연장 항이 0이므로 검산이 자동으로 닫힌다 → 역으로 합이 안 맞으면 **날짜 컷오프 계산**을 먼저 의심
- **통계(as-of 11-08 05:00 KST):** 마감 경과 **58건(증감 0)** · **60일 이상 40건(69%)** · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 **97/102(95%)** · 진행중 101 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(16일째) · 담당자별 경과 **강경철 28 · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 2 · 최유미 2 · 강경철·이상원 2 · 이향석 2 · 이상원 1** · 최장 `[에나지크] 캐나다 라벨 리뷰 방안` **149일** · 누적 지연완료 **213/412(52%)**
- **TSonaX:** 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 18일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(25일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-08 실측)
- **한국어 위키 갱신 6건**: `concepts/브랜업-업무-완료-판별.md`(**§13 신설** — 완전 무변동일 판별표(완료·삭제·시리즈·신규·필드변경 5항 전건 0) · '경과 58→58은 이동' 규칙 · 4항 검산이 자동으로 닫히는 조건 · 11-09 7건 도래 경고), `concepts/브랜업-대시보드-입력-품질.md`(**§8 신설** — 11-04~11-07 신규/중복 표(20/12 → 11/8 → 3/0 → 0/—) · '중복 0은 입력 중단이지 UI 개선 아님' · 권고 순위 재정렬(중복 차단 → 마감 과거선택 차단 → 알림)), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§19 신설** — 쇼핑백 발주서 **D-1(7번째 마감, 원본 13일째 0건)** · 11-09 카톤 자료와 겹침 · 11-09~11-15에 5건 집중), `concepts/브랜업-법인행정-재무-라인.md`(**§8 신설** + 기존 §8→§9 재번호 — 11-07 복지기금 D-0 **경과 1일** · `세무사 솔루션 분석` 오늘 D-0 · 11-09에 이 라인 5건 동시 도래 · 임차보증금 11-10 D-2 변동 없음), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-08 현황 — 태국 5일째 정지 · **4개국 16일째 업무 0건**, 공통 9종 확보 자료 0건), `concepts/tsonax.md`(연혁 11-08 추가 + 리스크 최상단 교체) + `channels/index.md`(11-08 스캔 노트 · 헤더 활성 채널 18개) · `index.md`(6개 요약 라인 갱신 + TSonaX 라인 11-08 추기) · `README.md`(재생성)
- **프로젝트 페이지 활동 추가 없음** — Slack 신규 메시지 0건 · 대시보드 신규·변경 0건이며 `project_id` 지정 업무 5건도 전건 장기 경과 그대로 → 특정 프로젝트에 귀속할 신규 활동 없음
- **미조치(신규)**: ① **`코스매틱-진행` vs `00코스매틱-진행` 중복 생성 정리** — 11-06 15:05/15:06 1분 간격, 정본 확인 필요(3일째) ② **봇 초대 4개 채널**(`제품-기획-제작`·`브랜업-멤버십-슬랙-소통-채널`·`코스매틱-진행`·`00코스매틱-진행`) ③ **11-07 하루가 통째로 비었다** — 11-06 정리 세션의 후속 집행이 0건이므로 **11-09(월) 7건이 재연기 없이 도래**할 위험 ④ **`[대시보드] 업무 상태변경 알림`(#572) 경과 2일** — 중복 차단 기능과 같은 배포로 묶어야 재발 감지 가능
- **미조치(지속)**: 쇼핑백 1만개 발주서 **13일째 원본 0건**(7번째 마감 11-09=D-1) · 완료 4건(쇼핑백 2차·세트박스 문안·저알레르기·3ea) 전부 **산출물 문서 0건** · `50ml 전면 문안` 기준 문서 0건 · 더마프로 리포트 원문 11일째 · 아세안 4개국 **16일째 업무 0건** · `[세무] 세무법인 결정` **77일째 미결**(후보 사실상 1곳) · `test_escalate_probe_20261006` 32일째 잔존 · 프로젝트 12/13 보류(진행중 0)
- 파일 변경: `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/tsonax.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261108.json` · `branup_completed_20261108.json` · `branup_snapshot_20261108_projects.json`

## [2026-11-09] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 103건 동기화 완료

## [2026-11-09] daily | 11-08은 '정리일' — 완료 0·신규 1·연장 2, 경과 58은 또 이동 / **연장 사유가 처음으로 기록됨** / Slack 17일 연속 0건

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **103건**(전일 102 → **+1**) · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교) → **업무 신규 메시지 0건 / 신규 파일 0건**. **26시간 창 0건 = 17일 연속**. 업무 대화 최신 `#뷰티-프로젝트` **10-23 01:57** → **17일째 무변동**. 168h 누적 **1건**(`wiki` 11-06 18:03 자체 린트 — 비업무) · 스레드 답글 0 · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, **5일째 동일**)
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 스캔 · 북마크 **0건** · **Canvas 이벤트 18건(신규 0건**, 최신 `브랜업-전체` 10-21 17:54) · errors 2(`제품-기획-제작`만)
- **채널:** rename 0 · 신규 채널 0 · **채널 페이지 신규 생성 0건**(봇 미참여 4개 채널 내용 확인 불가 → **봇 초대 대기 5일째**) · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음)
- 🔴 **대시보드 11-08(일) = '집행 아닌 정리일'** — 완료 **0**(완료 이력 **412건 그대로**, `closed_at` = 11-08 레코드 0건) · 하드 삭제 **0** · **신규 1**(`칸젠뷰티 범용성 제품` #629, 노수민, 15:40:49 등록·**마감 11-08 = 등록 당일 마감** → 익일 경과) · **마감 연장 2** · **제목·요약 변경 2**
- 🔑 **연장에 사유가 붙은 첫 사례** — 11-08 **21:44~23:39** 이향석 계정 4건 갱신: `사내근로복지기금 직원보너스 조사`(#623, 11-07→**11-11**, *"시작 못함 마감 연장 11/7 -> 11/11"*) · `[대시보드] 업무 상태변경 알림`(#572, 11-06→**11-13**, *"텔레그램 알림 기능 **버그 존재** : 마감일 연장 11/6 -> 11/13"*) · `[SVC] 11/05 재무관리 교육`(#556)·`[컨설팅] 재무/회계 정부지원`(#510) 제목에 **`-> 내용문서화`**. **연장 판별 시 `summary`를 함께 읽는 규칙**을 위키에 추가 — 기존 규칙(제목·`due_at`만)으로는 사유를 놓친다
- ⚠️ **`-> 내용문서화` = '했는데 기록이 없는 일'** — SVC 교육(11/05)·컨설팅(11/4~11/6) 모두 **참석은 끝났고 산출물만 남았다**는 표시. 완료 판정 기준은 `closed_at`이 아니라 **문서 확보 여부**여야 한다
- 🔑 **4항 브리지 검산(오차 0):** 어제 스냅샷 as-of 오늘 **59** − 해소(완료 0 + 삭제 0) − **연장 2** + 신규 즉시경과 **1** = **58** | 실측 **58**. 전일(11-07)에는 연장·즉시경과가 0이라 자동으로 닫혔지만 **하루 만에 두 항이 다시 필요**해졌다 → **"경과 58 사흘 연속"은 안정이 아니라 미처리+연기+신규의 상쇄**
- 📌 **11-09(월) D-0 7건이 예고대로 도래** — `[세무] 세무법인 결정`(78일째 미결) · `브랜업 반기 분기 년예상 매출/영업이익` · `쇼핑백(1만개) 발주서`(**7번째 마감**, 원본 14일째 0건) · `[SVC] 재무관리 교육` · `[SVC] 엡버서더 미팅` · `[주간업무회의] 11월 1주` · `오전에 카톤 관련 자료 받기`. D-1 1건(11-10 임차보증금) · D-2 4건(11-11)
- **통계(as-of 11-09 05:00 KST):** 마감 경과 **58건(증감 0)** · **60일 이상 41건(71%)** · `due_at` 미입력 14건 · 담당자 공백 6건 · `project_id` 미지정 **98/103(95%)** · 진행중 102 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(17일째) · 담당자별 경과 **강경철 28 · 김봉재 9 · 전경표 8 · 공백 4 · 노수민 3 · 최유미 2 · 강경철·이상원 2 · 이상원 1 · 이향석 1** · 최장 `[에나지크] 캐나다 라벨 리뷰 방안` **150일** · 누적 지연완료 **213/412(52%)**
- **TSonaX:** 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 19일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(26일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-09 실측)
- **한국어 위키 갱신 8건**: `concepts/브랜업-업무-완료-판별.md`(**§14 신설** — 11-08 5항 판별표(완료 0·삭제 0·신규 1·연장 2·제목변경 2) · 4항 검산 · 연장 사유 기록 규칙 · `-> 내용문서화` 해석), `concepts/브랜업-대시보드-입력-품질.md`(**§9 신설** — 연장 사유 기재율 2/2(이향석 1인 세션) · `#572`가 스스로 "알림 기능 버그 존재" 진술 → §7 권고 3건 전부 미해결 확인 · '등록 당일 마감' 재발 #629), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§20 신설** — 쇼핑백 7번째 마감 D-0·원본 14일째 0건·카톤 자료와 순서 의존 · 🆕 범용성 제품 #629 제형 단순화 → SKU·바코드 조합 전제 변화), `concepts/브랜업-법인행정-재무-라인.md`(**§9 신설** + 기존 §9→§10 재번호 — 이 라인 5건 11-09 동시 도래 · 세무법인 후보 단가표(현명 30/70/20만 · 솔로몬 10/25만 할인) · 78일째 미결), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(11-09 — 태국 6일째 정지 · **4개국 17일째 업무 0건**, 11-09 도래 7건 중 이 라인 0건), `concepts/줄리어스-대표-미팅-20260910.md`(**후속 조치 11-09 추가** — 에나지크 범용성 제품 재오퍼 요청 = 제형 단순화·SKU 축소 축), `concepts/tsonax.md`(연혁 11-09 추가 + Source 11-09 갱신) + `channels/index.md`(11-09 스캔 노트) · `index.md`(6개 요약 라인 갱신 — 대시보드 현황 103건·경과 58·60일 41건 포함) · `projects/브랜업_대시보드_개발.md`(**`## 📋 최근 활동` 신설** — #572 알림 2번째 연기 + "버그 존재" · 중복 차단 미구현 · `project_id` 미지정 98/103) · `README.md`(재생성)
- **미조치(신규)**: ① **`코스매틱-진행` vs `00코스매틱-진행` 중복 생성 정리** — 11-06 15:05/15:06, 정본 확인 필요(**4일째**) ② **봇 초대 4개 채널** ③ **11-09 7건이 오늘 도래** — 완료 0이 이틀 연속(11-07·11-08)이므로 **오늘 처리하지 않으면 11-10 경과가 +7 이상 증가** ④ **`#572`가 보고한 "텔레그램 알림 기능 버그"** — 대시보드 기능 자체의 결함이므로 개발 백로그로 옮겨야 함(동일 요청에 중복 차단 포함)
- **미조치(지속)**: 쇼핑백 1만개 발주서 **14일째 원본 0건**(7번째 마감=D-0) · 완료 4건(쇼핑백 2차·세트박스 문안·저알레르기·3ea) 전부 **산출물 문서 0건** · `50ml 전면 문안` 기준 문서 0건 · 더마프로 리포트 원문 12일째 · 아세안 4개국 **17일째 업무 0건** · `[세무] 세무법인 결정` **78일째 미결** · `test_escalate_probe_20261006` 33일째 잔존 · 프로젝트 12/13 보류(진행중 0) · **`kangen-뷰티-문안-바코드-표준.md` 366줄**(200줄 초과 — 분할 필요, 주간 린트 지적 유지)
- 파일 변경: `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/줄리어스-대표-미팅-20260910.md`, `concepts/tsonax.md`, `channels/index.md`, `index.md`, `projects/브랜업_대시보드_개발.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261109.json` · `branup_completed_20261109.json` · `branup_snapshot_20261109_projects.json`

## [2026-11-10] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 75건 동기화 완료

## [2026-11-10] daily | 11-09 = '역대 최대 보드 대청소' — 제거 41(완료 7 + **하드 삭제 34**), 경과 58 → 22 / **Slack 17일 만에 재개** (design-backup 전성분 통일안) / 세트박스 후면 검수 4건 정시 종결

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **75건**(전일 103 → **−28**) · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교, **curl 기반**) → 🔔 **업무 메시지 9건 / 신규 파일 0건 — 17일 연속 0건 종료**. 재개 채널은 **`#design-backup` 단독**(11-09 09:37~19:42, **노수민 SueminNoh** 8건 + Canvas 1건). 168h 누적 **10건**(design-backup 9 · `wiki` 1) · 스레드 답글 0 · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, **6일째**)
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 · 북마크 **0건** · **Canvas 이벤트 19건(신규 1건** = design-backup 11-09 19:06, 10-19 이후 첫 갱신) · errors 2
- **채널:** rename 0 · 신규 채널 0 · 페이지 신규 생성 0 · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음)
- 🆕 **`#design-backup` 11-09 = 문안 규격이 '파일'에서 '텍스트'로 넘어온 날** — ① `[전성분 통일] 스탭 1·2·3` **INCI 전문**(성분수 **94·105·63**, 불어 병기 `Water(Eau)`·`Milk Protein(Protéine du lait)`·`Beeswax(Cire d'abeille)`) ② `*후면 고시 사항*` **13항목**(**미국 전성분 불어 병기 추가**, 상자 `IMP`→`Imported by`/`Importé par`, 캐나다는 `IMP. BY / PAR` 유지, 바코드 제품별 상이) ③ `*[주요 변동 상황]*` **동판 2건**(50ml 캐나다 상짝 안쪽 · 15ml 상짝 Enagic 로고) + 색상 3건 ④ `15ml, 50ml 로고 동판 각 같은 위치`. **파일 0건**이라 다운로드·판독 없음 → 전문 `raw/articles/slack-design-backup-20261109-copy-ingredients.md`(sha256 기록)
- ⚠️ **전성분 대조 결과(중요):** 09-28 EYESEL 전성분표(93/104/63)와 비교해 **스탭3(63)만 일치**, 스탭1·2는 **각 +1**. 결정적으로 **09-28 표에 있던 `Mink Oil 5%`(STEP III)가 통일안 63성분에 없다** — 성분수 동일(63)하므로 **다른 성분과의 교체** 가능성. 63건 전량 대조 전에는 단정 불가 → **다음 회차 확인 1순위**(문안 표준 §21-1)
- 🔴 **대시보드 11-09(월) = 위키 추적 이래 최대 '보드 대청소'** — 활성 **103 → 75**(−28), 완료 이력 **412 → 424**(+12), 마감 경과 **58 → 22**(−36). 제거 **41** = **완료 7 + 하드 삭제 34**(시리즈 교체 0) · 신규 **13** · 마감 연장 **3** · 제목·요약 변경 **4**
- 🔑 **4항 브리지 검산 오차 0:** `어제 스냅샷 as-of 오늘 65 − 해소 43 − 연장 3 + 신규 즉시경과 0 = 22` | 실측 **22**. **해소 43 = 제거 40 + 마감 연장 3**(#362 11-09→11-11 · #378 11-09→11-13 · #370 10-10→12-12). 제거 41건 중 경과였던 것 40건(#464는 마감 없음)·나머지 1건은 조정 대상 아님
- 🔴 **−36을 개선으로 읽으면 안 된다** — 22건 중 **집행으로 닫힌 것 7건(19%)**, 나머지 **34건(79%)은 기록 없는 삭제**. 누적 하드 삭제 **11-01 7 → 11-02 0 → 11-03 1 → 11-04 0 → 11-05 0 → 11-06 22 → 11-07 0 → 11-08 0 → 11-09 34**. 34건 전부 **동일 보드(`dca8c6fe`) 소속** = 보드 이탈이 아닌 **건별 삭제**, 생성월 6월 5 · 7월 14 · 8월 4 · 9월 9 · 10월 2
- ⚠️ **삭제 34건에 실질 업무 다수** — `[에나지크] 캐나다 라벨 리뷰 방안`(#81, **최장 경과 150일**) · `[에나지크] 샘플/비매품 용기 문안…`(#365) · `[에나지크] 용기 면적에 따른 문항 정리`(#412) · `[에나지크] 지원 발주서 2p 별첨`(#86) · `캐나다향 해상/항공 부킹`(#262) · `아이젤 가격 협상 기초안`(#402) · `CDRI 멤버십 미팅 조율`(#472) · `[정육공방] 곰탕 포장용기 샘플테스트`(#319) · **`원티드 80% 환급 요청`(#451)** · `토스 반려 확인`(#417) · `카톤박스 견적 받기`(#380). **에나지크 라벨·발주서 계열 4건이 한꺼번에 소멸**한 것은 11-09 세트박스 후면 검수(전경표 4건 완료)와 같은 라인이라 **종결인지 정리인지 판별 불가**
- ✅ **긍정 정리 1건:** **33일째 잔존**하던 테스트 레코드 `test_escalate_probe_20261006`(#464) 삭제
- ✅ **11-09 완료 12건** — (a) 목록 내 7건: `[주간업무회의] 11월 1주`(#609, 11:22) · `코스메틱 기초 자료 리서치`(#117, 18:33) · `카탈로그 감리`(#303, 18:37) · `packing list 줄리어스 대표님께 전달`(#388, 18:37) · `[SVC] 11/05 재무관리 교육`(#556, 20:01) · `세무사 솔루션 분석`(#592, 20:04) · `[SVC] 엡버서더 미팅`(#557, 20:04) (b) **당일 등록·당일 완료 5건(전경표, 22:22 일괄)**: `클로브 ai 인수인계 회의`(#638) · `15mL 세트박스 후면 검토`(#639) · `50mL 세트박스 후면 수정사항 반영`(#641) · `세트박스 전후면 디자인 파일 최종 검수`(#647) · `메타 광고 세팅 변경`(#648) — **전건 정시**
- 🆕 **11-09 신규 13건** — `[계약석] 브랜업코러스 물품공급계약서 초안`(#630, 이향석, **11-10**) · `11월 2주차 채용공고 지원내역 검토`(#631) · `[칸겐뷰트] 실링 스티커 2차 리서치 자료 전달`(#632, **11-10**) · `[정육공방] OEM 계약서 초안`(#633, **11-11**) · `[정육공방] 정부지원사업 검토 및 보고`(#634, 11-13) · `[칸겐뷰트] 광고 소재 데이터 취합 및 기획안 전달`(#635, 11-13) · `[주간업무회의] 12월 1주`(#637, 12-04) · `변경된 문안 총정리 및 관리, 검수 파일 생성`(#640, 11-13) · `2027 AX 이니셔티브 컨퍼런스`(#642, 11-23) · `[SVC][Venture Park] AI와 비즈니스의 미래`(#643, 11-12) · `세트박스 입고 확인(조영길)`(#644, **11-10**) · `QQ 방식 전성분표 재문의`(#645, **11-10**) · `[정육공방] 카페24 지급보류 소명자료 준비`(#646, **11-10**)
- 🔑 **11-09 입력 품질: 첫 '대량 등록 + 무사고'** — 신규 13건 **중복 0**, **등록 즉시 경과 0**(마감 전건 미래: 11-10 4 · 11-11 1 · 11-12 1 · 11-13 5 · 11-23 1 · 12-04 1). 전경표가 10:07~10:11 **1분 간격 6건**을 넣고도 중복 미발생. 단 **등록 익일 마감 3건** 재발(#630 05:23·#632 10:08·#646 21:38). 구조 지표는 그대로 — `project_id` 미지정 **74/75(99%)** · `due_at` 미입력 13 · 담당 공백 2 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(18일째)
- 🔑 **경과 22건의 구성이 완전히 바뀌었다** — 60일 이상 **15건(68%)**, 그중 **13건이 김봉재·노수민·전경표의 6~9월 등록분**(최장 `nfc 명함 업체 컨택 후 발주` 136일). 즉 **대청소에서 살아남은 것이 '방치된 개인 과제'** → 삭제 기준이 '오래된 것'이 아니라 **'누가 담당했는가'** 였을 가능성(확인 필요). 담당자별 경과 **김봉재 9 · 강경철 4 · 노수민 3 · 전경표 3 · 최유미 2 · 이상원 1**
- 🔴 **쇼핑백(1만개) 발주서(#536) 8번째 마감 통과** — 11-09 → **경과 1일**, 등록(10-27) 후 **원본 15일째 0건**. 단가 4,082원·카톤 수지판비 조건 + 동판·색상이 11-09에 모두 확정됐으므로 **남은 것은 문서 1장**. `오전에 카톤 관련 자료 받기`(#626)도 같은 날 경과 → **순서 의존인데 둘 다 미처리**
- 🔑 **세무 라인:** `세무사 솔루션 분석`(#592) **완료(11-08 → 1일 지연)** 후 같은 시각(20:04) `[세무] 세무법인 결정`(#362) 갱신 — **후보 2명 추가(김선영·정서현)**, `김선영세무사 솔루션(어니스트 필요경비→프리랜서 급여처리, 3.3% + 경비처리비용 10%)`·`정서현 님과 논의 중` 신규. 마감 **11-09 → 11-11**, **79일째 미결**
- 🟡 **`반기 분기 년예상 매출/영업이익`(#378) 산출물 재정의** — "IR 재무자료 최근 것(2026)은 내년에 공식 자료가 세무사무실에서 나오니 **평소 자금내역을 업데이트해 예상재무표 작성**" → **11-09 → 11-13**. 즉 2026 공식 재무제표 확보 불가 → [[concepts/브랜업-ir-202610|IR 자료]] 재무 파트 갱신 계획에 반영 필요
- 🔴 **`#556`이 '내용문서화'를 달고 완료됐는데 문서가 없다** — 11-08 제목 변경(참석 종료·문서 미완 표시) → 11-09 20:01 완료. 판별 §14의 "완료 기준은 `closed_at`이 아니라 문서 확보" 규칙이 **하루 만에 위반**
- 📌 **11-10 D-0 6건:** `임차보증금 대출 방법 조사`(#628) · `브랜업코러스 물품공급계약서 초안`(#630) · `실링 스티커 2차 자료 전달`(#632) · `세트박스 입고 확인`(#644) · `QQ 방식 전성분표 재문의`(#645) · `카페24 지급보류 소명자료`(#646). **11-11 5건 · 11-13 11건** 뒤따름
- **통계(as-of 11-10 05:00 KST):** 마감 경과 **22건(−36)** · 60일 이상 **15건(68%)** · `due_at` 미입력 13 · 담당자 공백 2 · `project_id` 미지정 **74/75(99%)** · 진행중 74 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0** · 최장 `nfc 명함 업체 컨택 후 발주` **136일**(노수민) · 누적 지연완료 **393/424(93%)**
- **TSonaX:** 대시보드 활성 2건(#431·#201) **마감 없는 '진행중' 20일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(27일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-10 실측)
- **한국어 위키 갱신 12건**: `channels/branup-design-backup.md`(**11-09 섹션 신설** — INCI 3종·13항목·동판/색상·Canvas 15건/19건 + **주요 의결 4건 추가** + 관련 raw 링크), `concepts/kangen-뷰티-문안-바코드-표준.md`(**§21 신설** — 21-1 전성분 대조표(94/105/63 vs 93/104/63, Mink Oil 부재) · 21-2 후면 고시 13항목 표 + `IMP` 표기 충돌 경고 · 21-3 동판·색상 · 21-4 11-09 대시보드 상태표), `concepts/브랜업-업무-완료-판별.md`(**§15 신설** — 제거 41 3분류·4항 검산·삭제 34 목록·감사 추적 부재), `concepts/브랜업-대시보드-입력-품질.md`(**§10 신설** — 11-09 무사고 대량 등록·익일 마감 3건·경과 22 구성 변화·삭제 기준 가설), `concepts/브랜업-법인행정-재무-라인.md`(**§10 신설** + 기존 §10→§11 재번호 — 라인 4건 완료·세무 후보 확대·#378 산출물 재정의·#556 문서 부재), `concepts/tsonax.md`(연혁 11-10 + Source 갱신), `entities/브랜업코러스.md`(**11-09 물품공급계약서 섹션 신설** — 구매확인서→기본계약 전환의 의미·대조 4항목), **`entities/정육공방.md`(신규** — 7건 업무표 + 미확인 4항목, confidence low), `channels/index.md`(11-10 스캔 노트 + Last updated), `index.md`(헤더 65페이지·채널/개념 5개 라인 갱신·정육공방 등재), `projects/에나지크_발주_시뮬레이터.md`(**11-10 항목** — 문안 규격 확정·검수 종결·발주서 8번째 마감·에나지크 4건 삭제), `projects/브랜업_대시보드_개발.md`(**11-10 항목** — 보드 대청소·중복 0·알림 버그 미해결·soft delete 필요) + `README.md`(재생성) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261110.json` · `branup_completed_20261110.json` · `branup_snapshot_20261110_projects.json`
- **미조치(신규)**: ① **전성분 통일안 STEP III에서 `Mink Oil 5%` 소멸 — 교체 여부 확인**(63건 전량 대조 또는 디자인팀 문의) ② **상자 표기 `IMP` → `Imported by`가 7월 확정 표지(`IMP. BY`)와 충돌** — 인쇄 발주 전 확정 ③ **#9 디스트리뷰트 문구 원문 축약**(`*! 미국은 해당으로 병기`) — 대상 단어 생략, 확인 필요 ④ **삭제 34건 중 `원티드 80% 환급 요청`·`카톤박스 견적`·`CDRI 멤버십`의 종결 여부**(환급금·견적은 미수령 시 손실) ⑤ **`#556`이 문서 없이 완료** — SVC 교육 자료 등재 요청
- **미조치(지속)**: 쇼핑백 1만개 발주서 **원본 15일째 0건**(8번째 마감) · `50ml 전면 문안` 기준 문서 0건 · 더마프로 리포트 원문 · 아세안 4개국 **18일째 업무 0건** · `코스매틱-진행` vs `00코스매틱-진행` 중복 정리(**5일째**) · 봇 초대 4개 채널(**6일째**) · 프로젝트 12/13 보류(진행중 0) · `kangen-뷰티-문안-바코드-표준.md` **436줄**(200줄 초과 — 분할 필요)

## [2026-11-11] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 92건 동기화 완료

## [2026-11-11] daily | 11-10 = '집행일' — 완료 **13**(추적 이래 최다) · 신규 23 · **하드 삭제 1 = 쇼핑백 발주서(#536)** / Slack 0건(재개 다음날 무활동) / 문안 표준 페이지 **분할 완료**

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **92건**(전일 75 → **+17**) · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교, **curl 기반**) → **업무 메시지 0건 / 신규 파일 0건**. **26시간 창 0건 = 직전 재개(11-09) 이후 첫 무활동일**. 168h 누적 **10건**(design-backup 11-09 9건 · `wiki` 11-06 1건 — 전량 기수록). 업무 대화 최신 `#design-backup` **11-09 19:42** → **1일째 변동 없음** · 스레드 답글 0 · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, **7일째**)
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 · 북마크 **0건** · **Canvas 이벤트 19건(신규 0건**, 최신 `design-backup` 11-09 19:06) · errors 2(`제품-기획-제작`)
- **채널:** rename 0 · 신규 채널 0 · **채널 페이지 신규 생성 0건**(봇 미참여 4개 채널 내용 확인 불가 → **봇 초대 대기 7일째**) · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음)
- 🟢 **11-10(월) = '집행일'** — 활성 **75 → 92**(+17), 완료 이력 **424 → 437**(+13), 마감 경과 **22 → 22**(증감 0). 제거 **6** = 완료 **5**(목록 내) + **하드 삭제 1** · 신규 **23** · 마감 연장 **4** · **마감 단축 1** · 요약 변경 4
- 🔑 **4항 브리지 검산 오차 0:** `어제 스냅샷 as-of 오늘 28 − 해소 6 − 연장(경과이탈) 2 + 신규 즉시경과 2 = 22` | 실측 **22**. **연장 2건은 #621(칸겐뷰티 타임리스 레디언스 출원)·#624(바뀐 원료 목록 공유)** — 11-09→11-11. **#586·#523·#223은 경과 상태가 아니어서 연장 항에 잡히지 않는다** → 연장 항은 '경과를 벗어난 건수'로만 센다(전체 마감 변경 5건과 혼동 금지)
- 🔴 **유일한 삭제가 `쇼핑백(1만개) 발주서`(#536)** — due 11-09(8번째 마감) · 10-27 등록 후 **원본 15일째 0건**으로 위키가 매 회차 '미조치(지속)' 1순위에 올려둔 항목. 완료 이력 437건 대조 결과 **레코드 0건** → **취소인지 정리 실수인지 영구 판별 불가**. 더 큰 문제는 **추적 앵커 자체가 사라졌다**는 것(대시보드·알림·경과 집계·검색 어디에도 존재하지 않음). 같은 날 선행조건 `오전에 카톤 관련 자료 받기`(#626)는 **완료(10:20, 1일 지연)** → ㉠ 시스템 밖 실제 발주 ㉡ 자료만 받고 정리, **둘 다 열려 있어 당사자 확인 필요**
- ✅ **완료 13건 = 이 위키 추적 이래 최다**(직전 최다 11-09 12건) — 디자인 **2**(`세트박스 수정` #649 · **`15ml 박스 발주파일 제작 및 전송` #650**, 11-10 16:43, **11-09 통일안의 첫 문서 산출물**) · 태국 **3**(`THAI FDA 등록 정보 작성` #675 **11-11 마감을 1일 조기** · `아이젤 태국 등록 관련 문의` #670 · `실링 스티커 1차 CDRI 문의 송달` #632) · 입고·정산 **2**(`세트박스 입고 확인(조영길)` #644 1일 지연 · `[정육공방] 카페24 지급보류 소명자료` #646) · 기타 **6**(`칸젠뷰티 범용성 제품` #629 2일 지연 · `[코스메카] 아이솔루션` #657 **3일 조기** · `클로브AI 지출내역 트래킹` #673·#674 · `인스타그램 블루 배지` #672 · `오전 카톤 자료` #626). **13건 중 10건이 당일 등록·당일 완료**, 지연완료 누적 **404/437(92%)**
- 🆕 **11-10 신규 23건** — 노수민 **11건**(09:24~09:29 5분간 1분 간격: 아이젤 향료·용기·신규원료·튜브수배·룩앤필 / 두코 미스트 / 코스메카 클렌징밤 / 상자감리 / 명함 / 에나직 인스타 / 사이트 수정) · 이향석 **5건**(`[KCL] 삼덕회계 비용 제출` **3연속 시리즈** 11-16·11-23·11-30 + `[KCL] 11/30 최종보고서` + **상표권 #677**) · 강경철 **3건**(태국 문안·TRA QQ 전성분표·미출고분 검토) · 담당 **공백 4건**
- ⚠️ **입력 품질: 중복 1쌍 재발 + 등록 당일 마감 사흘 연속** — `[칸겐뷰트] 인스타그램 블루 배지 구독 재확인`이 **#671**(11:01, 담당 공백, due 11-10, **경과 잔존**)·**#672**(13:28 완료)로 이중 등록 → **11-05 이후 5일 만의 중복**. **등록 당일 마감 2건**(#671 11:01·#677 15:10, 둘 다 due 11-10 = 등록 즉시 경과)로 **사흘 연속(11-08 #629 · 11-09 3건 · 11-10 2건)**. 단 **`[KCL] 삼덕회계` 3연속(#667/#668/#669)은 롤링 시리즈로 중복 아님** → 중복 판정은 제목+마감일 동시 기준. 구조 지표 악화: `project_id` 미지정 **91/92(99%)**, 신규 23건 **전건 미지정**
- 🆕 **태국/아세안 라인 18일 만에 재개** — 완료 2 · 신규 2 · **마감 단축 1**(`태국 스티커 최적화` #586 **12-03 → 11-13, 20일 앞당김 = 이 위키 최초 관측**). **4개국(홍콩·말레이시아·싱가포르·필리핀)은 19일째 업무 0건** 유지
- 🔴 **금융 조달 봉쇄(#628)** — `신용보증기금 예산 부족으로 어려움, 2027년 초에 재시도` · 서울신보 일반상품은 **2025 하반기~2026 상반기 부가세 매출 1억 초과** 요건에 최대 1억·연 3% 중반·**대표이사 직접 방문 필수**. 즉 **2026년 내 은행권 조달 경로 없음**(경과 1일)
- 🟢 **`#510` 컨설팅 솔루션 4건 확정** — ① 연구비(화장품개발비) 자산화 → 자본잠식 해결(?) ② **주업종 도소매→제조업 "2026 가기 전에"** ③ 재경관리사 ④ 연구소설립 2027. **②는 `#628` 검토의견("업종전환 우선 추진보다 매출요건 확인")과 충돌** — 기록만 되고 결정 안 됨 → 미조치 등재
- 🟡 **SVC Seoul 10인실 입주 공고 개시(#523)** — 508호 29㎡ · 임대료 **월 3,365,490원** · 보증금 **10,096,470원** · 계약 ~2028.5.31 · 입주 12.9~12.23(**2027.1.1까지 필수**) · **서류 마감 11.16(월) 11:00** · 임대료 3개월 선납 필요. 마감 11-13 → **11-16**. **장기 경과 `svc 입주 방법 탐색 및 기획`(#371, 김봉재, 72일)이 처음 구체적 대상을 얻음** — 단 보증금 현금 확보가 `#628` 결론과 정면 충돌
- 🆕 **상표권 리스크(#677)** — 경기도 광명시 개인사업자가 **'브랜업' 상호 사용** 중, 사용 제재 요청 가능 여부 조사. 등록 11-10·마감 11-10 → 즉시 경과. 상표 등록 상태·근거 문서 0건
- 🔴 **`#362` 세무법인 80일째 미결** — 11-09 후보 2명 추가(김선영·정서현) 이후 **11-10 변동 0건**, 후보 6명. 11-11 D-0
- **통계(as-of 11-11 05:00 KST):** 마감 경과 **22건(증감 0)** · **60일 이상 15건(68%)** · `due_at` 미입력 13건 · 담당자 공백 6건 · `project_id` 미지정 **91/92(99%)** · 진행중 91 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(19일째) · 담당자별 경과 **김봉재 9 · 전경표 3 · 노수민 2 · 최유미 2 · 이향석 2 · 이향석·전경표 1 · 강경철 1 · 이상원 1 · 공백 1** · 최장 `nfc 명함 업체 컨택 후 발주` **137일** · 누적 지연완료 **404/437(92%)**
- 📌 **11-11 D-0 9건 · 11-12 3건 · 11-13 17건**(11-13은 **단일 날짜 최다**, 직전 최다 11-09 7건). 11-13: `#378` 매출예상 · `#504` 정부지원 모니터링 · `#515` 제품명 재등록 · `#572` 대시보드 알림 · `#586` 태국 스티커 · `#610` 주간업무회의 2주 · `#631` 채용공고 검토 · `#634` 정육공방 정부지원 · `#635` 광고소재 · `#640` 문안 총정리 · `#658` 코스메카 · `#660` 아이젤 QC · `#661` 카탈로그 · `#663` 명함 · `#664` 에나직 인스타 · `#665` 사이트 · `#676` 태국 문안
- **TSonaX:** 대시보드 활성 2건(#431 `[Toffer] 익절/손절 시나리오 개선`·#201 `대표님 지표추가`) **마감 없는 '진행중' 21일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(28일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-11 실측)
- 📄 **페이지 분할 완료(6주째 린트 지적 해소):** `concepts/kangen-뷰티-문안-바코드-표준` **466줄 → 285줄**. §16~§22를 **`concepts/kangen-문안-이력-2026-11`(206줄)로 분리**(신규). 분리에 따라 §16~§22를 가리키던 **참조 13건을 새 페이지로 리다이렉트**(`projects/에나지크_발주_시뮬레이터` 1 · `concepts/줄리어스-대표-미팅-20260910` 1 · `concepts/tsonax` 1 · `concepts/브랜업-업무-완료-판별` 4 · `concepts/칸겐보떼-아세안-규제-신고-자료` 5 · `concepts/브랜업-대시보드-입력-품질` 1) → **잔여 0건 확인**
- **한국어 위키 갱신 12건**: `concepts/브랜업-업무-완료-판별.md`(**§16 신설** — 11-10 8항 판별표 · 쇼핑백 #536 삭제의 의미 · 4항 검산 · '연장 항은 경과이탈만' 규칙 · 11-13 17건 경고), `concepts/브랜업-대시보드-입력-품질.md`(**§11 신설** — 신규 23건 표 · 중복 1쌍 재발 · KCL 3연속은 롤링 · 등록 당일 마감 사흘 연속 · 담당 공백 4건), `concepts/브랜업-법인행정-재무-라인.md`(**§11 신설** + 기존 §11→§12 재번호 — 금융 조달 봉쇄 · 컨설팅 솔루션 4건과 업종전환 충돌 · SVC 10인실 공고 상세 · 상표권 리스크), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(**§2026-11-11** — 태국 라인 재개 5행 표 · 마감 단축의 의미 · TRA 약어 신규), `concepts/kangen-뷰티-문안-바코드-표준.md`(§22 추가 후 **§16~§22 이력 페이지로 분할** + 포인터), `concepts/kangen-문안-이력-2026-11.md`(**신규** — §16~§22 전문 + 분리 사유), `concepts/tsonax.md`(연혁 11-11 + **리스크 최상단 교체** + Source 갱신), `channels/index.md`(11-11 스캔 노트 + Last updated), `index.md`(헤더 **66페이지** · 신규 페이지 등재 · 요약 라인 7건 갱신 · 일일 크론 노트), `projects/에나지크_발주_시뮬레이터.md`(**11-11 항목** — 첫 산출물·#536 삭제·입고 확보·태국 재개), `projects/브랜업_대시보드_개발.md`(**11-11 항목** + 중복 `## 📝 업무` 섹션 정리 — 개발 백로그 4건으로 확대) + `README.md`(재생성) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261111.json` · `branup_completed_20261111.json` · `branup_snapshot_20261111_projects.json`
- **미조치(신규)**: ① **쇼핑백 1만개 발주서가 실제 발행됐는지 확인**(#536 삭제 — 8번째 마감·원본 15일째 0건이던 최고 리스크 항목, 미발주 시 12월 양산 리스크) ② **업종전환 시점 결정** — 컨설턴트 "2026 가기 전" vs #628 "매출요건 확인 우선" **충돌** ③ **SVC 10인실 서류 11-16 11:00** — 사업계획서·입주신청서 + 보증금 1,010만원 현금 계획 ④ **상표권 #677 조사 착수** — 등록 상태부터 확인 ⑤ **#671 중복 사본 정리**(#672 완료, #671 경과 잔존) ⑥ **11-13 D-2 17건** — 단일 날짜 최다, 미처리 22건 위에 신규 23건이 쌓여 경과 30건대 재진입 위험
- **미조치(지속)**: `50ml 전면 문안` 기준 문서 0건 · `QQ 전성분표`/`TRA QQ`의 **Mink Oil 소멸 여부 미확인** · 완료 4건(쇼핑백 2차·세트박스 문안·저알레르기·3ea) 산출물 문서 0건 · `[세무] 세무법인 결정` **80일째 미결** · 아세안 4개국 **19일째 업무 0건** · `코스매틱-진행` vs `00코스매틱-진행` 중복 정리(**7일째**) · 봇 초대 4개 채널(**7일째**) · 프로젝트 12/13 보류(진행중 0) · `kangen-뷰티-문안-바코드-표준` **285줄**(200줄 초과 — §1~§15 핵심 규격이라 추가 분할 검토)
- 파일 변경: `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/kangen-뷰티-문안-바코드-표준.md`, `concepts/kangen-문안-이력-2026-11.md`(신규), `concepts/tsonax.md`, `concepts/줄리어스-대표-미팅-20260910.md`, `channels/index.md`, `index.md`, `projects/에나지크_발주_시뮬레이터.md`, `projects/브랜업_대시보드_개발.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 3종

## [2026-11-12] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 94건 동기화 완료

## [2026-11-12] daily | 11-11 = **삭제 없는 날** — 제거 8(완료 7 + 중복 사본 1), 경과 22→**21** / Slack 삽지 디자인 1건 / **지연율 산식 오류(92%→49.1%) 발견·정정**

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **94건**(전일 92 → **+2**) · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교, **curl 기반**) → 🔔 **업무 메시지 1건 / 신규 파일 0건**. 채널은 **`#design-backup` 단독** — **11-11 19:01 노수민(SueminNoh)** `*[삽지 디자인]*` (50ml 기존 방식 유지·레이아웃 일부 수정(미국-제형 이미지가 너무 큼)·글자 볼드 수정 / **15ml 원단 A6·양면 인쇄·벨벳코팅(?)**). **파일 0건**이라 다운로드·판독 없음 → 전문 `raw/articles/slack-design-backup-20261111-insert-design.md`(sha256 `59b7bf33…`)
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 · 북마크 **0건** · **Canvas 이벤트 19건(신규 0건**, 최신 `design-backup` 11-09 19:06) · errors 2(`제품-기획-제작`)
- **채널:** rename 0 · 신규 채널 0 · **채널 페이지 신규 생성 0건** · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음) · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, **8일째 봇 초대 대기**)
- ✅ **11-11 = '삭제 없는 날'** — 활성 **92 → 94**(+2), 완료 이력 **437 → 448**(+11). 제거 **8** = **완료 7**(id 일치) + **중복 사본 정리 1**(#671) · **하드 삭제 0** · 신규 **10** · 마감 연장 **4** · 단축 **0** · 요약 변경 4
- 🔑 **4항 브리지 검산 오차 0:** `어제 스냅샷 as-of 오늘 31 − 해소 7 − 연장(경과이탈) 4 + 신규 즉시경과 1 = 21` | 실측 **21**. **연장 4건** = #630(11-10→11-13)·#633(11-11→11-13)·#621·#624(11-11→11-12). **#572·#378·#504는 경과가 아니어서 연장 항에 안 잡힌다**(전체 마감 변경 8건과 혼동 금지)
- 🔑 **`#671`은 '완료'가 아니라 '중복 사본 정리'** — 11-10 중복 사고(#671 담당 공백 / #672 13:28 완료)의 미완 사본이 삭제됐다. **id 매칭 0건**이라 완료로 세면 11-11 완료가 12건으로 부풀려진다
- ✅ **완료 11건**: `#510` 컨설팅(08:39 정시) · **`#628` 임차보증금 대출(08:42, 1일 지연)** — **결론이 summary에 남은 첫 완료**(KB은행 단독 불가 → 신보 100% 보증서, 신보 예산 소진으로 **2027년 초 재시도**, 서울신보 기본 5천만·일반상품 1억/연 3% 중반·창업자금은 업종전환 후 1회) · `#645` QQ 전성분표(1일 지연) · **`#623` 복지기금(정시, "시작 못함" 2회 연기 끝)** · **`#678` TRA QQ 기준(정시)** · `#656` 두코 미스트(정시) · `#658` 코스메카 클렌징밤(**2일 조기**) + 당일 완료 4건(클로브AI 점심/저녁 · 리드 마케터 채용 구조 · 정육공방 샘플 활용)
- 🆕 **신규 10건이 4개 도메인으로 확산** — **보안**(`#686` 서버 해킹 대처: RDP·MySQL·데이터 송신 서버·웹서비스, **등록 당일 마감 → 즉시 경과**) · **정책자금**(`#681` 중진청, **긴급**, due **2027-01-01** = 관측 최장 미래 마감) · **업종전환**(`#680` 제조업 주업종 변경, **마감 없음** — 컨설팅 솔루션 ②의 실행 착수) · **신규 거래처**(`#692` 종이비누 김동규 이사, 견적·리드타임·MOQ·개발비) + 태국/문안 4건(`#682`·`#685`·`#687`·`#690`)
- 🔑 **`#678` 완료가 'Mink Oil 소멸' 질문을 종결** — 원료 단종 확정: **스텝1 INCI 1개 제외 + 복합물질 토코페롤 제외**, **스텝2 INCI 동일·배합비율 변경**, **스텝3 밍크오일 제외 → 스쿠알란**(동물성 오일 인증 문제). → 11-09 통일안(94/105/63)은 **변경 전 기준**이고 변경 후 스텝1은 93 이하 → **09-28 EYESEL 표(93/104/63)와 정합**. **15ml 박스 발주파일(#650)이 이미 전송**돼 **인쇄 전 확정본(#640, 11-13) 확보가 시급**
- 🆕 **`#682` 리서치 범위 5개국 → 23~25개국**(제목 23 vs 요약 25 **불일치**) — 10-23 요청서의 5개국 대비 4~5배. 공통 9종 자료 재사용 불가 → 4개국(홍콩·말레이시아·싱가포르·필리핀)은 **20일째 업무 0건** 유지
- 🆕 **`#688`(11-12 D-0)**: 원료 변경 시 **안전성검사·글로벌 등록 재수행 여부** 아이젤 문의 → 답에 따라 **KCL SGS 12-31 일정**이 흔들린다
- 🔴 **지연율 산식 오류 발견·정정(이 회차 최대 발견)** — 종전 회차는 `due_at`(`'YYYY-MM-DD'`)과 `closed_at`(`'YYYY-MM-DDTHH:MM:SS+09:00'`)을 **문자열로 비교**해 **같은 날 완료 193건을 전부 지연으로 집계**했다(11-10 '393/424(93%)'·11-11 '404/437(92%)'의 원인). **날짜 파싱 후 비교하면 220/448 = 49.1%**(정시 220 · 결측 8)이며, 11-09까지 보고된 52%대와 일치한다. → 규칙을 [[concepts/브랜업-업무-완료-판별]] §17-5에 명문화하고, `concepts/tsonax`·`index.md`의 해당 표기를 정정
- 🆕 **신규 페이지 `concepts/브랜업-상표권-리스크`** — `#677` summary가 '조사 메모'에서 **법률 자문 요청서**로 확장(11-11 08:41): 당사 출원 **40-2026-0210179·40-2026-0210195**(제35·42류) · 상대 사업자 **172-42-00737**, `bran-up.com`, `@bran_up_`, 인스타 첫 게시 **2023-01-04**, 상대 상표 출원·등록 없음, 도메인 등록일 비교 · **자문 4항목**(계속 사용 가능성·선사용 영향·현재 조치·공존 조건), **월 3시간 한도·서면 답변**, 경고장·합의서·소송은 범위 제외. **11-12 경과 1일**
- **통계(as-of 11-12 05:00 KST):** 마감 경과 **21건(−1)** · **60일 이상 15건(71%)** · `due_at` 미입력 **14건** · 담당자 공백 **5건** · `project_id` 미지정 **93/94(99%)** · 진행중 93 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(20일째) · 담당자별 경과 **김봉재 9 · 전경표 3 · 노수민 2 · 최유미 2 · 이향석 2 · 이상원 계열 2 · 이향석·전경표 1** · 최장 `nfc 명함 업체 컨택 후 발주` **138일**(노수민) · 누적 지연완료 **220/448(49.1%)**
- 📌 **11-12 D-0 8건 · 11-13 22건**(단일 날짜 최다) · D-3 2건(11-15). 11-13: `#378`·`#504`·`#515`·`#572`·`#586`·`#610`·`#630`·`#631`·`#633`·`#634`·`#635`·`#640`·`#660`·`#661`·`#663`·`#664`·`#665`·`#676`·`#682`·`#685`·`#687`·`#690`
- **TSonaX:** 대시보드 활성 2건(#431 `[Toffer] 익절/손절 시나리오 개선`·#201 `대표님 지표추가`) **마감 없는 '진행중' 22일째** · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(29일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-12 실측)
- **한국어 위키 갱신 12건**: `channels/branup-design-backup.md`(**11-11 삽지 섹션 신설** + raw 링크 + updated), `channels/index.md`(11-12 스캔 노트 + Last updated), `index.md`(헤더 **67페이지(concepts 25)** · 신규 페이지 등재 · 요약 6개 라인 갱신 · TSonaX 라인 11-12 추가 · 일일 크론 노트), `concepts/브랜업-업무-완료-판별.md`(**§17 신설** — 11-11 판별표·중복 사본 분류·4항 검산·**지연율 산식 정정**; §16의 '404건(92%)' 정정 주석), `concepts/브랜업-대시보드-입력-품질.md`(**§12 신설** — 신규 10건·중복 0 회복·등록 당일 마감 나흘 연속·**제목↔요약 숫자 불일치**·병렬 유사 업무 2건), `concepts/브랜업-법인행정-재무-라인.md`(**§12 신설** + 기존 §12→§13 재번호 — #628 결론 완료·#680 업종전환 업무화·#681 정책자금·#686 보안 축·상표권 페이지 연결·세무법인 81일), `concepts/칸겐보떼-아세안-규제-신고-자료.md`(**§2026-11-12** — 원료 단종·TRA QQ 종결·#688 검사 파급·23~25개국 확대), `concepts/kangen-문안-이력-2026-11.md`(**§23 신설** — 밍크오일→스쿠알란·토코페롤 제외·삽지 인쇄물), **`concepts/브랜업-상표권-리스크.md`(신규)**, `concepts/tsonax.md`(연혁 11-12 + 11-11 지연율 정정), `projects/에나지크_발주_시뮬레이터.md`(11-12 항목), `projects/브랜업_대시보드_개발.md`(11-12 항목 — **개발 백로그 5번째: 지연율 산식/`due_at` 정규화**) + `README.md`(재생성) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261112.json` · `branup_completed_20261112.json` · `branup_snapshot_20261112_projects.json` · 신규 raw `raw/articles/slack-design-backup-20261111-insert-design.md`
- **미조치(신규)**: ① **15ml 박스 발주파일 인쇄 전 전성분 확정본 확보** — 원료 변경(밍크오일→스쿠알란) 확정, #650이 이미 전송됨 ② **`#688` 답변 대기** — 안전성검사 재수행 여부가 KCL 12-31 일정을 좌우 ③ **`#682` 23 vs 25개국 확정** ④ **삽지 지시 확정 3건**(벨벳코팅 채택·삽지 수록 문안 범위·50ml 제형 이미지 축소 비율) ⑤ **업종전환 시점 결정**(#680 마감 없음 — 연내 시한인데 추적 불가) ⑥ **11-13 22건** — 단일 날짜 최다, 경과 30건대 재진입 위험 ⑦ **상표권 자문 회신** 확인
- **미조치(지속)**: **쇼핑백 1만개 발주서(#536) 복원·재등록 여부**(11-10 삭제 후 기록 없음, 12월 양산 리스크) · `50ml 전면 문안` 기준 문서 0건 · 완료 4건(쇼핑백 2차·세트박스 문안·저알레르기·3ea) 산출물 0건 · `[세무] 세무법인 결정` **81일째 미결** · 아세안 4개국 **20일째 업무 0건** · `코스매틱-진행` vs `00코스매틱-진행` 중복 정리(**8일째**) · 봇 초대 4개 채널(**8일째**) · 프로젝트 12/13 보류(진행중 0) · `kangen-뷰티-문안-바코드-표준` **285줄**(200줄 초과 — 분할 검토)
- 파일 변경: `channels/branup-design-backup.md`, `channels/index.md`, `index.md`, `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/kangen-문안-이력-2026-11.md`, `concepts/브랜업-상표권-리스크.md`(신규), `concepts/tsonax.md`, `projects/에나지크_발주_시뮬레이터.md`, `projects/브랜업_대시보드_개발.md`, `raw/articles/slack-design-backup-20261111-insert-design.md`(신규), `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`)

## [2026-11-13] sync | 브랜업 대시보드 동기화
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
- 프로젝트 13개, 업무 95건 동기화 완료


## [2026-11-13] daily | 11-12 = **완료 5 + 하드 삭제 6(전건 이향석·마감 없음)** — 경과 29→**28**, **TSonaX 대시보드 활성 0건** / 신규 12건 중 **미스트 포장 라인 9건**

- **동기화:** `branup_db_wiki_sync.py` → 프로젝트 **13개** · 업무 **95건**(전일 94 → **+1**) · **17개 파일** 갱신(`projects/*.md` 13, `projects/index.md`, `concepts/브랜업-대시보드-현황.md` 등)
- **Slack:** `conversations.list` **18개**(전일 동일) · 비아카이브 전량 `conversations.history`(시간필터 없이 `limit:80` 후 스크립트 내 비교, **curl 기반**) → **업무 메시지 0건 / 신규 파일 0건**. **26시간 창 0건** — 11-12(목) 하루 Slack 대화 전무. 168시간 누적 **11건**은 전량 기수록분(`design-backup` 10 · `wiki` 1). 업무 대화 최신 = `design-backup` **11-11 19:01**(삽지 디자인) → **2일째 무변동**
- **북마크·Canvas:** `slack_bookmark_scanner.py --all` → 채널 15개 · 북마크 **0건** · **Canvas 이벤트 19건(신규 0건**, 최신 `design-backup` 11-09 19:06) · errors 2(`제품-기획-제작`)
- **채널:** rename 0 · 신규 채널 0 · **채널 페이지 신규 생성 0건** · ID 매핑 **18/18**(페이지 보유 11/11, `channels/브랜업-공지사항`은 `(unknown)` 유지 — Slack 실체 없음) · **errors 4**(`제품-기획-제작` C0BL3S0BHV3 · `브랜업-멤버십-슬랙-소통-채널` C0CDVR5CHT7 · `코스매틱-진행` C0CG9DAJS9E · `00코스매틱-진행` C0CF9P6FUTX — 전부 `not_in_channel`, **9일째 봇 초대 대기**)
- ✅ **11-12 완료 5건**: `#686 [보안] 서버 해킹 및 외부 공격가능한 부분 조사 및 대처`(**08:31**, due 11-11 → 1일 지연) · `#687 [브랜업] K-뷰티론 정부지원사업 검토`(09:48, **1일 조기**) · `#693 중진공 정책 지원금 정부지원사업 검토`(09:49, **정시**) · `#653 [아이젤] 신규원료 1% 함량 처방 의뢰 및 회신`(10:01, **18일 조기**) · `#692 김동규 이사(종이비누)님과 통화`(11:09, 정시). 완료 이력 **448 → 453(+5)** — 11-10 13건·11-11 11건에서 **3일 연속 감소**
- 🔴 **하드 삭제 6건 — 전건 이향석·전건 `due_at` 없음.** 완료 이력 453건에 **id·제목 모두 0 hit**: `#32 신우·태평양 월별 자문계획 수립`(05-21 등록) · **`#201 [TSonaX] 대표님 지표추가(차트포함)`**(08-21) · `#419 [기술조사] 구글시트 발주 스케줄관리 모니터링 챗봇`(09-15) · `#427 에나지크↔OEM사 대금 결제 주기 상생방법`(09-18) · **`#431 [Toffer] 익절/손절 시나리오 개선`**(09-15) · `#460 [OTC] 미국 선크림 인증 절차 조사`(10-03). 삭제 사유 불명(보류 결정·통합·실수 구분 불가) — **감사 추적 0건**. 하드 삭제 **누적 70건**(11-01 7 · 11-06 22 · 11-09 34 · 11-10 1 · **11-12 6**)
- 🔴 **가장 큰 파급: `TSonaX`/`Toffer` 대시보드 활성 업무 0건.** #431·#201이 **완료가 아니라 삭제**됨 → **22일간 추적한 "마감 없는 진행중" 카운터 소멸**, 이제 **진척 판단 근거는 git 커밋뿐**
- 🆕 **신규 12건 전건 11-12 생성 — 9건이 `20ml 미스트 공병` 포장 라인**: 노수민 4(`#694 감리 색상 준비`·`#695 미스트용기 두코`·`#696 미스트 용기 단상자 준비`·`#697 개별 제품 단상자 준비`) · 전경표 4(`#700 [칸겐뷰트 RA] 20ml 공병 미스트 단상자 표시사항 리서치`·`#701 [칸겐뷰트] 20mL 공병 미스트 샘플 발송`·`#703`·`#704 클로브 AI 점심/저녁 지출 트래킹`) · 강경철 4(`#698 미스트 빈용기 수출 특이사항 리서치`·`#702 홍이사님께 미스트 단상자+인박스+카톤 방식 문의`·`#705 카톤 발주서 전달(지원)`·`#699 미스트+단상자 포장처 수배`). **11-11 `#656 [두코] 미스트 용기 의뢰·컨펌` 완료 직후** 이어지는 흐름 → **신규 페이지 `concepts/칸겐뷰티-미스트-용기-라인`**
- 🔑 **4항 브리지 검산 오차 0:** `어제 스냅샷 as-of 오늘 29 − 해소 3 − 연장(경과이탈) 4 + 신규 즉시경과 6 = 28` | 실측 **28**. **해소 3 = 제거된 경과분 중 완료분(#686·#692·#693)** — **삭제 6건은 마감이 없어 경과 집계에 없었으므로 해소 항에 잡히지 않는다**(이 구분 없이 `29−11−4+6=20`으로 계산하면 8건 오차. 스크립트 초기 산식이 실제로 이 오류를 냈고 **수동 재계산으로 정정**)
- 🔑 **연장 4건**: `#554`(11-11→11-13) · `#679`(11-12→11-13) · `#688`(**이틀 연속 연기**) · `#362`(**11-11→11-20, 9일**) / **경과 내 이동 1건**: `#677`(11-11→11-12, **3번째 연기** — summary `신우 답변 대기 11/10 → 11/11 답변 아직안옴 → 11/12`). 신규 즉시경과 **6건**(#694·#695·#700·#701·#703·#704) = 등록 당일 마감
- 🔴 **`#681 [중진청] 정책자금 신청` summary 갱신(11-12 10:08)** — 전경표 중진공 문의 결과: **상시근로자 5명 이상으로 지원대상 해당** · 관할 **서울서부지부** · **2026년 예산 전부 소진, 일반 정책자금은 2027년 1월 정기접수**. → 11-11 `#628`(신용보증기금 예산 소진 → 2027년 초)와 **같은 구조**로, **신보·중진공 두 경로 모두 2026년 조달 불가** 확정. 남은 경로는 ① 서울신보 일반상품(매출 1억 요건) ② 2027-01 정기접수 ③ 업종전환 후 창업자금 1회
- **통계(as-of 11-13 05:00 KST):** 마감 경과 **28건(−1)** · **60일 이상 15건(54%)** · `due_at` 미입력 **8건** · 담당자 공백 **5건** · `project_id` 미지정 **94/95(99%)** · 진행중 94 · 지연 1 · 프로젝트 **보류 12 · 완료 1 · 진행중 0**(21일째) · 담당자별 경과 **김봉재 9 · 전경표 7 · 노수민 5 · 강경철 2 · 이향석 2 · 최유미 2 · 이상원 1** · 최장 `nfc 명함 업체 컨택 후 발주` **139일**(노수민) · 누적 지연완료 **221/445 = 49.7%**(날짜 단위 비교)
- 📌 **11-13 D-0 27건(단일 날짜 최다)** — 전일 예고 22건 + 신규 5건(#698·#702·#705 + #688·#679 연장). ⚠️ 28건 위에 27건이 겹쳐 **11-14 경과 40건대 진입 가능**. D-2 3건(11-15) · D-3 2건(11-16)
- **TSonaX:** 대시보드 활성 **0건**(2건 삭제) · 개발 브랜치 `feat/minichart-tf-series-reconnect` **신규 커밋 0건(30일째)** — tip `c6041cd`(2026-10-14 12:47) · master `e42d7c9`(09-02) 무변동(`git ls-remote origin` 11-13 실측)
- **한국어 위키 갱신 14건**: **`concepts/칸겐뷰티-미스트-용기-라인.md`(신규)** · `concepts/브랜업-업무-완료-판별.md`(**§18** — 11-12 판별표·4항 검산·해소 항 정의·TSonaX 앵커 상실) · `concepts/브랜업-대시보드-입력-품질.md`(**§13** — 미스트 라인 9건·당일 마감 3건 다섯째 날·`[칸겐뷰트]` 오타·#694 식별 불가) · `concepts/브랜업-법인행정-재무-라인.md`(**§13** — #681 중진공 예산소진·#686 보안 종결·#362 82일째·삭제 6건) · `concepts/칸겐보떼-아세안-규제-신고-자료.md`(**§2026-11-13** — 태국 D-0·#688 이틀 연기·4개국 21일째 0건·#700 미스트 표시사항) · `concepts/kangen-문안-이력-2026-11.md`(**§24** — 11-13 문안 4건 동시 D-0·#640 확정본) · `concepts/브랜업-상표권-리스크.md`(3번째 연기·신우 답변 3일째) · `concepts/tsonax.md`(헤더·연혁 11-13·활성 0건·표 갱신) · `projects/kcl_sgs_안정성검사_사업_실행_12_31.md` · `projects/에나지크_발주_시뮬레이터.md` · `projects/브랜업_대시보드_개발.md` · `projects/시니어_마케터_채용_프로젝트.md` · `projects/칸겐뷰티_sns_운영.md` · `channels/index.md` + `index.md`(헤더 68페이지·신규 등재·요약 8개 라인) + `README.md`(재생성) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`) + 스냅샷 `~/.hermes/cache/scratch/branup_snapshot_20261113.json` · `branup_completed_20261113.json` · `branup_snapshot_20261113_projects.json`
- **미조치(신규)**: ① **TSonaX 대시보드 업무 재등록 여부 결정** — 2건이 기록 없이 삭제됨(코드 30일 정지) ② **`#640` 문안 확정본**(11-13) — 15ml 발주파일 인쇄 전 마지막 지점 ③ **`#688` 아이젤 회신**(이틀 연속 연기) — 안전성검사 재수행 여부가 KCL 12-31 일정 좌우 ④ **11-13 D-0 27건** 처리 여부 ⑤ **미스트 라인 거래처·수량·제품명** 확인(두코·홍이사) ⑥ **`#681` 2027-01 정기접수 대기 등록** — 2026년 경과 집계 사각지대 ⑦ **`#680`(마감 없음)·`#378` 등이 삭제 경로로 소멸할 위험** — 마감 부여 필요
- **미조치(지속)**: **쇼핑백 1만개 발주서(#536) 복원·재등록**(11-10 삭제 후 3일째 기록 없음) · `50ml 전면 문안` 기준 문서 0건 · `[세무] 세무법인 결정` **82일째 미결**(11-20 연장) · 아세안 4개국 **21일째 업무 0건** · `코스매틱-진행` vs `00코스매틱-진행` 중복 정리(**9일째**) · 봇 초대 4개 채널(**9일째**) · 프로젝트 12/13 보류(진행중 0) · 하드 삭제 70건 감사 추적 불가(soft delete 백로그)
- 파일 변경: `concepts/칸겐뷰티-미스트-용기-라인.md`(신규), `concepts/브랜업-업무-완료-판별.md`, `concepts/브랜업-대시보드-입력-품질.md`, `concepts/브랜업-법인행정-재무-라인.md`, `concepts/칸겐보떼-아세안-규제-신고-자료.md`, `concepts/kangen-문안-이력-2026-11.md`, `concepts/브랜업-상표권-리스크.md`, `concepts/tsonax.md`, `projects/kcl_sgs_안정성검사_사업_실행_12_31.md`, `projects/에나지크_발주_시뮬레이터.md`, `projects/브랜업_대시보드_개발.md`, `projects/시니어_마케터_채용_프로젝트.md`, `projects/칸겐뷰티_sns_운영.md`, `channels/index.md`, `index.md`, `README.md`, `log.md`(본 엔트리) + DB sync 자동 갱신분(`projects/*.md` 13건, `projects/index.md`, `concepts/브랜업-대시보드-현황.md`)

## [2026-11-13] lint | 주간 위키 린트(54주차) — broken 0 · 고아 6 · 미등재 7 · 태그위반 2 · stale 14

- **범위:** `~/wiki` 전체 — 콘텐츠 페이지 **68**(channels 11 · entities 18 · concepts 26 · projects 13, `channels/index`·`projects/index` 내비 파일 제외) · raw 원본 **58 md** · log 엔트리 **211**
- **broken wikilink 0건**(콘텐츠 페이지 기준, NFC 정규화·alias 선분리·raw 네임스페이스 등록 후 측정) · **ghost page 0건** · **frontmatter 결손 0건**
- **log.md 이력 문장 내 미해결 링크 3건** — `branup-work-dashboard` · `channels/브랜업-전체` · `통합주간전략 자동화`. 과거 린트가 "고친 링크"를 인용한 문장이라 **조치 대상 아님**(콘텐츠 결함 0건과 분리 집계)
- **고아 6건**(inbound 0, index 포함): `entities/project-ai_ax_직원_교육` · `entities/project-브랜업_대시보드_개발` · `entities/project-소라살롱_공구_프로젝트` · `entities/project-시니어_마케터_채용_프로젝트` · `entities/project-에나지크_발주_시뮬레이터` · `concepts/task-status` — **9월 18일 린트 이후 8주째 동일**, `_archive/` 이동 사용자 승인 대기
- **index 미등재 7건** — 위 6건 + `concepts/project-status`(타 페이지 유입 링크 있음 → 고아 아님) — 변동 없음
- **index 헤더 정합:** `Total pages: 68 (channels 11 · entities 18 · concepts 26 · projects 13)` = 실측 68 **일치**. 오늘 신설 `concepts/칸겐뷰티-미스트-용기-라인` 등재 확인
- **태그 위반 2종** — ① `brand`(`concepts/브랜업-상표권-리스크`, 11-12 신설) → **SCHEMA Business 항목에 등재 완료(자동 수정)** ② `task`(`concepts/task-status`) → 아카이브 대기 페이지 전용이라 미등재 유지(기존 방침)
- **stale(90일+) 11 → 14건**(+3): `concepts/task-status`·`concepts/project-status`(updated 2026-07-28, 108일) · `channels/브랜업-온보딩`(07-30, 106일). 최장은 `concepts/slack-adoption`(07-14, 122일). 전건 7월 이후 본문 무변동 — 시간 경과에 따른 자연 증가이며 새 결함은 아님
- **oversized(>200줄) 11건** — `entities/브랜업-신입직원-온보딩-매뉴얼` **802줄**(6주 연속 분할 권고) · `concepts/브랜업-업무-완료-판별` **378** · `concepts/브랜업-법인행정-재무-라인` **305** · `channels/코스메틱-본부` 288 · `concepts/kangen-뷰티-문안-바코드-표준` 286 · `entities/enagic-usa` 256 · `channels/branup-design-backup` 251 · `concepts/kangen-문안-이력-2026-11` 247 · `concepts/브랜업-대시보드-입력-품질` 232 · `concepts/칸겐보떼-아세안-규제-신고-자료` 223 · `concepts/에나지크-글로벌-물류-패키징-전략` 205. **일일 크론이 매일 §섹션을 덧붙이는 4개 페이지(업무-완료-판별·법인행정·입력-품질·아세안)는 분할 없이는 계속 증가** — 11-11에 문안 표준(466→285)을 분할한 것과 같은 조치가 필요
- **raw sha256** — 정상 **15** · 불일치 **15** · `source_file` 바이너리 해시 **4** · placeholder **18** · 필드 없음 **6**. 불일치 15건은 전건 `git log --oneline` **단일 ingest 커밋** = **본문 무편집, ingest 시점 해시 산출 규칙 불일치**(소스 변경 아님). placeholder 18건(`slack-advisory` 등)은 drift 검출 자체 불가
- **채널 ID 매핑 10/11** — `channels/브랜업-공지사항` `(unknown)` 유지(Slack 실체 없음). `slack_channel_id` 전건 실측 일치 확인
- **품질 신호** — `contested: true` **0건** · `confidence: low` **2건**(`concepts/branup-finance`·`entities/정육공방`)
- **log 로테이션** — log.md **211 엔트리**(기준 500 미만, 불필요). `log-2026.md` 663줄 보관 중
- **파일 변경:** `SCHEMA.md`(`brand` 등재 + 린트 노트 1행), `index.md`(미등재 섹션에 2026-11-13 주간 린트 노트), `log.md`(본 엔트리)
- **미조치(사용자 판단 필요):** ① 고아 7건 `_archive/` 이동 승인 ② `entities/브랜업-신입직원-온보딩-매뉴얼`(802줄) 분할 승인 ③ 일일 크론 누적 페이지 4건 분할 정책 ④ placeholder sha256 18건 백필 여부
