<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your GitHub Pages Site</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-image: url('https://github.com/Spokera/Spokera.github.io/assets/145135579/9b09c7a1-76ed-46c0-9d38-864be57a2d3e');
      background-size: cover;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      font-family: 'Arial', sans-serif;
      text-align: center;
    }

    button {
      background-color: #000; /* Black background color */
      color: white;
      padding: 12px 20px;
      font-size: 18px;
      border: none;
      cursor: pointer;
      border-radius: 10px; /* Rounded corners */
      transition: background-color 0.3s ease; /* Smooth transition */
    }

    button:hover {
      background-color: #333; /* Slightly lighter black background on hover */
    }
  </style>
</head>
<body>
  <div style="padding: 20px;">
    <!-- Image removed -->
  </div>
  
  <button onclick="redirectToPage()">Explore Main Page</button>

  <script>
    function redirectToPage() {
      window.location.href = "main";
    }
  </script>
</body>
</html>
