<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=hey%2C+I'm+Thomas+%F0%9F%91%8B;I+turn+caffeine+into+Verilog+%E2%98%95%E2%9E%A1%EF%B8%8F%F0%9F%94%8C;it+worked+in+simulation%2C+I+swear;currently+arguing+with+an+AD9361+%F0%9F%93%A1" alt="typing intro" />
</p>

<p align="center">
  <img src="https://media1.tenor.com/m/hoXoG1Wm_FcAAAAC/hi-dog.gif" height="130" alt="hi dog" />
</p>

```verilog
module thomas (
    input  wire coffee,
    input  wire deadline,
    output reg  [7:0] working_rtl
);
    // ECE @ IIIT Naya Raipur, batch of '28
    // status: 1 timing violation away from greatness
    always @(posedge coffee or posedge deadline)
        working_rtl <= working_rtl + 1;  // usually
endmodule
```

### 🧠 about me

- 🎓 ECE undergrad at **IIIT Naya Raipur**, mostly living inside Vivado
- 🔬 research intern at **IIIT Allahabad**: sensor networks, a bit of ML, a lot of COMSOL
- 📡 currently building a **2×2 MIMO SDR from scratch** (Artix-7 + AD9361 + 2.5GbE). the power rails work. the Ethernet link comes up. the radio is... a work in progress
- 🔭 into RISC-V, hardware accelerators, and taking designs all the way from RTL to GDS
- ⚡ fun fact: my Instagram handle is `thomas_alva_edison.exe` and I stand by it

### 🛠️ things I've made blink, compute, or occasionally catch fire

| | project | the vibe |
|---|---|---|
| 🫀 | [**snn-ecg-asic**](https://github.com/thomvs-dev/snn-ecg-asic) | spiking neural net that reads heartbeats, headed for silicon |
| 🧩 | [**riscv_single**](https://github.com/thomvs-dev/riscv_single) | single-cycle RISC-V CPU, because building your own CPU is a rite of passage |
| 🌉 | [**amba-bus-bridge-verilog**](https://github.com/thomvs-dev/amba-bus-bridge-verilog) | AHB ➡️ APB bridge. buses talking to buses |
| 🦇 | [**fpga_ultrasonic_sensor_interfacing**](https://github.com/thomvs-dev/fpga_ultrasonic_sensor_interfacing) | the FPGA learns echolocation |
| 🌡️ | [**fpga_DHTsensor_interfacing**](https://github.com/thomvs-dev/fpga_DHTsensor_interfacing) | asking a sensor how humid it is, one bit at a time |
| 💬 | [**uart_rx_tx**](https://github.com/thomvs-dev/uart_rx_tx) | UART from scratch. the "hello world" of talking to hardware |

### 🧰 my toolbox

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,matlab,linux,git,arduino,raspberrypi&perline=8" alt="skills" />
</p>

`Verilog` · `SystemVerilog` · `Vivado` · `LiteX` · `Yosys` · `OpenROAD` · `OpenLane` · `Magic` · `ngspice` · `Sky130` · `COMSOL`

### 📈 commit activity (powered by caffeine)

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
$ make bitstream
[INFO]  synthesis ............ ok
[INFO]  implementation ....... ok
[WARN]  timing ............... WNS = -0.042 ns 😐
[INFO]  thomas ............... "it's fine, it'll work on the board"
```

### 📫 say hi

<p align="left">
  <a href="mailto:thomas24101@iiitnr.edu.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/thomas-sajeev-varghese-351384329/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.instagram.com/thomas_alva_edison.exe"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>

<p align="center"><i>"Simple can be harder than complex." — Steve Jobs<br>(he never had to close timing on an FPGA)</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=gradient" width="100%" alt="" />
</p>
