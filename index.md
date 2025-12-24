---
layout: null
---
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>MMPB Project Page</title>

<link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<style>
  /* 기본 스타일 설정 */
  body {
    font-family: 'Google Sans', sans-serif;
    color: #333;
    background-color: #fff;
    margin: 0;
    padding: 0;
  }
  
  /* 메인 컨테이너 */
  .container {
    max-width: 1000px; /* 화면 폭을 시원하게 넓힘 */
    margin: 0 auto;
    padding: 40px 20px;
    text-align: center;
  }

  /* 제목 및 텍스트 스타일 */
  h1 { font-size: 2.0rem; font-weight: bold; margin-bottom: 10px; line-height: 1.2; }
  h2 { font-size: 1.8rem; margin-top: 50px; margin-bottom: 30px; border-bottom: 2px solid #eee; padding-bottom: 10px; text-align: center;}
  h3 { font-size: 1.2rem; margin-top: 30px; margin-bottom: 15px; }
  
  a { color: #209cee; text-decoration: none; }
  a:hover { text-decoration: underline; }

  /* 본문 정렬 */
  .content-text {
    text-align: center;
    font-size: 1.1rem;
    line-height: 1.6;
    max-width: 900px;
    margin: 0 auto;
  }
  
  /* BibTeX 박스 */
  pre {
    background: #f5f5f5;
    padding: 20px;
    border-radius: 10px;
    text-align: left;
    overflow-x: auto;
    font-family: monospace;
  }
</style>

<div class="container">

  <h1>MathBridge 2 (제목 수정 필요)</h1>

  <p style="font-size: 1.2rem; margin-top: 20px;">
    김남준, 성형기, 현시은, 김민건, 민하은, Jiyeon Shin, 조세은 .... 등 ... (전부 영문명으로 변경 필요)
  </p>
  
  <p style="color: #666;">
    Seoul National University, 수정
  </p>

  <div style="margin: 30px 0; display: flex; justify-content: center; gap: 10px;">
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">📄 arXiv</a>
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">💻 Code</a>
    <a href="https://huggingface.co/datasets/delay1/MathBridge2/tree/main" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">🤗 Dataset</a>
  </div>

  <h2>Abstract</h2>
  <div class="content-text">
    <p>
      (본문 내용)
    </p>
  </div>

  <h2>Key Takeaways</h2>
   내용 추가

  <h2>Results</h2>
   내용 추가 

  <h2>Statistics</h2>

  <div style="text-align: left; max-width: 950px; margin: 0 auto;">
    
    <h3 style="border-left: 5px solid #209cee; padding-left: 10px;">1. Overview</h3>
    <p style="font-size: 1.1rem; margin-left: 15px;">
      <strong>• Total Samples (총 문장 수):</strong> 31,336 개
    </p>

    <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 40px;">2. Distribution of Subjects</h3>
    
    <div style="display: flex; align-items: flex-start; gap: 40px; margin: 20px 0; flex-wrap: wrap;">
      <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="assets/images/result2.png" style="max-width: 100%; width: auto; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 0.9rem; margin-top: 10px;">Figure 1. Subject Distribution</p>
      </div>
      <div style="flex: 1.2; min-width: 300px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 12px; border:1px solid #ddd;">Field</th><th style="padding: 12px; border:1px solid #ddd;">Count</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Calculus</td><td style="padding: 10px; border:1px solid #ddd;">338</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Algebra</td><td style="padding: 10px; border:1px solid #ddd;">218</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Linear Algebra</td><td style="padding: 10px; border:1px solid #ddd;">9</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Geometry</td><td style="padding: 10px; border:1px solid #ddd;">3</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Economics</td><td style="padding: 10px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Statistics</td><td style="padding: 10px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd;">Analysis</td><td style="padding: 10px; border:1px solid #ddd;">6</td></tr>
          </tbody>
        </table>
      </div>
    </div>


    <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 50px;">3. Math Formula Ratio</h3>
    
    <div style="display: flex; align-items: center; gap: 40px; margin: 20px 0; flex-wrap: wrap;">
      <div style="flex: 1; min-width: 300px; text-align: center;">
        <img src="assets/images/result1.png" style="max-width: 100%; width: auto; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 0.9rem; margin-top: 10px;">Figure 2. Formula Ratio Analysis</p>
      </div>
      <div style="flex: 1.2; min-width: 300px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 12px; border:1px solid #ddd;">Metric</th><th style="padding: 12px; border:1px solid #ddd;">Value</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 10px; border:1px solid #ddd; text-align: left;">Total words</td><td style="padding: 10px; border:1px solid #ddd;">1,035,321</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd; text-align: left;">Formula words</td><td style="padding: 10px; border:1px solid #ddd;">112,880</td></tr>
            <tr><td style="padding: 10px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">Ratio</td><td style="padding: 10px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">10.90%</td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <h3 style="border-left: 5px solid #209cee; padding-left: 10px; margin-top: 50px;">4. Text Length & Diversity</h3>
    <div style="overflow-x: auto; margin-top: 20px;">
      <table style="width: 100%; border-collapse: collapse; text-align: center; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
          <tr><th style="padding: 12px; border:1px solid #ddd;">Metric</th><th style="padding: 12px; border:1px solid #ddd;">Count</th></tr>
        </thead>
        <tbody>
          <tr><td style="padding: 10px; border:1px solid #ddd;">Total Tokens</td><td style="padding: 10px; border:1px solid #ddd;">4,545,332</td></tr>
          <tr><td style="padding: 10px; border:1px solid #ddd;">Avg Tokens/Line</td><td style="padding: 10px; border:1px solid #ddd;">145.08</td></tr>
        </tbody>
      </table>
    </div>

  </div> <h2>BibTeX</h2>
  <pre><code>@inproceedings{kim2025mmpb,
  title={MMPB: It's Time for Multi-Modal Personalization},
  author={Kim, Jaeik and Kim, Woojin and Park, Woohyeon and Do, Jaeyoung},
  booktitle={NeurIPS},
  year={2025}
}</code></pre>

</div>
