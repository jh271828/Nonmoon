---
title: "EE463 Cleaning — contamination control과 wafer cleaning"
created: 2026-08-29
updated: 2026-08-29
tags: [learning]
source: "학습 세션 → Issue #71 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: GPT-5.6 Sol
source_issue: 71
---

# EE463 Cleaning — contamination control과 wafer cleaning

## 오늘 직접 학습한 지식

웨이퍼가 다음 공정으로 이동하는 도중에도 contaminant가 붙어서? 아니면 cleaning에서 오염물질을 완전히 0으로 만들 순 없기 때문에, 공장 전체를 깨끗하게 해야 그나마 contaminant가 덜 붙어서?

Class X에서 X는 1ft^3 공기의 공간에 있는 0.5마이크로미터 미만의 입자 평균 갯수. 전자는 평범한 사무실 수준, 후자는 예술의 경지에 다다른 클린룸의 수준

사람 피부에서 떨어져 나온 유기물이나 Na+, K+ 이온들을 만들어내는 source?

particle은 주로 돌같은 물질이라서, 화학반응시키기가 어려울 것 같은데.ㅣ.. 잘모르겠어

유기물은 산염기/산화환원 반응에 잘 반응해서?

메탈을 이온으로 만들어야 수용액에 용해되기 쉽기 때문에

metal의 전자가 H2O2로 이동

H2O2가 전자를 가져가고, Fe가 전자를 잃어 이온이 됨. 따라서 H2O2가 reduction, Fe가 oxidation

metal contamination 제거는 metal을 이온화 시킨후, 수용액에 씻겨 보내는 형태이다. 표준환원전위표에서 보다싶히, H2O2는 굉장한 Oxidant이다. 따라서 H2O2로 대부분의 metal들을 oxidation시켜 이온으로 만들 수 있다.

bunny suits 조차 contaminant를 0으로 만드는 것은 불가능 하기 때문에, 가능한 오염원을 배출할수 있는 source(사람) 수 자체를 줄이면 좋을것

공정에서 Contaminant는 반도체 소자의 performance에 영향을 줄 수 있으므로, 이를 최소화 해야한다.

최소화는 세가지 접근으로 제시된다. 1. clean room 조성, 2. wafer cleaning, 3. Human control

clean room은 오염물질이 붙는 것을 방지하는 단계이다. Class X와 같은 규격을 사용하며, X는 1ft^3의 공기 내에 0.5마이크로미터보다 큰 물질이 X개보다 적어야 된다는 것을 의미한다. 이러한 Clean room 은 HEPA filters&recirculation으로 공기질을 관리하고, 사람에게 Bunny suit를 입히면서 관리된다.

Wafer cleaning은 이미 붙은 오염물질을 씻는 단계이다. Contaminant에는 3가지가 있다. 첫번째, particle은 물리적으로 웨이퍼 표면에 붙어있으므로, 물리적 제거인 ultrasonic agiation을 사용해서 분리한다. 두번째, Organic은 유기물이므로 O2 plasma나 H2SO4와 같은 산화환원반응으로 제거한다. 세번째, metal은 H2O2를 통해 산화시켜 이온화 시킨 후, cleaning solution으로 제거한다.

Human control은 작업자의 수를 최소화 하는 것이다. Bunny suit조차 완벽하지 않기 때문에, 작업자의 수를 최소화하는 것이 오염물질을 조금이라도 더 줄일 수 있다.

## 취약 영역

- Class X 정의에서 처음에는 0.5 μm보다 작은 입자라고 반대로 기억했음. 최종 정리에서는 0.5 μm보다 큰 입자로 수정함.
- Organic contamination 제거를 단순히 산염기 반응 또는 산화환원 반응으로 표현하는 경향이 있음. 핵심은 강한 산화 조건에서 유기물을 분해/제거하는 것.
- RCA clean을 표준환원전위표로 설명할 때 렉노의 oxidation potential 표기와 부호 방향이 혼동될 수 있음.

## 다음 복습 질문

- Class X의 정확한 정의는 무엇이며 숫자가 작을수록 왜 더 깨끗한가?
- Particle, organic, metal contamination은 각각 어떤 방식으로 제거하며 왜 그 방식이 적합한가?
- RCA clean에서 H2O2가 metal contamination을 제거하는 과정을 전자 이동과 ionization까지 연결해 설명하라.
- Clean room, wafer cleaning, human control은 각각 contamination control에서 어떤 역할을 하는가?

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
