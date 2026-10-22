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
