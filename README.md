<!--
  README for GitHub profile: Satweek04
  Animated Classic design | Dark Green (#013220) + Black (#000000)
  Copy this entire file into your repo's README.md
-->

<!-- =========================
     ANIMATED SVG BANNER
     Pure SVG animations (works in GitHub README)
     ========================= -->
<div align="center">

<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner">
  <!-- Definitions -->
  <defs>
    <linearGradient id="bgGrad" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#013220"/>
      <stop offset="100%" stop-color="#00190f"/>
    </linearGradient>

    <!-- Soft glow filter -->
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Shimmer gradient for subtitle -->
    <linearGradient id="shimmer" x1="0" x2="1">
      <stop offset="0%" stop-color="#e6f6ef" stop-opacity="0.12"/>
      <stop offset="50%" stop-color="#b8f2d6" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#e6f6ef" stop-opacity="0.12"/>
    </linearGradient>

    <!-- Text drop shadow -->
    <filter id="textShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feOffset dx="2" dy="2" result="offOut"/>
      <feGaussianBlur in="offOut" stdDeviation="3" result="blurOut"/>
      <feBlend in="SourceGraphic" in2="blurOut" mode="normal"/>
    </filter>

    <!-- Clip path for subtitle reveal -->
    <clipPath id="revealClip">
      <!-- width is animated via inner rect -->
      <rect id="revealRect" x="0" y="-30" width="0" height="60" />
    </clipPath>
  </defs>

  <!-- Main rectangular background -->
  <rect width="1200" height="220" fill="url(#bgGrad)"/>

  <!-- Decorative classical flourish on right -->
  <g transform="translate(960,20) scale(0.9)" opacity="0.9">
    <path d="M10 80 C 40 10, 80 10, 110 80 S 190 150, 220 80" fill="none" stroke="#000000" stroke-opacity="0.45" stroke-width="4" stroke-linecap="round"/>
    <path d="M30 100 C 70 40, 120 40, 160 100" fill="none" stroke="#0b381f" stroke-width="2" stroke-linecap="round"/>
  </g>

  <!-- Animated separator bar (glowing) -->
  <rect x="60" y="150" rx="4" ry="4" width="1080" height="6" fill="#000000" filter="url(#softGlow)" opacity="0.9">
    <animate attributeName="width" values="0;1080" dur="1.2s" begin="0.6s" fill="freeze"/>
  </rect>

  <!-- NAME: slide up + fade in -->
  <text x="60" y="70" style="font-family: 'Times New Roman', Georgia, serif; font-size:42px; fill:#e6f6ef; letter-spacing:1px; font-weight:700;" opacity="0" filter="url(#textShadow)">
    <tspan>
      <animate attributeName="y" from="110" to="70" dur="0.9s" begin="0.2s" fill="freeze"/>
      <animate attributeName="opacity" from="0" to="1" dur="0.9s" begin="0.2s" fill="freeze"/>
      Subham Swateek Panigrahi
    </tspan>
  </text>

  <!-- SUBTITLE: subtle shimmer + reveal -->
  <g transform="translate(60,94)">
    <!-- subtitle text visible through clip path -->
    <g clip-path="url(#revealClip)">
      <text x="0" y="20" style="font-family: Georgia, serif; font-size:20px; fill:#e6f6ef;">
        <tspan>Aspiring Software Engineer • Full Stack & Frontend Developer</tspan>
      </text>
      <!-- shimmer overlay (slightly lighter) -->
      <text x="0" y="20" style="font-family: Georgia, serif; font-size:20px; fill:url(#shimmer); opacity:0.8;">
        <tspan>Aspiring Software Engineer • Full Stack & Frontend Developer</tspan>
      </text>
    </g>

    <!-- animate the clip rect width (reveal effect) -->
    <animate xlink:href="#revealRect" attributeName="width" from="0" to="780" dur="2.4s" begin="0.6s" fill="freeze" />
  </g>

  <!-- subtle caret blink (animated rect that moves with reveal) -->
  <rect id="caret" x="10" y="-6" width="6" height="18" fill="#e6f6ef" opacity="0">
    <animate attributeName="opacity" values="0;1;0" dur="1s" begin="2.6s" repeatCount="indefinite"/>
    <animate attributeName="x" values="10;760" dur="2.4s" begin="0.6s" fill="freeze"/>
    <set attributeName="opacity" to="0" begin="0" />
  </rect>

  <!-- Small embellishing dots that bounce -->
  <g transform="translate(60,160)">
    <circle cx="0" cy="0" r="5" fill="#00ff88" opacity="0">
      <animate attributeName="cy" values="0;-8;0" dur="1.2s" begin="1.1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="1.2s" begin="1.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="28" cy="0" r="4" fill="#9fe8c0" opacity="0">
      <animate attributeName="cy" values="0;-10;0" dur="1s" begin="1.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="1s" begin="1.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="52" cy="0" r="3.2" fill="#d6f9ea" opacity="0">
      <animate attributeName="cy" values="0;-6;0" dur="1.4s" begin="1.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;0" dur="1.4s" begin="1.2s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

<!-- Tagline -->
<div style="margin-top:8px;">
  <strong style="color:#e6f6ef; font-family: Georgia, serif;">Classic • Minimal • Professional</strong>
</div>

</div>

---

# 🧑‍💻 About Me
Hi there — I'm **Subham Swateek Panigrahi**, an aspiring **Software Engineer** focused on **Full Stack** and **Frontend** engineering.  
I build reliable, maintainable, and efficient web applications with attention to UI/UX and security.

📍 Odisha, India · ✉️ subhamswateek@gmail.com · 📞 +91 9178652323

---

# 🎓 Education
**SOA University, Bhubaneswar** — Master of Computer Applications *(2024–2026)*  
**Sri Aurobindo Science College, Cuttack** — Intermediate (Science, 81%)

---

# 🧠 Skills (animated icons)
<div align="center">

<!-- Simple inline SVG "skill tokens" with subtle pulse animation -->
<svg width="760" height="90" viewBox="0 0 760 90" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="skills">
  <!-- Token 1 -->
  <g transform="translate(10,10)">
    <circle cx="36" cy="36" r="28" fill="#001f14">
      <animate attributeName="r" values="26;30;26" dur="3.6s" begin="0.4s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">JS</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">JavaScript</text>
  </g>

  <!-- Token 2 -->
  <g transform="translate(120,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;28;24" dur="3.2s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">TS</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">TypeScript</text>
  </g>

  <!-- Token 3 -->
  <g transform="translate(230,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;29;24" dur="4s" begin="1.2s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">SQL</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">Databases</text>
  </g>

  <!-- Token 4 -->
  <g transform="translate(340,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;27;24" dur="3s" begin="1.6s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">Node</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">Node.js</text>
  </g>

  <!-- Token 5 -->
  <g transform="translate(450,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;29;24" dur="3.8s" begin="2.0s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">HTML</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">HTML5</text>
  </g>

  <!-- Token 6 -->
  <g transform="translate(560,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;28;24" dur="3.4s" begin="2.4s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" font-family="Arial, sans-serif" font-size="12" fill="#e6f6ef" text-anchor="middle">CSS</text>
    <text x="36" y="64" font-family="Georgia, serif" font-size="9" fill="#9fbfa6" text-anchor="middle">CSS3</text>
  </g>
</svg>

</div>

---

# 📊 Dynamic GitHub Graphs
*These cards are live — they update automatically (powered by third-party GitHub-readme-stats services). They respect a dark look to match the theme.*

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Satweek04&show_icons=true&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)

