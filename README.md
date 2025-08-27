<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CustomZone</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #1e90ff; /* fundal albastru */
      font-family: Arial, sans-serif;
    }

    h1 {
      font-size: 5em;
      font-weight: bold;
      text-transform: uppercase;
      background: linear-gradient(270deg, red, orange, yellow, green, blue, indigo, violet);
      background-size: 1500% 1500%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: rainbow 10s ease infinite;
      text-align: center;
    }

    @keyframes rainbow {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }
  </style>
</head>
<body>
  <h1>CustomZone</h1>
</body>
</html>
