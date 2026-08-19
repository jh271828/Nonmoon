---
title: "EE463 Process Technology Issues"
created: 2026-08-19
updated: 2026-08-19
tags: [learning]
source: "학습 세션 → Issue #36 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: ChatGPT
source_issue: 36
---

# EE463 Process Technology Issues

## 오늘 직접 학습한 지식

구경 대비 높이 비율?

etching공정이 정교하지 못하면, overetching(입구를 너무 과도하게 파버림)나 underetching(바닥을 덜 파버림)이 일어나지 않을까

capacitor일듯

capacitor에 전하를 저장하므로써 정보를 저장하기 때문이며, 시간이 지날수록 cap의 전하는 자연방전되기 때문에 dram은 주기적으로 refresh를 해줘야 될 것 같아. 이때, C가 충분히 확보되어야 time constant가 커져서 비교적 덜 빨리 방전되겠지?

dram은 C랑 MOSFET이 서로 분리된 구조라서 스위칭 속도가 빠르다는 장점이 있고, NAND는 floating gate를 통해 Capacitor와 MOSFET이 붙어 있게 되어 동작속도는 느리지만 집적도는 훨씬 높아 저장용량에 장점을 가지는 구조이기 때문에?

dram은 면적은 줄지만, C는 어느정도수준을 유지해야 되기 때문에 C를 길게 만들면서 구조가 높아졌고, 3d nand는 memory cell 자체를 쌓아서 만드는 구조라서 애초에 구조가 높아져.

## 취약 영역

- High aspect ratio etching의 핵심 난점을 overetch/underetch뿐 아니라 깊은 구조에서 etching species 전달, reaction product 배출, 수직 profile 제어와 연결할 필요
- DRAM retention을 단순 RC time constant로만 설명하지 않고 저장 전하 Q=CV, leakage, sense margin 관점으로 연결할 필요
- 3D NAND를 모두 floating-gate 구조로 일반화하면 안 됨. charge-trap 방식도 존재
- Slide 15 Atomic Scale Era에서 feature size가 원자 수십 개 수준이 될 때 원자 몇 개의 공정 오차가 상대적으로 커지는 이유는 아직 학습자가 설명하지 않음

## 다음 복습 질문

- High aspect ratio 구조에서 aspect ratio는 어떤 치수들의 비인가?
- High aspect ratio가 커질수록 etching과 deposition은 왜 어려워지는가?
- DRAM scaling에서 capacitor의 면적이 줄어도 capacitance를 충분히 확보해야 하는 이유는 무엇인가?
- DRAM retention time을 단순한 RC 자연방전으로만 설명하면 무엇이 빠지는가?
- feature size가 원자 몇십 개 수준까지 내려오면 왜 원자 몇 개의 공정 오차가 중요해지는가?

## Parking Lot 추가

- High aspect ratio etching의 species transport와 reaction product removal · blocker: no
- DRAM retention의 leakage path와 sense margin · blocker: no

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
