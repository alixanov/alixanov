<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>alixanov — GitHub Profile</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet"/>
<link href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}

:root{
  --bg:#ffffff;
  --bg2:#f7f7f6;
  --bg3:#f0efed;
  --bg-info:#e6f1fb;
  --text:#0a0a0a;
  --text2:#6b7280;
  --text-info:#185fa5;
  --border:rgba(0,0,0,0.08);
  --border2:rgba(0,0,0,0.13);
  --radius:8px;
  --radius-lg:14px;
}

@media(prefers-color-scheme:dark){
  :root{
    --bg:#111111;
    --bg2:#1c1c1e;
    --bg3:#2c2c2e;
    --bg-info:#0c2d4a;
    --text:#f5f5f5;
    --text2:#9ca3af;
    --text-info:#85b7eb;
    --border:rgba(255,255,255,0.07);
    --border2:rgba(255,255,255,0.12);
  }
}

body{
  font-family:'Inter',system-ui,sans-serif;
  background:var(--bg2);
  color:var(--text);
  min-height:100vh;
  padding:48px 20px;
  display:flex;
  justify-content:center;
  align-items:flex-start;
}

.root{width:100%;max-width:700px}

/* ── helpers ── */
.label{
  font-size:11px;
  font-weight:500;
  letter-spacing:.08em;
  text-transform:uppercase;
  color:var(--text2);
  margin:0 0 10px;
}

.card{
  background:var(--bg);
  border:.5px solid var(--border2);
  border-radius:var(--radius-lg);
  padding:1.25rem 1.5rem;
}

.gap{margin-top:1.75rem}

/* ── hero ── */
.hero{display:flex;align-items:center;gap:16px;margin-bottom:1.75rem}
.avatar{
  width:56px;height:56px;border-radius:50%;
  background:var(--bg-info);
  display:flex;align-items:center;justify-content:center;
  font-size:19px;font-weight:500;color:var(--text-info);flex-shrink:0;
}
.hero-name{font-size:17px;font-weight:500;color:var(--text)}
.hero-sub{font-size:13px;color:var(--text2);margin-top:3px}

.ghost{
  display:flex;align-items:center;gap:6px;
  padding:6px 14px;
  border:.5px solid var(--border2);
  border-radius:var(--radius);
  font-size:12px;font-weight:500;
  color:var(--text);text-decoration:none;
  background:var(--bg);
  transition:background .15s;white-space:nowrap;
}
.ghost:hover{background:var(--bg2)}

/* ── tech pills ── */
.tech-grid{display:flex;flex-wrap:wrap;gap:8px}
.pill{
  display:flex;align-items:center;gap:7px;
  padding:6px 13px;
  background:var(--bg2);
  border:.5px solid var(--border);
  border-radius:999px;
  font-size:13px;color:var(--text);
}
.pill img{width:18px;height:18px;border-radius:3px}

/* ── stats ── */
.stats-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px;margin-bottom:10px}
.stat{
  background:var(--bg2);
  border-radius:var(--radius);
  padding:1rem 1.25rem;
}
.stat-label{font-size:12px;color:var(--text2);margin-bottom:4px;display:flex;align-items:center;gap:4px}
.stat-value{font-size:22px;font-weight:500;color:var(--text)}

/* ── lang bar ── */
.lang-bar{display:flex;height:6px;border-radius:999px;overflow:hidden;gap:2px;margin:12px 0 10px}
.lang-list{display:flex;flex-wrap:wrap}
.lang-item{display:flex;align-items:center;gap:6px;font-size:12px;color:var(--text2);margin:0 14px 4px 0}
.lang-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}

/* ── heatmap ── */
.heat-wrap{display:flex;flex-wrap:wrap;gap:3px;margin-top:4px}
.legend-row{display:flex;align-items:center;gap:3px;margin-top:8px;font-size:11px;color:var(--text2)}

