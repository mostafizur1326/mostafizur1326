# MOSTALIF

<!-- Animated SVG text with gradient fill and wow effect -->

<div style="width: fit-content; margin: 20px auto;">
  <svg viewBox="0 0 600 150" width="600" height="150" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#ff0057">
          <animate attributeName="stop-color" values="#ff0057;#00ffea;#ff0057" dur="3s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#00ffea">
          <animate attributeName="stop-color" values="#00ffea;#ff0057;#00ffea" dur="3s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%" >
        <feDropShadow dx="0" dy="0" stdDeviation="6" flood-color="#ff0057" flood-opacity="0.7"/>
        <feDropShadow dx="0" dy="0" stdDeviation="10" flood-color="#00ffea" flood-opacity="0.8"/>
      </filter>
    </defs>
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
          font-family="Poppins, sans-serif" font-weight="900" font-size="80"
          fill="url(#grad)" filter="url(#glow)">
      MOSTALIF
    </text>
  </svg>
</div>
