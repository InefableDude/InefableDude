<!-- ============================================ -->
<!-- 🧠 HEADER ANIMADO (Frontend vibes)           -->
<!-- ============================================ -->
<div align="center">
  <svg width="100%" height="180" viewBox="0 0 800 180" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <animate attributeName="x1" values="0%;100%;0%" dur="5s" repeatCount="indefinite" />
        <stop offset="0%" stop-color="#dd0031" />   <!-- Angular red -->
        <stop offset="50%" stop-color="#c2185b" />
        <stop offset="100%" stop-color="#06b6d4" /> <!-- Tailwind cyan -->
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    <!-- Partículas animadas -->
    <circle cx="50" cy="90" r="2" fill="#dd0031" opacity="0.6">
      <animate attributeName="cy" values="90;20;90" dur="4s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.6;0;0.6" dur="4s" repeatCount="indefinite" />
    </circle>
    <circle cx="150" cy="110" r="1.5" fill="#c2185b" opacity="0.7">
      <animate attributeName="cy" values="110;40;110" dur="3.5s" repeatCount="indefinite" />
    </circle>
    <circle cx="300" cy="70" r="2.5" fill="#06b6d4" opacity="0.5">
      <animate attributeName="cy" values="70;10;70" dur="5s" repeatCount="indefinite" />
    </circle>
    <circle cx="500" cy="130" r="1.8" fill="#dd0031" opacity="0.8">
      <animate attributeName="cy" values="130;50;130" dur="4.2s" repeatCount="indefinite" />
    </circle>
    <circle cx="650" cy="80" r="2" fill="#c2185b" opacity="0.6">
      <animate attributeName="cy" values="80;20;80" dur="3.8s" repeatCount="indefinite" />
    </circle>
    <circle cx="750" cy="100" r="1.5" fill="#06b6d4" opacity="0.7">
      <animate attributeName="cy" values="100;30;100" dur="4.5s" repeatCount="indefinite" />
    </circle>
    <!-- Nombre y subtítulo -->
    <text x="400" y="90" text-anchor="middle" font-size="40" font-family="'Segoe UI', Arial, sans-serif" font-weight="bold" fill="url(#grad)" filter="url(#glow)">
      BARUCH RODRÍGUEZ
      <animate attributeName="font-size" values="40;42;40" dur="3s" repeatCount="indefinite" />
    </text>
    <text x="400" y="135" text-anchor="middle" font-size="16" font-family="Arial, sans-serif" fill="#94a3b8" letter-spacing="3">
      FRONTEND DEVELOPER · UX/UI ENTHUSIAST
    </text>
  </svg>
</div>

<!-- ============================================ -->
<!-- 🔗 BADGES DE CONTACTO                        -->
<!-- ============================================ -->
<div align="center">
  <a href="https://www.linkedin.com/in/baruch-rafael-rodriguez-covarrubias-3b793a2a5/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:udgbaruch@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://github.com/InefableDude">
    <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <br/>
  <img src="https://komarev.com/ghpvc/?username=inefabledude&label=👁️+Visitas&color=dd0031&style=for-the-badge" alt="visitas"/>
  <a href="https://www.codewars.com/users/Inefable_Dude">
    <img src="https://www.codewars.com/users/Inefable_Dude/badges/micro" alt="CodeWars" />
  </a>
</div>

<br/>

