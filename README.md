<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 120" fill="none">
  <style>
    @keyframes grow { 0%,100% { transform: scaleY(1); } 50% { transform: scaleY(1.05); } }
    @keyframes sway2 { 0%,100% { transform: rotate(-2deg); } 50% { transform: rotate(2deg); } }
    .p1 { animation: sway2 3s ease-in-out infinite; transform-origin: 120px 90px; }
    .p2 { animation: sway2 3.5s ease-in-out infinite 0.5s; transform-origin: 300px 90px; }
    .p3 { animation: sway2 2.8s ease-in-out infinite 1s; transform-origin: 480px 90px; }
  </style>

  <!-- shelf -->
  <rect x="40" y="92" width="520" height="4" rx="2" fill="#D4A574" opacity="0.6"/>
  <rect x="40" y="96" width="520" height="2" rx="1" fill="#C49A6C" opacity="0.4"/>

  <!-- pot 1: backend systems -->
  <g class="p1">
    <rect x="100" y="78" width="40" height="16" rx="4" fill="#E8A87C"/>
    <rect x="96" y="75" width="48" height="6" rx="2" fill="#E8A87C"/>
    <!-- plant -->
    <path d="M120 75 Q118 55 125 40" stroke="#6BBF59" stroke-width="2" fill="none"/>
    <path d="M120 75 Q122 58 115 45" stroke="#6BBF59" stroke-width="2" fill="none"/>
    <ellipse cx="125" cy="38" rx="6" ry="3.5" fill="#A8D882"/>
    <ellipse cx="114" cy="43" rx="5.5" ry="3" fill="#A8D882"/>
    <ellipse cx="120" cy="35" rx="5" ry="3" fill="#C8E6A0"/>
    <!-- label -->
    <text x="120" y="110" text-anchor="middle" font-family="Georgia, serif" font-size="9" fill="#8B6B9E" font-style="italic">backend systems</text>
  </g>

  <!-- pot 2: ai pipelines -->
  <g class="p2">
    <rect x="280" y="78" width="40" height="16" rx="4" fill="#C8A2E8" opacity="0.6"/>
    <rect x="276" y="75" width="48" height="6" rx="2" fill="#C8A2E8" opacity="0.6"/>
    <!-- cactus with flower -->
    <rect x="296" y="45" width="8" height="30" rx="4" fill="#6BBF59"/>
    <path d="M296 60 Q286 55 288 48" stroke="#6BBF59" stroke-width="4" fill="none" stroke-linecap="round"/>
    <path d="M304 55 Q314 50 312 43" stroke="#6BBF59" stroke-width="4" fill="none" stroke-linecap="round"/>
    <circle cx="300" cy="43" r="4" fill="#FF9EB5"/>
    <circle cx="300" cy="43" r="2" fill="#FFE066"/>
    <text x="300" y="110" text-anchor="middle" font-family="Georgia, serif" font-size="9" fill="#8B6B9E" font-style="italic">ai pipelines</text>
  </g>

  <!-- pot 3: open source -->
  <g class="p3">
    <rect x="460" y="78" width="40" height="16" rx="4" fill="#FFB4C8" opacity="0.6"/>
    <rect x="456" y="75" width="48" height="6" rx="2" fill="#FFB4C8" opacity="0.6"/>
    <!-- sunflower -->
    <path d="M480 75 Q478 55 480 38" stroke="#6BBF59" stroke-width="2" fill="none"/>
    <ellipse cx="475" cy="55" rx="5" ry="2.5" fill="#A8D882" transform="rotate(-25 475 55)"/>
    <circle cx="477" cy="33" r="4" fill="#FFD700"/><circle cx="483" cy="33" r="4" fill="#FFD700"/>
    <circle cx="480" cy="29" r="4" fill="#FFD700"/><circle cx="480" cy="37" r="4" fill="#FFD700"/>
    <circle cx="477" cy="30" r="4" fill="#FFE066"/><circle cx="483" cy="36" r="4" fill="#FFE066"/>
    <circle cx="480" cy="33" r="3" fill="#8B6B3E"/>
    <text x="480" y="110" text-anchor="middle" font-family="Georgia, serif" font-size="9" fill="#8B6B9E" font-style="italic">open source</text>
  </g>
</svg>
