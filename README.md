<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cairo | Data Science</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      background: #1e1e1e;
      border-radius: 16px;
      padding: 2rem;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.05);
      max-width: 600px;
      width: 90%;
    }
    .toggle-btn {
      background-color: #333;
      border: none;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      cursor: pointer;
      margin-bottom: 1rem;
    }
    .lang-section {
      display: none;
    }
    .lang-section.active {
      display: block;
    }
    h1 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
    }
    p {
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="card">
    <button class="toggle-btn" onclick="toggleLanguage()">Switch Language / Trocar Idioma</button>

    <div id="en" class="lang-section active">
      <h1>Hello! I'm Cairo</h1>
      <p>
        I'm currently in the 6th semester of my Bachelor's in Data Science. I love turning data into insights — especially in the context of Formula 1.<br><br>
        My favorite tools are Python, Pandas, Scikit-learn, and PyTorch. I’m also familiar with Linux and VS Code.<br><br>
        Currently working on F1-related data projects and enhancing my Machine Learning skills.
      </p>
    </div>

    <div id="pt" class="lang-section">
      <h1>Olá! Eu sou o Cairo</h1>
      <p>
        Estou no 6º semestre da graduação em Ciência de Dados. Gosto de transformar dados em insights — especialmente no contexto da Fórmula 1.<br><br>
        Minhas ferramentas preferidas são Python, Pandas, Scikit-learn e PyTorch. Também tenho familiaridade com Linux e VS Code.<br><br>
        Atualmente estou desenvolvendo projetos de dados relacionados à F1 e aprimorando meus conhecimentos em Machine Learning.
      </p>
    </div>
  </div>

  <script>
    function toggleLanguage() {
      const en = document.getElementById("en");
      const pt = document.getElementById("pt");
      en.classList.toggle("active");
      pt.classList.toggle("active");
    }
  </script>
</body>
</html>
