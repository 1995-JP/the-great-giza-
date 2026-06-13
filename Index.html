<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Hidden Geometry of Giza</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Rajdhani:wght@300;400;600&display=swap');

  :root {
    --gold: #C9A84C;
    --gold-bright: #FFD770;
    --gold-dim: #7A6030;
    --obsidian: #080608;
    --deep: #0D0B0F;
    --sand: #D4B483;
    --glow: rgba(201,168,76,0.18);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--obsidian);
    color: var(--sand);
    font-family: 'Rajdhani', sans-serif;
    overflow-x: hidden;
    min-height: 100vh;
  }

  /* ── STARFIELD ── */
  #stars {
    position: fixed; inset: 0;
    pointer-events: none;
    z-index: 0;
  }

  /* ── HERO ── */
  .hero {
    position: relative;
    z-index: 1;
    text-align: center;
    padding: 60px 20px 20px;
  }
  .hero-eyebrow {
    font-family: 'Rajdhani', sans-serif;
    font-size: 11px;
    letter-spacing: 6px;
    color: var(--gold-dim);
    text-transform: uppercase;
    margin-bottom: 16px;
  }
  .hero-title {
    font-family: 'Cinzel', serif;
    font-size: clamp(28px, 7vw, 64px);
    font-weight: 900;
    line-height: 1.05;
    background: linear-gradient(160deg, #FFD770 0%, #C9A84C 50%, #7A6030 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 12px;
  }
  .hero-sub {
    font-size: 14px;
    letter-spacing: 3px;
    color: var(--gold-dim);
    text-transform: uppercase;
  }

  /* ── SECTION LABEL ── */
  .section-label {
    font-family: 'Cinzel', serif;
    font-size: 10px;
    letter-spacing: 5px;
    color: var(--gold-dim);
    text-transform: uppercase;
    text-align: center;
    margin: 48px 0 12px;
  }

  /* ── STEP CARDS ── */
  .steps {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2px;
    max-width: 700px;
    margin: 0 auto;
    padding: 0 16px;
    position: relative;
    z-index: 1;
  }
  .step-card {
    background: linear-gradient(135deg, #13100A 0%, #0A0805 100%);
    border: 1px solid var(--gold-dim);
    padding: 24px 20px;
    position: relative;
    overflow: hidden;
    cursor: pointer;
    transition: border-color 0.3s, background 0.3s;
  }
  .step-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse at 50% 0%, var(--glow) 0%, transparent 70%);
    opacity: 0;
    transition: opacity 0.4s;
  }
  .step-card:hover::before { opacity: 1; }
  .step-card:hover { border-color: var(--gold); }

  .step-num {
    font-family: 'Cinzel', serif;
    font-size: 36px;
    font-weight: 900;
    color: var(--gold-dim);
    line-height: 1;
    margin-bottom: 8px;
    transition: color 0.3s;
  }
  .step-card:hover .step-num { color: var(--gold-bright); }
  .step-title {
    font-family: 'Cinzel', serif;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 2px;
    color: var(--gold);
    margin-bottom: 10px;
    text-transform: uppercase;
  }
  .step-body {
    font-size: 13px;
    line-height: 1.6;
    color: #A09070;
    font-weight: 300;
  }

  /* ── SVG DIAGRAMS ── */
  .diagrams {
    max-width: 700px;
    margin: 0 auto;
    padding: 0 16px;
    position: relative;
    z-index: 1;
  }
  .diagram-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2px;
    margin-bottom: 2px;
  }
  .diagram-box {
    background: #0D0A06;
    border: 1px solid var(--gold-dim);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    min-height: 160px;
  }
  .diagram-box svg {
    width: 100%;
    max-width: 180px;
    height: auto;
    filter: drop-shadow(0 0 8px rgba(201,168,76,0.4));
  }

  /* ── MAIN REVEAL ── */
  .reveal-section {
    max-width: 700px;
    margin: 2px auto 0;
    padding: 0 16px;
    position: relative;
    z-index: 1;
  }
  .reveal-box {
    background: linear-gradient(180deg, #0D0A06 0%, #060406 100%);
    border: 1px solid var(--gold);
    box-shadow: 0 0 60px rgba(201,168,76,0.08), inset 0 0 40px rgba(201,168,76,0.03);
    padding: 32px 24px;
    position: relative;
    overflow: hidden;
  }
  .reveal-box::after {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold-bright), transparent);
  }
  .reveal-title {
    font-family: 'Cinzel', serif;
    font-size: clamp(16px, 4vw, 22px);
    font-weight: 700;
    color: var(--gold-bright);
    text-align: center;
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 28px;
  }

  /* ── OCTAHEDRON SVG ── */
  #octa-svg {
    display: block;
    margin: 0 auto 28px;
    width: 100%;
    max-width: 360px;
  }

  /* ── STATS ROW ── */
  .stats {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2px;
    margin-top: 24px;
  }
  .stat {
    background: #0A0806;
    border: 1px solid var(--gold-dim);
    padding: 16px 12px;
    text-align: center;
  }
  .stat-val {
    font-family: 'Cinzel', serif;
    font-size: clamp(18px, 4vw, 28px);
    font-weight: 900;
    color: var(--gold-bright);
    display: block;
    line-height: 1.1;
  }
  .stat-label {
    font-size: 10px;
    letter-spacing: 2px;
    color: var(--gold-dim);
    text-transform: uppercase;
    margin-top: 6px;
    display: block;
  }

  /* ── PULSE RING on apex ── */
  .pulse { animation: pulseRing 2.4s ease-out infinite; }
  @keyframes pulseRing {
    0%   { opacity: 0.8; r: 4; }
    100% { opacity: 0;   r: 22; }
  }

  /* ── SCAN LINE ── */
  .scan { animation: scanMove 4s linear infinite; }
  @keyframes scanMove {
    0%   { transform: translateY(-160px); opacity: 0; }
    20%  { opacity: 0.6; }
    80%  { opacity: 0.6; }
    100% { transform: translateY(160px); opacity: 0; }
  }

  /* ── FOOTER ── */
  .footer {
    text-align: center;
    padding: 48px 20px;
    position: relative;
    z-index: 1;
    font-size: 10px;
    letter-spacing: 3px;
    color: var(--gold-dim);
    text-transform: uppercase;
  }
  .footer-line {
    width: 80px;
    height: 1px;
    background: var(--gold-dim);
    margin: 0 auto 16px;
  }

  /* ── GLOW FLOAT ANIMATION ── */
  @keyframes floatGlow {
    0%, 100% { filter: drop-shadow(0 0 6px rgba(201,168,76,0.5)); }
    50%       { filter: drop-shadow(0 0 20px rgba(255,215,112,0.9)); }
  }
  .float-glow { animation: floatGlow 3s ease-in-out infinite; }

  /* ── DASHED GROUND LINE anim ── */
  @keyframes dashMove {
    to { stroke-dashoffset: -20; }
  }
  .dash-anim { animation: dashMove 1s linear infinite; }
