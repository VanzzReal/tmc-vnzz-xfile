<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TROUBLE MAKER CREW</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Space+Mono:wght@400;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0a0a0c;
    --surface:#151318;
    --surface-2:#1d1a21;
    --text:#ece7de;
    --text-dim:#8d8894;
    --yellow:#f4c430;
    --red:#c81e3a;
    --border:#2c2830;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:'Inter',sans-serif;
    overflow-x:hidden;
    background-image:
      radial-gradient(circle at 15% 20%, rgba(200,30,58,0.08), transparent 40%),
      radial-gradient(circle at 85% 75%, rgba(244,196,48,0.06), transparent 45%);
  }
  ::selection{background:var(--yellow);color:#0a0a0c;}

  .noise{
    position:fixed;inset:0;pointer-events:none;z-index:2;opacity:0.035;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }

  a{color:inherit;text-decoration:none;}
  .eyebrow{
    font-family:'Space Mono',monospace;
    font-size:0.72rem;
    letter-spacing:0.28em;
    text-transform:uppercase;
    color:var(--text-dim);
  }

  /* ---------- NAV ---------- */
  nav{
    position:fixed;top:0;left:0;right:0;z-index:20;
    display:flex;justify-content:space-between;align-items:center;
    padding:22px 6%;
    backdrop-filter:blur(8px);
    background:linear-gradient(to bottom, rgba(10,10,12,0.85), transparent);
  }
  .nav-mark{
    font-family:'Anton',sans-serif;
    font-size:1.15rem;
    letter-spacing:0.04em;
  }
  .nav-mark span{color:var(--red);}
  .nav-links{display:flex;gap:28px;font-family:'Space Mono',monospace;font-size:0.75rem;letter-spacing:0.08em;text-transform:uppercase;}
  .nav-links a{color:var(--text-dim);transition:color .2s;}
  .nav-links a:hover{color:var(--yellow);}
  @media(max-width:640px){.nav-links{display:none;}}

  /* ---------- HERO ---------- */
  .hero{
    min-height:100svh;
    display:flex;flex-direction:column;align-items:center;justify-content:center;
    text-align:center;position:relative;padding:120px 6% 80px;
    border-bottom:1px solid var(--border);
  }
  .hero::before{
    content:"";position:absolute;inset:0;
    background:
      linear-gradient(var(--border) 1px, transparent 1px) 0 0/100% 64px,
      linear-gradient(90deg, var(--border) 1px, transparent 1px) 0 0/64px 100%;
    opacity:0.18;mask-image:radial-gradient(ellipse at center, black 10%, transparent 70%);
  }
  .stamp{
    position:relative;
    font-family:'Space Mono',monospace;
    font-size:0.7rem;letter-spacing:0.2em;text-transform:uppercase;
    border:1.5px solid var(--red);color:var(--red);
    padding:6px 16px;border-radius:999px;
    transform:rotate(-4deg);
    margin-bottom:28px;
    animation:stampIn .6s cubic-bezier(.2,.9,.3,1.3) both;
  }
  @keyframes stampIn{from{opacity:0;transform:rotate(-4deg) scale(1.6);}to{opacity:1;transform:rotate(-4deg) scale(1);}}

  .hero h1{
    position:relative;
    font-family:'Anton',sans-serif;
    font-weight:400;
    text-transform:uppercase;
    line-height:0.92;
    font-size:clamp(3rem, 12vw, 8.5rem);
    letter-spacing:0.01em;
    background:linear-gradient(180deg,#fff 0%, var(--text) 55%, #8f8b93 100%);
    -webkit-background-clip:text;background-clip:text;color:transparent;
  }
  .hero h1 .accent{
    -webkit-text-fill-color:var(--yellow);
    color:var(--yellow);
    -webkit-background-clip:unset;background-clip:unset;
  }
  .hero-tagline{
    margin-top:26px;
    font-family:'Space Mono',monospace;
    font-style:italic;
    font-size:clamp(0.95rem,2vw,1.2rem);
    color:var(--text-dim);
    max-width:560px;
  }
  .hero-tagline::before,.hero-tagline::after{content:'"';color:var(--yellow);}

  .hero-cta{
    margin-top:44px;
    display:flex;gap:14px;flex-wrap:wrap;justify-content:center;
  }
  .btn{
    font-family:'Space Mono',monospace;
    font-size:0.78rem;letter-spacing:0.08em;text-transform:uppercase;
    padding:14px 26px;border-radius:2px;
    display:inline-flex;align-items:center;gap:10px;
    transition:transform .18s ease, box-shadow .18s ease;
  }
  .btn-primary{background:var(--yellow);color:#100f0a;font-weight:700;}
  .btn-primary:hover{transform:translateY(-3px);box-shadow:0 10px 24px rgba(244,196,48,0.25);}
  .btn-ghost{border:1px solid var(--border);color:var(--text);}
  .btn-ghost:hover{transform:translateY(-3px);border-color:var(--text-dim);}

  .stage{
    position:relative;
    width:100%;max-width:280px;
    height:60px;
    margin:22px auto 0;
  }
  .creature{
    position:absolute;top:0;left:0;
    animation:patrol 7s ease-in-out infinite;
  }
  .creature-inner{
    display:block;
    animation:dinoBob 0.5s steps(2) infinite;
    filter:drop-shadow(0 6px 8px rgba(0,0,0,0.5));
  }
  .pixel-dino{width:52px;height:44px;image-rendering:pixelated;}
  .dino-frame{opacity:0;}
  .dino-frame-a{animation:dinoStep 0.5s steps(1) infinite;}
  .dino-frame-b{animation:dinoStep 0.5s steps(1) infinite;animation-delay:0.25s;}
  @keyframes dinoStep{0%,49%{opacity:1;}50%,100%{opacity:0;}}
  @keyframes dinoBob{0%,100%{transform:translateY(0);}50%{transform:translateY(-3px);}}
  @keyframes patrol{
    0%,100%{left:0;transform:scaleX(1);}
    48%{left:calc(100% - 52px);transform:scaleX(1);}
    52%{left:calc(100% - 52px);transform:scaleX(-1);}
    98%{left:0;transform:scaleX(-1);}
  }

  .scroll-cue{
    position:absolute;bottom:34px;left:50%;transform:translateX(-50%);
    font-family:'Space Mono',monospace;font-size:0.65rem;color:var(--text-dim);
    letter-spacing:0.2em;text-transform:uppercase;
    display:flex;flex-direction:column;align-items:center;gap:8px;
  }
  .scroll-cue span{width:1px;height:30px;background:linear-gradient(var(--text-dim),transparent);animation:drop 1.6s ease-in-out infinite;}
  @keyframes drop{0%{opacity:0;transform:scaleY(0);transform-origin:top;}40%{opacity:1;transform:scaleY(1);transform-origin:top;}60%{opacity:1;transform:scaleY(1);transform-origin:bottom;}100%{opacity:0;transform:scaleY(0);transform-origin:bottom;}}

  /* ---------- SECTION SHELL ---------- */
  section{padding:100px 6%;position:relative;}
  .section-head{max-width:680px;margin:0 auto 56px;text-align:center;}
  .section-head h2{
    font-family:'Anton',sans-serif;font-weight:400;text-transform:uppercase;
    font-size:clamp(2rem,5vw,3.2rem);margin-top:10px;letter-spacing:0.01em;
    position:relative;display:inline-block;
  }
  .section-head h2::after{
    content:"";display:block;height:10px;width:70%;margin:6px auto 0;
    background:var(--red);opacity:0.85;
    clip-path:polygon(0 40%,8% 0,20% 55%,33% 5%,46% 60%,58% 8%,71% 55%,84% 10%,100% 45%,100% 100%,0 100%);
  }

  /* ---------- ABOUT ---------- */
  .about{border-bottom:1px solid var(--border);}
  .about-body{
    max-width:720px;margin:0 auto;text-align:center;
    font-size:1.05rem;line-height:1.85;color:#cdc8d0;
  }
  .about-body strong{color:var(--yellow);font-weight:600;}

  /* ---------- RULES ---------- */
  .rules{background:var(--surface);border-bottom:1px solid var(--border);}
  .rules-grid{
    max-width:1040px;margin:0 auto;
    display:grid;grid-template-columns:repeat(3,1fr);gap:1px;
    background:var(--border);border:1px solid var(--border);
  }
  @media(max-width:860px){.rules-grid{grid-template-columns:repeat(2,1fr);}}
  @media(max-width:560px){.rules-grid{grid-template-columns:1fr;}}
  .rule-card{
    background:var(--surface);padding:32px 26px;
    transition:background .2s ease;
  }
  .rule-card:hover{background:var(--surface-2);}
  .rule-id{
    font-family:'Space Mono',monospace;font-size:0.7rem;color:var(--red);
    letter-spacing:0.15em;
  }
  .rule-card h3{
    font-family:'Anton',sans-serif;font-weight:400;text-transform:uppercase;
    font-size:1.15rem;margin:10px 0 10px;letter-spacing:0.01em;
  }
  .rule-card p{font-size:0.9rem;line-height:1.6;color:var(--text-dim);}

  /* ---------- JOIN ---------- */
  .join-grid{
    max-width:980px;margin:0 auto;
    display:grid;grid-template-columns:1fr 1fr 1fr;gap:22px;
  }
  @media(max-width:820px){.join-grid{grid-template-columns:1fr;}}
  .ticket{
    position:relative;
    background:var(--surface);
    border:1px dashed var(--border);
    border-radius:4px;
    padding:30px 26px 26px;
    display:flex;flex-direction:column;gap:14px;
    transition:transform .2s ease, border-color .2s ease;
  }
  .ticket:hover{transform:translateY(-6px);border-color:var(--yellow);}
  .ticket .tag{
    align-self:flex-start;
    font-family:'Space Mono',monospace;font-size:0.65rem;letter-spacing:0.15em;text-transform:uppercase;
    padding:4px 10px;border-radius:999px;
  }
  .tag-wa{background:rgba(244,196,48,0.14);color:var(--yellow);}
  .tag-dc{background:rgba(200,30,58,0.16);color:#ff6b83;}
  .ticket h3{font-family:'Anton',sans-serif;font-weight:400;text-transform:uppercase;font-size:1.3rem;}
  .ticket p{font-size:0.88rem;color:var(--text-dim);line-height:1.55;flex-grow:1;}
  .ticket .btn{justify-content:center;margin-top:6px;}

  .rating-row{display:flex;align-items:center;gap:8px;font-family:'Space Mono',monospace;font-size:0.8rem;}
  .rating-stars{color:var(--yellow);letter-spacing:2px;font-size:0.95rem;}
  .rating-num{color:var(--text-dim);}
  .join-notes{
    list-style:none;padding:0;margin:0;
    display:flex;flex-direction:column;gap:6px;
    font-size:0.8rem;color:var(--text-dim);
  }
  .join-notes li{padding-left:16px;position:relative;line-height:1.4;}
  .join-notes li::before{
    content:"•";position:absolute;left:0;color:var(--red);
  }

  /* ---------- FOOTER ---------- */
  footer{
    padding:44px 6% 60px;text-align:center;
    font-family:'Space Mono',monospace;font-size:0.72rem;color:var(--text-dim);
    letter-spacing:0.08em;
  }
  footer .seal{
    display:inline-block;margin-bottom:18px;
    border:1.5px solid var(--border);border-radius:50%;
    width:64px;height:64px;line-height:64px;
    font-family:'Anton',sans-serif;font-size:0.85rem;color:var(--text-dim);
    transform:rotate(-6deg);
  }

  @media (prefers-reduced-motion: reduce){
    *{animation:none !important;transition:none !important;}
  }

  :focus-visible{outline:2px solid var(--yellow);outline-offset:3px;}

  /* ---------- MASCOT ---------- */
  .mascot-fab{
    position:fixed;right:10px;bottom:0;z-index:30;
    width:70px;height:88px;
    cursor:pointer;user-select:none;
    animation:idleSway 3.2s ease-in-out infinite;
    transform-origin:50% 100%;
    filter:drop-shadow(0 10px 16px rgba(0,0,0,0.55));
  }
  .mascot-fab:hover{filter:drop-shadow(0 10px 16px rgba(0,0,0,0.55)) drop-shadow(0 0 10px rgba(244,196,48,0.35));}
  .mascot-fab.poked{animation:poke .7s cubic-bezier(.34,1.6,.64,1) 1;}
  @keyframes idleSway{0%,100%{transform:rotate(-1.4deg);}50%{transform:rotate(1.4deg);}}
  @keyframes poke{
    0%{transform:scale(1) rotate(0);}
    30%{transform:scale(0.92,1.08) rotate(-5deg);}
    60%{transform:scale(1.05,0.95) translateY(-10px) rotate(4deg);}
    100%{transform:scale(1) translateY(0) rotate(0);}
  }
  .mascot-svg{width:100%;height:100%;display:block;}
  .m-arm-r{transform-box:fill-box;transform-origin:15% 8%;}
  .mascot-fab.poked .m-arm-r{animation:wave .9s ease;}
  @keyframes wave{
    0%,100%{transform:rotate(0deg);}
    25%{transform:rotate(-95deg);}
    45%{transform:rotate(-70deg);}
    65%{transform:rotate(-95deg);}
    100%{transform:rotate(0deg);}
  }
  .expr{display:none;}
  .mascot-svg[data-expr="happy"] .expr-happy{display:block;}
  .mascot-svg[data-expr="blush"] .expr-blush{display:block;}
  .mascot-svg[data-expr="angry"] .expr-angry{display:block;}
  .mascot-svg[data-expr="surprised"] .expr-surprised{display:block;}
  .mascot-fab.poked .expr{transform-box:fill-box;transform-origin:center;animation:blink .7s ease;}
  @keyframes blink{0%,40%,100%{transform:scaleY(1);}50%{transform:scaleY(0.2);}}
  .steam{animation:steamRise 1.4s ease-in-out infinite;}
  @keyframes steamRise{0%,100%{opacity:0.25;transform:translateY(0);}50%{opacity:0.9;transform:translateY(-4px);}}
  .vein{animation:veinPulse 0.9s ease-in-out infinite;}
  @keyframes veinPulse{0%,100%{opacity:0.6;}50%{opacity:1;}}
  .spark{animation:sparkPop 1s ease-in-out infinite;}
  @keyframes sparkPop{0%,100%{opacity:0.4;transform:scale(0.9);}50%{opacity:1;transform:scale(1.15);}}
  .m-strand{animation:strandSway 2.6s ease-in-out infinite;transform-box:fill-box;transform-origin:top center;}
  @keyframes strandSway{0%,100%{transform:rotate(-2deg);}50%{transform:rotate(2deg);}}

  .mascot-bubble{
    position:absolute;top:-22px;right:6px;
    background:var(--yellow);color:#100f0a;
    font-family:'Space Mono',monospace;font-size:0.72rem;font-weight:700;
    padding:8px 12px;border-radius:10px;
    max-width:170px;text-align:center;line-height:1.35;
    opacity:0;transform:translateY(6px) scale(0.9);
    transition:opacity .25s ease, transform .25s ease;
    pointer-events:none;white-space:nowrap;
  }
  .mascot-bubble::after{
    content:"";position:absolute;bottom:-6px;right:26px;
    border-width:6px 6px 0;border-style:solid;
    border-color:var(--yellow) transparent transparent;
  }
  .mascot-bubble.show{opacity:1;transform:translateY(0) scale(1);}

  @media(max-width:520px){
    .mascot-fab{width:54px;height:68px;right:8px;}
    .mascot-bubble{font-size:0.62rem;padding:6px 9px;max-width:130px;}
  }
  @media (prefers-reduced-motion: reduce){
    .mascot-fab{animation:none;}
  }
</style>
</head>
<body>
<div class="noise"></div>

<nav>
  <div class="nav-mark">TM<span>.</span>CREW</div>
  <div class="nav-links">
    <a href="#about">Tentang</a>
    <a href="#rules">Rules</a>
    <a href="#join">Join</a>
  </div>
</nav>

<header class="hero">
  <div class="stamp">Est. Solid &amp; Loyal</div>
  <h1>TROUBLE MAKER<br><span class="accent">CREW</span></h1>

  <div class="stage" aria-hidden="true">
    <div class="creature">
      <div class="creature-inner">
        <svg class="pixel-dino" viewBox="0 0 44 34" shape-rendering="crispEdges" xmlns="http://www.w3.org/2000/svg">
          <rect x="26" y="2" width="12" height="10" fill="var(--yellow)"/>
          <rect x="34" y="6" width="3" height="3" fill="#1a1710"/>
          <rect x="18" y="10" width="20" height="6" fill="var(--yellow)"/>
          <rect x="8" y="14" width="26" height="8" fill="var(--yellow)"/>
          <rect x="2" y="14" width="7" height="5" fill="var(--yellow)"/>
          <rect x="22" y="20" width="5" height="3" fill="var(--yellow)"/>
          <g class="dino-frame dino-frame-a">
            <rect x="12" y="22" width="5" height="10" fill="var(--yellow)"/>
            <rect x="27" y="22" width="5" height="10" fill="var(--yellow)"/>
          </g>
          <g class="dino-frame dino-frame-b">
            <rect x="12" y="22" width="5" height="6" fill="var(--yellow)"/>
            <rect x="8" y="27" width="7" height="3" fill="var(--yellow)"/>
            <rect x="27" y="22" width="5" height="10" fill="var(--yellow)"/>
            <rect x="31" y="30" width="7" height="2" fill="var(--yellow)"/>
          </g>
        </svg>
      </div>
    </div>
  </div>

  <p class="hero-tagline">Respect is earned, loyalty is everything.</p>
  <div class="hero-cta">
    <a class="btn btn-primary" href="#join">Gabung Crew</a>
    <a class="btn btn-ghost" href="#rules">Baca Rules</a>
  </div>
  <div class="scroll-cue"><span></span>Scroll</div>
</header>

<section class="about" id="about">
  <div class="section-head">
    <p class="eyebrow">Welcome To The Family</p>
    <h2>Bukan Sekadar Grup</h2>
  </div>
  <p class="about-body">
    <strong>Trouble Maker Crew</strong> adalah tempat buat orang-orang yang solid, loyal, dan saling respect.
    Di sini, kamu bukan cuma member — kamu bagian dari keluarga yang saling jaga satu sama lain,
    baik di obrolan sehari-hari maupun waktu mabar bareng.
  </p>
</section>

<section class="rules" id="rules">
  <div class="section-head">
    <p class="eyebrow">Kode Etik Crew</p>
    <h2>Rules</h2>
  </div>
  <div class="rules-grid">
    <div class="rule-card">
      <span class="rule-id">RULE / 01</span>
      <h3>No Jomok &amp; Gay</h3>
      <p>Jaga sopan santun dalam bercanda maupun berinteraksi sesama member.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 02</span>
      <h3>No Toxic</h3>
      <p>Bercanda boleh, menghina atau merendahkan member lain tidak.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 03</span>
      <h3>No Spam</h3>
      <p>Dilarang spam chat, stiker, link, atau promosi tanpa izin.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 04</span>
      <h3>No Konten 18+</h3>
      <p>Segala bentuk konten dewasa dilarang di seluruh ruang crew.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 05</span>
      <h3>Respect Everyone</h3>
      <p>Hormati semua member tanpa terkecuali, tanpa pandang bulu.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 06</span>
      <h3>Keep It Active</h3>
      <p>Sesekali ikut nimbrung biar GC dan server tetap hidup.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 07</span>
      <h3>No Leak</h3>
      <p>Dilarang menyebarkan isi chat, foto, atau info member ke luar tanpa izin.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 08</span>
      <h3>No Cheat &amp; Scam</h3>
      <p>Penipuan atau tindakan yang merugikan member lain akan langsung ditindak.</p>
    </div>
    <div class="rule-card">
      <span class="rule-id">RULE / 09</span>
      <h3>No Unnecessary Conflict</h3>
      <p>Ada masalah? Selesaikan secara dewasa, jangan bikin suasana makin panas.</p>
    </div>
  </div>
</section>

<section class="join" id="join">
  <div class="section-head">
    <p class="eyebrow">Masuk Ke Dalam Crew</p>
    <h2>Join Us</h2>
  </div>
  <div class="join-grid">
    <div class="ticket">
      <span class="tag tag-wa">WhatsApp</span>
      <h3>Grup Chat Utama</h3>
      <p>Obrolan harian, info crew, dan tempat kumpul semua member Trouble Maker Crew.</p>
      <div class="rating-row">
        <span class="rating-stars">★★★★★</span>
        <span class="rating-num">4.8/5 dari member</span>
      </div>
      <ul class="join-notes">
        <li>Wajib kenalan singkat pas baru join</li>
        <li>Baca dulu rules sebelum aktif chat</li>
        <li>No fake akun, no silent member selamanya</li>
      </ul>
      <a class="btn btn-primary" href="https://chat.whatsapp.com/KGvf8S6aRZ30rJIYl9lWbA?s=cl&p=a&mlu=4" target="_blank" rel="noopener">Gabung GC →</a>
    </div>
    <div class="ticket">
      <span class="tag tag-wa">WhatsApp</span>
      <h3>Saluran WA</h3>
      <p>Update, pengumuman, dan info penting crew langsung dari saluran resmi Trouble Maker Crew.</p>
      <a class="btn btn-primary" href="https://chat.whatsapp.com/KGvf8S6aRZ30rJIYl9lWbA?s=cl&amp;p=a&amp;ilr=1" target="_blank" rel="noopener">Join Saluran →</a>
    </div>
    <div class="ticket">
      <span class="tag tag-dc">Discord</span>
      <h3>Info &amp; Ngobrol</h3>
      <p>Khusus informasi, ngobrol santai, dan segala hal seputar crew di luar mabar.</p>
      <a class="btn btn-ghost" href="https://discord.gg/uUPVZcnAG" target="_blank" rel="noopener">Buka Server →</a>
    </div>
    <div class="ticket">
      <span class="tag tag-dc">Discord</span>
      <h3>Mabar Game</h3>
      <p>Server khusus buat main bareng, atur squad, dan war bareng anak crew.</p>
      <a class="btn btn-ghost" href="https://discord.gg/DCpuyE29N" target="_blank" rel="noopener">Buka Server →</a>
    </div>
  </div>
</section>

<footer>
  <div class="seal">TM<br>CREW</div>
  <div>TROUBLE MAKER CREW — RESPECT IS EARNED, LOYALTY IS EVERYTHING.</div>
  <div style="margin-top:10px;color:var(--yellow);">By: Vanzz</div>
</footer>

<div class="mascot-fab" id="mascotFab" role="button" tabindex="0" aria-label="Maskot crew, ketuk untuk berinteraksi">
  <div class="mascot-bubble" id="mascotBubble"></div>
  <svg class="mascot-svg" id="mascotSvg" data-expr="happy" viewBox="0 0 200 250" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="hairGrad" x1="0" y1="0" x2="0.3" y2="1">
        <stop offset="0%" stop-color="#33303f"/>
        <stop offset="100%" stop-color="#17151d"/>
      </linearGradient>
      <linearGradient id="skinGrad" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#fbe1c2"/>
        <stop offset="100%" stop-color="#eec89f"/>
      </linearGradient>
      <linearGradient id="jacketGrad" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#3a3742"/>
        <stop offset="100%" stop-color="#26232c"/>
      </linearGradient>
    </defs>

    <g transform="translate(0,108) scale(1,0.555) translate(0,-106)">
    <!-- ===== LEGS / PANTS ===== -->
    <rect x="70" y="210" width="27" height="112" rx="12" fill="#1d1a21" stroke="#2c2830" stroke-width="2" transform="rotate(-5 84 266)"/>
    <rect x="103" y="210" width="27" height="116" rx="12" fill="#1d1a21" stroke="#2c2830" stroke-width="2"/>

    <!-- sneakers -->
    <g transform="rotate(-8 80 322)">
      <rect x="62" y="308" width="38" height="22" rx="9" fill="#e8e6e2"/>
      <rect x="62" y="320" width="38" height="10" rx="4" fill="var(--red)"/>
      <rect x="70" y="308" width="18" height="10" rx="4" fill="var(--yellow)" opacity="0.9"/>
    </g>
    <g>
      <rect x="98" y="316" width="38" height="22" rx="9" fill="#e8e6e2"/>
      <rect x="98" y="328" width="38" height="10" rx="4" fill="var(--red)"/>
      <rect x="106" y="316" width="18" height="10" rx="4" fill="var(--yellow)" opacity="0.9"/>
    </g>

    <!-- waistband -->
    <rect x="62" y="180" width="76" height="34" rx="14" fill="#1d1a21" stroke="#2c2830" stroke-width="2"/>
    <rect x="60" y="180" width="80" height="9" rx="4" fill="#0d0c10"/>

    <!-- ===== LEFT ARM (hand in pocket) ===== -->
    <g transform="rotate(10 62 130)">
      <rect x="53" y="118" width="19" height="52" rx="9.5" fill="url(#jacketGrad)" stroke="#0d0c10" stroke-width="2"/>
    </g>

    <!-- ===== HOODIE / TORSO ===== -->
    <rect x="64" y="106" width="72" height="80" rx="24" fill="url(#jacketGrad)" stroke="#0d0c10" stroke-width="3"/>
    <path d="M78 108 Q100 96 122 108 L122 116 Q100 106 78 116 Z" fill="#1d1a21"/>
    <rect x="86" y="120" width="28" height="20" rx="6" fill="#48454f"/>
    <text x="100" y="135" font-family="Space Mono" font-size="11" font-weight="700" fill="var(--red)" text-anchor="middle">TM</text>
    <line x1="86" y1="118" x2="80" y2="150" stroke="#0d0c10" stroke-width="2" stroke-linecap="round"/>
    <line x1="114" y1="118" x2="120" y2="150" stroke="#0d0c10" stroke-width="2" stroke-linecap="round"/>
    <circle cx="80" cy="151" r="2.4" fill="#0d0c10"/>
    <circle cx="120" cy="151" r="2.4" fill="#0d0c10"/>

    <!-- ===== RIGHT ARM (waves on click) ===== -->
    <g class="m-arm-r">
      <rect x="128" y="118" width="19" height="58" rx="9.5" fill="url(#jacketGrad)" stroke="#0d0c10" stroke-width="2"/>
      <ellipse cx="137.5" cy="180" rx="8" ry="9" fill="url(#skinGrad)"/>
    </g>
    </g>

    <g transform="translate(100,58) scale(1.35) translate(-100,-70)">
    <!-- ===== HEAD ===== -->
    <circle cx="100" cy="70" r="40" fill="url(#skinGrad)"/>
    <ellipse cx="116" cy="76" rx="17" ry="13" fill="#f7c9a3" opacity="0.35"/>

    <!-- ear-adjacent hair tufts -->
    <path d="M62 66 Q57 76 62 84 Q68 76 66 68 Z" fill="url(#hairGrad)"/>
    <path d="M138 66 Q143 76 138 84 Q132 76 134 68 Z" fill="url(#hairGrad)"/>

    <!-- ===== SNAPBACK CAP ===== -->
    <path d="M58 54 Q62 22 100 22 Q138 22 142 54 Q138 44 100 42 Q62 44 58 54 Z" fill="#101014"/>
    <ellipse cx="100" cy="42" rx="40" ry="21" fill="#101014"/>
    <path d="M56 50 Q54 64 38 68 Q37 55 47 45 Q52 46 56 50 Z" fill="var(--red)" stroke="#7a1226" stroke-width="1.5"/>
    <g transform="rotate(-4 98 39)">
      <rect x="85" y="25" width="26" height="26" rx="7" fill="#0a0a0c" stroke="var(--red)" stroke-width="2"/>
      <text x="98" y="45" font-family="Anton" font-size="19" fill="var(--red)" text-anchor="middle">T</text>
    </g>
    <path class="m-strand" d="M64 52 Q60 60 64 66" stroke="#4a4558" stroke-width="1.6" fill="none" stroke-linecap="round"/>

    <!-- ===== HAPPY (default / cool & flat) ===== -->
    <g class="expr expr-happy">
      <path d="M74 61 L91 62" stroke="#0a0a0c" stroke-width="2.6" fill="none" stroke-linecap="round"/>
      <path d="M126 61 L109 62" stroke="#0a0a0c" stroke-width="2.6" fill="none" stroke-linecap="round"/>
      <ellipse cx="83" cy="74" rx="9.5" ry="10.5" fill="#0a0a0c"/>
      <ellipse cx="117" cy="74" rx="9.5" ry="10.5" fill="#0a0a0c"/>
      <path d="M74.5 68 Q83 60 91.5 68 Q83 66.5 74.5 68 Z" fill="url(#skinGrad)"/>
      <path d="M108.5 68 Q117 60 125.5 68 Q117 66.5 108.5 68 Z" fill="url(#skinGrad)"/>
      <circle cx="87" cy="70" r="2" fill="#fff"/>
      <circle cx="121" cy="70" r="2" fill="#fff"/>
      <line x1="93" y1="93" x2="107" y2="93" stroke="#0a0a0c" stroke-width="2.4" stroke-linecap="round"/>
    </g>

    <!-- ===== BLUSH ===== -->
    <g class="expr expr-blush">
      <path d="M77 70 Q83 65 89 70" stroke="#0a0a0c" stroke-width="2.4" fill="none" stroke-linecap="round"/>
      <path d="M111 70 Q117 65 123 70" stroke="#0a0a0c" stroke-width="2.4" fill="none" stroke-linecap="round"/>
      <ellipse cx="83" cy="73" rx="9" ry="11" fill="#0a0a0c"/>
      <ellipse cx="117" cy="73" rx="9" ry="11" fill="#0a0a0c"/>
      <circle cx="87" cy="68" r="2" fill="#fff"/>
      <circle cx="121" cy="68" r="2" fill="#fff"/>
      <ellipse cx="73" cy="80" rx="9" ry="5.4" fill="var(--red)" opacity="0.55"/>
      <ellipse cx="127" cy="80" rx="9" ry="5.4" fill="var(--red)" opacity="0.55"/>
      <path d="M92 89 Q100 94 108 89 Q100 93 92 89 Z" fill="#7a2733"/>
      <line class="steam" x1="62" y1="58" x2="59" y2="47" stroke="#cfcad2" stroke-width="1.8" stroke-linecap="round"/>
      <line class="steam" x1="138" y1="58" x2="141" y2="47" stroke="#cfcad2" stroke-width="1.8" stroke-linecap="round" style="animation-delay:.3s"/>
    </g>

    <!-- ===== ANGRY ===== -->
    <g class="expr expr-angry">
      <path d="M76 62 L92 68" stroke="#0a0a0c" stroke-width="2.6" stroke-linecap="round"/>
      <path d="M124 62 L108 68" stroke="#0a0a0c" stroke-width="2.6" stroke-linecap="round"/>
      <ellipse cx="83" cy="74" rx="6.4" ry="5.4" fill="#0a0a0c"/>
      <ellipse cx="117" cy="74" rx="6.4" ry="5.4" fill="#0a0a0c"/>
      <path d="M91 92 Q100 87 109 92 Q100 89 91 92 Z" fill="#7a2733"/>
      <path class="vein" d="M130 52 L134 58 L129 59 L135 66" stroke="var(--red)" stroke-width="1.8" fill="none" stroke-linecap="round"/>
    </g>

    <!-- ===== SURPRISED ===== -->
    <g class="expr expr-surprised">
      <circle cx="83" cy="72" r="9" fill="#0a0a0c"/>
      <circle cx="117" cy="72" r="9" fill="#0a0a0c"/>
      <circle cx="87" cy="67" r="2.5" fill="#fff"/>
      <circle cx="121" cy="67" r="2.5" fill="#fff"/>
      <ellipse cx="100" cy="91" rx="5.4" ry="6.2" fill="#7a2733"/>
      <ellipse cx="73" cy="82" rx="4.4" ry="2.6" fill="var(--red)" opacity="0.3"/>
      <ellipse cx="127" cy="82" rx="4.4" ry="2.6" fill="var(--red)" opacity="0.3"/>
      <text class="spark" x="146" y="22" font-family="Anton" font-size="19" fill="var(--yellow)">!</text>
    </g>
    </g>
  </svg>
</div>

<script>
  (function(){
    var fab = document.getElementById('mascotFab');
    var svg = document.getElementById('mascotSvg');
    var bubble = document.getElementById('mascotBubble');
    var lines = {
      happy: ["Gas terus, gengs! 🔥", "Solid selalu!", "Trouble Maker never quit!"],
      blush: ["Eh... jangan liatin gitu~", "Ih, jadi malu deh~", "M-makasih udah mampir..."],
      angry: ["Awas ya kalo toxic!", "Grrr, jangan curang!", "No cheat, no scam! Titik!"],
      surprised: ["Woah, member baru?!", "Eh?! Kaget nih!", "Gila, rame banget!"]
    };
    var exprs = Object.keys(lines);
    function poke(){
      fab.classList.remove('poked');
      void fab.offsetWidth;
      fab.classList.add('poked');
      var expr = exprs[Math.floor(Math.random() * exprs.length)];
      svg.setAttribute('data-expr', expr);
      var pool = lines[expr];
      bubble.textContent = pool[Math.floor(Math.random() * pool.length)];
      bubble.classList.remove('show');
      void bubble.offsetWidth;
      bubble.classList.add('show');
      clearTimeout(fab._bubbleTimer);
      fab._bubbleTimer = setTimeout(function(){
        bubble.classList.remove('show');
        svg.setAttribute('data-expr', 'happy');
      }, 1900);
    }
    fab.addEventListener('click', poke);
    fab.addEventListener('keydown', function(e){
      if(e.key === 'Enter' || e.key === ' '){ e.preventDefault(); poke(); }
    });
  })();
</script>

</body>
</html>
