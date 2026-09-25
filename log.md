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
