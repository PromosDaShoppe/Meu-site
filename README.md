# Meu-<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>FC 26 Master — Treine, Vença, Domine</title>
  <meta name="description" content="Curso e dicas pra jogar FC 26. Aulas, treinos e acessórios com links da Shopee." />
  <!-- fonte -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0f17;
      --card:#0f1724;
      --accent:#00d2ff;
      --accent2:#7c4dff;
      --muted:#9aa6bd;
      --glass: rgba(255,255,255,0.03);
      --radius:14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;
      background: radial-gradient(1200px 400px at 10% 10%, rgba(0,210,255,0.04), transparent),
                  linear-gradient(180deg, #051021 0%, #08111b 100%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.4;
      padding-bottom:80px;
    }

    header{
      position:sticky; top:0; z-index:40;
      backdrop-filter: blur(6px);
      background: linear-gradient(180deg, rgba(6,10,18,0.6), rgba(6,10,18,0.35));
      border-bottom:1px solid rgba(255,255,255,0.03);
    }
    .container{max-width:1100px;margin:0 auto;padding:20px;}
    .nav{
      display:flex;align-items:center;justify-content:space-between;gap:16px;
    }
    .brand{display:flex;gap:12px;align-items:center}
    .logo{
      width:48px;height:48px;border-radius:10px;
      background:linear-gradient(135deg,var(--accent),var(--accent2));
      display:grid;place-items:center;font-weight:800;color:#051023;
      box-shadow: 0 6px 18px rgba(124,77,255,0.12), 0 2px 6px rgba(0,0,0,0.6);
    }
    .brand h1{font-size:18px;margin:0}
    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-weight:600}
    .cta{background:linear-gradient(90deg,var(--accent),var(--accent2));padding:10px 14px;border-radius:10px;color:#051023;font-weight:700;text-decoration:none}

    /* hero */
    .hero{
      display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:48px 0;
    }
    .hero-left h2{font-size:34px;margin:0 0 12px 0;letter-spacing:-0.5px}
    .tag{display:inline-block;background:linear-gradient(90deg,var(--accent2),var(--accent));padding:6px 10px;border-radius:999px;font-weight:700;color:#021035;margin-bottom:12px}
    .hero-left p{color:var(--muted);margin:0 0 18px}
    .btns{display:flex;gap:12px;flex-wrap:wrap}
    .btn{
      background:transparent;border:1px solid rgba(255,255,255,0.06);padding:12px 16px;border-radius:12px;color:var(--muted);text-decoration:none;font-weight:700
    }
    .main-visual{
      border-radius:16px;padding:18px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.05));
      box-shadow: 0 10px 40px rgba(0,0,0,0.6), inset 0 1px 0 rgba(255,255,255,0.02);
    }
    .game-card{
      border-radius:10px;height:240px;background-image: url('https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s='); background-size:cover;background-position:center;
      position:relative; overflow:hidden;
    }
    .glow{position:absolute;inset:0;background:linear-gradient(120deg, rgba(0,210,255,0.08), rgba(124,77,255,0.06));mix-blend-mode:overlay}
    .game-meta{position:absolute;left:16px;bottom:16px;color:#021023;background:linear-gradient(90deg,#fff, #fff0);padding:8px 12px;border-radius:8px;font-weight:800}

    /* sections */
    section{padding:28px 0}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    .card{background:var(--card);border-radius:12px;padding:16px;border:1px solid rgba(255,255,255,0.03)}
    .price{font-size:24px;font-weight:800;color:var(--accent);}

    /* shop grid */
    .shop-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .product{display:flex;flex-direction:column;gap:10px}
    .product img{width:100%;height:150px;object-fit:cover;border-radius:8px}

    /* footer */
    footer{padding:40px 0;color:var(--muted);font-size:14px}

    /* responsive */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr; text-align:center}
      .nav a{display:none}
      .shop-grid{grid-template-columns:repeat(2,1fr)}
      .grid-3{grid-template-columns:1fr}
    }
    @media (max-width:520px){
      .shop-grid{grid-template-columns:1fr}
      .game-card{height:200px}
    }

    /* small styles */
    .muted{color:var(--muted)}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);font-weight:700;color:var(--muted)}
    .faq-item{margin-bottom:12px}
    .hamburger{display:none}
    @media (max-width:980px){ .hamburger{display:block} .logo{width:44px;height:44px} }
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo">FC</div>
        <div>
          <h1>FC 26 Master</h1>
          <div class="muted" style="font-size:12px">Treine. Aprenda. Vença.</div>
        </div>
      </div>

      <div style="display:flex;align-items:center;gap:12px">
        <nav aria-label="Main navigation">
          <a href="#curso">Curso</a>
          <a href="#loja">Loja</a>
          <a href="#depoimentos">Depoimentos</a>
          <a href="#contato">Contato</a>
        </nav>
        <a class="cta" href="#precos">Comprar curso</a>
      </div>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-left">
        <span class="tag">Lançamento • FC 26</span>
        <h2>Domine FC 26 — do básico ao competitivo</h2>
        <p>Curso completo com táticas, treinos, posicionamento e atalhos de gameplay. Ideal pra jogadores que querem subir de nível rápido.</p>

        <div class="btns">
          <a class="btn" href="#curso">Ver currículo</a>
          <a class="btn" href="#loja">Acessórios (Shopee)</a>
          <a class="btn" id="openPreview" href="#precos">Comprar agora</a>
        </div>

        <div style="margin-top:18px" class="muted">Dica: poste dicas curtas no Reels/TikTok mostrando resultado antes/depois — converte muito.</div>
      </div>

      <div class="main-visual">
        <div class="game-card" role="img" aria-label="Visual do FC 26">
          <div class="glow"></div>
          <div class="game-meta">Curso + Treinos ao vivo</div>
        </div>
      </div>
    </section>

    <!-- CURSO -->
    <section id="curso">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <h3>Sobre o curso</h3>
        <div class="pill">Aulas gravadas + sessões ao vivo</div>
      </div>

      <div style="margin-top:14px" class="grid-3">
        <div class="card">
          <h4>O que você aprende</h4>
          <ul class="muted">
            <li>Posicionamento e táticas 1v1 / 5v5</li>
            <li>Treinos diários para melhorar reação e mira</li>
            <li>Comandos avançados e setups de controle</li>
          </ul>
        </div>

        <div class="card">
          <h4>Formato</h4>
          <p class="muted">Vídeos curtos, módulos, material em pdf e duas lives por mês para tirar dúvidas e analisar partidas.</p>
        </div>

        <div class="card">
          <h4>Garantia</h4>
          <p class="muted">7 dias de garantia ou seu dinheiro de volta (versão de teste grátis disponível).</p>
        </div>
      </div>
    </section>

    <!-- CURRÍCULO -->
    <section>
      <h3>Currículo rápido</h3>
      <div style="display:flex;gap:14px;margin-top:12px;flex-wrap:wrap">
        <div class="card" style="flex:1;min-width:220px">
          <h4>Módulo 1 — Fundamentos</h4>
          <p class="muted">Movimentação, configurações ideais, rotina de aquecimento.</p>
        </div>
        <div class="card" style="flex:1;min-width:220px">
          <h4>Módulo 2 — Táticas</h4>
          <p class="muted">Jogadas, leitura de jogo, sinergia de time.</p>
        </div>
        <div class="card" style="flex:1;min-width:220px">
          <h4>Módulo 3 — Competitivo</h4>
          <p class="muted">Posicionamento avançado, setups, psicologia de jogo.</p>
        </div>
      </div>
    </section>

    <!-- LOJA (Shopee) -->
    <section id="loja">
      <h3>Loja — acessórios (Shopee)</h3>
      <p class="muted">Produtos selecionados para melhorar seu setup. Use seus links de afiliado no lugar dos `SEU_LINK_SHOPEE_AQUI`.</p>

      <div class="shop-grid" style="margin-top:12px">
        <!-- Produto 1 -->
        <div class="product card">
          <img src="https://images.unsplash.com/photo-1545239351-1141bd82e8a6?q=80&w=1200&auto=format&fit=crop&s=" alt="Controle">
          <strong>Controle Pro (budget)</strong>
          <div class="muted">Compatível com mobile/PC.</div>
          <div style="display:flex;justify-content:space-between;align-items:center;margin-top:8px">
            <div class="price">R$ 89</div>
            <a class="btn" href="SEU_LINK_SHOPEE_AQUI" target="_blank" rel="noopener">Ver</a>
          </div>
        </div>

        <!-- Produto 2 -->
        <div class="product card">
          <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?q=80&w=1200&auto=format&fit=crop&s=" alt="Headset">
          <strong>Headset Gamer</strong>
          <div class="muted">Microfone e som estéreo.</div>
          <div style="display:flex;justify-content:space-between;align-items:center;margin-top:8px">
            <div class="price">R$ 129</div>
            <a class="btn" href="SEU_LINK_SHOPEE_AQUI" target="_blank" rel="noopener">Ver</a>
          </div>
        </div>

        <!-- Produto 3 -->
        <div class="product card">
          <img src="https://images.unsplash.com/photo-1545235617-9465b9f3f1c9?q=80&w=1200&auto=format&fit=crop&s=" alt="Suporte">
          <strong>Suporte/Holder</strong>
          <div class="muted">Para manter controle e postura.</div>
          <div style="display:flex;justify-content:space-between;align-items:center;margin-top:8px">
            <div class="price">R$ 39</div>
            <a class="btn" href="SEU_LINK_SHOPEE_AQUI" target="_blank" rel="noopener">Ver</a>
          </div>
        </div>
      </div>
    </section>

    <!-- PREÇOS -->
    <section id="precos">
      <h3>Planos</h3>
      <div style="display:flex;gap:12px;margin-top:12px;flex-wrap:wrap">
        <div class="card" style="flex:1;min-width:240px">
          <h4>Essencial</h4>
          <div class="price">R$ 39</div>
          <p class="muted">Acesso aos módulos gravados.</p>
          <a class="btn" href="#contato" onclick="openBuy('Essencial')">Comprar</a>
        </div>

        <div class="card" style="flex:1;min-width:240px;border:2px solid rgba(124,77,255,0.18)">
          <h4>Completo</h4>
          <div class="price">R$ 129</div>
          <p class="muted">Módulos + 2 lives por mês + grupo exclusivo.</p>
          <a class="btn" href="#contato" onclick="openBuy('Completo')">Comprar</a>
        </div>

        <div class="card" style="flex:1;min-width:240px">
          <h4>Membro VIP</h4>
          <div class="price">R$ 249</div>
          <p class="muted">Tudo + coaching individual mensal.</p>
          <a class="btn" href="#contato" onclick="openBuy('VIP')">Comprar</a>
        </div>
      </div>
    </section>

    <!-- depoimentos -->
    <section id="depoimentos">
      <h3>Depoimentos</h3>
      <div style="display:flex;gap:12px;margin-top:12px;flex-wrap:wrap">
        <div class="card" style="flex:1;min-width:260px">
          <strong>João (Top 500)</strong>
          <p class="muted">"Subi 3 divisões em 2 semanas, jogo mais confiante."</p>
        </div>
        <div class="card" style="flex:1;min-width:260px">
          <strong>Mariana</strong>
          <p class="muted">"As lives salvam — análises detalhadas do meu gameplay."</p>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section>
      <h3>Perguntas frequentes</h3>
      <div style="margin-top:12px">
        <div class="faq-item card">
          <strong>Posso fazer no celular?</strong>
          <p class="muted">Sim — o curso inclui dicas específicas para mobile e controladores.</p>
        </div>
        <div class="faq-item card">
          <strong>Como funcionam as lives?</strong>
          <p class="muted">Lives ao vivo no Discord/YouTube: análise de partidas e Q&A.</p>
        </div>
      </div>
    </section>

    <!-- contato -->
    <section id="contato">
      <h3>Contato / Comprar</h3>
      <div class="card" style="padding:18px;max-width:720px">
        <form id="contactForm">
          <label for="name">Nome</label><br>
          <input id="name" name="name" required style="width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);margin-top:6px;background:transparent;color:inherit"><br><br>

          <label for="email">E-mail / WhatsApp</label><br>
          <input id="email" name="email" required style="width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);margin-top:6px;background:transparent;color:inherit"><br><br>

          <label for="mensagem">Mensagem (ex: quero o plano Completo)</label><br>
          <textarea id="mensagem" name="mensagem" rows="3" style="width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);margin-top:6px;background:transparent;color:inherit"></textarea><br><br>

          <button type="submit" class="btn">Enviar</button>
          <span id="formStatus" style="margin-left:12px" class="muted"></span>
        </form>
      </div>
    </section>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap">
        <div class="muted">© <strong>FC 26 Master</strong> — Feito por você. Troca imagens e links e tá pronto.</div>
        <div class="muted">Made with ❤️ for gamers</div>
      </div>
    </footer>
  </main>

  <script>
    // Simples validação e comportamento do formulário (não envia nada real).
    const form = document.getElementById('contactForm');
    const status = document.getElementById('formStatus');
    form.addEventListener('submit', (e)=>{
      e.preventDefault();
      const name = form.name.value.trim();
      const email = form.email.value.trim();
      const msg = form.mensagem.value.trim();
      if(!name || !email){
        status.textContent = 'Preencha nome e e-mail/WhatsApp.';
        return;
      }
      // Aqui você pode trocar por envio real (fetch para backend ou Zapier)
      status.textContent = 'Enviado! Vou te contactar em breve.';
      form.reset();
      setTimeout(()=> status.textContent = '', 5000);
    });

    // função para abrir compra com pré-texto
    function openBuy(plano){
      const wa = encodeURIComponent(`Quero comprar o plano ${plano} — me explica como pagar e o que inclui.`);
      // substitua pelo seu número de WhatsApp com link oficial
      const waLink = `https://wa.me/SEU_NUMERO_AQUI?text=${wa}`;
      window.open(waLink,'_blank');
    }

    // preview CTA behavior (simples)
    document.getElementById('openPreview').addEventListener('click', (e)=>{
      // apenas rolar para preços
    });
  </script>
</body>
</html>
