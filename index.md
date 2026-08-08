<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Caio Moreno | Backend Developer & AI Engineer</title>
<style>
  :root {
    --bg: #0d1117;
    --card: #161b22;
    --text: #c9d1d9;
    --accent: #58a6ff;
    --muted: #8b949e;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Segoe UI', system-ui, sans-serif;
    line-height: 1.6;
  }
  header {
    text-align: center;
    padding: 80px 20px 40px;
  }
  header h1 { font-size: 2.5rem; color: #fff; }
  header p { color: var(--muted); font-size: 1.1rem; margin-top: 8px; }
  .links a {
    color: var(--accent);
    margin: 0 10px;
    text-decoration: none;
    font-weight: 600;
  }
  section {
    max-width: 900px;
    margin: 0 auto;
    padding: 50px 20px;
  }
  h2 {
    color: #fff;
    border-left: 4px solid var(--accent);
    padding-left: 12px;
    margin-bottom: 25px;
  }
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
  }
  .skill-card {
    background: var(--card);
    padding: 15px;
    border-radius: 8px;
  }
  .skill-card h3 { color: var(--accent); margin-bottom: 8px; font-size: 1rem; }
  .timeline-item {
    background: var(--card);
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 20px;
    border-left: 3px solid var(--accent);
  }
  .timeline-item h3 { color: #fff; }
  .timeline-item span { color: var(--muted); font-size: 0.9rem; }
  .roadmap-stage {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: var(--card);
    padding: 15px 20px;
    border-radius: 8px;
    margin-bottom: 15px;
  }
  .status {
    padding: 4px 12px;
    border-radius: 20px;
    font-size: 0.8rem;
    font-weight: 600;
  }
  .status.done { background: #238636; color: #fff; }
  .status.progress { background: #9e6a03; color: #fff; }
  .status.next { background: #30363d; color: var(--muted); }
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 20px;
  }
  .project-card {
    background: var(--card);
    padding: 20px;
    border-radius: 8px;
  }
  .project-card h3 { color: #fff; margin-bottom: 8px; }
  .project-card p { color: var(--muted); font-size: 0.95rem; margin-bottom: 10px; }
  .tag {
    display: inline-block;
    background: #21262d;
    color: var(--accent);
    padding: 2px 8px;
    border-radius: 4px;
    font-size: 0.75rem;
    margin: 2px 4px 2px 0;
  }
  .project-header {
  display: flex;
  justify-content: flex-end;
  margin-bottom: 12px;
}

.project-status {
  display: inline-block;
  padding: 4px 10px;
  border-radius: 999px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.03em;
}

.project-status.completed {
  background: #238636;
  color: #ffffff;
}

.project-status.in-progress {
  background: #9e6a03;
  color: #ffffff;
}

.tags {
  margin-top: 14px;
}

.project-features {
  color: var(--muted);
  padding-left: 20px;
  margin: 14px 0;
  font-size: 0.9rem;
}

.project-features li {
  margin-bottom: 5px;
}

  footer {
    text-align: center;
    padding: 40px 20px;
    color: var(--muted);
  }
</style>
</head>
<body>

<header>
  <h1>Caio Moreno de Paula Lara Silva</h1>
  <p>Backend Developer & Data Engineer — evoluindo para AI Engineer</p>
  <div class="links">
    <a href="mailto:caiomoreno.caio@gmail.com">E-mail</a>
    <a href="https://www.linkedin.com/feed/">LinkedIn</a>
    <a href="https://github.com/CaioMoreno">GitHub</a>
  </div>
</header>

<section>
  <h2>Sobre mim</h2>
  <p>
  Desenvolvedor Backend e Engenheiro de Dados com experiência em Python,
  SQL/PL-SQL, APIs REST, automação e otimização de bancos de dados Oracle.
  Atualmente, estou desenvolvendo o TruckFlow, uma API de gerenciamento de
  frotas e viagens, como parte da minha evolução rumo à Engenharia de IA. 
  Inglês C2 e experiência em projetos internacionais de
  Visão Computacional e interfaces cérebro-computador.</p>
</section>

<section>
  <h2>Skills Técnicas</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <h3>Linguagens</h3>
      <p>Python, SQL (Oracle, PostgreSQL, SQLite), C++, Java, JavaScript</p>
    </div>
    <div class="skill-card">
      <h3>Backend</h3>
      <p>FastAPI, Django, APIs REST, SQLAlchemy, JWT, pytest</p>
    </div>
    <div class="skill-card">
      <h3>Dados & IA</h3>
      <p>Pandas, NumPy, PySpark, TensorFlow, PyTorch</p>
    </div>
    <div class="skill-card">
      <h3>DevOps</h3>
      <p>Git, Docker, GitHub Actions (CI/CD), Bash/Shell, Linux</p>
    </div>
  </div>
</section>

<section>
  <h2>Experiência Profissional</h2>

  <div class="timeline-item">
    <h3>Desenvolvedor PL/SQL — Reply</h3>
    <span>08/2023 – 01/2025 · Belo Horizonte, MG</span>
    <p>Otimização de scripts PL/SQL, redução de 70% no tempo de consultas, automação de fluxos
    operacionais (+20% de produtividade) e mentoria técnica de novos desenvolvedores.</p>
  </div>

  <div class="timeline-item">
    <h3>Desenvolvedor Estagiário em SQL — Banco Mercantil</h3>
    <span>07/2022 – 07/2023 · Belo Horizonte, MG</span>
    <p>Manutenção de scripts SQL para dados financeiros, automação de +30 processos internos e
    otimização de consultas críticas.</p>
  </div>

  <div class="timeline-item">
    <h3>Estagiário de TI — Rede Hospitalar MaterDei</h3>
    <span>01/2021 – 07/2021 · Belo Horizonte, MG</span>
    <p>Suporte técnico para 500+ usuários e manutenção de consultas SQL em bancos clínicos e
    administrativos.</p>
  </div>

  <div class="timeline-item">
    <h3>Estagiário de Desenvolvimento de Sistemas — ASPPREV</h3>
    <span>01/2019 – 12/2019 · Belo Horizonte, MG</span>
    <p>Desenvolvimento de aplicações web com Java, SQL, JavaScript, HTML5 e CSS.</p>
  </div>
</section>

<section>
  <h2>Jornada de Carreira — Rumo a AI Engineer</h2>

  <div class="roadmap-stage">
    <div><strong>Fundamentos</strong> — SQL, Git, Linux</div>
    <span class="status done">Concluído</span>
  </div>
  <div class="roadmap-stage">
    <div><strong>Python Backend Developer</strong> — Construindo o TruckFlow com FastAPI, PostgreSQL, Docker e CI/CD</div>
    <span class="status progress">Em andamento</span>
  </div>
  <div class="roadmap-stage">
    <div><strong>Data, ML & Applied AI</strong> — Scikit-learn, PyTorch, Hugging Face</div>
    <span class="status next">Próxima etapa</span>
  </div>
  <div class="roadmap-stage">
    <div><strong>Cloud, MLOps & LLM Engineering</strong> — RAG, Vector DBs, AI Agents</div>
    <span class="status next">Próxima etapa</span>
  </div>
</section>

<section>
  <h2>Projetos em Destaque</h2>

  <div class="projects-grid">

    <div class="project-card">
      <div class="project-header">
        <span class="project-status completed">Concluído</span>
      </div>

      <h3>AI International Camp — BCI & EEG</h3>

      <p>
        Projeto internacional desenvolvido na Northwestern Polytechnical University,
        na China, premiado com o segundo lugar. Desenvolvimento de modelos de Deep
        Learning para processamento de sinais EEG e aplicações de Brain-Computer
        Interface no controle de veículos e drones por atividade cerebral.
      </p>

      <div class="tags">
        <span class="tag">TensorFlow</span>
        <span class="tag">PyTorch</span>
        <span class="tag">Deep Learning</span>
        <span class="tag">EEG</span>
        <span class="tag">BCI</span>
      </div>
    </div>

    <div class="project-card">
      <div class="project-header">
        <span class="project-status in-progress">Em andamento</span>
      </div>

      <h3>TruckFlow</h3>

      <p>
        API de gerenciamento de frotas e viagens centrada na experiência do
        motorista. O sistema organiza motoristas, veículos, cargas e viagens,
        incluindo validações operacionais, controle de entregas e aprovação de
        alterações importantes por despachantes.
      </p>

      <ul class="project-features">
        <li>Gerenciamento de motoristas, caminhões, carretas e usuários</li>
        <li>Controle de acesso por papéis: motorista, despachante e gerente</li>
        <li>Criação de viagens e atribuição de motoristas</li>
        <li>Registro de cargas e acompanhamento de entregas</li>
        <li>Controle de paradas e períodos de descanso</li>
        <li>Atualização do status das viagens</li>
        <li>Alterações de rotas e horários</li>
        <li>Registros de abastecimento e incidentes</li>
        <li>Validação de capacidade de carga e tempo de direção</li>
        <li>Testes automatizados e pipeline de CI/CD</li>
      </ul>

      <div class="tags">
        <span class="tag">FastAPI</span>
        <span class="tag">PostgreSQL</span>
        <span class="tag">SQLAlchemy</span>
        <span class="tag">JWT</span>
        <span class="tag">Docker</span>
        <span class="tag">pytest</span>
        <span class="tag">GitHub Actions</span>
      </div>
    </div>

  </div>
</section>

<section>
  <h2>Formação Acadêmica</h2>
  <div class="timeline-item">
    <h3>Bacharelado em Ciência da Computação — UFOP</h3>
    <span>Conclusão: 04/2026</span>
  </div>
  <div class="timeline-item">
    <h3>Técnico em Desenvolvimento de Sistemas — COLTEC-UFMG</h3>
    <span>12/2019</span>
  </div>
  <div class="timeline-item">
    <h3>MOOC de Programação Avançada em Python — Universidade de Helsinque</h3>
    <span>2024</span>
  </div>
</section>

<footer>
  <p>caiomoreno.caio@gmail.com · (31) 9 8364-5905 · Belo Horizonte, MG</p>
</footer>

</body>
</html>
