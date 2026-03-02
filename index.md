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
    padding: 100px 20px 40px 20px;
  }

  /* 제목 및 헤더 스타일 */
  h1 { font-size: 3.5rem; font-weight: 800; margin-bottom: 25px; line-height: 1.1;  text-align: center;  letter-spacing: -1.5px; color: #1a1a1a;}
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

<h2 id="citation">Citation</h2>
  
  <style>
    .citation-container {
      text-align: left;
      max-width: 1100px;
      margin: 0 auto;
      font-family: 'Google Sans', sans-serif;
      line-height: 1.5;
      color: #444;
      font-size: 0.95rem; /* 본문보다 살짝 작게 설정하여 학술적 느낌 부여 */
    }
    .citation-item {
      display: flex;
      gap: 15px;
      margin-bottom: 12px;
      align-items: flex-start;
    }
    .citation-number {
      font-weight: bold;
      color: #209cee; /* 번호에 포인트 컬러 적용 */
      min-width: 30px;
      text-align: right;
    }
    .citation-text {
      flex: 1;
    }
    .citation-text a {
      word-break: break-all; /* 긴 URL이 영역을 벗어나지 않도록 설정 */
    }
  </style>

  <div class="citation-container">
    <div class="citation-item">
      <div class="citation-number">[1]</div>
      <div class="citation-text">G. O. Young, ‘‘Synthetic structure of industrial plastics,’’ in <i>Plastics</i>, 2nd ed., vol. 3, J. Peters, Ed. New York, NY, USA: McGraw-Hill, 1964, pp. 15–64.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[2]</div>
      <div class="citation-text">W.-K. Chen, <i>Linear Networks and Systems</i>. Belmont, CA, USA: Wadsworth, 1993, pp. 123–135.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[3]</div>
      <div class="citation-text">J. U. Duncombe, ‘‘Infrared navigation—Part I: An assessment of feasibility,’’ <i>IEEE Trans. Electron Devices</i>, vol. ED-11, no. 1, pp. 34–39, Jan. 1959, 10.1109/TED.2016.2628402.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[4]</div>
      <div class="citation-text">E. P. Wigner, ‘‘Theory of traveling-wave optical laser,’’ <i>Phys. Rev.</i>, vol. 134, pp. A635–A646, Dec. 1965.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[5]</div>
      <div class="citation-text">E. H. Miller, ‘‘A note on reflector arrays,’’ <i>IEEE Trans. Antennas Propagat.</i>, to be published.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[6]</div>
      <div class="citation-text">E. E. Reber, R. L. Michell, and C. J. Carter, ‘‘Oxygen absorption in the earth’s atmosphere,’’ Aerospace Corp., Los Angeles, CA, USA, Tech. Rep. TR-0200 (4230-46)-3, Nov. 1988.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[7]</div>
      <div class="citation-text">J. H. Davis and J. R. Cogdell, ‘‘Calibration program for the 16-foot antenna,’’ Elect. Eng. Res. Lab., Univ. Texas, Austin, TX, USA, Tech. Memo. NGL-006-69-3, Nov. 15, 1987.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[8]</div>
      <div class="citation-text"><i>Transmission Systems for Communications</i>, 3rd ed., Western Electric Co., Winston-Salem, NC, USA, 1985, pp. 44–60.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[9]</div>
      <div class="citation-text"><i>Motorola Semiconductor Data Manual</i>, Motorola Semiconductor Products Inc., Phoenix, AZ, USA, 1989.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[10]</div>
      <div class="citation-text">G. O. Young, ‘‘Synthetic structure of industrial plastics,’’ in <i>Plastics</i>, vol. 3, <i>Polymers of Hexadromicon</i>, J. Peters, Ed., 2nd ed. New York, NY, USA: McGraw-Hill, 1964, pp. 15-64. [Online]. Available: <a href="http://www.bookref.com">http://www.bookref.com</a>.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[11]</div>
      <div class="citation-text"><i>The Founders’ Constitution</i>, Philip B. Kurland and Ralph Lerner, eds., Chicago, IL, USA: Univ. Chicago Press, 1987. [Online]. Available: <a href="http://press-pubs.uchicago.edu/founders/">http://press-pubs.uchicago.edu/founders/</a></div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[12]</div>
      <div class="citation-text"><i>The Terahertz Wave eBook</i>. ZOmega Terahertz Corp., 2014. [Online]. Available: <a href="http://dl.z-thz.com/eBook/zomegaebookpdf_1206_sr.pdf">http://dl.z-thz.com/eBook/zomegaebookpdf_1206_sr.pdf</a>. Accessed on: May 19, 2014.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[13]</div>
      <div class="citation-text">Philip B. Kurland and Ralph Lerner, eds., <i>The Founders’ Constitution</i>. Chicago, IL, USA: Univ. of Chicago Press, 1987, Accessed on: Feb. 28, 2010, [Online] Available: <a href="http://press-pubs.uchicago.edu/founders/">http://press-pubs.uchicago.edu/founders/</a></div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[14]</div>
      <div class="citation-text">J. S. Turner, ‘‘New directions in communications,’’ <i>IEEE J. Sel. Areas Commun.</i>, vol. 13, no. 1, pp. 11-23, Jan. 1995.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[15]</div>
      <div class="citation-text">W. P. Risk, G. S. Kino, and H. J. Shaw, ‘‘Fiber-optic frequency shifter using a surface acoustic wave incident at an oblique angle,’’ <i>Opt. Lett.</i>, vol. 11, no. 2, pp. 115–117, Feb. 1986.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[16]</div>
      <div class="citation-text">P. Kopyt et al., ‘‘Electric properties of graphene-based conductive layers from DC up to terahertz range,’’ <i>IEEE THz Sci. Technol.</i>, to be published. DOI: 10.1109/TTHZ.2016.2544142.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[17]</div>
      <div class="citation-text">PROCESS Corporation, Boston, MA, USA. Intranets: Internet technologies deployed behind the firewall for corporate productivity. Presented at INET96 Annual Meeting. [Online]. Available: <a href="http://home.process.com/Intranets/wp2.htp">http://home.process.com/Intranets/wp2.htp</a></div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[18]</div>
      <div class="citation-text">R. J. Hijmans and J. van Etten, ‘‘Raster: Geographic analysis and modeling with raster data,’’ R Package Version 2.0-12, Jan. 12, 2012. [Online]. Available: <a href="http://CRAN.R-project.org/package=raster">http://CRAN.R-project.org/package=raster</a></div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[19]</div>
      <div class="citation-text">Teralyzer. Lytera UG, Kirchhain, Germany [Online]. Available: <a href="http://www.lytera.de/Terahertz_THz_Spectroscopy.php?id=home">http://www.lytera.de/Terahertz_THz_Spectroscopy.php?id=home</a>, Accessed on: Jun. 5, 2014.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[20]</div>
      <div class="citation-text">U.S. House. 102nd Congress, 1st Session. (1991, Jan. 11). H. Con. Res. 1, Sense of the Congress on Approval of Military Action. [Online]. Available: LEXIS Library: GENFED File: BILLS</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[21]</div>
      <div class="citation-text">Musical toothbrush with mirror, by L. M. R. Brooks. (1992, May 19). Patent D326 189 [Online]. Available: NEXIS Library: LEXPAT File: DES</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[22]</div>
      <div class="citation-text">D. B. Payne and J. R. Stern, ‘‘Wavelength-switched passively coupled single-mode optical network,’’ in <i>Proc. IOOC-ECOC</i>, Boston, MA, USA, 1985, pp. 585–590.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[23]</div>
      <div class="citation-text">D. Ebehard and E. Voges, ‘‘Digital single sideband detection for interferometric sensors,’’ presented at the 2nd Int. Conf. Optical Fiber Sensors, Stuttgart, Germany, Jan. 2-5, 1984.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[24]</div>
      <div class="citation-text">G. Brandli and M. Dick, ‘‘Alternating current fed power supply,’’ U.S. Patent 4 084 217, Nov. 4, 1978.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[25]</div>
      <div class="citation-text">J. O. Williams, ‘‘Narrow-band analyzer,’’ Ph.D. dissertation, Dept. Elect. Eng., Harvard Univ., Cambridge, MA, USA, 1993.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[26]</div>
      <div class="citation-text">N. Kawasaki, ‘‘Parametric study of thermal and chemical nonequilibrium nozzle flow,’’ M.S. thesis, Dept. Electron. Eng., Osaka Univ., Osaka, Japan, 1993.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[27]</div>
      <div class="citation-text">A. Harrison, private communication, May 1995.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[28]</div>
      <div class="citation-text">B. Smith, ‘‘An approach to graphs of linear forms,’’ unpublished.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[29]</div>
      <div class="citation-text">A. Brahms, ‘‘Representation error for real numbers in binary computer arithmetic,’’ IEEE Computer Group Repository, Paper R-67-85.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[30]</div>
      <div class="citation-text"><i>IEEE Criteria for Class IE Electric Systems</i>, IEEE Standard 308, 1969.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[31]</div>
      <div class="citation-text"><i>Letter Symbols for Quantities</i>, ANSI Standard Y10.5-1968.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[32]</div>
      <div class="citation-text">R. Fardel, M. Nagel, F. Nuesch, T. Lippert, and A. Wokaun, ‘‘Fabrication of organic light emitting diode pixels by laser-assisted forward transfer,’’ <i>Appl. Phys. Lett.</i>, vol. 91, no. 6, Aug. 2007, Art. no. 061103.</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[33]</div>
      <div class="citation-text">J. Zhang and N. Tansu, ‘‘Optical gain and laser characteristics of InGaN quantum wells on ternary InGaN substrates,’’ <i>IEEE Photon. J.</i>, vol. 5, no. 2, Apr. 2013, Art. no. 2600111</div>
    </div>

    <div class="citation-item">
      <div class="citation-number">[34]</div>
      <div class="citation-text">S. Azodolmolky et al., ‘‘Experimental demonstration of an impairment aware network planning and operation tool for transparent/translucent optical networks,’’ <i>J. Lightw. Technol.</i>, vol. 29, no. 4, pp. 439–448, Sep. 2011.</div>
    </div>
  </div>