<!-- ============================================ -->
<!-- 🧑‍💼 SOBRE MÍ (con avatar animado)              -->
<!-- ============================================ -->
<table align="center" style="border: none; border-collapse: collapse;">
  <tr>
    <td width="60%" style="border: none; vertical-align: top; padding-right: 20px;">
      <h2>👨‍💻 Sobre mí</h2>
      <p align="justify">
        ¡Hola! Soy <strong>Baruch Rodríguez</strong>, desarrollador frontend apasionado por crear experiencias digitales que no solo se vean bien, sino que <strong>funcionen mejor</strong>.
        Mi stack principal gira en torno a <strong>Angular</strong>, <strong>TypeScript</strong>, <strong>TailwindCSS</strong> y <strong>Sass</strong>, siempre con el foco puesto en <strong>UX/UI</strong> y la optimización del flujo de usuario.
      </p>
      <p align="justify">
        No me limito a maquetar: analizo, rediseño y optimizo procesos para que cada sitio web o aplicación sea realmente útil. 
        Disfruto combinando diseño atómico, componentes reutilizables y buenas prácticas de accesibilidad.
      </p>
      <ul>
        <li>🌱 Ahora profundizando en: <strong>Angular Signals, RxJS, Testing con Jest</strong></li>
        <li>🤝 Abierto a colaborar en proyectos <strong>frontend desafiantes</strong></li>
        <li>📫 Contáctame: 
          <a href="mailto:udgbaruch@gmail.com"><strong>udgbaruch@gmail.com</strong></a>
        </li>
      </ul>
    </td>
    <td width="40%" align="center" style="border: none;">
      <!-- Avatar SVG con iniciales y aro giratorio -->
      <svg width="180" height="180" viewBox="0 0 180 180" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <clipPath id="circleClip">
            <circle cx="90" cy="90" r="80"/>
          </clipPath>
          <linearGradient id="avatarGrad" x1="0%" y1="0%" x2="100%" y2="100%">
            <animate attributeName="x2" values="100%;0%;100%" dur="6s" repeatCount="indefinite" />
            <stop offset="0%" stop-color="#dd0031"/>
            <stop offset="100%" stop-color="#06b6d4"/>
          </linearGradient>
        </defs>
        <circle cx="90" cy="90" r="85" fill="none" stroke="url(#avatarGrad)" stroke-width="4" stroke-dasharray="534" stroke-dashoffset="0">
          <animate attributeName="stroke-dashoffset" values="0;1068" dur="10s" repeatCount="indefinite" />
        </circle>
        <circle cx="90" cy="90" r="75" fill="#1e1b4b" stroke="#dd0031" stroke-width="2"/>
        <text x="90" y="105" text-anchor="middle" font-size="45" font-family="Arial" font-weight="bold" fill="url(#avatarGrad)">BR</text>
      </svg>
      <br/>
      <img src="https://github-readme-stats.vercel.app/api?username=InefableDude&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="stats" width="100%"/>
    </td>
  </tr>
</table>


<br/>

<!-- ============================================ -->
<!-- 🚀 PROYECTOS DESTACADOS (reframe frontend)   -->
<!-- ============================================ -->
<h2 align="center">🚀 Proyectos Destacados</h2>

