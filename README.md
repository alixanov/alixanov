<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alikhanov | Портфолио</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,500;14..32,600;14..32,700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', -apple-system, 'SF Pro Display', 'Helvetica Neue', sans-serif;
      background: linear-gradient(135deg, #F5F5F7 0%, #E8ECF0 100%);
      min-height: 100vh;
      padding: 48px 24px;
    }

    /* Стеклянная карточка (iOS 26 стиль) */
    .glass-card {
      background: rgba(255, 255, 255, 0.96);
      backdrop-filter: blur(20px);
      border-radius: 32px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.04), 0 1px 2px rgba(0, 0, 0, 0.02);
      border: 0.5px solid rgba(30, 58, 95, 0.08);
      transition: all 0.3s cubic-bezier(0.2, 0.9, 0.4, 1.1);
    }

    .glass-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 16px 40px rgba(0, 0, 0, 0.08);
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
    }

    /* Юридический акцент — глубокий синий */
    .legal-accent {
      color: #1E3A5F;
    }

    .legal-badge {
      background: #1E3A5F;
      color: white;
      padding: 6px 14px;
      border-radius: 40px;
      font-size: 12px;
      font-weight: 500;
      letter-spacing: 0.3px;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    /* Секции */
    .section {
      margin-bottom: 48px;
    }

    .section-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 24px;
      flex-wrap: wrap;
      gap: 16px;
    }

    .section-title {
      font-size: 20px;
      font-weight: 600;
      color: #1E3A5F;
      letter-spacing: -0.3px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .section-line {
      height: 3px;
      width: 48px;
      background: linear-gradient(90deg, #1E3A5F, #C4A43A);
      border-radius: 3px;
    }

    /* Сетка иконок */
    .icon-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 32px 24px;
    }

    .icon-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      transition: all 0.2s ease;
    }

    .icon-item:hover {
      transform: translateY(-4px);
    }

    .icon-label {
      font-size: 11px;
      font-weight: 500;
      color: #6B7A8A;
      letter-spacing: 0.3px;
    }

    /* Карточка статистики */
    .stats-wrapper {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .stats-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .stats-card {
      background: rgba(30, 58, 95, 0.03);
      border-radius: 24px;
      padding: 20px;
      border: 0.5px solid rgba(30, 58, 95, 0.1);
      transition: all 0.2s ease;
    }

    .stats-card:hover {
      background: rgba(30, 58, 95, 0.06);
      transform: translateY(-2px);
    }

    /* Контакты */
    .contacts-grid {
      display: flex;
      gap: 20px;
      justify-content: center;
      padding: 24px;
    }

    .contact-link {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 12px 28px;
      background: #1E3A5F;
      color: white;
      text-decoration: none;
      border-radius: 48px;
      font-weight: 500;
      font-size: 14px;
      transition: all 0.25s ease;
      letter-spacing: 0.3px;
    }

    .contact-link:hover {
      background: #2C5282;
      transform: scale(0.98);
      box-shadow: 0 6px 16px rgba(30, 58, 95, 0.25);
    }

    .contact-link-secondary {
      background: #FFFFFF;
      color: #1E3A5F;
      border: 1px solid #E5E5EA;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.02);
    }

    .contact-link-secondary:hover {
      background: #F5F7FA;
      transform: scale(0.98);
    }

    /* Футер */
    .footer {
      text-align: center;
      padding: 32px 24px;
      border-top: 0.5px solid rgba(30, 58, 95, 0.1);
      margin-top: 48px;
      font-size: 13px;
      color: #8E8E93;
    }

    /* Адаптивность */
    @media (max-width: 768px) {
      body { padding: 24px 16px; }
      .section-title { font-size: 18px; }
      .stats-grid { flex-direction: column; align-items: center; }
      .contact-link { padding: 10px 20px; font-size: 13px; }
      .icon-grid { gap: 16px; }
      .icon-item img { width: 44px; height: 44px; }
    }

    /* Анимация */
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .animate {
      animation: fadeInUp 0.5s cubic-bezier(0.2, 0.9, 0.4, 1.1) forwards;
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- ИНСТРУМЕНТЫ И ТЕХНОЛОГИИ -->
    <div class="section glass-card animate" style="animation-delay: 0.05s;">
      <div class="section-header" style="padding: 28px 28px 0 28px;">
        <div class="section-title">
          <span>⚡</span>
          Технологический стек
        </div>
        <div class="legal-badge">
          <span>✓</span> Сертифицировано
        </div>
      </div>
      <div class="icon-grid">
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=bash" alt="Bash" width="52" height="52"/><span class="icon-label">Bash</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=cpp" alt="C++" width="52" height="52"/><span class="icon-label">C++</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=css" alt="CSS" width="52" height="52"/><span class="icon-label">CSS3</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=js" alt="JS" width="52" height="52"/><span class="icon-label">JavaScript</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=html" alt="HTML" width="52" height="52"/><span class="icon-label">HTML5</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=docker" alt="Docker" width="52" height="52"/><span class="icon-label">Docker</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=git" alt="Git" width="52" height="52"/><span class="icon-label">Git</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=vscode" alt="VSCode" width="52" height="52"/><span class="icon-label">VS Code</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=powershell" alt="PowerShell" width="52" height="52"/><span class="icon-label">PowerShell</span></div>
        <div class="icon-item"><img src="https://skillicons.dev/icons?i=angular" alt="Angular" width="52" height="52"/><span class="icon-label">Angular</span></div>
      </div>
    </div>

    <!-- СТАТИСТИКА -->
    <div class="section glass-card animate" style="animation-delay: 0.1s;">
      <div class="section-header" style="padding: 28px 28px 0 28px;">
        <div class="section-title">
          <span>🔥</span>
          Статистика GitHub
        </div>
        <div class="legal-badge">
          <span>📊</span> Актуально
        </div>
      </div>
      <div style="padding: 28px;">
        <div class="stats-wrapper">
          <div class="stats-card">
            <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=alixanov&theme=default" alt="GitHub Profile Summary" style="width: 100%; border-radius: 16px;">
          </div>
          <div class="stats-grid">
            <div class="stats-card" style="flex: 1;">
              <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=alixanov&theme=default" alt="Languages" style="width: 100%; border-radius: 16px;">
            </div>
            <div class="stats-card" style="flex: 1;">
              <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=alixanov&theme=default" alt="Stats" style="width: 100%; border-radius: 16px;">
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- КОНТАКТЫ -->
    <div class="section glass-card animate" style="animation-delay: 0.15s;">
      <div class="section-header" style="padding: 28px 28px 0 28px;">
        <div class="section-title">
          <span>📫</span>
          Контактная информация
        </div>
        <div class="legal-badge">
          <span>⚖️</span> Связь 24/7
        </div>
      </div>
      <div class="contacts-grid">
        <a href="https://www.instagram.com/alikhanov.13/" class="contact-link" target="_blank" rel="noopener noreferrer">
          <span>📸</span> Instagram
        </a>
        <a href="https://t.me/alikhanov13" class="contact-link contact-link-secondary" target="_blank" rel="noopener noreferrer">
          <span>💬</span> Telegram
        </a>
      </div>
    </div>

    <!-- ФУТЕР -->
    <div class="footer">
      <p style="margin-bottom: 8px;">© 2026 Alikhanov — Профессиональный портфель разработчика</p>
      <p style="font-size: 11px;">Соответствует стандартам безопасности и качества</p>
    </div>

  </div>
</body>
</html>
