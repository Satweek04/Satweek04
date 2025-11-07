<!--
  README for GitHub profile: Satweek04
  Animated Classic design | Dark Green (#013220) + Black (#000000)
-->

<div align="center">

<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner">

  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#013220"/>
      <stop offset="100%" stop-color="#00190f"/>
    </linearGradient>

    <!-- =====================
         SVG FILTERS & GRADIENTS
         ===================== -->
    <!-- Soft glow filter -->
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Shimmer gradient for subtitle -->
    <linearGradient id="shimmer" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#c8f7dc" stop-opacity="0.1">
        <animate attributeName="offset" values="-0.3;1.3" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#b8f2d6" stop-opacity="0.9">
        <animate attributeName="offset" values="0;1.3" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#c8f7dc" stop-opacity="0.1">
        <animate attributeName="offset" values="0.3;1.6" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Text shadow for depth -->
    <filter id="textShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feOffset dx="2" dy="2" result="offset"/>
      <feGaussianBlur in="offset" stdDeviation="2" result="blurred"/>
      <feBlend in="SourceGraphic" in2="blurred" mode="normal"/>
    </filter>

    <!-- Clip path for subtitle reveal -->
    <clipPath id="revealClip">
      <rect id="revealRect" x="0" y="-30" width="0" height="60">
        <animate attributeName="width" from="0" to="780" dur="2.5s" begin="0.6s" fill="freeze"/>
      </rect>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="1200" height="220" fill="url(#bgGrad)"/>

  <!-- Glowing separator -->
  <rect x="60" y="150" rx="4" ry="4" width="1080" height="6" fill="#000000" filter="url(#softGlow)">
    <animate attributeName="width" from="0" to="1080" dur="1.2s" begin="0.5s" fill="freeze"/>
  </rect>

  <!-- Name -->
  <text x="60" y="70" font-family="'Times New Roman', Georgia, serif" font-size="42" fill="#e6f6ef" filter="url(#textShadow)" opacity="0">
    <tspan>
      <animate attributeName="y" from="110" to="70" dur="0.8s" begin="0.2s" fill="freeze"/>
      <animate attributeName="opacity" from="0" to="1" dur="0.8s" begin="0.2s" fill="freeze"/>
      Subham Swateek Panigrahi
    </tspan>
  </text>

  <!-- Subtitle -->
  <g transform="translate(60,94)" clip-path="url(#revealClip)">
    <text x="0" y="20" font-family="Georgia, serif" font-size="20" fill="#e6f6ef">
      Aspiring Software Engineer • Full Stack & Frontend Developer
    </text>
    <text x="0" y="20" font-family="Georgia, serif" font-size="20" fill="url(#shimmer)" opacity="0.9">
      Aspiring Software Engineer • Full Stack & Frontend Developer
    </text>
  </g>
</svg>

**Classic • Minimal • Professional**

</div>

---

## 🧑‍💻 About Me
Hi there — I'm **Subham Swateek Panigrahi**, an aspiring **Software Engineer** focused on **Full Stack** and **Frontend** engineering.  
I build reliable, maintainable, and efficient web applications with attention to UI/UX and security.

📍 Odisha, India · ✉️ subhamswateek@gmail.com · 📞 +91 9178652323

---

## 🎓 Education
**SOA University, Bhubaneswar** — Master of Computer Applications *(2024–2026)*  
**Sri Aurobindo Science College, Cuttack** — Intermediate (Science, 81%)

---

## 🧠 Skills (animated icons)
<div align="center">

<svg width="760" height="90" viewBox="0 0 760 90" xmlns="http://www.w3.org/2000/svg">
  <g transform="translate(10,10)">
    <circle cx="36" cy="36" r="28" fill="#001f14">
      <animate attributeName="r" values="26;30;26" dur="3s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" text-anchor="middle" fill="#e6f6ef" font-size="12">JS</text>
    <text x="36" y="64" text-anchor="middle" fill="#9fbfa6" font-size="9">JavaScript</text>
  </g>
  <g transform="translate(120,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;28;24" dur="3s" begin="0.4s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" text-anchor="middle" fill="#e6f6ef" font-size="12">TS</text>
    <text x="36" y="64" text-anchor="middle" fill="#9fbfa6" font-size="9">TypeScript</text>
  </g>
  <g transform="translate(230,10)">
    <circle cx="36" cy="36" r="26" fill="#001f14">
      <animate attributeName="r" values="24;29;24" dur="3s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
    <text x="36" y="42" text-anchor="middle" fill="#e6f6ef" font-size="12">SQL</text>
    <text x="36" y="64" text-anchor="middle" fill="#9fbfa6" font-size="9">Databases</text>
  </g>
</svg>

</div>

---

## 📊 Dynamic GitHub Graphs
<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Satweek04&show_icons=true&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Satweek04&layout=compact&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)
![GitHub Streak](https://streak-stats.demolab.com?user=Satweek04&theme=dark-green&ring=00ff88&fire=00ff88&currStreakLabel=00ff88)

</div>

---

## 🧩 Projects
- **Student’s Performance Tracker** — Full-stack system managing 500+ student records with SQL optimization.  
- **Weather Detector** — Real-time weather app with API integration and responsive design.  
- **Frontend Dashboard** — Internship project at *Preppright Edutech Pvt. Ltd.* improving UI/UX efficiency by ~40%.

---

## 🪪 Certifications
- Python Programming Certificate  
- Cybersecurity Fundamentals Certificate

---

## 🌱 Building
- Full-stack apps with focus on performance and secure APIs.  
- Modern front-end patterns and accessibility.

---

## 🤝 Connect
<p align="center">
  <a href="mailto:subhamswateek@gmail.com"><img src="https://img.shields.io/badge/Email-darkgreen?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Satweek04"><img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-darkgreen?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

<div align="center">
  <small style="font-family:'Georgia',serif;color:#9fbfa6;">Designed with ❤️ using Dark Green (#013220) & Black (#000000)</small>
</div>
