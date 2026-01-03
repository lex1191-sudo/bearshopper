<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bear Shopper | Compras desde USA</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
    }

    body {
      background: #f4f6f9;
      color: #222;
    }

    header {
      background: linear-gradient(90deg, #0a3161, #b31942);
      color: #fff;
      padding: 25px 15px;
      text-align: center;
    }

    header img {
      width: 180px;
      margin-bottom: 10px;
    }

    header h1 {
      font-size: 2.2rem;
      margin-bottom: 5px;
    }

    header p {
      font-size: 1rem;
      opacity: 0.9;
    }

    nav {
      background: #fff;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      flex-wrap: wrap;
    }

    nav a {
      text-decoration: none;
      color: #0a3161;
      font-weight: 600;
    }

    .hero {
      text-align: center;
      padding: 50px 20px;
      background: #fff;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 600px;
      margin: auto;
      font-size: 1.1rem;
      color: #555;
    }

    .badge {
      display: inline-block;
      background: #ffcc00;
      color: #000;
      padding: 8px 16px;
      border-radius: 30px;
      font-weight: bold;
      margin-top: 20px;
    }

    .categories {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .categories h3 {
      text-align: center;
      font-size: 1.8rem;
      margin-bottom: 30px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background: #fff;
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card span {
      font-size: 2.2rem;
      display: block;
      margin-bottom: 10px;
    }

    .how {
      background: #0a3161;
      color: #fff;
      padding: 50px 20px;
    }

    .how h3 {
      text-align: center;
      font-size: 1.8rem;
      margin-bottom: 25px;
    }

    .steps {
      max-width: 900px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .step {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 12px;
      text-align: center;
    }

    footer {
      background: #111;
      color: #ccc;
      text-align: center;
      padding: 25px 15px;
      margin-top: 40px;
    }

    footer strong {
      color: #fff;
    }
  </style>
</head>

<body>

  <header>
    <img src="bear-shopper.png" alt="Bear Shopper">
    <h1>Bear Shopper</h1>
    <p>Compras originales traídas desde USA 🇺🇸</p>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Calzado</a>
    <a href="#">Ropa</a>
    <a href="#">Bolsos</a>
    <a href="#">Perfumería</a>
    <a href="#">Cosméticos</a>
  </nav>

  <section class="hero">
    <h2>Comprá en USA sin complicaciones</h2>
    <p>
      En Bear Shopper traemos tus productos favoritos desde Estados Unidos,
      ya sea <strong>por encargo</strong> o desde nuestro <strong>stock disponible</strong>.
    </p>
    <div class="badge">🚧 Próximamente tienda activa</div>
  </section>

  <section class="categories">
    <h3>Categorías</h3>
    <div class="grid">
      <div class="card"><span>👟</span>Calzado</div>
      <div class="card"><span>👕</span>Ropa</div>
      <div class="card"><span>👜</span>Bolsos & Carteras</div>
      <div class="card"><span>🌸</span>Perfumería</div>
      <div class="card"><span>💄</span>Cosméticos</div>
    </div>
  </section>

  <section class="how">
    <h3>¿Cómo comprar?</h3>
    <div class="steps">
      <div class="step">📩 Nos escribís por redes o WhatsApp</div>
      <div class="step">🛒 Elegís producto (encargo o stock)</div>
      <div class="step">✈️ Lo traemos desde USA</div>
      <div class="step">📦 Entrega segura en Costa Rica</div>
    </div>
  </section>

  <footer>
    <p><strong>Bear Shopper</strong> © 2026</p>
    <p>Compras inteligentes desde USA 🇺🇸</p>
  </footer>

</body>
</html>
