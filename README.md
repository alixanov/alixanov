<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>alixanov — GitHub Profile</title>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet"/>
  <link href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg-primary: #ffffff;
      --bg-secondary: #f5f5f4;
      --bg-info: #e6f1fb;
      --text-primary: #0a0a0a;
      --text-secondary: #6b7280;
      --text-info: #185fa5;
      --border: rgba(0,0,0,0.1);
      --border-md: rgba(0,0,0,0.15);
      --radius-md: 8px;
      --radius-lg: 12px;
    }

    @media (prefers-color-scheme: dark) {
      :root {
        --bg-primary: #1c1c1e;
        --bg-secondary: #2c2c2e;
        --bg-info: #0c447c;
        --text-primary: #f9fafb;
        --text-secondary: #9ca3af;
        --text-info: #85b7eb;
        --border: rgba(255,255,255,0.1);
        --border-md: rgba(255,255,255,0.15);
      }
    }

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: var(--bg-primary);
      color: var(--text-primary);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 48px 20px;
    }

    .root {
      width: 100%;
      max-width: 680px;
    }

    .section-label {
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: var(--text-secondary);
      margin: 0 0 10px;
    }

    .card {
      background: var(--bg-primary);
      border: 0.5px solid var(--border-md);
      border-radius: var(--radius-lg);
      padding: 1.25rem 1.5rem;
    }

    .stat-card {
      background: var(--bg-secondary);
      border-radius: var(--radius-md);
      padding: 1rem 1.25rem;
    }

    .stat-label {
      font-size: 12px;
      color: var(--text-secondary);
      margin-bottom: 4px;
      display: flex;
      align-items: center;
      gap: 4px;
    }

    .stat-value {
      font-size: 22px;
      font-weight: 500;
      color: var(--text-primary);
    }

    .tech-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .tech-pill {
      display: flex;
      align-items: center;
      gap: 6px;
      padding: 6px 12px;
      background: var(--bg-secondary);
      border: 0.5px solid var(--border);
      border-radius: 999px;
      font-size: 13px;
      color: var(--text-primary);
    }

    .tech-pill img {
      width: 18px;
      height: 18px;
      border-radius: 3px;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 10px;
      margin-bottom: 10px;
    }

    .lang-bar {
      display: flex;
      height: 6px;
      border-radius: 999px;
      overflow: hidden;
      gap: 2px;
      margin: 12px 0 10px;
    }

    .lang-item {
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 12px;
      color: var(--text-secondary);
      margin-right: 14px;
      margin-bottom: 4px;
    }

    .lang-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      flex-shrink: 0;
    }

    .activity-row {
      display: flex;
      flex-wrap: wrap;
      gap: 3px;
      margin-top: 4px;
    }

    .day-cell {
      width: 10px;
      height: 10px;
      border-radius: 2px;
    }

    .contact-row {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }

    .contact-btn {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 8px 18px;
      border: 0.5px solid var(--border-md);
      border-radius: var(--radius-md);
      font-size: 13px;
      font-weight: 500;
      color: var(--text-primary);
      text-decoration: none;
      background: var(--bg-primary);
      cursor: pointer;
      transition: background 0.15s;
      font-family: inherit;
    }

    .contact-btn:hover { background: var(--bg-secondary); }

    .avatar {
      width: 56px;
      height: 56px;
      border-radius: 50%;
      background: var(--bg-info);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 20px;
      font-weight: 500;
      color: var(--text-info);
      flex-shrink: 0;
    }

    .section-gap { margin-top: 1.75rem; }

    .hero-card {
      display: flex;
      align-items: center;
      gap: 16px;
      margin-bottom: 1.75rem;
    }

    .hero-info { flex: 1; min-width: 0; }
    .hero-name { font-size: 17px; font-weight: 500; color: var(--text-primary); }
    .hero-sub { font-size: 13px; color: var(--text-secondary); margin-top: 2px; }

    .ghost-btn {
      display: flex;
      align-items: center;
      gap: 6px;
      padding: 6px 14px;
      border: 0.5px solid var(--border-md);
      border-radius: var(--radius-md);
      font-size: 12px;
      font-weight: 500;
      color: var(--text-primary);
      text-decoration: none;
      background: var(--bg-primary);
      white-space: nowrap;
      transition: background 0.15s;
    }

    .ghost-btn:hover { background: var(--bg-secondary); }

    .legend-row {
      display: flex;
      align-items: center;
      gap: 3px;
      margin-top: 8px;
      font-size: 11px;
      color: var(--text-secondary);
    }
  </style>
