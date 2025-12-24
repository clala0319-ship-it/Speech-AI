---
layout: default
title: Home
---
<link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<style>
.main-content, .wrapper, .container {
max-width: 1000px !important;
width: 100% !important;
padding: 20px !important;
margin: 0 auto !important; 
}

body, h1, h2, h3, h4, p, a {
font-family: 'Google Sans', 'Noto Sans', sans-serif !important;
color: #333;
}


h1 { font-size: 2.5em !important; line-height: 1.2 !important; margin-top: 30px !important;}
h2 { font-size: 1.8em !important; margin-top: 40px !important; margin-bottom: 20px !important;}


a { color: #209cee; text-decoration: none; }
a:hover { color: #1476b8; text-decoration: underline; }


header, footer { display: none !important; }
</style>

<div align="center">

  <h1 style="font-size: 2.5em; font-weight: bold; margin-bottom: 10px;">
    MathBridge2(제목 수정 필요)
  </h1>

  <p style="font-size: 1.2em;">
    김남준, 성형기, 현시은, 김민건, 민하은, Jiyeon Shin, 조세은(전부 영문명으로 변경 필요)
    
  </p>

  <p style="color: #555;">
    Seoul National University, 혁신융합대학(수정 필요)
  </p>


  <div style="display: flex; justify-content: center; gap: 10px;">
    <a href="링크주소" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      📄 arXiv
    </a>
    <a href="링크주소" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      💻 Code
    </a>
    <a href="https://huggingface.co/datasets/delay1/MathBridge2/tree/main" style="background-color: #333; color: white; padding: 8px 15px; border-radius: 20px; text-decoration: none; font-weight: bold;">
      🤗 Dataset
    </a>
  </div>

</div>
<br>
<hr>

<div style="max-width: 800px; margin: 0 auto; text-align: justify;">
  <h2 style="text-align: center;">Abstract</h2>
  <p style="font-size: 1.1em; line-height: 1.6;">
    초록 넣기
  </p>
</div>
<br><br>

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
