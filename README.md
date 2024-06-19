<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pastelería Gourmet - Página Principal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #F8C291;
      color: #fff;
      padding: 10px;
      text-align: center;
    }

    nav {
      background-color: #FF5733;
      color: #fff;
      padding: 10px;
      text-align: center;
    }

    main {
      padding: 20px;
    }

    footer {
      background-color: #F8C291;
      color: #fff;
      padding: 10px;
      text-align: center;
      width: 100%;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }

    th,
    td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #FFC300;
      color: white;
    }
  </style>
</head>

<body>
  <header>
    <h1>Pastelería Gourmet</h1>
  </header>
  <nav>
    <a href="#inicio">Inicio</a> |
    <a href="#productos">Productos</a> |
    <a href="#pedido">Pedidos</a> |
    <a href="#informacion">Información</a> |
   
  </nav>
  <main>
    <section id="inicio">
      <h2>Bienvenidos a Pastelería Gourmet</h2>
      <p>Somos una pastelería especializada en la creación de deliciosos postres gourmet. Nuestra historia se remonta a 2012, cuando comenzamos como un pequeño negocio familiar. Desde entonces, nuestro objetivo ha sido deleitar a nuestros clientes con exquisitas creaciones.</p>
      <p>Horario de atención: Lunes a Sábado de 9:00 am a 8:00 pm. Domingos de 10:00 am a 6:00 pm.</p>
    </section>

    <section id="productos">
      <h3>Productos de la Pastelería</h3>
      <table>
        <thead>
          <tr>
            <th>Producto</th>
            <th>Ingredientes</th>
            <th>Costo</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Macarons</td>
            <td>Almendras, azúcar, clara de huevo, ganache, crema de mantequilla, etc.</td>
            <td>$2.50 por unidad</td>
          </tr>
          <tr>
            <td>Tartas de Frutas</td>
            <td>Masa quebrada, frutas frescas, gelatina o glaseado</td>
            <td>$20 por tarta</td>
          </tr>
          <tr>
            <td>Galletas</td>
            <td>Harina, mantequilla, azúcar, huevos, extracto de vainilla, etc.</td>
            <td>$1.50 por unidad</td>
          </tr>
          <tr>
            <td>Pays</td>
            <td>Harina, mantequilla, azúcar, huevos, frutas, crema, etc.</td>
            <td>$25 por pay</td>
          </tr>
          <tr>
            <td>Pastelitos</td>
            <td>Harina, azúcar, mantequilla, huevos, levadura, relleno de elección, etc.</td>
            <td>$2 por unidad</td>
          </tr>
          <tr>
            <td>Muffins</td>
            <td>Harina, azúcar, mantequilla, huevos, leche, levadura, frutas o chocolate, etc.</td>
            <td>$2.50 por unidad</td>
          </tr>
          <tr>
            <td>Croissants</td>
            <td>Harina, mantequilla, azúcar, sal, levadura, huevo, agua, etc.</td>
            <td>$3 por unidad</td>
          </tr>
        </tbody>
      </table>
    </section>
       <a href="#inicio"> Volver al Inicio</a> 

    <section id="pedido">
      <h3>Realiza tu Pedido</h3>
      <form id="pedidoForm">
        <label for="macarons">Macarons ($2.50 por unidad):</label>
        <input type="number" id="macarons" name="macarons" min="0" value="0"><br>

        <label for="tartas">Tartas de Frutas ($20 por tarta):</label>
        <input type="number" id="tartas" name="tartas" min="0" value="0"><br>

        <label for="galletas">Galletas ($1.50 por unidad):</label>
        <input type="number" id="galletas" name="galletas" min="0" value="0"><br>

        <label for="pays">Pays ($25 por pay):</label>
        <input type="number" id="pays" name="pays" min="0" value="0"><br>

        <label for="pastelitos">Pastelitos ($2 por unidad):</label>
        <input type="number" id="pastelitos" name="pastelitos" min="0" value="0"><br>

        <label for="muffins">Muffins ($2.50 por unidad):</label>
        <input type="number" id="muffins" name="muffins" min="0" value="0"><br>

        <label for="croissants">Croissants ($3 por unidad):</label>
        <input type="number" id="croissants" name="croissants" min="0" value="0"><br>

        <button type="button" onclick="calcularTotal()">Calcular Total</button>
      </form>
    </section>
 
    <section id="total">
      <h3>Total del Pedido</h3>
      <p id="totalPedido">$0.00</p>
    </section>
  </main>
       <a href="#inicio"> Volver al Inicio</a> 
  <section id="blog">
    <h2>Celebración de Aniversario</h2>
    <img src="aniversario.jpg" alt="Imagen del blog 1" width="400" height="
300">
    <p>¡Hoy celebramos nuestro primer aniversario! Agradecemos a todos nuestros clientes por su apoyo y preferencia. Para celebrarlo, hemos preparado una selección especial de postres exclusivos. ¡Ven y celebra con nosotros!</p>

  </section>
  <section class="blog-post">
    <h2>Nueva Colección de Macarons</h2>
    <img src="macarons.jpg" alt="Imagen del blog 2" width="400" height="300">
    <p>¡Estamos emocionados de presentar nuestra nueva colección de macarons! Con una amplia gama de colores y sabores, estos deliciosos dulces franceses son el regalo perfecto para cualquier ocasión. Ven y descubre tus favoritos.</p>
  </section>
  <section class="blog">
    <h2>Receta del Mes - Tarta de Frutas</h2>
    <img src="tarta.jpg" alt="Imagen del blog 3">
    <p>¿Quieres probar algo nuevo en casa? Te compartimos nuestra receta de la tarta de frutas, una deliciosa combinación de masa crujiente y frutas frescas de temporada. Sigue nuestros pasos y sorprende a tus seres queridos.</p>
  </section>
         <a href="#inicio"> Volver al Inicio</a> 
  <section id="informacion">
    <h3>Información de Contacto</h3>
    <p>Aquí puedes encontrar nuestra información de contacto y ubicación.</p>
  </section>
         <a href="#inicio"> Volver al Inicio</a> 
  <section id="contacto">
    <footer>
      <p>Pastelería Gourmet</p>
      <p>Teléfono: 123-456-789</p>
      <p>¡Gracias por visitarnos y disfrutar de nuestros deliciosos postres!</p>
    </footer>
  </section>
  <script>
    function calcularTotal() {
      var macarons = parseFloat(document.getElementById('macarons').value);
      var tartas = parseFloat(document.getElementById('tartas').value);
      var galletas = parseFloat(document.getElementById('galletas').value);
      var pays = parseFloat(document.getElementById('pays').value);
      var pastelitos = parseFloat(document.getElementById('pastelitos').value);
      var muffins = parseFloat(document.getElementById('muffins').value);
      var croissants = parseFloat(document.getElementById('croissants').value);

      var total = (macarons * 2.50) + (tartas * 20) + (galletas * 1.50) + (pays * 25) + (pastelitos * 2) + (muffins * 2.50) + (croissants * 3);

      document.getElementById('totalPedido').innerText = '$' + total.toFixed(2);
    }
  </script>
</body>
</html>
