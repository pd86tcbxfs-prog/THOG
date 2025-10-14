# THOG
Meu projeto 
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>The House of G — Exclusivo & Discreto</title>
  <meta name="description" content="The House of G — Conteúdo exclusivo no Instagram e encontros para eventos, festas e viagens. Assinaturas diário, semanal e mensal." />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#070606;
      --panel:#0f0f0f;
      --gold:#c9a74a;
      --gold-dark:#9b7d2a;
      --muted:#bfb7b0;
      --pearl:#f6f5f3;
      --glass: rgba(255,255,255,0.02);
      --radius:14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Montserrat,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;color:var(--pearl);background:linear-gradient(180deg,#040404 0%, #0b0b0b 100%);-webkit-font-smoothing:antialiased}
    a{color:inherit;text-decoration:none}
    header{position:fixed;top:0;left:0;right:0;z-index:60;display:flex;align-items:center;justify-content:space-between;padding:14px 28px;background:linear-gradient(180deg, rgba(0,0,0,0.35), rgba(0,0,0,0.06));backdrop-filter: blur(6px);border-bottom:1px solid rgba(255,255,255,0.03)}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{display:flex;align-items:center;gap:8px}
    .logo h2{font-family:Playfair Display,serif;margin:0;font-size:20px;letter-spacing:0.02em;color:var(--gold)}
    .sub{font-size:12px;color:var(--muted)}
    nav{display:flex;gap:16px;align-items:center}
    nav button{background:transparent;border:0;color:var(--muted);padding:8px 12px;border-radius:10px;font-weight:600;cursor:pointer}
    nav button.active{color:var(--pearl);background:rgba(255,255,255,0.02);box-shadow:0 1px 0 rgba(255,255,255,0.02) inset}
    .cta{background:linear-gradient(90deg,var(--gold),var(--gold-dark));padding:8px 14px;border-radius:10px;color:#060505;font-weight:700;cursor:pointer}
    /* layout */
    main{padding-top:86px}
    .container{max-width:1100px;margin:0 auto;padding:40px 20px}
    .hero{display:flex;gap:28px;align-items:center;justify-content:space-between;flex-wrap:wrap}
    .hero-left{flex:1;min-width:300px}
    h1{font-family:Playfair Display,serif;font-size:40px;margin:6px 0 12px}
    .lead{color:var(--muted);line-height:1.6;font-size:1rem;margin-bottom:20px}
    .hero-actions{display:flex;gap:12px;flex-wrap:wrap}
    .btn{padding:12px 16px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--pearl);cursor:pointer;font-weight:700}
    .btn.primary{background:linear-gradient(90deg,var(--gold),var(--gold-dark));color:#070606}
    .panel{background:linear-gradient(180deg, var(--glass), rgba(255,255,255,0.01));padding:20px;border-radius:var(--radius);border:1px solid rgba(255,255,255,0.03)}
    /* sections */
    .section-title{font-family:Playfair Display,serif;font-size:24px;margin-bottom:12px;color:var(--pearl)}
    .about p{color:var(--muted);line-height:1.7}
    /* plans */
    .plans{display:flex;gap:18px;flex-wrap:wrap;margin-top:18px}
    .plan{flex:1;min-width:220px;border-radius:12px;padding:18px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(0,0,0,0.02));border:1px solid rgba(255,255,255,0.03)}
    .plan h3{margin:0 0 8px;font-size:18px}
    .price{font-family:Playfair Display,serif;font-size:28px;color:var(--gold);margin:6px 0 10px}
    .plan small{color:var(--muted)}
    .plan .note{color:var(--muted);font-size:13px;margin-top:10px}
    /* contact */
    .contact-grid{display:flex;gap:18px;align-items:flex-start;flex-wrap:wrap}
    .contact-grid .panel{flex:1;min-width:260px}
    .socials{display:flex;gap:10px;margin-top:12px}
    .socials a{display:inline-flex;align-items:center;gap:8px;padding:10px 12px;border-radius:10px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02);color:var(--pearl)}
    .socials a .ig{font-weight:700;color:var(--gold)}
    footer{padding:20px 0;margin-top:30px;border-top:1px solid rgba(255,255,255,0.03)}
    footer .small{color:var(--muted);font-size:13px}
    /* subtle visual */
    .silhouette{opacity:0.08;filter:grayscale(60%) blur(.2px);pointer-events:none}
    /* responsive */
    @media(max-width:900px){
      .hero{flex-direction:column;align-items:flex-start}
      nav{display:none}
      header{padding:12px 16px}
    }
    @media(max-width:520px){
      h1{font-size:30px}
      .price{font-size:22px}
    }
    /* accessibility focus */
    button:focus, a:focus {outline:2px solid rgba(201,167,74,0.18); outline-offset:2px}
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo" aria-hidden="false">
        <svg width="36" height="36" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" style="filter:drop-shadow(0 2px 6px rgba(0,0,0,0.4))">
          <circle cx="32" cy="32" r="30" fill="none" stroke="url(#g1)" stroke-width="2"/>
          <defs><linearGradient id="g1" x1="0" x2="1"><stop offset="0" stop-color="#e4c36a"/><stop offset="1" stop-color="#b98b2b"/></linearGradient></defs>
          <text x="50%" y="52%" text-anchor="middle" font-family="Playfair Display,serif" font-size="22" fill="#c9a74a" font-weight="700">G</text>
        </svg>
        <div>
          <h2>The House of G</h2>
          <div class="sub">Agência & Concierge</div>
        </div>
      </div>
    </div>

    <nav role="navigation" aria-label="Navegação principal">
      <button class="tab-btn active" data-tab="home">Home</button>
      <button class="tab-btn" data-tab="about">Sobre</button>
      <button class="tab-btn" data-tab="plans">Assinaturas</button>
      <button class="tab-btn" data-tab="contact">Contato</button>
      <a class="cta" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener">Ir ao Instagram</a>
    </nav>
  </header>

  <main>
    <div class="container">

      <!-- HOME -->
      <section id="home" class="tab-panel" aria-labelledby="home">
        <div class="hero">
          <div class="hero-left">
            <p class="sub">Exclusividade • Discrição • Atendimento premium</p>
            <h1>The House of G</h1>
            <p class="lead">Somos uma vitrine discreta onde apresentamos conteúdos exclusivos das nossas acompanhantes — disponíveis para encontros casuais, festas e viagens. O atendimento e o cadastro dos clientes são realizados via Instagram.</p>

            <div class="hero-actions">
              <a class="btn primary" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener">Acessar Instagram</a>
              <button class="btn" onclick="scrollToSection('plans')">Ver Planos</button>
            </div>

            <div style="margin-top:18px" class="panel" aria-hidden="false">
              <strong>Como funciona</strong>
              <p style="color:var(--muted);margin:8px 0 0">
                1) Você acessa nosso Instagram @thehouseofg__.<br>
                2) Visualiza conteúdos exclusivos das acompanhantes (fotos, stories e highlights).<br>
                3) Para assinar ou agendar, envie mensagem direta — nosso time fará o cadastro e orientações de pagamento.<br>
                4) Assinaturas liberam acesso ao conteúdo privado e prioridade em reservas.
              </p>
            </div>
          </div>

          <div style="width:360px;min-width:260px" aria-hidden="true">
            <div class="panel" style="height:100%;display:flex;flex-direction:column;justify-content:space-between;gap:12px">
              <div>
                <h3 style="margin:0 0 6px">Destaques</h3>
                <p style="color:var(--muted);margin:0">Modelos selecionadas, atendimento 24/7 e reservas para eventos e viagens.</p>
              </div>

              <div style="display:flex;flex-direction:column;gap:10px;margin-top:6px">
                <div style="background-image:url('assets/cover.jpg');background-size:cover;background-position:center;border-radius:12px;height:170px"></div>
                <small style="color:var(--muted)">Imagens meramente ilustrativas. Perfis reais no Instagram</small>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- ABOUT -->
      <section id="about" class="tab-panel" style="display:none">
        <div class="section-title">Sobre a plataforma</div>
        <div class="panel about">
          <p>
            <strong>The House of G</strong> é uma página-curadoria no Instagram que reúne acompanhantes treinadas e selecionadas para atendimento em encontros casuais, eventos sociais e viagens. Nosso foco é oferecer conteúdo exclusivo e uma experiência de reserva segura e discreta.
          </p>

          <p style="margin-top:12px;color:var(--muted)">
            A conta no Instagram funciona como nosso catálogo principal: lá publicamos novidades, stories privados e highlights por assinatura. Todas as interações de cadastro e atendimento são realizadas através de mensagens diretas no Instagram para garantir agilidade e discrição.
          </p>

          <div style="margin-top:14px;display:flex;gap:12px;flex-wrap:wrap">
            <div class="panel" style="min-width:220px">
              <strong>Para clientes</strong>
              <p style="color:var(--muted);margin:8px 0 0">Assinaturas com acesso a conteúdos exclusivos e prioridade em reservas.</p>
            </div>
            <div class="panel" style="min-width:220px">
              <strong>Para modelos</strong>
              <p style="color:var(--muted);margin:8px 0 0">Seleção por perfil, verificação e suporte de concierge para eventos.</p>
            </div>
          </div>
        </div>
      </section>

      <!-- PLANS -->
      <section id="plans" class="tab-panel" style="display:none">
        <div class="section-title">Planos & Valores</div>

        <div class="plans" role="list">
          <!-- Diário -->
          <div class="plan panel" role="listitem" aria-label="Plano diário">
            <h3>Diário</h3>
            <div class="price">R$ 79,90</div>
            <small class="muted">Acesso por 24 horas ao conteúdo privado</small>
            <p class="note">Acesso a posts exclusivos e stories privados publicados durante o dia.</p>
            <div style="margin-top:12px">
              <a class="btn primary" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener">Assinar pelo Instagram</a>
            </div>
          </div>

          <!-- Semanal -->
          <div class="plan panel" role="listitem" aria-label="Plano semanal">
            <h3>Semanal</h3>
            <div class="price">R$ 119,90</div>
            <small class="muted">Acesso contínuo por 7 dias</small>
            <p class="note">Melhor custo benefício para quem quer acompanhar por mais tempo e receber prioridade em reservas de curto prazo.</p>
            <div style="margin-top:12px">
              <a class="btn primary" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener">Assinar pelo Instagram</a>
            </div>
          </div>

          <!-- Mensal -->
          <div class="plan panel" role="listitem" aria-label="Plano mensal">
            <h3>Mensal</h3>
            <div class="price">R$ 159,90</div>
            <small class="muted">Acesso por 30 dias</small>
            <p class="note">Assinatura completa: acesso a conteúdo exclusivo, prioridade em reservas e descontos em eventos parceiros.</p>
            <div style="margin-top:12px">
              <a class="btn primary" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener">Assinar pelo Instagram</a>
            </div>
          </div>
        </div>

        <div style="margin-top:18px;color:var(--muted)" class="panel">
          <strong>Observações</strong>
          <ul style="margin:8px 0 0;padding-left:16px;color:var(--muted);line-height:1.6">
            <li>Pagamentos e confirmações de assinatura são realizados via atendimento no Instagram.</li>
            <li>Reservas de encontros, festas e viagens são tratadas individualmente com verificação e garantias de segurança.</li>
            <li>Política de reembolso e termos serão informados durante o atendimento no Instagram.</li>
          </ul>
        </div>
      </section>

      <!-- CONTACT -->
      <section id="contact" class="tab-panel" style="display:none">
        <div class="section-title">Contato & Cadastro</div>

        <div class="contact-grid">
          <div class="panel">
            <h3 style="margin-top:0">Atendimento via Instagram</h3>
            <p style="color:var(--muted)">Todo o processo de cadastro de usuários e atendimento é feito pela nossa página no Instagram. Clique no botão abaixo para enviar uma mensagem direta e solicitar sua assinatura ou reserva.</p>

            <div class="socials" role="list">
              <a role="listitem" href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener" aria-label="Instagram The House of G">
                <span class="ig">@thehouseofg__</span>
                <span style="opacity:0.85;color:var(--muted)">Visitar & enviar DM</span>
              </a>

              <a role="listitem" href="mailto:Thehouseofg@live.com" aria-label="Enviar e-mail para Thehouseofg">
                <span style="font-weight:700">✉️</span>
                <span style="opacity:0.85;color:var(--muted)">Thehouseofg@live.com</span>
              </a>
            </div>

            <p style="color:var(--muted);margin-top:12px">Dica: ao enviar a DM, informe o plano desejado (Diário / Semanal / Mensal) e a sua disponibilidade (data/local) para agilizar o atendimento.</p>
          </div>

          <div class="panel" aria-hidden="true" style="min-width:300px">
            <h4 style="margin-top:0">FAQ Rápido</h4>
            <ul style="color:var(--muted);line-height:1.7">
              <li><strong>Como pago?</strong> O processo de pagamento será explicado no atendimento via Instagram.</li>
              <li><strong>É seguro?</strong> Trabalhamos com verificação de perfis e confirmação antes de qualquer encontro.</li>
              <li><strong>Posso cancelar?</strong> Cancelamentos e reembolsos são tratados individualmente — consulte durante o atendimento.</li>
            </ul>
          </div>
        </div>
      </section>

      <footer>
        <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
          <div class="small">© <span id="year"></span> The House of G — Todos os direitos reservados</div>
          <div class="small">Contato: <a href="mailto:Thehouseofg@live.com" style="color:var(--muted)">Thehouseofg@live.com</a> • Instagram: <a href="https://instagram.com/thehouseofg__" target="_blank" rel="noopener" style="color:var(--gold)">@thehouseofg__</a></div>
        </div>
      </footer>

    </div>
  </main>

  <script>
    // year
    document.getElementById('year').textContent = new Date().getFullYear();

    // tab navigation (abas)
    const tabs = document.querySelectorAll('.tab-btn');
    const panels = document.querySelectorAll('.tab-panel');

    function setActiveTab(tabName){
      tabs.forEach(b => {
        if(b.dataset.tab === tabName) b.classList.add('active');
        else b.classList.remove('active');
      });
      panels.forEach(p => {
        if(p.id === tabName) p.style.display = '';
        else p.style.display = 'none';
      });
      // scroll to top for better UX on mobile
      window.scrollTo({top:0,behavior:'smooth'});
    }

    tabs.forEach(btn => {
      btn.addEventListener('click', () => setActiveTab(btn.dataset.tab));
    });

    // set default
    setActiveTab('home');

    // scroll helper for buttons
    function scrollToSection(id){
      // use tab if exists
      const el = document.getElementById(id);
      if(el){
        setActiveTab(id);
      } else {
        // fallback: scroll
        window.location.hash = id;
      }
    }

    // keyboard accessibility: left/right arrows to switch tabs
    document.addEventListener('keydown', (e) => {
      const activeIndex = Array.from(tabs).findIndex(t => t.classList.contains('active'));
      if(e.key === 'ArrowRight'){
        const next = (activeIndex + 1) % tabs.length;
        setActiveTab(tabs[next].dataset.tab);
      } else if(e.key === 'ArrowLeft'){
        const prev = (activeIndex - 1 + tabs.length) % tabs.length;
        setActiveTab(tabs[prev].dataset.tab);
      }
    });
  </script>
</body>
</html>
