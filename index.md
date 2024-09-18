---
layout: page
---

<head>
  <style>
    * {
      box-sizing: border-box;
    }
    /* Style the body */
    body {
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
    }
    /* Column container */
    .row {  
      display: flex;
      flex-wrap: wrap;
      align-items: stretch; /* Ensures both columns stretch to the same height */
    }
    /* Sidebar/left column */
    .side {
      flex: 60%;
      background-color: #030e4e;
      text-align: left;
      justify-content: center;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 10px;
      display: flex;
      flex-direction: column;
      justify-content: center; /* Vertically centers the text inside the side column */
    }
    /* Main column */
    .main {
      flex: 40%;
      background-color: #f4f4f9;
      padding: 0px;
      display: flex;
      justify-content: left; /* Centers the picture horizontally */
      align-items: bottom; /* Centers the picture vertically */
    }
    picture {
      display: flex;
      justify-content: left;
      align-items: bottom;
      border: 8px solid orange;
      margin: 0;

    }
    img {
      max-width: 100%;
      height: auto;
    }
    /* Adjusting margins for h1, h2, and p to reduce space */
    h1 {
      font-size: 200%;
      color: orange;
      margin-bottom: 5px;
    }
    h2 {
      font-size: 400%;
      color: white;
      margin-bottom: 0px;
    }
    p {
      margin-bottom: -10px;
      color: white;
      line-height: 1.6;
    }
    /* Responsive layout */
    @media screen and (max-width: 700px) {
      .row {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

<!-- The flexible grid (content) -->
<div class="row">
  <div class="side">
    <h1>Hello, welcome</h1>
    <h2>I'm Michael Bieri</h2>
    <p>From Switzerland, with a broad interest in technology. My journey began with a WordPress homepage, and through the world of Arduino, I eventually found myself in the realm of digitalisation and data. In my professional career, I have six years of experience as a requirements engineer and project manager in electronic and building technology. Alongside my passion for technology, I also enjoy music 🎺 and sports 🧭🚲.</p>
  </div>
  <div class="main">
    <picture>
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
    </picture>
  </div>
</div>
</body>
