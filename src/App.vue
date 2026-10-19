
<script setup>
import './old-style.css'
</script>

<template>
  <div class="ambient ambient-one" aria-hidden="true"></div>
  <div class="ambient ambient-two" aria-hidden="true"></div>

  <header class="site-header reveal">
    <a class="brand" href="#" aria-label="NING'S SPACE">
      <span class="brand-icon">✿</span>
      <span>NING'S SPACE</span>
    </a>

    <p class="eyebrow">
      <span class="status-dot"></span>
      PERSONAL PROFILE · AI JOURNEY
    </p>

    <h1>
      嗨，我是瑾寧！
      <span class="wave" aria-hidden="true">✿</span>
    </h1>

    <p class="intro">
      喜歡探索新知，也正在學習 AI、程式設計與電機工程。
      <br class="desktop-break" />
      希望透過每一次練習，把想法慢慢變成真正的作品。
    </p>

    <div class="hero-tags" aria-label="個人興趣標籤">
      <span class="hero-tag">AI &amp; Data</span>
      <span class="hero-tag">Engineering</span>
      <span class="hero-tag">Curious Mind</span>
    </div>
  </header>

  <main class="profile">
    <section class="card about reveal" aria-labelledby="about-title">
      <span class="card-mark mark-pink">01</span>
      <p class="card-kicker">ABOUT ME</p>
      <h2 id="about-title">關於我</h2>
      <p>
        我喜歡接觸不同領域的知識，享受從不懂到逐漸理解的過程。
        目前正一步步累積程式設計、人工智慧與工程實作的經驗。
      </p>
      <div class="card-decoration decoration-flower" aria-hidden="true">✿</div>
    </section>

    <section class="card interests reveal" aria-labelledby="interests-title">
      <span class="card-mark mark-yellow">02</span>
      <p class="card-kicker">MY INTERESTS</p>
      <h2 id="interests-title">我的興趣</h2>
      <p>
        喜歡研究 AI 新技術、閱讀論文、探索資料背後的規律，
        也喜歡把學到的知識整理成自己的筆記與作品。
      </p>
      <span class="tag">持續探索，持續成長</span>
      <div class="card-decoration decoration-star" aria-hidden="true">✦</div>
    </section>

    <section class="card skills reveal" aria-labelledby="skills-title">
      <span class="card-mark mark-blue">03</span>
      <p class="card-kicker">CURRENT EXPLORATION</p>
      <h2 id="skills-title">正在探索 AI</h2>
      <p>
        從 Python 程式設計開始，逐步學習機器學習、資料分析與
        電機工程，希望將 AI 技術應用到實際問題中。
      </p>

      <div class="tech-stack" aria-label="目前學習的技術">
        <span class="tech-chip">
          <span class="chip-dot dot-purple"></span>Python
        </span>
        <span class="tech-chip">
          <span class="chip-dot dot-pink"></span>AI / ML
        </span>
        <span class="tech-chip">
          <span class="chip-dot dot-blue"></span>Data Analysis
        </span>
        <span class="tech-chip">
          <span class="chip-dot dot-yellow"></span>Stock Research
        </span>
      </div>

      <div class="card-decoration decoration-orbit" aria-hidden="true">
        <span></span><span></span><span></span>
      </div>
    </section>

    <section class="projects reveal" aria-labelledby="projects-title">
      <div class="section-heading">
        <div>
          <p class="card-kicker">SELECTED WORK</p>
          <h2 id="projects-title">我的作品集</h2>
        </div>
        <span class="section-note">LEARN · BUILD · GROW</span>
      </div>

      <div class="project-list">
        <article class="project-card project-pink">
          <div class="project-topline">
            <span class="project-icon icon-pink" aria-hidden="true">✿</span>
            <span class="project-number">PROJECT 01</span>
          </div>

          <h3>AI Stock Analyzer</h3>
          <p>
            股票資料分析練習專案，嘗試結合 Python、資料分析與 AI，
            探索如何整理市場資訊，並從數據中尋找值得研究的方向。
          </p>

          <div class="project-footer">
            <span class="tag">Python</span>
            <span class="tag">Data Analysis</span>
            <span class="tag">Stock Research</span>
          </div>

          <a
            href="https://github.com/jinning0308/test1012/tree/main/stock-analyzer"
            class="stock-button"
            target="_blank"
            rel="noopener noreferrer"
          >
            查看專案 ↗
          </a>
        </article>

        <article class="project-card project-lavender">
          <div class="project-topline">
            <span class="project-icon icon-purple" aria-hidden="true">♡</span>
            <span class="project-number">PROJECT 02</span>
          </div>

          <h3>My First Website</h3>
          <p>
            從 HTML 與 CSS 開始製作個人網站，練習網頁結構、
            色彩搭配、卡片設計與響應式排版。
          </p>

          <div class="project-footer">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">Vue</span>
          </div>
        </article>
      </div>
    </section>

    <section class="learning-note reveal" aria-label="學習小語">
      <span class="note-icon" aria-hidden="true">♡</span>
      <p>
        <strong>Still learning, still growing.</strong>
        <br />
       
      </p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="footer-line"></div>
    <p>DESIGNED WITH <span aria-hidden="true">♡</span> BY NING</p>
    <p class="footer-small">A little space for learning and growing.</p>
  </footer>
</template>
