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


<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:7C3AED,45:22D3EE,100:7C3AED" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=27&duration=2500&pause=900&color=22D3EE&center=true&vCenter=true&width=800&height=55&lines=02+%2F+INTRODUCTION;03+%2F+PROBLEM+STATEMENT;04+%2F+PROJECT+OBJECTIVES" alt="Introduction, Problem Statement and Project Objectives" />

<img src="https://img.shields.io/badge/RESEARCH-0B1020?style=for-the-badge&labelColor=312E81" />
<img src="https://img.shields.io/badge/POWER_ELECTRONICS-0B1020?style=for-the-badge&labelColor=0E7490" />
<img src="https://img.shields.io/badge/ENGINEERING_DESIGN-0B1020?style=for-the-badge&labelColor=6D28D9" />

<br/><br/>

</div>

---

<details open>
<summary><strong>✦ 02. INTRODUCTION — Background & Engineering Context</strong></summary>

<br/>

<div align="center">

### `FROM ALTERNATING CURRENT TO USEFUL DC POWER`

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:312E81,50:22D3EE,100:312E81" width="65%" />

</div>

Electrical and electronic systems frequently require a **direct-current (DC) power source**, even when the available energy source provides alternating-current (AC) voltage. This requirement arises in embedded systems, industrial control circuits, instrumentation, electronic interfaces, and power-supply applications.

A rectifier performs the conversion from AC into a unidirectional current. Among the common rectifier topologies, the **full-wave bridge rectifier** is widely used because it utilizes both half-cycles of the AC waveform without requiring a center-tapped transformer.

However, designing a practical rectifier involves more than connecting four diodes. The engineer must consider source voltage, diode ratings, load current, power dissipation, reverse-voltage withstand capability, PCB trace dimensions, terminal placement, and the quality of the resulting DC waveform.

This project addresses these considerations by combining theoretical electrical analysis with PCB-oriented engineering. It progresses from understanding the circuit principle to developing a physical board that can be inspected, assembled, and tested.

Its academic value lies in the opportunity to extend basic rectification into **quantitative performance evaluation, simulation, design optimization, and experimental validation**—making it a useful foundation for advanced engineering work.

<div align="center">

<img src="https://img.shields.io/badge/AC_INPUT-6366F1?style=flat-square" />
<img src="https://img.shields.io/badge/4--DIODE_BRIDGE-7C3AED?style=flat-square" />
<img src="https://img.shields.io/badge/RECTIFIED_OUTPUT-0891B2?style=flat-square" />

</div>

</details>

---

<details open>
<summary><strong>✦ 03. PROBLEM STATEMENT — The Engineering Challenge</strong></summary>

<br/>

<div align="center">

### `DESIGNING A RELIABLE AC-TO-DC CONVERSION STAGE`

</div>

The central engineering question addressed by this project is:

> **How can an AC input be converted into a reliable, unidirectional DC output using a compact PCB while maintaining acceptable electrical losses, component temperatures, and output-waveform quality?**

The investigation focuses on the following engineering challenges:

| ID | Engineering question |
|:--:|---|
| <img src="https://img.shields.io/badge/01-6366F1?style=flat-square" /> | How do the four diodes conduct during the positive and negative input half-cycles? |
| <img src="https://img.shields.io/badge/02-7C3AED?style=flat-square" /> | What output voltage is expected after accounting for diode forward-voltage drops? |
| <img src="https://img.shields.io/badge/03-0891B2?style=flat-square" /> | How do diode current and reverse-voltage ratings affect operating limits and safety margins? |
| <img src="https://img.shields.io/badge/04-4F46E5?style=flat-square" /> | How does PCB layout influence current paths, manufacturability, and reliability? |
| <img src="https://img.shields.io/badge/05-9333EA?style=flat-square" /> | How can theoretical behavior be compared with simulated and measured results? |
| <img src="https://img.shields.io/badge/06-0E7490?style=flat-square" /> | What modifications are required to obtain smoother, regulated, or higher-current DC output? |

<div align="center">

<img width="85%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7C3AED,50:22D3EE,100:7C3AED" />

</div>

</details>

---

<details open>
<summary><strong>✦ 04. PROJECT OBJECTIVES — Design & Validation Roadmap</strong></summary>

<br/>

<div align="center">

