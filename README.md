# My-game
学校よ，あばよ
<!DOCTYPE html>
<html>
<head>
  <title>きのこクリックゲーム</title>
  <style>
    body { text-align: center; font-family: sans-serif; }
    button { font-size: 24px; padding: 10px 20px; }
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
