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
      padding: 20px;
      width: 70%; /* Breite des Artikels auf 60% beschränken */
      background-color: #020c42;
      height: auto;
      margin-right: 20px; /* Abstand nach rechts hinzufügen */
      text-align: justify; /* Textausrichtung auf Blocksatz setzen */
    }

    picture {
      float: right;
      padding: 20px;
      width: 30%;
      background-color: #ffffff;
      height: auto;
      margin-left: none; /* Abstand nach links hinzufügen */
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
    <article>
      <h1 style="color:orange;">Hello, welcome</h1>
      <h2 style="font-size:400%;color:white;">I'm Michael Bieri</h2>
      <p style="color:white;">I'm Michael from Switzerland, a broadly interested person in technology. My journey began with a WordPress homepage, and through the Arduino world, I now landed in the world of digitalization and data topics. In my professional career I have 6 years of experience as an electronic and building technology requirements engineer / project manager. Alongside my tech pursuits, I also enjoy aviation✈️, music🎺, and sports🧭🚲.</p>
    </article>
  </section>

  <section>
    <picture>
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri" style="width:100%; height:auto;">
    </picture>
  </section>

</body>
</html>
