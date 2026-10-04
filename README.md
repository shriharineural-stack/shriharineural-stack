<!-- Red Neon Gradient for Text -->
<linearGradient id="red-glow-grad" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#ff4458" />
  <stop offset="40%" stop-color="#ff1a35" />
  <stop offset="70%" stop-color="#ffffff" />
  <stop offset="100%" stop-color="#ff2a45" />
  <animate attributeName="x1" from="-100%" to="100%" dur="7s" repeatCount="indefinite" />
  <animate attributeName="x2" from="0%" to="200%" dur="7s" repeatCount="indefinite" />
</linearGradient>

<!-- Border Glow Gradient -->
<linearGradient id="border-grad" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#7f1d1d" />
  <stop offset="30%" stop-color="#ef4444" />
  <stop offset="50%" stop-color="#ff4d6d" />
  <stop offset="70%" stop-color="#ef4444" />
  <stop offset="100%" stop-color="#7f1d1d" />
</linearGradient>

<!-- Filters for Neon Glow -->
<filter id="glow-red" x="-20%" y="-20%" width="140%" height="140%">
  <feGaussianBlur stdDeviation="8" result="blur" />
  <feMerge>
    <feMergeNode in="blur" />
    <feMergeNode in="blur" />
    <feMergeNode in="SourceGraphic" />
  </feMerge>
</filter>

<filter id="ambient-blur">
  <feGaussianBlur stdDeviation="40" />
</filter>

<!-- Grid Pattern -->
<pattern id="tech-grid" width="30" height="30" patternUnits="userSpaceOnUse">
  <path d="M 30 0 L 0 0 0 30" fill="none" stroke="#ef4444" stroke-width="0.75" stroke-opacity="0.08" />
</pattern>
