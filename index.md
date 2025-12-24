---
layout: default
title: Home
---
<div align="center">

  <h1 style="font-size: 2.5em; font-weight: bold; margin-bottom: 10px;">
    MMPB: It's Time for Multi-Modal Personalization
  </h1>

  <span style="background-color: #ff0055; color: white; padding: 5px 15px; border-radius: 20px; font-weight: bold; font-size: 0.9em;">
    NeurIPS 2025
  </span>

  <br><br>

  <p style="font-size: 1.2em;">
    <a href="#" style="color: #4169E1; text-decoration: none;">Jaeik Kim</a><sup>1</sup>, 
    <a href="#" style="color: #4169E1; text-decoration: none;">Woojin Kim</a><sup>2</sup>,
    <a href="#" style="color: #4169E1; text-decoration: none;">Woohyeon Park</a><sup>2</sup>
  </p>

  <p style="color: #555;">
    Seoul National University, <sup>1</sup>IPAI <sup>2</sup>ECE
  </p>

  <br>

  <div style="display: flex; justify-content: center; gap: 10px;">
    <a href="링크주소" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      📄 arXiv
    </a>
    <a href="링크주소" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      💻 Code
    </a>
    <a href="링크주소" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      🤗 Dataset
    </a>
  </div>

  <br>

  <div style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap;">
    <span style="border: 1px solid #ddd; padding: 5px 10px; border-radius: 20px; color: #555; font-size: 0.9em;">
      111 concepts
    </span>
    <span style="border: 1px solid #ddd; padding: 5px 10px; border-radius: 20px; color: #555; font-size: 0.9em;">
      10k+ image-query pairs
    </span>
    <span style="border: 1px solid #ddd; padding: 5px 10px; border-radius: 20px; color: #555; font-size: 0.9em;">
      23 VLMs evaluated
    </span>
  </div>

</div>
<br>
<hr>

## Abstract
여기에 논문 요약 내용을 적으시면 됩니다...
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
