# quero-vc-z-buceta-
msg de carinho 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Mensagem Especial</title>
  <style>
    body {
      margin: 0;
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    .container {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background-color: red;
      border: 3px solid white;
      padding: 30px;
      border-radius: 15px;
      text-align: center;
      font-size: 1.5em;
      box-shadow: 0 0 20px red;
    }

    .heart {
      position: absolute;
      font-size: 24px;
      animation: float 5s linear infinite;
    }

    @keyframes float {
      0% {
        transform: translateY(100vh);
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh);
        opacity: 0;
      }
    }
  </style>
</head>
<body>

  <!-- MENSAGEM -->
  <div class="container">
    ❤️ Quer ser a patrocinadora oficial da minha vida sem rumo? ❤️
  </div>

  <!-- CORAÇÕES SUBINDO -->
  <script>
    function createHeart() {
      const heart = document.createElement("div");
      heart.classList.add("heart");
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = 3 + Math.random() * 2 + "s";
      heart.innerText = "❤️";
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 5000);
    }

    setInterval(createHeart, 300);
  </script>

  <!-- ÁUDIO AUTOMÁTICO -->
  <audio autoplay loop>
    <!-- SUBSTITUA O CAMINHO ABAIXO PELO SEU ARQUIVO DE MÚSICA -->
    <source src=" https://youtu.be/DHEOF_rcND8?si=Sasj2Yj_j_PcH42E " type="audio/mpeg">
    Seu navegador não suporta áudio.
  </audio>

</body>
</html>