</style>
</head>
<body>

<canvas id="stars"></canvas>

<!-- HERO -->
<div class="hero">
  <p class="hero-eyebrow">Classified Geometry · Giza Plateau · 2560 BCE</p>
  <h1 class="hero-title">THE HIDDEN<br>FORM</h1>
  <p class="hero-sub">What lies beneath the desert</p>
</div>

<p class="section-label">§ The Theoretical Framework</p>

<!-- STEP CARDS -->
<div class="steps">
  <div class="step-card">
    <div class="step-num">I</div>
    <div class="step-title">The Hypercube</div>
    <p class="step-body">A vast, tilted mathematical hypercube is proposed as the originating form — existing in four-dimensional space before its projection onto three.</p>
  </div>
  <div class="step-card">
    <div class="step-num">II</div>
    <div class="step-title">Ground Plane</div>
    <p class="step-body">A horizontal plane — the desert floor — intersects the hypercube, slicing away its lower extremity and revealing only the emergent geometry above.</p>
  </div>
  <div class="step-card">
    <div class="step-num">III</div>
    <div class="step-title">Intersection</div>
    <p class="step-body">Where ground meets cube, pyramidal forms emerge. The visible structure is merely the cross-section of something far larger and stranger.</p>
  </div>
  <div class="step-card">
    <div class="step-num">IV</div>
    <div class="step-title">The Hidden Half</div>
    <p class="step-body">The inverted mirror — an equal pyramid descending 660 meters below ground — forms the lower lobe of a perfect octahedron buried in silence.</p>
  </div>
