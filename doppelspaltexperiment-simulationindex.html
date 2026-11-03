<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Youngs Doppelspaltexperiment – Interaktive Simulation</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,opsz,wght@0,9..40,400;0,9..40,500;0,9..40,600&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
<style>
/* ================================================================ TOKENS */
:root{
  --bg:#050b17;--bg2:#0a1220;--surf:#0f1b2d;--card:rgba(12,22,38,.82);
  --card-strong:#101d32;--bord:rgba(148,163,184,.18);--bord2:rgba(0,200,255,.32);
  --pri:#67e8f9;--pri-d:#2dd4bf;--vio:#a78bfa;--acc:#fbbf24;
  --ok:#34d399;--err:#fb7185;--ww:#f87171;
  --tx:#e2e8f0;--tx2:#b9c7dc;--mu:#7d8ca7;
  --FD:'Syne',system-ui,sans-serif;
  --FB:'DM Sans',system-ui,sans-serif;
  --FM:'JetBrains Mono','Courier New',monospace;
  --shadow-soft:0 24px 80px rgba(3, 10, 22, .45);
  --shadow-card:0 18px 40px rgba(10, 18, 32, .35);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:var(--FB);background:
    radial-gradient(circle at top left, rgba(103,232,249,.12), transparent 35%),
    radial-gradient(circle at bottom right, rgba(167,139,250,.14), transparent 32%),
    linear-gradient(180deg, var(--bg) 0%, var(--bg2) 100%);
  color:var(--tx);line-height:1.7;overflow-x:hidden;position:relative;
}
body::before, body::after {
  content:'';position:fixed;inset:auto;pointer-events:none;filter:blur(80px);opacity:.6;z-index:0;
}
body::before { width:360px;height:360px;background:rgba(99,102,241,.18);left:-80px;top:120px; }
body::after { width:420px;height:420px;background:rgba(34,211,238,.14);right:-80px;bottom:140px; }
::-webkit-scrollbar{width:5px}
::-webkit-scrollbar-track{background:rgba(5,11,23,.9)}
::-webkit-scrollbar-thumb{background:linear-gradient(180deg, rgba(103,232,249,.8), rgba(167,139,250,.8));border-radius:3px}

