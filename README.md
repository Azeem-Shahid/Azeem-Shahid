<svg width="680" height="200" viewBox="0 0 680 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M2 1L8 5L2 9" fill="none" stroke="context-stroke" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
    </marker>
  </defs>
  <!-- Background -->
  <rect width="680" height="200" rx="14" fill="#0D1117"/>
  <!-- Subtle grid -->
  <line x1="0" y1="100" x2="680" y2="100" stroke="#ffffff" stroke-width="0.3" opacity="0.06"/>
  <line x1="340" y1="0" x2="340" y2="200" stroke="#ffffff" stroke-width="0.3" opacity="0.06"/>
  <!-- Title -->
  <text x="340" y="28" text-anchor="middle" font-family="monospace" font-size="13" font-weight="500" fill="#00F7FF" opacity="0.85">SecureOps — Automated Security Pipeline</text>
  <!-- Node 1: Code Push -->
  <rect x="20" y="55" width="80" height="44" rx="8" fill="#0F2027" stroke="#00F7FF" stroke-width="0.8"/>
  <text x="60" y="73" text-anchor="middle" font-family="monospace" font-size="11" font-weight="500" fill="#00F7FF">Code</text>
  <text x="60" y="88" text-anchor="middle" font-family="monospace" font-size="10" fill="#7ecfcf">Push</text>
  <!-- Arrow 1 -->
  <line x1="101" y1="77" x2="123" y2="77" stroke="#00F7FF" stroke-width="1" marker-end="url(#arrow)" opacity="0.6"/>
  <!-- Node 2: GitHub Actions -->
  <rect x="124" y="55" width="90" height="44" rx="8" fill="#0F2027" stroke="#2088FF" stroke-width="0.8"/>
  <text x="169" y="73" text-anchor="middle" font-family="monospace" font-size="11" font-weight="500" fill="#2088FF">GitHub</text>
  <text x="169" y="88" text-anchor="middle" font-family="monospace" font-size="10" fill="#7aadee">Actions</text>
  <!-- Arrow 2 -->
  <line x1="215" y1="77" x2="232" y2="77" stroke="#2088FF" stroke-width="1" marker-end="url(#arrow)" opacity="0.6"/>
  <!-- Branch lines to 5 scanners -->
  <line x1="233" y1="77" x2="233" y2="30"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="233" y1="77" x2="233" y2="124" stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="233" y1="30"  x2="255" y2="30"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <line x1="233" y1="56"  x2="255" y2="56"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <line x1="233" y1="77"  x2="255" y2="77"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <line x1="233" y1="98"  x2="255" y2="98"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <line x1="233" y1="124" x2="255" y2="124" stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <!-- 5 Scanner boxes -->
  <rect x="256" y="18"  width="82" height="24" rx="6" fill="#1a2a3a" stroke="#4E9BCD" stroke-width="0.7"/>
  <text x="297" y="34"  text-anchor="middle" font-family="monospace" font-size="10" fill="#4E9BCD">SonarQube</text>
  <rect x="256" y="44"  width="82" height="24" rx="6" fill="#1a2a3a" stroke="#6b8eee" stroke-width="0.7"/>
  <text x="297" y="60"  text-anchor="middle" font-family="monospace" font-size="10" fill="#6b8eee">Trivy</text>
  <rect x="256" y="66"  width="82" height="24" rx="6" fill="#1a2a3a" stroke="#aaaaaa" stroke-width="0.7"/>
  <text x="297" y="82"  text-anchor="middle" font-family="monospace" font-size="10" fill="#cccccc">OWASP DC</text>
  <rect x="256" y="88"  width="82" height="24" rx="6" fill="#1a2a3a" stroke="#FC4B08" stroke-width="0.7"/>
  <text x="297" y="104" text-anchor="middle" font-family="monospace" font-size="10" fill="#FC4B08">Semgrep</text>
  <rect x="256" y="112" width="82" height="24" rx="6" fill="#1a2a3a" stroke="#FF4444" stroke-width="0.7"/>
  <text x="297" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#FF4444">Gitleaks</text>
  <!-- Merge lines back -->
  <line x1="338" y1="30"  x2="345" y2="30"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="338" y1="56"  x2="345" y2="56"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="338" y1="77"  x2="345" y2="77"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="338" y1="98"  x2="345" y2="98"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="338" y1="124" x2="345" y2="124" stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="345" y1="30"  x2="345" y2="124" stroke="#aaaaaa" stroke-width="0.5" opacity="0.4"/>
  <line x1="345" y1="77"  x2="365" y2="77"  stroke="#aaaaaa" stroke-width="0.5" opacity="0.4" marker-end="url(#arrow)"/>
  <!-- Node 3: Quality Gate -->
  <rect x="366" y="55" width="82" height="44" rx="8" fill="#0F2027" stroke="#F5A623" stroke-width="0.9"/>
  <rect x="398" y="68" width="16" height="12" rx="3" fill="none" stroke="#F5A623" stroke-width="1.2"/>
  <path d="M400 68 Q400 62 406 62 Q412 62 412 68" fill="none" stroke="#F5A623" stroke-width="1.2"/>
  <circle cx="406" cy="74" r="2" fill="#F5A623"/>
  <text x="407" y="94" text-anchor="middle" font-family="monospace" font-size="10" fill="#F5A623">Quality Gate</text>
  <!-- Arrow 3 -->
  <line x1="449" y1="77" x2="466" y2="77" stroke="#F5A623" stroke-width="1" marker-end="url(#arrow)" opacity="0.7"/>
  <!-- Node 4: Claude AI -->
  <rect x="467" y="55" width="76" height="44" rx="8" fill="#0F2027" stroke="#a78bfa" stroke-width="0.8"/>
  <path d="M494 64 Q505 60 516 64 L516 74 Q505 82 494 78 Z" fill="none" stroke="#a78bfa" stroke-width="1.1"/>
  <text x="505" y="94" text-anchor="middle" font-family="monospace" font-size="10" fill="#a78bfa">Claude AI</text>
  <!-- Arrow 4 -->
  <line x1="544" y1="77" x2="560" y2="77" stroke="#a78bfa" stroke-width="1" marker-end="url(#arrow)" opacity="0.7"/>
  <!-- Node 5: Dashboard -->
  <rect x="561" y="55" width="88" height="44" rx="8" fill="#0F2027" stroke="#00ff88" stroke-width="0.9"/>
  <rect x="578" y="76" width="5" height="10" rx="1" fill="#00ff88" opacity="0.8"/>
  <rect x="585" y="70" width="5" height="16" rx="1" fill="#00ff88" opacity="0.9"/>
  <rect x="592" y="73" width="5" height="13" rx="1" fill="#00ff88" opacity="0.8"/>
  <text x="620" y="77" text-anchor="middle" font-family="monospace" font-size="10" font-weight="500" fill="#00ff88">Dashboard</text>
  <text x="620" y="91" text-anchor="middle" font-family="monospace" font-size="10" fill="#7dddb0">+ PDF Report</text>
  <!-- Bottom annotations -->
  <text x="297" y="152" text-anchor="middle" font-family="monospace" font-size="10" fill="#ffffff" opacity="0.35">5 scanners in parallel</text>
  <text x="340" y="178" text-anchor="middle" font-family="monospace" font-size="11" fill="#ffffff" opacity="0.25">Automated · AI-Powered · Role-Based · Production-Grade</text>
</svg>
