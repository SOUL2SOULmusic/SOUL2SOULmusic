<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soul2Soul – Musik aus Leidenschaft</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        header, section, footer {
            margin-bottom: 40px;
        }
        h1, h2 {
            color: #444;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
        }
        footer {
            font-size: 0.9em;
            color: #777;
        }
        a {
            color: #0066cc;
            text-decoration: none;
        }
        .gallery img, .gallery video {
            width: 300px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Soul2Soul</h1>
    <p>Musik aus Leidenschaft – ein flexibles Trio mit Herz und Seele.</p>
</header>

<section id="ueber-uns">
    <h2>Über uns</h2>
    <p>
        Soul2Soul ist im Kern ein kreatives Trio: Micha Margraf, Aris Parwez und Thomas Stolkmann.
        Die Musiker wechseln innerhalb der Songs ihre Instrumente, um den jeweils singenden Kollegen optimal zu unterstützen.
        Bei größeren Auftritten wird die Band von Peter Staab an den Tasten verstärkt.
    </p>
</section>

<section id="bandmitglieder">
    <h2>Bandmitglieder</h2>
    <ul>
        <li><strong>Micha Margraf</strong> – Gitarre, Gesang, Bass, Percussion</li>
        <li><strong>Aris Parwez</strong> – Gitarre, Gesang, Bass, Percussion</li>
        <li><strong>Thomas Stolkmann</strong> – Solo-Gitarre, Gesang</li>
        <li><strong>Peter Staab</strong> (Gast) – Tasten (bei großen Auftritten)</li>
    </ul>
</section>

<section id="galerie">
    <h2>Galerie</h2>
    <div class="gallery">
        <!-- Hier kannst du Bilder hinzufügen -->
        <img src="bilder/beispielbild1.jpg" alt="Auftritt 1">
        <img src="bilder/beispielbild2.jpg" alt="Auftritt 2">

        <!-- Hier kannst du Videos hinzufügen -->
        <video controls>
            <source src="videos/beispielvideo1.mp4" type="video/mp4">
            Dein Browser unterstützt kein Video.
        </video>
        <video controls>
            <source src="videos/beispielvideo2.mp4" type="video/mp4">
            Dein Browser unterstützt kein Video.
        </video>
    </div>
</section>

<section id="kontakt">
    <h2>Kontakt</h2>
    <p>Für Buchungen und Anfragen: <a href="mailto:soul2soul@example.com">soul2soul@example.com</a></p>
</section>

<footer>
    <p>© 2025 Soul2Soul. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
