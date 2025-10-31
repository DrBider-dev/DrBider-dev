<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brayan Ag | Desarrollador & Entusiasta de Linux</title>
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/518/518713.png" />
  <style>
    /* === Estilos generales === */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: #0D1117;
      color: #E0E0E0;
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
    }

    h1, h2 {
      color: #00BFA6;
      text-align: center;
    }

    a {
      color: #00BFA6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* === Header === */
    header {
      padding: 50px 20px;
      text-align: center;
      background: linear-gradient(135deg, #0D1117, #1a1f2b);
      border-bottom: 2px solid #00BFA6;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      color: #A0A0A0;
    }

    /* === Badges === */
    .badges {
      text-align: center;
      margin: 20px 0;
    }

    .badges img {
      margin: 5px;
    }

    /* === Secciones === */
    section {
      max-width: 900px;
      margin: 50px auto;
      padding: 0 20px;
    }

    section p {
      text-align: justify;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      background-color: #161B22;
      border-radius: 10px;
      overflow: hidden;
    }

    td {
      padding: 15px;
      border-bottom: 1px solid #2E2E2E;
      text-align: center;
    }

    td:first-child {
      color: #00BFA6;
      font-weight: bold;
      width: 35%;
    }

    /* === Lista de proyectos === */
    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      background-color: #161B22;
      margin: 10px 0;
      padding: 15px;
      border-radius: 10px;
      transition: transform 0.2s ease, background 0.2s ease;
    }

    ul li:hover {
      transform: translateY(-3px);
      background-color: #1E232E;
    }

    /* === Contacto === */
    .contact {
      text-align: center;
      margin-top: 20px;
    }

    .contact a img {
      margin: 10px;
      transition: transform 0.2s ease;
    }

    .contact a img:hover {
      transform: scale(1.1);
    }

    /* === Cita final === */
    blockquote {
      text-align: center;
      font-style: italic;
      margin-top: 50px;
      color: #B0B0B0;
    }

    footer {
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      font-size: 0.9rem;
      color: #888;
      border-top: 1px solid #222;
    }

    /* === Responsive === */
    @media (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }

      table td {
        display: block;
        text-align: left;
      }

      td:first-child {
        width: 100%;
        border-bottom: none;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>👋 ¡Hola, soy Brayan Ag!</h1>
    <p>Desarrollador Java | Linux Enthusiast | Karateka 🥋</p>
  </header>

  <div class="badges">
    <img src="https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white"/>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/Networking-0078D7?style=for-the-badge&logo=cisco&logoColor=white"/>
  </div>

  <section>
    <h2>💡 Sobre mí</h2>
    <p>
      Soy un apasionado de la tecnología, el software libre y la personalización del entorno de trabajo. 
      Utilizo <b>Arch Linux</b> con <b>BSPWM</b> como mi sistema principal, disfrutando de configurar cada detalle para optimizar mi flujo de trabajo.
    </p>
    <br>
    <p>
      Tengo experiencia desarrollando en <b>Java</b> aplicando el patrón <b>MVC</b>, además de conocimientos en redes y simulación topológica con 
      <b>Packet Tracer</b> y <b>Mikrotik RouterOS</b>. Me apasiona aprender nuevas tecnologías y resolver problemas de forma estructurada.
    </p>
    <br>
    <p>
      Fuera del teclado, practico <b>karate</b> 🥋 — disciplina que me enseña a mantener el equilibrio, la precisión y la constancia, valores que también aplico al desarrollo y la ingeniería.
    </p>
  </section>

  <section>
    <h2>🧠 Habilidades técnicas</h2>
    <table>
      <tr>
        <td>💻 Lenguajes</td>
        <td>Java, Python, JavaScript, Bash</td>
      </tr>
      <tr>
        <td>🧰 Herramientas</td>
        <td>Git, Docker, MySQL, Packet Tracer</td>
      </tr>
      <tr>
        <td>⚙️ Sistemas</td>
        <td>Arch Linux, Windows</td>
      </tr>
      <tr>
        <td>🌐 Redes</td>
        <td>Diseño topológico, Routing, VLANs, Mikrotik</td>
      </tr>
    </table>
  </section>

  <section>
    <h2>🚀 Proyectos destacados</h2>
    <ul>
      <li>📘 <b>Autoservicio Los Paisas</b> — Sistema de gestión de ventas e inventario con patrón MVC en Java.</li>
      <li>🌍 <b>Proyecto RedIRIS</b> — Simulación de red académica con Mikrotik y Packet Tracer.</li>
      <li>💡 <b>App tipo Duolingo</b> — Diseño de base de datos para una app educativa interactiva.</li>
    </ul>
  </section>

  <section>
    <h2>📫 Contacto</h2>
    <div class="contact">
      <a href="https://github.com/brayanag" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
      </a>
      <a href="mailto:tuemail@ejemplo.com">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
      </a>
    </div>
  </section>

  <blockquote>
    “El código, como las artes marciales, no se trata de fuerza, sino de precisión, equilibrio y constancia.”  
    <br>— <b>Brayan Ag</b>
  </blockquote>

  <footer>
    © 2025 Brayan Ag — Todos los derechos reservados.
  </footer>

</body>
</html>
