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

```mermaid
flowchart TB
    AC(["~ AC INPUT"])

    subgraph BRIDGE["FULL-WAVE DIODE BRIDGE"]
        direction TB
        D1["D1 · Diode"] 
        D2["D2 · Diode"]
        D3["D3 · Diode"]
        D4["D4 · Diode"]
    end

    AC --> D1
    AC --> D3
    D1 --> POS["+ DC OUTPUT"]
    D3 --> NEG["− DC OUTPUT"]
    D2 --> POS
    D4 --> NEG
    POS --> LOAD["LOAD"]
    LOAD --> NEG

    style AC fill:#172554,stroke:#22D3EE,color:#FFFFFF,stroke-width:2px
    style D1 fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style D2 fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style D3 fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style D4 fill:#312E81,stroke:#818CF8,color:#FFFFFF
    style POS fill:#064E3B,stroke:#34D399,color:#FFFFFF,stroke-width:2px
    style NEG fill:#7F1D1D,stroke:#F87171,color:#FFFFFF,stroke-width:2px
    style LOAD fill:#0F172A,stroke:#A5B4FC,color:#FFFFFF
    style BRIDGE fill:#0B1026,stroke:#6366F1,color:#E0E7FF
```

<div align="center">

**AC INPUT → DIODE BRIDGE → DC OUTPUT**

<sub>MIDNIGHT BLUE · ELECTRIC CYAN · VIOLET</sub>

</div>


![image alt](https://github.com/BenkhiraAhmedBaderEddine1/Full-Wave-Bridge-Rectifier-PCB/blob/b1377209773fa9046c340cb3bbc02719d7b8a191/photo_2026-10-22_20-11-33.jpg)
![image alt](https://github.com/BenkhiraAhmedBaderEddine1/Full-Wave-Bridge-Rectifier-PCB/blob/b1377209773fa9046c340cb3bbc02719d7b8a191/photo_2026-10-22_20-11-35.jpg)
![image alt](https://github.com/BenkhiraAhmedBaderEddine1/Full-Wave-Bridge-Rectifier-PCB/blob/b1377209773fa9046c340cb3bbc02719d7b8a191/photo_2026-10-22_20-11-37.jpg)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:6366F1,50:22D3EE,100:A78BFA" width="100%" />

<br/>

<img src="https://img.shields.io/badge/01-RESEARCH%20%26%20DESIGN-111827?style=for-the-badge&labelColor=312E81" />

# PROJECT ABSTRACT

### Design, Analysis & Implementation of a Full-Wave Bridge Rectifier PCB

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=2500&pause=1000&color=22D3EE&center=true&vCenter=true&width=650&height=35&lines=POWER+ELECTRONICS;AC%E2%86%92DC+CONVERSION;FROM+THEORY+TO+PCB+IMPLEMENTATION" alt="Project focus" />

<br/>

</div>

---

<details open>
<summary><strong>▸ ABSTRACT — Engineering Overview</strong></summary>

<br/>

This project presents the **design, electrical analysis, and printed circuit board (PCB) implementation of a Full-Wave Bridge Rectifier**, a fundamental building block in power electronics and AC-to-DC conversion systems.

The primary objective is to develop a compact, structured, and practical electronic circuit capable of converting an alternating-current (AC) input into a unidirectional pulsating direct-current (DC) output. The design employs a **four-diode bridge configuration**, utilizing both half-cycles of the input waveform to achieve full-wave rectification.

The project integrates circuit theory, semiconductor diode characteristics, electrical calculations, schematic development, PCB layout considerations, component selection, and hardware validation. Particular attention is given to diode conduction paths, forward-voltage losses, reverse-voltage stress, current-handling capability, thermal behavior, and the relationship between electrical performance and PCB layout.

The theoretical analysis establishes the expected output waveform and provides a foundation for evaluating average DC voltage, RMS voltage, rectification efficiency, ripple factor, and power dissipation. When a smoothing capacitor is incorporated, further analysis can be conducted to investigate output ripple and load-dependent voltage variations.

The resulting PCB provides a practical engineering platform for studying AC-to-DC conversion and the relationship between theoretical circuit behavior and physical implementation. It also establishes a foundation for future improvements involving enhanced filtering, voltage regulation, thermal optimization, circuit simulation, and experimental performance characterization.

</details>

---

<div align="center">

### `CORE ENGINEERING CONCEPTS`

<img src="https://img.shields.io/badge/01-CIRCUIT%20THEORY-111827?style=flat-square&labelColor=312E81" />
<img src="https://img.shields.io/badge/02-DIODE%20BRIDGE-111827?style=flat-square&labelColor=4338CA" />
<img src="https://img.shields.io/badge/03-AC--DC%20CONVERSION-111827?style=flat-square&labelColor=0891B2" />
<img src="https://img.shields.io/badge/04-PCB%20ENGINEERING-111827?style=flat-square&labelColor=0E7490" />
<img src="https://img.shields.io/badge/05-RIPPLE%20ANALYSIS-111827?style=flat-square&labelColor=6D28D9" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:6366F1,50:22D3EE,100:A78BFA" width="75%" />

</div>

### `KEYWORDS`

`Power Electronics` · `Full-Wave Rectification` · `Bridge Rectifier` · `Printed Circuit Board` · `AC-to-DC Conversion` · `Semiconductor Diodes` · `Ripple Analysis` · `Circuit Design` · `Hardware Validation`

<div align="center">

<sub>POWER ELECTRONICS • CIRCUIT ANALYSIS • PCB IMPLEMENTATION</sub>

</div>
