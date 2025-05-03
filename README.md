# sharvellstudios
<!DOCTYPE HTML>
<html>
<head>
  <title>Sharvell Studios</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    /* Basic reset and styling */
    body, html {
      margin: 0;
      padding: 0;
      font-family: "Source Sans Pro", sans-serif;
      color: #ffffff;
      background: #1c1c1c;
    }

    body.is-preload * {
      transition: none !important;
    }

    #wrapper {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      position: relative;
      z-index: 1;
      text-align: center;
      padding: 2rem;
    }

    .logo {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .content .inner h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin: 2rem 0;
    }

    nav ul li a {
      color: #00c6ff;
      text-decoration: none;
      font-size: 1.1rem;
    }

    article {
      max-width: 700px;
      margin: 4rem auto;
    }

    .image.main img {
      width: 100%;
      max-width: 600px;
      height: auto;
      border-radius: 10px;
      margin: 1.5rem 0;
    }

    #footer {
      text-align: center;
      font-size: 0.9rem;
      margin: 2rem 0;
    }

    #footer a {
      color: #00c6ff;
      text-decoration: none;
    }

    #bg {
      position: fixed;
      top: 0;
      left: 0;
      z-index: 0;
      width: 100%;
      height: 100%;
      background-image: url('assets/images/bg.jpg'), url('assets/images/overlay.png');
      background-size: cover, cover;
      background-repeat: no-repeat, repeat;
      background-position: center, center;
      opacity: 1;
    }
  </style>
</head>
<body class="is-preload">

  <!-- Wrapper -->
  <div id="wrapper">

    <!-- Header -->
    <header id="header">
      <div class="logo">
        <span class="icon fa-gem">💎</span>
      </div>
      <div class="content">
        <div class="inner">
          <h1>Sharvell Studios</h1>
          <p>A creative portfolio website styled with the Dimension template.</p>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#intro">Intro</a></li>
          <li><a href="#work">Work</a></li>
          <li><a href="#about">About</a></li>
        </ul>
      </nav>
    </header>

    <!-- Main -->
    <div id="main">
      <article id="intro">
        <h2 class="major">Intro</h2>
        <span class="image main"><img src="assets/images/pic01.jpg" alt="Intro Image" /></span>
        <p>This is a sample intro section using the Dimension template.</p>
      </article>

      <article id="work">
        <h2 class="major">Work</h2>
        <span class="image main"><img src="assets/images/pic02.jpg" alt="Work Image" /></span>
        <p>Here is where your portfolio or showcase would go.</p>
      </article>

      <article id="about">
        <h2 class="major">About</h2>
        <span class="image main"><img src="assets/images/pic03.jpg" alt="About Image" /></span>
        <p>A little about yourself or your studio goes here.</p>
      </article>
    </div>

    <!-- Footer -->
    <footer id="footer">
      <p>&copy; Sharvell Studios. Template from <a href="https://html5up.net">HTML5 UP</a>.</p>
    </footer>
  </div>

  <!-- Background -->
  <div id="bg"></div>

  <!-- Smooth scroll JS -->
  <script>
    document.addEventListener("DOMContentLoaded", () => {
      const links = document.querySelectorAll("nav a");
      links.forEach(link => {
        link.addEventListener("click", event => {
          event.preventDefault();
          const id = link.getAttribute("href").substring(1);
          const section = document.getElementById(id);
          if (section) {
            section.scrollIntoView({ behavior: "smooth" });
          }
        });
      });
    });
  </script>

</body>
</html>
your-project/
│
├── index.html  ← (This file)
└── assets/
    └── images/
        ├── bg.jpg
        ├── overlay.png
        ├── pic01.jpg
        ├── pic02.jpg
        └── pic03.jpg
