---
layout: page
title: 👋 Hi there
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
      width: 70%;
      background-color: #020c42;
      height: auto;
    }

    section::after {
      content: "";
      display: table;
      clear: both;
    }

    /* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
    @media (max-width: 600px) {
      nav, article {
        width: 100%;
        height: auto;
      }
    }
  </style>
</head>
<body>
<section>
  <nav>
<img src="/assets/images/MichaelBieri.png" alt="Italian Trulli" style="width:100%; height:auto;">
  </nav>
  <article>
    <h1 style="color:orange;">Hello, welcome</h1>
    <h2 style="font-size:400%;color:white;">I'm Michael Bieri</h1>
	<p style="color:white;">I'm Michael from Switzerland, a broadly interested person in 	technology. My journey began with a WordPress homepage, and through the Arduino world,
	I now landed in the world of digitalization and data topics.
	In my professional career I have 6 years of experience as an electronic and building 	technology requirements engineer / project manager.
	Alongside my tech pursuits, I also enjoy aviation✈️, music🎺, and sports🧭🚲.</p>
  </article>
</section>
</body>
</html>
