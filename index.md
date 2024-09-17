---
layout: page
---

<head>
  <style>
    .content {
      display: flex;
      justify-content: space-between; /* Stellt sicher, dass der Artikel und das Bild getrennt sind */
      align-items: flex-start;
      margin-bottom: 20px;
      height: 100vh; /* Volle Höhe des Viewports für klare Trennung */
    }
    article {
      flex: 1 1 60%;
      padding: 20px;
      background-color: #020c42;
      color: white;
      text-align: left;
      line-height: 1.5;
      box-sizing: border-box;
    }
    .picture-box {
      flex: 1 1 40%; /* Bildbereich bekommt 40% des Platzes */
      background-color: #FFFFFF;
      padding: 20px;
      display: flex;
      justify-content: center; /* Bild mittig im Bereich zentrieren */
      align-items: center;
    }
    picture {
      display: block;
      max-width: 100%;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    /* Responsive layout */
    @media (max-width: 1024px) {
      .content {
        flex-direction: column; /* In kleiner Ansicht untereinander anordnen */
      }
      article, .picture-box {
        flex: 1 1 100%; /* Beide Bereiche bekommen 100% Breite */
      }
    }
    @media (max-width: 480px) {
      article, .picture-box {
        padding: 10px;
      }
      h1 {
        font-size: 150%;
      }
      h2 {
        font-size: 250%;
      }
      p {
        font-size: 90%;
        line-height: 1.2;
      }
    }
  </style>
</head>
<body>
  <section class="content">
    <article>
      <h1>Hello, welcome</h1>
      <h2>I'm Michael Bieri</h2>
      <p>from Switzerland, with a broad interest in technology. My journey began with a WordPress homepage, and through the world of Arduino, I eventually found myself in the realm of digitalisation and data. In my professional career, I have six years of experience as a requirements engineer and project manager in electronic and building technology. Alongside my passion for technology, I also enjoy music 🎺 and sports 🧭🚲.</p>
    </article>
    <div class="picture-box">
      <picture>
        <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
      </picture>
    </div>
  </section>
</body>