/* ── contacts ── */
.contact-row{display:flex;gap:10px;flex-wrap:wrap}
.cbtn{
  display:flex;align-items:center;gap:8px;
  padding:9px 18px;
  border:.5px solid var(--border2);
  border-radius:var(--radius);
  font-size:13px;font-weight:500;
  color:var(--text);text-decoration:none;
  background:var(--bg);
  transition:background .15s;
  font-family:inherit;
}
.cbtn:hover{background:var(--bg2)}
</style>
</head>
<body>
<div class="root">

  <!-- Hero -->
  <div class="card hero">
    <div class="avatar">AL</div>
    <div style="flex:1;min-width:0">
      <p class="hero-name">alixanov</p>
      <p class="hero-sub">Fullstack developer · Tashkent, UZ</p>
    </div>
    <a href="https://github.com/alixanov" class="ghost" target="_blank">
      <i class="ti ti-brand-github"></i> GitHub
    </a>
  </div>

  <!-- Технологии -->
  <p class="label">Инструменты и технологии</p>
  <div class="card">
    <div class="tech-grid">
      <div class="pill"><img src="https://skillicons.dev/icons?i=react"      alt="React"/>React</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=nodejs"     alt="Node.js"/>Node.js</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=js"         alt="JavaScript"/>JavaScript</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=angular"    alt="Angular"/>Angular</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=cpp"        alt="C++"/>C++</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=html"       alt="HTML5"/>HTML5</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=css"        alt="CSS3"/>CSS3</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=docker"     alt="Docker"/>Docker</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=git"        alt="Git"/>Git</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=vscode"     alt="VS Code"/>VS Code</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=bash"       alt="Bash"/>Bash</div>
      <div class="pill"><img src="https://skillicons.dev/icons?i=powershell" alt="PowerShell"/>PowerShell</div>
    </div>
  </div>

  <!-- Статистика -->
  <div class="gap">
    <p class="label">Статистика GitHub</p>

    <div class="stats-grid">
      <div class="stat">
        <p class="stat-label"><i class="ti ti-git-commit"></i>Коммиты</p>
        <p class="stat-value">1 240</p>
      </div>
      <div class="stat">
        <p class="stat-label"><i class="ti ti-folder"></i>Репозитории</p>
        <p class="stat-value">38</p>
      </div>
      <div class="stat">
        <p class="stat-label"><i class="ti ti-star"></i>Звёзды</p>
        <p class="stat-value">74</p>
      </div>
    </div>

    <!-- Языки -->
    <div class="card" style="margin-bottom:10px">
      <p style="font-size:13px;font-weight:500;color:var(--text);margin-bottom:10px">Языки</p>
      <div class="lang-bar">
        <div style="flex:45;background:#378ADD;border-radius:999px 0 0 999px"></div>
        <div style="flex:25;background:#E24B4A"></div>
        <div style="flex:15;background:#1D9E75"></div>
        <div style="flex:10;background:#EF9F27"></div>
        <div style="flex:5;background:#888780;border-radius:0 999px 999px 0"></div>
      </div>
      <div class="lang-list">
        <div class="lang-item"><span class="lang-dot" style="background:#378ADD"></span>JavaScript 45%</div>
        <div class="lang-item"><span class="lang-dot" style="background:#E24B4A"></span>HTML 25%</div>
        <div class="lang-item"><span class="lang-dot" style="background:#1D9E75"></span>CSS 15%</div>
        <div class="lang-item"><span class="lang-dot" style="background:#EF9F27"></span>C++ 10%</div>
        <div class="lang-item"><span class="lang-dot" style="background:#888780"></span>Other 5%</div>
      </div>
    </div>

    <!-- Heatmap -->
    <div class="card">
      <p style="font-size:13px;font-weight:500;color:var(--text);margin-bottom:8px">Активность за год</p>
      <div class="heat-wrap" id="heatmap"></div>
      <div class="legend-row">Меньше <span id="legend"></span> Больше</div>
    </div>
  </div>

  <!-- Контакты -->
  <div class="gap">
    <p class="label">Связаться</p>
    <div class="card">
      <div class="contact-row">
        <a href="https://www.instagram.com/alikhanov.13/" class="cbtn" target="_blank">
          <i class="ti ti-brand-instagram" style="font-size:16px;color:#E4405F"></i>Instagram
        </a>
        <a href="https://t.me/alikhanov13" class="cbtn" target="_blank">
          <i class="ti ti-brand-telegram" style="font-size:16px;color:#229ED9"></i>Telegram
        </a>
        <a href="https://github.com/alixanov" class="cbtn" target="_blank">
          <i class="ti ti-brand-github" style="font-size:16px"></i>GitHub
        </a>
      </div>
    </div>
  </div>

</div>

<script>
  const colors = ['#e5e7eb','#B5D4F4','#378ADD','#185FA5','#042C53'];
  const hm = document.getElementById('heatmap');
  for(let i=0;i<364;i++){
    const r=Math.random();
    const lvl=r<0.4?0:r<0.65?1:r<0.82?2:r<0.93?3:4;
    const d=document.createElement('div');
    d.style.cssText=`width:10px;height:10px;border-radius:2px;background:${colors[lvl]}`;
    hm.appendChild(d);
  }
  const leg=document.getElementById('legend');
  colors.forEach(c=>{
    const s=document.createElement('span');
    s.style.cssText=`display:inline-block;width:10px;height:10px;border-radius:2px;background:${c};margin:0 2px;vertical-align:middle`;
    leg.appendChild(s);
  });
</script>
</body>
</html>