/* ================================================================ HERO */
#hero{
  position:relative;min-height:100vh;
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  text-align:center;padding:80px 24px 60px;overflow:hidden;z-index:1;
}
#heroCanvas{position:absolute;inset:0;width:100%;height:100%;opacity:.42;pointer-events:none}
#hero::before{
  content:'';position:absolute;inset:0;
  background:
    radial-gradient(ellipse 70% 50% at 50% 32%,rgba(103,232,249,.16) 0%,transparent 66%),
    radial-gradient(ellipse 42% 42% at 18% 78%,rgba(167,139,250,.16) 0%,transparent 60%),
    radial-gradient(ellipse 38% 34% at 86% 70%,rgba(45,212,191,.12) 0%,transparent 62%);
  pointer-events:none;
}
.hero-in{
  position:relative;z-index:2;max-width:860px;padding:32px 34px 28px;
  border:1px solid rgba(148,163,184,.18);background:rgba(7,17,28,.32);
  border-radius:30px;backdrop-filter:blur(14px);box-shadow:var(--shadow-soft);
}
.hero-badge{
  display:inline-block;font-family:var(--FM);font-size:.7rem;letter-spacing:.2em;
  text-transform:uppercase;color:var(--pri);border:1px solid rgba(103,232,249,.35);
  padding:7px 18px;border-radius:999px;margin-bottom:28px;
  background:linear-gradient(135deg, rgba(103,232,249,.08), rgba(167,139,250,.08));
}
.hero-title{
  font-family:var(--FD);font-size:clamp(2.2rem,5.2vw,4.2rem);font-weight:800;
  line-height:1.08;color:#fff;margin-bottom:20px;letter-spacing:-.04em;
  text-align:center;text-shadow:0 0 30px rgba(103,232,249,.15);
  width:100%;max-width:100%;
}
.hero-title em{
  display:block;width:100%;max-width:100%;margin:0 auto;
  text-align:center;font-style:normal;white-space:normal;
  overflow-wrap:normal;word-break:normal;line-height:.82;
  background:linear-gradient(130deg,#67e8f9 0%,#a78bfa 45%,#f9a8d4 100%);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
}
.hero-sub{font-size:clamp(.96rem,2vw,1.12rem);color:var(--tx2);max-width:620px;margin:0 auto 42px;line-height:1.8}
.hero-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
.btn{
  display:inline-flex;align-items:center;gap:8px;padding:12px 24px;border-radius:12px;
  font-family:var(--FB);font-size:.96rem;font-weight:600;cursor:pointer;border:1px solid transparent;
  transition:all .2s ease;text-decoration:none;white-space:nowrap;
}
.btn-pri{
  background:linear-gradient(135deg,#67e8f9 0%,#38bdf8 35%,#a78bfa 100%);
  color:#06131c;box-shadow:0 16px 40px rgba(56,189,248,.34);
}
.btn-pri:hover{transform:translateY(-2px);box-shadow:0 24px 55px rgba(56,189,248,.44)}
.btn-ghost{
  background:rgba(15,23,42,.42);color:var(--tx);border-color:rgba(148,163,184,.24);
  box-shadow:inset 0 0 0 1px rgba(255,255,255,.02);
}
.btn-ghost:hover{background:rgba(103,232,249,.08);border-color:rgba(103,232,249,.38);color:var(--pri)}
.btn-sm{padding:7px 14px;font-size:.82rem;border-radius:8px}
.btn-icon{padding:7px 11px}
.btn-danger{background:linear-gradient(135deg, rgba(251,113,133,.13), rgba(127,29,29,.2));border:1px solid rgba(251,113,133,.32);color:#fca5a5}
.btn-danger:hover{background:rgba(251,113,133,.18)}
.hero-scroll{
  position:absolute;bottom:32px;left:50%;transform:translateX(-50%);
  color:var(--mu);font-size:.72rem;letter-spacing:.15em;text-transform:uppercase;
  display:flex;flex-direction:column;align-items:center;gap:6px;
  animation:hScroll 2.4s ease-in-out infinite;
}
@keyframes hScroll{0%,100%{transform:translateX(-50%) translateY(0);opacity:.7}50%{transform:translateX(-50%) translateY(8px);opacity:1}}

/* ================================================================ SECTIONS */
section{padding:70px 24px}
.sec-lbl{font-family:var(--FM);font-size:.68rem;letter-spacing:.2em;text-transform:uppercase;color:var(--pri);margin-bottom:10px}
.sec-title{font-family:var(--FD);font-size:clamp(1.4rem,3vw,2rem);font-weight:700;color:#fff;margin-bottom:12px}
.sec-desc{color:var(--tx2);max-width:560px;margin:0 auto}
.sec-head{text-align:center;margin-bottom:48px}

/* ================================================================ SIMULATION */
#simSec{padding:50px clamp(16px,3vw,48px) 40px}
.sim-wrap{width:100%;max-width:1600px;margin:0 auto;display:grid;grid-template-columns:minmax(0,1fr) clamp(320px,28vw,400px);gap:clamp(20px,2.4vw,36px);align-items:start}
@media(max-width:980px){.sim-wrap{grid-template-columns:1fr}}
.cv-box{
  background:linear-gradient(180deg, rgba(15,27,45,.96), rgba(8,15,24,.96));
  border:1px solid rgba(148,163,184,.14);border-radius:22px;overflow:hidden;position:relative;
  box-shadow:var(--shadow-card);backdrop-filter:blur(12px);
}
.cv-topbar{display:flex;justify-content:space-between;align-items:center;padding:10px 14px;border-bottom:1px solid var(--bord);gap:8px;flex-wrap:wrap;background:rgba(15,23,42,.4)}
.mode-pill{display:flex;align-items:center;gap:6px;font-family:var(--FM);font-size:.68rem;color:var(--pri)}
.blink{width:6px;height:6px;border-radius:50%;background:var(--pri);box-shadow:0 0 8px var(--pri);animation:blinkAnim 2s infinite}
@keyframes blinkAnim{0%,100%{opacity:1}50%{opacity:.25}}
.bar-btns{display:flex;gap:6px}
#mainCanvas{display:block;width:100%;height:auto}
.cv-leg{display:flex;gap:14px;padding:7px 14px;border-top:1px solid var(--bord);font-family:var(--FM);font-size:.62rem;color:var(--mu);flex-wrap:wrap}
.leg-i{display:flex;align-items:center;gap:5px}
.leg-d{width:9px;height:9px;border-radius:50%;flex-shrink:0}
.graph-hdr{display:flex;align-items:center;justify-content:space-between;padding:6px 14px;border-top:1px solid var(--bord);font-family:var(--FM);font-size:.62rem;color:var(--mu);text-transform:uppercase;letter-spacing:.1em}
#graphCanvas{display:block;width:100%;height:auto;border-top:1px solid rgba(255,255,255,.04);cursor:crosshair}
#photonBar{padding:6px 14px;font-family:var(--FM);font-size:.7rem;color:var(--mu);border-top:1px solid var(--bord);display:none;align-items:center;justify-content:space-between;gap:8px}

/* Welcher-Weg badge */
.ww-badge{
  position:absolute;top:44px;right:10px;z-index:10;
  display:none;align-items:center;gap:6px;
  background:rgba(239,68,68,.15);border:1px solid rgba(239,68,68,.4);
  border-radius:6px;padding:4px 10px;
  font-family:var(--FM);font-size:.65rem;color:#ef4444;
}
.ww-badge.on{display:flex}
.ww-dot{width:6px;height:6px;border-radius:50%;background:#ef4444;animation:blinkAnim .8s infinite}

/* Keyboard shortcut hints */
.kbd-bar{
  display:flex;gap:8px;padding:6px 14px;border-top:1px solid var(--bord);
  font-family:var(--FM);font-size:.6rem;color:var(--mu);flex-wrap:wrap;align-items:center;
}
.kbd{
  background:var(--card);border:1px solid var(--bord2);border-radius:3px;
  padding:1px 5px;color:var(--tx2);font-size:.58rem;
}

/* Info chips */
.info-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(145px,1fr));gap:10px;margin-top:18px}
.info-chip{
  background:linear-gradient(180deg, rgba(13,22,38,.84), rgba(14,19,33,.9));
  border:1px solid rgba(148,163,184,.14);border-radius:12px;padding:12px 14px;
  transition:border-color .2s, transform .2s;cursor:default;box-shadow:0 12px 24px rgba(3,7,18,.18);
}
.info-chip:hover{border-color:var(--bord2);transform:translateY(-1px)}
.chip-lbl{font-family:var(--FM);font-size:.6rem;text-transform:uppercase;letter-spacing:.1em;color:var(--mu);margin-bottom:4px}
.chip-val{font-family:var(--FM);font-size:1rem;font-weight:600;color:var(--pri)}
.chip-u{font-size:.68rem;color:var(--tx2);margin-left:3px}

/* Controls panel */
.ctrl-panel{
  background:linear-gradient(180deg, rgba(11,19,32,.94), rgba(9,17,29,.96));
  border:1px solid rgba(148,163,184,.16);border-radius:22px;padding:18px;display:flex;flex-direction:column;gap:13px;
  box-shadow:var(--shadow-card);backdrop-filter:blur(12px);
}
.ctrl-hdr{font-family:var(--FD);font-size:.78rem;font-weight:700;color:var(--tx2);text-transform:uppercase;letter-spacing:.1em;border-bottom:1px solid var(--bord);padding-bottom:10px;display:flex;justify-content:space-between;align-items:center}
.ctrl-sub{font-weight:400;font-size:.68rem;color:var(--mu)}
.sl-grp{display:flex;flex-direction:column;gap:4px}
.sl-hdr{display:flex;justify-content:space-between;align-items:center;font-size:.82rem}
.sl-nm{color:var(--tx2);font-weight:500}
.sl-vl{font-family:var(--FM);font-size:.75rem;color:var(--pri);background:rgba(0,200,255,.08);padding:2px 8px;border-radius:4px}
input[type="range"]{
  -webkit-appearance:none;appearance:none;width:100%;height:3px;border-radius:2px;
  background:var(--surf);outline:none;cursor:pointer;margin-top:5px;
}
input[type="range"]::-webkit-slider-thumb{
  -webkit-appearance:none;width:15px;height:15px;border-radius:50%;
  background:var(--pri);box-shadow:0 0 8px rgba(0,200,255,.5);cursor:pointer;transition:transform .1s;
}
input[type="range"]::-webkit-slider-thumb:hover{transform:scale(1.25)}
input[type="range"]::-moz-range-thumb{width:15px;height:15px;border-radius:50%;background:var(--pri);border:none;cursor:pointer}
.wl-wrap{position:relative;margin:6px 0 2px}
.wl-bar{height:5px;border-radius:3px;background:linear-gradient(to right,#7b00ff 0%,#4b00ff 8%,#0033ff 16%,#0099ff 26%,#00ccff 33%,#00ff88 45%,#aaff00 55%,#ffee00 63%,#ff8800 73%,#ff2200 85%,#cc0000 100%)}
.wl-thumb{position:absolute;top:-4px;width:13px;height:13px;border-radius:50%;border:2px solid #fff;transform:translateX(-50%);pointer-events:none;transition:left .08s;box-shadow:0 0 8px rgba(0,0,0,.5)}
.seg-ctrl{display:flex;gap:3px;background:var(--surf);border-radius:7px;padding:3px}
.seg-btn{flex:1;padding:5px 4px;border:none;border-radius:5px;background:transparent;color:var(--mu);font-family:var(--FB);font-size:.78rem;font-weight:500;cursor:pointer;transition:all .15s}
.seg-btn.on{background:var(--card);color:var(--pri);box-shadow:0 0 10px rgba(0,200,255,.15)}
.chk-row{display:flex;align-items:center;gap:9px;font-size:.82rem;color:var(--tx2);cursor:pointer}
.chk-row input[type="checkbox"]{accent-color:var(--pri);width:14px;height:14px;cursor:pointer}
.chk-ww input[type="checkbox"]{accent-color:var(--err)}
.chk-ww{color:#ef9999}
hr.div{border:none;border-top:1px solid var(--bord)}

/* ---- Control groups ---- */
.ctrl-group{display:flex;flex-direction:column;gap:12px}
.grp-hdr{display:flex;align-items:center;gap:7px;font-family:var(--FM);font-size:.66rem;letter-spacing:.14em;text-transform:uppercase;color:var(--vio);margin-top:2px}
.grp-hdr .grp-ico{font-size:.85rem}
.grp-hdr::after{content:'';flex:1;height:1px;background:linear-gradient(to right,rgba(155,92,246,.35),transparent)}
.grp-hdr.c-pri{color:var(--pri)}
.grp-hdr.c-pri::after{background:linear-gradient(to right,rgba(0,200,255,.35),transparent)}
.grp-hdr.c-acc{color:var(--acc)}
.grp-hdr.c-acc::after{background:linear-gradient(to right,rgba(245,158,11,.35),transparent)}
.derived-row{display:flex;justify-content:space-between;align-items:center;font-family:var(--FM);font-size:.72rem;color:var(--mu);background:var(--surf);border:1px solid var(--bord);border-radius:6px;padding:6px 10px}
.derived-row b{color:var(--tx2);font-weight:600}

/* ---- Panel toggle buttons row (Lernmodus / Messung / Auswertung) ---- */
.panel-tabs{display:flex;gap:6px;flex-wrap:wrap;padding:10px 14px;border-top:1px solid var(--bord)}
.ptab{flex:1;min-width:110px;padding:8px 10px;border-radius:7px;border:1px solid var(--bord);background:var(--surf);color:var(--tx2);font-family:var(--FB);font-size:.76rem;font-weight:600;cursor:pointer;transition:all .15s;display:flex;align-items:center;justify-content:center;gap:6px}
.ptab:hover{border-color:var(--bord2);color:var(--tx)}
.ptab.on{background:rgba(0,200,255,.1);border-color:var(--pri);color:var(--pri)}

/* ---- Lernmodus panel ---- */
.aux-panel{display:none;padding:16px;border-top:1px solid var(--bord);background:var(--bg2)}
.aux-panel.on{display:block}
.aux-panel h4{font-family:var(--FD);font-size:.85rem;color:#fff;margin-bottom:10px;display:flex;align-items:center;gap:7px}
.aux-panel p{color:var(--tx2);font-size:.82rem;line-height:1.7;margin-bottom:10px}
.aux-fml{background:var(--card);border:1px solid var(--bord);border-left:3px solid var(--vio);border-radius:0 8px 8px 0;padding:10px 14px;font-family:var(--FM);font-size:.8rem;color:var(--tx);margin:10px 0}
.aux-fml .cm{color:var(--mu);font-size:.68rem;display:block;margin-top:3px}
.aux-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:8px;margin-top:10px}
.aux-cell{background:var(--card);border:1px solid var(--bord);border-radius:8px;padding:9px 12px}
.aux-cell .l{font-family:var(--FM);font-size:.58rem;text-transform:uppercase;letter-spacing:.08em;color:var(--mu);margin-bottom:3px}
.aux-cell .v{font-family:var(--FM);font-size:.9rem;color:var(--pri);font-weight:600}
.aux-cell .v.dev-ok{color:var(--ok)}
.aux-cell .v.dev-bad{color:var(--err)}
.aux-hint{font-family:var(--FM);font-size:.68rem;color:var(--mu);margin-top:8px;padding-top:8px;border-top:1px dashed var(--bord)}

/* ---- Measurement points ---- */
.meas-list{display:flex;flex-direction:column;gap:6px;margin-top:10px;max-height:220px;overflow-y:auto}
.meas-item{display:flex;align-items:center;gap:8px;background:var(--card);border:1px solid var(--bord);border-radius:7px;padding:7px 10px;font-family:var(--FM);font-size:.68rem;color:var(--tx2)}
.meas-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0;border:1.5px solid #fff}
.meas-item b{color:var(--tx);font-weight:600}
.meas-rm{margin-left:auto;background:none;border:none;color:var(--err);cursor:pointer;font-size:.9rem;line-height:1;padding:2px 4px}
.meas-empty{color:var(--mu);font-size:.76rem;font-style:italic;padding:6px 0}

/* ---- Evaluation table ---- */
.eval-tbl{width:100%;border-collapse:collapse;font-family:var(--FM);font-size:.72rem;margin-top:8px}
.eval-tbl th{text-align:left;color:var(--mu);font-weight:500;text-transform:uppercase;font-size:.6rem;letter-spacing:.08em;padding:4px 6px;border-bottom:1px solid var(--bord)}
.eval-tbl td{padding:4px 6px;border-bottom:1px solid rgba(255,255,255,.03);color:var(--tx2)}
.eval-tbl td.m0{color:var(--pri);font-weight:600}

@media(max-width:640px){
  .aux-grid{grid-template-columns:repeat(2,1fr)}
  .ptab{min-width:80px;font-size:.7rem;padding:7px 6px}
}

/* ================================================================ EXPLANATION */
#expSec{padding-top:60px}
.exp-card{
  max-width:900px;margin:0 auto;background:linear-gradient(180deg, rgba(12,22,38,.9), rgba(9,16,29,.96));
  border:1px solid rgba(148,163,184,.16);border-radius:20px;padding:44px;box-shadow:var(--shadow-card);
}
@media(max-width:600px){.exp-card{padding:24px}}
.exp-card h2{font-family:var(--FD);font-size:1.6rem;font-weight:700;color:#fff;margin-bottom:20px}
.exp-card h3{font-family:var(--FD);font-size:1rem;font-weight:700;color:var(--pri);margin:28px 0 10px}
.exp-card p{color:var(--tx2);line-height:1.85;margin-bottom:14px}
.exp-card strong{color:var(--tx)}
.fml{background:var(--surf);border-left:3px solid var(--pri);border-radius:0 8px 8px 0;padding:14px 20px;font-family:var(--FM);font-size:.88rem;color:var(--tx);margin:16px 0;overflow-x:auto;line-height:1.9}
.fml .cm{color:var(--mu);font-size:.78rem}
.hl{background:rgba(0,200,255,.05);border:1px solid rgba(0,200,255,.18);border-radius:10px;padding:18px 22px;margin:18px 0}
.hl p{margin:0;color:var(--tx)}

footer{text-align:center;padding:36px 24px;border-top:1px solid var(--bord);color:var(--mu);font-size:.8rem}
footer span{color:var(--pri)}
</style>
</head>
<body>

<!-- ════ HERO ════ -->
<section id="hero">
  <canvas id="heroCanvas" aria-hidden="true"></canvas>
  <div class="hero-in">
    <div class="hero-badge">🌊 Quantenphysik &amp; Wellenoptik</div>
    <h1 class="hero-title">Thomas Youngs<br><em>Doppelspalt-<br>experiment</em></h1>
    <p class="hero-sub">Licht, Wellen und Interferenz – ein Experiment aus dem Jahr 1801, das unsere Vorstellung der Natur für immer veränderte. Erlebe die Quantenwelt interaktiv.</p>
    <div class="hero-btns">
      <a href="#simSec" class="btn btn-pri">⚗️ Simulation starten</a>
      <a href="#expSec" class="btn btn-ghost">📖 Physik erkunden</a>
    </div>
  </div>
  <div class="hero-scroll">
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" aria-hidden="true"><polyline points="6 9 12 15 18 9"/></svg>
    Scrollen
  </div>
</section>

<!-- ════ SIMULATION ════ -->
<section id="simSec">
  <div class="sec-head">
    <div class="sec-lbl">⚙️ Interaktive Simulation</div>
    <h2 class="sec-title">Das Experiment selbst erkunden</h2>
    <p class="sec-desc">Bewege die Regler und beobachte, wie das Interferenzmuster in Echtzeit reagiert.</p>
  </div>

  <div class="sim-wrap">
    <div>
      <div class="cv-box" id="cvBox">
        <div class="cv-topbar">
          <div class="mode-pill"><div class="blink"></div><span id="modeLbl">Wellenmodus aktiv</span></div>
          <div class="bar-btns">
            <button class="btn btn-ghost btn-sm btn-icon" id="btnFS" title="Vollbild">⛶</button>
            <button class="btn btn-ghost btn-sm" id="btnShot" title="Screenshot">📷</button>
            <button class="btn btn-ghost btn-sm" id="btnReset">↺ Reset</button>
          </div>
        </div>

        <!-- Welcher-Weg badge overlay -->
        <div class="ww-badge" id="wwBadge"><div class="ww-dot"></div>Welcher-Weg aktiv – Interferenz zerstört</div>

        <canvas id="mainCanvas" width="800" height="420"></canvas>

        <div class="cv-leg">
          <div class="leg-i"><div class="leg-d" style="background:#00ccff"></div>Quelle</div>
          <div class="leg-i"><div class="leg-d" style="background:rgba(255,255,255,.4)"></div>Spalt</div>
          <div class="leg-i"><div class="leg-d" style="background:#ffd700"></div>Konstruktiv</div>
          <div class="leg-i"><div class="leg-d" style="background:#050e20"></div>Destruktiv</div>
          <div class="leg-i"><div class="leg-d" style="background:#ff7c3a"></div>Schirm</div>
          <div class="leg-i" style="color:rgba(100,120,160,.6);margin-left:auto;font-size:.55rem">← Hover auf Schirm: Intensität messen</div>
        </div>

        <div class="graph-hdr">
          <span>📈 Intensitätsverteilung I(y)</span>
          <span id="fringeInfo" style="color:var(--pri)"></span>
        </div>
        <canvas id="graphCanvas" width="800" height="110"></canvas>

        <div id="photonBar">
          <span>⚛ Photonen aufgetroffen: <span id="pCount" style="color:var(--pri);font-weight:600">0</span></span>
          <button class="btn btn-danger btn-sm" id="btnClear">🗑 Löschen</button>
        </div>

        <div class="kbd-bar">
          <span>Tastenkürzel:</span>
          <span><kbd class="kbd">Leertaste</kbd> Pause</span>
          <span><kbd class="kbd">S</kbd> Schritt</span>
          <span><kbd class="kbd">R</kbd> Reset</span>
          <span><kbd class="kbd">←→</kbd> λ ±5nm</span>
          <span><kbd class="kbd">↑↓</kbd> d ±5μm</span>
          <span><kbd class="kbd">1</kbd><kbd class="kbd">2</kbd><kbd class="kbd">5</kbd> Spalte</span>
          <span><kbd class="kbd">L</kbd> Lernmodus</span>
        </div>

        <!-- Auxiliary panels: Lernmodus / Messung / Auswertung -->
        <div class="panel-tabs">
          <button class="ptab" id="tabLearn">📘 Lernmodus</button>
          <button class="ptab" id="tabMeas">🎯 Messpunkte</button>
          <button class="ptab" id="tabEval">📊 Auswertung</button>
        </div>

        <div class="aux-panel" id="panelLearn">
          <h4>🔬 Warum entstehen helle und dunkle Streifen?</h4>
          <p>Jeder der Spalte wirkt nach dem Huygens'schen Prinzip als eigenständige Kugelwellenquelle. Auf dem Weg zu einem Punkt P auf dem Schirm legen die beiden Teilwellen unterschiedlich lange Strecken zurück – den <strong>Gangunterschied Δs</strong>. Passen die Wellenberge exakt zusammen (Δs = ganzzahliges Vielfaches von λ), addieren sich die Amplituden → <strong>heller Streifen</strong>. Trifft ein Wellenberg auf ein Wellental (Δs = halbzahliges Vielfaches von λ), löschen sich die Wellen aus → <strong>dunkler Streifen</strong>.</p>
          <div class="aux-fml">Maxima (hell):&nbsp; d · sin θ = m · λ<span class="cm">m = 0, ±1, ±2, … — Ordnung des Maximums</span></div>
          <div class="aux-fml">Minima (dunkel):&nbsp; d · sin θ = (m + ½) · λ<span class="cm">liegt jeweils zwischen zwei benachbarten Maxima</span></div>
          <div class="aux-fml">Gangunterschied:&nbsp; Δs = d · sin θ ≈ d · y / L<span class="cm">Kleinwinkel-Näherung, gültig für y ≪ L</span></div>
          <p>Klicke im Wellenfeld oder auf dem Schirm auf einen Punkt, um dort den aktuellen Gangunterschied und die resultierende Phase live zu berechnen:</p>
          <div class="aux-grid" id="learnLive">
            <div class="aux-cell"><div class="l">Position y</div><div class="v" id="lv-y">–</div></div>
            <div class="aux-cell"><div class="l">Gangunterschied Δs</div><div class="v" id="lv-ds">–</div></div>
            <div class="aux-cell"><div class="l">Δs / λ</div><div class="v" id="lv-dsl">–</div></div>
            <div class="aux-cell"><div class="l">Phasendifferenz Δφ</div><div class="v" id="lv-phi">–</div></div>
            <div class="aux-cell"><div class="l">Ordnung m</div><div class="v" id="lv-m">–</div></div>
            <div class="aux-cell"><div class="l">Intensität I(y)</div><div class="v" id="lv-i">–</div></div>
          </div>
          <div class="aux-hint">Tipp: Bei Δs = 0, λ, 2λ … → konstruktiv (hell). Bei Δs = 0.5λ, 1.5λ … → destruktiv (dunkel).</div>
        </div>

        <div class="aux-panel" id="panelMeas">
          <h4>🎯 Messcursor &amp; Messpunkte</h4>
          <p>Bewege die Maus über den Schirm für eine Sofortablesung, oder klicke auf den Schirm bzw. das Diagramm, um bis zu 6 feste Messpunkte zu setzen. Jeder Punkt zeigt Position, Intensität, Abstand vom Zentralmaximum und Interferenzordnung.</p>
          <div class="meas-list" id="measList"><div class="meas-empty">Noch keine Messpunkte gesetzt – klicke auf den Schirm.</div></div>
          <div style="display:flex;gap:8px;margin-top:10px">
            <button class="btn btn-ghost btn-sm" id="btnMeasClear">🗑 Messpunkte löschen</button>
          </div>
        </div>

        <div class="aux-panel" id="panelEval">
          <h4>📊 Automatische Auswertung</h4>
          <p>Alle Werte werden bei jeder Parameteränderung sofort neu berechnet.</p>
          <div class="aux-grid">
            <div class="aux-cell"><div class="l">Zentralmaximum</div><div class="v" id="ev-c0">y = 0.00 mm</div></div>
            <div class="aux-cell"><div class="l">Streifenabstand Δy (Theorie)</div><div class="v" id="ev-dy">–</div></div>
            <div class="aux-cell"><div class="l">Streifenabstand Δy (simuliert)</div><div class="v" id="ev-dysim">–</div></div>
            <div class="aux-cell"><div class="l">Relative Abweichung</div><div class="v" id="ev-dev">–</div></div>
            <div class="aux-cell"><div class="l">Sichtbare Maxima (±30mm)</div><div class="v" id="ev-cnt">–</div></div>
          </div>
          <table class="eval-tbl">
            <thead><tr><th>Ordnung m</th><th>Theorie y [mm]</th><th>Simuliert y [mm]</th><th>Δ [μm]</th></tr></thead>
            <tbody id="evalTbody"></tbody>
          </table>
        </div>
      </div>

      <div class="info-grid">
        <div class="info-chip"><div class="chip-lbl">Wellenlänge λ</div><div class="chip-val" id="iv-lam">550<span class="chip-u">nm</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Frequenz f</div><div class="chip-val" id="iv-f">–<span class="chip-u">THz</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Spaltabstand d</div><div class="chip-val" id="iv-d">150<span class="chip-u">μm</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Schirmabstand L</div><div class="chip-val" id="iv-L">1000<span class="chip-u">mm</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Streifenabstand Δy</div><div class="chip-val" id="iv-dy">–<span class="chip-u">mm</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Spaltbreite a</div><div class="chip-val" id="iv-a">30<span class="chip-u">μm</span></div></div>
        <div class="info-chip"><div class="chip-lbl">Sichtb. Maxima</div><div class="chip-val" id="iv-mx">–</div></div>
      </div>
    </div>

    <!-- Controls -->
    <div class="ctrl-panel">
      <div class="ctrl-hdr">Steuerung <span class="ctrl-sub">Echtzeit</span></div>

      <div class="ctrl-group">
        <div class="grp-hdr c-pri"><span class="grp-ico">💡</span>Lichtquelle</div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Wellenlänge λ</span><span class="sl-vl" id="sv-lam">550 nm</span></div>
          <div class="wl-wrap"><div class="wl-bar"></div><div class="wl-thumb" id="wlThumb"></div></div>
          <input type="range" id="sl-lam" min="380" max="750" value="550" step="1">
        </div>

        <div class="derived-row"><span>Frequenz f = c / λ</span><b id="sv-f">–</b></div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Amplitude E₀</span><span class="sl-vl" id="sv-amp">1.00</span></div>
          <input type="range" id="sl-amp" min="20" max="200" value="100" step="1">
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Kohärenz</span><span class="sl-vl" id="sv-coh">100 %</span></div>
          <input type="range" id="sl-coh" min="0" max="100" value="100" step="1">
        </div>
      </div>

      <hr class="div">

      <div class="ctrl-group">
        <div class="grp-hdr"><span class="grp-ico">▤</span>Doppelspalt</div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Anzahl Spalte</span></div>
          <div class="seg-ctrl" id="slitSeg">
            <button class="seg-btn" data-n="1">Einzel</button>
            <button class="seg-btn on" data-n="2">Doppel</button>
          </div>
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Spaltabstand d</span><span class="sl-vl" id="sv-d">150 μm</span></div>
          <input type="range" id="sl-d" min="30" max="500" value="150" step="5">
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Spaltbreite a</span><span class="sl-vl" id="sv-a">30 μm</span></div>
          <input type="range" id="sl-a" min="3" max="120" value="30" step="1">
        </div>
      </div>

      <hr class="div">

      <div class="ctrl-group">
        <div class="grp-hdr c-acc"><span class="grp-ico">📐</span>Geometrie</div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Schirmabstand L</span><span class="sl-vl" id="sv-L">1000 mm</span></div>
          <input type="range" id="sl-L" min="200" max="3000" value="1000" step="10">
        </div>
      </div>

      <hr class="div">

      <div class="ctrl-group">
        <div class="grp-hdr"><span class="grp-ico">🖥</span>Darstellung</div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Visualisierungsmodus</span></div>
          <div class="seg-ctrl" id="modeSeg">
            <button class="seg-btn on" data-m="wave">🌊 Welle</button>
            <button class="seg-btn" data-m="photon">⚛ Photon</button>
          </div>
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Feld-Darstellung</span></div>
          <div class="seg-ctrl" id="fieldSeg">
            <button class="seg-btn on" data-f="amplitude">Amplitude</button>
            <button class="seg-btn" data-f="intensity">Intensität</button>
            <button class="seg-btn" data-f="wavefront">Nur Wellenfront</button>
          </div>
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Helligkeit</span><span class="sl-vl" id="sv-br">100 %</span></div>
          <input type="range" id="sl-br" min="10" max="200" value="100" step="1">
        </div>

        <div class="sl-grp">
          <div class="sl-hdr"><span class="sl-nm">Animationsgeschw.</span><span class="sl-vl" id="sv-sp">1.0×</span></div>
          <input type="range" id="sl-sp" min="0" max="30" value="10" step="1">
        </div>

        <label class="chk-row"><input type="checkbox" id="chk-env" checked> Beugungshüllkurve einblenden</label>
        <label class="chk-row"><input type="checkbox" id="chk-max" checked> Maxima/Minima markieren</label>
        <label class="chk-row"><input type="checkbox" id="chk-wf"  checked> Wellenfronten zeigen</label>
        <label class="chk-row chk-ww"><input type="checkbox" id="chk-ww"> Welcher-Weg-Messung (Interferenz zerstört)</label>
      </div>

      <hr class="div">

      <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">
        <button class="btn btn-ghost btn-sm" id="btnSound">🔇 Ton</button>
        <button class="btn btn-ghost btn-sm" id="btnPause">⏸ Pause</button>
      </div>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">
        <button class="btn btn-ghost btn-sm" id="btnStep">⏭ Schritt</button>
        <button class="btn btn-ghost btn-sm" id="btnFS2">⛶ Vollbild</button>
      </div>
    </div>
  </div>
</section>

<!-- ════ ERKLÄRUNG ════ -->
<section id="expSec">
  <div class="sec-head">
    <div class="sec-lbl">📚 Physikalische Erklärung</div>
    <h2 class="sec-title">Das Experiment verstehen</h2>
  </div>
  <div class="exp-card">
    <h2>Thomas Youngs Doppelspaltexperiment (1801/02)</h2>
    <p>Im Jahr 1801 führte der britische Universalgelehrte <strong>Thomas Young</strong> ein Experiment durch, das die Physik revolutionieren sollte: Er ließ Licht durch zwei schmale Spalte fallen und beobachtete auf einem dahinter aufgestellten Schirm ein Muster aus hellen und dunklen Streifen. Dieses Ergebnis widersprach Newtons Teilchentheorie des Lichts fundamental – und bewies dessen <strong>Wellennatur</strong>.</p>
    <div class="hl"><p>🌊 <strong>Analogie:</strong> Stell dir einen ruhigen Teich vor. Wirfst du zwei Steine gleichzeitig hinein, entstehen kreisförmige Wellen. Wo Wellenberge beider Quellen aufeinandertreffen, entsteht ein größerer Wellenberg (<em>konstruktive Interferenz</em>). Wo ein Wellenberg auf ein Wellental trifft, löschen sie sich aus (<em>destruktive Interferenz</em>). Genau dasselbe geschieht mit Lichtwellen am Doppelspalt.</p></div>
    <h3>Das Prinzip der Interferenz</h3>
    <p>Trifft Licht auf den Doppelspalt, wirkt jeder Spalt nach dem <strong>Huygens'schen Prinzip</strong> als eigenständige Kugelwellenquelle. Die zwei Wellen überlagern sich und erzeugen je nach Gangunterschied konstruktive oder destruktive Interferenz.</p>
    <div class="fml">d · sin(θ) = m · λ &nbsp;&nbsp;&nbsp; (m = 0, ±1, ±2, ...) → helle Streifen<br>d · sin(θ) = (m + ½) · λ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; → dunkle Streifen<br><span class="cm">// d = Spaltabstand, θ = Winkel, λ = Wellenlänge, m = Ordnung</span></div>
    <h3>Der Streifenabstand</h3>
    <div class="fml">Δy ≈ λ · L / d<br><span class="cm">// Probiere die Regler – größeres λ oder L → breitere Streifen, größeres d → engere Streifen</span></div>
    <h3>Die Hüllkurve – Einfluss der Spaltbreite</h3>
    <div class="fml">I(y) = I₀ · sinc²(π·a·y / λL) · cos²(π·d·y / λL)<br><span class="cm">// sinc²-Term: Einzelspalt-Hüllkurve &nbsp;|&nbsp; cos²-Term: Doppelspalt-Interferenz</span></div>
    <div class="hl"><p>⚛️ <strong>Photonenmodus:</strong> Einzelne Photonen treffen scheinbar zufällig auf den Schirm. Nach und nach baut sich das Interferenzmuster auf – als würden die Photonen „wissen", wo die hellen Streifen sein werden, ohne je gleichzeitig an beiden Spalten zu sein.</p></div>
  </div>
</section>

<footer>
</footer>

<script>
'use strict';

/* ══════════════════════════════════════════════════════════════════
   § 1  STATE & PARAMETER
   ══════════════════════════════════════════════════════════════════ */

const P = {
  lambda: 550,  // nm
  d:      150,  // μm
  a:       30,  // μm
  L:     1000,  // mm
  bright:  1.0,
  N:         2,
  speed:   1.0, // animation speed multiplier
  amp:     1.0, // source amplitude E0 (relative)
  coh:     1.0, // degree of coherence, 0..1
};

const C_LIGHT = 299792458; // m/s

const ST = {
  mode:        'wave',
  showEnv:     true,
  showMax:     true,
  showWF:      true,
  welcherWeg:  false,
  paused:      false,
  soundOn:     false,
  t:           0,
  lastTs:      0,
  animId:      null,
  // Photon accumulation
  accumCanvas: null,
  accumCtx:    null,
  photonCnt:   0,
  // Flying photons in photon mode
  flyingPhotons: [],
  // Measurement cursor
  cursorX: -1,
  cursorY: -1,
  // Graph hover
  graphCursorX: -1,
  // Field visualisation mode: 'amplitude' | 'intensity' | 'wavefront'
  fieldMode: 'amplitude',
  // Fixed measurement points [{y_m, id, color}]
  measPoints: [],
  measId: 0,
  // Learn mode
  learnOn: false,
  activePanel: null, // 'learn' | 'meas' | 'eval' | null
  // Single-step request while paused
  stepFrame: false,
  // Audio
  audioCtx:  null,
  audioOsc:  null,
  audioGain: null,
};

/* ══════════════════════════════════════════════════════════════════
   § 2  PHYSIK-HILFSFUNKTIONEN
   ══════════════════════════════════════════════════════════════════ */

function wlToRGB(wl) {
  let r = 0, g = 0, b = 0;
  if      (wl < 380) { r = 0.5;             g = 0;             b = 1;            }
  else if (wl < 440) { r = -(wl-440)/60;    g = 0;             b = 1;            }
  else if (wl < 490) { r = 0;               g = (wl-440)/50;   b = 1;            }
  else if (wl < 510) { r = 0;               g = 1;             b = -(wl-510)/20; }
  else if (wl < 580) { r = (wl-510)/70;     g = 1;             b = 0;            }
  else if (wl < 645) { r = 1;               g = -(wl-645)/65;  b = 0;            }
  else               { r = 1;               g = 0;             b = 0;            }
  let fac = 1;
  if      (wl < 420) fac = 0.3 + 0.7*(wl-380)/40;
  else if (wl > 700) fac = 0.3 + 0.7*(750-wl)/50;
  const G = 0.85;
  return {
    r: Math.round(255*Math.pow(Math.max(0,r*fac),G)),
    g: Math.round(255*Math.pow(Math.max(0,g*fac),G)),
    b: Math.round(255*Math.pow(Math.max(0,b*fac),G)),
  };
}

function wlCSS(wl, a=1) {
  const {r,g,b} = wlToRGB(wl);
  return `rgba(${r},${g},${b},${a})`;
}

function sinc(x) {
  if (Math.abs(x)<1e-9) return 1;
  return Math.sin(Math.PI*x)/(Math.PI*x);
}

/** Coherent N-slit intensity (Fernfeld-Näherung), inkl. Quellamplitude E0² */
function screenI(y_m, lam_m, d_m, a_m, Lm, N) {
  const sinT = y_m / Math.hypot(y_m, Lm);
  const beta  = a_m * sinT / lam_m;
  const env   = sinc(beta)*sinc(beta);
  let pattern;
  if (N===1) {
    pattern = env;
  } else {
    const gam  = Math.PI*d_m*sinT/lam_m;
    const sg   = Math.sin(gam);
    let interf;
    if (Math.abs(sg)<1e-8) {
      interf = 1;
    } else {
      const v = Math.sin(N*gam)/(N*sg);
      interf  = v*v;
    }
    pattern = env*interf;
  }
  return pattern * P.amp*P.amp;
}

/**
 * Incoherent superposition: each slit contributes only its own
 * single-slit diffraction lobe, no interference cross-terms.
 * Used for Welcher-Weg (full decoherence) and as the c=0 limit of
 * partial coherence.
 */
function screenI_incoherent(y_m, lam_m, a_m, Lm) {
  const slits   = slitPos();
  const RANGE_M = 0.030;
  const h       = H();
  let I_total   = 0;
  slits.forEach(s => {
    const s_y_m = (s.y/h - 0.5)*RANGE_M*2;
    const dy    = y_m - s_y_m;
    const sinT  = dy / Math.hypot(dy, Lm);
    const beta  = a_m * sinT / lam_m;
    I_total    += sinc(beta)**2;
  });
  return (I_total / slits.length) * P.amp*P.amp;
}

/**
 * Effective intensity.
 * - Welcher-Weg aktiv  → vollständig inkohärent (kein Muster).
 * - sonst: lineare Überlagerung von kohärentem und inkohärentem
 *   Anteil gemäß Kohärenzgrad P.coh (1 = perfekt kohärent,
 *   0 = unkohärent → keine Interferenzstreifen, nur Hüllkurve).
 */
function screenI_eff(y_m, lam_m, d_m, a_m, Lm, N) {
  if (ST.welcherWeg) return screenI_incoherent(y_m, lam_m, a_m, Lm);
  if (N===1) return screenI(y_m, lam_m, d_m, a_m, Lm, N);
  const c = Math.max(0, Math.min(1, P.coh));
  if (c>=1) return screenI(y_m, lam_m, d_m, a_m, Lm, N);
  if (c<=0) return screenI_incoherent(y_m, lam_m, a_m, Lm);
  return c*screenI(y_m, lam_m, d_m, a_m, Lm, N) + (1-c)*screenI_incoherent(y_m, lam_m, a_m, Lm);
}

function fringeSpacing() {
  if (P.N===1 || ST.welcherWeg) return NaN;
  return (P.lambda*1e-9 * P.L*1e-3) / (P.d*1e-6) * 1e3; // mm
}

function visMaxima() {
  if (P.N===1) return '~5';
  return 2*Math.max(1,Math.floor(P.d/P.a))+1;
}

/**
 * Findet lokale Maxima der simulierten Intensitätsverteilung I(y)
 * durch feines Abtasten im sichtbaren Schirmbereich (±RANGE_M).
 * Liefert [{y_m, I}] sortiert nach y.
 */
function findSimulatedMaxima(nSamples=4000) {
  const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
  const RANGE_M=0.030;
  const ys=[], Is=[];
  for(let i=0;i<=nSamples;i++){
    const y_m=(-RANGE_M)+(2*RANGE_M)*(i/nSamples);
    ys.push(y_m);
    Is.push(screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N));
  }
  const peaks=[];
  const thresh=0.02;
  for(let i=1;i<Is.length-1;i++){
    if(Is[i]>Is[i-1]&&Is[i]>=Is[i+1]&&Is[i]>thresh){
      peaks.push({y_m:ys[i], I:Is[i]});
    }
  }
  return peaks;
}

/** Gangunterschied Δs [m] und Ordnung m für einen Punkt y auf dem Schirm */
function pathDifference(y_m) {
  const d_m=P.d*1e-6, Lm=P.L*1e-3;
  const sinT=y_m/Math.hypot(y_m,Lm);
  return d_m*sinT; // Δs in Metern
}

/* ══════════════════════════════════════════════════════════════════
   § 3  CANVAS-SETUP
   ══════════════════════════════════════════════════════════════════ */

const MC  = document.getElementById('mainCanvas');
const GC  = document.getElementById('graphCanvas');
const ctx = MC.getContext('2d');
const gx  = GC.getContext('2d');

function resizeCvs() {
  const cw  = MC.parentElement.clientWidth || 800;
  MC.width  = cw;
  MC.height = Math.round(cw*420/800);
  GC.width  = cw;
  GC.height = Math.round(cw*110/800);
  // Re-init accumulation buffer on resize
  if (ST.accumCanvas) initAccumBuffer();
}

const W  = () => MC.width;
const H  = () => MC.height;
const GW = () => GC.width;
const GH = () => GC.height;

const LO = {
  get srcX()  { return W()*0.07; },
  get barX()  { return W()*0.32; },
  get scX()   { return W()*0.87; },
  get scW()   { return W()*0.10; },
  get midY()  { return H()*0.50; },
};

function slitPos() {
  const cx     = LO.barX;
  const cy     = LO.midY;
  const sep_px = (P.d/400)*H()*0.55;
  if (P.N===1) return [{x:cx,y:cy}];
  if (P.N===2) return [{x:cx,y:cy-sep_px/2},{x:cx,y:cy+sep_px/2}];
  return [-2,-1,0,1,2].map(i=>({x:cx,y:cy+i*sep_px*0.5}));
}

function slitHeight_px() {
  return Math.max(5,(P.a/200)*H()*0.55);
}

/* ══════════════════════════════════════════════════════════════════
   § 4  RENDER-FUNKTIONEN
   ══════════════════════════════════════════════════════════════════ */

/* 4.1 Background */
function drawBG() {
  const w=W(), h=H();
  ctx.fillStyle='#020c1b';
  ctx.fillRect(0,0,w,h);
  ctx.strokeStyle='rgba(255,255,255,0.022)';
  ctx.lineWidth=0.5;
  const gs=38;
  for(let x=0;x<w;x+=gs){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,h);ctx.stroke()}
  for(let y=0;y<h;y+=gs){ctx.beginPath();ctx.moveTo(0,y);ctx.lineTo(w,y);ctx.stroke()}
  const qg=ctx.createLinearGradient(0,0,LO.barX,0);
  qg.addColorStop(0,'rgba(0,50,110,0.13)');
  qg.addColorStop(1,'rgba(0,50,110,0.00)');
  ctx.fillStyle=qg; ctx.fillRect(0,0,LO.barX,h);
}

/* 4.2 Source */
function drawSource(t) {
  const sx=LO.srcX, sy=LO.midY;
  if(ST.showWF) {
    const LAM_PX=30, SPEED=55, NUM_R=14, col=wlToRGB(P.lambda);
    const maxR=LO.barX-sx+10;
    for(let i=0;i<NUM_R;i++) {
      const r=((t*SPEED*0.05-i*LAM_PX)%(NUM_R*LAM_PX)+NUM_R*LAM_PX)%(NUM_R*LAM_PX);
      if(r<2||r>maxR) continue;
      const alpha=(1-r/maxR)*0.5;
      if(alpha<0.01) continue;
      ctx.beginPath();
      ctx.arc(sx,sy,r,-Math.PI/2,Math.PI/2);
      ctx.strokeStyle=`rgba(${col.r},${col.g},${col.b},${alpha})`;
      ctx.lineWidth=1.5; ctx.stroke();
    }
  }
  const glow=ctx.createRadialGradient(sx,sy,0,sx,sy,22);
  glow.addColorStop(0,'#ffffff');
  glow.addColorStop(0.3,wlCSS(P.lambda,0.85));
  glow.addColorStop(1,'rgba(0,200,255,0)');
  ctx.beginPath(); ctx.arc(sx,sy,22,0,Math.PI*2);
  ctx.fillStyle=glow; ctx.fill();
  const pulse=1+0.18*Math.sin(t*0.07);
  ctx.beginPath(); ctx.arc(sx,sy,5.5*pulse,0,Math.PI*2);
  ctx.fillStyle='#fff'; ctx.fill();
  ctx.fillStyle='rgba(140,180,230,0.4)';
  ctx.font='9px JetBrains Mono,monospace'; ctx.textAlign='center';
  ctx.fillText('QUELLE',sx,12);
}

/* 4.3 Barrier */
function drawBarrier() {
  const slits=slitPos(), bx=LO.barX, bw=10;
  const slitH=slitHeight_px(), h=H();
  const segs=slits.map(s=>({y0:s.y-slitH/2,y1:s.y+slitH/2}))
                  .sort((a,b)=>a.y0-b.y0);
  ctx.fillStyle='#1a3558'; ctx.strokeStyle='#254a7a'; ctx.lineWidth=1;
  const ds=(y0,y1)=>{if(y1<=y0)return; ctx.fillRect(bx-bw/2,y0,bw,y1-y0); ctx.strokeRect(bx-bw/2,y0,bw,y1-y0);};
  ds(0,segs[0].y0);
  for(let i=0;i<segs.length-1;i++) ds(segs[i].y1,segs[i+1].y0);
  ds(segs[segs.length-1].y1,h);
  // Slit glow (light exiting) – only in wave mode
  if(ST.mode!=='photon') {
    slits.forEach(s=>{
      const sg=ctx.createLinearGradient(bx-bw,0,bx+bw*3.5,0);
      sg.addColorStop(0,wlCSS(P.lambda,0.0));
      sg.addColorStop(0.4,wlCSS(P.lambda,0.55));
      sg.addColorStop(1,wlCSS(P.lambda,0.0));
      ctx.fillStyle=sg;
      ctx.fillRect(bx-bw/2,s.y-slitH/2,bw*3.5,slitH);
    });
  }

  // Welcher-Weg detector icons at slits
  if(ST.welcherWeg) {
    slits.forEach((s,i)=>{
      const pulse=0.6+0.4*Math.sin(ST.t*4+i*1.5);
      ctx.beginPath();
      ctx.arc(bx-bw/2-8,s.y,4.5*pulse,0,Math.PI*2);
      ctx.fillStyle=`rgba(255,60,60,${pulse*0.9})`;
      ctx.fill();
      ctx.fillStyle='rgba(255,100,100,0.85)';
      ctx.font='6px JetBrains Mono,monospace'; ctx.textAlign='center';
      ctx.fillText(`D${i+1}`,bx-bw/2-8,s.y+12);
    });
  }

  ctx.fillStyle='rgba(140,180,230,0.4)';
  ctx.font='9px JetBrains Mono,monospace'; ctx.textAlign='center';
  ctx.fillText('BARRIERE',bx,12);
}

/* ─────────────────────────────────────────────────────────────────
   4.4  ANIMATED WAVE FIELD  ★ Kernverbesserung ★
   Bipolare Darstellung des echten E-Feldes:
   · Wellenberge (E>0) → satte Wellenlängenfarbe + Glühen
   · Wellenknoten (E≈0) → tiefschwarz (echte destruktive Interferenz)
   · Wellentäler (E<0) → kühles Dunkelblau (Gegenpol)
   Die Knotenlinien bleiben permanent dunkel, die konstruktiven
   Linien bleiben permanent hell – das visuelle Kernmerkmal der
   Interferenz wird dadurch sofort sichtbar.
   ───────────────────────────────────────────────────────────────── */
function drawAnimatedField(t) {
  const x0  = Math.floor(LO.barX+8);
  const x1  = Math.floor(LO.scX-2);
  const fw  = x1-x0;
  const fh  = H();
  if(fw<=0||fh<=0) return;
  if(ST.fieldMode==='wavefront') return; // nur Ringe, kein volles Feld

  const slits = slitPos();
  const N     = slits.length;
  const col   = wlToRGB(P.lambda);

  // Visual wavelength scales with physical λ for realism
  const LAM_PX = 26+(P.lambda-380)/370*20;  // 26–46 px
  const k      = (2*Math.PI)/LAM_PX;
  const omega  = k*44*P.speed;

  // Welcher-Weg: incoherent superposition – no interference fringes
  const ww = ST.welcherWeg;
  const coh = ww ? 0 : Math.max(0,Math.min(1,P.coh));
  const isIntensityView = ST.fieldMode==='intensity';
  const ampScale = Math.min(1.8, P.amp);

  const STEP = 3;
  const img  = ctx.createImageData(fw, fh);

  for(let py=0; py<fh; py+=STEP) {
    for(let px=0; px<fw; px+=STEP) {
      const cx = x0+px;
      const cy = py;

      let E = 0, ampSum = 0;
      for(let i=0; i<N; i++) {
        const dx  = cx-slits[i].x;
        const dy  = cy-slits[i].y;
        const r   = Math.sqrt(dx*dx+dy*dy);
        if(r<1){ E+=1; ampSum+=1; continue; }
        const amp = 1/(1+r*0.006);
        ampSum   += amp;
        // Partial coherence: mix a per-slit random phase in as
        // coherence drops, so fringes fade smoothly toward c=0.
        const phase = (1-coh)>1e-6 ? (i*2.7+r*0.31)*(1-coh) : 0;
        E += amp*Math.cos(k*r - omega*t + phase);
      }
      // Normalise to [-1, 1]
      E = (ampSum>0 ? E/ampSum : 0) * ampScale;

      let rr, gg, bb, aa;
      if(isIntensityView) {
        // Intensity view: I = E², always positive, no bipolar colouring
        const I = Math.min(1, E*E);
        const v = Math.pow(I, 0.6)*Math.min(1.7, P.bright);
        rr = Math.min(255, Math.round(col.r*v + 25*v));
        gg = Math.min(255, Math.round(col.g*v + 15*v));
        bb = Math.min(255, Math.round(col.b*v + 8*v));
        aa = Math.round(60+195*v);
      } else if(E>0) {
        // Crest: wavelength colour, extra glow boost at peaks
        const v  = Math.pow(E, 0.75)*Math.min(1.7, P.bright);
        rr = Math.min(255, Math.round(col.r*v + 30*v));
        gg = Math.min(255, Math.round(col.g*v + 20*v));
        bb = Math.min(255, Math.round(col.b*v + 10*v));
        aa = Math.round(180+55*E);
      } else {
        // Trough: cool dark blue — visually distinct from crests
        const v = Math.pow(-E, 0.85)*Math.min(1.4, P.bright);
        rr = Math.round(8*v);
        gg = Math.round(18*v);
        bb = Math.min(255, Math.round(80*v));
        aa = Math.round(140+60*(-E));
      }

      for(let dy=0; dy<STEP&&py+dy<fh; dy++) {
        for(let dx2=0; dx2<STEP&&px+dx2<fw; dx2++) {
          const idx=((py+dy)*fw+(px+dx2))*4;
          img.data[idx]   =rr;
          img.data[idx+1] =gg;
          img.data[idx+2] =bb;
          img.data[idx+3] =aa;
        }
      }
    }
  }
  ctx.putImageData(img, x0, 0);

  // ── Glow overlay on antinodal lines (constructive bright streaks)
  // Uses a second lightweight pass at lower resolution for performance
  if(!ww && N>1) {
    ctx.save();
    ctx.beginPath(); ctx.rect(x0,0,fw,fh); ctx.clip();
    ctx.globalCompositeOperation='lighter';
    const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, Lm=P.L*1e-3;
    const RANGE_M=0.030;
    // Draw faint golden lines along the constructive-interference directions
    const dy_m = P.N>1 ? fringeSpacing()*1e-3 : NaN;
    if(!isNaN(dy_m)&&dy_m>0) {
      const dy_px=(dy_m/(RANGE_M*2))*fh;
      const gcol=wlToRGB(P.lambda);
      for(let m=-6;m<=6;m++) {
        const yMid=fh/2+m*dy_px;
        const grd=ctx.createLinearGradient(x0,yMid-dy_px*0.3,x0,yMid+dy_px*0.3);
        grd.addColorStop(0,  'rgba(0,0,0,0)');
        grd.addColorStop(0.5,`rgba(${gcol.r},${gcol.g},${gcol.b},0.10)`);
        grd.addColorStop(1,  'rgba(0,0,0,0)');
        ctx.fillStyle=grd;
        ctx.fillRect(x0,yMid-dy_px*0.3,fw,dy_px*0.6);
      }
    }
    ctx.globalCompositeOperation='source-over';
    ctx.restore();
  }
}

/* 4.4b Lightweight wavefront rings (used in wave+field modes on top of field) */
function drawWavefronts(t) {
  if(!ST.showWF||ST.mode==='field') return;
  const slits=slitPos(), LAM_PX=32+(P.lambda-550)/200*10, SPEED=52, NUM_R=18;
  const col=wlToRGB(P.lambda);
  ctx.save();
  ctx.beginPath(); ctx.rect(LO.barX+6,0,LO.scX-LO.barX-6,H()); ctx.clip();
  ctx.globalCompositeOperation='lighter';
  slits.forEach(s=>{
    const maxR=Math.hypot(LO.scX-s.x,H()/2)*1.1;
    for(let i=0;i<NUM_R;i++){
      const r=((t*SPEED*0.05-i*LAM_PX)%(NUM_R*LAM_PX)+NUM_R*LAM_PX)%(NUM_R*LAM_PX);
      if(r<2) continue;
      const alpha=Math.max(0,(1-r/maxR)*0.14);
      if(alpha<0.003) continue;
      ctx.beginPath(); ctx.arc(s.x,s.y,r,0,Math.PI*2);
      ctx.strokeStyle=`rgba(${col.r},${col.g},${col.b},${alpha})`;
      ctx.lineWidth=1.2; ctx.stroke();
    }
  });
  ctx.globalCompositeOperation='source-over';
  ctx.restore();
}

/* 4.5 Screen – pixel-accurate intensity pattern */
function drawScreen() {
  const sx=LO.scX, sw=LO.scW, h=H();
  ctx.fillStyle='#06080f'; ctx.fillRect(sx,0,sw,h);
  ctx.strokeStyle='#ff7c3a'; ctx.lineWidth=2;
  ctx.beginPath(); ctx.moveTo(sx,0); ctx.lineTo(sx,h); ctx.stroke();

  const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
  const col=wlToRGB(P.lambda);
  const RANGE_M=0.030;
  const stripW=Math.max(1,Math.ceil(sw));
  const img=ctx.createImageData(stripW,h);

  for(let py=0;py<h;py++) {
    const y_m=(py/h-0.5)*RANGE_M*2;
    const I=screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N)*P.bright;
    const v=Math.min(1,Math.sqrt(I));
    for(let px=0;px<stripW;px++){
      const dep=0.55+0.45*(1-px/stripW);
      const idx=(py*stripW+px)*4;
      img.data[idx]   =Math.min(255,Math.round(col.r*v*dep));
      img.data[idx+1] =Math.min(255,Math.round(col.g*v*dep));
      img.data[idx+2] =Math.min(255,Math.round(col.b*v*dep));
      img.data[idx+3] =255;
    }
  }
  ctx.putImageData(img,sx,0);

  // Maxima markers
  if(ST.showMax&&P.N>1&&!ST.welcherWeg) {
    const dy_m=fringeSpacing()*1e-3;
    if(!isNaN(dy_m)&&dy_m>0){
      const dy_px=(dy_m/(RANGE_M*2))*h;
      ctx.strokeStyle='rgba(255,215,50,0.5)';
      ctx.lineWidth=0.8; ctx.setLineDash([2,4]);
      for(let m=-10;m<=10;m++){
        const yp=h/2+m*dy_px;
        if(yp<0||yp>h) continue;
        ctx.beginPath(); ctx.moveTo(sx,yp); ctx.lineTo(sx+sw,yp); ctx.stroke();
        if(Math.abs(m)<=3){
          ctx.fillStyle='rgba(255,215,50,0.6)';
          ctx.font='7px JetBrains Mono,monospace'; ctx.textAlign='left';
          ctx.fillText(`m=${m}`,sx+sw+2,yp+3);
        }
      }
      ctx.setLineDash([]);
    }
  }
  ctx.fillStyle='rgba(255,124,58,0.5)';
  ctx.font='8px JetBrains Mono,monospace'; ctx.textAlign='center';
  ctx.fillText('SCHIRM',sx+sw/2,12);
}

/* ─────────────────────────────────────────────────────────────────
   4.6  PHOTON ACCUMULATION BUFFER  ★ Neue Funktion ★
   Ein persistenter Offscreen-Canvas speichert alle aufgetroffenen
   Photonen. Das Muster baut sich statistisch auf – wie im echten
   Experiment.
   ───────────────────────────────────────────────────────────────── */
function initAccumBuffer() {
  if(!ST.accumCanvas) {
    ST.accumCanvas=document.createElement('canvas');
    ST.accumCtx=ST.accumCanvas.getContext('2d');
  }
  ST.accumCanvas.width=W(); ST.accumCanvas.height=H();
  ST.accumCtx.fillStyle='#06080f';
  ST.accumCtx.fillRect(0,0,W(),H());
  ST.photonCnt=0;
}

function clearAccumBuffer() {
  if(ST.accumCtx){
    ST.accumCtx.fillStyle='#06080f';
    ST.accumCtx.fillRect(0,0,ST.accumCanvas.width,ST.accumCanvas.height);
  }
  ST.photonCnt=0;
  ST.flyingPhotons=[];
  document.getElementById('pCount').textContent='0';
}

function addPhotonToAccum(y_px, col) {
  if(!ST.accumCtx) return;
  const x=LO.scX+LO.scW*(0.18+Math.random()*0.64);
  const r=0.8+Math.random()*1.8;
  ST.accumCtx.beginPath();
  ST.accumCtx.arc(x,y_px,r,0,Math.PI*2);
  ST.accumCtx.fillStyle=`rgba(${col.r},${col.g},${col.b},0.75)`;
  ST.accumCtx.fill();
}

/* ─────────────────────────────────────────────────────────────────
   4.7  FLYING PHOTON TRAJECTORIES  ★ Neue Funktion ★
   Animiert einzelne Photonen von der Quelle durch einen Spalt
   bis zum Schirm. Jede Landestelle wird aus der Intensitäts-
   verteilung gezogen – der Quanten-Zufall wird sichtbar.
   ───────────────────────────────────────────────────────────────── */
function spawnFlyingPhoton() {
  const slits=slitPos(), col=wlToRGB(P.lambda);
  const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
  const RANGE_M=0.030, h=H();

  // Pick slit (uniform for now)
  const si=Math.floor(Math.random()*slits.length);
  const slit=slits[si];

  // Sample landing position from intensity distribution
  let screenY=h/2;
  const maxTries=300;
  for(let i=0;i<maxTries;i++){
    const y_m=(Math.random()-0.5)*RANGE_M*2;
    const I=screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N)*P.bright;
    if(Math.random()<Math.min(1,I)){
      screenY=(y_m/(RANGE_M*2)+0.5)*h;
      break;
    }
  }

  ST.flyingPhotons.push({
    phase:'to_slit',
    x:LO.srcX, y:LO.midY,
    slitX:slit.x, slitY:slit.y,
    screenX:LO.scX+LO.scW*0.45,
    screenY,
    slitIdx:si,
    col, progress:0,
    speed:0.022+Math.random()*0.018,
  });
}

function updateAndDrawFlyingPhotons() {
  const toRemove=[];
  ST.flyingPhotons.forEach((ph,idx)=>{
    ph.progress+=ph.speed*Math.max(0.1,P.speed);
    const p=Math.min(1,ph.progress);

    if(ph.phase==='to_slit'){
      ph.x=LO.srcX+(ph.slitX-LO.srcX)*p;
      ph.y=LO.midY+(ph.slitY-LO.midY)*p;
      if(ph.progress>=1){ ph.phase='to_screen'; ph.progress=0; ph.x=ph.slitX; ph.y=ph.slitY; }
    } else {
      ph.x=ph.slitX+(ph.screenX-ph.slitX)*p;
      ph.y=ph.slitY+(ph.screenY-ph.slitY)*p;
      if(ph.progress>=1){
        addPhotonToAccum(ph.screenY,ph.col);
        ST.photonCnt++;
        document.getElementById('pCount').textContent=ST.photonCnt.toLocaleString('de-DE');
        toRemove.push(idx);
        return;
      }
    }

    // Draw photon dot with glow
    const gr=ctx.createRadialGradient(ph.x,ph.y,0,ph.x,ph.y,7);
    gr.addColorStop(0,`rgba(${ph.col.r},${ph.col.g},${ph.col.b},0.9)`);
    gr.addColorStop(1,'rgba(0,0,0,0)');
    ctx.beginPath(); ctx.arc(ph.x,ph.y,7,0,Math.PI*2);
    ctx.fillStyle=gr; ctx.fill();
    ctx.beginPath(); ctx.arc(ph.x,ph.y,1.8,0,Math.PI*2);
    ctx.fillStyle='rgba(255,255,255,0.95)'; ctx.fill();

    // Welcher-Weg: label which slit was used
    if(ST.welcherWeg&&ph.phase==='to_screen'&&ph.progress<0.35){
      ctx.fillStyle='rgba(255,80,80,0.9)';
      ctx.font='7px JetBrains Mono,monospace'; ctx.textAlign='center';
      ctx.fillText(`S${ph.slitIdx+1}`,ph.x,ph.y-10);
    }
  });
  toRemove.reverse().forEach(i=>ST.flyingPhotons.splice(i,1));

  // Spawn new photons (rate proportional to brightness)
  if(!ST.paused&&ST.flyingPhotons.length<18){
    const rate=Math.max(1,Math.ceil(P.bright*2.5));
    for(let i=0;i<rate;i++) spawnFlyingPhoton();
  }
}

function drawPhotonMode() {
  if(!ST.accumCanvas) initAccumBuffer();

  // ── Only paint the screen column ──────────────────────────────
  // The BG, wave field, source and barrier are already rendered
  // beneath this call, so we must NOT overdraw the whole canvas.
  const sx=LO.scX, sw=LO.scW, h=H();
  ctx.fillStyle='#06080f';
  ctx.fillRect(sx,0,sw,h);

  // Blit only the screen-column slice from the accumulation buffer
  ctx.drawImage(ST.accumCanvas, sx,0,sw,h, sx,0,sw,h);

  // Screen edge line
  ctx.strokeStyle='#ff7c3a'; ctx.lineWidth=2;
  ctx.beginPath(); ctx.moveTo(sx,0); ctx.lineTo(sx,h); ctx.stroke();

  // Maxima markers (same as wave mode, so user can compare)
  if(ST.showMax&&P.N>1&&!ST.welcherWeg) {
    const RANGE_M=0.030;
    const dy_m=fringeSpacing()*1e-3;
    if(!isNaN(dy_m)&&dy_m>0){
      const dy_px=(dy_m/(RANGE_M*2))*h;
      ctx.strokeStyle='rgba(255,215,50,0.35)';
      ctx.lineWidth=0.7; ctx.setLineDash([2,4]);
      for(let m=-10;m<=10;m++){
        const yp=h/2+m*dy_px;
        if(yp<0||yp>h) continue;
        ctx.beginPath(); ctx.moveTo(sx,yp); ctx.lineTo(sx+sw,yp); ctx.stroke();
      }
      ctx.setLineDash([]);
    }
  }

  // Flying photons drawn on top
  updateAndDrawFlyingPhotons();

  ctx.fillStyle='rgba(255,124,58,0.5)';
  ctx.font='8px JetBrains Mono,monospace'; ctx.textAlign='center';
  ctx.fillText('SCHIRM',sx+sw/2,12);
}

/* ─────────────────────────────────────────────────────────────────
   4.8  MEASUREMENT CURSOR  ★ Neue Funktion ★
   Hover über den Canvas zeigt Kreuzfadenlinien plus Info-Box mit
   Schirmposition y [mm] und normierter Intensität I(y).
   ───────────────────────────────────────────────────────────────── */
function drawMeasurementCursor() {
  const cx=ST.cursorX, cy=ST.cursorY;
  if(cx<0) return;
  const w=W(), h=H();

  ctx.save();
  ctx.strokeStyle='rgba(255,255,255,0.25)';
  ctx.lineWidth=0.7; ctx.setLineDash([3,5]);
  ctx.beginPath(); ctx.moveTo(cx,0); ctx.lineTo(cx,h); ctx.stroke();
  ctx.beginPath(); ctx.moveTo(0,cy); ctx.lineTo(w,cy); ctx.stroke();
  ctx.setLineDash([]);

  // Only show intensity readout when hovering over screen region
  if(cx>=LO.scX&&cx<=LO.scX+LO.scW) {
    const RANGE_M=0.030;
    const y_m=(cy/h-0.5)*RANGE_M*2;
    const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
    const I=screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N);
    const y_mm=(y_m*1000).toFixed(1);
    const I_pct=(I*100).toFixed(0);
    const col=wlToRGB(P.lambda);

    const bx=cx>w-115?cx-105:cx+8, by=Math.max(5,Math.min(h-46,cy-20));
    ctx.fillStyle='rgba(4,12,30,0.88)';
    ctx.strokeStyle=`rgba(${col.r},${col.g},${col.b},0.5)`;
    ctx.lineWidth=0.8;
    roundRect(ctx,bx,by,96,38,5); ctx.fill(); ctx.stroke();

    ctx.fillStyle='rgba(100,150,200,0.7)'; ctx.font='7px JetBrains Mono,monospace'; ctx.textAlign='left';
    ctx.fillText('y =',bx+7,by+13);
    ctx.fillStyle=`rgba(${col.r},${col.g},${col.b},1)`;
    ctx.font='bold 9px JetBrains Mono,monospace';
    ctx.fillText(`${y_mm} mm`,bx+25,by+13);
    ctx.fillStyle='rgba(100,150,200,0.7)'; ctx.font='7px JetBrains Mono,monospace';
    ctx.fillText('I =',bx+7,by+28);
    ctx.fillStyle='#fff'; ctx.font='bold 9px JetBrains Mono,monospace';
    ctx.fillText(`${I_pct} %`,bx+25,by+28);
  }
  ctx.restore();
}

/* ─────────────────────────────────────────────────────────────────
   4.8b  FESTE MESSPUNKTE  ★ Neue Funktion ★
   Bis zu 6 dauerhafte Messpunkte, die per Klick auf Schirm oder
   Diagramm gesetzt werden. Zeigen Position, Intensität, Abstand
   vom Zentralmaximum, Ordnung und (bei ≥2 Punkten) den Abstand
   zum vorherigen Punkt.
   ───────────────────────────────────────────────────────────────── */
const MEAS_COLORS = ['#ffd700','#ff6b9d','#10b981','#9b5cf6','#00ccff','#f59e0b'];
const MAX_MEAS = 6;

function yFromRowFrac(frac) {
  const RANGE_M = 0.030;
  return (frac - 0.5) * RANGE_M * 2;
}

function measStats(y_m) {
  const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
  const I  = screenI_eff(y_m, lam_m, d_m, a_m, Lm, P.N);
  const ds = pathDifference(y_m);
  const m  = ds/lam_m;
  return { y_mm: y_m*1000, I, ds_um: ds*1e6, order: m };
}

function addMeasPoint(y_m) {
  if (ST.measPoints.length >= MAX_MEAS) ST.measPoints.shift();
  ST.measPoints.push({ id: ++ST.measId, y_m, color: MEAS_COLORS[ST.measId % MEAS_COLORS.length] });
  refreshMeasList();
  requestAnimationFrame(drawGraph);
}

function removeMeasPoint(id) {
  ST.measPoints = ST.measPoints.filter(p => p.id !== id);
  refreshMeasList();
  requestAnimationFrame(drawGraph);
}

function refreshMeasList() {
  const el = document.getElementById('measList');
  if (!el) return;
  if (ST.measPoints.length === 0) {
    el.innerHTML = '<div class="meas-empty">Noch keine Messpunkte gesetzt – klicke auf den Schirm.</div>';
    return;
  }
  const sorted = [...ST.measPoints].sort((a,b)=>a.y_m-b.y_m);
  el.innerHTML = sorted.map((p, i) => {
    const s = measStats(p.y_m);
    const prev = i>0 ? sorted[i-1] : null;
    const gap = prev ? `&nbsp;·&nbsp;Δ zum Nachbarn: <b>${((p.y_m-prev.y_m)*1000).toFixed(2)} mm</b>` : '';
    return `<div class="meas-item">
      <span class="meas-dot" style="background:${p.color}"></span>
      <span>y=<b>${s.y_mm.toFixed(2)} mm</b>&nbsp;·&nbsp;I=<b>${(s.I*100).toFixed(0)}%</b>&nbsp;·&nbsp;m≈<b>${s.order.toFixed(2)}</b>${gap}</span>
      <button class="meas-rm" title="Entfernen" onclick="removeMeasPoint(${p.id})">✕</button>
    </div>`;
  }).join('');
}

function drawMeasPoints() {
  if (!ST.measPoints.length) return;
  const h=H(), sx=LO.scX, sw=LO.scW;
  ST.measPoints.forEach(p=>{
    const py=(p.y_m/0.030/2+0.5)*h;
    ctx.save();
    ctx.strokeStyle=p.color; ctx.lineWidth=1.3; ctx.setLineDash([4,3]);
    ctx.beginPath(); ctx.moveTo(0,py); ctx.lineTo(sx+sw,py); ctx.stroke();
    ctx.setLineDash([]);
    ctx.beginPath(); ctx.arc(sx+sw*0.5,py,4,0,Math.PI*2);
    ctx.fillStyle=p.color; ctx.fill();
    ctx.strokeStyle='#fff'; ctx.lineWidth=1; ctx.stroke();
    ctx.restore();
  });
}

/* ─────────────────────────────────────────────────────────────────
   4.8c  LERNMODUS: LIVE-GANGUNTERSCHIED  ★ Neue Funktion ★
   ───────────────────────────────────────────────────────────────── */
function lastInspectY() {
  if (ST.measPoints.length) return ST.measPoints[ST.measPoints.length-1].y_m;
  return 0;
}

function updateLearnLive(y_m) {
  if (y_m===null || y_m===undefined || isNaN(y_m)) return;
  const lam_m=P.lambda*1e-9;
  const s = measStats(y_m);
  const phi_deg = ((s.order % 1) * 360 + 360) % 360; // Phase innerhalb einer Periode
  const set=(id,v)=>{const e=document.getElementById(id); if(e) e.textContent=v;};
  set('lv-y', `${s.y_mm.toFixed(2)} mm`);
  set('lv-ds', `${s.ds_um.toFixed(3)} μm`);
  set('lv-dsl', `${s.order.toFixed(3)} λ`);
  set('lv-phi', `${phi_deg.toFixed(0)}°`);
  set('lv-m', Number.isInteger(Math.round(s.order*100)/100) ? s.order.toFixed(2) : s.order.toFixed(2));
  set('lv-i', `${(s.I*100).toFixed(0)} %`);
}

/* Zeichnet die zwei Weglinien von den Spalten zum ausgewählten Punkt,
   um den Gangunterschied Δs visuell erfahrbar zu machen. */
function drawPathDifference() {
  if (!ST.learnOn) return;
  const y_m = lastInspectY();
  const h=H();
  const targetY=(y_m/0.030/2+0.5)*h;
  const targetX=LO.scX;
  const slits=slitPos();
  if (slits.length<2) return;
  const s1=slits[0], s2=slits[slits.length-1];
  ctx.save();
  ctx.setLineDash([5,4]);
  ctx.lineWidth=1.3;
  ctx.strokeStyle='rgba(255,215,0,0.85)';
  ctx.beginPath(); ctx.moveTo(s1.x,s1.y); ctx.lineTo(targetX,targetY); ctx.stroke();
  ctx.strokeStyle='rgba(155,92,246,0.85)';
  ctx.beginPath(); ctx.moveTo(s2.x,s2.y); ctx.lineTo(targetX,targetY); ctx.stroke();
  ctx.setLineDash([]);
  ctx.beginPath(); ctx.arc(targetX,targetY,4,0,Math.PI*2);
  ctx.fillStyle='#fff'; ctx.fill();
  ctx.restore();
}

/* ─────────────────────────────────────────────────────────────────
   4.8d  AUTOMATISCHE AUSWERTUNG  ★ Neue Funktion ★
   ───────────────────────────────────────────────────────────────── */
function updateEvaluation() {
  const dyTheory = fringeSpacing();
  const set=(id,v,cls)=>{const e=document.getElementById(id); if(!e)return; e.textContent=v; if(cls){e.className='v '+cls;} };
  set('ev-c0', 'y = 0.00 mm');

  if (P.N===1 || ST.welcherWeg || isNaN(dyTheory)) {
    set('ev-dy','–'); set('ev-dysim','–'); set('ev-dev','–'); set('ev-cnt','0');
    document.getElementById('evalTbody').innerHTML =
      '<tr><td colspan="4" style="color:var(--mu);font-style:italic">Kein Interferenzmuster (Einzelspalt oder Welcher-Weg aktiv)</td></tr>';
    return;
  }

  const peaks = findSimulatedMaxima();
  const RANGE_MM = 30;
  const visible = peaks.filter(p=>Math.abs(p.y_m*1000)<=RANGE_MM);

  // Simulierter Streifenabstand: Abstand zwischen den simulierten Maxima
  // nächst m=0 und m=1 (robust gegen fehlende Ordnungen an
  // Beugungshüllkurven-Nullstellen, z.B. wenn d/a ganzzahlig ist).
  let dySim = NaN;
  if (visible.length>=2) {
    const nearest=(yTargetM)=>{
      let best=null, bd=Infinity;
      visible.forEach(p=>{const diff=Math.abs(p.y_m-yTargetM/1000); if(diff<bd){bd=diff;best=p;}});
      return best;
    };
    const p0=nearest(0), p1=nearest(dyTheory);
    if (p0 && p1 && p0!==p1) dySim = Math.abs(p1.y_m-p0.y_m)*1000;
  }

  set('ev-dy', `${dyTheory.toFixed(3)} mm`);
  set('ev-dysim', isNaN(dySim)?'–':`${dySim.toFixed(3)} mm`);
  if (!isNaN(dySim)) {
    const dev = Math.abs(dySim-dyTheory)/dyTheory*100;
    set('ev-dev', `${dev.toFixed(2)} %`, dev<2?'dev-ok':(dev>8?'dev-bad':''));
  } else {
    set('ev-dev','–');
  }
  set('ev-cnt', `${visible.length}`);

  // Tabelle: theoretische Ordnungen m vs. nächstliegendes simuliertes Maximum
  const mMax = Math.min(8, Math.floor(RANGE_MM/dyTheory));
  let rows='';
  for (let m=-mMax; m<=mMax; m++) {
    const yTheo = m*dyTheory;
    let closest=null, bestDiff=Infinity;
    visible.forEach(p=>{
      const diff=Math.abs(p.y_m*1000-yTheo);
      if(diff<bestDiff){bestDiff=diff;closest=p;}
    });
    const ySim = closest ? (closest.y_m*1000) : NaN;
    const diffUm = closest ? Math.abs(ySim-yTheo)*1000 : NaN;
    rows += `<tr><td class="${m===0?'m0':''}">${m}</td><td>${yTheo.toFixed(3)}</td><td>${isNaN(ySim)?'–':ySim.toFixed(3)}</td><td>${isNaN(diffUm)?'–':diffUm.toFixed(1)}</td></tr>`;
  }
  document.getElementById('evalTbody').innerHTML = rows;
}

function roundRect(ctx2, x, y, w, h, r) {
  ctx2.beginPath();
  ctx2.moveTo(x+r,y); ctx2.lineTo(x+w-r,y);
  ctx2.quadraticCurveTo(x+w,y,x+w,y+r); ctx2.lineTo(x+w,y+h-r);
  ctx2.quadraticCurveTo(x+w,y+h,x+w-r,y+h); ctx2.lineTo(x+r,y+h);
  ctx2.quadraticCurveTo(x,y+h,x,y+h-r); ctx2.lineTo(x,y+r);
  ctx2.quadraticCurveTo(x,y,x+r,y); ctx2.closePath();
}

/* 4.9 Labels */
function drawLabels() {
  const h=H();
  ctx.strokeStyle='rgba(100,150,200,0.18)'; ctx.lineWidth=0.8; ctx.setLineDash([3,5]);
  ctx.beginPath(); ctx.moveTo(LO.barX,h-11); ctx.lineTo(LO.scX,h-11); ctx.stroke();
  ctx.setLineDash([]);
  ctx.fillStyle='rgba(100,150,200,0.45)'; ctx.font='8px JetBrains Mono,monospace'; ctx.textAlign='center';
  ctx.fillText(`L = ${P.L} mm`,(LO.barX+LO.scX)/2,h-2);
}

/* ══════════════════════════════════════════════════════════════════
   § 5  ANIMATION LOOP
   ══════════════════════════════════════════════════════════════════ */

function renderFrame(ts) {
  if(!ST.paused || ST.stepFrame) {
    const dt=ST.lastTs>0 ? Math.min(50,ts-ST.lastTs)/1000 : 1/60;
    ST.t+=ST.stepFrame ? (1/24) : dt;
    ST.stepFrame=false;
  }
  ST.lastTs=ts;
  const t=ST.t;

  drawBG();

  if(ST.mode!=='photon') {
    drawSource(t);
    drawAnimatedField(t);
    if(ST.showWF) drawWavefronts(t);
  }

  drawBarrier();

  if(ST.mode==='photon') {
    drawPhotonMode();
  } else {
    drawScreen();
  }

  drawMeasPoints();
  drawPathDifference();
  drawMeasurementCursor();
  drawLabels();
  ST.animId=requestAnimationFrame(renderFrame);
}

function startAnim() {
  if(ST.animId) cancelAnimationFrame(ST.animId);
  ST.lastTs=0;
  ST.animId=requestAnimationFrame(renderFrame);
}

/* ══════════════════════════════════════════════════════════════════
   § 6  INTENSITY GRAPH – with hover cursor
   ══════════════════════════════════════════════════════════════════ */

function drawGraph() {
  const gw=GW(), gh=GH();
  gx.fillStyle='#040e1e'; gx.fillRect(0,0,gw,gh);

  // Grid
  gx.strokeStyle='rgba(255,255,255,0.04)'; gx.lineWidth=0.5;
  [0.25,0.5,0.75].forEach(f=>{gx.beginPath();gx.moveTo(0,gh*f);gx.lineTo(gw,gh*f);gx.stroke()});

  const lam_m=P.lambda*1e-9, d_m=P.d*1e-6, a_m=P.a*1e-6, Lm=P.L*1e-3;
  const col=wlToRGB(P.lambda);
  const RANGE=0.030;

  // Main curve
  const pts=[];
  for(let px=0;px<=gw;px++){
    const y_m=((px/gw)-0.5)*RANGE*2;
    const I=screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N)*P.bright;
    const yp=gh-Math.min(1,Math.sqrt(I))*(gh-18)-5;
    pts.push(yp);
  }

  // Fill
  gx.beginPath(); gx.moveTo(0,gh);
  pts.forEach((y,x)=>gx.lineTo(x,y));
  gx.lineTo(gw,gh); gx.closePath();
  const grad=gx.createLinearGradient(0,0,0,gh);
  grad.addColorStop(0,`rgba(${col.r},${col.g},${col.b},0.38)`);
  grad.addColorStop(1,`rgba(${col.r},${col.g},${col.b},0.02)`);
  gx.fillStyle=grad; gx.fill();

  // Line
  gx.beginPath();
  pts.forEach((y,x)=>(x===0?gx.moveTo(x,y):gx.lineTo(x,y)));
  gx.strokeStyle=`rgba(${col.r},${col.g},${col.b},0.92)`;
  gx.lineWidth=1.8; gx.stroke();

  // Envelope
  if(ST.showEnv&&P.N>1&&!ST.welcherWeg){
    gx.beginPath();
    for(let px=0;px<=gw;px++){
      const y_m=((px/gw)-0.5)*RANGE*2;
      const sinT=y_m/Math.hypot(y_m,Lm);
      const env=sinc(a_m*sinT/lam_m)**2*P.bright;
      const yp=gh-Math.min(1,Math.sqrt(env))*(gh-18)-5;
      px===0?gx.moveTo(px,yp):gx.lineTo(px,yp);
    }
    gx.strokeStyle='rgba(255,185,50,0.5)'; gx.lineWidth=1.2;
    gx.setLineDash([4,5]); gx.stroke(); gx.setLineDash([]);
  }

  // Centre axis
  gx.strokeStyle='rgba(255,255,255,0.07)'; gx.lineWidth=0.8;
  gx.setLineDash([2,4]);
  gx.beginPath(); gx.moveTo(gw/2,0); gx.lineTo(gw/2,gh); gx.stroke();
  gx.setLineDash([]);

  // Labels
  gx.fillStyle='rgba(100,150,200,0.5)'; gx.font='8px JetBrains Mono,monospace';
  gx.textAlign='left';  gx.fillText('I',4,12);
  gx.textAlign='center';gx.fillText('Position y auf dem Schirm',gw/2,gh-2);
  gx.textAlign='right'; gx.fillText('+30mm',gw-2,gh-10);
  gx.textAlign='left';  gx.fillText('-30mm',2,gh-10);

  // ── Feste Messpunkte
  ST.measPoints.forEach(p=>{
    const px=((p.y_m/(RANGE*2))+0.5)*gw;
    if(px<0||px>gw) return;
    gx.save();
    gx.strokeStyle=p.color; gx.lineWidth=1.1; gx.setLineDash([3,3]);
    gx.beginPath(); gx.moveTo(px,0); gx.lineTo(px,gh); gx.stroke();
    gx.setLineDash([]);
    gx.restore();
  });

  // ── Graph hover cursor
  if(ST.graphCursorX>=0&&ST.graphCursorX<=gw){
    const px=ST.graphCursorX;
    const y_m=((px/gw)-0.5)*RANGE*2;
    const I=screenI_eff(y_m,lam_m,d_m,a_m,Lm,P.N)*P.bright;
    const yp=gh-Math.min(1,Math.sqrt(I))*(gh-18)-5;

    gx.strokeStyle='rgba(255,255,255,0.3)'; gx.lineWidth=0.7; gx.setLineDash([2,3]);
    gx.beginPath(); gx.moveTo(px,0); gx.lineTo(px,gh); gx.stroke();
    gx.setLineDash([]);

    // Dot on curve
    gx.beginPath(); gx.arc(px,yp,3.5,0,Math.PI*2);
    gx.fillStyle=`rgba(${col.r},${col.g},${col.b},1)`; gx.fill();
    gx.strokeStyle='#fff'; gx.lineWidth=1; gx.stroke();

    // Tooltip
    const y_mm=(y_m*1000).toFixed(1);
    const I_pct=(I*100).toFixed(0);
    const bx=px>gw-90?px-88:px+6;
    const by=Math.max(2,Math.min(gh-26,yp-12));
    gx.fillStyle='rgba(4,12,30,0.9)';
    roundRect(gx,bx,by,82,22,4); gx.fill();
    gx.fillStyle='rgba(100,150,200,0.7)'; gx.font='7px JetBrains Mono,monospace';
    gx.textAlign='left'; gx.fillText(`y=${y_mm}mm  I=${I_pct}%`,bx+4,by+14);
  }
}

/* ══════════════════════════════════════════════════════════════════
   § 7  UI & EVENT-LISTENER
   ══════════════════════════════════════════════════════════════════ */

function setSliderBg(el) {
  const pct=((el.value-el.min)/(el.max-el.min))*100;
  el.style.background=`linear-gradient(to right,#00ccff 0%,#00ccff ${pct}%,#071528 ${pct}%)`;
}

function updateWlThumb() {
  const pct=(P.lambda-380)/(750-380)*100;
  const thumb=document.getElementById('wlThumb');
  thumb.style.left=pct+'%'; thumb.style.background=wlCSS(P.lambda,1);
}

function updateInfo() {
  const dy=fringeSpacing();
  const f_THz=(C_LIGHT/(P.lambda*1e-9))/1e12;
  document.getElementById('iv-lam').innerHTML=`${P.lambda}<span class="chip-u">nm</span>`;
  document.getElementById('iv-f').innerHTML=`${f_THz.toFixed(1)}<span class="chip-u">THz</span>`;
  document.getElementById('iv-d').innerHTML=`${P.d}<span class="chip-u">μm</span>`;
  document.getElementById('iv-L').innerHTML=`${P.L}<span class="chip-u">mm</span>`;
  document.getElementById('iv-a').innerHTML=`${P.a}<span class="chip-u">μm</span>`;
  document.getElementById('iv-dy').innerHTML=isNaN(dy)?`–`:`${dy.toFixed(2)}<span class="chip-u">mm</span>`;
  document.getElementById('iv-mx').textContent=visMaxima();
  document.getElementById('fringeInfo').textContent=isNaN(dy)?'':`Δy ≈ ${dy.toFixed(2)} mm`;
  document.getElementById('sv-f').textContent=`${f_THz.toFixed(2)} THz`;
}

function syncUI() {
  document.getElementById('sv-lam').textContent=`${P.lambda} nm`;
  document.getElementById('sv-d').textContent=`${P.d} μm`;
  document.getElementById('sv-a').textContent=`${P.a} μm`;
  document.getElementById('sv-L').textContent=`${P.L} mm`;
  document.getElementById('sv-br').textContent=`${Math.round(P.bright*100)} %`;
  document.getElementById('sv-sp').textContent=`${P.speed.toFixed(1)}×`;
  document.getElementById('sv-amp').textContent=`${P.amp.toFixed(2)}`;
  document.getElementById('sv-coh').textContent=`${Math.round(P.coh*100)} %`;
  updateWlThumb(); updateInfo();
  requestAnimationFrame(drawGraph);
  refreshMeasList();
  updateEvaluation();
  updateLearnLive(lastInspectY());
}

// ── Physical-constraint helpers ───────────────────────────────────
/**
 * Minimum gap between slit edges (μm).  Slits must never overlap.
 */
const MIN_GAP = 5;

/**
 * Recompute valid min/max for the d and a sliders and clamp
 * P.d / P.a into that range.  Call after any change to P.d,
 * P.a, P.N, or canvas size (N=5 upper bound depends on H()).
 *
 * Rules enforced:
 *   1. d ≥ a + MIN_GAP          (slit edges never touch)
 *   2. d_max depends on N so all slit centres stay inside canvas
 *   3. a ≤ d − MIN_GAP          (derived from rule 1)
 */
function updateSliderBounds() {
  const elD = document.getElementById('sl-d');
  const elA = document.getElementById('sl-a');

  // ── d: absolute limits only – NOT coupled to a ────────────────
  // d can always move freely; a will follow it downward.
  const dMin = 30;
  const offFactor = P.N === 1 ? 0 : P.N === 2 ? 0.5 : 1.0;
  const dMaxRaw   = offFactor > 0
    ? ((H() / 2 - 20) * 400) / (H() * 0.55 * offFactor)
    : 500;
  const dMax     = Math.min(500, Math.floor(dMaxRaw / 5) * 5);
  const dMaxSafe = Math.max(dMin, dMax);

  elD.min   = dMin;
  elD.max   = dMaxSafe;
  P.d       = Math.max(dMin, Math.min(dMaxSafe, Math.round(P.d / 5) * 5));
  elD.value = P.d;

  // ── a: upper bound follows d downward ─────────────────────────
  // When d shrinks, aMax shrinks → a is automatically clamped down.
  const aMax  = Math.max(3, P.d - MIN_GAP);
  elA.min     = 3;
  elA.max     = aMax;
  P.a         = Math.max(3, Math.min(aMax, P.a));
  elA.value   = P.a;

  setSliderBg(elD);
  setSliderBg(elA);
}

// ── Sliders ───────────────────────────────────────────────────────
const SLIDERS = [
  { id: 'sl-lam', key: 'lambda', parse: v => +v },
  { id: 'sl-d',   key: 'd',     parse: v => +v },
  { id: 'sl-a',   key: 'a',     parse: v => +v },
  { id: 'sl-L',   key: 'L',     parse: v => +v },
  { id: 'sl-br',  key: 'bright',parse: v => +v / 100 },
  { id: 'sl-sp',  key: 'speed', parse: v => +v / 10 },
  { id: 'sl-amp', key: 'amp',   parse: v => +v / 100 },
  { id: 'sl-coh', key: 'coh',   parse: v => +v / 100 },
];

SLIDERS.forEach(({ id, key, parse }) => {
  const el = document.getElementById(id);
  setSliderBg(el);
  el.addEventListener('input', () => {
    P[key] = parse(el.value);
    if (key === 'a') {
      // Slit width grew → push d up so edges never overlap
      if (P.d < P.a + MIN_GAP) {
        P.d = Math.min(500, Math.ceil((P.a + MIN_GAP) / 5) * 5);
        const elD = document.getElementById('sl-d');
        elD.value = P.d;
      }
    }
    // For both d and a: recalculate bounds (clamps a down when d shrank)
    if (key === 'd' || key === 'a') updateSliderBounds();
    setSliderBg(el);
    syncUI();
    if (ST.soundOn && ST.audioOsc && ST.audioCtx)
      ST.audioOsc.frequency.setValueAtTime(
        180 + (P.lambda - 380) / 370 * 500, ST.audioCtx.currentTime
      );
  });
});

// ── Slit count
document.querySelectorAll('#slitSeg .seg-btn').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('#slitSeg .seg-btn').forEach(b=>b.classList.remove('on'));
    btn.classList.add('on'); P.N=parseInt(btn.dataset.n,10);
    updateSliderBounds(); syncUI();
    if(ST.mode==='photon') clearAccumBuffer();
  });
});