</div>

<p class="section-label">§ Geometric Derivation</p>

<!-- DIAGRAMS -->
<div class="diagrams">
  <div class="diagram-row">
    <!-- Hypercube wireframe -->
    <div class="diagram-box">
      <svg viewBox="0 0 180 160" fill="none" xmlns="http://www.w3.org/2000/svg">
        <title>Wireframe hypercube projection</title>
        <!-- outer cube -->
        <polygon points="90,10 160,50 160,120 90,150 20,120 20,50" stroke="#C9A84C" stroke-width="1" fill="none" opacity="0.5"/>
        <!-- inner cube -->
        <polygon points="90,40 130,62 130,108 90,128 50,108 50,62" stroke="#C9A84C" stroke-width="1" fill="none" opacity="0.8"/>
        <!-- connectors -->
        <line x1="90" y1="10" x2="90" y2="40" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <line x1="160" y1="50" x2="130" y2="62" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <line x1="160" y1="120" x2="130" y2="108" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <line x1="90" y1="150" x2="90" y2="128" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <line x1="20" y1="120" x2="50" y2="108" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <line x1="20" y1="50" x2="50" y2="62" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
        <!-- center dot -->
        <circle cx="90" cy="84" r="3" fill="#FFD770" opacity="0.9"/>
        <circle cx="90" cy="84" r="3" fill="#FFD770" class="pulse"/>
        <text x="90" y="155" text-anchor="middle" font-family="Rajdhani" font-size="9" fill="#7A6030" letter-spacing="2">HYPERCUBE</text>
      </svg>
    </div>
    <!-- Ground plane intersection -->
    <div class="diagram-box">
      <svg viewBox="0 0 180 160" fill="none" xmlns="http://www.w3.org/2000/svg">
        <title>Ground plane slicing the cube</title>
        <!-- above ground: pyramid -->
        <polygon points="90,15 155,95 25,95" stroke="#FFD770" stroke-width="1.5" fill="rgba(201,168,76,0.08)"/>
        <!-- ground line animated -->
        <line x1="10" y1="95" x2="170" y2="95" stroke="#C9A84C" stroke-width="2" stroke-dasharray="6 3" class="dash-anim"/>
        <!-- below ground: ghost inverted pyramid -->
        <polygon points="90,145 155,95 25,95" stroke="#C9A84C" stroke-width="1" fill="none" stroke-dasharray="4 4" opacity="0.35"/>
        <!-- scan line -->
        <rect x="25" y="0" width="130" height="2" fill="url(#scanGrad)" class="scan" opacity="0.5"/>
        <defs>
          <linearGradient id="scanGrad" x1="0" y1="0" x2="1" y2="0">
            <stop offset="0%" stop-color="transparent"/>
            <stop offset="50%" stop-color="#FFD770"/>
            <stop offset="100%" stop-color="transparent"/>
          </linearGradient>
        </defs>
        <text x="90" y="155" text-anchor="middle" font-family="Rajdhani" font-size="9" fill="#7A6030" letter-spacing="2">INTERSECTION</text>
      </svg>
    </div>
  </div>
</div>

<p class="section-label">§ The Unveiled Geometry</p>

