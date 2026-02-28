<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
  <title>আমার পরি 🦋</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Bengali:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-gradient-1: #fff0f3;
      --bg-gradient-2: #ffc8dd;
      --text-dark: #4a2b33;
      --text-light: #6b4c55;
      --accent: #d84b6b;
      --accent-hover: #c23b59;
      --card-bg: rgba(255, 255, 255, 0.65);
      --glass-border: rgba(255, 255, 255, 0.8);
    }

    * { 
      margin: 0; 
      padding: 0; 
      box-sizing: border-box; 
      font-family: 'Noto Sans Bengali', sans-serif; 
      -webkit-tap-highlight-color: transparent; 
    }

    body {
      background: linear-gradient(135deg, var(--bg-gradient-1) 0%, var(--bg-gradient-2) 100%);
      color: var(--text-dark);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      transition: background 1.5s ease;
    }

    .container {
      position: relative;
      width: 100%;
      max-width: 420px;
      height: 100vh;
      max-height: 850px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 20px;
    }

    .page {
      position: absolute;
      top: 50%;
      left: 20px;
      right: 20px;
      transform: translateY(-50%) scale(0.95);
      background: var(--card-bg);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      border: 1px solid var(--glass-border);
      border-radius: 28px;
      padding: 35px 25px;
      opacity: 0;
      pointer-events: none;
      transition: all 0.6s cubic-bezier(0.25, 1, 0.5, 1);
      box-shadow: 0 15px 35px rgba(216, 75, 107, 0.15);
      text-align: center;
    }

    .page.active {
      opacity: 1;
      pointer-events: auto;
      transform: translateY(-50%) scale(1);
      z-index: 10;
    }

    .page.prev {
      transform: translateY(-60%) scale(0.95);
      opacity: 0;
    }

    h1 { font-size: 1.7rem; font-weight: 600; margin-bottom: 12px; color: var(--accent); }
    p { font-size: 1.15rem; line-height: 1.7; margin-bottom: 18px; color: var(--text-light); }
    .name-highlight { color: var(--accent); font-weight: 700; font-size: 1.25rem; }
    
    .time-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-size: 0.9rem;
      background: rgba(255, 255, 255, 0.8);
      color: var(--accent);
      padding: 6px 16px;
      border-radius: 30px;
      margin-bottom: 20px;
      font-weight: 600;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .btn {
      display: block;
      width: 100%;
      padding: 15px;
      border: none;
      border-radius: 16px;
      background: var(--accent);
      color: white;
      font-size: 1.15rem;
      font-weight: 600;
      cursor: pointer;
      margin-top: 15px;
      transition: transform 0.2s, box-shadow 0.3s;
      box-shadow: 0 6px 20px rgba(216, 75, 107, 0.3);
    }

    .btn:active { transform: scale(0.96); }
    .btn-outline { background: rgba(255,255,255,0.5); border: 2px solid var(--accent); color: var(--accent); box-shadow: none; }

    /* Interactive Reveal Text */
    .hidden-text-container { margin: 25px 0; text-align: left; }
    .hidden-text {
      padding: 14px 18px;
      background: rgba(255, 255, 255, 0.7);
      border-radius: 14px;
      margin-bottom: 12px;
      color: transparent;
      cursor: pointer;
      position: relative;
      transition: 0.4s ease;
      border: 1px dashed rgba(216, 75, 107, 0.5);
      font-size: 1.1rem;
      font-weight: 500;
    }
    .hidden-text::before {
      content: 'এখানে একটু ছুঁয়ে দে ✨';
      position: absolute;
      left: 18px;
      color: var(--accent);
      font-size: 1rem;
      font-weight: 500;
    }
    .hidden-text.revealed { 
      color: var(--text-dark); 
      border: 1px solid rgba(216, 75, 107, 0.3); 
      background: rgba(255, 255, 255, 0.95); 
      box-shadow: 0 4px 12px rgba(216, 75, 107, 0.1);
    }
    .hidden-text.revealed::before { display: none; }

    /* The Final Question Area */
    .action-area { position: relative; height: 140px; margin-top: 25px; }
    .btn-yes { position: absolute; width: 46%; left: 0; top: 20px; font-size: 1.1rem; }
    .btn-no { position: absolute; width: 46%; right: 0; top: 20px; background: #f0f0f0; color: #888; border: 1px solid #ddd; box-shadow: none; font-size: 1.1rem; }

    /* Hold Button */
    .hold-area { text-align: center; margin-top: 35px; }
    .hold-btn {
      width: 90px; height: 90px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.8);
      border: 3px solid var(--accent);
      display: flex; align-items: center; justify-content: center;
      margin: 0 auto;
      color: var(--accent);
      position: relative;
      user-select: none;
      touch-action: none;
      font-size: 2rem;
      box-shadow: 0 0 20px rgba(216, 75, 107, 0.2);
    }
    .hold-fill {
      position: absolute; bottom: 0; left: 0; width: 100%; height: 0%;
      background: var(--accent); border-radius: 50%;
      transition: height 0.1s linear; opacity: 0.2;
    }

    .particles { position: fixed; top:0; left:0; width: 100%; height: 100%; pointer-events: none; z-index: 100; }
    
    .floating-element {
      position: absolute;
      animation: floatUp 4s linear forwards;
      pointer-events: none;
    }

    @keyframes floatUp {
      0% { transform: translateY(0) scale(0.8) rotate(0deg); opacity: 0; }
      20% { opacity: 1; }
      80% { opacity: 1; }
      100% { transform: translateY(-100vh) scale(1.2) rotate(45deg); opacity: 0; }
    }
  </style>
