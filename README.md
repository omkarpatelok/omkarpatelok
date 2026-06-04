<div align="center">

<svg viewBox="0 0 820 200" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#070b14"/>
      <stop offset="100%" style="stop-color:#0c1220"/>
    </linearGradient>
    <radialGradient id="g1" cx="25%" cy="60%" r="50%">
      <stop offset="0%" style="stop-color:#1d4ed8;stop-opacity:0.25"/>
      <stop offset="100%" style="stop-color:#1d4ed8;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="g2" cx="80%" cy="35%" r="45%">
      <stop offset="0%" style="stop-color:#6d28d9;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#6d28d9;stop-opacity:0"/>
    </radialGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#60a5fa"/>
      <stop offset="55%" style="stop-color:#a78bfa"/>
      <stop offset="100%" style="stop-color:#38bdf8"/>
    </linearGradient>
    <linearGradient id="divider" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#8b5cf6;stop-opacity:0.7"/>
      <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="820" height="200" fill="url(#bg)" rx="10"/>
  <rect width="820" height="200" fill="url(#g1)" rx="10"/>
  <rect width="820" height="200" fill="url(#g2)" rx="10"/>

  <!-- subtle grid -->
  <g opacity="0.04" stroke="#60a5fa" stroke-width="0.6">
    <line x1="0" y1="50" x2="820" y2="50"/>
    <line x1="0" y1="100" x2="820" y2="100"/>
    <line x1="0" y1="150" x2="820" y2="150"/>
    <line x1="205" y1="0" x2="205" y2="200"/>
    <line x1="410" y1="0" x2="410" y2="200"/>
    <line x1="615" y1="0" x2="615" y2="200"/>
  </g>

  <!-- corner accents -->
  <path d="M 20 20 L 50 20 L 50 22 L 22 22 L 22 50 L 20 50 Z" fill="#3b82f6" opacity="0.5"/>
  <path d="M 800 20 L 770 20 L 770 22 L 798 22 L 798 50 L 800 50 Z" fill="#8b5cf6" opacity="0.5"/>
  <path d="M 20 180 L 50 180 L 50 178 L 22 178 L 22 150 L 20 150 Z" fill="#3b82f6" opacity="0.5"/>
  <path d="M 800 180 L 770 180 L 770 178 L 798 178 L 798 150 L 800 150 Z" fill="#8b5cf6" opacity="0.5"/>

  <!-- name -->
  <text x="410" y="98" font-family="'Segoe UI',Arial,sans-serif" font-size="52"
    font-weight="800" letter-spacing="3" text-anchor="middle"
    fill="url(#nameGrad)" filter="url(#glow)">OMKAR PATEL</text>

  <!-- divider line -->
  <rect x="160" y="112" width="500" height="1" fill="url(#divider)" rx="1"/>

  <!-- tagline -->
  <text x="410" y="142" font-family="'Segoe UI',Arial,sans-serif" font-size="13"
    font-weight="400" letter-spacing="4" text-anchor="middle" fill="#64748b">
    AI BUILDER · FULL STACK · PRODUCT ENGINEER
  </text>

  <!-- border -->
  <rect x="1" y="1" width="818" height="198" rx="9"
    fill="none" stroke="url(#divider)" stroke-width="0.8" opacity="0.3"/>
</svg>

<br/>

![Views](https://komarev.com/ghpvc/?username=omkarpatelok&style=flat-square&color=3b82f6&labelColor=0d1526&label=profile+views)

</div>

---

I'm a CS student at MIT-WPU building **AI-powered products**, **real-time systems**, and **thoughtful UI** — shipping things that actually work, not just demos.

Currently: Full Stack + UI/UX Internship hunting · Oracle OCI Certified (95%) · SIH 2025 participant

---

### 🛠 Stack

<div align="center">

[![Skills](https://skillicons.dev/icons?i=js,ts,python,java,cpp,react,nodejs,express,flask,postgres,mongodb,figma,aws,git,vercel&theme=dark&perline=8)](https://skillicons.dev)

</div>

---

### 🚀 Projects

<table>
<tr>
<td width="50%">

**[✍️ Rewrite AI](https://rewrite-ai.vercel.app)**
React · Node.js · Gemini API
Full-stack AI rewriting tool with real-time LLM streaming. 70% faster rewrites, zero loading states.
[Live ↗](https://rewrite-ai.vercel.app) · [Code](https://github.com/omkarpatelok/ReWrite_AI)

</td>
<td width="50%">

**[⚡ Real-Time DB Notifications](https://github.com/omkarpatelok/apt-assignment)**
Node.js · PostgreSQL · WebSockets
Push-based pipeline using `LISTEN/NOTIFY` — eliminated polling entirely. Documented 3 arch approaches.
[Code](https://github.com/omkarpatelok/apt-assignment)

</td>
</tr>
<tr>
<td width="50%">

**[🎨 Sciqus Redesign](https://sciqus-redesign.vercel.app)**
HTML · CSS · JS
Redesigned a live SaaS product's marketing site as a UX case study — before interviewing there.
[Live ↗](https://sciqus-redesign.vercel.app) · [Code](https://github.com/omkarpatelok/sciqus-redesign)

</td>
<td width="50%">

**[🌧 RTRWH Assist](https://rtrwh-assist.vercel.app)**
JS · Google Maps API · Python
SIH 2025 civic-tech app — roof polygon mapping, 100+ city rainfall data, PDF reports. v15 prototype.
[Live ↗](https://rtrwh-assist.vercel.app) · [Code](https://github.com/omkarpatelok/RTRWH_Assist)

</td>
</tr>
</table>

---

### 📊 Stats

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=omkarpatelok&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=60a5fa&icon_color=a78bfa&text_color=94a3b8&count_private=true"/>
&nbsp;
<img height="155" src="https://github-readme-streak-stats.herokuapp.com/?user=omkarpatelok&theme=tokyonight&hide_border=true&background=070b14&stroke=1e293b&ring=60a5fa&fire=a78bfa&currStreakLabel=60a5fa&sideLabels=94a3b8&dates=475569&currStreakNum=e2e8f0&sideNums=e2e8f0"/>

</div>

---

### 🏆 Achievements

| | |
|---|---|
| ☁️ Oracle OCI 2025 Foundations Associate | `95% score` · Valid until Apr 2028 |
| 🎨 Figma UI/UX Design Essentials | Udemy · Apr 2026 |
| ☁️ Google Cloud Arcade 2025 | 40+ badges · 100+ labs |
| 🏫 Smart India Hackathon 2025 | Team CodeSMOS · University Internal |

---

### 🤝 Let's connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/omkarpatel.in-0d1526?style=for-the-badge&logo=vercel&logoColor=60a5fa)](https://omkarpatel.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1526?style=for-the-badge&logo=linkedin&logoColor=60a5fa)](https://www.linkedin.com/in/omkaarrr/)
[![Email](https://img.shields.io/badge/Email-0d1526?style=for-the-badge&logo=gmail&logoColor=a78bfa)](mailto:omkarpatelhere@gmail.com)

</div>

<div align="center">
<sub>Building toward something global · Pune, India 🇮🇳</sub>
</div>
