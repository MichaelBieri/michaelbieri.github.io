---
layout: page
---

<body>
  <main>
    <style>
    * {
      box-sizing: border-box;
    }

    article {
      float: left; 
      padding: 30px;
      width: 60%; /* Breite des Artikels auf 60% beschränken */
      max-width: 600px; /* Maximale Breite festlegen */
      background-color: #020c42;
      height: auto;
      margin-right: 20px; /* Abstand nach rechts hinzufügen */
      text-align: justify; /* Textausrichtung auf Blocksatz setzen */
      border-radius: 10px; /* Abgerundete Ecken hinzufügen */
    }

    picture {
      float: right;
      padding: 30px;
      width: 30%;
      background-color: #ffffff;
      height: auto;
      margin-left: 20px; /* Abstand nach links hinzufügen */
    }

    section::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
    @media (max-width: 600px) {
      picture, article {
        width: 100%;
        height: auto;
        margin: 0; /* Margin entfernen für kleinere Bildschirme */
      }
    }
  </style>
</head>
<body>
<section>
  <picture>
    <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri" style="width:100%; height:auto;">
  </picture>
  <article>
    <h1 style="color:orange;">Hello, welcome</h1>
    <h2 style="font-size:400%;color:white;">I'm Michael Bieri</h2>
    <p style="color:white;">I'm Michael from Switzerland, a broadly interested person in technology. My journey began with a WordPress homepage, and through the Arduino world, I now landed in the world of digitalization and data topics. In my professional career I have 6 years of experience as an electronic and building technology requirements engineer / project manager. Alongside my tech pursuits, I also enjoy aviation✈️, music🎺, and sports🧭🚲.</p>
  </article>
</section>
</body>
</html>
