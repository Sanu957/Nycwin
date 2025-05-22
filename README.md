<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Diu Wins Clone</title>
  <style>
    body {
      background-color: #111;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    h1 {
      margin-top: 100px;
      font-size: 3em;
    }
    button {
      font-size: 1.5em;
      padding: 10px 30px;
      margin-top: 30px;
      cursor: pointer;
      background: #fff;
      border: none;
      border-radius: 10px;
    }
    #result {
      margin-top: 30px;
      font-size: 2em;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Diu Wins</h1>
  <button onclick="playGame()">Play</button>
  <div id="result"></div>

  <script>
    function playGame() {
      const result = Math.random() < 0.5 ? "YOU WIN!" : "YOU LOSE!";
      document.getElementById("result").textContent = result;
    }
  </script>
</body>
</html># Nycwin
