<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tech Zone Imports</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #0a1a2f;
    }

    header {
      background: #0a1a2f;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      font-size: 22px;
      color: #00aaff;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .banner {
      background: linear-gradient(to right, #0a1a2f, #002244);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    .banner h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .produtos {
      padding: 40px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .card img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .card h3 {
      margin: 10px 0;
      color: #0a1a2f;
    }

    .card p {
      font-size: 16px;
      margin-bottom: 15px;
    }

    .btn-whatsapp {
      display: inline-block;
      background: #00aaff;
      color: white;
      padding: 10px 15px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn-whatsapp:hover {
      background: #0088cc;
    }

    .sobre {
      padding: 40px 20px;
      text-align: center;
      background: #f5f5f5;
    }

    footer {
      background: #0a1a2f;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tech Zone Imports</h1>
    <nav>
      <a href="#home">Início</a>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="banner" id="home">
    <h2>Celulares e Acessórios Premium</h2>
    <p>Os melhores preços com garantia de 1 ano</p>
  </section>

  <section class="produtos" id="produtos">
    <div class="card">
      <img src="https://via.placeholder.com/250x200" alt="Celular 1">
      <h3>POCO C75</h3>
      <p>8GB RAM | 256GB | Câmera 50MP</p>
      <a class="btn-whatsapp" href="https://wa.me/5531973091442?text=Olá,%20tenho%20interesse%20no%20POCO%20C75" target="_blank">Comprar no WhatsApp</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/250x200" alt="Celular 2">
      <h3>Redmi Note 14 Pro</h3>
      <p>12GB RAM | 512GB | Tela AMOLED</p>
      <a class="btn-whatsapp" href="https://wa.me/5531973091442?text=Olá,%20tenho%20interesse%20no%20Redmi%20Note%2014%20Pro" target="_blank">Comprar no WhatsApp</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/250x200" alt="Acessório">
      <h3>Fones Bluetooth</h3>
      <p>Som HD | Bateria 24h</p>
      <a class="btn-whatsapp" href="https://wa.me/5531973091442?text=Olá,%20tenho%20interesse%20nos%20Fones%20Bluetooth" target="_blank">Comprar no WhatsApp</a>
    </div>
  </section>

  <section class="sobre" id="contato">
    <h2>Sobre a Tech Zone Imports</h2>
    <p>Somos especializados na venda de celulares e acessórios importados, oferecendo garantia de 1 ano e suporte completo para nossos clientes.</p>
  </section>

  <footer>
    <p>📞 WhatsApp: (31) 9 7309-1442</p>
    <p>© 2025 Tech Zone Imports - Todos os direitos reservados</p>
  </footer>

</body>
</html>
