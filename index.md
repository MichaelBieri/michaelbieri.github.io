---
layout: page
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Article with Image</title>
  <style>
    * {
      box-sizing: border-box;
    }

    /* Container for both the article and the picture */
    .content {
      display: flex;
      flex-wrap: wrap; /* Ensures responsive layout on small screens */
      align-items: flex-start;
    }

    /* Styling for the article */
    article {
      flex: 1 1 60%; /* The article will take up 60% of the width */
      padding: 20px;
      background-color: #020c42;
      margin-right: 20px;
      text-align: justify;
    }

    /* Styling for the image container */
    picture {
      flex: 1 1 30%; /* The picture will take up 30% of the width */
      background-color: #ffffff;
      padding: 0;
      margin: 0;
    }

    /* Responsive layout: Stacks article and image vertically on small screens */
    @media (max-width: 600px) {
      .content {
        flex-direction: column;
      }

      article, picture {
        width: 100%;
        margin-right: 0; /* Remove the margin for smaller screens */
      }
    }
  </style>
</head>

<body>
  <section class="content">
    <article>
      <h1 style="color:orange;">Hello, welcome</h1>
      <h2 style="font-size:400%;color:white;">I'm Michael Bieri</h2>
      <p style="color:white;">I'm Michael from Switzerland, a broadly interested person in technology. My journey began with a WordPress homepage, and through the Arduino world, I now landed in the world of digitalization and data topics. In my professional career I have 6 years of experience as an electronic and building technology requirements engineer / project manager. Alongside my tech pursuits, I also enjoy aviation✈️, music🎺, and sports🧭🚲.</p>
    </article>

    <picture>
      <img src="/assets/images/MichaelBieri.png" alt="Michael Bieri" style="width:100%; height:auto;">
    </picture>
  </section>
</body>
</html>