// ── Mode
const MODE_LBL={wave:'Wellenmodus aktiv',photon:'Photonenmodus aktiv',field:'Feldmodus aktiv'};
document.querySelectorAll('#modeSeg .seg-btn').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('#modeSeg .seg-btn').forEach(b=>b.classList.remove('on'));
    btn.classList.add('on'); ST.mode=btn.dataset.m;
    document.getElementById('modeLbl').textContent=MODE_LBL[ST.mode];
    const pb=document.getElementById('photonBar');
    if(ST.mode==='photon'){ pb.style.display='flex'; initAccumBuffer(); }
    else pb.style.display='none';
    syncUI();
  });
});

// ── Checkboxes
document.getElementById('chk-env').addEventListener('change',e=>{ST.showEnv=e.target.checked;requestAnimationFrame(drawGraph)});
document.getElementById('chk-max').addEventListener('change',e=>{ST.showMax=e.target.checked});
document.getElementById('chk-wf') .addEventListener('change',e=>{ST.showWF=e.target.checked});
const chkWW = document.getElementById('chk-ww');
if(chkWW){
  chkWW.addEventListener('change',e=>{
    ST.welcherWeg=e.target.checked;
    const badge = document.getElementById('wwBadge');
    if(badge) badge.classList.toggle('on',ST.welcherWeg);
    if(ST.mode==='photon') clearAccumBuffer();
    syncUI();
  });
}

