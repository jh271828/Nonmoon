---
title: "학습 상태 — 러너 진입점"
updated: 2026-08-23
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
1. Contact는 device terminal/silicide와 Metal 1 사이의 vertical connection이라는 표현을 다음 복습에서 재확인
2. Well formation을 channel 자체 형성보다 NMOS/PMOS가 형성될 body region 형성으로 표현하는 정확성 보완
3. CMOS Process Flow에서 Metal의 역할은 아직 스스로 설명하지 않음
4. implant species 선택을 단순히 charge가 아니라 확산성·질량·junction 형성 등 물리적 성질과 연결하는 설명은 다음 학습에서 검증 필요
5. 슬라이드 11에서 기존 oxide를 그대로 쓰지 않고 새 oxide를 형성하는 이유는 다음 학습에서 다시 검증 필요

## 다음 복습 질문 (top 5 — 세션 시작 시 1~2개 예측용)
> 다음 세션에서 다시 물을 것. 러너가 채워 나간다.
1. Contact와 Metal은 각각 어떤 방향/범위의 electrical connection을 담당하는가?
2. Well formation은 channel 자체를 만드는 것인가, NMOS/PMOS가 형성될 body region을 만드는 것인가?

## 최근 궤적 (러너가 갱신)

- 2026-08-18 · EE463 Introduction과 Scaling → [daily/2026-08-18-ee463-introduction-scaling.md](daily/2026-08-18-ee463-introduction-scaling.md)
- 2026-08-19 · EE463 Introduction 진행상황 반영 → [daily/2026-08-19-ee463-introduction.md](daily/2026-08-19-ee463-introduction.md)
- 2026-08-19 · EE463 Introduction 진행상황 갱신 → [daily/2026-08-19-ee463-introduction-2.md](daily/2026-08-19-ee463-introduction-2.md)
- 2026-08-19 · EE463 Process Technology Issues → [daily/2026-08-19-ee463-process-technology-issues.md](daily/2026-08-19-ee463-process-technology-issues.md)
- 2026-08-20 · EE463 Introduction — Atomic Scale Era와 Scaling 한계 → [daily/2026-08-20-ee463-introduction-atomic-scale-era-scaling-2.md](daily/2026-08-20-ee463-introduction-atomic-scale-era-scaling-2.md)
- 2026-08-23 · CMOS 공정 흐름 — 이전 두 세션 통합 → [daily/2026-08-23-cmos.md](daily/2026-08-23-cmos.md)
- 2026-08-23 · CMOS Process Flow — 전체 흐름 검증 → [daily/2026-08-23-cmos-2.md](daily/2026-08-23-cmos-2.md)

## 세션 진행 프로토콜 (러너가 따르는 대본)
**① 목표 → ② 예측(내가 먼저 자기 말로) → ③ 설명·교정(오개념을 근거와 함께) → ④ 퀴즈/적용 → ⑤ 채점·기록.**
떠먹여주지 않는다. 내가 먼저 설명하게 하고, 약한 고리를 근거와 함께 짚는다.

## 쓰기 계약 (세션 종료 시 러너가 하는 일)
1. `daily/YYYY-MM-DD-<주제>.md` 생성 — `templates/session-card.md` 형식, **정규 헤딩 준수**(`## 오늘 직접 학습한 지식` / `## 취약 영역` / `## 다음 복습 질문`).
2. 이해 승급이 있으면 `mastery.md`에 한 줄 append — `설명가능`은 **반박 통과 + 증거(오늘 daily 링크)** 있을 때만.
3. **이 STATUS.md 갱신** — 작게: 오늘 목표·top5 약점·top5 복습·최근 궤적 한 줄. (전체는 mastery/daily에, 여기엔 초점만.)
