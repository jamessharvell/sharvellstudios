# sharvellstudios
<!DOCTYPE HTML>
<html>
<head>
  <title>Sharvell Studios</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />

  <!-- Embedded CSS -->
  <style>
    body {
      background-color: #1c1c1c;
      color: #fff;
      font-family: "Source Sans Pro", sans-serif;
      margin: 0;
      padding: 0;
    }

    #wrapper {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
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
    }

    nav ul li a {
      color: #00c6ff;
      text-decoration: none;
      font-size: 1.1rem;
    }

    section {
      padding: 5rem 1rem;
    }

    footer {
      margin-top: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

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
          <p>Welcome to my portfolio powered by the Dimension template from <a href="https://html5up.net" style="color:#00c6ff">HTML5 UP</a>.</p>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#intro">Intro</a></li>
          <li><a href="#work">Work</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <!-- Main Sections -->
    <div id="main">
      <section id="intro">
        <h2>Intro</h2>
        <p>This is where your introduction would go.</p>
      </section>
      <section id="work">
        <h2>Work</h2>
        <p>Projects and samples of what you've built.</p>
      </section>
      <section id="about">
        <h2>About</h2>
        <p>Information about Sharvell Studios and background.</p>
      </section>
      <section id="contact">
        <h2>Contact</h2>
        <p>Ways to reach you or follow your work.</p>
      </section>
    </div>

    <!-- Footer -->
    <footer id="footer">
      <p class="copyright">&copy; Sharvell Studios. Design: <a href="https://html5up.net" style="color:#00c6ff">HTML5 UP</a>.</p>
    </footer>

  </div>

  <!-- Embedded JS -->
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
/* main.css — basic reset and layout */
body {
  background-color: #1c1c1c;
  color: #fff;
  font-family: "Source Sans Pro", sans-serif;
  margin: 0;
  padding: 0;
}

#wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
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
}

nav ul li a {
  color: #00c6ff;
  text-decoration: none;
}
/assets/js/main.js
// main.js — minimal functional script
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