<!-- Proyecto 1: Librería (frontend) -->
<div align="center">
  <table style="border: 1px solid #dd0031; border-radius: 12px; background: #0d1117; width: 90%; border-collapse: separate; border-spacing: 0; overflow: hidden; box-shadow: 0 4px 20px rgba(221,0,49,0.3);">
    <tr>
      <td style="background: linear-gradient(135deg, #dd0031, #c2185b); padding: 10px 20px; border: none;">
        <h3 style="margin:0; color: white;">📚 Librería MERN · Catálogo Interactivo</h3>
      </td>
    </tr>
    <tr>
      <td style="padding: 20px; border: none;">
        <p><strong>Frontend dinámico con React, Tailwind y Sass para gestionar libros.</strong></p>
        <p>
          <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
          <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
          <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
          <img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=fastapi&logoColor=white"/>
        </p>
        <ul>
          <li>🎨 UI responsiva y amigable con componentes reutilizables</li>
          <li>⚡ Consumo de API REST con operaciones CRUD completas</li>
          <li>✨ Diseño moderno con Sass y utilidades de Tailwind</li>
        </ul>
        <p>
          <a href="https://github.com/InefableDude/frontend-mern-libreria-basica">📁 Frontend</a> &nbsp;|&nbsp;
          <a href="https://github.com/InefableDude/backend-mern-libreria-basica">📁 Backend</a>
        </p>
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- Proyecto 2: Stocks Market -->
<div align="center">
  <table style="border: 1px solid #06b6d4; border-radius: 12px; background: #0d1117; width: 90%; border-collapse: separate; border-spacing: 0; overflow: hidden; box-shadow: 0 4px 20px rgba(6,182,212,0.3);">
    <tr>
      <td style="background: linear-gradient(135deg, #06b6d4, #0288d1); padding: 10px 20px; border: none;">
        <h3 style="margin:0; color: white;">📊 Stocks Market · Visualización de Datos</h3>
      </td>
    </tr>
    <tr>
      <td style="padding: 20px; border: none;">
        <p><strong>Dashboard interactivo con gráficos y modales inteligentes.</strong></p>
        <p>
          <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
          <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white"/>
          <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
        </p>
        <ul>
          <li>📈 Gráficos dinámicos con animaciones suaves</li>
          <li>🧩 Modales personalizables para detalles de acciones</li>
          <li>🎯 Enfoque en UX para navegación de datos financieros</li>
        </ul>
        <p>
          <a href="https://github.com/InefableDude/frontend-mern-stocks">📁 Frontend</a> &nbsp;|&nbsp;
          <a href="https://github.com/InefableDude/backend-mern-stocks">📁 Backend</a>
        </p>
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- Proyecto 3: Black Bone (UI puro) -->
<div align="center">
  <table style="border: 1px solid #c2185b; border-radius: 12px; background: #0d1117; width: 90%; border-collapse: separate; border-spacing: 0; overflow: hidden; box-shadow: 0 4px 20px rgba(194,24,91,0.3);">
    <tr>
      <td style="background: linear-gradient(135deg, #c2185b, #8e24aa); padding: 10px 20px; border: none;">
        <h3 style="margin:0; color: white;">🖤 Black Bone · Tienda Urban/Gothic UI</h3>
      </td>
    </tr>
    <tr>
      <td style="padding: 20px; border: none;">
        <p><strong>Diseño de landing page oscura y elegante, 100% responsive.</strong></p>
        <p>
          <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
          <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
          <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
        </p>
        <ul>
          <li>🎭 Tipografías modernas: Playfair Display + Raleway</li>
          <li>📱 Layout responsive con técnicas avanzadas de CSS</li>
          <li>🧭 Navegación clara enfocada en la experiencia del usuario</li>
        </ul>
        <p>
          <a href="https://github.com/InefableDude/black-bone-html-css">📁 Repositorio</a>
        </p>
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- ============================================ -->
<!-- ⚙️ TECH STACK (orientado a frontend)         -->
<!-- ============================================ -->
<h2 align="center">⚙️ Tech Stack</h2>

<div align="center">
  <!-- Frontend Core -->
  <h3>🧩 Frontend Core</h3>
  <p>
    <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular"/>
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  </p>

  <!-- Estilos & Frameworks -->
  <h3>🎨 Estilos &amp; Frameworks</h3>
  <p>
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
    <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass"/>
    <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="SCSS"/>
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
    <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js"/>
  </p>

  <!-- Backend & Bases de datos -->
  <h3>⚙️ Backend &amp; Bases de Datos</h3>
  <p>
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
    <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB"/>
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  </p>

  <!-- Herramientas & Plataformas -->
  <h3>🛠️ Herramientas &amp; Plataformas</h3>
  <p>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
    <img src="https://img.shields.io/badge/openSUSE-73BA25?style=for-the-badge&logo=opensuse&logoColor=white" alt="openSUSE"/>
    <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
    <img src="https://img.shields.io/badge/Gulp-CF4647?style=for-the-badge&logo=gulp&logoColor=white" alt="Gulp"/>
    <img src="https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white" alt="Composer"/>
    <img src="https://img.shields.io/badge/FileZilla-BF0000?style=for-the-badge&logo=filezilla&logoColor=white" alt="FileZilla"/>
    <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown"/>
  </p>
</div>

<br/>

