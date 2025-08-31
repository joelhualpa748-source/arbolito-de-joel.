<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Árbol de Amor Animado</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        width: 100vw;
        height: 100vh;
        overflow: hidden;
        background: #fcfcfc;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        font-family: 'Arial', sans-serif;
      }

      #heart-button {
        position: relative;
        background-color: transparent;
        border: none;
        width: 100px;
        height: 90px;
        cursor: pointer;
        outline: none;
        animation: pulse 1.5s infinite alternate;
        z-index: 10;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 0;
        font-size: 5rem;
        transition: transform 0.5s ease-out, opacity 0.5s ease-out;
      }

      #heart-button span {
        position: relative;
        transform: translateY(0.1em);
      }
      
      #heart-button.hidden-expand {
        transform: scale(2);
        opacity: 0;
      }

      @keyframes pulse {
        0% { transform: scale(1); }
        100% { transform: scale(1.1); }
      }

      .hidden {
        display: none !important;
      }

      .tree-container {
        width: 92vw !important;
        height: 62vw !important;
        max-width: 98vw;
        max-height: 80vw;
        min-width: 180px;
        min-height: 180px;
        position: absolute;
        top: 48%;
        left: 50%;
        transform: translate(-50%, -50%);
        z-index: 2;
      }

      .tree-container svg {
        width: 100%;
        height: 100%;
        display: block;
      }

      .tree-container svg.move-and-scale {
        transition: transform 1.2s cubic-bezier(.77,0,.18,1);
        transform: translateY(60px) scale(1.18);
      }

      .animated-heart {
        transform-origin: center;
        animation: beat 1s infinite;
      }

      @keyframes beat {
        0%, 100% { transform: scale(1); }
        20% { transform: scale(1.1); }
        40% { transform: scale(0.95); }
        60% { transform: scale(1.08); }
        80% { transform: scale(1); }
      }

      #fireworks-canvas {
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        display: block;
        z-index: 1;
        pointer-events: none;
      }

      #center-text {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        font-size: 5rem;
        color: #e60026;
        font-family: 'Arial Black', Arial, sans-serif;
        text-shadow: 2px 2px 8px #ffb3b3;
        z-index: 2;
        letter-spacing: 0.5rem;
        user-select: none;
        display: flex;
        gap: 0.5rem;
        pointer-events: none;
      }

      .letter {
        opacity: 0;
        transition: opacity 0.5s;
      }

      .tree-container svg path {
        transition: fill-opacity 0.5s, stroke-dashoffset 1.2s;
      }

      .dedication-text {
        position: absolute;
        top: 0vw;
        left:35%;
        transform: translateX(-50%) scale(0.5);
        max-width: 98vw;
        font-size: 1.05rem;
        text-align: center;
        color: #000000;
        font-family: 'Courier New', Courier, monospace;
        white-space: pre-line;
        z-index: 3;
        opacity: 0;
        pointer-events: none;
        transition: opacity 0.8s, transform 0.8s;
      }
      
      .dedication-text p {
          text-align: center;
          margin: 0;
          padding: 0;
      }

      .dedication-text.typing {
        opacity: 1;
        transform: translateX(-50%) scale(1);
      }

      @keyframes fadeInText {
        from { opacity: 0; }
        to { opacity: 1; }
      }

      #floating-objects {
        position: fixed;
        left: 0;
        top: 0;
        width: 100vw;
        height: 100vh;
        pointer-events: none;
        z-index: 10;
      }

      .floating-petal {
        position: absolute;
        will-change: transform, opacity;
        opacity: 0.85;
        pointer-events: none;
        width: 13px;
        height: 18px;
        background: radial-gradient(ellipse at 60% 30%, #ffd6e0 60%, #ff69b4 100%);
        border-radius: 60% 40% 60% 40% / 60% 60% 40% 40%;
      }

      .signature {
        position: static;
        display: block;
        margin: 2.2em auto 0 auto;
        left: auto;
        bottom: auto;
        transform: none;
        font-size: 1.25rem;
        color: #e60026;
        opacity: 0;
        z-index: 5;
        white-space: pre;
        pointer-events: none;
        transition: opacity 0.7s;
        text-align: center;
      }

      .signature.visible {
        opacity: 1;
        animation: signature-draw 2.2s steps(24) forwards;
      }

      @keyframes signature-draw {
        from { clip-path: inset(0 100% 0 0); }
        to   { clip-path: inset(0 0 0 0); }
      }

      .countdown {
        position: fixed;
        left: 50%;
        bottom: 10vw;
        transform: translateX(-50%);
        font-family: 'Courier New', Courier, monospace;
        font-size: 0.98rem;
        color: #333;
        background: #fff8;
        padding: 0.5em 0.7em;
        border-radius: 1em;
        z-index: 6;
        box-shadow: 0 2px 8px #e6002611;
        pointer-events: none;
        letter-spacing: 0.05em;
        min-width: 60vw;
        max-width: 92vw;
        text-align: center;
        transition: opacity 0.8s cubic-bezier(.77,0,.18,1), transform 0.8s cubic-bezier(.77,0,.18,1);
        opacity: 0;
        transform: translateX(-50%) translateY(30px);
      }

      .countdown.visible {
        opacity: 1;
        transform: translateX(-50%) translateY(0);
      }

      @media (max-width: 700px) {
        .signature {
          position: static;
          display: block;
          margin: 2.2em auto 0 auto;
          left: auto;
          bottom: auto;
          transform: none;
          font-size: 1.25rem;
          text-align: center;
        }
      }
    </style>
</head>
<body>
    <button id="heart-button"><span>❤️</span></button>
    <div id="floating-objects" class="hidden"></div>
    <div class="dedication-text hidden" id="dedication-text">
      <div class="signature" id="signature"></div>
    </div>
    <div class="countdown hidden" id="countdown"></div>
    <div class="tree-container hidden" id="tree-container"></div>
    <audio id="bg-music" preload="auto"></audio>
    <script>
      const heartButton = document.getElementById('heart-button');
      const floatingObjects = document.getElementById('floating-objects');
      const dedicationText = document.getElementById('dedication-text');
      const countdown = document.getElementById('countdown');
      const treeContainer = document.getElementById('tree-container');
      const audio = document.getElementById('bg-music');
      const musicSrc = 'https://github.com/jesuxzx/No-se/raw/4ae811281adbf86bd4673bbf251b975dc86619bb/music2.mp3';

      heartButton.addEventListener('click', () => {
        heartButton.classList.add('hidden-expand');
        floatingObjects.classList.remove('hidden');
        dedicationText.classList.remove('hidden');
        countdown.classList.remove('hidden');
        treeContainer.classList.remove('hidden');
        startAnimation();
        playBackgroundMusic();
      });

      function startAnimation() {
        fetch('https://raw.githubusercontent.com/jesuxzx/No-se/6b60d208327d199882f0068b7edba3f438251d13/treelove.svg')
          .then(res => res.text())
          .then(svgText => {
            const container = document.getElementById('tree-container');
            container.innerHTML = svgText;
            const svg = container.querySelector('svg');
            if (!svg) return;
            const allPaths = Array.from(svg.querySelectorAll('path'));
            allPaths.forEach(path => {
              path.style.stroke = '#222';
              path.style.strokeWidth = '2.5';
              path.style.fillOpacity = '0';
              const length = path.getTotalLength();
              path.style.strokeDasharray = length;
              path.style.strokeDashoffset = length;
              path.style.transition = 'none';
            });
            setTimeout(() => {
              allPaths.forEach((path, i) => {
                path.style.transition = `stroke-dashoffset 1.2s cubic-bezier(.77,0,.18,1) ${i * 0.08}s, fill-opacity 0.5s ${0.9 + i * 0.08}s`;
                path.style.strokeDashoffset = 0;
                setTimeout(() => {
                  path.style.fillOpacity = '1';
                  path.style.stroke = '';
                  path.style.strokeWidth = '';
                }, 1200 + i * 80);
              });
              const totalDuration = 1200 + (allPaths.length - 1) * 80 + 500;
              setTimeout(() => {
                svg.classList.add('move-and-scale');
                setTimeout(() => {
                  showDedicationText();
                  startFloatingObjects();
                  showCountdown();
                }, 1200);
              }, totalDuration);
            }, 50);
            const heartPaths = allPaths.filter(el => {
              const style = el.getAttribute('style') || '';
              return style.includes('#FC6F58') || style.includes('#C1321F');
            });
            heartPaths.forEach(path => {
              path.classList.add('animated-heart');
            });
          });
      }

      function getURLParam(name) {
        const url = new URL(window.location.href);
        return url.searchParams.get(name);
      }

      function showDedicationText() {
        let text = getURLParam('text');
        if (!text) {
          text = `Para el amor de mi vida:
Desde el primer momento supe que eras tú. Tu sonrisa, tu voz, tu forma de ser… todo en ti me hace sentir en casa.
Gracias por acompañarme en cada paso, por entenderme incluso en silencio, y por llenar mis días de amor.
Te amo más de lo que las palabras pueden expresar.`;
        } else {
          text = decodeURIComponent(text).replace(/\\n/g, '\n');
        }
        const container = document.getElementById('dedication-text');
        
        container.classList.add('typing');

        let i = 0;
        function type() {
          if (i <= text.length) {
            container.textContent = text.slice(0, i);
            i++;
            setTimeout(type, text.charAt(i - 2) === '\n' ? 350 : 45);
          } else {
            setTimeout(showSignature, 600);
          }
        }
        type();
      }

      function showSignature() {
        const dedication = document.getElementById('dedication-text');
        let signature = dedication.querySelector('#signature');
        if (!signature) {
          signature = document.createElement('div');
          signature.id = 'signature';
          signature.className = 'signature';
          dedication.appendChild(signature);
        }
        let firma = getURLParam('firma');
        signature.textContent = firma ? decodeURIComponent(firma) : "Con amor, Tu Joel";
        signature.classList.add('visible');
      }

      function startFloatingObjects() {
        const container = document.getElementById('floating-objects');
        let count = 0;
        function spawn() {
          let el = document.createElement('div');
          el.className = 'floating-petal';
          el.style.left = `${Math.random() * 90 + 2}%`;
          el.style.top = `${100 + Math.random() * 10}%`;
          el.style.opacity = 0.7 + Math.random() * 0.3;
          container.appendChild(el);
          const duration = 6000 + Math.random() * 4000;
          const drift = (Math.random() - 0.5) * 60;
          setTimeout(() => {
            el.style.transition = `transform ${duration}ms linear, opacity 1.2s`;
            el.style.transform = `translate(${drift}px, -110vh) scale(${0.8 + Math.random() * 0.6}) rotate(${Math.random() * 360}deg)`;
            el.style.opacity = 0.2;
          }, 30);
          setTimeout(() => {
            if (el.parentNode) el.parentNode.removeChild(el);
          }, duration + 2000);
          if (count++ < 32) setTimeout(spawn, 350 + Math.random() * 500);
          else setTimeout(spawn, 1200 + Math.random() * 1200);
        }
        spawn();
      }

     

      function playBackgroundMusic() {
        audio.src = musicSrc;
        audio.volume = 0.7;
        audio.loop = true;
        audio.play();
      }
    </script>
</body>
</html>
