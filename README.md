<div align="center">

# André Alves

### Control & Automation Engineering — UFPE

**Automation + Software + Data + Decision**

Industrial control (PLC/SCADA), full-stack software, and applied AI — built to solve
real problems on real machines, not just on a whiteboard.

[![Email](https://img.shields.io/badge/Email-andre.alves2aandrade%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andre.alves2aandrade@gmail.com)

</div>

---

## About

I work across the full stack of an automated system: the PLC logic and field wiring on
the shop floor, the SCADA/HMI and backend services that talk to it, and the software —
sometimes AI-assisted — that turns that data into something a person can act on.

Most of the projects below came out of real industrial and business problems: a machine
that needed a control system, a client that needed their process monitored, a team that
needed a tool that didn't exist yet. A few are personal projects built solo, end to end.

Every repository here has been reviewed and sanitized for public sharing — real client
data, credentials, and third-party personal information are removed or replaced with
placeholders before publication. Where a repository documents work done as part of a
team (frequently the case in Junior Enterprise / academic team projects, where Git
history doesn't always reflect who did what), that is stated plainly in the repo's own
README rather than glossed over.

## Focus areas

- 🏭 **Industrial automation** — PLC programming (Rockwell Studio 5000 / Structured Text,
  Siemens S7), SCADA/HMI (Elipse E3, FactoryTalk View), EtherNet/IP integration
- 🪞 **Digital twins & simulation** — real-time 3D synchronization with physical PLCs,
  Python-based process simulation frameworks
- 🔌 **Embedded & IoT** — ESP32/MicroPython, BLE, RFID/NFC, GPIO/I2C/serial hardware
  integration
- 🌐 **Backend & full-stack** — REST APIs (Node.js/Express), React frontends, Electron
  desktop apps, Android (Kotlin + Compose)
- 🤖 **Applied AI** — multi-provider LLM orchestration, AI-assisted workflow automation
- 📊 **Data & reporting** — automated report/document generation, anomaly detection,
  decision-support dashboards

## Featured projects

| | |
|---|---|
| **[ascendos-personal-assistant](https://github.com/2A-alves/ascendos-personal-assistant)** | Android personal assistant (Kotlin + Jetpack Compose) with a multi-provider LLM backend (Gemini/Groq/Cerebras/Mistral/OpenRouter). Solo project, full multi-module architecture. |
| **[factory-simulation-library](https://github.com/2A-alves/factory-simulation-library)** | Python framework for simulating industrial processes, with a physical three-phase-separator model, 134 automated tests, and real PLC integration. Solo project. |
| **[industrial-digital-twin](https://github.com/2A-alves/industrial-digital-twin)** | Unity 3D digital twin synced in real time with a physical PLC over EtherNet/IP (`libplctag`). |
| **[rockwell-plc-unwinder-control](https://github.com/2A-alves/rockwell-plc-unwinder-control)** | Complete Rockwell Studio 5000 + FactoryTalk View project for a real fiber-unwinding machine — full controller logic, HMI, and recipe system, published in full with the original client's authorization. |
| **[warehouse-rfid-locker-system](https://github.com/2A-alves/warehouse-rfid-locker-system)** | UHF RFID / NFC smart-locker system: embedded hardware integration, REST API, React frontend. |

## All projects

### Industrial automation, PLC & SCADA

| Project | Description |
|---|---|
| [industrial-digital-twin](https://github.com/2A-alves/industrial-digital-twin) | Unity 3D digital twin synced with a physical PLC over EtherNet/IP |
| [factory-simulation-library](https://github.com/2A-alves/factory-simulation-library) | Industrial process simulation framework in Python, with real PLC integration |
| [rockwell-plc-unwinder-control](https://github.com/2A-alves/rockwell-plc-unwinder-control) | Rockwell Studio 5000 + FactoryTalk View control project for a fiber-unwinding machine |
| [s7-ethernet-plc-driver](https://github.com/2A-alves/s7-ethernet-plc-driver) | C#/.NET driver for Siemens S7 PLCs over EtherNet/IP |
| [coil-winding-recipe-manager](https://github.com/2A-alves/coil-winding-recipe-manager) | Desktop recipe editor/sender for a coil-winding machine's Rockwell PLC |
| [hipervisorio-case-study](https://github.com/2A-alves/hipervisorio-case-study) | SCADA (Elipse E3) case study: EV-charging microgrid supervisory system |

### Embedded, IoT & hardware integration

| Project | Description |
|---|---|
| [warehouse-rfid-locker-system](https://github.com/2A-alves/warehouse-rfid-locker-system) | UHF RFID / NFC smart-locker system: hardware, REST API, React frontend |
| [esp32-ble-indoor-positioning](https://github.com/2A-alves/esp32-ble-indoor-positioning) | Indoor positioning via ESP32 BLE-RSSI anchors + Python trilateration service |
| [smart-coffee-station](https://github.com/2A-alves/smart-coffee-station) | Self-service coffee machine automation: ESP32 firmware, Node.js backend, React frontend |
| [smart-home-automation](https://github.com/2A-alves/smart-home-automation) | Home automation: Node.js backend + ESP32 device controller |

### Applied AI

| Project | Description |
|---|---|
| [ascendos-personal-assistant](https://github.com/2A-alves/ascendos-personal-assistant) | Android assistant (Kotlin + Compose) with a multi-provider LLM backend |
| [jarvis-media-pipeline](https://github.com/2A-alves/jarvis-media-pipeline) | AI-assisted video editing automation: indexing, cut-plan generation, Premiere Pro export |

### Business apps, ERP & reporting

| Project | Description |
|---|---|
| [avante-erp-platform](https://github.com/2A-alves/avante-erp-platform) | Case study: production ERP with access control, RTSP camera streaming, AI-assisted workflows |
| [trade-erp-desktop](https://github.com/2A-alves/trade-erp-desktop) | Electron + React desktop ERP: customers, suppliers, contracts, invoicing |
| [pos-consultation-mobile-app](https://github.com/2A-alves/pos-consultation-mobile-app) | React Native / Expo app: QR-code product scanning + quote/proforma generation |
| [asset-tracking-system](https://github.com/2A-alves/asset-tracking-system) | Full-stack asset checkout/tracking demo |
| [power-monitoring-report-generator](https://github.com/2A-alves/power-monitoring-report-generator) | Python/pandas pipeline for electrical power-monitoring: anomaly detection, charts, LaTeX reports |
| [proforma-pdf-generator](https://github.com/2A-alves/proforma-pdf-generator) | Node.js library for generating proforma/order PDF documents |

### Utilities

| Project | Description |
|---|---|
| [engineering-labs](https://github.com/2A-alves/engineering-labs) | Collection of smaller engineering utilities: team diary, dashboards, QR label generators |

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=flat-square&logo=unity&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Rockwell Automation](https://img.shields.io/badge/Rockwell-Studio%205000-CC0000?style=flat-square)
![Siemens S7](https://img.shields.io/badge/Siemens-S7-009999?style=flat-square)
![Elipse E3](https://img.shields.io/badge/Elipse-E3-005A9C?style=flat-square)

## Contact

📧 [andre.alves2aandrade@gmail.com](mailto:andre.alves2aandrade@gmail.com)
