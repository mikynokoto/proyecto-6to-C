<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tienda de Belleza Online</title>
<style>
  body { font-family: Arial, sans-serif; }
  header, footer { background-color: #f4f4f4; padding: 10px 20px; }
  h1 { color: #333; }
  .producto { margin: 15px; border: 1px solid #ddd; padding: 10px; border-radius: 5px; }
  .producto img { max-width: 100%; }
  .descripcion { color: #555; }
  form { margin-top: 20px; }
  label { display: block; margin: 5px 0; }
</style>
</head>
<body>

<header>
  <h1>Tienda de Belleza Online</h1>
</header>

<section id="productos">
  <!-- Producto 1 -->
  <article class="producto">
    <img src="shampoo.jpg" alt="Shampoo Hidratante">
    <h2>Shampoo Hidratante</h2>
    <p class="descripcion">Ideal para cabello seco y dañado.</p>
    <button>Comprar</button>
  </article>
  
  <!-- Producto 2 -->
  <article class="producto">
    <img src="acondicionador.jpg" alt="Acondicionador Nutritivo">
    <h2>Acondicionador Nutritivo</h2>
    <p class="descripcion">Nutrición profunda para puntas abiertas.</p>
    <button>Comprar</button>
  </article>
  
  <!-- Más productos... -->
</section>

<footer>
  <form action="/suscripcion" method="post">
    <label for="email">Suscríbete a nuestro boletín:</label>
    <input type="email" id="email" name="email" placeholder="Ingresa tu email">
    <button type="submit">Suscribirse</button>
  </form>
</footer>

</body>
</html>
