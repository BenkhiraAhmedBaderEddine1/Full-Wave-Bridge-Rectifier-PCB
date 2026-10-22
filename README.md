 <div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:080B24,45:172554,75:4338CA,100:06B6D4&text=FULL-WAVE%20BRIDGE%20RECTIFIER&fontSize=30&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn&desc=POWER%20ELECTRONICS%20%2F%20PCB%20ENGINEERING&descAlignY=62&descSize=14" />

<br/>

<img src="https://img.shields.io/badge/POWER_ELECTRONICS-0B1026?style=for-the-badge&logo=atom&logoColor=22D3EE" />
<img src="https://img.shields.io/badge/CIRCUIT_DESIGN-172554?style=for-the-badge&logoColor=67E8F9" />
<img src="https://img.shields.io/badge/PCB_ENGINEERING-312E81?style=for-the-badge&logoColor=C4B5FD" />

### ⚡ Converting Alternating Current into Direct Current

*A bridge rectifier circuit designed to explore semiconductor conduction, full-wave rectification, and practical printed circuit board engineering.*

<br/>

<img width="80%" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=900&color=22D3EE&center=true&vCenter=true&width=750&height=40&lines=AC+INPUT+%E2%86%92+DIODE+BRIDGE+%E2%86%92+DC+OUTPUT;FOUR+DIODES.+ONE+RECTIFICATION+STAGE.;FROM+CIRCUIT+THEORY+TO+PCB+DESIGN." alt="Project tagline" />

</div>

---

<div align="center">

### `CIRCUIT VISUALIZATION // FULL-WAVE RECTIFICATION`

</div>

<p align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 370" width="100%" role="img" aria-label="Full-wave bridge rectifier circuit with four diodes, AC input, and DC output">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#080B24"/>
        <stop offset="100%" stop-color="#111B40"/>
      </linearGradient>
      <linearGradient id="wire" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#6366F1"/>
        <stop offset="100%" stop-color="#22D3EE"/>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <style>
        .wire{fill:none;stroke:url(#wire);stroke-width:3;stroke-linecap:round;stroke-linejoin:round}
        .node{fill:#22D3EE;filter:url(#glow)}
        .diode{fill:#0B1026;stroke:#A5B4FC;stroke-width:2}
        .label{font: bold 13px monospace;fill:#E0E7FF}
        .sub{font:11px monospace;fill:#93A4D4}
        .pulse{fill:none;stroke:#67E8F9;stroke-width:3;stroke-dasharray:8 13;animation:flow 1.4s linear infinite;filter:url(#glow)}
        @keyframes flow{to{stroke-dashoffset:-42}}
      </style>
    </defs>
    <rect width="820" height="370" rx="18" fill="url(#bg)" stroke="#3730A3" stroke-width="1.5"/>
    <g opacity=".13" stroke="#818CF8" stroke-width=".6">
      <path d="M30 40H790 M30 80H790 M30 120H790 M30 160H790 M30 200H790 M30 240H790 M30 280H790 M30 320H790"/>
      <path d="M70 20V350 M110 20V350 M150 20V350 M190 20V350 M230 20V350 M270 20V350 M310 20V350 M350 20V350 M390 20V350 M430 20V350 M470 20V350 M510 20V350 M550 20V350 M590 20V350 M630 20V350 M670 20V350 M710 20V350 M750 20V350"/>
    </g>
    <text x="28" y="29" class="sub">POWER CIRCUIT / BR-01</text>
    <text x="790" y="29" text-anchor="end" class="sub">AC → DC</text>
    <g class="wire">
      <path d="M170 145H265 L410 65 L555 145H650"/>
      <path d="M170 235H265 L410 315 L555 235H650"/>
      <path d="M265 145V235 M555 145V235"/>
      <path d="M265 145H410 M555 145H410" opacity=".0"/>
      <path d="M265 145L410 145 M410 145L555 145" opacity=".0"/>
      <path d="M410 65V105 M410 275V315"/>
      <path d="M410 105V145 M410 235V275" opacity=".0"/>
    </g>
    <g>
      <circle cx="105" cy="190" r="34" fill="#0B1026" stroke="#818CF8" stroke-width="2"/>
      <path d="M80 190 C88 166 98 166 105 190 S122 214 130 190" fill="none" stroke="#C4B5FD" stroke-width="2.5"/>
      <path class="wire" d="M139 190H170 M170 145V235"/>
      <text x="105" y="247" text-anchor="middle" class="label">AC INPUT</text>
      <text x="105" y="263" text-anchor="middle" class="sub">~ VAC</text>
    </g>
    <g>
      <path d="M265 145l-23 -12v24z" class="diode"/>
      <path d="M242 132v26" stroke="#22D3EE" stroke-width="3"/>
      <path d="M555 145l-23 -12v24z" class="diode" transform="translate(1110 0) scale(-1 1)"/>
      <path d="M578 132v26" stroke="#22D3EE" stroke-width="3"/>
      <path d="M265 235l-23 -12v24z" class="diode" transform="translate(0 470) scale(1 -1)"/>
      <path d="M242 222v26" stroke="#A5B4FC" stroke-width="3"/>
      <path d="M555 235l-23 -12v24z" class="diode" transform="translate(1110 470) scale(-1 -1)"/>
      <path d="M578 222v26" stroke="#A5B4FC" stroke-width="3"/>
      <text x="286" y="121" class="label">D1</text>
      <text x="510" y="121" class="label">D2</text>
      <text x="286" y="266" class="label">D3</text>
      <text x="510" y="266" class="label">D4</text>
    </g>
    <g class="wire">
      <path d="M410 65V42H650V145"/>
      <path d="M410 315V338H650V235"/>
    </g>
    <g>
      <circle cx="650" cy="145" r="5" class="node"/>
      <circle cx="650" cy="235" r="5" class="node"/>
      <path d="M650 145H700V165 M650 235H700V215 M700 165V215" class="wire"/>
      <rect x="684" y="174" width="32" height="32" rx="4" fill="#0B1026" stroke="#A5B4FC" stroke-width="2"/>
      <text x="700" y="194" text-anchor="middle" class="label">R</text>
      <text x="700" y="252" text-anchor="middle" class="label">DC LOAD</text>
      <text x="700" y="268" text-anchor="middle" class="sub">+ / −</text>
    </g>
    <path d="M177 145L240 145 M290 145L390 90 M430 90L540 145 M580 145L640 145" class="pulse"/>
    <path d="M640 235L580 235 M530 235L430 290 M390 290L290 235 M240 235L177 235" class="pulse" opacity=".7"/>
    <text x="410" y="190" text-anchor="middle" class="label">DIODE BRIDGE</text>
    <text x="410" y="207" text-anchor="middle" class="sub">FULL-WAVE RECTIFICATION</text>
    <text x="28" y="344" class="sub">CONCEPTUAL SVG SCHEMATIC · NOT A PCB NETLIST</text>
    <circle cx="790" cy="344" r="4" fill="#22D3EE" filter="url(#glow)"/>
  </svg>
</p>

<div align="center">

<sub>ANIMATED SVG CIRCUIT · NEON CYAN SIGNAL FLOW · MIDNIGHT BLUE ENGINEERING THEME</sub>

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:080B24,50:312E81,100:06B6D4&height=90&section=footer" width="100%" />
</div>

