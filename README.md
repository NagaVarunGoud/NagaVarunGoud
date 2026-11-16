<div align="center">

# Hi there, I'm D. Naga Varun Goud 👋
### Embedded Software Engineer | Linux System Programming & C Firmware | ARM Architecture

[![LinkedIn](https://img.shields.io/badge/LinkedIn-naga--varun--goud-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/naga-varun-goud)
[![GitHub](https://img.shields.io/badge/GitHub-NagaVarunGoud-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NagaVarunGoud)
[![Email](https://img.shields.io/badge/Email-nagavarun.goud.23%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nagavarun.goud.23@gmail.com)
[![Location](https://img.shields.io/badge/Location-Hyderabad%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Hyderabad)

</div>

---

### 👨‍💻 Profile Summary

Embedded Software Engineer with hands-on experience developing **C firmware**, **Linux system programming**, and **peripheral drivers** for ARM-based microprocessors and microcontrollers in embedded Linux environments. Currently working as an **R&D Engineer at HBL Engineering Limited**, focusing on hardware–software co-design, peripheral protocol validation, and system integration.

- 🔭 **Current Role:** R&D Engineer at **HBL Engineering Limited** (Embedded C & Linux system-level programs for ARM platforms).
- 🎓 **Education:** B.Tech in Electronics and Communication Engineering (ECE) — HITAM (CGPA: 8.05 / 10.0, 2022–2026).
- ⚙️ **Core Focus:** ARM Cortex-A & Cortex-M, Bare-Metal register-level programming, Linux Device Trees, Buildroot BSPs, and CAN-FD / LPUART / SPI / I2C bus interfaces.
- 📜 **Research:** Co-author of *Analysis of BPSK and QPSK Modulation in AWGN and Rayleigh Fading Channels with Path Loss*.

---

### 🛠️ Technical Skills

| Domain | Technologies & Platforms |
| :--- | :--- |
| **Languages** | Embedded C, C++, Python, Verilog HDL, MATLAB, Bash, JavaScript |
| **Architectures & Processors** | ARM Cortex-A55, ARM Cortex-M33, ARM Cortex-M4F, NXP i.MX93, NXP MCX-E247, ESP32, ESP8266, Raspberry Pi, Arduino |
| **Embedded & Systems Concepts** | Linux System Programming, Register-Level Programming, Peripheral Driver Development, Interrupt-Driven Design, Zero-Heap Deterministic Execution |
| **Embedded Linux & BSP** | Buildroot (`BR2_EXTERNAL`), Linux Device Trees, eMMC Production Images, NXP UUU (Universal Update Utility), Weston/Wayland, Qt6 C++ (DMI) |
| **Protocols & Peripherals** | CAN-FD (SocketCAN @ 2 Mbps), LPUART, UART, SPI, I2C, GPIO, PDM Audio |
| **EDA, Debugging & Tools** | NXP LinkServer (MCU-Link CMSIS-DAP), GDB, Logic Analyzers, Intel Quartus Prime, Git, Linux |

---

### 💼 Professional Experience

#### **R&D Engineer — HBL Engineering Limited, Hyderabad** *(July 2026 – Present)*
- Developing embedded C software and Linux system-level programs for ARM-based microprocessor and microcontroller platforms.
- Architecting and validating peripheral drivers and system integration in a Linux-based environment.

#### **R&D Intern — HBL Engineering Limited, Hyderabad** *(Jan 2026 – July 2026)*
- Configured and validated **UART**, **I2C**, **SPI**, and **GPIO** interfaces for deterministic peripheral data transfer through hardware–software co-design.
- Conducted hardware debugging and serial communication troubleshooting across ARM architectures.

---

### 🚀 Key Projects

#### **Embedded Systems & Firmware Architecture**

- **NXP FRDM-i.MX93 Embedded Linux Platform**
  *ARM Cortex-A55/M33 • Buildroot • C++ • Qt6 • CAN-FD • LPUART*
  - Engineered a reproducible Buildroot external tree (`BR2_EXTERNAL`) for NXP i.MX93, tailoring Device Tree nodes for industrial LPUART and PDM audio, and generating automated eMMC production images.
  - Validated hardware peripheral interfaces including bidirectional LPUART loopback and CAN-FD (SocketCAN @ 2 Mbps); automated board flashing pipelines using NXP Universal Update Utility (UUU).
  - Integrated a low-latency Weston/Wayland display stack and cross-compiled a Qt6 C++ Driver Machine Interface (DMI) with deterministic pre-rendered asset blitting for zero-flicker telemetry.

- **NXP FRDM-MCX-E247 Bare-Metal Interrupt & GPIO Framework**
  *ARM Cortex-M4F • Bare-Metal C • NVIC • Register-Level GPIO • LinkServer/GDB*
  - Designed a deterministic, bare-metal NVIC interrupt management layer and atomic multi-pin PORT dispatcher in embedded C with zero dynamic heap allocation.
  - Developed register-level GPIO driver abstractions manipulating hardware registers (`PDDR`, `PDIR`, `PSOR`, `PCOR`) with edge-triggered interrupts and atomic status flag clearing (`ISFR`).
  - Automated target flashing and interactive GDB debugging pipelines via NXP LinkServer (MCU-Link CMSIS-DAP) to validate ISR latency and non-blocking event handling.

#### **Open Source & Hardware Telemetry Projects**

- 🤟 **[Gesture-to-Speech (G2S) Assistive System](https://github.com/NagaVarunGoud/g2s_project)**
  *Python • MediaPipe • Scikit-learn (SVM) • Text-to-Speech*
  - Real-time gesture recognition engine extracting hand landmarks from live camera video using MediaPipe and classifying gestures via an SVM classifier with multilingual TTS speech synthesis.

- 🌤️ **[Wireless Weather Monitoring System](https://github.com/NagaVarunGoud/Wireless-Weather-Monitoring-System)**
  *ESP8266 • DHT11 • Flask • Wi-Fi Telemetry • Twilio SMS*
  - IoT weather station capturing real-time environmental data sent over Wi-Fi to a Flask backend with live telemetry dashboard and automated threshold SMS alerts.

- 💨 **[Real-Time Dust Monitoring System](https://github.com/NagaVarunGoud/Dust-Monitoring-System)**
  *Arduino • Flask • Socket.IO • WebSockets*
  - Microcontroller-driven particulate matter monitoring platform featuring real-time WebSocket telemetry, historical logs, and threshold alarm indicators.

- 🎛️ **[Dynamic Noise Filtration & FPGA DSP Pipeline](https://github.com/NagaVarunGoud/Dynamic-Noise-Filtration)**
  *MATLAB • Digital Signal Processing (DSP) • FPGA Coefficient Export*
  - FIR and IIR digital filter design in MATLAB for dynamic noise removal with coefficient export ready for hardware FPGA implementation.

- ⚡ **[4-Bit Bidirectional Shift Register](https://github.com/NagaVarunGoud/verilog-bidirectional-shift-register)**
  *Verilog HDL • Digital VLSI • Testbench Simulation*
  - Verilog HDL implementation of a 4-bit bidirectional shift register with modular verification testbench.

---

### 📄 Research & Publications

- **Analysis of BPSK and QPSK Modulation in AWGN and Rayleigh Fading Channels with Path Loss** *(Co-Author)*
  - Simulated digital modulation schemes in MATLAB to evaluate bit error rate (BER) performance and robustness across AWGN and multipath fading channels.

---

### 📊 GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NagaVarunGoud&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NagaVarunGoud&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>© D. Naga Varun Goud • Embedded Software Engineer</sub>
</div>
