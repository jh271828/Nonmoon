---
title: "EE463 Introduction — Atomic Scale Era와 Scaling 한계"
created: 2026-08-20
updated: 2026-08-20
tags: [learning]
source: "학습 세션 → Issue #40 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: GPT-5.6 Sol
source_issue: 40
---

# EE463 Introduction — Atomic Scale Era와 Scaling 한계

> ⚠️ 서버 경고: READING_STATUS 갱신은 논문 모드 전용이라 반영되지 않았다(이 절은 세션 노트에만 남는다). 자료(강의노트 등) 진도는 sections에 {name: "자료 진도 갱신", body: "### Progress\n…\n### Next Session\n…"} 절로 다시 보내라 — 모드와 무관하게 반영된다.

## 오늘 직접 학습한 지식

작아지면 소모 전력도 줄고, 웨이퍼 하나에 만들수 있는 트랜지스터가 늘어나서, 트랜지스터의 개당 제작 비용도 감소해.

1000개에서 +-2는 오차율이 0.2%인데, 20개에서 +-2는 오차율이 10%야.

channel길이가 트랜지스터마다 10%씩이나 차이나면, 의도한 회로대로 작동하지 않을 가능성이 올라가니까.

반도체의 pitch크기가 원자 겨우 수백개~수십개의 크기와 비견될 정도로 작아지는 시기이기 때문

아직까지도 목표한 scaling을 달성하고 있기 때문

스케일링이 심화될수록, 오차가 전체 오차율에 크게 반영되기 때문에

마찬가지로 무작위성에 의한 오차가, 전체 오차율에 더욱 큰 비중을 차지하기 때문에?

process control은 가능, stochastic은 불가능

원자 겨우 수십개로 이루어진 구조이기 때문에, 방금 말했던 두가지 오차가 더 크게 작용한다는 것

기존 기술로는 더 줄이는데 한계가 있었기 때문에. 또는 기존 기술로는 공정 오차가 너무 컸기 때문에

새로운 공정,새로운 구조, 새로운 재료, 새로운 기술을 적용하여 다양한 방식으로 크기를 줄여왔다라고 말해야 된다

gate와 channel이 기판에 수직에서 수평으로 겹겹히 쌓인 구조로 바뀌었고, 게이트에 닿는 채널의 수가 더 많아지면서? 그다음엔 모르겠다

게이트가 채널을 더욱더 스위칭하기 쉬워진다

3면에서 4면으로 바뀌면서, gate가 channel에 대한 electrostatic control을 강력하게 할 수 있고, 따라서 스케일링을 더욱 하더라도 원치않는 사이드이펙트를 방지할 수 있기때문에

## 취약 영역

- Process Control과 Stochastic Effects의 차이는 구분했지만 stochastic effect가 발생하는 구체적인 물리적 예시는 아직 설명하지 않음
- FinFET/GAA가 억제하는 short-channel effect와 leakage의 구체적인 물리는 아직 학습 범위 밖으로 미룸

## 다음 복습 질문

- 같은 ±2 원자 오차가 1000원자 구조보다 20원자 구조에서 더 심각한 이유는 무엇인가?
- Process Control 문제와 Stochastic Effects의 차이는 무엇이며 공정 장비가 완벽해져도 어느 쪽이 남는가?
- 단순한 비례 축소만으로 scaling을 지속하지 않고 process innovation과 architecture evolution이 필요해진 이유는 무엇인가?
- FinFET과 GAA Nanosheet에서 gate가 channel을 감싸는 방식은 어떻게 다르며 GAA가 scaling에 유리한 이유는 무엇인가?

## 논문 읽기 상태 초안 (반영되지 않음)

### Progress

EE463 1 Introduction Slide 19까지 완료. Slide 15 Atomic Scale Era, Slide 16~17 Process Implications of Scaling, Slide 18 CMOS Technology advancement, Slide 19 GAA Nanosheet까지 학습 및 검증 완료.

### Current Understanding

Atomic scale로 접근할수록 동일한 절대 오차의 상대적 영향이 커지고 process control과 stochastic effects가 중요해진다는 점을 설명할 수 있다. 단순 축소만으로 scaling을 지속한 것이 아니라 새로운 공정·재료·구조를 도입해왔으며, FinFET에서 GAA로 가면서 gate가 channel을 3면에서 4면으로 감싸 electrostatic control을 강화해 추가 scaling에 유리하다는 점을 설명할 수 있다.

### Next Session

EE463 Introduction 다음 챕터/다음 강의 범위부터 시작. Introduction Slide 19까지는 완료된 것으로 취급하고 반복하지 않는다.

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
