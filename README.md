<!DOCTYPE html>
<html>
<head>
  <title>Surprise Gift</title>
  <style>
    body { 
      font-family: Arial; 
      text-align: center; 
      background: #ffe6f2; 
    }
    #message {
      display: none;
      font-size: 24px;
      margin-top: 20px;
      color: #d63384;
    }
    button {
      padding: 15px 25px;
      border: none;
      background: #d63384;
      color: white;
      font-size: 18px;
      border-radius: 10px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Your Surprise Gift 🎁</h1>
  <button onclick="reveal()">Click to Reveal</button>
  <p id="message">💖 This gift is specially for you! 💖</p>

  <script>
    function reveal() {
      document.getElementById('message').style.display = "block";
    }
  </script>
</body>
</html>
