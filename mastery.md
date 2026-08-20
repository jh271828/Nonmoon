---
title: "이해도 원장 (Mastery Ledger)"
kind: mastery
---

# 이해도 원장 — "진짜 공부했다"의 증거

> 개념마다 상태를 추적한다. **상태가 아니라 변화로** 기록한다.
> 상태: `미학습` → `암기`(답은 아는데 스스로 설명 못 함) → `설명가능`(스스로 유도·설명함).
> **`설명가능`은 AI의 반박을 통과하고, 증거(그 세션의 daily 링크)가 있을 때만.** 증거 없는 `설명가능`은 자기기만이다.
>
> ⚙️ 아래 표는 **자동 관리된다** — 세션에서 승급이 나오면 CI가 여기에 접어 넣는다.
> 손으로 고쳐도 되지만, `MASTERY-TABLE` 마커는 지우지 말 것(지우면 자동 갱신이 멈춘다).

<!-- MASTERY-TABLE:START -->
| 개념 | 상태 | 중요도 | 최근 검증일 | 증거(daily 세션) | 변화 메모(무엇이·왜 바뀌었나) |
|---|---|---|---|---|---|
| HBM bandwidth와 wide I/O의 관계 | memorized | TSV 구조를 통해서 Die의 정보들이 수직으로 내려가서 더 촘촘해진 Interposer에 도달한 이후, 다수의 병렬 I/O를 통해서 프로세서에 정보를 같은시간 내에 훨씬더 많은 정보를 전달할 수 있게 된다. 따라서 BW가 높아진다. |  |  |  |
| Moore's Law와 transistor scaling의 관계 | memorized | transistor scaling은 트랜지스터 크기를 줄인다는 개념이고 Moore's Law는 이러한 transistor scaling이 2년마다 약 0.7배의 크기로 작아지는 경향성을 나타내는 현상이야. |  |  |  |
| Classical scaling의 한계 | memorized | 스케일을 줄일때마다 nonideal effect들의 영향도 강해져. 정확히는 어떤 효과들이 있었는지 기억안나지만 복습하면 기억날 것 같아. 또한 Lithography에서도 한계가 있겠지. 분해능 문제? 있을 것 같아. |  |  |  |
| High aspect ratio의 의미 | memorized | 구경 대비 높이 비율? |  |  |  |
| DRAM capacitor와 capacitance 확보 | memorized | capacitor에 전하를 저장하므로써 정보를 저장하기 때문이며, 시간이 지날수록 cap의 전하는 자연방전되기 때문에 dram은 주기적으로 refresh를 해줘야 될 것 같아. 이때, C가 충분히 확보되어야 time constant가 커져서 비교적 덜 빨리 방전되겠지? |  |  |  |
| DRAM과 3D NAND에서 high aspect ratio가 생기는 이유 | can_explain | dram은 면적은 줄지만, C는 어느정도수준을 유지해야 되기 때문에 C를 길게 만들면서 구조가 높아졌고, 3d nand는 memory cell 자체를 쌓아서 만드는 구조라서 애초에 구조가 높아져. |  |  |  |
| Atomic scale에서 공정 오차의 상대적 중요성 | can_explain | 1000개에서 +-2는 오차율이 0.2%인데, 20개에서 +-2는 오차율이 10%야. channel길이가 트랜지스터마다 10%씩이나 차이나면, 의도한 회로대로 작동하지 않을 가능성이 올라가니까. |  |  |  |
| Atomic Scale Era의 의미와 scaling 지속 | can_explain | 반도체의 pitch크기가 원자 겨우 수백개~수십개의 크기와 비견될 정도로 작아지는 시기이기 때문. 아직까지도 목표한 scaling을 달성하고 있기 때문 |  |  |  |
| Process Control과 Stochastic Effects | can_explain | 스케일링이 심화될수록, 오차가 전체 오차율에 크게 반영되기 때문에. 마찬가지로 무작위성에 의한 오차가, 전체 오차율에 더욱 큰 비중을 차지하기 때문에? process control은 가능, stochastic은 불가능 |  |  |  |
| Scaling과 process innovation 및 architecture evolution | can_explain | 새로운 공정,새로운 구조, 새로운 재료, 새로운 기술을 적용하여 다양한 방식으로 크기를 줄여왔다라고 말해야 된다 |  |  |  |
| FinFET 대비 GAA의 electrostatic control | can_explain | 3면에서 4면으로 바뀌면서, gate가 channel에 대한 electrostatic control을 강력하게 할 수 있고, 따라서 스케일링을 더욱 하더라도 원치않는 사이드이펙트를 방지할 수 있기때문에 |  |  |  |
<!-- MASTERY-TABLE:END -->

## 읽는 법

- **암기**가 많다 = 답은 아는데 설명은 못 하는 상태. 그 개념부터 다시 설명해 보면 된다.
- **설명가능**이 늘어나는 것이 발전의 증거다. 개수보다 *무엇이* 올라갔는지를 본다.
- 같은 개념이 나중에 올라가면 새 줄로 쌓여 **변화**가 보인다(덮어쓰지 않는다).
