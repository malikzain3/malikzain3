<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 450" width="100%" height="100%">
  <defs>
    <style>
      .bg { fill: #0d1117; rx: 10px; }
      .border { stroke: #30363d; stroke-width: 2; fill: none; rx: 10px; }
      .title-bar { fill: #161b22; }
      .dot-red { fill: #ff5f56; }
      .dot-yellow { fill: #ffbd2e; }
      .dot-green { fill: #27c93f; }
      .text-title { font-family: monospace; font-size: 13px; fill: #8b949e; }
      .text-main { font-family: 'Courier New', Courier, monospace; font-size: 13px; fill: #c9d1d9; }
      .text-accent { fill: #58a6ff; font-weight: bold; }
      .text-green { fill: #3fb950; }
      .text-purple { fill: #bc8cff; }
      .box-border { stroke: #30363d; stroke-width: 1.5; fill: #0d1117; rx: 6px; }
      .box-header { font-family: monospace; font-size: 12px; fill: #8b949e; font-weight: bold; }

      /* Animation Styles */
      @keyframes pulse {
        0% { opacity: 0.2; }
        50% { opacity: 1; }
        100% { opacity: 0.2; }
      }
      .live-dot { fill: #f85149; animation: pulse 1.2s infinite; }

      @keyframes scan {
        0% { transform: translateY(0px); opacity: 0; }
        50% { opacity: 0.5; }
        100% { transform: translateY(350px); opacity: 0; }
      }
      .scanline {
        fill: url(#scan-gradient);
        animation: scan 3.5s linear infinite;
      }

      @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0; }
      }
      .cursor { animation: blink 0.8s infinite; fill: #58a6ff; }
    </style>

    <linearGradient id="scan-gradient" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#58a6ff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#58a6ff" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#58a6ff" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <!-- Main Background -->
  <rect width="900" height="450" class="bg" />
  <rect width="900" height="450" class="border" />

  <!-- Window Bar -->
  <path d="M 0,10 Q 0,0 10,0 L 890,0 Q 900,0 900,10 L 900,35 L 0,35 Z" class="title-bar" />
  <circle cx="20" cy="18" r="6" class="dot-red" />
  <circle cx="40" cy="18" r="6" class="dot-yellow" />
  <circle cx="60" cy="18" r="6" class="dot-green" />
  <text x="450" y="22" text-anchor="middle" class="text-title">profile.sh --live</text>

  <!-- VISUAL.MAP Frame -->
  <rect x="20" y="55" width="360" height="375" class="box-border" />
  <text x="35" y="50" class="box-header">VISUAL.MAP</text>
  
  <!-- Image Loading with GitHub Raw Fallback -->
  <image href="https://raw.githubusercontent.com/malikzain3/malikzain3/main/profile.png" x="30" y="65" width="340" height="355" preserveAspectRatio="xMidYMid slice" />
  
  <!-- Sci-Fi Radar Overlay Animation -->
  <rect x="30" y="65" width="340" height="30" class="scanline" />

  <!-- SYSTEM.INFO Frame -->
  <rect x="400" y="55" width="480" height="375" class="box-border" />
  <text x="415" y="50" class="box-header">SYSTEM.INFO</text>

  <!-- Animated Live Status -->
  <circle cx="830" cy="72" r="5" class="live-dot" />
  <text x="840" y="76" class="text-main" style="fill: #f85149; font-weight: bold; font-size: 11px;">LIVE</text>

  <!-- Dynamic Content -->
  <g class="text-main">
    <text x="420" y="100"><tspan class="text-accent">Subject</tspan> ........................... Zainulabdin</text>
    <text x="420" y="125"><tspan class="text-accent">Role</tspan> ...................... Frontend Developer</text>
    <text x="420" y="150"><tspan class="text-accent">Origin</tspan> .................... Islamabad, Pakistan</text>
    <text x="420" y="175"><tspan class="text-accent">Education</tspan> ............................. BSSE</text>
    <text x="420" y="200"><tspan class="text-accent">Status</tspan> ......... Building + Learning + Shipping</text>
    <text x="420" y="225"><tspan class="text-accent">ToolChain</tspan> ........ VS Code, Antigravity, Kiro, Git</text>
    <text x="420" y="250"><tspan class="text-accent">Core. Lang</tspan> ......... JavaScript, TypeScript, HTML/CSS</text>
    <text x="420" y="275"><tspan class="text-accent">Core. Frontend</tspan> ................. React, Tailwind CSS</text>
    <text x="420" y="300"><tspan class="text-accent">Core. Backend</tspan> ............................ Node.js</text>
    <text x="420" y="325"><tspan class="text-accent">Core. Database</tspan> ................. FE Base, Firebase</text>

    <!-- Social Links Section -->
    <text x="420" y="360" class="text-purple">- Contact &amp; Socials</text>
    <text x="420" y="385"><tspan class="text-green">Grid. Mail</tspan> .......... zainmalik84466@gmail.com</text>
    <text x="420" y="405"><tspan class="text-green">Grid. Portfolio</tspan> ............. zainulabdin.me <rect x="680" y="394" width="8" height="13" class="cursor" /></text>
  </g>
</svg>
