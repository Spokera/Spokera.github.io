<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      background-image: url('https://github.com/aamongusman/amongus/assets/145135579/bd6fc867-0e6d-4beb-b806-987fc43d57ea');
      background-size: cover;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      backdrop-filter: blur(5px); /* Add blurred effect to the background */
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