// ── Buttons
document.getElementById('btnPause').addEventListener('click',function(){
  ST.paused=!ST.paused; this.textContent=ST.paused?'▶ Weiter':'⏸ Pause';
});

document.getElementById('btnClear').addEventListener('click',()=>clearAccumBuffer());

document.getElementById('btnReset').addEventListener('click',()=>{
  P.lambda=550;P.d=150;P.a=30;P.L=1000;P.bright=1;P.N=2;P.speed=1;P.amp=1;P.coh=1;
  document.getElementById('sl-lam').value=550;
  document.getElementById('sl-d').value=150;
  document.getElementById('sl-a').value=30;
  document.getElementById('sl-L').value=1000;
  document.getElementById('sl-br').value=100;
  document.getElementById('sl-sp').value=10;
  document.getElementById('sl-amp').value=100;
  document.getElementById('sl-coh').value=100;
  SLIDERS.forEach(({id})=>setSliderBg(document.getElementById(id)));
  document.querySelectorAll('#modeSeg .seg-btn').forEach(b=>b.classList.remove('on'));
  document.querySelector('#modeSeg .seg-btn[data-m="wave"]').classList.add('on');
  document.querySelectorAll('#fieldSeg .seg-btn').forEach(b=>b.classList.remove('on'));
  document.querySelector('#fieldSeg .seg-btn[data-f="amplitude"]').classList.add('on');
  ST.mode='wave'; ST.fieldMode='amplitude'; ST.paused=false; ST.welcherWeg=false;
  ST.measPoints=[]; ST.stepFrame=false;
  document.getElementById('modeLbl').textContent='Wellenmodus aktiv';
  document.getElementById('photonBar').style.display='none';
  document.getElementById('btnPause').textContent='⏸ Pause';
  document.getElementById('wwBadge').classList.remove('on');
  document.getElementById('chk-ww').checked=false;
  document.getElementById('chk-env').checked=true; ST.showEnv=true;
  document.getElementById('chk-max').checked=true; ST.showMax=true;
  document.getElementById('chk-wf').checked=true;  ST.showWF=true;
  document.querySelectorAll('#slitSeg .seg-btn').forEach(b=>b.classList.remove('on'));
  document.querySelector('#slitSeg .seg-btn[data-n="2"]').classList.add('on');
  clearAccumBuffer(); updateSliderBounds(); syncUI(); refreshMeasList();
});

