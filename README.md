# My-game
学校よ，あばよ
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>きのこクリックゲーム</title>
  <style>
    body {
      text-align: center;
      font-family: "Arial", sans-serif;
      background-color: #f0fff0;
      padding-top: 50px;
    }
    h1 {
      color: #8f5e3b;
    }
    button {
      font-size: 24px;
      padding: 10px 20px;
      background-color: #d4a373;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
    }
    button:hover {
      background-color: #c17c4f;
    }
    #score {
      font-size: 32px;
      color: #4a7c59;
    }
  </style>
</head>
<body>
  <h1>🍄 きのこをクリック！</h1>
  <p>スコア: <span id="score">0</span></p>
  <button onclick="addScore()">きのこをクリック！</button>

  <script>
    let score = 0;
    function addScore() {
      score++;
      document.getElementById("score").textContent = score;
    }
  </script>
</body>
</html>
