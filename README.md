<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hello</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      height: 100vh;
      display: flex;
      flex-direction: column;
    }

    .navbar {
      display: flex;
      justify-content: flex-end;
      padding: 20px;
      gap: 30px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .center {
      flex-grow: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 40px;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="your-resume-link.pdf" target="_blank">My Resume</a>
    <a href="https://www.linkedin.com/in/your-linkedin" target="_blank">LinkedIn</a>
  </div>

  <div class="center">
    Hello
  </div>
</body>
</html>