### `FROM CIRCUIT THEORY TO PCB IMPLEMENTATION`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=2200&pause=700&color=A78BFA&center=true&vCenter=true&width=700&height=32&lines=ANALYZE+%E2%86%92+DESIGN+%E2%86%92+IMPLEMENT;CALCULATE+%E2%86%92+SIMULATE+%E2%86%92+VALIDATE" alt="Engineering workflow" />

</div>

**Main objective:** To design and analyze a full-wave bridge rectifier PCB for AC-to-DC conversion, considering its electrical behavior, component selection, and practical implementation requirements.

#### `01 — THEORETICAL ANALYSIS`

- Understand the operating principle of a four-diode bridge rectifier.
- Calculate expected output voltage, current, ripple, and power losses.
- Analyze diode conduction paths and semiconductor voltage drops.

#### `02 — CIRCUIT & PCB DESIGN`

- Develop and verify the electrical schematic.
- Select components according to the intended input voltage and load.
- Create a manufacturable PCB layout.
- Check footprints, polarity, electrical connectivity, and clearances.

#### `03 — TESTING & PERFORMANCE EVALUATION`

- Assemble and inspect the PCB, if fabrication is included.
- Evaluate circuit operation through electrical measurements and waveform analysis.
- Compare theoretical, simulated, and measured results where available.
- Identify limitations and propose technically justified improvements.

<div align="center">

<img src="https://img.shields.io/badge/01-THEORY-312E81?style=for-the-badge" />
<img src="https://img.shields.io/badge/02-DESIGN-4338CA?style=for-the-badge" />
<img src="https://img.shields.io/badge/03-IMPLEMENTATION-0E7490?style=for-the-badge" />
<img src="https://img.shields.io/badge/04-VALIDATION-7C3AED?style=for-the-badge" />

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0B1020,50:312E81,100:0891B2&section=footer" />

</div>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:7C3AED,50:22D3EE,100:6366F1" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&duration=2600&pause=900&color=22D3EE&center=true&vCenter=true&width=850&height=55&lines=05+%2F+PROJECT+SCOPE;06+%2F+THEORETICAL+ANALYSIS;ENGINEERING+%2B+MATHEMATICS" alt="Project Scope and Theoretical Analysis" />

<img src="https://img.shields.io/badge/SYSTEM-AC--DC_CONVERSION-0B1020?style=for-the-badge&labelColor=312E81" />
<img src="https://img.shields.io/badge/TOPOLOGY-FULL--WAVE_BRIDGE-0B1020?style=for-the-badge&labelColor=0E7490" />
<img src="https://img.shields.io/badge/FOCUS-CIRCUIT_ANALYSIS-0B1020?style=for-the-badge&labelColor=6D28D9" />

<br/>

<sub>DEFINE THE SYSTEM · UNDERSTAND THE CIRCUIT · QUANTIFY THE PERFORMANCE</sub>

</div>

---

<details open>
<summary><strong>✦ 05. SCOPE OF THE PROJECT</strong></summary>

<br/>

<div align="center">

### `SYSTEM BOUNDARIES & FUNCTIONAL ARCHITECTURE`

</div>

The core of this project is the design and analysis of a **full-wave bridge rectifier PCB**. Its scope focuses on AC-to-DC rectification, semiconductor operation, circuit implementation, and the electrical characteristics of the resulting output.

The circuit is not assumed to be a regulated power supply. Filtering and voltage regulation are treated as optional extensions unless they are explicitly implemented in the actual design.

#### Functional stages

```mermaid
flowchart LR
    A["AC INPUT<br/>Low-voltage source"] --> B["DIODE BRIDGE<br/>Four semiconductors"]
    B --> C["FULL-WAVE<br/>RECTIFICATION"]
    C --> D["PULSATING DC<br/>OUTPUT"]
    D -. "Optional" .-> E["FILTER<br/>Capacitor"]
    E -. "Optional" .-> F["REGULATOR<br/>Voltage control"]

    classDef source fill:#172554,stroke:#60A5FA,color:#FFFFFF,stroke-width:2px
    classDef bridge fill:#312E81,stroke:#A78BFA,color:#FFFFFF,stroke-width:2px
    classDef output fill:#064E3B,stroke:#34D399,color:#FFFFFF,stroke-width:2px
    classDef optional fill:#27272A,stroke:#71717A,color:#E4E4E7,stroke-dasharray:5 5

    class A source
    class B,C bridge
    class D output
    class E,F optional
```

<div align="center">

