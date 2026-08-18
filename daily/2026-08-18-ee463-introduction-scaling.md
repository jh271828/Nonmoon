---
title: "EE463 Introduction과 Scaling"
created: 2026-08-18
updated: 2026-08-18
tags: [learning]
source: "학습 세션 → Issue #31 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: ChatGPT
source_issue: 31
---

# EE463 Introduction과 Scaling

> ⚠️ 서버 경고: 정제본·READING_STATUS 갱신은 논문 모드에서만 반영된다. 이 절은 세션 노트에만 남는다.

## 오늘 직접 학습한 지식

scailing factor를 줄이면, mosfet구조에서의 channel length나 width가 감소해서, V라던지 Drain 농도등이 변화하고, 이에 따라서 power도 감소하고, 비용도 감소하고, 정보를 전달하는 속도는 증가하고, 부피도 감소해서 집적도도 늘고, cutoff frequency도 증가하는 걸로 알고있어.

source에서 drain까지 거리가 곧 channel length이고, 이 거리가 짧아진다는 것은 캐리어가 더빠르게 drain에 도착한다는 얘기. 따라서 스위칭이 빨라진다.

같은 wafer의 크기에 더 많은 transistor를 만들수 있기 때문에, transistor의 개당 생산비용이 감소한다. 덧붙혀 말하면, transistor의 제작 비용 대부분은 wafer비용이다.

용어 그대로의 설명은 알고있으니까 설명안해도 돼.
좀더 와닿는 의미로 이해한 바로는
HP: 매우 복잡한 연산 가능
LP: 전력소비가 적은 장치
LSTP: 언제든 켰다끄기에 최적화된 장비

flash는 비휘발성 장치. 장비를 꺼도 정보가 그대로 남아있어. 디램은 휘발성 장치. 장비가 on일때만 정보를 저장할 수 있어. 대신 dram은 효율적이야.

transistor scaling은 트랜지스터 크기를 줄인다는 개념이고
Moore's Law는 이러한 transistor scaling이 2년마다 약 0.7배의 크기로 작아지는 경향성을 나타내는 현상이야.

1/root(2)니까 약 0.7이겠네

교수님이 말씀해주셨는데, 32nm가 실제 32nm를 뜻하는것이 아니라, 실제 pitch는 112.5nm이지만 신기술에 의해, 이전 기술의 32nm로 만들었을 때와 동일한 performance를 낼 경우 이렇게 쓴다고 했어.

스케일을 줄일때마다 nonideal effect들의 영향도 강해져. 정확히는 어떤 효과들이 있었는지 기억안나지만 복습하면 기억날 것 같아. 또한 Lithography에서도 한계가 있겠지. 분해능 문제? 있을 것 같아.

## 취약 영역

- HP를 복잡한 연산 가능으로 이해했으나 핵심은 연산 복잡도보다 높은 처리 성능을 우선하는 설계라는 구분 필요
- LSTP를 켰다 끄기에 최적화된 것으로 표현했으나 핵심은 standby leakage/power를 낮추는 것
- DRAM의 효율적이라는 표현이 모호하며 전원이 공급되어도 refresh가 필요하다는 점
- Moore's Law를 2년마다 선형 크기가 0.7배가 되는 법칙으로 이해했으나 직접적인 정의는 chip당 transistor 수가 약 2년마다 2배가 되는 경험적 추세
- Scaling 시 강해지는 구체적인 non-ideal effects는 기억이 흐릿함
- Lithography scaling의 resolution 한계는 이후 Lithography 단원에서 깊게 학습 필요

## 다음 복습 질문

- HP, LP, LSTP는 각각 무엇을 우선 최적화하는가?
- Flash와 DRAM의 핵심 차이는 무엇이며 DRAM에는 왜 refresh가 필요한가?
- Moore's Law와 transistor scaling은 어떻게 구분되는가?
- 왜 transistor 수를 같은 chip 면적에서 2배로 늘리려면 선형 dimension이 약 0.7배가 되는가?
- Technology node 숫자와 실제 gate pitch가 왜 같지 않을 수 있는가?
- 왜 classical geometric scaling만으로 계속 scaling하기 어려워졌는가?
- Lithography의 resolution 한계가 scaling과 어떻게 연결되는가?

## 논문 읽기 상태 초안 (반영되지 않음)

### Progress

EE463 1 Introduction: Slide 6 Examples of Si integrated devices부터 Slide 13 CMOS Technology Trend까지 학습. Slide 10 Pitch scaling, Slide 11 32 nm processor cross-section, Slide 12 30 years of scaling, Slide 13 CMOS Technology Trend를 확인함.

### Current Understanding

Introduction의 세부 역사나 MOSFET 선수지식보다 반도체 집적회로 공정 전체 맥락을 우선하기로 함. Scaling이 집적도·성능·비용 개선을 이끌었고, 단순 geometric scaling이 한계에 부딪히면서 strain, high-k/metal gate, FinFET 등의 effective scaling 기술과 KrF→ArF→EUV lithography 발전이 등장했다는 큰 흐름까지 진행함.

### Next Session

Slide 14부터 계속. Introduction 전체 맥락에서 중요도가 낮은 기술은 가볍게, 이후 EE463 공정 학습에 직접 연결되는 핵심 기술은 깊게 다룬다.

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
