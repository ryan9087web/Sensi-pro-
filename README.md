# sensi pro
# Sensi-pro-
<!DOCTYPE html>

<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sensi Pro</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b10;
      color: white;
      min-height: 100vh;
    }

    header {
      padding: 25px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 32px;
      color: #00e5ff;
    }

    header p {
      margin-top: 8px;
      color: #aaa;
    }

    .container {
      padding: 20px;
      max-width: 500px;
      margin: auto;
    }

    .card {
      background: #15151d;
      border-radius: 18px;
      padding: 20px;
      margin-bottom: 15px;
      border: 1px solid #252532;
    }

    .card h2 {
      margin-bottom: 10px;
    }

    .card p {
      color: #aaa;
      line-height: 1.5;
    }

    button {
      width: 100%;
      padding: 16px;
      margin-top: 12px;
      border: none;
      border-radius: 12px;
      background: #7c3aed;
      color: white;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      opacity: 0.9;
    }

    .sensibilidade {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-top: 15px;
    }

    .item {
      background: #20202a;
      padding: 14px;
      border-radius: 12px;
      text-align: center;
    }

    .item span {
      display: block;
      color: #aaa;
      font-size: 13px;
      margin-bottom: 5px;
    }

    .item strong {
      font-size: 23px;
      color: #00e5ff;
    }
  </style>

</head>

<body>

  <header>
    <h1>🎯 SENSI PRO</h1>
    <p>Encontre sua sensibilidade ideal</p>
  </header>

  <main class="container">

```
<section class="card">
  <h2>🔥 Minha Sensibilidade</h2>
  <p>Uma configuração inicial para você testar.</p>

  <div class="sensibilidade">
    <div class="item">
      <span>Geral</span>
      <strong>96</strong>
    </div>

    <div class="item">
      <span>Red Dot</span>
      <strong>91</strong>
    </div>

    <div class="item">
      <span>Mira 2x</span>
      <strong>87</strong>
    </div>

    <div class="item">
      <span>Mira 4x</span>
      <strong>80</strong>
    </div>

    <div class="item">
      <span>AWM</span>
      <strong>58</strong>
    </div>

    <div class="item">
      <span>Olhadinha</span>
      <strong>76</strong>
    </div>
  </div>
</section>

<section class="card">
  <h2>⚡ Criar minha Sensi</h2>
  <p>Escolha seu estilo e receba uma configuração personalizada.</p>

  <button onclick="alert('Em breve vamos criar sua sensibilidade!')">
    GERAR SENSIBILIDADE
  </button>
</section>

<section class="card">
  <h2>🎯 Teste de Mira</h2>
  <p>Treine sua precisão e velocidade em um campo de testes.</p>

  <button onclick="alert('O campo de teste será adicionado na próxima etapa!')">
    TESTAR MINHA MIRA
  </button>
</section>
```

  </main>

</body>
</html>
