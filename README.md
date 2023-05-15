
<br>
<br>
<center>
<html>
  <head>
    <title>Ejemplo de letras animadas en HTML</title>
    <style>
      .animacion {
        font-size: 38px;
        animation: animar 2s infinite;
        color: green;
      }

      @keyframes animar {
        0% {
          transform: translateY(0);
        }
        50% {
          transform: translateY(-20px);
        }
        100% {
          transform: translateY(0);
        }
      }
    </style>
  </head>
  <body>
    <div class="animacion">𝗗𝗘𝗦𝗖𝗔𝗥𝗚𝗔 𝗡𝗨𝗘𝗦𝗧𝗥𝗔 𝗔𝗣𝗣</div>
  </body>
</html>



<br>
<center>
<html>
  <head>
    <title>Ejemplo de video de fondo en HTML</title>
    <style>
      #video-bg {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: -1;
        object-fit: cover;
      }
      
      @media (max-width: 10px) {
        #video-bg {
          object-fit: contain;
        }
      }
    </style>
  </head>
  <body>
    <video id="video-bg" autoplay loop muted>
      <source src="https://ia601609.us.archive.org/28/items/mar-33194/mar-33194.mp4" type="video/mp4">
    </video>
    <h1></h1>
  </body>
</html>
<img src="https://i.ibb.co/TbwKKtq/LOGO-2-1.png" alt="Descripción de la imagen" width="200" height="200">
<br>

<br>
<html>
  <head>
    <title>Ejemplo de botón con diseño en HTML</title>
    <style>
      .boton {
        display: inline-block;
        padding: 10px 20px;
        font-size: 16px;
        font-weight: bold;
        text-align: center;
        text-decoration: none;
        background-color: #4CAF50;
        color: white;
        border-radius: 5px;
        box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.25);
        transition: all 0.2s ease-in-out;
      }
      
      .boton:hover {
        background-color: #3e8e41;
        box-shadow: 4px 4px 4px rgba(0, 0, 0, 0.5);
      }
    </style>
  </head>
  <body>
    <a href="https://apk.e-droid.net/apk/app2627354-rqht1s.apk?v=1" class="boton" target="_blank">DESCARGAR</a>
  </body>
</html> 
