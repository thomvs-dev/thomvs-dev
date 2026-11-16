<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=680&lines=hey%2C+I'm+Thomas+%F0%9F%91%8B;I+draw+tiny+hearts+on+met5+%E2%9D%A4%EF%B8%8F;DRC+0.+LVS+match.+life+is+good.;making+SRAM+do+the+math+%F0%9F%A7%AE" alt="typing intro" />
</p>

<p align="center">
  <img src="https://media1.tenor.com/m/hoXoG1Wm_FcAAAAC/hi-dog.gif" height="130" alt="hi dog" />
</p>

### 🧠 about me

- 🎓 ECE undergrad at **IIIT Naya Raipur** ('28), here for the chips
- 🔬 research intern at **NYCU, Taiwan**: RRAM-based analog matrix computing for massive-MIMO signal processing (in-memory computing, IR drop, ADC bottlenecks, the fun stuff)
- 📡 FPGA design intern at **Mantiswave Networks**: building an Artix-7 + AD9361 SDR, LVDS I/Q datapaths, clock-domain crossings, board bring-up
- 🛰️ previously: FPGA radar signal processing at **DRDO**, COMSOL + energy-harvesting sensor networks at **IIIT Allahabad**
- 📝 first paper (HEART-CH) under review at IEEE Internet of Things Journal
- 🔭 into: in-memory computing, low-power VLSI, RISC-V, domain-specific accelerators, RTL-to-GDS
- 🏆 PM Sarvottam Trophy scholar, and won an industry-academia meet pitching my FPGA ECG accelerator

### 🚀 latest builds

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/thomvs-dev/snn-ecg-asic"><img src="https://raw.githubusercontent.com/thomvs-dev/snn-ecg-asic/main/docs/chip_art.png" alt="SNN ECG chip layout" width="100%" /></a>
      <h3><a href="https://github.com/thomvs-dev/snn-ecg-asic">🫀 snn-ecg-asic</a></h3>
      A spiking neural net that classifies heartbeats, taken from RTL to a routed <b>SKY130</b> layout with OpenROAD. Yes, there's a heart engraved on met5.
      <br><br>
      ⚡ clock gating took idle power from <b>5.68 mW → 0.7 µW</b><br>
      ✅ DRC 0 · LVS match · timing clean at TT/ff/ss<br>
      📐 494 × 494 µm, 15.7k cells, 25 MHz
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/thomvs-dev/larp"><img src="https://raw.githubusercontent.com/thomvs-dev/larp/main/figures/headline.png" alt="SRAM CIM energy per token" width="100%" /></a>
      <h3><a href="https://github.com/thomvs-dev/larp">🧮 SRAM CIM LLM simulator</a></h3>
      What if the memory did the multiply-adds? Runs real HuggingFace LLMs (Qwen2.5, TinyLlama, OPT, GPT-2) on simulated SRAM compute-in-memory and reports accuracy <i>and</i> energy per token.
      <br><br>
      🎯 6-bit ADC matches 8-bit digital perplexity<br>
      🔋 2.1× less compute energy than a digital INT8 datapath<br>
      🧪 validated against ASiM, 3 silicon macros, AccelForge
    </td>
  </tr>
</table>

### 🛠️ more stuff I've made

| | project | the vibe |
|---|---|---|
| 🧩 | [**riscv_single**](https://github.com/thomvs-dev/riscv_single) | my own RISC-V CPU, because every chip person has to build one |
| 🌉 | [**amba-bus-bridge-verilog**](https://github.com/thomvs-dev/amba-bus-bridge-verilog) | AHB ➡️ APB bridge. buses talking to buses |
| 💬 | [**uart_rx_tx**](https://github.com/thomvs-dev/uart_rx_tx) | UART from scratch. the "hello world" of talking to hardware |
| 🦇 | [**fpga_ultrasonic_sensor_interfacing**](https://github.com/thomvs-dev/fpga_ultrasonic_sensor_interfacing) | the FPGA learns echolocation |
| 🌡️ | [**fpga_DHTsensor_interfacing**](https://github.com/thomvs-dev/fpga_DHTsensor_interfacing) | asking a sensor how humid it is, one bit at a time |

### 🧰 my toolbox

**chip design:** `Verilog` · `SystemVerilog` · `Yosys` · `OpenROAD` · `OpenLane` · `Magic` · `Netgen` · `KLayout` · `Sky130` · `Cadence Virtuoso`<br>
**FPGA:** `Vivado` · `Vitis` · `ModelSim` · `Icarus` · `GTKWave` · Zynq-7020 · Kintex-7 · Artix-7<br>
**everything else:** `Python` · `C/C++` · `Tcl` · `PyTorch` · `MATLAB` · `COMSOL` · `KiCad`

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,c,cpp,pytorch,matlab,linux,git&perline=7" alt="skills" />
</p>

### 📈 commit activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=thomvs-dev&theme=github-compact&hide_border=true&area=true" alt="activity graph" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/thomvs-dev/thomvs-dev/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/thomvs-dev/thomvs-dev/output/github-snake.svg" alt="snake eating my contributions" />
  </picture>
</p>

### 🐛 current status

```
$ make signoff
[INFO]  synthesis ............ ok
[INFO]  place & route ........ ok
[INFO]  DRC .................. 0 violations 🎉
[INFO]  LVS .................. match
[WARN]  thomas ............... "one more clock gate and I'll sleep"
```

### 📫 say hi

<p align="left">
  <a href="mailto:thomas24101@iiitnr.edu.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/thomas-sajeev-varghese-351384329/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><i>"Simple can be harder than complex." — Steve Jobs<br>(he never had to close timing at the ss corner)</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=gradient" width="100%" alt="" />
</p>
