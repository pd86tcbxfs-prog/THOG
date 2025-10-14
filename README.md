# THOG 
Índex.html 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The House of G</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    header {
      background-color: #000;
      color: gold;
      width: 100%;
      padding: 20px 0;
      font-size: 2em;
      font-weight: bold;
    }

    main {
      padding: 30px 20px;
      max-width: 600px;
    }

    h2 {
      color: #000;
      margin-bottom: 10px;
    }

    p {
      margin-bottom: 20px;
    }

    .planos {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-bottom: 30px;
    }

    .plano {
      background: #fff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }

    .plano span {
      font-weight: bold;
      color: #000;
    }

    a.botao {
      display: inline-block;
      background: gold;
      color: #000;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
      transition: 0.3s;
    }

    a.botao:hover {
      background: darkgoldenrod;
    }
  </style>
</head>
<body>
  <header>
    The House of G
  </header>
  <main>
    <h2>Bem-vindo(a)!</h2>
    <p>Conheça nossos planos de acesso e entre em contato pelo Instagram para cadastro e atendimento personalizado.</p>

    <div class="planos">
      <div class="plano">Diário: <span>R$ 79,90</span></div>
      <div class="plano">Semanal: <span>R$ 119,00</span></div>
    </div>

    <a class="botao" href="https://www.instagram.com/thehouseofg__/" target="_blank">
      Acessar pelo Instagram
    </a>
  </main>
</body>
</html>
