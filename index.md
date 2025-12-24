---
layout: default
title: Home
---

# Math Speech
**짧은 한 줄 소개** — 예: *Multimodal Something for Something.*

---

## Overview
### 1. 샘플수 : 총 문장 수 
 - 31336개
   

### 2. 강의과목비율

![결과 요약 그림2](assets/images/result2.png)

| Field | Count |
|------|------:|
| Calculus | 338 |
| Algebra | 218 |
| Linear Algebra | 9 |
| Geometry | 3 |
| Economics | 2 |
| Statistics | 2 |
| Analysis | 6 |


### 3. 일반 텍스트 대비 수식이 차지하는 비율

![결과 요약 그림](assets/images/result1.png)

| Field | Count |
|---|---:|
| 총 분석된 단어 수 (context + spoken) | 1,035,321개 |
| 총 spoken (수식) 단어 수 | 112,880개 |
| 일반 텍스트 대비 spoken (수식)이 차지하는 비율 | **10.90%** |


### 4. 텍스트 전체 길이

| Field | Count |
|---|---:|
| 총 토큰 수 | 4,545,332 |
| 총 라인 수 | 31,336 |
| 라인당 평균 토큰 수 | 145.08 |
| 가장 긴 라인 | 2,417 |
| 가장 짧은 라인 | 4 |


### 5. 수식 텍스트 다양성 지표

| Metric | Symbol | Operator | Combined (Symbol+Operator) | Structural Pattern Diversity |
|------|--------|----------|-----------------------------|-------------------------------|
| total tokens | 81,790 | 40,925 | **230,211** | 31,336 |
| unique types | 1,030 | 60 | 433 | **2,362** |
| TTR | 0.0126 | 0.0015 | **0.00188** | **0.0754** |
| Shannon Entropy (bits) | **5.8024** | 3.7460 | 5.2485 | **5.8944** |
| Normalized Entropy | 0.5798 | **0.6342** | 0.5993 | **0.5260** |
| avg unique tokens / equation | 2.1930 | 1.0805 | — | — |


## Datasat Links
- [MathBridge2 (Hugging Face)](https://huggingface.co/datasets/delay1/MathBridge2/tree/main)
