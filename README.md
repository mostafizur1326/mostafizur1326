<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>MOSTALIF Animation</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@900&display=swap');

  body {
    background: #111;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
  }

  .wow-text {
    font-family: 'Poppins', sans-serif;
    font-size: 6rem;
    font-weight: 900;
    color: transparent;
    background: linear-gradient(270deg, #ff0057, #00ffea, #ff0057);
    background-size: 600% 600%;
    -webkit-background-clip: text;
    background-clip: text;
    animation: gradientMove 4s ease infinite;
    text-shadow:
      0 0 5px #ff0057,
      0 0 10px #ff0057,
      0 0 20px #00ffea,
      0 0 30px #00ffea,
      0 0 40px #ff0057,
      0 0 50px #ff0057;
  }

  @keyframes gradientMove {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
</style>
</head>
<body>
  <div class="wow-text">MOSTALIF</div>
</body>
</html>
