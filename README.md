# 🤖 ASTRA MVP – Autonomous Smart Tech Robotic Assistant (MVP)

A powerful, emotion-aware mobile assistant robot built for real-world intelligence, research, interaction, and multi-domain AI applications.

## 🌟 Vision

**ASTRA (Autonomous Smart Tech Robotic Assistant)** is designed to be a modular, scalable robotic system combining computer vision, real-time ML, intelligent mobility, and emotional intelligence to interact with the physical world in an intuitive, human-centered way.

The MVP serves as a proof-of-concept platform for robotics + AI/ML + embedded systems + HCI research and innovation.

---

## 🔩 Hardware Overview

| Component | Description |
|----------|-------------|
| **Main Controller** | NVIDIA Jetson Orin Nano Super (8-core ARM Cortex + 20 TOPS AI) |
| **Support Boards** | Raspberry Pi 5 (Sensor I/O & lightweight ML), Arduino Mega (actuators), ESP32 (wireless, BLE, sensor fusion) |
| **Camera** | Intel RealSense D435i (Depth + RGB) |
| **Lidar** | RPLidar A1/A2 (for mapping & navigation) |
| **Display** | 64x64 LED Matrix or OLED screen for Emotion UI |
| **Mobility** | 2WD or 4 Omni-wheel base (with geared motors + motor drivers) |
| **Sensors** | Ultrasonic, IMU (MPU6050), IR, ToF, GPS, Compass |
| **Connectivity** | GSM module (SIM800L), WiFi (ESP32 + Jetson), GPS (Neo6M) |
| **Power System** | 12V Li-ion battery (8000–10000mAh), 5V and 3.3V regulators |
| **Chassis** | 3D printed + lightweight aluminum/ABS custom frame |
| **Optional** | 6-DOF Robotic Arm (MG996R / Dynamixel motors) |

---

## 💸 Estimated BOM (₹ INR)

| Item                        | Approx. Cost |
|-----------------------------|--------------|
| Jetson Orin Nano Super      | ₹25,000–28,000 |
| Raspberry Pi 5              | ₹7,000 |
| Arduino Mega + ESP32        | ₹1,500 |
| Intel RealSense D435i       | ₹15,000–20,000 |
| RPLidar A1                  | ₹10,000 |
| GSM + GPS Modules           | ₹1,500 |
| Emotion Display (LED/OLED)  | ₹2,000 |
| Motors + Wheels + Drivers   | ₹4,000–6,000 |
| Battery + BMS + Power Mgmt  | ₹3,500–4,500 |
| Chassis & Structure         | ₹8,000–10,000 |
| Misc Sensors, Wiring, PCB   | ₹3,000 |
| **Total**                   | **₹90,000–1,30,000** |

**About : 1,50,000 INR **

---

## 💻 Software Stack

| Layer | Tools / Languages / Frameworks |
|-------|-------------------------------|
| **OS & Middleware** | Ubuntu 20.04 LTS (Jetson), Raspberry Pi OS |
| **Languages** | Python, C++, Bash, Arduino (C), JavaScript (web UI) |
| **AI/ML** | PyTorch, TensorFlow Lite, OpenCV, YOLOv8, ONNX |
| **Robotics** | ROS2 Foxy, RPLidar SDK, Jetson GPIO |
| **CV & Perception** | RealSense SDK, DepthAI, MediaPipe |
| **Voice Control** | Vosk / Whisper / Google STT |
| **Emotion Engine** | Custom expression-to-LED rendering logic |
| **Cloud/Comms** | MQTT, WebSocket, GSM API, GPS tracker |
| **Web UI (Optional)** | Flask / Node.js dashboard for remote monitoring |

---

## 🧠 Core Features

- ✅ Real-time Object Detection & Tracking (YOLOv8)
- ✅ Emotion Display System (LED Matrix)
- ✅ Voice Command Execution (offline-capable)
- ✅ Mobility & Navigation with Lidar & Depth Cam
- ✅ Environment Mapping & Obstacle Avoidance
- ✅ Sensor Fusion with IMU + GPS + GSM
- ✅ ROS2 Integration for modular system design
- ✅ Data logging, remote diagnostics (via web dashboard)
- ✅ Modular design (sensor/arm additions possible)

---

## 🧬 Design Inspiration

- 🟢 **Wall-E’s** compact & expressive form
- 🔵 **NVIDIA's humanoid research robot (GTC 2025)** for futuristic, emotion-aware presence
- ♻️ Designed for modularity, extensibility & research-grade experimentation

---

## 📏 Dimensions

| Part           | Size (approx) |
|----------------|---------------|
| Height         | 60 cm |
| Width          | 35 cm |
| Depth          | 30 cm |
| Wheel Base     | 25–28 cm |
| Emotion Display | 10x10 cm |
| Arm Length (opt) | ~25–30 cm |

---

## 🔬 Research Domains It Touches

- 🤖 Robotics & Mechatronics
- 🧠 AI/ML & Real-time Inference
- 📍 SLAM & Autonomous Navigation
- 👁️ Computer Vision & Emotion Recognition
- 🗣️ Human-Robot Interaction (HRI)
- 🌍 Edge Computing & IoT Fusion
- 🧩 Multi-Agent Coordination (future expansion)

---

## 🎯 Future Goals

- Integrate GPT-4 Vision or LLaVA-style perception models
- Add autonomous path planning & swarm logic
- Upgrade to custom-built PCB for cleaner internals
- Publish white paper on ASTRA’s system design
- Open-source ROS2 packages for education/research

---

## 🧑‍🏫 Target Audience

- Professors & Researchers in AI/Robotics
- Labs like MIT CSAIL, Stanford AI Lab, ETH Zurich ASL
- Hackathons, Expo Showcases (e.g., Aero India 2026)
- Open-source robotics & edge-AI community

---

## 🙋‍♂️ Built With ❤️ By

**M4YH3M-DEV**  
🔗 [GitHub](https://github.com/M4YH3M-DEV)  
🧪 BTech '28 | AI/Robotics/OS/LLMs | Building for the Future


