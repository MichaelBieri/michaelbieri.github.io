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
      }
    }
  </style>
</head>
<body>
  <section class="content">
    <article>
      <h1 style="font-size:200%;color:orange;">Hello, welcome</h1>
      <h2 style="font-size:400%;color:white;">I'm Michael Bieri</h2>
      <p style="color:white;">I'm Michael from Switzerland, a broadly interested person in technology. My journey began with a WordPress homepage, and through the Arduino world, I now landed in the world of digitalization and data topics. In my professional career I have 6 years of experience as an electronic and building technology requirements engineer / project manager. Alongside my tech pursuits, I also enjoy music🎺 and sports🧭🚲.</p>
    </article>
    <picture>
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
    </picture>
  </section>
</body>
