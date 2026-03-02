---
layout: null
---
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>MathBridge2 Test</title>

<link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

<style>
  /* 기본 스타일 설정 - 전체 Google Sans 적용 */
  body {
    font-family: 'Google Sans', sans-serif;
    color: #333;
    background-color: #fff;
    margin: 0;
    padding: 0;
  }
  
  /* 메인 컨테이너 - 통계 섹션 폭(1100px)에 맞춤 */
  .container {
    max-width: 1100px; 
    margin: 0 auto;
    padding: 40px 20px;
  }

  /* 제목 및 헤더 스타일 */
  h1 { font-size: 2.3rem; font-weight: bold; margin-bottom: 10px; line-height: 1.2; text-align: center; }
  h2 { font-size: 1.8rem; margin-top: 50px; margin-bottom: 30px; border-bottom: 2px solid #eee; padding-bottom: 10px; text-align: center; font-weight: bold; text-transform: uppercase; }
  h3 { font-size: 1.2rem; margin-top: 30px; margin-bottom: 15px; }
  
  a { color: #209cee; text-decoration: none; }
  a:hover { text-decoration: underline; }

  /* 본문 정렬 및 리스트 스타일 */
  .abstract-content {
    text-align: justify;
    text-justify: inter-word;
    font-size: 1.1rem;
    line-height: 1.7;
    margin-bottom: 40px;
    color: #444;
  }
  
  .list-content {
    text-align: left;
    font-size: 1.1rem;
    line-height: 1.7;
  }

  .list-content ul {
    list-style-type: disc;
    padding-left: 20px;
  }

  .list-content li {
    margin-bottom: 12px;
  }

  .highlight {
    font-weight: bold;
    color: #000;
  }
</style>

<div class="container">

  <h1>A Data-Centric Approach to Improving Spoken
Mathematical Equation Recognition with ASR in
Real-World Lecture Environments</h1>
  
  <div style="text-align: center; margin-top: 25px; margin-bottom: 15px;">
    <span style="font-size: 1.4rem; font-weight: 700; color: #000;">
    <a href="#">Hyeonggi Seong</a><sup>1</sup>, 
    <a href="#">Namjoon Kim</a><sup>1</sup>, 
    <a href="#">Hyungon Ryu</a><sup>2</sup>,
    <a href="#">Jiyeon Shin</a><sup>1</sup>,
    <a href="#">Haeun Min</a><sup>3</sup>, 
    <a href="#">Hyungyu Lee</a><sup>3</sup>, 
    <a href="#">Seeun Jo</a><sup>1</sup>,
    <a href="#">Sieun Hyun</a><sup>1</sup>,
    <a href="#">Hyukjae Lee</a><sup>1</sup>
  </span>
  </div>
  
<div style="text-align: center;">
    <p style="color: #666; font-size: 1.1rem; font-weight: 500; margin: 0; line-height: 1.7;">
    <sup>1</sup>Seoul National University, 1 Gwanak-ro, Gwanak-gu, Seoul, 08826, Republic of Korea (e-mail: author@snu.ac.kr)<br>
    <sup>2</sup>Chung-Ang University, 84 Heukseok-ro, Dongjak-gu, Seoul, 06974, Republic of Korea (e-mail: author@cau.ac.kr)<br>
    <sup>3</sup>NVIDIA Korea

  </div>

  <p style="color: #888; font-size: 1.0rem; margin-top: 20px; font-weight: 400;">
      * Corresponding Author :  HyukJae Lee (e-mail: hjlee@snu.ac.kr).
    </p>
  </div>

  <div style="margin: 30px 0; display: flex; justify-content: center; gap: 10px;">
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">📄 arXiv</a>
    <a href="#" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">💻 Code</a>
    <a href="https://huggingface.co/datasets/delay1/MathBridge2/tree/main" style="background: #333; color: white; padding: 10px 20px; border-radius: 30px; font-weight: bold;">🤗 Dataset</a>
  </div>

  <h2>Abstract</h2>
  <div class="abstract-content">
    Converting spoken mathematical expressions into LaTeX is a critical yet under-addressed 
    problem: it requires translating ambiguous, conversational speech into a rigid symbolic language while 
    recovering precise structure such as nesting, operator precedence, and scope. As lecture capture and AI 
    assisted learning tools become ubiquitous, the inability to reliably convert spoken mathematics into editable, 
    searchable LaTeX has become a practical bottleneck for education and research—limiting high-quality 
    lecture transcription, accessible note-taking, and downstream reuse of mathematical content. Despite major 
    advances in automatic speech recognition (ASR) and large language models (LLMs), existing approaches for 
    mathematical ASR post-correction often depend on multiple transcripts, focus on isolated equations rather 
    than natural lecture utterances, and are evaluated on small, constrained test sets. These limitations leave the 
    real-world lecture settings—where speakers omit terms, reference symbols implicitly, and mix equations 
    with explanatory sentences—largely unseen. To close this gap, we release the first fully open-source, large 
    scale dataset of spoken mathematics: over 30,000 human-annotated audio samples from real English lectures, 
    spanning diverse scientific domains and covering both equations and mathematical sentences. We also 
    introduce a practical conversion pipeline that pairs an ASR post-correction model with a formula-detecting 
    LLM to more accurately identify and render mathematical content in lecture speech. On our new S2L 
    Equations benchmark, our models outperform MathSpeech by more than xx.x percentage points, establishing 
    a strong baseline for speech-to-LaTeX conversion under realistic lecture conditions.
  </div>

  <hr style="border: 0; border-top: 1px solid #eee; margin: 40px 0;">

  <h2>Key Takeaways</h2>
  <div class="list-content">
    <ul>
      <li><span class="highlight">Introduction of S2L Dataset:</span> We present the first large-scale, open-source dataset for Speech-to-LaTeX (S2L) conversion, featuring over 30,000 human-annotated samples from real lectures and 571,000 synthetic samples.</li>
      <li><span class="highlight">Addressing Real-World Complexity:</span> This work specifically tackles "mixed-content" scenarios where mathematical expressions are naturally interleaved with explanatory natural language, reflecting actual lecture environments.</li>
      <li><span class="highlight">Novel ASR Post-Correction Pipeline:</span> We propose a robust pipeline pairing state-of-the-art ASR models with fine-tuned formula-detecting LLMs to resolve operator precedence and structural ambiguities.</li>
      <li><span class="highlight">Commitment to Open Science:</span> By releasing a high-quality human-annotated corpus and a generation pipeline, we establish a foundation for accessible scientific note-taking and content reuse.</li>
    </ul>
  </div>

  <h2>Results</h2>
  <div class="list-content">
    <ul>
      <li><span class="highlight">Superior Performance:</span> Our Enhanced MathSpeech pipeline significantly outperforms existing baselines (e.g., MathSpeech) on the S2L-Equations benchmark in both CER and TexBLEU metrics.</li>
      <li><span class="highlight">Robust Mixed-Content Transcription:</span> The LLM-based detection module maintains high accuracy in transcribing natural language while precisely rendering embedded LaTeX formulas.</li>
      <li><span class="highlight">High Mathematical Fidelity:</span> Our fine-tuned Qwen2.5-Math models demonstrate a high compilation success rate, ensuring syntactically correct symbolic structures even with ambiguous speech.</li>
      <li><span class="highlight">Efficiency at Scale:</span> With models as small as 120M parameters, the proposed pipeline offers superior performance-efficiency trade-offs compared to much larger commercial LLMs.</li>
    </ul>
  </div>

  <h2>Statistics</h2>

  <div style="text-align: left; max-width: 1100px; margin: 0 auto;">
    
    <h3 style="border-left: 6px solid #209cee; padding-left: 15px;">1. Overview</h3>
    <p style="font-size: 1.2rem; margin-left: 20px;">
      <strong>• Total Samples (총 문장 수):</strong> 31,336 개
    </p>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 50px;">2. Distribution of Subjects</h3>
    
    <div style="display: flex; align-items: center; gap: 50px; margin: 30px 0; flex-wrap: wrap;">
      <div style="flex: 1.2; min-width: 400px; text-align: center;">
        <img src="assets/images/result2.png" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 1.0rem; margin-top: 15px;">Figure 1. Subject Distribution</p>
      </div>
      <div style="flex: 1; min-width: 350px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.1rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 15px; border:1px solid #ddd;">Field</th><th style="padding: 15px; border:1px solid #ddd;">Count</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Calculus</td><td style="padding: 12px; border:1px solid #ddd;">338</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Algebra</td><td style="padding: 12px; border:1px solid #ddd;">218</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Linear Algebra</td><td style="padding: 12px; border:1px solid #ddd;">9</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Geometry</td><td style="padding: 12px; border:1px solid #ddd;">3</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Economics</td><td style="padding: 12px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Statistics</td><td style="padding: 12px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Analysis</td><td style="padding: 12px; border:1px solid #ddd;">6</td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 60px;">3. Math Formula Ratio</h3>
    
    <div style="display: flex; align-items: center; gap: 50px; margin: 30px 0; flex-wrap: wrap;">
      <div style="flex: 1.2; min-width: 400px; text-align: center;">
        <img src="assets/images/result1.png" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 1.0rem; margin-top: 15px;">Figure 2. Formula Ratio Analysis</p>
      </div>
      <div style="flex: 1; min-width: 350px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.1rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 15px; border:1px solid #ddd;">Metric</th><th style="padding: 15px; border:1px solid #ddd;">Value</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 12px; border:1px solid #ddd; text-align: left;">Total words</td><td style="padding: 12px; border:1px solid #ddd;">1,035,321</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd; text-align: left;">Formula words</td><td style="padding: 12px; border:1px solid #ddd;">112,880</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">Ratio</td><td style="padding: 12px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">10.90%</td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 60px;">4. Text Length & Diversity</h3>
    <div style="overflow-x: auto; margin-top: 30px;">
      <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.0rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
          <tr><th style="padding: 15px; border:1px solid #ddd;">Metric</th><th style="padding: 15px; border:1px solid #ddd;">Count</th></tr>
        </thead>
        <tbody>
          <tr><td style="padding: 12px; border:1px solid #ddd;">Total Tokens</td><td style="padding: 12px; border:1px solid #ddd;">4,545,332</td></tr>
          <tr><td style="padding: 12px; border:1px solid #ddd;">Avg Tokens/Line</td><td style="padding: 12px; border:1px solid #ddd;">145.08</td></tr>
        </tbody>
      </table>
    </div>

  </div>

  <h2>Citation</h2>
  <div style="background-color: #f5f5f5; padding: 20px; border-radius: 10px; font-family: monospace; font-size: 0.9rem;">
    @article{yourname2026s2l,<br>
    &nbsp;&nbsp;title={S2L: Spoken Mathematical Expressions to LaTeX Dataset},<br>
    &nbsp;&nbsp;author={Your Name and Collaborators},<br>
    &nbsp;&nbsp;journal={arXiv preprint arXiv:xxxx.xxxxx},<br>
    &nbsp;&nbsp;year={2026}<br>
    }
  </div>

</div>

</div>
  <h2>Statistics</h2>

  <div style="text-align: left; max-width: 1100px; margin: 0 auto;">
    
    <h3 style="border-left: 6px solid #209cee; padding-left: 15px;">1. Overview</h3>
    <p style="font-size: 1.2rem; margin-left: 20px;">
      <strong>• Total Samples (총 문장 수):</strong> 31,336 개
    </p>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 50px;">2. Distribution of Subjects</h3>
    
    <div style="display: flex; align-items: center; gap: 50px; margin: 30px 0; flex-wrap: wrap;">
      <div style="flex: 1.2; min-width: 400px; text-align: center;">
        <img src="assets/images/result2.png" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 1.0rem; margin-top: 15px;">Figure 1. Subject Distribution</p>
      </div>
      <div style="flex: 1; min-width: 350px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.1rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 15px; border:1px solid #ddd;">Field</th><th style="padding: 15px; border:1px solid #ddd;">Count</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Calculus</td><td style="padding: 12px; border:1px solid #ddd;">338</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Algebra</td><td style="padding: 12px; border:1px solid #ddd;">218</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Linear Algebra</td><td style="padding: 12px; border:1px solid #ddd;">9</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Geometry</td><td style="padding: 12px; border:1px solid #ddd;">3</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Economics</td><td style="padding: 12px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Statistics</td><td style="padding: 12px; border:1px solid #ddd;">2</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd;">Analysis</td><td style="padding: 12px; border:1px solid #ddd;">6</td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 60px;">3. Math Formula Ratio</h3>
    
    <div style="display: flex; align-items: center; gap: 50px; margin: 30px 0; flex-wrap: wrap;">
      <div style="flex: 1.2; min-width: 400px; text-align: center;">
        <img src="assets/images/result1.png" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
        <p style="color: #666; font-size: 1.0rem; margin-top: 15px;">Figure 2. Formula Ratio Analysis</p>
      </div>
      <div style="flex: 1; min-width: 350px; overflow-x: auto;">
        <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.1rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
          <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
            <tr><th style="padding: 15px; border:1px solid #ddd;">Metric</th><th style="padding: 15px; border:1px solid #ddd;">Value</th></tr>
          </thead>
          <tbody>
            <tr><td style="padding: 12px; border:1px solid #ddd; text-align: left;">Total words</td><td style="padding: 12px; border:1px solid #ddd;">1,035,321</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd; text-align: left;">Formula words</td><td style="padding: 12px; border:1px solid #ddd;">112,880</td></tr>
            <tr><td style="padding: 12px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">Ratio</td><td style="padding: 12px; border:1px solid #ddd; font-weight: bold; color: #107bbd;">10.90%</td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <h3 style="border-left: 6px solid #209cee; padding-left: 15px; margin-top: 60px;">4. Text Length & Diversity</h3>
    <div style="overflow-x: auto; margin-top: 30px;">
      <table style="width: 100%; border-collapse: collapse; text-align: center; font-size: 1.0rem; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <thead style="background-color: #f8f9fa; border-bottom: 2px solid #eee;">
          <tr><th style="padding: 15px; border:1px solid #ddd;">Metric</th><th style="padding: 15px; border:1px solid #ddd;">Count</th></tr>
        </thead>
        <tbody>
          <tr><td style="padding: 12px; border:1px solid #ddd;">Total Tokens</td><td style="padding: 12px; border:1px solid #ddd;">4,545,332</td></tr>
          <tr><td style="padding: 12px; border:1px solid #ddd;">Avg Tokens/Line</td><td style="padding: 12px; border:1px solid #ddd;">145.08</td></tr>
        </tbody>
      </table>
    </div>

  </div>

  <h2>Citation</h2>
   내용 추가 

</div>
