<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Ujin Kim | AI & Security</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
        "Noto Sans KR", sans-serif;
      background: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
    }

    a {
      color: #58a6ff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .container {
      width: min(900px, 90%);
      margin: 0 auto;
      padding: 80px 0;
    }

    /* Profile */

    .profile {
      display: flex;
      align-items: center;
      gap: 32px;
      margin-bottom: 64px;
    }

    .avatar {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #30363d;
      background: #161b22;
    }

    .profile-info h1 {
      font-size: 42px;
      color: #f0f6fc;
      margin-bottom: 5px;
    }

    .profile-info .username {
      color: #8b949e;
      font-size: 20px;
      margin-bottom: 20px;
    }

    .profile-info p {
      max-width: 600px;
      font-size: 17px;
    }

    .links {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
      margin-top: 20px;
    }

    .button {
      display: inline-block;
      padding: 8px 14px;
      border: 1px solid #30363d;
      border-radius: 6px;
      background: #21262d;
      color: #f0f6fc;
      transition: 0.2s;
    }

    .button:hover {
      background: #30363d;
      text-decoration: none;
    }

    /* Sections */

    section {
      margin-bottom: 56px;
    }

    section h2 {
      color: #f0f6fc;
      font-size: 24px;
      padding-bottom: 10px;
      margin-bottom: 24px;
      border-bottom: 1px solid #21262d;
    }

    /* Tech Stack */

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .tag {
      padding: 6px 12px;
      border-radius: 20px;
      background: #161b22;
      border: 1px solid #30363d;
      font-size: 14px;
    }

    /* Projects */

    .projects {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 16px;
    }

    .project {
      padding: 20px;
      background: #0d1117;
      border: 1px solid #30363d;
      border-radius: 8px;
      transition: 0.2s;
    }

    .project:hover {
      border-color: #58a6ff;
      transform: translateY(-2px);
    }

    .project h3 {
      color: #58a6ff;
      margin-bottom: 8px;
    }

    .project p {
      color: #8b949e;
      font-size: 14px;
      margin-bottom: 16px;
    }

    .project-stack {
      font-size: 13px;
      color: #7ee787;
    }

    /* Experience */

    .timeline-item {
      margin-bottom: 25px;
    }

    .timeline-item h3 {
      color: #f0f6fc;
      font-size: 18px;
    }

    .timeline-item .date {
      color: #8b949e;
      font-size: 14px;
      margin-bottom: 5px;
    }

    /* Footer */

    footer {
      text-align: center;
      color: #484f58;
      border-top: 1px solid #21262d;
      padding-top: 30px;
      margin-top: 60px;
      font-size: 14px;
    }

    @media (max-width: 700px) {
      .profile {
        flex-direction: column;
        align-items: flex-start;
      }

      .profile-info h1 {
        font-size: 34px;
      }

      .projects {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

<div class="container">

  <!-- Profile -->
  <header class="profile">

    <!--
      profile.jpg를 index.html과 같은 폴더에 넣으면 됨.
      GitHub 프로필 이미지 URL을 직접 넣어도 됨.
    -->
    <img
      class="avatar"
      src="profile.jpg"
      alt="Profile Image"
    />

    <div class="profile-info">

      <h1>Ujin Kim</h1>

      <div class="username">
        AI · Security · Systems
      </div>

      <p>
        AI와 System Security의 접점에 관심을 가지고 있습니다.
        AI-enabled Security, Secure AI Systems,
        Compiler 및 Low-level Systems 분야를 공부하고 있습니다.
      </p>

      <div class="links">

        <a
          class="button"
          href="https://github.com/YOUR_USERNAME"
          target="_blank"
        >
          GitHub
        </a>

        <a
          class="button"
          href="mailto:your@email.com"
        >
          Email
        </a>

        <a
          class="button"
          href="#projects"
        >
          Projects
        </a>

      </div>

    </div>
  </header>


  <!-- About -->
  <section>

    <h2>About Me</h2>

    <p>
      안녕하세요. AI Software를 전공하고 있는 김우진입니다.
    </p>

    <br>

    <p>
      Computer Vision, NLP 등의 AI 프로젝트를 수행하면서
      AI 기술 자체뿐만 아니라 이를 실제 시스템에 안전하게 적용하는 문제에
      관심을 가지게 되었습니다.
    </p>

    <br>

    <p>
      현재는 <strong>AI for Security</strong>와
      <strong>Security for AI</strong>를 중심으로
      System Security, AI Agent Security,
      Compiler 및 NPU 관련 기술을 공부하고 있습니다.
    </p>

  </section>


  <!-- Interests -->
  <section>

    <h2>Research Interests</h2>

    <div class="tags">

      <span class="tag">AI for Security</span>
      <span class="tag">Security for AI</span>
      <span class="tag">System Security</span>
      <span class="tag">AI Agent Security</span>
      <span class="tag">Compiler</span>
      <span class="tag">LLVM / MLIR</span>
      <span class="tag">NPU</span>
      <span class="tag">Program Analysis</span>
      <span class="tag">Machine Learning</span>

    </div>

  </section>


  <!-- Tech Stack -->
  <section>

    <h2>Tech Stack</h2>

    <div class="tags">

      <span class="tag">Python</span>
      <span class="tag">C / C++</span>
      <span class="tag">PyTorch</span>
      <span class="tag">Linux</span>
      <span class="tag">Docker</span>
      <span class="tag">Kubernetes</span>
      <span class="tag">FastAPI</span>
      <span class="tag">Git</span>
      <span class="tag">LLVM</span>
      <span class="tag">MLIR</span>

    </div>

  </section>


  <!-- Projects -->
  <section id="projects">

    <h2>Featured Projects</h2>

    <div class="projects">

      <div class="project">

        <h3>AI Security Research</h3>

        <p>
          AI를 활용한 보안 자동화 및 시스템 보안 연구.
          취약점 탐지, 프로그램 분석 및 자동 패치 기술에 관심을 가지고 있습니다.
        </p>

        <div class="project-stack">
          Python · Security · Program Analysis
        </div>

      </div>


      <div class="project">

        <h3>NPU / SNN Compiler</h3>

        <p>
          NIR 기반 SNN 모델을 MLIR 및 Hardware Backend로
          lowering하는 Compiler Pipeline을 공부하고 있습니다.
        </p>

        <div class="project-stack">
          MLIR · LLVM · NIR · SNN
        </div>

      </div>


      <div class="project">

        <h3>Hardware Trojan Detection</h3>

        <p>
          Graph Neural Network 기반 Hardware Trojan Detection 연구.
          회로 그래프에서 anomaly 및 malicious component를 탐지합니다.
        </p>

        <div class="project-stack">
          PyTorch · GNN · Hardware Security
        </div>

      </div>


      <div class="project">

        <h3>Financial Security AI</h3>

        <p>
          금융 및 보안 데이터를 활용한 AI 시스템과
          Retrieval-Augmented Generation 기반 서비스를 개발했습니다.
        </p>

        <div class="project-stack">
          LLM · RAG · Information Retrieval
        </div>

      </div>

    </div>

  </section>


  <!-- Experience -->
  <section>

    <h2>Experience</h2>

    <div class="timeline-item">

      <h3>Gachon University</h3>

      <div class="date">
        B.S. in AI Software
      </div>

      <p>
        Artificial Intelligence, Machine Learning,
        Computer Systems 및 Security 분야를 공부하고 있습니다.
      </p>

    </div>


    <div class="timeline-item">

      <h3>Research Experience</h3>

      <div class="date">
        AI · Security · Systems
      </div>

      <p>
        AI 연구 프로젝트와 System / Security 관련 연구를 수행하며
        다양한 실제 문제에 머신러닝 기술을 적용했습니다.
      </p>

    </div>

  </section>


  <!-- Contact -->
  <section>

    <h2>Contact</h2>

    <p>
      Research, Project 또는 Collaboration 관련 연락을 환영합니다.
    </p>

    <br>

    <p>
      GitHub:
      <a href="https://github.com/YOUR_USERNAME">
        github.com/YOUR_USERNAME
      </a>
    </p>

    <p>
      Email:
      <a href="mailto:your@email.com">
        your@email.com
      </a>
    </p>

  </section>


  <footer>
    © 2026 Ujin Kim · Built with HTML & CSS
  </footer>

</div>

</body>
</html>
