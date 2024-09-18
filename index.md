---
layout: page
---

<head>
  <style>
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
      flex: 60%;
      background-color: #f4f4f9;
      padding: 10px;
      display: flex;
      justify-content: flex-start; /* Aligns items to the left */
      align-items: flex-end; /* Aligns items to the bottom */
    }
    picture {
      display: flex;
      justify-content: left;
      align-items: bottom;
      margin-left: -20px;
      margin-top: 0px;
      border: 8px solid orange; /* Adds a 4px solid orange border */
      width: 100%; /* Adjust the width of the picture container */
      height: 300px; /* Set a fixed height for the picture */
    }
    img {
      width: 100%; /* Ensures the image takes up the entire width of the picture */
      height: 100%; /* Ensures the image fits within the specified height */
      object-fit: cover; /* Maintains aspect ratio while filling the picture container */
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