<img src="https://img.shields.io/badge/CORE_SCOPE-RECTIFICATION_ONLY-312E81?style=for-the-badge" />
<img src="https://img.shields.io/badge/OPTIONAL-FILTERING-52525B?style=for-the-badge" />
<img src="https://img.shields.io/badge/OPTIONAL-VOLTAGE_REGULATION-52525B?style=for-the-badge" />

</div>

#### Scope definition

| Functional stage | Description | Project status |
|---|---|---|
| AC input | Low-voltage AC source or transformer secondary | Required |
| Four-diode bridge | Converts both AC half-cycles | Core circuit |
| Rectified output | Unidirectional, pulsating DC voltage | Required |
| Capacitor filtering | Reduces output-voltage ripple | Optional |
| Voltage regulation | Maintains a controlled DC output | Optional |

> **Engineering boundary:** The actual PCB schematic determines which stages are present. A filter or regulator must not be claimed as an implemented feature unless it exists in the circuit.

</details>

---

<details open>
<summary><strong>✦ 06. THEORETICAL BACKGROUND & MATHEMATICAL ANALYSIS</strong></summary>

<br/>

<div align="center">

### `THE PHYSICS BEHIND FULL-WAVE RECTIFICATION`

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:312E81,50:22D3EE,100:7C3AED" width="70%" />

</div>

### `6.1 — Operating Principle`

A full-wave bridge rectifier consists of four semiconductor diodes connected in a bridge configuration. During each half-cycle of the AC input, a different pair of diodes conducts, maintaining the same polarity across the load.

Consequently, both the positive and negative half-cycles contribute to the rectified output. The output voltage is unidirectional but remains pulsating unless a suitable filtering stage is added.

#### Bridge rectification — functional flow

```mermaid
flowchart TD
    A(["AC INPUT<br/>v(t) = Vm sin(ωt)"]) --> B{"Input half-cycle?"}

    B -->|"Positive"| C["Conducting pair<br/>D1 and D4*"]
    B -->|"Negative"| D["Conducting pair<br/>D2 and D3*"]

    C --> E["Current through load<br/>in the same direction"]
    D --> E

    E --> F["FULL-WAVE OUTPUT<br/>vout(t) ≥ 0"]

    F --> G["Pulsating DC"]
    G --> H["Optional smoothing filter"]

    classDef input fill:#172554,stroke:#60A5FA,color:#FFFFFF,stroke-width:2px
    classDef decision fill:#312E81,stroke:#A78BFA,color:#FFFFFF,stroke-width:2px
    classDef conduction fill:#0F766E,stroke:#5EEAD4,color:#FFFFFF,stroke-width:2px
    classDef result fill:#064E3B,stroke:#34D399,color:#FFFFFF,stroke-width:2px
    classDef extension fill:#27272A,stroke:#A1A1AA,color:#FFFFFF,stroke-dasharray:5 5

    class A input
    class B decision
    class C,D,E conduction
    class F,G result
    class H extension
```

<sub>*The conducting diode pairs depend on the bridge's actual diode labeling and input/output terminal orientation. Confirm the pair names against your schematic.</sub>



