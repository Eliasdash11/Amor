
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
       <img src="![WhatsApp Image 2024-06-10 at 11 56 54 AM](https://github.com/Eliasdash11/Amor/assets/172306840/a98a8d06-d387-4545-baa7-1fe868f55b4c)" alt="Imagen 1" />
        <img src="![WhatsApp Image 2024-06-10 at 11 55 47 AM](https://github.com/Eliasdash11/Amor/assets/172306840/4df9c9a4-4dea-4a98-bce9-ae2af7ec490b)" alt="Imagen 2" />
        <img src="![WhatsApp Image 2024-06-10 at 11 54 50 AM](https://github.com/Eliasdash11/Amor/assets/172306840/aa018edf-a70d-4f04-903e-59d5db760754)" alt="Imagen 3" />
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
