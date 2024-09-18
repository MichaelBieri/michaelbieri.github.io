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
      padding: 0;
      display: flex;
      justify-content: center; /* Center the content horizontally */
      align-items: center; /* Center the content vertically */
      min-height: 100vh; /* Full viewport height */
    }

    /* Column container */
    .row {  
      display: flex;
      flex-wrap: wrap;
      align-items: center; /* Center items vertically */
      justify-content: center; /* Center items horizontally */
      max-width: 1200px; /* Limit the row width */
      margin: 0 auto; /* Center the row container */
    }

    /* Sidebar/left column */
    .side {
      flex: 60%;
      background-color: #030e4e;
      text-align: left;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 10px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    /* Main column */
    .main {
      flex: 40%;
      background-color: #f4f4f9;
      padding: 0;
      display: flex;
      justify-content: center; /* Center the image inside */
      align-items: center; /* Align image vertically */
    }

    img {
      max-width: 100%;
      height: auto;
      border: 8px solid orange;
    }

    h1 {
      font-size: 200%;
      color: orange;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 400%;
      color: white;
      margin-bottom: 30px;
    }

    p {
      margin-bottom: 40px;
      color: white;
      line-height: 1.6;
    }

    /* Responsive layout */
    @media screen and (max-width: 700px) {
      .row {
        flex-direction: column;
      }

      .side, .main {
        flex: 100%; /* Full width on small screens */
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
    <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri">
  </div>
</div>

</body>
