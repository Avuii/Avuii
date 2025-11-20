
<p align="center">
  <img src="baner.png" alt="Kasia Stańczyk banner" width="100%" />
</p>

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
        /* konieczne dla transform-origin w SVG */
        .animated { transform-box: fill-box; transform-origin: center; }
        .moon { animation: floatMoon 6s ease-in-out infinite; }
        .petal { animation: sway 4s ease-in-out infinite; }
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
 <g class="moon animated" aria-hidden="true" transform-box="fill-box" transform-origin="120px 70px">
   <circle cx="120" cy="70" r="36" fill="#fff7ff" />
    <circle cx="135" cy="60" r="36" fill="#ffebf5" opacity="0.8"/>
    <circle cx="110" cy="80" r="6" fill="#ffd6e8" opacity="0.6"/>
<!-- SMIL fallback: translate + rotate -->
  <animateTransform attributeName="transform" attributeType="XML"
        type="translate" dur="6s" values="0 0; 0 -6; 0 0" repeatCount="indefinite"/>
  <animateTransform attributeName="transform" attributeType="XML"
     type="rotate" dur="6s" values="0; -3; 0" repeatCount="indefinite"/>
    </g>
<!-- Title -->
    <text x="190" y="60" class="title">🌸 Kasia Stańczyk — Creative Dev</text>
    <text x="190" y="86" class="subtitle">Graphic designer • Aspiring Software Developer • CS student @ Uni Łódź</text>
    <!-- Right: pastel flower (CSS + SMIL fallback) -->
    <g transform="translate(480,30)" class="petal animated" aria-hidden="true" transform-box="fill-box" transform-origin="520px 100px">
      <ellipse cx="40" cy="70" rx="34" ry="18" fill="#ffd6e8" />
      <ellipse cx="16" cy="46" rx="14" ry="28" fill="#ffe9f7" transform="rotate(-30 16 46)"/>
      <ellipse cx="64" cy="46" rx="14" ry="28" fill="#fff0f6" transform="rotate(30 64 46)"/>
      <circle cx="40" cy="58" r="10" fill="#ffb7d5" />
      <!-- SMIL fallback -->
      <animateTransform attributeName="transform" attributeType="XML"
        type="translate" dur="4s" values="0 0; 0 -4; 0 0" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" attributeType="XML"
        type="rotate" dur="4s" values="0; 3; 0" repeatCount="indefinite"/>
    </g>
    <!-- little sparkles (CSS + SMIL opacity fallback, z drobnym opóźnieniem) -->
    <circle class="spark animated" cx="320" cy="20" r="2.6" fill="#fff3f8" transform-box="fill-box" transform-origin="320px 20px">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.4s" repeatCount="indefinite" begin="0s" />
    </circle>
    <circle class="spark animated" cx="360" cy="40" r="1.8" fill="#e8fbff" transform-box="fill-box" transform-origin="360px 40px">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.4s" repeatCount="indefinite" begin="0.45s" />
    </circle>
    <circle class="spark animated" cx="420" cy="22" r="2.2" fill="#fff0f6" transform-box="fill-box" transform-origin="420px 22px">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.4s" repeatCount="indefinite" begin="1s" />
    </circle>
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

### 🛠️ Tech & Tools 
<p align="center">
  <img alt="C++" src="https://img.shields.io/badge/C++-ffb7d5?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img alt="Python" src="https://img.shields.io/badge/Python-bde0fe?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ffe5a5?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-ff9aa2?style=for-the-badge&logo=html5&logoColor=white"/>
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-aec6ff?style=for-the-badge&logo=css3&logoColor=white"/>
  <img alt="SQL" src="https://img.shields.io/badge/SQL-ffb5e8?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### 🎨 Design
<p align="center">
<img alt="Figma" src="https://img.shields.io/badge/Figma-ffb7d5?style=for-the-badge&logo=figma&logoColor=white"/>
<img alt="Canva" src="https://img.shields.io/badge/Canva-bde0fe?style=for-the-badge&logo=canva&logoColor=white"/>
<img alt="AutoCAD" src="https://img.shields.io/badge/AutoCAD-ff9aa2?style=for-the-badge&logo=autodesk&logoColor=white"/>
<img alt="Aseprite" src="https://img.shields.io/badge/Aseprite-aec6ff?style=for-the-badge&logo=aseprite&logoColor=white"/>
<img alt="Three.js" src="https://img.shields.io/badge/Three.js-ffe5a5?style=for-the-badge&logo=three.js&logoColor=black"/>
<img alt="3ds Max" src="https://img.shields.io/badge/3ds_Max-bde0fe?style=for-the-badge&logo=autodesk&logoColor=white"/>
</p>

### 🖥️ IDE
<p align="center">
<img alt="Visual Studio" src="https://img.shields.io/badge/Visual_Studio-ffb5e8?style=for-the-badge&logo=visual-studio&logoColor=white"/>
<img alt="VS Code" src="https://img.shields.io/badge/VS_Code-aec6ff?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
<img alt="PyCharm" src="https://img.shields.io/badge/PyCharm-ff9aa2?style=for-the-badge&logo=pycharm&logoColor=white"/>
<img alt="CLion" src="https://img.shields.io/badge/CLion-ffb7d5?style=for-the-badge&logo=clion&logoColor=white"/>
<img alt="Rider" src="https://img.shields.io/badge/Rider-ffb5e8?style=for-the-badge&logo=jetbrains&logoColor=white"/>
</p>

### 🧰 Other Tools
<p align="center">
<img alt="GitHub" src="https://img.shields.io/badge/GitHub-f2d7ee?style=for-the-badge&logo=github&logoColor=black"/>
<img alt="Godot" src="https://img.shields.io/badge/Godot-bde0fe?style=for-the-badge&logo=godot-engine&logoColor=white"/>
<img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-cdf5f6?style=for-the-badge&logo=latex&logoColor=008080"/>
<img alt="FCL" src="https://img.shields.io/badge/FCL-aec6ff?style=for-the-badge&logo=gear&logoColor=white"/>
</p>

---

## 📊 GitHub Stats 
<p align="center">
  <img alt="GitHub Stats" height="140" src="https://github-readme-stats.vercel.app/api?username=avuii&show_icons=true&theme=rose_pine&hide_border=true"/>
  <img alt="Top Languages" height="140" src="https://github-readme-stats.vercel.app/api/top-langs/?username=avuii&layout=compact&theme=rose_pine&hide_border=true"/>
  <img alt="GitHub Streak" height="140" src="https://github-readme-streak-stats.herokuapp.com/?user=avuii&theme=rose_pine&hide_border=true"/>
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

