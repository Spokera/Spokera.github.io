<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
    }

    button {
      background-color: rgba(128, 128, 128, 0.5); /* Gray and transparent background */
      color: white;
      padding: 10px 15px;
      font-size: 16px;
      border: none;
      cursor: pointer;
      border-radius: 10px; /* Rounded corners */
    }
  </style>
</head>
<body>
  <div style="padding: 20px;">
    <!-- Image removed -->
  </div>
  
  <button onclick="redirectToPage()">Go to main page</button>

  <script>
    function redirectToPage() {
      window.location.href = "main";
    }
  </script>
</body>
</html>