![image alt](https://github.com/BenkhiraAhmedBaderEddine1/Full-Wave-Bridge-Rectifier-PCB/blob/f37bd425aad6ffb6e8810d74ae36cebe46ec6604/Screenshot%202026-10-22%20201908.png)

- the load in the defined output direction.
- Negative half-cycle: the other diagonal pair conducts, maintaining the same current direction through the load.
- Result: both half-cycles contribute to the output, producing a pulsating DC waveform with twice the input frequency.
For a conventional single-phase input, the rectified ripple frequency is therefore twice the AC supply frequency

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:7C3AED,45:22D3EE,100:6366F1" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=27&duration=2500&pause=900&color=22D3EE&center=true&vCenter=true&width=850&height=55&lines=06.2+IDEAL+OUTPUT+VOLTAGE;06.3+PRACTICAL+RECTIFICATION;06.4+RMS+%26+EFFICIENCY;06.5+OUTPUT+FILTERING" alt="Rectifier mathematical analysis" />

<img src="https://img.shields.io/badge/MATHEMATICAL_MODELING-0B1020?style=for-the-badge&labelColor=312E81" />
<img src="https://img.shields.io/badge/POWER_ELECTRONICS-0B1020?style=for-the-badge&labelColor=0E7490" />
<img src="https://img.shields.io/badge/QUANTITATIVE_ANALYSIS-0B1020?style=for-the-badge&labelColor=6D28D9" />

<br/>

<sub>FROM SINUSOIDAL INPUT TO RECTIFIED DC · THEORY MEETS ENGINEERING</sub>

</div>

---

<details open>
<summary><strong>✦ 06.2 — IDEAL OUTPUT VOLTAGE</strong></summary>

<br/>

For a sinusoidal AC input, the instantaneous source voltage is defined as

$$
\boxed{v_s(t)=V_m\sin(\omega t)}
$$

where \(V_m\) is the peak input voltage and \(\omega=2\pi f\) is the angular frequency.

For ideal diodes, the full-wave rectified output is

$$
\boxed{v_o(t)=\left|V_m\sin(\omega t)\right|}
$$

The average DC component of the unfiltered output is

$$
V_{DC}=\frac{1}{2\pi}\int_0^{2\pi}|V_m\sin\theta|\,d\theta
$$

$$
\boxed{V_{DC}=\frac{2V_m}{\pi}}
$$

Since \(V_m=\sqrt{2}\,V_{AC,\mathrm{RMS}}\), the average output can also be expressed as

$$
\boxed{V_{DC}\approx0.9003\,V_{AC,\mathrm{RMS}}}
$$

<div align="center">

<img src="https://img.shields.io/badge/KEY_RESULT-0.9003_%C3%97_VAC%2CRMS-312E81?style=for-the-badge" />

</div>

> **Engineering note:** This is the average output of an ideal, unfiltered full-wave rectifier. It is not the peak output voltage of a rectifier with a large smoothing capacitor.

</details>

---

<details open>
### ✦ 06.3 — PRACTICAL OUTPUT VOLTAGE

In a practical bridge rectifier, two diodes conduct in series during each half-cycle. The instantaneous output voltage can be approximated by:

$$
\boxed{v_o(t) \approx \max\left( |v_s(t)| - 2V_F,\ 0 \right)}
$$

where \(V_F\) represents the forward-voltage drop of one conducting diode.

The actual output depends on the diode characteristics, input amplitude, source impedance, load current, and temperature. The constant-drop model is useful for initial calculations but should be verified against datasheets and measurements.

For a resistive load \(R_L\), Ohm's law gives:

$$
\boxed{i_L(t) = \frac{v_o(t)}{R_L}}
$$

The instantaneous power dissipated by the load is:

$$
\boxed{p_L(t) = v_o(t)i_L(t) = \frac{v_o^2(t)}{R_L}}
$$

| **Parameter** | **Symbol** | **Engineering Meaning** |
|:---|:---:|:---|
| Peak input voltage | \(V_m\) | Maximum instantaneous AC input |
| Diode forward drop | \(V_F\) | Voltage drop across one conducting diode |
| Load resistance | \(R_L\) | Resistive output load |
| Load current | \(i_L(t)\) | Instantaneous current through the load |

---

### ✦ 06.4 — RMS VOLTAGE & RECTIFICATION EFFICIENCY

For an ideal, unfiltered, full-wave rectified waveform, the RMS output voltage is:

$$
\boxed{V_{o,\mathrm{RMS}} = \frac{V_m}{\sqrt{2}}}
$$

The ripple factor measures the RMS magnitude of the AC component relative to the DC component:

$$
r = \sqrt{\left(\frac{V_{o,\mathrm{RMS}}}{V_{DC}}\right)^2 - 1}
$$

Substituting the ideal full-wave rectifier expressions gives:

$$
\boxed{r = \sqrt{\frac{\pi^2}{8} - 1} \approx 0.482}
$$

Rectification efficiency is defined as the ratio of useful DC load power to the AC input power:

$$
\boxed{\eta = \frac{P_{DC}}{P_{AC}} \times 100\%}
$$

For an ideal full-wave rectifier with a resistive load and ideal diodes, the theoretical maximum rectification efficiency is:

$$
\boxed{\eta_{\max} = \frac{8}{\pi^2} \times 100\% \approx 81.2\%}
$$

This is a theoretical value, not a measured efficiency result for the physical PCB. Real diode losses, source impedance, transformer losses, and other nonidealities reduce overall performance.

---

### ✦ 06.5 — OUTPUT FILTERING & RIPPLE ANALYSIS

When a smoothing capacitor \(C\) is connected across the load, it charges near the rectified voltage peaks and discharges through the load between successive peaks.

For a capacitor-input filter, the approximate peak-to-peak ripple voltage is:

$$
\boxed{V_{r(pp)} \approx \frac{I_L}{2fC}}
$$

where:

- \(V_{r(pp)}\) is the peak-to-peak ripple voltage.
- \(I_L\) is the approximate DC load current.
- \(f\) is the AC input frequency.
- \(C\) is the smoothing capacitance.

The full-wave rectifier's ripple repetition frequency is:

$$
\boxed{f_r = 2f}
$$

**Engineering note:** The ripple approximation assumes a sufficiently large smoothing capacitor and relatively small ripple. Actual ripple depends on load current, capacitance, input frequency, diode characteristics, and source impedance.
<div align="center">

```mermaid
flowchart LR
    A["AC Source"] --> B["Four-Diode Bridge"]
    B --> C["Pulsating DC"]
    C --> D{"Filter fitted?"}
    D -->|Yes| E["Capacitor Filter"]
    D -->|No| F["Unfiltered Output"]
    E --> G["Reduced Ripple"]
    F --> H["Higher Ripple"]

    classDef source fill:#172554,stroke:#60A5FA,color:#fff,stroke-width:2px
    classDef bridge fill:#312E81,stroke:#A78BFA,color:#fff,stroke-width:2px
    classDef output fill:#064E3B,stroke:#34D399,color:#fff,stroke-width:2px
    classDef choice fill:#0E7490,stroke:#22D3EE,color:#fff,stroke-width:2px
    class A source
    class B bridge
    class C,E,F,G,H output
    class D choice
```

</div>

**Design trade-off:** A smoothing capacitor reduces ripple but can increase peak charging currents and diode stress. Capacitor voltage rating, ripple-current rating, load conditions, and diode current capability must therefore be considered.

</details>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:7C3AED,50:22D3EE,100:6366F1" />

## ✦ 07 — ILLUSTRATIVE DESIGN CALCULATIONS

<sub>EXAMPLE VALUES FOR ANALYSIS · NOT MEASURED PCB RESULTS</sub>

</div>

For illustration, consider a sinusoidal input of \(12\,\mathrm{V_{RMS}}\), a frequency of \(50\,\mathrm{Hz}\), a resistive load of \(1\,\mathrm{k\Omega}\), and a nominal diode forward drop of \(0.7\,\mathrm{V}\) per conducting diode.

<div align="center">

| DESIGN PARAMETER | VALUE |
|:--|--:|
| AC input voltage | **12 V RMS** |
| Input frequency | **50 Hz** |
| Peak input voltage | **16.97 V** |
| Rectified ripple frequency | **100 Hz** |
| Load resistance | **1 kΩ** |
| Assumed forward drop per diode | **0.7 V** |

</div>

### `07.1 — Peak Output Voltage`

$$
V_m=\sqrt{2}\times12\approx16.97\,\mathrm{V}
$$

$$
\boxed{V_{o,pk}\approx16.97-2(0.7)=15.57\,\mathrm{V}}
$$

### `07.2 — Average Output Voltage`

Ideal, unfiltered output:

$$
V_{DC,\mathrm{ideal}}=0.9003\times12\approx10.80\,\mathrm{V}
$$

Simplified constant-diode-drop estimate:

$$
V_{DC,\mathrm{approx}}\approx\frac{2V_m}{\pi}-2V_F
$$

$$
\boxed{V_{DC,\mathrm{approx}}\approx9.40\,\mathrm{V}}
$$

This simplified estimate is not an exact integration of the practical conduction waveform. It can become inaccurate at low input voltages or under significant loading.

### `07.3 — Average Load Current & Power`

Using the simplified average-voltage estimate:

$$
I_{L,\mathrm{approx}}\approx\frac{9.40}{1000}
=\boxed{9.40\,\mathrm{mA}}
$$

$$
P_{L,\mathrm{approx}}\approx\frac{(9.40)^2}{1000}
=\boxed{88.36\,\mathrm{mW}}
$$

These are illustrative estimates based on the stated assumptions. Actual load power should be calculated from the measured or simulated voltage and current waveforms.

<div align="center">

<img src="https://img.shields.io/badge/NOTE-ILLUSTRATIVE_CALCULATIONS-312E81?style=for-the-badge" />
<img src="https://img.shields.io/badge/NO_MEASURED_RESULTS_CLAIMED-0B1020?style=for-the-badge&labelColor=0E7490" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:080B24,50:312E81,100:0891B2&section=footer" width="100%" />

<sub>MATHEMATICAL MODELING · POWER CONVERSION · PCB ENGINEERING</sub>

</div>
