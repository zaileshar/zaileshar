<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=220&text=Zailesh%20A%20R&fontSize=70&color=0:5C4AE4,100:7986CB&fontColor=E8EAF6&animation=fadeIn&fontAlignY=55&stroke=5C4AE4&strokeWidth=1&desc=VLSI+Design+Engineering+Student&descAlignY=75&descSize=15&descColor=C5CAE9"/>

<a href="mailto:zaileshar@gmail.com">
  <img src="https://img.shields.io/badge/Email-zaileshar%40gmail.com-0D1230?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=0D1230"/>
</a>
&ensp;
<a href="https://www.linkedin.com/in/zaileshar/">
  <img src="https://img.shields.io/badge/LinkedIn-Zailesh%20A%20R-0D1230?style=flat-square&logo=linkedin&logoColor=5C9EFF&labelColor=0D1230"/>
</a>
&ensp;
<a href="https://zaileshar.github.io/">
  <img src="https://img.shields.io/badge/Portfolio-zaileshar.github.io-5C4AE4?style=flat-square&logo=githubpages&logoColor=white&labelColor=5C4AE4"/>
</a>

<br><br>

<img src="https://img.shields.io/badge/RTL-0D1230?style=flat-square&labelColor=0D1230&color=0D1230"/>
<img src="https://img.shields.io/badge/%E2%86%92-5C4AE4?style=flat-square&color=5C4AE4&labelColor=5C4AE4"/>
<img src="https://img.shields.io/badge/Synthesis-0D1230?style=flat-square&labelColor=0D1230&color=0D1230"/>
<img src="https://img.shields.io/badge/%E2%86%92-5C4AE4?style=flat-square&color=5C4AE4&labelColor=5C4AE4"/>
<img src="https://img.shields.io/badge/Timing-0D1230?style=flat-square&labelColor=0D1230&color=0D1230"/>
<img src="https://img.shields.io/badge/%E2%86%92-5C4AE4?style=flat-square&color=5C4AE4&labelColor=5C4AE4"/>
<img src="https://img.shields.io/badge/Silicon-0D1230?style=flat-square&labelColor=0D1230&color=0D1230"/>

</div>

<br>

---

## ⬡ &nbsp;How I got here

> *How does logic written in code eventually become real silicon?*

That question genuinely stopped me when I first came across it. Sand. A processor. The gap between those two things is enormous, and I've been slowly trying to understand it ever since.

I'm a **VLSI Design Engineering student**, and most of what I work on comes down to this: getting RTL to hold up beyond simulation. A lot of student projects stop at the waveform. I want to know what happens after — why certain coding styles cause synthesis tools to bloat area unexpectedly, where timing violations actually originate, and what it takes to write RTL that doesn't fall apart under real constraints.

I don't always get it right on the first pass. But I'd rather build something, watch the synthesis report light up with warnings, and trace them back to the source — than write code that looks clean but I don't fully understand.

---

## ⬡ &nbsp;Design Philosophy

<div align="center">

<table border="0" cellpadding="18" cellspacing="0">
<tr>
<td align="center" width="200">
<b>Synthesizable First</b><br/>
<sub>Every construct is verified<br/>against real synthesis tools</sub>
</td>
<td align="center" width="10"><sub>│</sub></td>
<td align="center" width="200">
<b>Constraint-Driven</b><br/>
<sub>SDC written to reflect genuine<br/>physical intent, not formality</sub>
</td>
<td align="center" width="10"><sub>│</sub></td>
<td align="center" width="200">
<b>PPA Aware</b><br/>
<sub>Every design choice weighed<br/>on power, performance, area</sub>
</td>
</tr>
</table>

<br>

> **_Can this realistically become silicon?_**

</div>

<br>

When I write RTL, I try to ask one question throughout: will this actually synthesize the way I think it will? That means:

- &nbsp;✦&nbsp; No constructs that are technically valid Verilog but **synthesis tools handle inconsistently**
- &nbsp;✦&nbsp; Clocking and reset logic that's **explicit and intentional**, not just implied
- &nbsp;✦&nbsp; SDC constraints that reflect what the design actually needs, not what makes the tool go green
- &nbsp;✦&nbsp; Some awareness of what the **timing and area reports are going to look like** before I'm staring at them
- &nbsp;✦&nbsp; RTL that could, in principle, be handed to a physical design flow without major rework

