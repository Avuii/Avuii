<!-- Banner (umieść plik baner.png w repo, alt dla dostępności) -->
<p align="center">
  <img src="baner.png" alt="Kasia Stańczyk banner" width="100%" />
</p>

<!-- Animated SVG header (inline SVG — delikatny ruch, działa na GitHubie) -->
<p align="center">
  <svg width="680" height="140" viewBox="0 0 680 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img">
    <title>Pastel header: moon and flowers</title>
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0" stop-color="#ffd6e8"/>
        <stop offset="1" stop-color="#e6f7ff"/>
      </linearGradient>
      <filter id="f1" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="b"/>
        <feBlend in="SourceGraphic" in2="b"/>
      </filter>
      <style type="text/css"><![CDATA[
        .title { font: 700 28px/1 "Segoe UI", system-ui, -apple-system; fill: #ffb7d5; }
        .subtitle { font: 400 14px/1 "Segoe UI", system-ui; fill: #7a7a9d; }
        .moon { transform-origin: 120px 70px; animation: floatMoon 6s ease-in-out infinite; }
        .petal { transform-origin: 520px 100px; animation: sway 4s ease-in-out infinite; }
        .spark { animation: twinkle 2.4s linear infinite; opacity: 0.9; }
        @keyframes floatMoon {
          0% { transform: translateY(0) rotate(0deg); }
          50% { transform: translateY(-6px) rotate(-3deg); }
          100% { transform: translateY(0) rotate(0deg); }
        }
        @keyframes sway {
          0% { transform: translateY(0) rotate(0deg); }
          50% { transform: translateY(-4px) rotate(3deg); }
          100% { transform: translateY(0) rotate(0deg); }
        }
        @keyframes twinkle {
          0%,100% { opacity: 0.9; transform: scale(1); }
          50% { opacity: 0.3; transform: scale(0.8); }
        }
      ]]></style>
    </defs>

    <!-- Left: moon -->
    <g class="moon" aria-hidden="true">
      <circle cx="120" cy="70" r="36" fill="#fff7ff" />
      <circle cx="135" cy="60" r="36" fill="#ffebf5" opacity="0.8"/>
      <circle cx="110" cy="80" r="6" fill="#ffd6e8" opacity="0.6"/>
    </g>

    <!-- Title -->
    <text x="190" y="60" class="title">🌸 Kasia Stańczyk — Creative Dev</text>
    <text x="190" y="86" class="subtitle">Graphic designer • Aspiring Software Developer • CS student @ Uni Łódź</text>

    <!-- Right: pastel flower -->
    <g transform="translate(480,30)" class="petal" aria-hidden="true">
      <ellipse cx="40" cy="70" rx="34" ry="18" fill="#ffd6e8" />
      <ellipse cx="16" cy="46" rx="14" ry="28" fill="#ffe9f7" transform="rotate(-30 16 46)"/>
      <ellipse cx="64" cy="46" rx="14" ry="28" fill="#fff0f6" transform="rotate(30 64 46)"/>
      <circle cx="40" cy="58" r="10" fill="#ffb7d5" />
    </g>

    <!-- little sparkles -->
    <circle class="spark" cx="320" cy="20" r="2.6" fill="#fff3f8"/>
    <circle class="spark" cx="360" cy="40" r="1.8" fill="#e8fbff"/>
    <circle class="spark" cx="420" cy="22" r="2.2" fill="#fff0f6"/>
  </svg>
</p>

<h1 align="center">
  <span style="font-size: 2.4rem; color: #ffb7d5;">🌸 Hi, I'm <strong>Kasia Stańczyk</strong> 🌙</span>
</h1>

<p align="center" style="font-size: 1.1rem; color:#ffdfee;">
  🎨 <strong>Graphic</strong> & 💻 <strong>Aspiring Software Developer</strong><br>
  📍 Poland | 🎓 CS student — University of Łódź <br>
  🌱 I love creating things that not only <strong>work</strong>, but also <strong>look magical</strong>.
</p>

---

## 💡 About Me
I combine **creativity with technology**
— studying **Applied Computer Science** (specializing in *Programming and Algorithms*) while exploring both **visual design** and **software development**.

- 🖌️ I design promotional graphics & user interfaces  
- 📱 I run social media for my faculty  
- 💻 I code in **C++**, **Python**, and explore **frontend** technologies  
- 🛠️ Gaining experience in **databases** and **operating systems**

---

## 🔍 Looking For
An **internship** opportunity where I can grow in both **design** and **development**, collaborate on meaningful projects, and continue learning from inspiring teams.

---

## 🛠️ Tech & Tools (unified pastel badges)
<p align="center">
  <!-- all "for-the-badge" for visual consistency -->
  <img alt="C++" src="https://img.shields.io/badge/C++-ffb7d5?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img alt="Python" src="https://img.shields.io/badge/Python-bde0fe?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ffe5a5?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-ff9aa2?style=for-the-badge&logo=html5&logoColor=white"/>
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-aec6ff?style=for-the-badge&logo=css3&logoColor=white"/>
  <img alt="SQL" src="https://img.shields.io/badge/SQL-ffb5e8?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

<p align="center">
  <img alt="Figma" src="https://img.shields.io/badge/Figma-ffd6e8?style=for-the-badge&logo=figma&logoColor=white"/>
  <img alt="Canva" src="https://img.shields.io/badge/Canva-bde0fe?style=for-the-badge&logo=canva&logoColor=white"/>
  <img alt="Godot" src="https://img.shields.io/badge/Godot-aec6ff?style=for-the-badge&logo=godot-engine&logoColor=white"/>
</p>

---

## 🌟 Featured Projects
| Project | Tech | Quick excerpt |
|---|---:|---|
| **Magic UI** | JS / Figma | Mini pastel UI library — reusable components & documentation. |
| **Godot Cute Game** | Godot | Platformer with pixel-art and charming mechanics. |
| **Portfolio site** | HTML / CSS / JS | Responsive portfolio with SVG animations and case studies. |

*(Tip: dodaj linki do repozytoriów w nazwach projektów, np. `[Magic UI](https://github.com/avuii/magic-ui)` )*

---

## 📊 GitHub Stats (streak + activity)
<p align="center">
  <!-- Zamień `avuii` na swój username jeśli trzeba -->
  <img alt="GitHub Stats" height="140" src="https://github-readme-stats.vercel.app/api?username=avuii&show_icons=true&theme=rose_pine&hide_border=true"/>
  <img alt="Top Languages" height="140" src="https://github-readme-stats.vercel.app/api/top-langs/?username=avuii&layout=compact&theme=rose_pine&hide_border=true"/>
  <img alt="GitHub Streak" height="140" src="https://github-readme-streak-stats.herokuapp.com/?user=avuii&theme=rose_pine&hide_border=true"/>
</p>

<!-- Animated divider -->
<p align="center" aria-hidden="true">
  <svg width="100%" height="28" viewBox="0 0 800 28" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
    <defs>
      <linearGradient id="lineGrad" x1="0" x2="1">
        <stop offset="0" stop-color="#ffd6e8" />
        <stop offset="0.5" stop-color="#fff1f7" />
        <stop offset="1" stop-color="#e6f7ff" />
      </linearGradient>
      <style><![CDATA[
        .wave { animation: wave 6s linear infinite; transform-origin: 50% 50%; }
        @keyframes wave {
          0% { transform: translateX(0); }
          50% { transform: translateX(-30px); }
          100% { transform: translateX(0); }
        }
      ]]></style>
    </defs>
    <g fill="none" stroke="url(#lineGrad)" stroke-width="3" class="wave">
      <path d="M0 14 C80 0, 160 28, 240 14 S400 0, 480 14 S640 28, 720 14 S800 0, 880 14" />
    </g>
  </svg>
</p>

## 🤝 Let's Connect!
<p align="center">
  <a href="https://www.linkedin.com/in/katarzyna-stanczykk/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:k.stanczyk4364@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://avuii.github.io/portfolio/">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-FF69B4?style=for-the-badge&logo=google-chrome&logoColor=white"/>
  </a>
</p>

---

_Thanks for visiting my profile — feel free to reach out or ⭐ one of my future projects!_

