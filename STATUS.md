---
title: "학습 상태 — 러너 진입점"
updated: 2026-08-29
kind: status
---

# 🎯 학습 상태 (Runner Entrypoint)

> **"오늘 세션 시작"을 누르면 러너(Custom GPT)가 가장 먼저 읽는 한 파일.**
> 여기서 현재 위치를 잡고 시작한다 — 전체를 스캔하지 않는다.
> **작게 유지한다** — 전체 목록(약점·복습·개념)은 `mastery.md`·`daily/`에 두고, 여기엔 **지금 초점만**.
> 세션이 끝나면 러너가 이 파일을 갱신한다(아래 §쓰기 계약).

<!-- 처음 시작할 때: 아래 <...> 를 내 목표로 바꾸면 된다. 러너에게 "새 목표 세우기"라고 해도 된다. -->

## 지금 활성 트랙

| 트랙 | 목표 (끝나면 무엇을 스스로 설명/수행할 수 있나) | 모드 |
|---|---|---|
| **<트랙 이름 — 예: "딥러닝 복원" / "SSL 랩 컨택 준비">** | <목표 한 줄> | <진도 / 복원 / 논문> |

> 📌 **정해진 날짜(시험 등)가 있으면만** 여기 적는다. 없으면 비워 둔다 —
> 이 시스템은 일정표가 아니라 **오늘 15~60분**을 굴리는 도구다.

> **모드**: `진도`(지금 듣는 과목 — 주차·시험 기준) · `복원`(들었는데 기억 안 나는 과목 — 스캔부터) · `논문`(논문·랩·교수)

## 🎯 오늘 할 것 (이게 주인공이다 — 15~60분)

- HBM 본문을 읽다가 필요한 시점에 패키징 기초를 꺼내 학습한다.

## 지금 약한 것 (top 5 — 세션은 여기서 시작)
> 전체는 [[mastery.md]]. 아직 `설명가능`이 아닌 것부터.
1. Class X 정의에서 처음에는 0.5 μm 미만이라고 답했으나, 원문상 0.5 μm보다 큰 particle 개수 기준으로 교정함.
2. Organic contamination 제거를 산-염기/산화환원으로 넓게 표현했으나, 핵심은 O2 plasma 또는 H2SO4/H2O2의 강한 산화 조건으로 분해하는 것.
3. Page 4의 generation lifetime 식과 DRAM refresh 특성 연결은 설명을 듣고 이해했으나 스스로 완전한 설명은 아직 검증하지 않음.
4. Organic contamination 제거의 핵심은 산-염기 반응보다는 강한 산화 조건에서 유기물을 분해하는 것.
5. RCA clean 전위표는 렉노가 oxidation potential을 사용하므로 일반적인 reduction potential과 부호 방향을 혼동하지 않기.

## 다음 복습 질문 (top 5 — 세션 시작 시 1~2개 예측용)
> 다음 세션에서 다시 물을 것. 러너가 채워 나간다.
1. Class X의 X는 정확히 무엇을 의미하는가?
2. Clean room, wafer cleaning, human control의 역할 차이를 각각 설명하라.
3. Particle, organic, metal contamination은 각각 어떤 방식으로 제거되는가?
4. RCA clean에서 H2O2가 metal contamination을 제거하는 과정을 전자 이동부터 solution 용해까지 설명하라.
5. Au, Cu, Fe 같은 deep-level impurity가 DRAM refresh 특성에 왜 악영향을 주는가?

## 최근 궤적 (러너가 갱신)

- 2026-08-19 · EE463 Process Technology Issues → [daily/2026-08-19-ee463-process-technology-issues.md](daily/2026-08-19-ee463-process-technology-issues.md)
- 2026-08-20 · EE463 Introduction — Atomic Scale Era와 Scaling 한계 → [daily/2026-08-20-ee463-introduction-atomic-scale-era-scaling-2.md](daily/2026-08-20-ee463-introduction-atomic-scale-era-scaling-2.md)
- 2026-08-23 · CMOS 공정 흐름 — 이전 두 세션 통합 → [daily/2026-08-23-cmos.md](daily/2026-08-23-cmos.md)
- 2026-08-23 · CMOS Process Flow — 전체 흐름 검증 → [daily/2026-08-23-cmos-2.md](daily/2026-08-23-cmos-2.md)
- 2026-08-23 · EE463 Wafer → [daily/2026-08-23-cmos-3.md](daily/2026-08-23-cmos-3.md)
- 2026-08-29 · EE463 Cleaning contamination control → [daily/2026-08-29-ee463-cleaning-contamination-control.md](daily/2026-08-29-ee463-cleaning-contamination-control.md)
- 2026-08-29 · EE463 Cleaning — contamination control과 wafer cleaning → [daily/2026-08-29-ee463-cleaning-contamination-control-wafer-cleaning-3.md](daily/2026-08-29-ee463-cleaning-contamination-control-wafer-cleaning-3.md)

## 세션 진행 프로토콜 (러너가 따르는 대본)
**① 목표 → ② 예측(내가 먼저 자기 말로) → ③ 설명·교정(오개념을 근거와 함께) → ④ 퀴즈/적용 → ⑤ 채점·기록.**
떠먹여주지 않는다. 내가 먼저 설명하게 하고, 약한 고리를 근거와 함께 짚는다.

## 쓰기 계약 (세션 종료 시 러너가 하는 일)
1. `daily/YYYY-MM-DD-<주제>.md` 생성 — `templates/session-card.md` 형식, **정규 헤딩 준수**(`## 오늘 직접 학습한 지식` / `## 취약 영역` / `## 다음 복습 질문`).
2. 이해 승급이 있으면 `mastery.md`에 한 줄 append — `설명가능`은 **반박 통과 + 증거(오늘 daily 링크)** 있을 때만.
3. **이 STATUS.md 갱신** — 작게: 오늘 목표·top5 약점·top5 복습·최근 궤적 한 줄. (전체는 mastery/daily에, 여기엔 초점만.)
