<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Instalação de Wallbox • Recife</title>
  <meta name="description" content="Instalação profissional de carregadores elétricos (Wallbox) em Recife. Garantia, segurança e atendimento rápido via WhatsApp." />
  <style>
    :root{
      --accent: #25D366;
      --bg:#f7f8fa;
      --card:#ffffff;
      --muted:#666;
      --maxw:1100px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Arial,sans-serif;
      background:var(--bg);
      color:#111;
      -webkit-font-smoothing:antialiased;
    }
    .wrap{max-width:var(--maxw);margin:0 auto;padding:28px;}
    header{
      background:linear-gradient(90deg,#0b0b0b,#2b2b2b);
      color:white;
      padding:48px 20px;
      text-align:center;
      border-radius:8px;
    }
    header h1{margin:0;font-size:30px;letter-spacing:0.4px}
    header p{margin:10px 0 0;font-size:16px;color:#ddd}
    .cta{display:inline-block;margin-top:18px;background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700}
    main{margin-top:22px}
    .row{display:flex;gap:20px;flex-wrap:wrap}
    .card{background:var(--card);padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(12,12,12,0.06);flex:1}
    .intro{flex: 1 1 100%;text-align:center}
    h2{margin:6px 0 12px;font-size:22px;text-align:center}
    p.lead{color:var(--muted);line-height:1.5}
    /* gallery */
    .galeria{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px;margin-top:14px}
    .galeria figure{margin:0;background:#fff;border-radius:10px;overflow:hidden;box-shadow:0 6px 18px rgba(12,12,12,0.06)}
    .galeria img{display:block;width:100%;height:220px;object-fit:cover}
    figure figcaption{padding:10px;font-size:14px;color:var(--muted)}
    footer{margin-top:28px;padding:18px;text-align:center;color:#fff;background:#111;border-radius:8px}
    /* responsive */
    @media (max-width:560px){
      header{padding:30px 12px}
      .galeria img{height:180px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>Instalação de Wallbox • Recife</h1>
      <p>Instalação profissional de carregadores para veículos elétricos — residencial e condomínio.</p>
      <a class="cta" href="https://wa.me/5581981401914" target="_blank" rel="noopener">Chamar no WhatsApp</a>
    </header>

    <main>
      <section class="row">
        <div class="card intro">
          <h2>Por que contratar um profissional?</h2>
          <p class="lead">Garantimos instalação segura, dimensionamento correto, proteção e aterramento conforme normas técnicas. Fornecemos ART quando necessário e utilizamos materiais de qualidade.</p>
        </div>
      </section>

      <section class="row" aria-labelledby="galleryTitle">
        <div class="card" style="flex:1 1 100%;">
          <h2 id="galleryTitle">Galeria de Instalações</h2>
          <p class="lead" style="text-align:center">Fotos reais de algumas instalações que executamos. Clique nas imagens para ampliar.</p>

          <div class="galeria">
            <figure>
              <img src="foto01.jpg" alt="Instalação de carregador em poste de garagem" onerror="this.style.display='none'">
              <figcaption>Carregador BYD instalado em vaga de garagem</figcaption>
            </figure>

            <figure>
              <img src="foto02.jpg" alt="Carregador WEG WeMob instalado em garagem" onerror="this.style.display='none'">
              <figcaption>Carregador WEG WeMob Wall G2 — veículo Haval H6</figcaption>
            </figure>

            <figure>
              <img src="foto03.jpg" alt="Unidade de proteção e carregador GWM instalados" onerror="this.style.display='none'">
              <figcaption>Unidade com proteção (Clamper) e carregador GWM</figcaption>
            </figure>
          </div>

          <p style="text-align:center;margin-top:12px;color:var(--muted)">Se suas fotos não aparecerem, confirme que os arquivos <strong>foto01.jpg</strong>, <strong>foto02.jpg</strong> e <strong>foto03.jpg</strong> foram enviados para este repositório (<em>case-sensitive</em>).</p>
        </div>
      </section>

      <section class="row" style="margin-top:18px">
        <div class="card" style="flex:1 1 60%;">
          <h2>Serviços</h2>
          <ul style="line-height:1.6;color:var(--muted);padding-left:18px">
            <li>Instalação de Wallbox / EVSE</li>
            <li>Dimensionamento de circuito e proteção</li>
            <li>Aterramento e certificação</li>
            <li>Instalação em garagens residenciais e condomínios</li>
          </ul>
        </div>

        <div class="card" style="flex:1 1 35%;">
          <h2>Contato rápido</h2>
          <p style="color:var(--muted)">Solicite orçamento e agendamento via WhatsApp:</p>
          <p style="font-weight:700"><a href="https://wa.me/5581981401914" style="color:var(--accent);text-decoration:none" target="_blank" rel="noopener">+55 (81) 98140-1914</a></p>
        </div>
      </section>
    </main>

    <footer>
      © 2025 • Instalação de Wallbox • Recife — Site gerado automaticamente
    </footer>
  </div>

  <script>
    // Small helper: if images are missing, optionally show placeholders (keeps layout stable)
    document.querySelectorAll('.galeria img').forEach(function(img){
      img.addEventListener('error', function(){
        // show a light placeholder block instead of broken image
        var ph = document.createElement('div');
        ph.style.height = img.height + 'px';
        ph.style.background = '#e9eef4';
        ph.style.display = 'flex';
        ph.style.alignItems = 'center';
        ph.style.justifyContent = 'center';
        ph.style.color = '#7b8a99';
        ph.style.fontSize = '14px';
        ph.textContent = 'Imagem não encontrada';
        img.parentNode.replaceChild(ph, img);
      });
    });
  </script>
</body>
</html>
