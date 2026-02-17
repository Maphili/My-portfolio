<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>My First Website</title>

    <!-- CSS Styling -->
    <style>
      body {
        background-color: lightblue;
        font-family: Arial, sans-serif;
        text-align: center;
        margin-top: 100px;
      }

      h1 {
        color: navy;
      }

      button {
        padding: 10px 20px;
        font-size: 16px;
        background-color: navy;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
    </style>
  </head>

  <body>
    <h1>Welcome to philile's haven</h1>
    <p>This is my first website built with love🎉</p>

    <button onclick="showMessage()">Click Me</button>

    <!-- JavaScript -->
    <script>
      function showMessage() {
        alert("Hello 👋 thanks for clicking!");
      }
    </script>
  </body>
</html>
