<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#07070f">
<title>Happy Diwali</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600&family=Hind:wght@400&display=swap" rel="stylesheet">
<style>
:root {
  --gold: #f6c453;
  --cream: #fff4dc;
  --top: #07070f;
  --bot: #0d0d1c;
  --a: 0;
  box-sizing: border-box;
  color-scheme: dark;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
html, body {
  height: 100%;
  width: 100%;
  background: #07070f;
  color: var(--cream);
  font-family: 'Hind', system-ui, -apple-system, sans-serif;
  overflow: hidden;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}
.stage {
  position: relative;
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  text-align: center;
  padding: 20px 20px 40px;
  background: radial-gradient(ellipse at 50% 78%, rgba(255,176,46,var(--a)) 0%, rgba(255,176,46,0) 70%), linear-gradient(var(--top), var(--bot));
  transition: background 0.5s ease;
  z-index: 1;
}
header, .msg, section { position: relative; z-index: 2; }
h1 {
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-weight: 600;
  font-size: clamp(2.4rem, 10vw, 4.2rem);
  color: var(--gold);
  line-height: 1.1;
  margin-top: 10px;
}
.hint { font-size: 1rem; opacity: 0.85; margin-top: 8px; }
.msg {
  max-width: 22em;
  font-family: 'Cormorant Garamond', Georgia, serif;
  font-size: clamp(1.3rem, 5vw, 1.8rem);
  line-height: 1.4;
  min-height: 4.5em;
  opacity: 0;
  transform: translateY(10px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.msg.on { opacity: 1; transform: translateY(0); }
.row {
  display: flex;
  gap: clamp(10px, 3.5vw, 22px);
  align-items: flex-end;
  justify-content: center;
  margin-bottom: 20px;
}
button {
  font: inherit;
  appearance: none;
  -webkit-appearance: none;
  border: 0;
  background: none;
  cursor: pointer;
  touch-action: manipulation;
}
button:focus-visible { outline: 2px solid var(--gold); border-radius: 8px; }
.diya { padding: 6px; }
.diya svg { width: clamp(52px, 15vw, 76px); height: auto; display: block; overflow: visible; }
.flame {
  opacity: 0;
  transform-origin: 50% 100%;
  transform: scale(0.3);
  transition: opacity 0.4s ease, transform 0.4s ease;
}
.lit .flame {
  opacity: 1;
  transform: scale(1);
  animation: flick 1.5s ease-in-out infinite alternate;
}
.halo { opacity: 0; transition: opacity 0.6s ease; }
.lit .halo { opacity: 0.6; }

@keyframes flick {
  0% { transform: scale(1) rotate(-2deg); }
  50% { transform: scale(1.08, 0.94) rotate(2deg); }
  100% { transform: scale(0.96, 1.05) rotate(-1deg); }
}

.btns {
  display: flex;
  gap: 10px;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
.pill {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: rgba(255, 255, 255, 0.05);
  color: var(--gold);
  border: 1px solid var(--gold);
  border-radius: 999px;
  padding: 8px 16px;
  font-size: 0.95rem;
  transition: background 0.2s, transform 0.1s;
}
.pill:active { transform: scale(0.95); background: rgba(246, 196, 83, 0.15); }
#share { opacity: 0; pointer-events: none; transition: opacity 0.5s; }
#share.on { opacity: 1; pointer-events: auto; }

/* Lantern */
button.kandil {
  position: relative;
  z-index: 2;
  height: clamp(120px, 20vh, 190px);
  transform-origin: 50% 0;
  animation: sway 4.5s ease-in-out infinite alternate;
}
.kandil svg { height: 100%; width: auto; display: block; overflow: visible; }
.kandil .body { fill: #2b1d2f; stroke: #7a5a30; stroke-width: 1.5; stroke-linejoin: round; }
.kandil .ribs { stroke: #7a5a30; stroke-width: 1; opacity: 0.55; }
.kandil .tail { fill: #3a2a38; stroke: #7a5a30; stroke-width: 1; }
.kandil .cap { fill: #b8862b; }
.kandil .strand { stroke: #e0a33a; stroke-width: 1.4; stroke-linecap: round; }
.kandil .bead { fill: #e0a33a; }
.kandil .bulb { fill: #fff4dc; opacity: 0; transform-origin: center; transition: opacity 0.5s; }
.kandil .kglow { opacity: 0; transition: opacity 0.6s; pointer-events: none; }
.kandil .litbody { opacity: 0; transition: opacity 0.5s; }
.kandil.lit .litbody { opacity: 1; }
.kandil.lit .tail { fill: #e0793a; }
.kandil.lit .ribs { stroke: #fff4dc; opacity: 0.5; }
.kandil.lit .bulb { opacity: 1; animation: pulse 2s ease-in-out infinite alternate; }
.kandil.lit .kglow { opacity: 0.85; }
.kandil.lit svg { filter: drop-shadow(0 0 16px rgba(255,160,40,0.7)); }

@keyframes sway {
  0% { transform: rotate(-3deg); }
  100% { transform: rotate(3deg); }
}
@keyframes pulse {
  0% { transform: scale(0.92); opacity: 0.85; }
  100% { transform: scale(1.1); opacity: 1; }
}

canvas#fx {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  pointer-events: none !important;
  z-index: 10;
}
</style>
</head>
<body>
<main class="stage" id="stage">
  <button class="kandil" id="kandil" type="button" aria-label="Kandil Lantern">
    <svg viewBox="0 0 120 225" aria-hidden="true">
      <defs>
        <radialGradient id="kg" cx="50%" cy="42%" r="60%">
          <stop offset="0" stop-color="#fff4dc"/>
          <stop offset=".35" stop-color="#ffd27a"/>
          <stop offset=".7" stop-color="#ff9b2e"/>
          <stop offset="1" stop-color="#e0602a"/>
        </radialGradient>
        <radialGradient id="kh" cx="50%" cy="50%" r="50%">
          <stop offset="0" stop-color="#ffb02e" stop-opacity=".9"/>
          <stop offset="1" stop-color="#ffb02e" stop-opacity="0"/>
        </radialGradient>
      </defs>
      <circle class="kglow" cx="60" cy="95" r="78" fill="url(#kh)"/>
      <line x1="60" y1="0" x2="60" y2="34" stroke="#b8862b" stroke-width="1.5"/>
      <path class="cap" d="M52 40 L60 28 L68 40 L64 46 L56 46 Z"/>
      <path class="tail" d="M52 145 L68 145 L60 186 Z"/>
      <polygon class="body" points="60,43 69.95,70.98 96.77,58.23 84.02,85.05 112,95 84.02,104.95 96.77,131.77 69.95,119.02 60,147 50.05,119.02 23.23,131.77 35.98,104.95 8,95 35.98,85.05 23.23,58.23 50.05,70.98"/>
      <polygon class="litbody" fill="url(#kg)" stroke="#7a5a30" stroke-width="1.5" stroke-linejoin="round" points="60,43 69.95,70.98 96.77,58.23 84.02,85.05 112,95 84.02,104.95 96.77,131.77 69.95,119.02 60,147 50.05,119.02 23.23,131.77 35.98,104.95 8,95 35.98,85.05 23.23,58.23 50.05,70.98"/>
      <g class="ribs" fill="none">
        <line x1="60" y1="43" x2="60" y2="147"/>
        <line x1="8" y1="95" x2="112" y2="95"/>
        <line x1="23.23" y1="58.23" x2="96.77" y2="131.77"/>
        <line x1="96.77" y1="58.23" x2="23.23" y2="131.77"/>
      </g>
      <circle class="bulb" cx="60" cy="95" r="13"/>
      <circle class="bead" cx="60" cy="190" r="3.5"/>
      <line class="strand" x1="60" y1="193" x2="60" y2="222"/>
      <line class="strand" x1="60" y1="193" x2="50" y2="218"/>
      <line class="strand" x1="60" y1="193" x2="70" y2="218"/>
      <line class="strand" x1="60" y1="193" x2="42" y2="212"/>
      <line class="strand" x1="60" y1="193" x2="78" y2="212"/>
    </svg>
  </button>

  <header>
    <h1>Happy Diwali</h1>
    <p class="hint" id="hint">It’s dark. Tap a diya or the kandil to bring light.</p>
  </header>

  <p class="msg" id="msg" aria-live="polite"></p>

  <section>
    <div class="row" id="row" role="group" aria-label="Diyas"></div>
    <div class="btns">
      <button class="pill" type="button" data-fx="anar">🌸 Anar</button>
      <button class="pill" type="button" data-fx="chakri">🌀 Chakri</button>
      <button class="pill" type="button" data-fx="sky">🎆 Sky shots</button>
      <button class="pill" id="share" type="button">Share</button>
    </div>
  </section>
</main>
<canvas id="fx"></canvas>

<script>
window.addEventListener('DOMContentLoaded', function() {
  var MSGS = [
    'May every diya you light bring you brightness and good fortune.',
    'May your home glow with warmth, laughter and love.',
    'May light win over every dark corner of your year.',
    'May good health and sweet moments follow you all year.',
    'Shubh Deepavali! May joy shine on you and your family.'
  ];
  var N = MSGS.length;
  var row = document.getElementById('row');
  var msg = document.getElementById('msg');
  var hint = document.getElementById('hint');
  var share = document.getElementById('share');
  var stage = document.getElementById('stage');
  var kandil = document.getElementById('kandil');
  var lit = 0, kon = 0, timer;

  var diyaSvg = '<svg viewBox="0 0 100 90" aria-hidden="true">' +
    '<circle class="halo" cx="50" cy="38" r="40" fill="#ffb02e"/>' +
    '<path class="flame" d="M50 6C60 20 66 28 62 38C60 44 55 46 50 46C45 46 40 44 38 38C34 28 44 22 50 6Z" fill="#ffb02e"/>' +
    '<path class="flame" d="M50 22C55 30 57 34 55 39C54 42 52 43 50 43C48 43 46 42 45 39C43 34 47 30 50 22Z" fill="#fff4dc"/>' +
    '<path d="M8 50H92C92 74 74 86 50 86C26 86 8 74 8 50Z" fill="#c8622b"/>' +
    '<path d="M8 50H92C91 54 88 57 84 59H16C12 57 9 54 8 50Z" fill="#e0793a"/>' +
    '<rect x="47" y="44" width="6" height="8" rx="2" fill="#3a1d10"/></svg>';

  for (var i = 0; i < N; i++) {
    (function(index) {
      var b = document.createElement('button');
      b.className = 'diya';
      b.type = 'button';
      b.setAttribute('aria-label', 'Diya ' + (index + 1));
      b.style.marginBottom = (index % 2 ? '14px' : '0');
      b.innerHTML = diyaSvg;
      b.addEventListener('click', function() { tap(b, index); });
      row.appendChild(b);
    })(i);
  }

  function lerp(a, b, t) { return Math.round(a + (b - a) * t); }
  function mix(c1, c2, t) { return 'rgb(' + lerp(c1[0], c2[0], t) + ',' + lerp(c1[1], c2[1], t) + ',' + lerp(c1[2], c2[2], t) + ')'; }

  function bright() {
    var t = Math.min(1, (lit + kon * 0.8) / (N + 0.8));
    stage.style.setProperty('--top', mix([7, 7, 15], [52, 44, 122], t));
    stage.style.setProperty('--bot', mix([13, 13, 28], [170, 84, 34], t));
    stage.style.setProperty('--a', (t * 0.55).toFixed(2));
  }

  function show(text) {
    msg.classList.remove('on');
    clearTimeout(timer);
    timer = setTimeout(function() {
      msg.textContent = text;
      msg.classList.add('on');
    }, 120);
  }

  function hintText() {
    if (lit === 0 && !kon) return 'It’s dark. Tap a diya or the kandil to bring light.';
    if (lit === N && kon) return 'The whole night is glowing. Happy Diwali!';
    if (lit === N) return 'All diyas are lit. Tap the kandil to light it too.';
    if (lit === 0) return 'The kandil is glowing. Tap a diya to light it too.';
    return (N - lit) + (N - lit === 1 ? ' diya' : ' diyas') + ' left. Tap a lit diya to blow it out.';
  }

  function tap(b, idx) {
    initAudio();
    if (b.classList.contains('lit')) {
      b.classList.remove('lit');
      lit--;
      bright();
      hint.textContent = hintText();
      if (lit === 0) {
        clearTimeout(timer);
        msg.classList.remove('on');
        if (!kon) share.classList.remove('on');
      }
    } else {
      b.classList.add('lit');
      lit++;
      bright();
      burst(b, 16, true);
      hint.textContent = hintText();
      share.classList.add('on');
      show(MSGS[idx]);
    }
  }

  kandil.addEventListener('click', function() {
    initAudio();
    if (kon) {
      kon = 0;
      kandil.classList.remove('lit');
      if (lit === 0) share.classList.remove('on');
    } else {
      kon = 1;
      kandil.classList.add('lit');
      var r = kandil.getBoundingClientRect();
      burst(null, 20, true, r.left + r.width / 2, r.top + r.height * 0.45);
      share.classList.add('on');
    }
    bright();
    hint.textContent = hintText();
  });

  share.addEventListener('click', function() {
    if (navigator.share) {
      navigator.share({ title: 'Happy Diwali', text: 'Happy Diwali! Light a diya with me:', url: location.href }).catch(function(){});
    } else if (navigator.clipboard) {
      navigator.clipboard.writeText(location.href);
      share.textContent = 'Link copied!';
      setTimeout(function() { share.textContent = 'Share'; }, 2000);
    }
  });

  /* Particle & Firework Engine */
  var cv = document.getElementById('fx');
  var ctx = cv.getContext('2d');
  var P = [], E = [], R = [];
  var running = false;
  var dpr = Math.min(window.devicePixelRatio || 1, 2);

  function resizeCanvas() {
    cv.width = window.innerWidth * dpr;
    cv.height = window.innerHeight * dpr;
  }
  resizeCanvas();
  window.addEventListener('resize', resizeCanvas);

  var COLS = ['#f6c453', '#ffb02e', '#ff5d73', '#5ee0ff', '#b388ff', '#fff4dc', '#7dff9b'];

  function burst(el, count, small, px, py) {
    var x, y;
    if (px !== undefined) {
      x = px; y = py;
    } else if (el) {
      var r = el.getBoundingClientRect();
      x = r.left + r.width / 2;
      y = r.top + r.height * 0.3;
    } else {
      x = window.innerWidth * (0.2 + Math.random() * 0.6);
      y = window.innerHeight * (0.15 + Math.random() * 0.35);
    }
    var c1 = COLS[Math.floor(Math.random() * COLS.length)];
    var c2 = COLS[Math.floor(Math.random() * COLS.length)];
    for (var k = 0; k < count; k++) {
      var a = Math.PI * 2 * k / count + Math.random() * 0.2;
      var s = (small ? 1.5 : 3) + Math.random() * (small ? 2.5 : 5);
      P.push({
        x: x, y: y,
        vx: Math.cos(a) * s,
        vy: Math.sin(a) * s,
        l: 1,
        d: 0.015 + Math.random() * 0.015,
        c: k % 2 ? c1 : c2,
        r: small ? 2 : 2.8
      });
    }
    startLoop();
  }

  function startLoop() {
    if (!running) {
      running = true;
      requestAnimationFrame(renderLoop);
    }
  }

  function groundY() {
    return row.getBoundingClientRect().bottom - 8;
  }

  function launchRocket(big, delay) {
    setTimeout(function() {
      whistleSound();
      R.push({
        x: window.innerWidth * (0.15 + Math.random() * 0.7),
        y: groundY(),
        vy: -11,
        top: window.innerHeight * (0.12 + Math.random() * 0.28),
        big: big
      });
      startLoop();
    }, delay);
  }

  function renderLoop() {
    ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
    ctx.clearRect(0, 0, window.innerWidth, window.innerHeight);

    // Emitters (Anar / Chakri)
    for (var i = E.length - 1; i >= 0; i--) {
      var e = E[i];
      e.t++;
      if (e.t > e.life) { E.splice(i, 1); continue; }

      if (e.type === 'anar') {
        for (var k = 0; k < 7; k++) {
          var a = -Math.PI / 2 + (Math.random() - 0.5) * 0.8;
          var s = 4.5 + Math.random() * 4;
          P.push({
            x: e.x, y: e.y,
            vx: Math.cos(a) * s,
            vy: Math.sin(a) * s,
            l: 1,
            d: 0.02 + Math.random() * 0.02,
            c: ['#ffe9a0', '#f6c453', '#ffb02e', '#fff4dc'][k % 4],
            r: 2.5
          });
        }
      } else if (e.type === 'chakri') {
        e.a += 0.45;
        e.x += e.dx;
        for (var j = 0; j < 3; j++) {
          var angle = e.a + j * 2.09;
          var speed = 3.5 + Math.random() * 3;
          P.push({
            x: e.x + Math.cos(e.a) * 12,
            y: e.y + Math.sin(e.a) * 12,
            vx: Math.cos(angle) * speed,
            vy: Math.sin(angle) * speed * 0.6 - 1,
            l: 1,
            d: 0.04 + Math.random() * 0.02,
            c: j % 2 ? '#ffb02e' : '#fff4dc',
            r: 2.2
          });
        }
      }
    }

    // Rockets
    for (var rIdx = R.length - 1; rIdx >= 0; rIdx--) {
      var rk = R[rIdx];
      rk.y += rk.vy;
      P.push({
        x: rk.x + (Math.random() - 0.5) * 2,
        y: rk.y,
        vx: (Math.random() - 0.5) * 0.5,
        vy: 1 + Math.random(),
        l: 0.8,
        d: 0.06,
        c: '#ffb02e',
        r: 1.5
      });
      if (rk.y <= rk.top) {
        burst(null, rk.big ? 85 : 55, false, rk.x, rk.y);
        popSound();
        R.splice(rIdx, 1);
      }
    }

    // Sparks
    for (var pIdx = P.length - 1; pIdx >= 0; pIdx--) {
      var p = P[pIdx];
      p.x += p.vx;
      p.y += p.vy;
      p.vy += 0.07;
      p.vx *= 0.985;
      p.l -= p.d;
      if (p.l <= 0) { P.splice(pIdx, 1); continue; }

      ctx.globalAlpha = p.l;
      ctx.fillStyle = p.c;
      ctx.beginPath();
      ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
      ctx.fill();
    }
    ctx.globalAlpha = 1;

    if (P.length > 0 || E.length > 0 || R.length > 0) {
      requestAnimationFrame(renderLoop);
    } else {
      running = false;
    }
  }

  // Audio Context handling
  var audioCtx = null;
  function initAudio() {
    try {
      if (!audioCtx) {
        var AudioClass = window.AudioContext || window.webkitAudioContext;
        if (AudioClass) audioCtx = new AudioClass();
      }
      if (audioCtx && audioCtx.state === 'suspended') {
        audioCtx.resume();
      }
    } catch (e) {}
  }

  function popSound() {
    try {
      if (!audioCtx) return;
      var len = Math.floor(audioCtx.sampleRate * 0.25);
      var buf = audioCtx.createBuffer(1, len, audioCtx.sampleRate);
      var d = buf.getChannelData(0);
      for (var i = 0; i < len; i++) d[i] = (Math.random() * 2 - 1) * Math.pow(1 - i / len, 4);
      var s = audioCtx.createBufferSource();
      var g = audioCtx.createGain();
      g.gain.value = 0.4;
      s.buffer = buf;
      s.connect(g);
      g.connect(audioCtx.destination);
      s.start(0);
    } catch (e) {}
  }

  function hissSound(sec) {
    try {
      if (!audioCtx) return;
      var len = Math.floor(audioCtx.sampleRate * sec);
      var b = audioCtx.createBuffer(1, len, audioCtx.sampleRate);
      var a = b.getChannelData(0);
      for (var i = 0; i < len; i++) a[i] = (Math.random() * 2 - 1) * 0.2 * (1 - i / len);
      var s = audioCtx.createBufferSource();
      var f = audioCtx.createBiquadFilter();
      f.type = 'highpass';
      f.frequency.value = 2800;
      s.buffer = b;
      s.connect(f);
      f.connect(audioCtx.destination);
      s.start(0);
    } catch (e) {}
  }

  function whistleSound() {
    try {
      if (!audioCtx) return;
      var o = audioCtx.createOscillator();
      var g = audioCtx.createGain();
      var t = audioCtx.currentTime;
      o.frequency.setValueAtTime(450, t);
      o.frequency.exponentialRampToValueAtTime(1700, t + 0.8);
      g.gain.setValueAtTime(0.05, t);
      g.gain.linearRampToValueAtTime(0, t + 0.8);
      o.connect(g);
      g.connect(audioCtx.destination);
      o.start(t);
      o.stop(t + 0.8);
    } catch (e) {}
  }

  // Button triggers
  var FX = {
    anar: function() {
      hissSound(2.2);
      E.push({ type: 'anar', x: window.innerWidth * (0.25 + Math.random() * 0.5), y: groundY(), t: 0, life: 160 });
      startLoop();
    },
    chakri: function() {
      hissSound(2.4);
      E.push({ type: 'chakri', x: window.innerWidth * (0.35 + Math.random() * 0.3), y: groundY(), t: 0, life: 170, a: 0, dx: (Math.random() - 0.5) * 1.5 });
      startLoop();
    },
    sky: function() {
      for (var i = 0; i < 5; i++) {
        launchRocket(true, i * 360);
      }
    }
  };

  document.querySelectorAll('[data-fx]').forEach(function(btn) {
    btn.addEventListener('click', function() {
      initAudio();
      var type = btn.getAttribute('data-fx');
      if (FX[type]) FX[type]();
    });
  });
});
</script>
</body>
</html>