</head>
<body>
  <div class="root">

    <!-- Hero -->
    <div class="card hero-card">
      <div class="avatar">AL</div>
      <div class="hero-info">
        <p class="hero-name">alixanov</p>
        <p class="hero-sub">Fullstack developer · Tashkent, UZ</p>
      </div>
      <a href="https://github.com/alixanov" class="ghost-btn" target="_blank">
        <i class="ti ti-brand-github"></i> GitHub
      </a>
    </div>

    <!-- Технологии -->
    <p class="section-label">Инструменты и технологии</p>
    <div class="card">
      <div class="tech-grid">
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=react" alt="React"/>React</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js"/>Node.js</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=js" alt="JavaScript"/>JavaScript</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=angular" alt="Angular"/>Angular</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=cpp" alt="C++"/>C++</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=html" alt="HTML5"/>HTML5</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=css" alt="CSS3"/>CSS3</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=docker" alt="Docker"/>Docker</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=git" alt="Git"/>Git</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=vscode" alt="VS Code"/>VS Code</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=bash" alt="Bash"/>Bash</div>
        <div class="tech-pill"><img src="https://skillicons.dev/icons?i=powershell" alt="PowerShell"/>PowerShell</div>
      </div>
    </div>

    <!-- Статистика -->
    <div class="section-gap">
      <p class="section-label">Статистика GitHub</p>
      <div class="stats-grid">
        <div class="stat-card">
          <p class="stat-label"><i class="ti ti-git-commit"></i> Коммиты</p>
          <p class="stat-value">1 240</p>
        </div>
        <div class="stat-card">
          <p class="stat-label"><i class="ti ti-folder"></i> Репозитории</p>
          <p class="stat-value">38</p>
        </div>
        <div class="stat-card">
          <p class="stat-label"><i class="ti ti-star"></i> Звёзды</p>
          <p class="stat-value">74</p>
        </div>
      </div>

      <!-- Языки -->
      <div class="card">
        <p style="font-size:13px; font-weight:500; color:var(--text-primary); margin-bottom:10px;">Языки</p>
        <div class="lang-bar">
          <div style="flex:45; background:#378ADD; border-radius:999px 0 0 999px;"></div>
          <div style="flex:25; background:#E24B4A;"></div>
          <div style="flex:15; background:#1D9E75;"></div>
          <div style="flex:10; background:#EF9F27;"></div>
          <div style="flex:5;  background:#888780; border-radius:0 999px 999px 0;"></div>
        </div>
        <div style="display:flex; flex-wrap:wrap;">
          <div class="lang-item"><span class="lang-dot" style="background:#378ADD;"></span>JavaScript 45%</div>
          <div class="lang-item"><span class="lang-dot" style="background:#E24B4A;"></span>HTML 25%</div>
          <div class="lang-item"><span class="lang-dot" style="background:#1D9E75;"></span>CSS 15%</div>
          <div class="lang-item"><span class="lang-dot" style="background:#EF9F27;"></span>C++ 10%</div>
          <div class="lang-item"><span class="lang-dot" style="background:#888780;"></span>Other 5%</div>
        </div>
      </div>

      <!-- Heatmap -->
      <div class="card" style="margin-top:10px;">
        <p style="font-size:13px; font-weight:500; color:var(--text-primary); margin-bottom:8px;">Активность за год</p>
        <div class="activity-row" id="heatmap"></div>
        <div class="legend-row">
          Меньше <span id="legend"></span> Больше
        </div>
      </div>
    </div>

    <!-- Контакты -->
    <div class="section-gap">
      <p class="section-label">Связаться</p>
      <div class="card">
        <div class="contact-row">
          <a href="https://www.instagram.com/alikhanov.13/" class="contact-btn" target="_blank">
            <i class="ti ti-brand-instagram" style="font-size:16px; color:#E4405F;"></i> Instagram
          </a>
          <a href="https://t.me/alikhanov13" class="contact-btn" target="_blank">
            <i class="ti ti-brand-telegram" style="font-size:16px; color:#229ED9;"></i> Telegram
          </a>
          <a href="https://github.com/alixanov" class="contact-btn" target="_blank">
            <i class="ti ti-brand-github" style="font-size:16px;"></i> GitHub
          </a>
        </div>
      </div>
    </div>

  </div>

  <script>
    const heatmap = document.getElementById('heatmap');
    const levels = ['#e5e7eb','#B5D4F4','#378ADD','#185FA5','#042C53'];

    for (let i = 0; i < 52 * 7; i++) {
      const d = document.createElement('div');
      const r = Math.random();
      const lvl = r < 0.4 ? 0 : r < 0.65 ? 1 : r < 0.82 ? 2 : r < 0.93 ? 3 : 4;
      d.style.cssText = `width:10px;height:10px;border-radius:2px;background:${levels[lvl]};`;
      heatmap.appendChild(d);
    }

    const leg = document.getElementById('legend');
    levels.forEach(c => {
      const s = document.createElement('span');
      s.style.cssText = `display:inline-block;width:10px;height:10px;border-radius:2px;background:${c};margin:0 2px;vertical-align:middle;`;
      leg.appendChild(s);
    });
  </script>
</body>
</html>
