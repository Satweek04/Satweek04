<!--
  README for GitHub profile: Satweek04
  Animated & Classical Design | Dark Green (#013220) + Black (#000000)
-->

<div align="center">

<!-- =========================
     ANIMATED SVG BANNER
     ========================= -->
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner">

  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bgGrad" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#013220"/>
      <stop offset="100%" stop-color="#000000"/>
    </linearGradient>

    <!-- Glow Filter -->
    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Shimmer Gradient -->
    <linearGradient id="shimmer" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#aef2c9" stop-opacity="0.1">
        <animate attributeName="offset" values="-0.5;1.5" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#d9ffe7" stop-opacity="0.9">
        <animate attributeName="offset" values="0;1.5" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#aef2c9" stop-opacity="0.1">
        <animate attributeName="offset" values="0.5;2" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Text Shadow -->
    <filter id="textShadow" x="-20%" y="-20%" width="140%" height="140%">
      <feOffset dx="2" dy="2" result="off"/>
      <feGaussianBlur in="off" stdDeviation="2" result="blur"/>
      <feBlend in="SourceGraphic" in2="blur" mode="normal"/>
    </filter>

    <!-- Clip Path for Subtitle -->
    <clipPath id="revealClip">
      <rect id="revealRect" x="0" y="-30" width="0" height="60">
        <animate attributeName="width" from="0" to="780" dur="2.5s" begin="0.6s" fill="freeze"/>
      </rect>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="1200" height="220" fill="url(#bgGrad)"/>

  <!-- Animated Line -->
  <rect x="60" y="150" rx="3" ry="3" width="1080" height="4" fill="#00ff88" filter="url(#softGlow)">
    <animate attributeName="width" from="0" to="1080" dur="1.2s" begin="0.3s" fill="freeze"/>
  </rect>

  <!-- Name Animation -->
  <text x="60" y="70" font-family="'Times New Roman', Georgia, serif" font-size="42" fill="#e6f6ef" filter="url(#textShadow)" opacity="0">
    <tspan>
      <animate attributeName="y" from="100" to="70" dur="1s" begin="0.2s" fill="freeze"/>
      <animate attributeName="opacity" from="0" to="1" dur="1.5s" begin="0.2s" fill="freeze"/>
      Subham Swateek Panigrahi
    </tspan>
  </text>

  <!-- Subtitle -->
  <g transform="translate(60,94)" clip-path="url(#revealClip)">
    <text x="0" y="20" font-family="Georgia, serif" font-size="20" fill="url(#shimmer)" opacity="0.9">
      Aspiring Software Engineer • Full Stack & Frontend Developer
    </text>
  </g>
</svg>

**Classic • Elegant • Dynamic**

</div>

---

## 🧑‍💻 About Me
Hi there — I'm **Subham Swateek Panigrahi**, an aspiring **Software Engineer** passionate about **Full Stack Development** and **UI/UX excellence**.  
I build efficient, secure, and elegant digital experiences.

📍 *Odisha, India*  
✉️ *subhamswateek@gmail.com*  
📞 *+91 9178652323*  

---

## 🎓 Education
- **SOA University, Bhubaneswar** — Master of Computer Applications *(2024–2026)*  
- **Sri Aurobindo Science College, Cuttack** — Intermediate (Science, 81%)

---

## 🧠 Skills & Tools

<div align="center">

| Category | Skills |
|-----------|---------|
| 💻 **Languages** | ![JavaScript](https://img.icons8.com/color/48/javascript.png) ![TypeScript](https://img.icons8.com/color/48/typescript.png) ![Python](https://img.icons8.com/color/48/python.png) ![Java](https://img.icons8.com/color/48/java.png) |
| ⚙️ **Frameworks** | ![Node.js](https://img.icons8.com/color/48/nodejs.png) ![React](https://img.icons8.com/color/48/react-native.png) |
| 🧩 **Database & Tools** | ![MySQL](https://img.icons8.com/color/48/mysql-logo.png) ![GitHub](https://img.icons8.com/ios-glyphs/48/github.png) ![VS Code](https://img.icons8.com/color/48/visual-studio-code-2019.png) |

</div>

---

## 📊 Dynamic GitHub Graphs

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Satweek04&show_icons=true&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)
<br/>
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Satweek04&layout=compact&theme=chartreuse-dark&bg_color=000000&title_color=00ff88&text_color=ffffff)
<br/>
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

## 🌱 What I'm Building
- Secure, performance-driven full-stack apps  
- Modern, accessible front-end systems with animation & depth

---

## 🤝 Connect With Me
<p align="center">
  <a href="mailto:subhamswateek@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-%23001320.svg?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000"></a>
  <a href="https://github.com/Satweek04"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-%23001320.svg?style=for-the-badge&logo=github&logoColor=white&labelColor=000000"></a>
  <a href="https://www.linkedin.com"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%23001320.svg?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000"></a>
</p>

---

<div align="center">
  <small style="font-family:'Georgia',serif;color:#9fbfa6;">Subham Swateek Panigraphi</small>
</div>