document.getElementById('btnFS').addEventListener('click',()=>{
  const el=document.getElementById('cvBox');
  if(!document.fullscreenElement) el.requestFullscreen?.();
  else document.exitFullscreen?.();
});

document.getElementById('btnShot').addEventListener('click',()=>{
  const a=document.createElement('a');
  a.href=MC.toDataURL('image/png'); a.download='doppelspalt_simulation.png'; a.click();
});

// ── Sound
document.getElementById('btnSound').addEventListener('click',function(){
  ST.soundOn=!ST.soundOn; this.textContent=ST.soundOn?'🔊 Ton':'🔇 Ton';
  if(ST.soundOn){
    ST.audioCtx=ST.audioCtx||new(window.AudioContext||window.webkitAudioContext)();
    const ac=ST.audioCtx;
    const osc=ac.createOscillator(), gn=ac.createGain();
    osc.type='sine';
    osc.frequency.setValueAtTime(180+(P.lambda-380)/370*500,ac.currentTime);
    gn.gain.setValueAtTime(0.025,ac.currentTime);
    osc.connect(gn); gn.connect(ac.destination); osc.start();
    ST.audioOsc=osc; ST.audioGain=gn;
  } else { ST.audioOsc?.stop?.(); ST.audioOsc=null; }
});

