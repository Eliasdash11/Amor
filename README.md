<!doctype html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Perdóname</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        background-color: #f5f5f5;
        margin: 0;
        padding: 0;
      }
      .container {
        margin-top: 50px;
      }
      h1 {
        color: #ff6f61;
      }
      p {
        font-size: 1.2em;
      }
      .heart {
        font-size: 100px;
        color: #ff6f61;
      }
      .images {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
      }
      .images img {
        width: 150px;
        height: 150px;
        margin: 10px;
        border-radius: 50%;
        transition: transform 0.3s;
      }
      .images img:hover {
        transform: scale(1.2);
      }
      button {
        background-color: #ff6f61;
        color: white;
        border: none;
        padding: 15px 30px;
        font-size: 1.2em;
        cursor: pointer;
        border-radius: 5px;
        margin-top: 20px;
      }
      button:hover {
        background-color: #ff3e2e;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Perdóname, Amor</h1>
      <p>
        No hay palabras suficientes para expresar cuánto lo siento, sueño con
        que tu seas la mujer de mis dias sin importar lo que nos pasase, eres mi
        unico amor real y en el que confio por encima de todas las cosas,
        lamento todo lo que soy, pero aun asi con mis fallas quiero amarte,
        dejame ser tu amor toda la vida porfavor.
      </p>
      <div class="heart">💜🥺</div>
      <div class="images">
       <img src="![d4335031-06a8-4ac0-ab7b-ab31be6479df](https://github.com/Eliasdash11/Amor/assets/172306840/b573b8b3-3ac0-4466-b75c-4dfa4706878b)" alt="Imagen 1" />
        <img src="![a4cbabc2-884e-42b0-a1e5-848587a787ab](https://github.com/Eliasdash11/Amor/assets/172306840/4f4739b4-7ac0-4fad-b0db-4c2551f3ecab)" alt="Imagen 2" />
        <img src="![73498697-f538-4dc8-a721-e1dc9486086d](https://github.com/Eliasdash11/Amor/assets/172306840/e242dbab-c65f-4b00-904b-3e63fb25b53b)" alt="Imagen 3" />
      </div>
      <button onclick="showMessage()">Toca aqui amor</button>
      <div id="extraMessage" style="display: none; margin-top: 20px">
        <p>
          Te amo con todo mi corazón y haré todo lo posible para hacerte feliz.
        </p>
      </div>
    </div>

    <script>
      function showMessage() {
        document.getElementById("extraMessage").style.display = "block";
      }
    </script>
  </body>
</html>
