# Happy-birthday-Luay
A birthday surprise for luay
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(pink, white);
      text-align: center;
    }

    h1 {
      margin-top: 80px;
      color: #d63384;
    }

    button {
      padding: 15px 25px;
      font-size: 18px;
      background: #ff4d6d;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 20px;
    }

    button:hover {
      background: #e6004c;
    }

    #gift {
      display: none;
      margin-top: 40px;
      padding: 20px;
      background: white;
      width: 80%;
      margin-left: auto;
      margin-right: auto;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
    }

    .confetti {
      font-size: 30px;
    }
  </style>
</head>

<body>

  <h1>🎉 Happy Birthday 🎉</h1>

  <p class="confetti">🎂🎈🎁</p>

  <button onclick="openGift()">Open My Gift 🎁</button>

  <div id="gift">
    <h2>💖 Your Birthday Letter 💖</h2>
    <p>
      Happy Birthday 🥹❤️<br><br>
      You mean so much to me and I hope your day is filled with love, happiness, and everything you wish for 💕<br><br>
      I’m grateful for you always 💖🎂
    </p>
  </div>

  <script>
    function openGift() {
      document.getElementById("gift").style.display = "block";
    }
  </script>

</body>
</html>
