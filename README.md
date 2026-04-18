<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guilherme Truta</title>

  <!-- Fonte Syne -->
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Syne', sans-serif;
      background-color: #0d0d0d;
      color: #ffffff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      padding: 20px;
    }

    .container {
      max-width: 800px;
    }

    h1 {
      font-size: 3rem;
      font-weight: 700;
    }

    h1 span {
      color: #ff5c00;
    }

    p {
      margin-top: 20px;
      font-size: 1.1rem;
      color: #b3b3b3;
      line-height: 1.6;
    }

    .buttons {
      margin-top: 30px;
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .btn {
      padding: 12px 24px;
      border-radius: 8px;
      font-size: 0.95rem;
      cursor: pointer;
      transition: all 0.3s ease;
      text-decoration: none;
    }

    .primary {
      background-color: #ffffff;
      color: #000000;
    }

    .primary:hover {
      background-color: #e6e6e6;
    }

    .secondary {
      border: 1px solid #ffffff;
      color: #ffffff;
    }

    .secondary:hover {
      background-color: #ffffff;
      color: #000000;
    }

    .footer {
      position: absolute;
      bottom: 20px;
      font-size: 0.8rem;
      color: #666;
    }

  </style>
</head>

<body>

  <div class="container">
    <h1>Guilherme <span>Truta</span></h1>

    <p>
      Desenvolvedor Front-End apaixonado por transformar ideias em experiências digitais.
      Estudante do IFPB, focado em criar soluções úteis, modernas e bem construídas.
    </p>

    <div class="buttons">
      <a href="https://github.com/guilhermetruta" class="btn primary">Ver GitHub</a>
      <a href="#" class="btn secondary">Entrar em contato</a>
    </div>
  </div>

  <div class="footer">
    © 2026 • Construído com código e café
  </div>

</body>
</html>
