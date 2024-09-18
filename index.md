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
      /* Change color on hover */
      .navbar a:hover {
        background-color: #ddd;
        color: black;
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
        background-color: #f1f1f1;
        padding: 20px;
      }
      /* Main column */
      .main {
        flex: 70%;
        background-color: white;
        padding: 20px;
      }
      /* Fake image, just for this example */
      .fakeimg {
        background-color: #aaa;
        width: 100%;
        padding: 20px;
      }
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
    <div class=""/assets/images/MichaelBieri.png"" style="height:200px;">Image</div>
    <br>
  </div>