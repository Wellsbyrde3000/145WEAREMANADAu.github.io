<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Intercambio de Rupias</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

    body {
      background-image: url("https://i.pinimg.com/564x/75/a3/c4/75a3c4c4f6a93bfd63c4de7edb11f0ee.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      font-family: 'Montserrat', sans-serif;
      color: #000; /* Texto negro */
    }

    .contenedor {
      display: flex;
      flex-wrap: wrap; /* Add this line to wrap the items into rows */
      justify-content: center; /* Center the rows */
      margin: 20px;
    }

    .producto {
      display: flex;
      align-items: center;
      width: calc(33.333% - 20px); /* Adjust the width to fit 3 columns */
      margin: 10px;
      border: 1px solid #ddd;
      padding: 10px;
      border-radius: 5px;
    }

    .imagen {
      width: 100px;
      height: 100px;
      margin-right: 10px;
    }

    .precio {
      font-size: 18px;
      font-weight: bold;
    }

    h1 {
      text-align: center;
      font-size: 36px;
      margin-top: 20px;
    }

    h2 {
      text-align: center;
      font-size: 24px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Intercambio de Rupias</h1>
  <h2>Uso exclusivo de Grupo 145</h2>
  
  <div class="contenedor">
    <div class="producto">
      <img src="https://concepto.de/wp-content/uploads/2019/07/animales-de-la-selva-jaguar-e1562026291504.jpg" alt="Imagen 1" class="imagen">
      <div class="precio">100rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/6f/a8/63/6fa86314fce94881c2a7b7c7eebd46c7.jpg" alt="Imagen 2" class="imagen">
      <div class="precio">200rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/c1/3f/05/c13f05b228c4fe42a8ff584a16148fbd.jpg" alt="Imagen 3" class="imagen">
      <div class="precio">300rupias</div>
    </div>
    <div class="producto">
      <img src="https://concepto.de/wp-content/uploads/2019/07/animales-de-la-selva-jaguar-e1562026291504.jpg" alt="Imagen 4" class="imagen">
      <div class="precio">100rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/6f/a8/63/6fa86314fce94881c2a7b7c7eebd46c7.jpg" alt="Imagen 5" class="imagen">
      <div class="precio">200rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/c1/3f/05/c13f05b228c4fe42a8ff584a16148fbd.jpg" alt="Imagen 6" class="imagen">
      <div class="precio">300rupias</div>
    </div>
    <div class="producto">
      <img src="https://concepto.de/wp-content/uploads/2019/07/animales-de-la-selva-jaguar-e1562026291504.jpg" alt="Imagen 7" class="imagen">
      <div class="precio">100rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/6f/a8/63/6fa86314fce94881c2a7b7c7eebd46c7.jpg" alt="Imagen 8" class="imagen">
      <div class="precio">200rupias</div>
    </div>
    <div class="producto">
      <img src="https://i.pinimg.com/564x/c1/3f/05/c13f05b228c4fe42a8ff584a16148fbd.jpg" alt="Imagen 9" class="imagen">
      <div class="precio">300rupias</div>
    </div>
  </div>
</body>
</html>
