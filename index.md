---
layout: null
---
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>MMPB Project Page</title>

<link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<style>
  /* 기본 설정 */
  body {
    font-family: 'Google Sans', sans-serif;
    color: #333;
    background-color: #fff;
    margin: 0;
    padding: 0;
  }

  /* 내용을 가운데로 모아주는 컨테이너 */
  .container {
    max-width: 900px;
    margin: 0 auto;
    padding: 40px 20px;
    text-align: center;
  }

  /* 제목 및 폰트 스타일 */
  h1 { font-size: 2.5rem; font-weight: bold; margin-bottom: 10px; line-height: 1.2; }
  h2 { font-size: 2rem; margin-top: 50px; margin-bottom: 20px; border-bottom: 2px solid #eee; padding-bottom: 10px; }
  a { color: #209cee; text-decoration: none; }
  a:hover { text-decoration: underline; }

  /* 본문 정렬 */
  .content-text {
    text-align: justify;
    font-size: 1.1rem;
    line-height: 1.6;
  }
  
  /* BibTeX 박스 */
  pre {
    background: #f5f5f5;
    padding: 20px;
    border-radius: 10px;
    text-align: left;
    overflow-x: auto;
  }
</style>

<div class="container">

  <h1>MathBridge 2 (제목 수정 필요)<h1>

  <p style="font-size: 1.2rem; margin-top: 20px;">
    김남준, 성형기, 현시은, 김민건, 민하은, Jiyeon Shin, 조세은(전부 영문명으로 변경 필요)
  </p>
  
  <p style="color: #666;">
    Seoul National University (수정 필요)
  </p>

  <div style="margin: 30px 0; display: flex; justify-content: center; gap: 10px;">
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">📄 arXiv</a>
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">💻 Code</a>
    <a href="https://huggingface.co/datasets/delay1/MathBridge2/tree/main" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">🤗 Dataset</a>
  </div>

  <h2>Abstract</h2>
  <div class="content-text">
    <p>
      초록 추후 작성
    </p>
  </div>

  <h2>Key Takeaways</h2>
   내용 추가

  <h2>Results</h2>
   내용 추


<h2>Statistics</h2>

<div style="text-align: left; max-width: 800px; margin: 0 auto;">
  
  <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">1. Overview</h3>
  <p style="font-size: 1.1rem; margin-left: 15px;">
    <strong>• Total Samples (총 문장 수):</strong> 31,336 개
  </p>

  <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">2. Distribution of Subjects</h3>
  
  <div style="text-align: center; margin: 20px 0;">
    <img src="assets/images/result2.png" style="max-width: 80%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  </div>

  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px; text-align: center;">
      <thead style="background-color: #f8f9fa;">
        <tr>
          <th style="padding: 12px; border: 1px solid #ddd;">Field</th>
          <th style="padding: 12px; border: 1px solid #ddd;">Count</th>
        </tr>
      </thead>
      <tbody>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Calculus</td><td style="padding: 8px; border: 1px solid #ddd;">338</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Algebra</td><td style="padding: 8px; border: 1px solid #ddd;">218</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Linear Algebra</td><td style="padding: 8px; border: 1px solid #ddd;">9</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Geometry</td><td style="padding: 8px; border: 1px solid #ddd;">3</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Economics</td><td style="padding: 8px; border: 1px solid #ddd;">2</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Statistics</td><td style="padding: 8px; border: 1px solid #ddd;">2</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Analysis</td><td style="padding: 8px; border: 1px solid #ddd;">6</td></tr>
      </tbody>
    </table>
  </div>

  <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">3. Math Formula Ratio</h3>
  
  <div style="text-align: center; margin: 20px 0;">
    <img src="assets/images/result1.png" style="max-width: 80%; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  </div>

  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px; text-align: center;">
      <thead style="background-color: #f8f9fa;">
        <tr>
          <th style="padding: 12px; border: 1px solid #ddd;">Field</th>
          <th style="padding: 12px; border: 1px solid #ddd;">Count / Ratio</th>
        </tr>
      </thead>
      <tbody>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Total analyzed words</td><td style="padding: 8px; border: 1px solid #ddd;">1,035,321</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Total spoken (formula) words</td><td style="padding: 8px; border: 1px solid #ddd;">112,880</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd; font-weight: bold; color: #209cee;">Formula Ratio</td><td style="padding: 8px; border: 1px solid #ddd; font-weight: bold; color: #209cee;">10.90%</td></tr>
      </tbody>
    </table>
  </div>

  <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">4. Text Length Statistics</h3>
  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px; text-align: center;">
      <thead style="background-color: #f8f9fa;">
        <tr>
          <th style="padding: 12px; border: 1px solid #ddd;">Metric</th>
          <th style="padding: 12px; border: 1px solid #ddd;">Count</th>
        </tr>
      </thead>
      <tbody>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Total Tokens</td><td style="padding: 8px; border: 1px solid #ddd;">4,545,332</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Total Lines</td><td style="padding: 8px; border: 1px solid #ddd;">31,336</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Avg Tokens per Line</td><td style="padding: 8px; border: 1px solid #ddd;">145.08</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Max Line Length</td><td style="padding: 8px; border: 1px solid #ddd;">2,417</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd;">Min Line Length</td><td style="padding: 8px; border: 1px solid #ddd;">4</td></tr>
      </tbody>
    </table>
  </div>

  <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">5. Diversity Metrics</h3>
  <div style="overflow-x: auto;">
    <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px; text-align: center; font-size: 0.9rem;">
      <thead style="background-color: #f8f9fa;">
        <tr>
          <th style="padding: 10px; border: 1px solid #ddd;">Metric</th>
          <th style="padding: 10px; border: 1px solid #ddd;">Symbol</th>
          <th style="padding: 10px; border: 1px solid #ddd;">Operator</th>
          <th style="padding: 10px; border: 1px solid #ddd;">Combined</th>
          <th style="padding: 10px; border: 1px solid #ddd;">Structural Pattern</th>
        </tr>
      </thead>
      <tbody>
        <tr><td style="padding: 8px; border: 1px solid #ddd; text-align: left;">Total Tokens</td><td>81,790</td><td>40,925</td><td><strong>230,211</strong></td><td>31,336</td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd; text-align: left;">Unique Types</td><td>1,030</td><td>60</td><td>433</td><td><strong>2,362</strong></td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd; text-align: left;">TTR</td><td>0.0126</td><td>0.0015</td><td><strong>0.00188</strong></td><td><strong>0.0754</strong></td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd; text-align: left;">Shannon Entropy</td><td><strong>5.8024</strong></td><td>3.7460</td><td>5.2485</td><td><strong>5.8944</strong></td></tr>
        <tr><td style="padding: 8px; border: 1px solid #ddd; text-align: left;">Norm. Entropy</td><td>0.5798</td><td><strong>0.6342</strong></td><td>0.5993</td><td><strong>0.5260</strong></td></tr>
      </tbody>
    </table>
  </div>

</div>
<br><br>
