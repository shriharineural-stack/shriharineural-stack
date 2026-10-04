<svg xmlns="http://www.w3.org/2000/svg"
     width="1600"
     height="500"
     viewBox="0 0 1600 500">

  <defs>

    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#020204"/>
      <stop offset="55%" stop-color="#09090d"/>
      <stop offset="100%" stop-color="#210308"/>
    </linearGradient>

    <linearGradient id="red" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#65000e"/>
      <stop offset="50%" stop-color="#ff1744"/>
      <stop offset="100%" stop-color="#65000e"/>
    </linearGradient>

    <radialGradient id="glow">
      <stop offset="0%" stop-color="#ff1744" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#ff1744" stop-opacity="0"/>
    </radialGradient>

    <pattern id="grid"
             width="50"
             height="50"
             patternUnits="userSpaceOnUse">

      <path d="M50 0H0V50"
            fill="none"
            stroke="#ff1744"
            stroke-opacity="0.08"/>

    </pattern>

  </defs>

  <!-- BACKGROUND -->
  <rect width="1600" height="500" fill="url(#bg)"/>

  <!-- GRID -->
  <rect width="1600" height="500" fill="url(#grid)"/>

  <!-- CENTER GLOW -->
  <ellipse
    cx="800"
    cy="250"
    rx="650"
    ry="230"
    fill="url(#glow)"
  />

  <!-- TOP NEON LINE -->
  <rect
    x="100"
    y="35"
    width="1400"
    height="2"
    fill="url(#red)"
  />

  <!-- B