---

## ⬡ &nbsp;How I work through problems

The most useful thing I've found is to write the same design more than one way and then synthesize both. The reports tell you things that no amount of staring at RTL will. An unexpected critical path, area that's twice what you expected, a register that got inferred differently — these are more educational than most textbook explanations.

<div align="center">

```
Build  →  Synthesize  →  Read the reports  →  Fix something  →  Repeat
```

</div>

The timing report in particular has taught me more about clocking and datapath structure than anything else. It's specific in a way that forces you to actually understand what's happening, not just guess.

---

## ⬡ &nbsp;Areas of Active Exploration

<div align="center">

| Domain | Current Focus | Why It Matters |
|:-------|:--------------|:---------------|
| **RTL Design** | ASIC-grade Verilog · SystemVerilog · synthesis-aware coding styles | The foundation everything else is built on |
| **Arithmetic Datapaths** | Adders · multipliers · dividers · critical path analysis | Where PPA trade-offs are most vivid and instructive |
| **Timing Analysis** | SDC constraints · setup/hold · slack-driven optimization | The gateway between design intent and silicon reality |
| **RISC-V Architecture** | Datapath · control logic · peripheral integration | Complex, real-world design context at every level |
| **Physical Awareness** | Floorplanning · placement sensitivity · clock tree thinking | Bridging RTL decisions to downstream physical outcomes |

</div>

---

## ⬡ &nbsp;Technology Stack

<div align="center">

**HDL & Design Languages**

![Verilog](https://img.shields.io/badge/Verilog-0D1230?style=flat-square&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-0D1230?style=flat-square&logoColor=white)

<br>

**Synthesis, Verification & Sign-Off**

![Design Compiler](https://img.shields.io/badge/Synopsys%20Design%20Compiler-1A1A3E?style=flat-square)
![VCS](https://img.shields.io/badge/Synopsys%20VCS-1A1A3E?style=flat-square)
![PrimeTime](https://img.shields.io/badge/PrimeTime-1A1A3E?style=flat-square)
![Formality](https://img.shields.io/badge/Formality-1A1A3E?style=flat-square)
![ModelSim](https://img.shields.io/badge/ModelSim-1A1A3E?style=flat-square)

<br>

**Analog & Custom IC**

![Cadence Virtuoso](https://img.shields.io/badge/Cadence%20Virtuoso-1A1A3E?style=flat-square)
![Spectre](https://img.shields.io/badge/Spectre%20Simulator-1A1A3E?style=flat-square)
![DRC/LVS](https://img.shields.io/badge/DRC%20%2F%20LVS-1A1A3E?style=flat-square)

<br>

**FPGA Prototyping & Scripting**

![Quartus Prime](https://img.shields.io/badge/Intel%20Quartus%20Prime-1A1A3E?style=flat-square)
![DE2-115](https://img.shields.io/badge/DE2--115%20FPGA-1A1A3E?style=flat-square)
![TCL](https://img.shields.io/badge/TCL%20Scripting-1A1A3E?style=flat-square)
![Python](https://img.shields.io/badge/Python-1A1A3E?style=flat-square&logo=python&logoColor=3776AB)

</div>

---

## ⬡ &nbsp;GitHub Activity

<div align="center">


<img height="175" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=zaileshar&layout=compact&hide_border=true&bg_color=0D1230&title_color=7986CB&text_color=C5CAE9&langs_count=6"/>

</div>

---

## ⬡ &nbsp;Projects & Work

Code and experiments are on GitHub. For the full picture — design documentation, schematic walkthroughs, simulation results, synthesis reports — most of that lives on my portfolio site since it doesn't fit well in a repo.

<div align="center">

<br>

<a href="https://zaileshar.github.io/">
  <img src="https://img.shields.io/badge/Open%20Portfolio%20%E2%86%92%20Detailed%20Designs%20%26%20Results-5C4AE4?style=for-the-badge&logoColor=white"/>
</a>

<br>

</div>

---

<div align="center">

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=120&section=footer&text=Still+figuring+it+out.+One+synthesis+report+at+a+time.&fontSize=13&color=0:5C4AE4,100:7986CB&fontColor=C5CAE9&animation=fadeIn&fontAlignY=60"/>

</div>
