<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ST's Fragance</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: #6c3483;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      background-color: #2c3e50;
      color: white;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 10px;
      text-decoration: none;
      font-size: 1rem;
    }
    .hero {
      background-image: url('https://via.placeholder.com/1200x400?text=ST%27s+Fragance');
      background-size: cover;
      background-position: center;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 1.8em;
      text-shadow: 2px 2px 4px #000;
      padding: 0 10px;
      text-align: center;
    }
    .content {
      padding: 30px 20px;
      text-align: center;
    }
    .content h2 {
      margin-bottom: 10px;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .product {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 10px;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .product p {
      margin: 5px 0;
    }
    .footer {
      background-color: #f1f1f1;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      .hero {
        font-size: 1.4em;
        height: 200px;
      }
      nav a {
        margin: 5px;
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>ST's Fragance</h1>
    <p>Encuentra tu esencia ideal</p>
  </header>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>
  <div class="hero" id="inicio">
    <div>Fragancias únicas para personas únicas</div>
  </div>
  <div class="content" id="productos">
    <h2>Nuestros Perfumes</h2>
    <div class="products-grid">
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/61PbfbwH+KL._AC_SY450_.jpg" alt="Le Beau Le Parfum">
        <p><strong>Le Beau Le Parfum</strong></p>
        <p>Un aroma seductor y exótico con notas amaderadas y orientales.</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/71H8mHq1n5L._AC_SY450_.jpg" alt="Le Male Elixir">
        <p><strong>Le Male Elixir</strong></p>
        <p>Una versión intensa y misteriosa del clásico Le Male, con notas cálidas y especiadas.</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/71OMVnUdSFL._AC_SY450_.jpg" alt="Halloween Man Mystery">
        <p><strong>Halloween Man Mystery</strong></p>
        <p>Una fragancia intrigante con toques de ámbar, especias y madera.</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/71lgZzhP-yL._AC_SY450_.jpg" alt="Acqua di Gio">
        <p><strong>Acqua di Gio</strong></p>
        <p>Un clásico fresco y acuático que evoca libertad y elegancia.</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/71K2bZGuFJL._AC_SY450_.jpg" alt="Invictus Parfum">
        <p><strong>Invictus Parfum</strong></p>
        <p>Fuerza y frescura en una fragancia intensa y moderna para el hombre seguro.</p>
      </div>
      <div class="product">
        <img src="https://m.media-amazon.com/images/I/51LzLv8PMSL._AC_SY450_.jpg" alt="Cloud Ariana Grande">
        <p><strong>Cloud - Ariana Grande</strong></p>
        <p>Un perfume dulce y envolvente con notas de coco, vainilla y lavanda, ideal para ella.</p>
      </div>
    </div>
  </div>
  <div class="content" id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>ST's Fragance nace de la pasión por las esencias que inspiran y destacan la personalidad de cada cliente.</p>
  </div>
  <div class="content" id="contacto">
    <h2>Contacto</h2>
    <p>Correo: contacto@stsfragance.com</p>
    <p>Teléfono: +52 425 105 9988</p>
  </div>
  <div class="footer">
    &copy; 2025 ST's Fragance. Todos los derechos reservados.
  </div>
</body>
</html>
