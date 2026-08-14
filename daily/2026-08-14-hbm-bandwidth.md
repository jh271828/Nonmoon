---
title: "HBM Bandwidth 장점 이해"
created: 2026-08-14
updated: 2026-08-14
tags: [learning]
source: "학습 세션 → Issue #24 (수집기: ingest_learning_note.py)"
status: active
kind: mixed
runner: 탑다운
source_issue: 24
---

# HBM Bandwidth 장점 이해

## 오늘 직접 학습한 지식

이제 HBM의 구조는 어느정도 이해했어. 그다음에 나오는 내용이 HBM이 어느 장점을 가지냐인 것 같아. 일단 Bandwidth가 왜 빨라졌는지는 잘 모르겠어.

정보를 보내는 속도?

정보를 보내는 속도인가?

동시에 데이터를 보내는 통로를 엄청 많이 만든다?

여기서 질문. Micro Bump랑 Interposer는 이전세대의 메모리에도 있는 구조 아니야?

더 많은 I/O를 넣을 수 있다

TSV를 통해서 내려간다

TSV 구조를 통해서 Die의 정보들이 수직으로 내려가서 더 촘촘해진 Interposer에 도달한 이후, 다수의 병렬 I/O를 통해서 프로세서에 정보를 같은시간 내에 훨씬더 많은 정보를 전달할 수 있게 된다. 따라서 BW가 높아진다.

GDDR에는 MicroBump로 직접 연결하므로, 더 촘촘하게 만들기에는 물리적 한계가 있다?

## 취약 영역

- Bandwidth를 처음에는 단순히 정보를 보내는 속도로 이해했으나, 단위 시간당 전송 가능한 데이터 양이라는 구분을 더 복습할 필요가 있음.
- GDDR이 GPU와 micro-bump로 직접 연결된다고 생각했음. 일반적인 GDDR은 별도 메모리 패키지로 GPU와 주로 PCB 배선을 통해 연결된다는 점을 다시 확인할 필요가 있음.
- GDDR이 HBM처럼 I/O 개수를 크게 늘리기 어려운 이유를 아직 교정 후 자기 말로 다시 설명하지 않음.

## 다음 복습 질문

- Bandwidth가 높다는 것은 정확히 무엇을 의미하는가?
- HBM의 높은 bandwidth에서 TSV와 silicon interposer는 각각 어떤 역할을 하는가?
- GDDR은 왜 HBM처럼 I/O 개수를 크게 늘리기 어려운가?

> ⚠️ 아래 헤딩은 수집기가 자동 보정했다 — 세션에 실제 기록이 없었다는 뜻이다.

## 현재 이해 수준
- (이번 세션 기록 없음)

## 미해결 질문
- (이번 세션 기록 없음)
