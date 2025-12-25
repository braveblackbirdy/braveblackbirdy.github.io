<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Аня — Джун-тестировщик | Портфолио</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
  :root{
    --bg:#f7f5f2;          /* тёплый светлый беж */
    --card:#ffffff;
    --muted:#8c8c87;       /* мягкий серо‑оливковый */
    --accent:#9aa88f;      /* спокойный оливковый */
    --accent-light:#dfe4db;
    --radius:14px;
    --maxw:900px;
    color-scheme: light;
  }

  *{box-sizing:border-box}
  body{
    font-family:Inter,system-ui,Segoe UI,Roboto,Arial;
    margin:0;
    background:linear-gradient(180deg,var(--bg) 0%, #f2f0ec 100%);
    color:#2a2a28;
    line-height:1.5;
  }

  .wrap{
    max-width:var(--maxw); 
    margin:0 auto; 
    padding:20px;
  }
  
  .card{
    background:var(--card);
    border-radius:var(--radius);
    padding:24px;
    box-shadow:0 8px 30px rgba(40,40,40,0.06);
    display:grid;
    grid-template-columns: 1fr 320px;
    gap:28px;
    align-items:start;
  }

  .main-content {
    padding:0;
  }
  
  .content-card {
    background: var(--card);
    border-radius: var(--radius);
    padding:28px;
    box-shadow:0 8px 30px rgba(40,40,40,0.06);
  }
  
  .profile-photo{
    width:140px;
    height:140px;
    object-fit:cover;
    border-radius:14px;
    box-shadow:0 4px 16px rgba(0,0,0,0.08);
    margin-bottom:20px;
    display:block;
  }
  
  h1{
    font-size:24px;
    font-weight:700;
    color:#2a2a28;
    margin:0 0 16px 0;
    line-height:1.3;
  }
  
  h2{
    font-size:18px;
    font-weight:600;
    color:#7365a3;
    margin:0 0 16px 0;
    text-transform:uppercase;
    letter-spacing:0.05em;
  }
  
  section{
    margin-bottom:32px;
  }
  
  section:last-child{
    margin-bottom:0;
  }
  
  p{
    font-size:16px;
    color:#4a4a46;
    margin:0 0 16px 0;
    line-height:1.6;
  }
  
  p:last-child{
    margin-bottom:0;
  }
  
  ul{
    padding-left:20px;
    margin:0 0 20px 0;
  }
  
  ul:last-child{
    margin-bottom:0;
  }
  
  li{
    margin-bottom:8px;
    font-size:16px;
    color:#4a4a46;
    line-height:1.5;
  }
  
  .contacts{
    display:flex;
    flex-direction:column;
    gap:12px;
    margin-bottom:24px;
  }
  
  .contact-header{
    display:flex;
    gap:12px;
    align-items:center;
    justify-content:space-between;
    margin-bottom:16px;
  }
  
  .contact-header strong{
    font-size:18px;
    display:block;
    margin-bottom:4px;
  }
  
  .contact-header .location{
    color:var(--muted);
    font-size:14px;
  }
  
  .contact-header .junior-badge{
    background:var(--accent-light);
    color:#4e584b;
    padding:6px 12px;
    border-radius:8px;
    font-weight:600;
    font-size:14px;
    white-space:nowrap;
  }
  
  .contact-links{
    display:flex;
    flex-direction:column;
    gap:10px;
  }
  
  .contact-links a{
    display:flex;
    align-items:center;
    gap:12px;
    padding:14px 16px;
    border-radius:12px;
    text-decoration:none;
    color:#2e2e2e;
    background:#fafafa;
    transition:all 0.2s ease;
  }
  
  .contact-links a:hover{
    background:#f0f0f0;
    transform:translateY(-2px);
  }
  
  .contact-links a span{
    flex:1;
  }
  
  .skills-grid{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin-bottom:24px;
  }
  
  .skill-tag{
    padding:10px 14px;
    background:#ffffff;
    border-radius:999px;
    font-size:14px;
    color:#474742;
    box-shadow:0 2px 8px rgba(0,0,0,0.05);
    transition:all 0.2s ease;
  }
  
  .skill-tag:hover{
    transform:translateY(-2px);
    box-shadow:0 4px 12px rgba(0,0,0,0.1);
  }
  
  .aside-section{
    margin-bottom:28px;
  }
  
  .aside-section:last-child{
    margin-bottom:0;
  }
  
  .aside-section ul{
    padding-left:18px;
  }
  
  .aside-section li{
    font-size:15px;
    margin-bottom:10px;
    color:#4a4a46;
  }
  
  .aside-section h2{
    font-size:16px;
    margin-bottom:12px;
    color:#7365a3;
  }
  
  footer{
    margin-top:24px;
    text-align:center;
    color:var(--muted);
    font-size:14px;
    padding:20px 0;
    border-top:1px solid rgba(0,0,0,0.05);
  }

  /* ===== МОБИЛЬНАЯ ВЕРСИЯ ===== */
  @media (max-width: 768px) {
    .wrap{
      padding:16px;
    }
    
    .card{
      grid-template-columns:1fr;
      padding:20px;
      gap:24px;
      border-radius:12px;
    }
    
    .content-card{
      padding:20px;
      border-radius:12px;
    }
    
    .profile-photo{
      width:120px;
      height:120px;
      margin:0 auto 20px;
    }
    
    h1{
      font-size:22px;
      text-align:center;
      margin-bottom:20px;
    }
    
    h2{
      font-size:16px;
      margin-bottom:14px;
    }
    
    section{
      margin-bottom:28px;
    }
    
    p{
      font-size:15px;
      text-align:center;
      margin-bottom:16px;
    }
    
    ul{
      padding-left:18px;
    }
    
    li{
      font-size:15px;
      margin-bottom:8px;
    }
    
    /* Сайдбар становится карточкой */
    .right{
      order:2;
      padding:0;
    }
    
    .card-aside{
      background:var(--card);
      border-radius:var(--radius);
      padding:24px;
      box-shadow:0 8px 30px rgba(40,40,40,0.06);
    }
    
    .contact-header{
      flex-direction:column;
      align-items:flex-start;
      gap:8px;
      text-align:center;
    }
    
    .contact-header .junior-badge{
      align-self:center;
    }
    
    .contact-links{
      gap:8px;
    }
    
    .contact-links a{
      padding:12px 14px;
      font-size:15px;
    }
    
    .skills-grid{
      gap:8px;
    }
    
    .skill-tag{
      padding:8px 12px;
      font-size:13px;
    }
    
    .aside-section{
      margin-bottom:24px;
    }
    
    .aside-section h2{
      text-align:center;
    }
    
    .aside-section ul{
      text-align:left;
    }
    
    /* Центрирование контактов в основной части */
    #contacts ul{
      text-align:center;
      list-style:none;
      padding-left:0;
    }
    
    #contacts li{
      text-align:center;
      margin-bottom:12px;
      font-size:16px;
    }
    
    /* Навыки в основной части */
    #skills ul{
      text-align:left;
    }
    
    footer{
      font-size:13px;
      padding:16px 0;
      margin-top:20px;
    }
  }

  /* Еще меньшие экраны */
  @media (max-width: 480px) {
    .wrap{
      padding:12px;
    }
    
    .card{
      padding:16px;
      gap:20px;
      border-radius:10px;
    }
    
    .content-card{
      padding:20px;
      border-radius:10px;
    }
    
    .profile-photo{
      width:100px;
      height:100px;
    }
    
    h1{
      font-size:20px;
    }
    
    h2{
      font-size:15px;
    }
    
    .contact-links a{
      font-size:14px;
      padding:10px 12px;
    }
    
    .skill-tag{
      padding:6px 10px;
      font-size:12px;
    }
    
    .aside-section li{
      font-size:14px;
    }
    
    footer{
      font-size:12px;
    }
  }

  /* Планшеты и промежуточные размеры */
  @media (min-width: 769px) and (max-width: 1024px) {
    .wrap{
      max-width:95%;
    }
    
    .card{
      gap:24px;
    }
    
    .right{
      width:280px;
    }
  }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="region" aria-label="Сайт-визитка Ани">
      <!-- Основной контент -->
      <main class="main-content">
        <div class="content-card">
          <section id="about">
            <img src="me.jpg" alt="Фото Ани" class="profile-photo">
            <h1>Привет! Я Аня, 27</h1>
            <p>
              Джун-тестировщик в поиске классной позиции. Раньше 6+ лет работала автором и аналитиком контента — поэтому у меня очень развита логика, внимание к деталям и умение находить несостыковки. Люблю тщательно проверять ошибки, чтобы всё работало так, как должно.
            </p>
            <p>
              Учусь тестированию, делаю тест-планы, чек-листы и тест-кейсы, оформляю баг-репорты. Хочу расти в классной продуктовой команде.
            </p>
          </section>

          <section id="skills">
            <h2>Навыки</h2>
            <ul>
              <li>Тест-дизайн: чек-листы, тест-кейсы</li>
              <li>Оформление баг-репортов</li>
              <li>Postman, Charles, Devtools, MongoDB, MYSQL, Test-it, Jira, Figma</li>
              <li>Работа с документацией (и без тоже ок!)</li>
              <li>HTML, CSS</li>
              <li>Английский C1</li>
            </ul>
          </section>

          <section id="contacts">
            <h2>Контакты</h2>
            <ul>
              <li>📍 Москва</li>
              <li>📧 braveblackbirdy@gmail.com</li>
              <li>🔗 Telegram: @braveblackbirdy</li>
            </ul>
          </section>
        </div>
      </main>

      <!-- Сайдбар -->
      <aside class="right">
        <div class="card-aside">
          <div class="contacts">
            <div class="contact-header">
              <div>
                <strong>Аня, 27</strong>
                <div class="location">Москва (готова к переезду)</div>
              </div>
              <div class="junior-badge">Джун</div>
            </div>

            <div class="contact-links">
              <a href="mailto:braveblackbirdy@gmail.com" aria-label="Email">
                <span>📧 braveblackbirdy@gmail.com</span>
              </a>
              <a href="tel:+79267960720" aria-label="Телефон">
                <span>📱 +7 (926) 796-07-20</span>
              </a>
              <a href="https://t.me/braveblackbirdy" target="_blank" rel="noopener noreferrer" aria-label="Telegram">
                <span>🔗 Telegram: @braveblackbirdy</span>
              </a>
            </div>
          </div>

          <div class="aside-section">
            <h2>Навыки и инструменты</h2>
            <div class="skills-grid">
              <div class="skill-tag">Postman</div>
              <div class="skill-tag">Devtools</div>
              <div class="skill-tag">SoapUI</div>
              <div class="skill-tag">Metabase</div>
              <div class="skill-tag">Charles</div>
              <div class="skill-tag">Kibana</div>
              <div class="skill-tag">Grafana</div>
              <div class="skill-tag">Yandex.Tracker</div>
              <div class="skill-tag">Jira</div>
              <div class="skill-tag">Тест‑кейсы</div>
              <div class="skill-tag">Баг‑репорты</div>
              <div class="skill-tag">4 языка</div>
            </div>
          </div>

          <div class="aside-section">
            <h2>Когда-то</h2>
            <ul>
              <li>Съездила на стажировку в Иран</li>
              <li>Создала контент для курсов, которые прошли ~70 000 человек (#Sekta).</li>
              <li>Собрала онлайн‑сообщество из 800+ психологов для коворкинга.</li>
            </ul>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      <div>© Аня — джун‑тестировщик • Готова к собеседованиям и тестовым заданиям.</div>
    </footer>
  </div>
</body>
</html>
