<!--
  ╔══════════════════════════════════════════════════════════════════╗
  ║         OMKAR PATEL — GitHub Profile README                     ║
  ║         github.com/omkarpatelok                                  ║
  ║                                                                  ║
  ║  SETUP CHECKLIST (one-time):                                     ║
  ║  1. Create repo named exactly: omkarpatelok                      ║
  ║  2. Add this file as README.md                                   ║
  ║  3. For contribution snake:                                      ║
  ║     - Go to Actions tab → New workflow                           ║
  ║     - Create snake.yml (template below in comments)              ║
  ║  4. Replace YOUR_VERCEL_LINKS if any changed                     ║
  ╚══════════════════════════════════════════════════════════════════╝
-->

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    HERO BANNER                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <!-- Main background gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#080c18;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0d1526;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0a0818;stop-opacity:1" />
    </linearGradient>
    <!-- Blue accent glow -->
    <radialGradient id="blueGlow" cx="30%" cy="50%" r="45%">
      <stop offset="0%" style="stop-color:#1e40af;stop-opacity:0.35" />
      <stop offset="100%" style="stop-color:#1e40af;stop-opacity:0" />
    </radialGradient>
    <!-- Purple accent glow -->
    <radialGradient id="purpleGlow" cx="75%" cy="40%" r="40%">
      <stop offset="0%" style="stop-color:#7c3aed;stop-opacity:0.3" />
      <stop offset="100%" style="stop-color:#7c3aed;stop-opacity:0" />
    </radialGradient>
    <!-- Text gradient for name -->
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#60a5fa" />
      <stop offset="50%" style="stop-color:#a78bfa" />
      <stop offset="100%" style="stop-color:#38bdf8" />
    </linearGradient>
    <!-- Subtle line gradient -->
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0" />
      <stop offset="30%" style="stop-color:#3b82f6;stop-opacity:0.8" />
      <stop offset="70%" style="stop-color:#8b5cf6;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:0" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="280" fill="url(#bg)" rx="12"/>
  <rect width="900" height="280" fill="url(#blueGlow)" rx="12"/>
  <rect width="900" height="280" fill="url(#purpleGlow)" rx="12"/>

  <!-- Grid lines — subtle -->
  <g opacity="0.06" stroke="#60a5fa" stroke-width="0.5">
    <line x1="0" y1="56" x2="900" y2="56"/>
    <line x1="0" y1="112" x2="900" y2="112"/>
    <line x1="0" y1="168" x2="900" y2="168"/>
    <line x1="0" y1="224" x2="900" y2="224"/>
    <line x1="150" y1="0" x2="150" y2="280"/>
    <line x1="300" y1="0" x2="300" y2="280"/>
    <line x1="450" y1="0" x2="450" y2="280"/>
    <line x1="600" y1="0" x2="600" y2="280"/>
    <line x1="750" y1="0" x2="750" y2="280"/>
  </g>

  <!-- Decorative hexagons — right side -->
  <g opacity="0.12" stroke="#8b5cf6" stroke-width="1" fill="none">
    <polygon points="760,40 785,27 810,40 810,66 785,79 760,66" />
    <polygon points="800,80 820,69 840,80 840,102 820,113 800,102" />
    <polygon points="730,100 750,89 770,100 770,122 750,133 730,122" />
    <polygon points="845,30 860,22 875,30 875,46 860,54 845,46" />
  </g>

  <!-- Decorative circuit nodes — left side -->
  <g opacity="0.15">
    <circle cx="60" cy="80" r="3" fill="#3b82f6"/>
    <circle cx="60" cy="80" r="8" fill="none" stroke="#3b82f6" stroke-width="0.8"/>
    <line x1="68" y1="80" x2="100" y2="80" stroke="#3b82f6" stroke-width="0.8"/>
    <circle cx="100" cy="80" r="2.5" fill="#3b82f6"/>
    <line x1="100" y1="80" x2="100" y2="110" stroke="#3b82f6" stroke-width="0.8"/>
    <circle cx="100" cy="110" r="2.5" fill="#60a5fa"/>
    <line x1="100" y1="110" x2="130" y2="110" stroke="#60a5fa" stroke-width="0.8"/>

    <circle cx="55" cy="200" r="3" fill="#8b5cf6"/>
    <circle cx="55" cy="200" r="8" fill="none" stroke="#8b5cf6" stroke-width="0.8"/>
    <line x1="63" y1="200" x2="95" y2="200" stroke="#8b5cf6" stroke-width="0.8"/>
    <circle cx="95" cy="200" r="2.5" fill="#a78bfa"/>
    <line x1="95" y1="192" x2="95" y2="200" stroke="#a78bfa" stroke-width="0.8"/>
  </g>

  <!-- Accent line above name -->
  <rect x="200" y="68" width="500" height="1.5" fill="url(#lineGrad)" rx="1"/>

  <!-- MAIN NAME -->
  <text
    x="450" y="135"
    font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    font-size="58"
    font-weight="800"
    letter-spacing="2"
    text-anchor="middle"
    fill="url(#nameGrad)"
    filter="url(#softGlow)"
  >OMKAR PATEL</text>

  <!-- Role tags -->
  <text
    x="450" y="168"
    font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    font-size="15"
    font-weight="400"
    letter-spacing="4"
    text-anchor="middle"
    fill="#94a3b8"
  >AI BUILDER  ·  FULL STACK DEVELOPER  ·  PRODUCT ENGINEER</text>

  <!-- Accent line below roles -->
  <rect x="250" y="180" width="400" height="1" fill="url(#lineGrad)" rx="1" opacity="0.6"/>

  <!-- Tagline -->
  <text
    x="450" y="215"
    font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif"
    font-size="14"
    font-weight="300"
    letter-spacing="1"
    text-anchor="middle"
    fill="#64748b"
    font-style="italic"
  >Building Products That Solve Real Problems</text>

  <!-- Bottom accent dots -->
  <circle cx="390" cy="248" r="2.5" fill="#3b82f6" opacity="0.6"/>
  <circle cx="405" cy="248" r="2.5" fill="#8b5cf6" opacity="0.6"/>
  <circle cx="420" cy="248" r="2.5" fill="#38bdf8" opacity="0.6"/>
  <circle cx="450" cy="248" r="4" fill="#60a5fa" opacity="0.9" filter="url(#glow)"/>
  <circle cx="480" cy="248" r="2.5" fill="#38bdf8" opacity="0.6"/>
  <circle cx="495" cy="248" r="2.5" fill="#8b5cf6" opacity="0.6"/>
  <circle cx="510" cy="248" r="2.5" fill="#3b82f6" opacity="0.6"/>

  <!-- Border glow -->
  <rect x="1" y="1" width="898" height="278" rx="11"
    fill="none" stroke="url(#lineGrad)" stroke-width="1" opacity="0.4"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              PROFILE VIEWS + SOCIAL ROW                -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=omkarpatelok&style=for-the-badge&color=1e40af&labelColor=0d1526&label=PROFILE+VIEWS)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-omkarpatel.in-3b82f6?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1526)](https://omkarpatel.in)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1526)](https://www.linkedin.com/in/omkaarrr/)

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--               PROFESSIONAL INTRODUCTION                -->
<!-- ═══════════════════════════════════════════════════════ -->

<img align="right" width="180" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="coding gif"/>

### Hey, I'm Omkar 👋

I'm a **Computer Science student** at MIT World Peace University, Pune — specializing in **Cybersecurity**, building things at the intersection of **AI, full-stack engineering, and product design**.

I don't just learn technologies — I ship products with them. Every project in my portfolio is **deployed, live, and built to solve a real problem**.

Right now I'm focused on:
- 🤖 Building AI-powered developer tools
- ⚡ Real-time backend systems and event-driven architectures
- 🎨 UI/UX design that makes complex products feel simple
- ☁️ Cloud-native applications on AWS and Oracle OCI

> *I think like an engineer, design like a product manager, and ship like a founder.*

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ABOUT ME                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🧭 About Me

```typescript
const omkar = {
  location:     "Pune, India 🇮🇳",
  education:    "B.Tech CSE (Cybersecurity) @ MIT-WPU",
  currentYear:  "2nd Year → Building toward Sem VII",
  focus:        ["Full Stack", "AI Integration", "UI/UX", "Cloud"],
  techPhilophy: "Ship fast. Iterate. Make it beautiful.",
  interests:    ["SaaS Products", "AI Tools", "Open Source", "Startups"],
  lifeGoal:     "Build a globally impactful tech product",
  funFact:      "I redesigned a company's SaaS product before interviewing there 🎯"
};
```

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  CURRENT FOCUS                         -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🎯 Current Focus

<table>
<tr>
<td width="50%">

**🔨 Building**
- AI-powered web applications
- Real-time event-driven backends
- SaaS product UI/UX design systems

</td>
<td width="50%">

**📖 Learning**
- TypeScript & advanced React patterns
- System design & scalable architecture
- Cloud infrastructure (AWS, OCI)

</td>
</tr>
<tr>
<td width="50%">

**🎯 Targeting**
- Full Stack & AI Engineering roles
- Startup & product-focused internships
- Oracle OCI Certified ✅ | Score: **95%**

</td>
<td width="50%">

**💡 Exploring**
- Open source contributions
- Developer tooling & DX
- AI-assisted development workflows

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   TECH STACK                           -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🛠️ Tech Stack

<div align="center">

**Languages**

[![Skills](https://skillicons.dev/icons?i=js,python,cpp,java&theme=dark)](https://skillicons.dev)

**Frontend**

[![Skills](https://skillicons.dev/icons?i=react,vite,html,css,figma&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![Skills](https://skillicons.dev/icons?i=nodejs,express,flask,fastapi,postgres,mongodb,sqlite&theme=dark)](https://skillicons.dev)

**Cloud & Tools**

[![Skills](https://skillicons.dev/icons?i=aws,git,github,vercel,vscode,postman&theme=dark)](https://skillicons.dev)

**AI & APIs**

![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![SpaCy](https://img.shields.io/badge/SpaCy_NER-09A3D5?style=flat-square&logo=spacy&logoColor=white)
![LangChain](https://img.shields.io/badge/LLM_Integration-00A67E?style=flat-square&logo=openai&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                FEATURED PROJECTS                       -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ✍️ [Rewrite AI](https://rewrite-ai.vercel.app)
**AI-Powered Text Rewriting Tool**

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)

Full-stack AI application with real-time LLM streaming, tone selector (formal/casual/professional/creative), and zero loading states. Reduced rewriting time by **70%**.

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶-3b82f6?style=flat-square)](https://rewrite-ai.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/omkarpatelok/ReWrite_AI)

</td>
<td width="50%" valign="top">

### ⚡ [Real-Time DB Notifications](https://github.com/omkarpatelok/apt-assignment)
**PostgreSQL → WebSocket Push Pipeline**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

Eliminated polling entirely with PostgreSQL `LISTEN/NOTIFY` + DB triggers. Evaluated 3 architectural approaches with documented trade-offs. Built as a company technical assignment.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/omkarpatelok/apt-assignment)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 [Sciqus AMS Redesign](https://sciqus-redesign.vercel.app)
**SaaS Product UI/UX Case Study**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Independently analysed a live SaaS product, identified UX gaps, and shipped a complete redesign — before ever interviewing at the company. Improved CTA hierarchy, visual flow, and mobile responsiveness.

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶-3b82f6?style=flat-square)](https://sciqus-redesign.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/omkarpatelok/sciqus-redesign)

</td>
<td width="50%" valign="top">

### 🌧️ [RTRWH Assist](https://rtrwh-assist.vercel.app)
**Smart Rainwater Harvesting Tool**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Maps API](https://img.shields.io/badge/Google_Maps_API-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

SIH 2025 submission — civic tech web app with interactive polygon-based roof mapping, rainfall data for 100+ cities, multilingual UI, and automated PDF reports. Iterated to **v15** prototype.

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶-3b82f6?style=flat-square)](https://rtrwh-assist.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/omkarpatelok/RTRWH_Assist)

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--             AI & SECURITY PROJECTS                     -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🤖 AI & Security Engineering

<details>
<summary><b>🛡️ AI Cloud Data Security Scanner</b> — Click to expand</summary>

<br/>

> **Cloud-native PII detection platform for AWS S3** — Enterprise-grade, multi-layer data classification pipeline.

**Tech Stack:** Java 21 · Spring Boot · Python · FastAPI · SpaCy NER · HuggingFace BART · AWS S3 · Apache Tika/PDFBox

**What it does:**
- Scans **15+ file formats** (PDF, Office, images via OCR, binary) in AWS S3
- **3-layer detection:** Regex patterns → SpaCy Named Entity Recognition → BART zero-shot AI classification
- Composite **risk scoring 0–100** across 4 tiers (CRITICAL / HIGH / MEDIUM / LOW)
- **Auto-quarantines** critical-risk files (score ≥ 70) to a secure S3 bucket
- Real-time **glassmorphism SPA dashboard** with KPI cards, audit logs, scan history
- Circuit breaker + graceful degradation if AI services are down

**Architecture:**
```
S3 Upload → Content Extraction → Regex Engine → SpaCy NER → BART Classifier
         → Risk Scoring → Policy Engine → Quarantine / Audit Log → Dashboard
```

[![GitHub](https://img.shields.io/badge/GitHub-View_Code-181717?style=flat-square&logo=github)](https://github.com/omkarpatelok/ai-cloud-data-security)

</details>

<details>
<summary><b>🔐 PUF-Based IoT Authentication System</b> — Click to expand</summary>

<br/>

> **Hardware fingerprint authentication for IoT devices** — Prevents device cloning using Physical Unclonable Functions.

**Tech Stack:** ESP32 · Python · Flask · SQLite · HMAC-SHA256 · MQTT

**What it does:**
- Each ESP32 generates a unique hardware fingerprint (PUF) — unclonable by design
- Server issues challenges; device responds using its fingerprint
- **100% authentication accuracy** across enrolled devices
- Real-time Flask admin dashboard with live auth event monitoring
- Full audit trail in SQLite database

[![GitHub](https://img.shields.io/badge/GitHub-View_Code-181717?style=flat-square&logo=github)](https://github.com/sujay3806/puf-auth-server)

</details>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  GITHUB STATS                          -->
<!-- ═══════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=omkarpatelok&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1526&title_color=60a5fa&icon_color=a78bfa&text_color=94a3b8&ring_color=3b82f6&include_all_commits=true&count_private=true" alt="Omkar's GitHub Stats"/>
&nbsp;&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omkarpatelok&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1526&title_color=60a5fa&text_color=94a3b8&langs_count=8" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=omkarpatelok&theme=tokyonight&hide_border=true&background=0d1526&stroke=3b82f6&ring=60a5fa&fire=a78bfa&currStreakLabel=60a5fa&sideLabels=94a3b8&dates=64748b&currStreakNum=e2e8f0&sideNums=e2e8f0" alt="GitHub Streak"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--           CONTRIBUTION SNAKE ANIMATION                 -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🐍 Contribution Activity

<div align="center">

<!--
  TO ENABLE THE SNAKE ANIMATION:
  1. Go to your profile repo (omkarpatelok) → Actions → New Workflow
  2. Create .github/workflows/snake.yml with this content:

  name: Generate Contribution Snake
  on:
    schedule:
      - cron: "0 0 * * *"
    workflow_dispatch:
  jobs:
    build:
      runs-on: ubuntu-latest
      steps:
        - uses: actions/checkout@v3
        - uses: Platane/snk/svg-only@v3
          with:
            github_user_name: omkarpatelok
            outputs: |
              dist/github-snake.svg?palette=github-dark
              dist/github-snake-dark.svg?palette=github-dark&color_snake=a78bfa
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  3. Then uncomment the img tag below and delete this comment block
-->

![Snake animation](https://raw.githubusercontent.com/omkarpatelok/omkarpatelok/output/github-snake-dark.svg)

<!-- FALLBACK if snake isn't set up yet — remove this line once snake works -->
<!-- ![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=omkarpatelok&theme=react-dark&hide_border=true&bg_color=0d1526&color=60a5fa&line=3b82f6&point=a78bfa) -->

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--               LEARNING JOURNEY                         -->
<!-- ═══════════════════════════════════════════════════════ -->

## 📈 Learning Journey

```
2023  ──────────────────────────────────────────────────────────────────
      Started B.Tech CSE (Cybersecurity) @ MIT-WPU
      ↓ First web projects — HTML/CSS/JS fundamentals

2024  ──────────────────────────────────────────────────────────────────
      ↓ Python + Flask — backend development
      ↓ React 18 — component-driven frontend
      ↓ Image Encryption Tool (first team project shipped)
      ↓ PUF IoT Authentication — hardware + software integration

2025  ──────────────────────────────────────────────────────────────────
      ↓ Google Cloud Arcade — 40+ badges, cloud infrastructure
      ↓ SIH 2025 — RTRWH Assist, Google Maps API, multilingual UI
      ↓ PostgreSQL, WebSockets, real-time systems

2026  ──────────────────────────────────────────────────────────────────
      ↓ Oracle OCI Certified (95% score) 🏆
      ↓ Rewrite AI — Full-stack React + Gemini API + real-time streaming
      ↓ AI Cloud Security Scanner — Java/Spring Boot + AI microservices
      ↓ Figma UI/UX Design Essentials Certified
      ↓ Company technical assignments (APT, Sciqus) — production-ready code

NOW   ──────────────────────────────────────────────────────────────────
      → TypeScript, System Design, Open Source, Startup Products
```

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--          CERTIFICATIONS & ACHIEVEMENTS                 -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🏆 Certifications & Achievements

<table>
<tr>
<td align="center" width="25%">

**☁️ Oracle OCI**
Foundations Associate 2025
`Score: 95%` ✨
Valid until Apr 2028

</td>
<td align="center" width="25%">

**🎨 Figma**
UI/UX Design Essentials
Udemy Certified
Apr 2026

</td>
<td align="center" width="25%">

**☁️ Google Cloud**
Arcade Challenge 2025
`40+ Badges`
100+ Hands-on Labs

</td>
<td align="center" width="25%">

**🏫 SIH 2025**
Smart India Hackathon
University Internal
Team CodeSMOS

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                ALL PROJECTS GRID                       -->
<!-- ═══════════════════════════════════════════════════════ -->

## 📦 All Projects

| Project | Stack | Live | Type |
|---|---|---|---|
| [Rewrite AI](https://github.com/omkarpatelok/ReWrite_AI) | React · Node · Gemini API | [▶ Live](https://rewrite-ai.vercel.app) | Solo |
| [Real-Time DB Notifications](https://github.com/omkarpatelok/apt-assignment) | Node · PostgreSQL · WebSockets | — | Solo · Assignment |
| [Sciqus AMS Redesign](https://github.com/omkarpatelok/sciqus-redesign) | HTML · CSS · JS | [▶ Live](https://sciqus-redesign.vercel.app) | Solo · Case Study |
| [Sciqus Responsive Website](https://github.com/omkarpatelok/sciqus-project) | HTML · CSS · Vanilla JS | [▶ Live](https://sciqus-project.vercel.app) | Solo · Assignment |
| [RTRWH Assist](https://github.com/omkarpatelok/RTRWH_Assist) | JS · Google Maps API · Python | [▶ Live](https://rtrwh-assist.vercel.app) | Team · SIH 2025 |
| [AI Cloud Security Scanner](https://github.com/omkarpatelok/ai-cloud-data-security) | Java · Spring Boot · FastAPI · AWS S3 | — | Team |
| [PUF IoT Auth](https://github.com/sujay3806/puf-auth-server) | Python · Flask · ESP32 · MQTT | — | Team |
| [Image Encryption Tool](https://github.com/omkarpatelok/Image-Steganography) | Python · Flask · JS | — | Team |

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--               CONNECT WITH ME                          -->
<!-- ═══════════════════════════════════════════════════════ -->

## 🤝 Connect With Me

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-omkarpatel.in-3b82f6?style=for-the-badge&labelColor=0d1526)](https://omkarpatel.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Omkar_Patel-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1526)](https://www.linkedin.com/in/omkaarrr/)
[![Email](https://img.shields.io/badge/Email-omkarpatelhere@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1526)](mailto:omkarpatelhere@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-@omkarpatelok-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1526)](https://github.com/omkarpatelok)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   FUN FACTS                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## ⚡ Fun Facts

- 🎯 I redesigned a company's SaaS product **before** interviewing there — and used the live URL as my portfolio piece
- 🔁 I iterated a single project to **v15** before submitting to a national hackathon
- 🤖 I build with AI APIs not just to add AI — but because it genuinely improves the product
- 🏗️ I treat every technical assignment like a real production codebase — documented, tested, deployed
- ☁️ Scored **95%** on Oracle Cloud certification — 30 points above the passing score
- 🌍 Long-term goal: build a product used by people in 10+ countries

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--               PROFESSIONAL QUOTE                       -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

---

*"The best way to predict the future is to build it."*

**— Alan Kay**

---

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     FOOTER                             -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg viewBox="0 0 900 60" xmlns="http://www.w3.org/2000/svg" width="100%">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#080c18;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#0d1526;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#080c18;stop-opacity:1"/>
    </linearGradient>
    <linearGradient id="footerLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0"/>
      <stop offset="50%" style="stop-color:#8b5cf6;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="60" fill="url(#footerBg)" rx="8"/>
  <rect x="0" y="0" width="900" height="1.5" fill="url(#footerLine)"/>
  <text x="450" y="35" font-family="'Segoe UI', Arial, sans-serif" font-size="13"
    text-anchor="middle" fill="#475569" letter-spacing="2">
    BUILT WITH PASSION · SHIPPED WITH PURPOSE
  </text>
  <text x="450" y="52" font-family="'Segoe UI', Arial, sans-serif" font-size="10"
    text-anchor="middle" fill="#334155" letter-spacing="1">
    © 2026 Omkar Patel · Pune, India
  </text>
</svg>

</div>
