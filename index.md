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
    }
    /* Sidebar/left column */
    .side {
      flex: 60%;
      background-color: #030e4e;
      text-align: left; /* Text aligned left */
      justify-content: center;
      color: white; /* Ensure text is white */
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px; /* Adds spacing inside the .side element */
    }
    /* Main column */
    .main {
      flex:40%;
      background-color: #f4f4f9;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    picture {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-left: -10px;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    /* Adjusting margins for h1, h2, and p to reduce space */
    h1 {
      font-size: 150%;
      color: orange;
      margin-bottom: 5px; /* Reduced space */
    }
    h2 {
      font-size: 300%;
      color: white;
      margin-bottom: 10px; /* Reduced space */
    }
    p {
      margin-bottom: 10px; /* Reduced space */
      line-height: 1.2; /* Reduced line spacing */
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