<br/>

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Satweek04&layout=compact&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=Satweek04&theme=dark-green&ring=00ff88&fire=00ff88&currStreakLabel=00ff88)

</div>

---

# 🧩 Selected Projects
- **Student’s Performance Tracker** — Full-stack system managing 500+ student records with SQL optimization.  
- **Weather Detector** — Real-time weather app with API integration and responsive design.  
- **Frontend Dashboard** — Internship project at *Preppright Edutech Pvt. Ltd.* improving UI/UX efficiency by ~40%.

---

# 🪪 Certifications
- Python Programming Certificate  
- Cybersecurity Fundamentals Certificate

---

# 🌱 What I'm building
- Production-grade full-stack apps with focus on performance and secure APIs.  
- Modern front-end patterns and accessible UI components.

---

# 🤝 Connect with me
<p align="center">
  <a href="mailto:subhamswateek@gmail.com"><img alt="email" src="https://img.shields.io/badge/Email-%23001320.svg?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000"></a>
  <a href="https://github.com/Satweek04"><img alt="github" src="https://img.shields.io/badge/GitHub-%23001320.svg?style=for-the-badge&logo=github&logoColor=white&labelColor=000000"></a>
  <a href="https://www.linkedin.com"><img alt="linkedin" src="https://img.shields.io/badge/LinkedIn-%23001320.svg?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000"></a>
</p>

---

<div align="center" style="margin-top:16px;">
  <small style="font-family:'Georgia', serif; color:#9fbfa6;">Designed with care • Dark Green <code>#013220</code> & Black <code>#000000</code></small>
</div>
