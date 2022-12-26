<!DOCTYPE html>
<html>
<head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=VT323&display=swap" rel="stylesheet">

  <title>Sito web in stile Matrix</title>
  <style>
    body {
      background-color: black;
      color: white;
    }
    #logo {
      display: block;
      margin: 0 auto;
      font-size: 36px;
      font-weight: bold;
    }
    @font-face {
      font-family: 'VT323', monospace;
      src: url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    }
    #logo {
      font-family: 'Matrix';
    }
    .gcse-search {
      display: block;
      margin: 0 auto;
    }
    #footer {
      background-color: green;
      border-top: 1px solid white;
      color: white;
      font-size: 14px;
      text-align: center;
      padding: 20px;
    }
    #footer a {
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div id="logo">PolicoroSearch</div>
  <script async src="https://cse.google.com/cse.js?cx=d7418e5f1a6c84f9e"></script>
  <div class="gcse-search"></div>
  <div id="footer">
    <a href="https://www.instagram.com/" target="_blank"><img src="path/to/instagram-icon.png" alt="Icona di Instagram" style="height: 18px;"></a>
    <a href="link-to-faq.html">FAQ</a> | <a href="link-to-contattaci.html">Contattaci</a> | <a href="link-to-posta-il-tuo-sito.html">Posta il tuo Sito</a>
  </div>
  <script>
    var colors = ['white', 'green', 'white'];
    var currentColor = 0;

    function updateLogo() {
      document.getElementById('logo').style.color = colors[currentColor];
      currentColor = (currentColor + 1) % colors.length;
    }

    setInterval(updateLogo, 500);
  </script>
</body>