// ── Canvas mouse: measurement cursor
MC.addEventListener('mousemove',e=>{
  const rect=MC.getBoundingClientRect();
  const sx=MC.width/rect.width, sy=MC.height/rect.height;
  ST.cursorX=(e.clientX-rect.left)*sx;
  ST.cursorY=(e.clientY-rect.top)*sy;
  if (ST.learnOn) updateLearnLive(yFromRowFrac(ST.cursorY/H()));
});
MC.addEventListener('mouseleave',()=>{ ST.cursorX=-1; ST.cursorY=-1; });

MC.addEventListener('click',e=>{
  const rect=MC.getBoundingClientRect();
  const sy=MC.height/rect.height;
  const py=(e.clientY-rect.top)*sy;
  const y_m=yFromRowFrac(py/H());
  addMeasPoint(y_m);
  updateLearnLive(y_m);
});

// ── Graph mouse: hover values
GC.addEventListener('mousemove',e=>{
  const rect=GC.getBoundingClientRect();
  ST.graphCursorX=(e.clientX-rect.left)*(GC.width/rect.width);
  requestAnimationFrame(drawGraph);
  if (ST.learnOn) {
    const y_m=((ST.graphCursorX/GW())-0.5)*0.030*2;
    updateLearnLive(y_m);
  }
});
GC.addEventListener('mouseleave',()=>{ ST.graphCursorX=-1; requestAnimationFrame(drawGraph); });
GC.addEventListener('click',e=>{
  const rect=GC.getBoundingClientRect();
  const px=(e.clientX-rect.left)*(GC.width/rect.width);
  const y_m=((px/GW())-0.5)*0.030*2;
  addMeasPoint(y_m);
  updateLearnLive(y_m);
});

