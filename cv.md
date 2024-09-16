---
layout: page
---

<h1> Please take a look at my CV </h1>

[Get it]({{ '/assets/pdfs/CV_MichaelBieri.pdf' | relative_url }})

<button name="button" onclick="{{ '/assets/pdfs/CV_MichaelBieri.pdf' | relative_url }}">Click here to download the CV</button>

<head>
  <style>
    .download-btn {
      background-color: orange; /* Orange background */
      color: white; /* White text */
      padding: 15px 25px; /* Padding for the button */
      text-align: center;
      text-decoration: none; /* Remove underline from the text */
      display: inline-block; /* Make it behave like a button */
      font-size: 16px;
      font-weight: bold;
      border-radius: 5px; /* Rounded corners */
      border: none; /* No border */
      cursor: pointer; /* Pointer cursor on hover */
      transition: background-color 0.3s; /* Smooth hover effect */
    }

    .download-btn:hover {
      background-color: #ff7f00; /* Darker orange on hover */
    }
  </style>
</head>
<body>

  <!-- Orange button to download the PDF -->
  <a href="/assets/pdfs/yourfile.pdf" download="yourfile.pdf" class="download-btn">Download PDF</a>

</body>
</html>