<!-- ============================================ -->
<!-- 📈 ESTADÍSTICAS ANIMADAS                     -->
<!-- ============================================ -->
<h2 align="center">📈 Estadísticas de GitHub</h2>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=InefableDude&theme=radical&hide_border=true" alt="racha" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=InefableDude&layout=compact&theme=radical&hide_border=true&langs_count=8" alt="lenguajes más usados" />
  <br/>
  <img src="https://github-profile-trophy-fork-two.vercel.app/?username=InefableDude&theme=monokai&no-frame=true&row=1&column=7" alt="trofeos" width="100%"/>
</div>

<br/>

<!-- ============================================ -->
<!-- 🌟 MIS OBJETIVOS (animados)                  -->
<!-- ============================================ -->
<h2 align="center">🌟 Mis Objetivos</h2>

<div align="center">
  <table style="background: transparent; width: 80%; border: none;">
    <tr>
      <!-- Dominar JS/TS & Angular -->
      <td align="center" style="border: none; padding: 15px;">
        <svg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
          <circle cx="30" cy="30" r="25" fill="none" stroke="#dd0031" stroke-width="3">
            <animate attributeName="r" values="25;28;25" dur="2s" repeatCount="indefinite"/>
          </circle>
          <text x="30" y="38" text-anchor="middle" font-size="22" fill="#dd0031">🅰️</text>
        </svg>
        <br/><strong>Maestría JS/TS &amp; Angular</strong><br/>Dominar patrones avanzados,<br/>signals, testing y rendimiento
      </td>
      <!-- UX/UI & Diseño funcional -->
      <td align="center" style="border: none; padding: 15px;">
        <svg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
          <circle cx="30" cy="30" r="25" fill="none" stroke="#06b6d4" stroke-width="3">
            <animate attributeName="r" values="25;28;25" dur="2s" repeatCount="indefinite" begin="0.3s"/>
          </circle>
          <text x="30" y="38" text-anchor="middle" font-size="22" fill="#06b6d4">🎨</text>
        </svg>
        <br/><strong>UX/UI &amp; Diseño Funcional</strong><br/>Crear interfaces que guíen,<br/>conviertan y deleiten al usuario
      </td>
      <!-- Soluciones completas -->
      <td align="center" style="border: none; padding: 15px;">
        <svg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg">
          <circle cx="30" cy="30" r="25" fill="none" stroke="#c2185b" stroke-width="3">
            <animate attributeName="r" values="25;28;25" dur="2s" repeatCount="indefinite" begin="0.6s"/>
          </circle>
          <text x="30" y="38" text-anchor="middle" font-size="22" fill="#c2185b">⚡</text>
        </svg>
        <br/><strong>Soluciones Completas</strong><br/>No solo rediseño, optimizo<br/>flujos para máxima utilidad
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- ============================================ -->
<!-- 🔮 FRASE MOTIVACIONAL                        -->
<!-- ============================================ -->
<div align="center">
  <svg width="500" height="80" viewBox="0 0 500 80" xmlns="http://www.w3.org/2000/svg">
    <rect x="0" y="0" width="500" height="80" rx="15" fill="#0d1117" stroke="#dd0031" stroke-width="1"/>
    <text x="250" y="45" text-anchor="middle" font-size="18" font-family="Arial, sans-serif" fill="#94a3b8">
      ✨ "Diseño funcional que convierte visitas en experiencias" ✨
      <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
    </text>
  </svg>
</div>

<br/>

<!-- ============================================ -->
<!-- 📬 CONTACTO FINAL                            -->
<!-- ============================================ -->
<h2 align="center">📬 ¡Conectemos!</h2>

<div align="center">
  <a href="https://www.linkedin.com/in/baruch-rafael-rodriguez-covarrubias-3b793a2a5/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:udgbaruch@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://github.com/InefableDude">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <br/><br/>
  <p style="color: #dd0031; font-size: 16px;">
    ⭐ ¿Te gusta mi enfoque? ¡Dale una estrella a mis repos! ⭐
  </p>
</div>

<br/>

