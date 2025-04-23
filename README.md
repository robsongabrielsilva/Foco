<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Checklist Diário - Estudos e Rotina</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      padding: 20px;
      max-width: 700px;
      margin: auto;
    }
    h1, h2 {
      text-align: center;
      color: #333;
    }
    .section {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    li {
      margin-bottom: 10px;
      display: flex;
      align-items: center;
    }
    input[type="checkbox"] {
      margin-right: 10px;
      width: 20px;
      height: 20px;
      appearance: none;
      border: 2px solid #888;
      border-radius: 4px;
      outline: none;
      cursor: pointer;
      position: relative;
    }
    input[type="checkbox"]:checked {
      background-color: #4CAF50;
      border-color: #4CAF50;
    }
    input[type="checkbox"]:checked::after {
      content: "\2713";
      color: white;
      font-size: 16px;
      position: absolute;
      top: 0;
      left: 4px;
    }
    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>
  <h1>✅ Checklist Diário</h1>

  <div class="section">
    <h2>☀️ Manhã</h2>
    <ul>
      <li><input type="checkbox">Acordar e café da manhã</li>
      <li><input type="checkbox">Estudo de inglês (vocabulário, leitura ou listening – 30 a 60 min)</li>
      <li><input type="checkbox">Academia (conforme divisão do treino)</li>
      <li><input type="checkbox">Banho e refeição pós-treino</li>
      <li><input type="checkbox">Organização do dia / anotações no planner (5 min)</li>
    </ul>
  </div>

  <div class="section">
    <h2>🌤 Tarde</h2>
    <ul>
      <li><input type="checkbox">Estudo de Leis (para concurso – 1h a 1h30)</li>
      <li><input type="checkbox">Trabalho / compromissos profissionais</li>
      <li><input type="checkbox">Refeição + pausa</li>
    </ul>
  </div>

  <div class="section">
    <h2>🌙 Noite</h2>
    <ul>
      <li><input type="checkbox">Estudo para pesquisa / leitura acadêmica (1h)</li>
      <li><input type="checkbox">Atividade física (funcional ou vôlei, conforme o dia)</li>
      <li><input type="checkbox">Refeição leve</li>
      <li><input type="checkbox">Revisão rápida (15 min do que foi estudado no dia)</li>
      <li><input type="checkbox">Momento de descanso / lazer</li>
      <li><input type="checkbox">Dormir bem 😴</li>
    </ul>
  </div>

  <div class="footer">
    Desenvolvido com 💻 para ajudar na sua organização e foco!
  </div>
</body>
</html>