// ── Field-visualisation mode (Amplitude / Intensität / nur Wellenfront)
document.querySelectorAll('#fieldSeg .seg-btn').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('#fieldSeg .seg-btn').forEach(b=>b.classList.remove('on'));
    btn.classList.add('on'); ST.fieldMode=btn.dataset.f;
    if (ST.fieldMode==='wavefront') {
      ST.showWF=true;
      document.getElementById('chk-wf').checked=true;
    }
  });
});

// ── Auxiliary panel tabs (Lernmodus / Messpunkte / Auswertung)
const PANELS={learn:{tab:'tabLearn',panel:'panelLearn'},meas:{tab:'tabMeas',panel:'panelMeas'},eval:{tab:'tabEval',panel:'panelEval'}};
function setActivePanel(name){
  ST.activePanel = (ST.activePanel===name) ? null : name;
  ST.learnOn = ST.activePanel==='learn';
  Object.entries(PANELS).forEach(([key,ids])=>{
    const on = ST.activePanel===key;
    document.getElementById(ids.tab).classList.toggle('on',on);
    document.getElementById(ids.panel).classList.toggle('on',on);
  });
  if (ST.activePanel==='eval') updateEvaluation();
  if (ST.activePanel==='meas') refreshMeasList();
  if (ST.activePanel==='learn') updateLearnLive(lastInspectY());
}
document.getElementById('tabLearn').addEventListener('click',()=>setActivePanel('learn'));
document.getElementById('tabMeas').addEventListener('click',()=>setActivePanel('meas'));
document.getElementById('tabEval').addEventListener('click',()=>setActivePanel('eval'));
document.getElementById('btnMeasClear').addEventListener('click',()=>{ST.measPoints=[];refreshMeasList();requestAnimationFrame(drawGraph);});