<!-- MAIN REVEAL -->
<div class="reveal-section">
  <div class="reveal-box">
    <div class="reveal-title">The Complete Form</div>

    <!-- OCTAHEDRON SVG -->
    <svg id="octa-svg" viewBox="0 0 360 520" fill="none" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="skyGrad" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#0D0B10"/>
          <stop offset="100%" stop-color="#1A1408"/>
        </linearGradient>
        <linearGradient id="groundGrad" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#1A1408"/>
          <stop offset="100%" stop-color="#090706"/>
        </linearGradient>
        <linearGradient id="faceLeft" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0%" stop-color="#C9A84C" stop-opacity="0.25"/>
          <stop offset="100%" stop-color="#C9A84C" stop-opacity="0.04"/>
        </linearGradient>
        <linearGradient id="faceRight" x1="1" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#C9A84C" stop-opacity="0.12"/>
          <stop offset="100%" stop-color="#C9A84C" stop-opacity="0.02"/>
        </linearGradient>
        <linearGradient id="faceLeftLow" x1="0" y1="0" x2="1" y2="1">
          <stop offset="0%" stop-color="#7A6030" stop-opacity="0.15"/>
          <stop offset="100%" stop-color="#7A6030" stop-opacity="0.03"/>
        </linearGradient>
        <linearGradient id="faceRightLow" x1="1" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#7A6030" stop-opacity="0.08"/>
          <stop offset="100%" stop-color="#7A6030" stop-opacity="0.02"/>
        </linearGradient>
        <filter id="goldGlow">
          <feGaussianBlur stdDeviation="3" result="blur"/>
          <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
      </defs>

      <!-- SKY BG -->
      <rect x="0" y="0" width="360" height="240" fill="url(#skyGrad)"/>
      <!-- GROUND BG -->
      <rect x="0" y="240" width="360" height="280" fill="url(#groundGrad)"/>

      <!-- Ground line -->
      <line x1="0" y1="240" x2="360" y2="240" stroke="#C9A84C" stroke-width="1.5" stroke-dasharray="8 4" class="dash-anim"/>
      <text x="10" y="237" font-family="Rajdhani" font-size="10" fill="#C9A84C" letter-spacing="2" opacity="0.7">GROUND LEVEL</text>

      <!-- ── UPPER PYRAMID (above ground) ── -->
      <!-- left face -->
      <polygon points="180,20 60,240 180,240" fill="url(#faceLeft)" stroke="#C9A84C" stroke-width="1.5"/>
      <!-- right face -->
      <polygon points="180,20 300,240 180,240" fill="url(#faceRight)" stroke="#C9A84C" stroke-width="1.5"/>
      <!-- base midline -->
      <line x1="60" y1="240" x2="300" y2="240" stroke="#FFD770" stroke-width="1"/>
      <!-- apex dot + pulse -->
      <circle cx="180" cy="20" r="4" fill="#FFD770" filter="url(#goldGlow)"/>
      <circle cx="180" cy="20" r="4" fill="#FFD770" class="pulse"/>

      <!-- ── LOWER INVERTED PYRAMID (below ground) ── -->
      <!-- left face -->
      <polygon points="180,460 60,240 180,240" fill="url(#faceLeftLow)" stroke="#7A6030" stroke-width="1.2" stroke-dasharray="5 3"/>
      <!-- right face -->
      <polygon points="180,460 300,240 180,240" fill="url(#faceRightLow)" stroke="#7A6030" stroke-width="1.2" stroke-dasharray="5 3"/>
      <!-- nadir dot -->
      <circle cx="180" cy="460" r="3" fill="#C9A84C" opacity="0.6"/>
      <circle cx="180" cy="460" r="3" fill="#C9A84C" class="pulse" style="animation-delay:1.2s"/>

      <!-- Centerline vertical -->
      <line x1="180" y1="20" x2="180" y2="460" stroke="#C9A84C" stroke-width="0.6" stroke-dasharray="4 6" opacity="0.4"/>

      <!-- ── DIMENSION ANNOTATIONS ── -->
      <!-- Exposed height arrow -->
      <line x1="318" y1="20" x2="318" y2="240" stroke="#FFD770" stroke-width="1"/>
      <line x1="310" y1="20" x2="326" y2="20" stroke="#FFD770" stroke-width="1"/>
      <line x1="310" y1="240" x2="326" y2="240" stroke="#FFD770" stroke-width="1"/>
      <text x="328" y="100" font-family="Cinzel" font-size="13" fill="#FFD770" font-weight="700">~146.6 m</text>
      <text x="328" y="116" font-family="Rajdhani" font-size="9" fill="#7A6030" letter-spacing="2">EXPOSED</text>

      <!-- Buried height arrow -->
      <line x1="318" y1="240" x2="318" y2="460" stroke="#C9A84C" stroke-width="1" stroke-dasharray="3 3"/>
      <line x1="310" y1="460" x2="326" y2="460" stroke="#C9A84C" stroke-width="1"/>
      <text x="328" y="355" font-family="Cinzel" font-size="13" fill="#C9A84C" font-weight="700">~660.4 m</text>
      <text x="328" y="371" font-family="Rajdhani" font-size="9" fill="#7A6030" letter-spacing="2">BURIED</text>

      <!-- Horizontal span arrow -->
      <line x1="60" y1="490" x2="300" y2="490" stroke="#C9A84C" stroke-width="1"/>
      <line x1="60" y1="482" x2="60" y2="498" stroke="#C9A84C" stroke-width="1"/>
      <line x1="300" y1="482" x2="300" y2="498" stroke="#C9A84C" stroke-width="1"/>
      <text x="180" y="486" text-anchor="middle" font-family="Cinzel" font-size="13" fill="#C9A84C" font-weight="700">~807 m</text>
      <text x="180" y="508" text-anchor="middle" font-family="Rajdhani" font-size="9" fill="#7A6030" letter-spacing="3">VERTEX TO VERTEX</text>

      <!-- Interior chambers (upper pyramid) -->
      <!-- King's Chamber -->
      <rect x="155" y="145" width="22" height="14" rx="1" fill="none" stroke="#FFD770" stroke-width="0.8" opacity="0.6"/>
      <text x="150" y="142" font-family="Rajdhani" font-size="8" fill="#C9A84C" text-anchor="middle" letter-spacing="1">KING'S</text>
      <text x="150" y="152" font-family="Rajdhani" font-size="8" fill="#C9A84C" text-anchor="middle" letter-spacing="1">CHAMBER</text>
      <!-- Queen's Chamber -->
      <rect x="162" y="190" width="18" height="12" rx="1" fill="none" stroke="#C9A84C" stroke-width="0.8" opacity="0.5"/>
      <text x="180" y="215" font-family="Rajdhani" font-size="8" fill="#7A6030" text-anchor="middle" letter-spacing="1">QUEEN'S CHAMBER</text>
      <!-- Grand gallery -->
      <line x1="177" y1="159" x2="214" y2="148" stroke="#FFD770" stroke-width="1" opacity="0.5"/>
      <text x="220" y="145" font-family="Rajdhani" font-size="8" fill="#C9A84C" letter-spacing="1">GRAND</text>
      <text x="220" y="155" font-family="Rajdhani" font-size="8" fill="#C9A84C" letter-spacing="1">GALLERY</text>
    </svg>

    <!-- STATS -->
    <div class="stats">
      <div class="stat">
        <span class="stat-val">146.6<span style="font-size:0.5em">m</span></span>
        <span class="stat-label">Visible Height</span>
      </div>
      <div class="stat">
        <span class="stat-val">660.4<span style="font-size:0.5em">m</span></span>
        <span class="stat-label">Buried Depth</span>
      </div>
      <div class="stat">
        <span class="stat-val">807<span style="font-size:0.5em">m</span></span>
        <span class="stat-label">Full Span</span>
      </div>
    </div>
  </div>
