<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GranaGame Mobile</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background-color: #f9fafb;
      font-family: 'Poppins', sans-serif;
      color: #0a0a0a;
    }

    header {
      background: linear-gradient(180deg, #116E55 0%, #013B36 100%);
      color: white;
      text-align: center;
      padding: 60px 15px;
    }

    header img {
      width: 100px;
      height: auto;
      margin-bottom: 10px;
    }

    h1 {
      font-size: 1.8em;
      margin: 8px 0;
    }

    p {
      font-size: 0.95em;
      line-height: 1.5;
      margin: 0 20px;
    }

    .cta {
      background-color: #FFC107;
      color: #013B36;
      border: none;
      padding: 14px 30px;
      font-size: 1em;
      border-radius: 30px;
      transition: 0.3s;
      cursor: pointer;
      margin-top: 22px;
    }

    .cta:hover {
      background-color: #FFD54F;
      transform: scale(1.05);
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    .icon-section {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 25px 15px;
      margin-bottom: 25px;
    }

    form {
      background: white;
      border-radius: 12px;
      box-shadow: 0 5px 10px rgba(0,0,0,0.08);
      padding: 30px 20px;
      margin: 0 15px 60px;
    }

    form label {
      font-weight: 600;
      font-size: 0.9em;
      margin-bottom: 5px;
      display: block;
    }

    form input {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    form button {
      width: 100%;
      padding: 13px;
      border: none;
      border-radius: 8px;
      background-color: #116E55;
      color: white;
      font-size: 1em;
      cursor: pointer;
      transition: 0.3s;
    }

    form button:hover {
      background-color: #0f5844;
    }

    footer {
      text-align: center;
      background-color: #013B36;
      color: white;
      padding: 25px 15px;
      font-size: 0.85em;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://cdn.abacus.ai/images/75b42bf1-9fc6-445f-8d90-0b61df804a2f.png" alt="GranaGame Logo">
    <h1>GranaGame</h1>
    <p><strong>Suas finanças no jogo, sua vida no controle.</strong></p>
    <button class="cta" onclick="document.getElementById('form').scrollIntoView({ behavior: 'smooth' });">
      Participe da Lista VIP 🚀
    </button>
  </header>

  <section>
    <div class="icon-section">
      <h3>🎮 Gamificação Inteligente</h3>
      <p>Torne seu dinheiro um jogo divertido. Alcance metas, ganhe XP e desbloqueie conquistas reais.</p>
    </div>

    <div class="icon-section">
      <h3>🤖 Seu Coach de IA</h3>
      <p>Receba dicas automáticas e personalizadas para economizar mais e investir melhor.</p>
    </div>

    <div class="icon-section">
      <h3>📈 Seu Progresso em Tempo Real</h3>
      <p>Acompanhe seus resultados com gráficos e desafios semanais que tornam tudo leve e motivador.</p>
    </div>
  </section>

  <form id="form" action="https://forms.gle/3fcTvFheum3G4xkb8" target="_blank">
    <h3 style="text-align:center; color:#013B36;">🚀 Entre para a lista VIP</h3>
    <label>Nome</label>
    <input type="text" placeholder="Seu nome completo">
    <label>E-mail</label>
    <input type="email" placeholder="Digite seu e-mail" required>
    <label>Telefone (WhatsApp)</label>
    <input type="tel" placeholder="(XX) XXXXX-XXXX">
    <button type="submit">Quero receber novidades!</button>
  </form>

  <footer>
    © 2025 GranaGame — Suas finanças no jogo, sua vida no controle.
  </footer>

</body>
</html># index.html
