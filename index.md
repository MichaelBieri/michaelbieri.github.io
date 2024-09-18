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
      flex: 40%;
      background-color: #030e4e;
      text-align: left; /* Text aligned left */
      justify-content: center;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 20px; /* Adds spacing inside the .side element */
      margin-bottom: 10px; /* Reduced space */
    }
    /* Main column */
    .main {
      flex:60%;
      background-color: #f4f4f9;
      padding: 20px;
      display: flex;
      justify-content: flex-start; /* Aligns items to the left */
      align-items: flex-end; /* Aligns items to the bottom */
    }
    picture {
      display: flex;
      justify-content: left;
      align-items: bottom;
      margin-left: -20px;
      margin-top: 10px;
      border: 8px solid orange; /* Adds a 4px solid orange border */
    }
    img {
      max-width: 80%;
      height: auto;
    }
    /* Adjusting margins for h1, h2, and p to reduce space */
    h1 {
      font-size: 170%;
      color: orange;
      margin-bottom: 5px; /* Reduced space */
    }
    h2 {
      font-size: 330%;
      color: white;
      margin-bottom: 10px; /* Reduced space */
    }
    p {
      margin-bottom: -10px; /* Reduced space */
      color: white;
      line-height: 1.5; /* Reduced line spacing */
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