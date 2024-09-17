---
layout: page
---

<head>
  <style>
    .content {
      display: flex;
      flex-wrap: wrap;
      align-items: flex-start;
      margin-bottom: 20px;
    }
    article {
      flex: 1 1 60%;
      padding: 20px;
      background-color: #020c42;
      margin: auto;
      text-align: left;
      line-height: 1.5;
      max-width: 100%;
      box-sizing: border-box; 
    }
    picture {
      flex: 1 1 30%;
      background-color: #020c42;
      padding: 0;
      margin: center;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    /* Adjusting margins for h1, h2, and p to reduce space */
    h1 {
      font-size: 200%;
      color: orange;
      margin-bottom: 5px; /* Reduced space */
    }
    h2 {
      font-size: 400%;
      color: white;
      margin-bottom: 10px; /* Reduced space */
    }
    p {
      color: white;
      margin-bottom: 10px; /* Reduced space */
      line-height: 1.2; /* Reduced line spacing */
    }
    /* Responsive layout */
    @media (max-width: 1024px) {
      article {
        flex: 1 1 100%;
      }
      picture {
        flex: 1 1 100%;
        text-align: center;
      }
    }
    @media (max-width: 480px) {
      .content {
        flex-direction: column;
      }
      article, picture {
        width: 100%;
        margin: 0;
        text-align: center;
      }
      article {
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
      <p>I'm Michael from Switzerland, with a broad interest in technology. My journey began with a WordPress homepage, and through the world of Arduino, I eventually found myself in the realm of digitalisation and data. In my professional career, I have six years of experience as a requirements engineer and project manager in electronic and building technology. Alongside my passion for technology, I also enjoy music 🎺 and sports 🧭🚲.</p>
    </article>
    <picture>
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
    </picture>
  </section>
</body>