<div align="center">

# Hi, I'm Mohamed Amine Hamdi 👋

### Embedded Systems & Edge AI Engineer · Computer Vision · IoT · TinyML · Robotics

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=2E9EF7&center=true&vCenter=true&width=650&lines=Building+real-time+CV+%26+ML+systems+on+microcontrollers;ESP32+%7C+STM32+%7C+Raspberry+Pi+%7C+FPGA;TinyML+%7C+Edge+AI+%7C+Embedded+Linux+%7C+ROS;Highest+Honors+Graduate+%E2%80%93+ISSATSO%2C+Tunisia)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-amine-hamdi-26358127b)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Hammah1msi@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohameedhamdii)
![Profile Views](https://komarev.com/ghpvc/?username=mohameedhamdii&color=2E9EF7&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🧭 About Me

- 🎓 Highest-Honors (*Mention Très Bien*) graduate in **Electronics, Electrotechnics & Automation — Embedded Systems specialization**, ISSATSO, Université de Sousse (2023–2026)
- 🔧 I build **real-time computer vision, IoT, and machine-learning systems** on microcontrollers, single-board computers, and FPGAs — ESP32, STM32, Raspberry Pi, Arty A7
- 🧪 Three years across a research lab, an industrial engineering team, and independent builds: embedded C/C++, model training & quantization, REST API / mobile integration
- 🇩🇪 Currently preparing applications for **Master's programs in Germany** in embedded systems / IoT engineering
- 🌍 Based between Sidi Bouzid and Sousse, Tunisia
- ⚡ Every project below ships with real verification — GHDL testbenches, golden-reference Python-vs-firmware equivalence checks, 184/184 automated tests, cryptographic OTA-rejection tests

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,arduino,raspberrypi,linux,git,docker&theme=dark" />
</p>
<p align="left">
  <img src="https://skillicons.dev/icons?i=tensorflow,opencv,pytorch,flask,react,fastapi,postgres,ros&theme=dark" />
</p>

| Category | Skills |
|---|---|
| **Embedded** | C, C++, ESP32 / ESP32-CAM, ESP-IDF, STM32, Arduino, Raspberry Pi, FreeRTOS, Embedded Linux |
| **AI / ML / CV** | Python, TensorFlow / Keras, LiteRT Micro, ONNX, YOLOv8, OpenCV, MediaPipe, CNNs, int8 Quantization, Generative AI |
| **Edge, IoT & FPGA** | TinyML, Edge AI, MQTT, RFID, Sensor Networks, VHDL, FPGA (Vivado), GHDL, FFT / DSP, ROS |
| **Software** | Flask REST API, React / React Native, Git, Linux, KiCad, Blender 3D, PLC Basics |

---

## 🚀 Featured Projects

*(Full source lives in my pinned repositories below.)*

### 🌱 SERRE.AI — Smart Agricultural Greenhouse
**Final-year engineering project (PFE), LATIS Laboratory, ENISo** · *Jan – Jun 2026*
A complete IoT system for smart greenhouse management, combining embedded hardware, computer vision, and AI-driven automation.
- Raspberry Pi 4B + ESP32-CAM on a motorized bi-angular camera rail for crop monitoring
- On-device plant-disease detection: ResNet9 (ONNX) — **95.8% accuracy across 38 classes**, PlantVillage dataset
- YOLOv8 growth-stage detection · XGBoost actuator control · IsolationForest anomaly detection · GDD/DLI harvest prediction
- Flask REST API (43 endpoints), React Native mobile app, real-time 3D digital twin in Blender
- **184/184 automated tests passed** — supervised by Dr. Hatem Garrab & Mrs. Asma Ben Rhouma, with Mohamed Aziz Kadri

`Python` `Flask` `ESP32-CAM` `YOLOv8` `ResNet9` `React Native` `Blender`

### 🚗 Edge-Deployed Driver Drowsiness & Distraction Detector
EU ADDW-compliant, fully offline Driver Monitoring System running at 10+ FPS on a Raspberry Pi 4 — a custom dual-head CNN for drowsiness, MediaPipe gaze tracking, YOLOv8 phone/seatbelt detection, and real-time rPPG heart-rate monitoring. Privacy-by-design (no raw data logging), with a live Streamlit analytics dashboard.

`Python` `OpenCV` `YOLOv8` `MediaPipe` `Edge Computing`

### 🦾 Natural-Language-Controlled 6-DOF Robot Arm
A Vision-Language-Action system that drives a 6-DOF arm from plain-language commands (*"pick up the red block, place it on the blue mat"*) — computer vision for perception, an on-device LLM for task planning, and analytical inverse kinematics for motion. Deployable on Raspberry Pi 5 + ROS 2, or as a standalone simulator with a live web dashboard.

`Python` `ROS 2` `FastAPI` `OpenCV` `YOLOv8` `Inverse Kinematics` `LLM Integration`

### 🦯 Scene Narrator — Accessible AI Wearable
A battery-powered wearable that narrates surroundings and reads text aloud for visually impaired users — fully offline, no cloud. On-device vision-language model + OCR + offline TTS with bone-conduction audio. Dual firmware (ESP32-P4 + Raspberry Pi Zero 2 W) with custom power management delivering **4–8 hours of runtime** on a 2000 mAh battery.

`ESP-IDF` `C/C++` `Python` `TFLite` `On-Device AI` `Hardware Design`

### 🏭 TinyML Defect Detector — Edge AI + Fleet OTA System
Real-time defect classification on ESP32-S3 (LiteRT Micro), fully offline, extended into a fleet-management system: mTLS device provisioning, an MQTT broker with per-device topic isolation, and a signed OTA pipeline (canary → fleet-wide rollout, automatic rollback on failed self-test). FastAPI + PostgreSQL backend and React dashboard for live fleet telemetry — verified end-to-end, including a live test confirming a **tampered firmware image is cryptographically rejected**.

`ESP-IDF` `FastAPI` `PostgreSQL` `MQTT (Mosquitto)` `React` `Docker`

### 🔍 TinyML Industrial Defect Detector — Edge AI on ESP32-S3
The core edge-AI pipeline: camera capture → preprocessing → on-device inference → actuation, zero network dependency. Trained and quantized a depthwise-separable CNN to int8 (benchmarked against MobileNetV2 transfer learning), with a golden-reference methodology verifying bit-exact equivalence between the Python and on-device pipelines.

`Python` `TensorFlow/Keras` `ESP-IDF` `FreeRTOS` `LiteRT Micro`

### 🚘 CAN/UDS Vehicle Diagnostic Scanner
A real-time diagnostic tool that reads live engine data and parses Diagnostic Trouble Codes from raw CAN frames — ISO-TP, OBD-II, and UDS implemented from scratch. Includes a simulated vehicle ECU in Python for CI/CD, an ESP32 hardware implementation in C, and a responsive web UI for telemetry.

`Python` `C` `ESP32` `CAN Bus` `UDS` `OBD-II`

### 📳 Vibration Anomaly Detector — FPGA Signal Processing
A full VHDL RTL pipeline targeting the Digilent Arty A7-35T: signal conditioning, 1024-point FFT, magnitude/band-energy extraction, baseline calibration, and anomaly detection with UART reporting. Verified with a GHDL-based bit-exact testbench against a Python golden-reference model.

`VHDL` `Vivado` `GHDL` `FFT/DSP`

**Other builds:** STM32 autonomous car · Arduino solar tracker · RFID + keypad smart lock

---

## 💼 Experience

| Role | Organization | Period |
|---|---|---|
| Research Intern | LATIS Laboratory, ENISo, Sousse | Jan – Jun 2026 |
| Embedded Systems Intern | COALA Group, Sidi Bouzid | Jun – Aug 2024 |
| Industrial Electronics Intern | Margarette Steiff, Sidi Bouzid | Jul – Aug 2023 |

- **LATIS Laboratory** — Trained a ResNet9 model to 95.8% accuracy (38 classes) on Roboflow-annotated plant-disease data; deployed the greenhouse IoT sensor network and AI inference pipeline.
- **COALA Group** — Delivered embedded automation projects end-to-end, from hardware debugging to firmware integration.
- **Margarette Steiff** — Hands-on exposure to factory automation, PLCs, and production-line sensor systems.

---

## 🎓 Education

- **Licence Appliquée — Electronics, Electrotechnics & Automation** (Embedded Systems specialization)
  ISSATSO — Institut Supérieur des Sciences Appliquées et de Technologie de Sousse, Université de Sousse · 2023–2026 · Highest Honors (*Mention Très Bien*)
- **Baccalauréat, Sciences Techniques** · 2023

---

## 📜 Certifications

| Certification | Issuer | Issued |
|---|---|---|
| Python Essentials 2 | Cisco | Sep 2026 |
| Python Essentials 1 | Cisco | Sep 2026 |
| Introduction to Generative AI | Google | Aug 2026 |
| Introduction to IoT | Cisco | Aug 2026 |
| Getting Started with AI on Jetson Nano | NVIDIA | Jun 2026 |
| Deep Learning Fundamentals | NVIDIA | 2025 |
| AI for Business Professionals | HP LIFE | — |
| Strategic Planning in the AI Age | HP LIFE | — |
| A Beginner's Guide to Open Source Software Development (LFD102) | The Linux Foundation | — |
| Code Foundation for ROS | The Construct Robotics Institute | Oct 2024 |

*Credential IDs — Generative AI: `26797054` · LFD102: `LF-ntwi0muuiz` · ROS: `RIAC5B41F62294E`*

---

## 🌐 Languages

| Language | Level |
|---|---|
| Arabic | Native |
| French | Fluent (C1) |
| English | Intermediate (B1) |
| German | Elementary (A2) |

---

## 📊 GitHub Stats

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=mohameedhamdii&show_icons=true&theme=dark&hide_border=true" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohameedhamdii&layout=compact&theme=dark&hide_border=true" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=mohameedhamdii&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

---

<div align="center">

📫 Open to embedded systems / edge AI roles and Master's opportunities in Germany — reach out on [LinkedIn](https://www.linkedin.com/in/mohamed-amine-hamdi-26358127b) or by [email](mailto:Hammah1msi@gmail.com).

</div>
