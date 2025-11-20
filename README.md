<!--
  README for GitHub profile repo
  - Username: natiman8634
  - Name: Natnael Samson
  - Tech: html, css, js, react, git, java, figma, mongodb
  - Includes an animated "snake" SVG and company (Netflix/Amazon) badges
-->

<!-- Intro / Header -->
<h1 align="center">Hi 👋, I'm Natnael Samson (<code>natiman8634</code>)</h1>
<p align="center">
  <a href="https://github.com/natiman8634" target="_blank"><img alt="GitHub followers" src="https://img.shields.io/github/followers/natiman8634?label=Follow&style=social"></a>
  <a href="mailto:youremail@example.com" target="_blank"><img alt="Email" src="https://img.shields.io/badge/Email-youremail%40example.com-blue?style=flat-square&logo=gmail"></a>
  <img alt="Top Langs" src="https://github-readme-stats.vercel.app/api/top-langs/?username=natiman8634&layout=compact&hide=Makefile">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=natiman8634&show_icons=true&count_private=true&line_height=21">
</p>

<!-- Animated snake (SVG data URI) -->
<p align="center">
  <!-- Snake animation (SVG embedded as data URI) -->
  <img alt="Snake animation" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="560" height="120" viewBox="0 0 560 120">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop stop-color="%2300b4ff" offset="0%"/>
        <stop stop-color="%238000ff" offset="50%"/>
        <stop stop-color="%23ff3d81" offset="100%"/>
      </linearGradient>
      <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
        <feDropShadow dx="0" dy="6" stdDeviation="6" flood-color="%23000000" flood-opacity="0.25"/>
      </filter>
    </defs>
    <rect width="100%" height="100%" rx="12" fill="%23f8fbff"/>
    <g transform="translate(20,60)">
      <path id="snake" d="M0 0 C40 -30, 120 30, 160 0 S280 -30, 320 0 S440 -30, 480 0" fill="none" stroke="url(%23g)" stroke-width="8" stroke-linecap="round" filter="url(%23shadow)"/>
      <!-- moving circle "head" -->
      <g id="head">
        <circle r="8" fill="%23fff"/>
        <circle r="5" fill="%23ff3d81">
          <animate attributeName="r" values="5;8;5" dur="1.8s" repeatCount="indefinite" />
        </circle>
      </g>
      <!-- animate head along the path -->
      <animateMotion xlink:href="#head" dur="6s" repeatCount="indefinite">
        <mpath xlink:href="#snake"/>
      </animateMotion>
    </g>
    <text x="18" y="18" font-family="Verdana" font-size="10" fill="%23666">Portfolio • natiman8634 • Natnael Samson</text>
  </svg>' />

  <br>
  <sub><i>Animated 'snake' shows activity — works in most Markdown renderers that support SVG images.</i></sub>
</p>

---

# About Me
- 👨‍💻 **Name:** Natnael Samson (`natiman8634`)  
- 🔭 **I’m working on:** React apps, full-stack projects using MongoDB & Java backends  
- 🌱 **I’m learning:** advanced React patterns, performance optimization, accessibility  
- 🎨 **Tools:** Figma for UI/UX prototypes  
- ⚙️ **Tech Stack:** HTML, CSS, JavaScript, React, Git/GitHub, Java, MongoDB, Figma

---

# Skills & Tools
| Frontend | Backend | Database | Design | VCS |
|---|---:|:---:|:---:|:---:|
| HTML · CSS · JS · React · Tailwind (optional) | Java · Node.js (if used) | MongoDB | Figma · Adobe XD | Git · GitHub |

Badges:
<p>
  <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?logo=javascript&logoColor=black" alt="JS"/>
  <img src="https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/MongoDB-%2347A248.svg?logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?logo=java&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Figma-%23F24E1E.svg?logo=figma&logoColor=white" alt="Figma"/>
</p>

---

# Featured Projects
> Replace the placeholders with your actual project links, gh-pages URLs, or demo URLs.

## 1) Netflix Clone — UI Practice
- **Tech:** React · HTML · CSS  
- **Description:** UI clone of a streaming layout with responsive cards and movie detail modal.  
- **Demo:** `[DEMO URL HERE]` — *Replace with hosted demo*  
- **Repo:** `https://github.com/natiman8634/netflix-clone` *(replace if different)*  
- **Company badge:**  
  <a href="https://www.netflix.com" target="_blank"><img alt="Netflix" src="https://img.shields.io/badge/Netflix-%20-E50914?logo=netflix&logoColor=white"></a>

## 2) Amazon-like eCommerce UI
- **Tech:** HTML · CSS · JS · React  
- **Description:** Product grid, filters, and simple cart state (client-side).  
- **Demo:** `[DEMO URL HERE]`  
- **Repo:** `https://github.com/natiman8634/amazon-ui` *(replace if different)*  
- **Company badge:**  
  <a href="https://www.amazon.com" target="_blank"><img alt="Amazon" src="https://img.shields.io/badge/Amazon-%20-FF9900?logo=amazon&logoColor=black"></a>

---

# How to use this README (quick)
1. **Copy** the whole content above into your repository's `README.md` (root of the repo named exactly like your GitHub username to appear on your profile).  
2. **Edit:** Update any links, email, demo URLs, and repo names where I put placeholders like `[DEMO URL HERE]`.  
3. **Badges / Stats:** The GitHub stats images use `natiman8634` — if your username changes, update those links.  
4. **Images & GIFs:** For project demos, add short GIFs in `/assets` in the repo and reference them with `![demo](/assets/demo.gif)`.  
5. **Hosting SVGs:** If the snake SVG ever fails to render, you can add the SVG file to the repo (e.g., `/assets/snake.svg`) and replace the data URI with `![snake](/assets/snake.svg)`.  
6. **Commit & Push:** `git add README.md && git commit -m "chore: polished portfolio readme" && git push`.

---

# Advanced enhancements (optional)
- **Profile README tabs**: use GitHub README tabs or simple JS-free tabs via anchors.  
- **Project cards**: host images & use compact card sections with GIF previews.  
- **Interactive demos**: embed CodeSandbox or StackBlitz links.  
- **Automations**: Use GitHub Actions to auto-update a "Latest blog post" section.  
- **Animated contribution graph**: use third-party services or GitHub's own graph (link to profile).  
- **Accessibility:** add alt text for every image and ensure contrast of badges.

---

# Contact
- GitHub: https://github.com/natiman8634  
- Email: youremail@example.com *(replace)*  
- LinkedIn / Portfolio: add your links here

---

*If you want, I can:*
- Replace placeholders with real demo URLs if you provide them.
- Generate the snake SVG as a standalone file and a project demo GIF or an improved animated header.
- Convert this README into a multi-file portfolio (index.html + assets) you can host on GitHub Pages.