// ── Step-Animation (Einzelbild vorwärts, nur im Pause-Modus sinnvoll)
document.getElementById('btnStep').addEventListener('click',()=>{
  ST.paused=true;
  document.getElementById('btnPause').textContent='▶ Weiter';
  ST.stepFrame=true;
});

// ── Zweiter Vollbild-Knopf im Bedienpanel (gleiche Funktion wie btnFS)
document.getElementById('btnFS2').addEventListener('click',()=>{
  document.getElementById('btnFS').click();
});

/* ──────────────────────────────────────────────
   ★ KEYBOARD SHORTCUTS ★
   ────────────────────────────────────────────── */
document.addEventListener('keydown',e=>{
  // Don't fire on inputs
  if(e.target.tagName==='INPUT'||e.target.tagName==='TEXTAREA') return;
  switch(e.key){
    case ' ': e.preventDefault();
      ST.paused=!ST.paused;
      document.getElementById('btnPause').textContent=ST.paused?'▶ Weiter':'⏸ Pause';
      break;
    case 'r': case 'R':
      document.getElementById('btnReset').click(); break;
    case 'ArrowRight':
      P.lambda=Math.min(750,P.lambda+5);
      document.getElementById('sl-lam').value=P.lambda;
      setSliderBg(document.getElementById('sl-lam')); syncUI(); break;
    case 'ArrowLeft':
      P.lambda=Math.max(380,P.lambda-5);
      document.getElementById('sl-lam').value=P.lambda;
      setSliderBg(document.getElementById('sl-lam')); syncUI(); break;
    case 'ArrowUp':
      P.d=Math.min(500,P.d+5);
      document.getElementById('sl-d').value=P.d;
      setSliderBg(document.getElementById('sl-d')); syncUI(); break;
    case 'ArrowDown':
      P.d=Math.max(30,P.d-5);
      document.getElementById('sl-d').value=P.d;
      setSliderBg(document.getElementById('sl-d')); syncUI(); break;
    case '1':
      document.querySelector('#slitSeg .seg-btn[data-n="1"]').click(); break;
    case '2':
      document.querySelector('#slitSeg .seg-btn[data-n="2"]').click(); break;
    case 's': case 'S':
      document.getElementById('btnStep').click(); break;
    case 'l': case 'L':
      setActivePanel('learn'); break;
  }
});

/* ══════════════════════════════════════════════════════════════════
   § 8  HERO BACKGROUND ANIMATION
   ══════════════════════════════════════════════════════════════════ */

(function heroAnim(){
  const hc=document.getElementById('heroCanvas');
  const hx=hc.getContext('2d');
  function rsz(){hc.width=hc.offsetWidth||window.innerWidth;hc.height=hc.offsetHeight||window.innerHeight}
  rsz(); window.addEventListener('resize',rsz);
  const COLORS=['#00ccff','#9b5cf6','#ff6b9d','#00ff88','#ffd700'];
  const nodes=Array.from({length:7},(_,i)=>({
    x:Math.random()*(hc.width||800),y:Math.random()*(hc.height||600),
    color:COLORS[i%COLORS.length],timer:Math.random()*200,interval:100+Math.random()*200,
    vx:(Math.random()-.5)*0.3,vy:(Math.random()-.5)*0.3,
  }));
  const rings=[];
  function frame(){
    const W=hc.width,H=hc.height;
    hx.clearRect(0,0,W,H);
    nodes.forEach(n=>{
      n.x+=n.vx; n.y+=n.vy;
      if(n.x<0||n.x>W)n.vx*=-1;
      if(n.y<0||n.y>H)n.vy*=-1;
      if(++n.timer>n.interval){n.timer=0;rings.push({x:n.x,y:n.y,r:0,maxR:180+Math.random()*150,color:n.color})}
    });
    for(let i=rings.length-1;i>=0;i--){
      const rng=rings[i]; rng.r+=1.1;
      const alpha=0.45*(1-rng.r/rng.maxR);
      if(alpha<=0){rings.splice(i,1);continue}
      const hex=rng.color;
      const r=parseInt(hex.slice(1,3),16),g=parseInt(hex.slice(3,5),16),b=parseInt(hex.slice(5,7),16);
      hx.beginPath(); hx.arc(rng.x,rng.y,rng.r,0,Math.PI*2);
      hx.strokeStyle=`rgba(${r},${g},${b},${alpha.toFixed(3)})`; hx.lineWidth=1.4; hx.stroke();
    }
    requestAnimationFrame(frame);
  }
  requestAnimationFrame(frame);
})();

/* ══════════════════════════════════════════════════════════════════
   § 10  INITIALISATION
   ══════════════════════════════════════════════════════════════════ */

window.addEventListener('resize',()=>{resizeCvs(); updateSliderBounds(); requestAnimationFrame(drawGraph)});
resizeCvs();
SLIDERS.forEach(({id})=>setSliderBg(document.getElementById(id)));
updateSliderBounds();   // set correct d/a interdependency from the start
syncUI();
startAnim();
drawGraph();

console.log(
  '%cYoungs Doppelspaltexperiment\n%cInteraktive Quantenphysik-Simulation v2',
  'color:#00ccff;font-size:1.1rem;font-weight:bold',
  'color:#94a3b8;font-size:.85rem'
);
</script>
</body>
</html>
