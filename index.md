---
layout: page
---

<body>
  <head>
    <style>
      * {
        box-sizing: border-box;
      }
      /* Style the body */
      body {
        margin: 0;
      }
      /* Column container */
      .row {  
        display: flex;
        flex-wrap: wrap;
      }
      /* Create two unequal columns that sits next to each other */
      /* Sidebar/left column */
      .side {
        flex: 30%;
        background-color: #f4f4f9;
        padding: 20px;
        text-align: left;
        justify-content: center; 
      }
      /* Main column */
      .main {
        flex: 70%;
        background-color: white;
        padding: 20px;
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
      /* Fake image, just for this example */
      /* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
      @media screen and (max-width: 700px) {
        .row, .navbar {   
          flex-direction: column;
        }
      }
    </style>
  </head>
</body>

<!-- The flexible grid (content) -->
<div class="row">
  <div class="side">
    <h1>Hello, welcome</h1>    
    <h2>I'm Michael Bieri</h2>
    <h5>Pfrom Switzerland, with a broad interest in technology. My journey began with a WordPress homepage, and through the world of Arduino, I eventually found myself in the realm of digitalisation and data. In my professional career, I have six years of experience as a requirements engineer and project manager in electronic and building technology. Alongside my passion for technology, I also enjoy music 🎺 and sports 🧭🚲.</h5>
  </div>
  <div class="main">
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
    <br>
  </div>