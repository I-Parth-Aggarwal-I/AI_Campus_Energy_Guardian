# ⚡ Energy Guardian

> **AMD Slingshot Hackathon** — AI-Powered Campus Energy Monitoring

<p align="center">
  <img src="https://img.shields.io/badge/status-hackathon-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/built%20with-AMD-76B900?style=for-the-badge" />
  <img src="https://img.shields.io/badge/frontend-vanilla%20js-f7df1e?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/3D-three.js-black?style=for-the-badge&logo=threedotjs" />
</p>

---

## 🚀 What is Energy Guardian?

Energy Guardian is a **real-time AI campus energy monitoring dashboard** that gives facility managers complete visibility over every watt consumed across their campus — zones, buildings, solar panels, grid connections, and more.

No more flying blind. No more surprise electricity bills.

---

## ✨ Features

| Module | Description |
|--------|-------------|
| 🗺️ **3D Campus Map** | Interactive WebGL view of campus buildings. Left-drag to rotate, scroll to zoom, click to inspect zones. |
| ⚡ **Live Grid Status** | Real-time voltage & frequency charts with 24-hour history. |
| ☀️ **Solar PV Monitoring** | Rooftop array output, MPPT efficiency, and irradiance tracking. |
| 🏢 **Zone Management** | Per-building load cards with live status indicators. |
| 🔔 **Alert Engine** | Automated anomaly detection and high-load alerts. |
| 🤖 **AI Chatbot** | Ask natural language questions like *"Which zone wastes the most?"* |
| 📊 **Analytics & Reports** | Monthly consumption trends, sustainability scores, downloadable reports. |
| ⚙️ **Settings** | Configurable alert thresholds and notification rules. |

---

## 🏗️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (zero framework dependencies)
- **3D Rendering:** [Three.js r128](https://threejs.org/) — WebGL campus visualization
- **Fonts:** Google Fonts — Rajdhani, Share Tech Mono, Cinzel
- **AI Integration:** Bell-curve demand modelling, ONNX Runtime, Anthropic Claude API (chatbot)
- **AMD Products:** AMD Ryzen AI PC, Radeon GPU (DirectML), NPU (VitisAI / ONNX Runtime)
- **Data Layer:** Local JSON, SQLite, ReportLab (PDF), 5-second live refresh cycle

---

## 📁 Project Structure

```
energy-guardian/
├── energy_guardian.html   # Single-file SPA — the entire app
└── README.md              # This file
```

> Everything runs from a single HTML file — no build step, no dependencies to install.

---

## 🖥️ Running Locally

```bash
# Clone the repo
git clone https://github.com/I-Parth-Aggarwal-I/AI_Campus_Energy_Guardian.git
cd AI_Campus_Energy_Guardian

# Open in browser (macOS)
open energy_guardian.html

# Open in browser (Linux)
xdg-open energy_guardian.html

# Or just double-click the file
```

That's it. No `npm install`. No server. Just open and go.

---

## 📸 Dashboard Tabs

| Tab | What You'll See |
|-----|----------------|
| **Dashboard** | Live demand curve, zone grid, energy mix donut, weekly bar chart |
| **3D Campus** | Rotating WebGL campus model with clickable zones |
| **Grid** | Voltage & frequency charts, grid parameters panel |
| **Solar PV** | Irradiance curve, array status cards |
| **Facilities** | All monitored buildings with manager details |
| **Alerts** | Active incidents with severity tags |
| **AI Chatbot** | Chat interface + quick prompts + live context panel |
| **Reports** | Monthly trends + downloadable report links |
| **Settings** | Notification preferences and alert thresholds |

---

## 🎥 Demo

> 📹 *[Demo Video Link - ](https://youtu.be/-DBfs5aHK_8)https://youtu.be/-DBfs5aHK_8*

---

## 👥 Team

| | |
|--|--|
| **Team Name** | Pixel Pioneers |
| **Team Leader** | Parth Aggarwal |
| **Member** | Aryan Bansal |
| **Member** | Kundan Sahil |
| **Problem Statement** | Educational campuses experience significant energy inefficiencies due to the absence of real-time monitoring, predictive insights, and cost-effective optimization tools.|

---

## 🏆 AMD Slingshot

This project was built for the **AMD Slingshot Hackathon**.

---

## 📄 License

Submitted for hackathon evaluation. © 2025 Energy Guardian Team.

---

## 🙏 Acknowledgements

- [AMD Slingshot](https://www.amd.com/) — for the platform & challenge
- [Three.js](https://threejs.org/) — 3D rendering engine