</head>
<body>

  <div class="container">
    
    <div class="page active" id="page1">
      <div class="time-badge" id="timeBadge">⏳ সময়...</div>
      <h1 id="greeting">আমার ফেন্সী,</h1>
      <p>আমার সবচেয়ে কাছের মানুষ তুই। <span class="name-highlight">পরি</span>, তোর এই পাগলটাকে একটু সময় দিবি?</p>
      
      <div class="hold-area">
        <p style="font-size: 1rem; color: var(--accent); margin-bottom: 12px; font-weight: 500;">তোর হাতটা এখানে রাখ 🤍</p>
        <div class="hold-btn" id="holdBtn">
          <div class="hold-fill" id="holdFill"></div>
          🦋
        </div>
      </div>
    </div>

    <div class="page" id="page2">
      <h1>জানো <span class="name-highlight">পরি</span> 🌸</h1>
      <p>যত দিন যাচ্ছে, তোমাকে যেন আরও নতুন করে ভালোবাসছি। তুমি শুধু আমার <span class="name-highlight">ফেন্সী</span> নও, তুমি আমার পুরো পৃথিবী।</p>
      <p>আমার দিন শুরু হয় তোমাকে ভেবে, আর শেষ হয় তোমার মাঝেই। আমার সব রাগ, সব অভিমানের একটাই ঠিকানা—তুমি।</p>
      <button class="btn" onclick="nextPage()">আমার দিকে তাকাও 🥺</button>
    </div>

    <div class="page" id="page3">
      <p>তোমার কিছু ব্যাপার আমাকে রোজ নতুন করে প্রেমে ফেলে, জানো? 💖</p>
      <div class="hidden-text-container">
        <div class="hidden-text" onclick="reveal(this)">১. তোমার ওই মিষ্টি শাসন আর রাগ করার ধরন 🥺</div>
        <div class="hidden-text" onclick="reveal(this)">২. আমার দিকে তোমার ওই মায়াবী তাকানো ✨</div>
        <div class="hidden-text" onclick="reveal(this)">৩. আমার সব পাগলামি মুখ বুজে সহ্য করা 🦋</div>
      </div>
      <button class="btn btn-outline" id="btnPage3" style="opacity: 0.3; pointer-events: none;" onclick="nextPage()">আর কী? শুনবি?</button>
    </div>

    <div class="page" id="page4">
      <h1>শোনো আমার বউ 👑</h1>
      <p>জীবনে যাই হয়ে যাক, এই হাতটা আমি কখনো ছাড়বো না। তোমার সবটুকু জুড়ে শুধু আমি থাকতে চাই, আর আমার সবটুকু জুড়ে তুমি।</p>
      <p>পৃথিবীর সবচেয়ে সুন্দর অনুভূতি হলো তোমাকে নিজের বলতে পারা, <span class="name-highlight">ফেন্সী</span>।</p>
      <button class="btn" onclick="nextPage()">সত্যি বলছিস? 🥺</button>
    </div>

    <div class="page" id="page5">
      <h1 style="font-size: 1.5rem;">আজকে আবার জিজ্ঞেস করতে ইচ্ছে করছে...</h1>
      <div style="background: rgba(255, 255, 255, 0.6); padding: 20px; border-radius: 16px; border-left: 4px solid var(--accent); margin-bottom: 25px; margin-top: 15px;">
        <p style="margin:0; color: var(--text-dark); font-size: 1.25rem; font-weight: 600;">সারাজীবন ঠিক এভাবেই আমার আদরের '<span class="name-highlight">পরি</span>' হয়ে থাকবি তো? 💍</p>
      </div>
      
      <div class="action-area" id="actionArea">
        <button class="btn btn-yes" onclick="nextPage()">সবসময় তোর 💖</button>
        <button class="btn btn-no" id="btnNo">কক্ষনো না 😒</button>
      </div>
    </div>

    <div class="page" id="page6">
      <h1>আমি জানতাম! 😍</h1>
      <p>আমি পৃথিবীর সবচেয়ে ভাগ্যবান, কারণ তুমি আমার।</p>
      <p>অনেক অনেক ভালোবাসি তোমাকে, <span class="name-highlight">আমার ফেন্সী</span>। একদম অনন্তকাল পর্যন্ত এভাবেই জ্বালাবো! 🦋✨</p>
      <div style="text-align: center; margin-top: 35px; font-size: 3rem; animation: pulse 1.5s infinite;">❤️</div>
    </div>

  </div>

  <div class="particles" id="particlesContainer"></div>

  <style>
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.15); }
      100% { transform: scale(1); }
    }
  </style>

  <script>
    let currentPage = 1;
    let revealedItems = 0;

    function setGreeting() {
      const hour = new Date().getHours();
      let greetingText = '';
      let emoji = '';
      
      if (hour >= 5 && hour < 12) {
        greetingText = 'শুভ সকাল, বউ'; emoji = '🌅';
      } else if (hour >= 12 && hour < 16) {
        greetingText = 'শুভ দুপুর, আমার জান'; emoji = '☀️';
      } else if (hour >= 16 && hour < 18) {
        greetingText = 'শুভ বিকেল, পরি'; emoji = '☕';
      } else if (hour >= 18 && hour < 20) {
        greetingText = 'শুভ সন্ধ্যা, ফেন্সী'; emoji = '🌆';
      } else {
        greetingText = 'অনেক রাত হলো, বউ'; emoji = '🌙';
      }

      document.getElementById('greeting').innerText = greetingText;
      
      setInterval(() => {
        const now = new Date();
        let h = now.getHours();
        let m = now.getMinutes();
        let ampm = h >= 12 ? 'PM' : 'AM';
        h = h % 12; h = h ? h : 12; 
        m = m < 10 ? '0' + m : m;
        document.getElementById('timeBadge').innerHTML = `এখন ${h}:${m} ${ampm} ${emoji}`;
      }, 1000);
    }

    function nextPage() {
      if(currentPage > 5) return;
      document.getElementById(`page${currentPage}`).classList.remove('active');
      document.getElementById(`page${currentPage}`).classList.add('prev');
      currentPage++;
      document.getElementById(`page${currentPage}`).classList.add('active');
      
      if(currentPage === 6) showEffects();
    }

    // Hold Button Logic
    const holdBtn = document.getElementById('holdBtn');
    const holdFill = document.getElementById('holdFill');
    let holdInterval;
    let holdProgress = 0;

    const startHold = (e) => {
      e.preventDefault();
      holdInterval = setInterval(() => {
        holdProgress += 4;
        holdFill.style.height = `${holdProgress}%`;
        if(holdProgress >= 100) {
          clearInterval(holdInterval);
          nextPage();
        }
      }, 40);
    };

    const stopHold = () => {
      clearInterval(holdInterval);
      holdProgress = 0;
      holdFill.style.height = '0%';
    };

    holdBtn.addEventListener('mousedown', startHold);
    holdBtn.addEventListener('touchstart', startHold);
    holdBtn.addEventListener('mouseup', stopHold);
    holdBtn.addEventListener('mouseleave', stopHold);
    holdBtn.addEventListener('touchend', stopHold);

    // Reveal Texts
    window.reveal = function(el) {
      if(!el.classList.contains('revealed')) {
        el.classList.add('revealed');
        revealedItems++;
        
        // Tap visual effect
        let rect = el.getBoundingClientRect();
        createMiniBurst(rect.left + rect.width/2, rect.top + rect.height/2);

        if(revealedItems === 3) {
          const btn = document.getElementById('btnPage3');
          btn.style.opacity = '1';
          btn.style.pointerEvents = 'auto';
          btn.style.background = 'var(--accent)';
          btn.style.color = 'white';
        }
      }
    };

    function createMiniBurst(x, y) {
      const burst = document.createElement('div');
      burst.innerText = '✨';
      burst.style.position = 'fixed';
      burst.style.left = x + 'px';
      burst.style.top = y + 'px';
      burst.style.fontSize = '1.5rem';
      burst.style.pointerEvents = 'none';
      burst.style.transition = 'all 0.6s ease-out';
      burst.style.zIndex = '1000';
      document.body.appendChild(burst);
      
      setTimeout(() => {
        burst.style.transform = `translate(${Math.random()*60 - 30}px, -40px) scale(1.5)`;
        burst.style.opacity = '0';
      }, 10);
      setTimeout(() => burst.remove(), 600);
    }

    // Evading NO Button
    const noBtn = document.getElementById('btnNo');
    const actionArea = document.getElementById('actionArea');

    const dodge = (e) => {
      e.preventDefault();
      const maxX = actionArea.offsetWidth - noBtn.offsetWidth;
      const maxY = actionArea.offsetHeight - noBtn.offsetHeight;
      const randomX = Math.floor(Math.random() * maxX);
      const randomY = Math.floor(Math.random() * maxY);
      noBtn.style.left = `${randomX}px`;
      noBtn.style.top = `${randomY}px`;
      noBtn.innerText = ['ধরতে পারবি না 😛', 'কক্ষনো না 😒', 'উঁহু, হবে না 🙈'][Math.floor(Math.random()*3)];
    };

    noBtn.addEventListener('mouseover', dodge);
    noBtn.addEventListener('touchstart', dodge);

    // Final Celebration Effects
    function showEffects() {
      const container = document.getElementById('particlesContainer');
      const elements = ['💖', '🌸', '🦋', '✨', '💍'];
      
      setInterval(() => {
        const el = document.createElement('div');
        el.className = 'floating-element';
        el.innerText = elements[Math.floor(Math.random() * elements.length)];
        el.style.left = Math.random() * 100 + 'vw';
        el.style.top = '100vh';
        el.style.fontSize = (Math.random() * 1.5 + 1) + 'rem';
        container.appendChild(el);

        setTimeout(() => el.remove(), 4000);
      }, 250);
    }

    setGreeting();
  </script>
</body>
</html>
