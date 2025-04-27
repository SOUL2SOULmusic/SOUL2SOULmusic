<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Soul2Soul - Musik aus Kassel</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e0e6c54d.js" crossorigin="anonymous"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #ffffff;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(90deg, #f9f9f9, #ffffff);
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #555;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ff7f50;
    }
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h1, h2 {
      color: #222;
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      margin-bottom: 20px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .gallery img, .gallery video {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
      cursor: pointer;
    }
    .gallery img:hover, .gallery video:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #f1f1f1;
      text-align: center;
      padding: 30px 20px;
      margin-top: 50px;
      font-size: 14px;
      color: #777;
    }
    .social-icons {
      margin-top: 15px;
    }
    .social-icons a {
      margin: 0 10px;
      color: #777;
      font-size: 24px;
      transition: color 0.3s ease;
      text-decoration: none;
    }
    .social-icons a:hover {
      color: #ff7f50;
    }
  </style>
</head>
<body>

<header>
  <h1>Soul2Soul</h1>
  <nav>
    <a href="#about">Über uns</a>
    <a href="#press">Pressetext</a>
    <a href="#gallery">Galerie</a>
    <a href="#contact">Kontakt</a>
  </nav>
</header>

<section id="about">
  <h2>Über uns</h2>
  <p><strong>Soul2Soul</strong> ist ein Trio aus Kassel, bestehend aus <strong>Micha Margraf</strong>, <strong>Aris Parwez</strong> und <strong>Thomas Stolktmann</strong>.
  Gemeinsam bringen sie Musik von Seele zu Seele – authentisch, bewegend und voller Leidenschaft.</p>
</section>

<section id="press">
  <h2>Pressetext</h2>
  <p>
    Aus den Herzen Kassels entsteht eine musikalische Begegnung, die unter die Haut geht: <strong>Soul2Soul</strong> – das Trio bestehend aus 
    <strong>Micha Margraf</strong>, <strong>Aris Parwez</strong> und <strong>Thomas Stolktmann</strong>.<br><br>
    Mit einer einzigartigen Mischung aus Soul, Pop und akustischen Einflüssen schaffen sie bewegende Klanglandschaften, die Emotionen wecken 
    und Menschen miteinander verbinden.<br><br>
    Die Musik von Soul2Soul ist mehr als nur Unterhaltung – sie ist Einladung und Inspiration zugleich. Feinfühlig arrangierte Songs, 
    ehrliche Texte und eine spürbare Leidenschaft prägen ihren Stil und machen jedes Konzert zu einem besonderen Erlebnis.<br><br>
    Ob auf großen Bühnen, bei intimen Veranstaltungen oder privaten Events: Soul2Soul berührt, begeistert und bleibt im Herzen.<br><br>
    <em>Soul2Soul – von Seele zu Seele.</em>
  </p>
</section>

<section id="gallery">
  <h2>Galerie</h2>
  <div class="gallery">
    <img src="bilder/bild1.jpg" alt="Soul2Soul Bild 1">
    <img src="bilder/bild2.jpg" alt="Soul2Soul Bild 2">
    <video controls>
      <source src="videos/video1.mp4" type="video/mp4">
      Dein Browser unterstützt dieses Videoformat nicht.
    </video>
    <img src="bilder/bild3.jpg" alt="Soul2Soul Bild 3">
  </div>
</section>

<section id="contact">
  <h2>Kontakt</h2>
  <p>Ihr möchtet mehr über uns erfahren oder uns buchen? Schreibt uns gerne eine E-Mail an:<br><br>
    <a href="mailto:kontakt@soul2soul.de" style="color: #ff7f50; text-decoration: none;">kontakt@soul2soul.de</a>
  </p>
</section>

<footer>
  &copy; 2025 Soul2Soul - Alle Rechte vorbehalten
  <div class="social-icons">
    <a href="https://www.instagram.com/dein-instagram" target="_blank"><i class="fab fa-instagram"></i></a>
    <a href="https://www.youtube.com/dein-youtube" target="_blank"><i class="fab fa-youtube"></i></a>
  </div>
</footer>

</body>
</html>
