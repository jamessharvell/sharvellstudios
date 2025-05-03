# sharvellstudios
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sharvell Studios</title>
  <style>
    /* Reset and base styles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      color: #f4f4f4;
      background: #0e0e0e url('https://images.unsplash.com/photo-1601621031328-c2f26e7e017b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1650&q=80') no-repeat center center fixed;
      background-size: cover;
      scroll-behavior: smooth;
    }

    header, section, footer {
      padding: 4rem 2rem;
      text-align: center;
      background: rgba(0,0,0,0.7);
    }

    header {
      padding-top: 6rem;
    }

    h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      margin-bottom: 0.5rem;
    }

    p {
      max-width: 700px;
      margin: 0 auto 1.5rem;
      line-height: 1.6;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
      padding: 0;
    }

    nav a {
      color: #00c6ff;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffffff;
    }

    .section-title {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    img {
      max-width: 100%;
      height: auto;
      margin: 2rem 0;
      border-radius: 10px;
    }

    footer {
      font-size: 0.9rem;
      padding: 2rem;
    }

    /* Button style */
    .button {
      background: #00c6ff;
      color: #0e0e0e;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    .button:hover {
      background: #0094cc;
      color: white;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header id="home">
    <h1>Sharvell Studios 🎬</h1>
    <p>Crafting Cinematic Experiences & Creative Visual Storytelling</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2 class="section-title">About Us</h2>
    <p>Sharvell Studios is a visionary film production house focused on narrative-driven visual storytelling. We produce cinematic content for film, television, and branded media with a distinct artistic flair.</p>
    <img src="https://images.unsplash.com/photo-1515165562835-cbdf432f4f79?ixlib=rb-4.0.3&auto=format&fit=crop&w=1650&q=80" alt="About Sharvell Studios" />
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2 class="section-title">Projects</h2>
    <p>Here are some of our featured productions and collaborations.</p>
    <img src="https://images.unsplash.com/photo-1611691541759-8cfbafbd951b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1650&q=80" alt="Project Still" />
    <img src="https://images.unsplash.com/photo-1558992796-c1e748ea1ba2?ixlib=rb-4.0.3&auto=format&fit=crop&w=1650&q=80" alt="Behind the Scenes" />
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2 class="section-title">Contact</h2>
    <p>Interested in collaborating or learning more? Get in touch with us.</p>
    <a class="button" href="mailto:info@sharvellstudios.com">Email Us</a>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Sharvell Studios. Design inspired by HTML5 UP's Dimension.
  </footer>

</body>
</html>
