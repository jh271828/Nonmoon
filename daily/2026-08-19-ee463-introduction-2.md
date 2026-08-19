---
title: "EE463 Introduction 진행상황 갱신"
created: 2026-08-19
updated: 2026-08-19
tags: [learning]
source: "학습 세션 → Issue #35 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: ChatGPT
source_issue: 35
---

# EE463 Introduction 진행상황 갱신

> ⚠️ 서버 경고: 정제본·READING_STATUS 갱신은 논문 모드에서만 반영된다. 이 절은 세션 노트에만 남는다.

## 오늘 직접 학습한 지식

구경 대비 높이 비율?

etching공정이 정교하지 못하면, overetching(입구를 너무 과도하게 파버림)나 underetching(바닥을 덜 파버림)이 일어나지 않을까

capacitor일듯

capacitor에 전하를 저장하므로써 정보를 저장하기 때문이며, 시간이 지날수록 cap의 전하는 자연방전되기 때문에 dram은 주기적으로 refresh를 해줘야 될 것 같아. 이때, C가 충분히 확보되어야 time constant가 커져서 비교적 덜 빨리 방전되겠지?

dram은 C랑 MOSFET이 서로 분리된 구조라서 스위칭 속도가 빠르다는 장점이 있고, NAND는 floating gate를 통해 Capacitor와 MOSFET이 붙어 있게 되어 동작속도는 느리지만 집적도는 훨씬 높아 저장용량에 장점을 가지는 구조이기 때문에?

## 취약 영역

- High aspect ratio etching의 핵심 난점을 overetch/underetch뿐 아니라 깊은 구조에서 etching species 전달, reaction product 배출, 수직 profile 제어와 연결할 필요
- DRAM retention을 단순 RC time constant로만 설명하지 않고 저장 전하 Q=CV, leakage, sense margin 관점으로 연결할 필요
- 3D NAND를 모두 floating-gate 구조로 일반화하면 안 됨. charge-trap 방식도 존재
- DRAM과 3D NAND가 high aspect ratio 구조를 택한 서로 다른 이유를 아직 자기 말로 다시 설명하고 반박을 통과하지 않음

## 다음 복습 질문

- High aspect ratio 구조에서 aspect ratio는 어떤 치수들의 비인가?
- 3D NAND의 적층 수가 증가할수록 etching과 deposition이 왜 어려워지는가?
- DRAM scaling에서 capacitor의 면적이 줄어도 capacitance를 충분히 확보해야 하는 이유는 무엇인가?
- DRAM retention time을 단순한 RC 자연방전으로만 설명하면 무엇이 빠지는가?
- DRAM과 3D NAND는 각각 왜 high aspect ratio 구조가 필요해졌는가?

## 논문 읽기 상태 초안 (반영되지 않음)

### Progress

EE463 1 Introduction: Slide 14 Process Technology Issues까지 진행. 3D NAND, DRAM, Logic scaling에서 high aspect ratio와 공정 난도가 증가한다는 내용을 학습 중.

### Current Understanding

High aspect ratio를 구경 대비 높이/깊이의 비율로 인식함. High-AR 구조가 etching과 thin-film deposition 난도를 높인다는 연결을 확인함. DRAM은 cell 면적 scaling에도 capacitance와 저장 전하를 확보해야 하므로 capacitor가 높고 가늘어지고, 3D NAND는 수직 적층으로 bit density를 높이면서 high-AR 구조가 된다는 차이를 교정 중. DRAM retention을 RC 자연방전만으로 보는 설명과 3D NAND를 floating-gate로 일반화하는 부분은 추가 교정이 필요함.

### Next Session

Slide 14에서 DRAM과 3D NAND가 각각 왜 high aspect ratio 구조가 필요한지 학습자가 자기 말로 다시 설명하는 것부터 재개한 뒤 Slide 15로 진행.

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
