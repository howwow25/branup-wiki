# 📚 브랜업 위키 (Branup Wiki)

> 브랜업(주)의 업무 지식베이스 — Hermes AI 에이전트가 Karpathy LLM Wiki 패턴으로 운영합니다.
> Obsidian Vault 호환. Slack/Telegram 게이트웨이 연동.

---

## 📋 페이지 목록

### 📌 엔터티 (Entities)
- **[아이젤 제조위탁계약](entities/aizel-contract.md)** — 브랜업 vs 아이젤 조항별 상세 비교, NDA, 계약검토 포함
- **[아이젤 계약검토 요청서](entities/aizel-contract-review-request.md)** — 신우 외부 검토 의뢰, 7대 목표·8대 쟁점·NDA 분석
- **[브랜업 조직도](entities/branup-org-chart.md)** — 주요 인물·부서·협력사
- **[Enagic USA](entities/enagic-usa.md)** — 북미 유통 파트너 (에나지크)

### 📌 개념 (Concepts)
- **[아이젤 미팅 회의록](concepts/aizel-meeting-2026-07-14.md)** — 부자재 검수, 신규 포트폴리오, 물량 전망
- **[아이젤 신규 라인업 제안서](concepts/aizel-proposal-lineup-2026-07-14.md)** — 아이젤 제안 10종 신규 제품군
- **[통합주간전략 자동화](concepts/integrated-weekly-strategy.md)** — AI 기반 주간 업무 자동 취합 구상
- **[Slack 도입 및 내재화](concepts/slack-adoption.md)** — 브랜업 Slack 전환 과정, 과제
- **[정부지원사업 모니터링](concepts/government-support-programs.md)** — 수출바우처·지원사업 모니터링
- **[수출바우처](concepts/export-voucher.md)** — 중진공 수출바우처 제도 상세
- **[PL보험](concepts/product-liability-insurance.md)** — 미국 수출 PL보험 현황 및 쟁점
- **[브랜업 재무현황](concepts/branup-finance.md)** — 재무 상태 및 리스크 요인
- **[TSonaX](concepts/tsonax.md)** — 실시간 차트 분석 시스템

---

## 🤖 업데이트 방식
- **표준 구조:** Karpathy LLM Wiki 3-Layer (raw/ → entities+concepts+comparisons+queries → _archive/)
- **워크플로우:** Hermes가 Slack/Telegram 대화를 감지 → 위키 자동 업데이트
- **매일 새벽 5시 (KST)** — Slack 채널 대화 요약 → raw/ 저장 + 위키 페이지 업데이트
- **주간 금요일 18:00** — 위키 lint (고아 페이지, 깨진 링크, 만료 콘텐츠 점검)
- **GitHub** — 모든 변경사항 자동 push

---

*최종 업데이트: 2026-07-15 | 총 14페이지 (리빌드 완료)*