</div>

<!-- FOOTER -->
<div class="footer">
  <div class="footer-line"></div>
  Speculative Geometry · Not Peer Reviewed · Made for Wonder
</div>

<script>
// ── STARFIELD ──
const canvas = document.getElementById('stars');
const ctx = canvas.getContext('2d');
let stars = [];

function resize() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}

function initStars() {
  stars = [];
  for (let i = 0; i < 280; i++) {
    stars.push({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      r: Math.random() * 1.2,
      a: Math.random(),
      speed: 0.003 + Math.random() * 0.008
    });
  }
}

function drawStars(t) {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  stars.forEach(s => {
    const alpha = 0.3 + 0.7 * Math.abs(Math.sin(t * s.speed + s.x));
    ctx.beginPath();
    ctx.arc(s.x, s.y, s.r, 0, Math.PI * 2);
    ctx.fillStyle = `rgba(201,168,76,${alpha * s.a})`;
    ctx.fill();
  });
}

let t = 0;
function loop() {
  t += 0.016;
  drawStars(t);
  requestAnimationFrame(loop);
}

resize();
initStars();
loop();
window.addEventListener('resize', () => { resize(); initStars(); });

// ── CARD HOVER SOUND (optional visual only) ──
document.querySelectorAll('.step-card').forEach(card => {
  card.addEventListener('mouseenter', () => {
    card.style.transform = 'translateY(-2px)';
    card.style.transition = 'transform 0.2s ease';
  });
  card.addEventListener('mouseleave', () => {
    card.style.transform = '';
  });
});
</script>
</body>
</html>
