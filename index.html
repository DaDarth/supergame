<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Roll Duel</title>
  <style>
    body {
      font-family: sans-serif;
      background: #111;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 0;
      padding: 2rem;
    }
    h1 {
      color: #0f0;
    }
    .dice-container {
      display: flex;
      gap: 1rem;
      margin: 1rem 0;
      font-size: 4rem;
    }
    .btns {
      margin: 1rem 0;
    }
    button {
      padding: 1rem 2rem;
      font-size: 1.2rem;
      margin: 0 0.5rem;
      cursor: pointer;
      background: #222;
      color: #0f0;
      border: 1px solid #0f0;
      border-radius: 8px;
    }
    .result {
      font-size: 1.5rem;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <h1>🎲 Roll Duel</h1>
  <div class="dice-container" id="dice">
    🎲 🎲
  </div>
  <div class="btns">
    <button onclick="rollDice()">Roll</button>
    <button onclick="riskRoll()" id="riskBtn" disabled>Risk It</button>
  </div>
  <div class="result" id="result"></div>

  <script>
    let firstScore = 0;
    let finalScore = 0;
    let isSecondRoll = false;

    function randomDie() {
      return Math.floor(Math.random() * 6) + 1;
    }

    function showDice(d1, d2) {
      const dice = ["⚀","⚁","⚂","⚃","⚄","⚅"];
      document.getElementById("dice").innerHTML = `${dice[d1 - 1]} ${dice[d2 - 1]}`;
    }

    function rollDice() {
      const d1 = randomDie();
      const d2 = randomDie();
      firstScore = d1 + d2;
      isSecondRoll = false;
      showDice(d1, d2);
      document.getElementById("result").innerText = `You rolled ${firstScore}. Lock in or Risk it?`;
      document.getElementById("riskBtn").disabled = false;
    }

    function riskRoll() {
      const d1 = randomDie();
      const d2 = randomDie();
      finalScore = d1 + d2;
      showDice(d1, d2);
      document.getElementById("riskBtn").disabled = true;
      isSecondRoll = true;
      checkPayout(finalScore);
    }

    function checkPayout(score) {
      let payout;
      if (score <= 5) {
        payout = "❌ You lose.";
      } else if (score <= 8) {
        payout = "🪙 Payout: x1.5";
      } else if (score <= 10) {
        payout = "🪙 Payout: x2";
      } else {
        payout = "💰 Payout: x3!";
      }
      document.getElementById("result").innerText = `Final score: ${score} — ${payout}`;
    }
  </script>
</body>
</html>
