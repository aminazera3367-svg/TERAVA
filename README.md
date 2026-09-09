<div align="center">

# 🛡️ Terava — Smart Tourist Safety Monitoring \& Incident Response System

**AI • Geo-Fencing • Blockchain-based Digital ID**

Built for **Smart India Hackathon 2025** · Problem Statement **SIH25002**

Theme: **Travel \& Tourism** · Team **Cognita**

**- Built for SIH 2025**

</div>

\---

## 📌 Overview

Terava is a tourist-safety platform that combines **AI risk prediction**, **Geo-fencing**, and a **Blockchain-backed digital ID** to keep travelers safe and give authorities the tools to respond faster.

Tourists get real-time risk alerts, one-tap SOS, and a tamper-proof digital identity. Government/police teams get a live incident dashboard, heatmaps, and analytics to coordinate emergency response — even in remote or crowded areas where connectivity is unreliable.

## ❓ Problem Statement

> Tourists, especially in unfamiliar or high-risk areas, lack a reliable way to get real-time safety alerts and immediate help during an emergency. Authorities, in turn, lack a unified system to monitor tourist safety, verify identity, and respond quickly to incidents.

Terava addresses this with a hybrid approach: AI-driven risk scanning, ethical/public data analysis, and a secure digital ID — built with privacy and legality at the core.

## ✨ Key Features

### For Tourists

* 🆘 **SOS / Emergency Button** — one-tap alert with live location, confirmation countdown, and auto-notify to emergency contacts and authorities
  
* 🤖 **Proactive SOS with real time data** — AI detects anomalous behaviour and can trigger alerts automatically before a user manually asks for help
  
* 🗺️ **Safety Zone Map** — interactive map (Leaflet) showing safe zones, police stations, hospitals, and live risk areas
  
* 📈 **AI Risk Predictions** — high-risk area prediction, anomaly detection, and crowd-density alerts with confidence scores
  
* 🪪 **Blockchain Digital ID** — tamper-proof, Ethereum-backed tourist registration as an alternative to standard sign-up
  
* 📇 **Emergency Contacts \& Evidence Vault** — manage trusted contacts and attach evidence (photos/files) to incident reports
  
* 🔐 **Multi-Factor Authentication** — email, SMS, and authenticator-app based MFA on login, SOS, and sensitive actions
  
* 🎙️ **Voice Assistant** — voice commands like "Help", "Emergency", "Show Map"
  
* 🌓 **Accessibility** — dark mode and high-contrast theme support
  
* 🔔 **Live Notifications \& Alert Log**

### For Government / Authorities

* 📊 **Live Dashboard** — active incidents, average response time, resolved-today stats
* 🗺️ **Incident Map** — clustering, heatmap view, and filters for real-time situational awareness
* 🚓 **Incident Management** — review, respond to, and resolve tourist-reported incidents
* 🔑 **Secure Government Login** — separate authenticated portal for department access

## 🧠 How It Works

1. Tourists register via a blockchain-secured digital ID (or a simple account) and share trip/itinerary details.
2. The AI engine continuously scores risk using location, crowd density, and behavioural signals, feeding predictions to the map and alert system.
3. If a tourist triggers SOS — or the system detects an anomaly — an alert with live location goes out to emergency contacts and the nearest authorities over a resilient mesh/hybrid network.
4. Authorities track everything from a live dashboard, respond, and log resolution — closing the loop from detection to response.

## 🏗️ Tech Stack

|Layer|Technology|
|-|-|
|**Frontend**|React.js, HTML/CSS, Chart.js|
|**Maps \& Geo-Fencing**|Leaflet, PyDeck|
|**Backend**|Streamlit / Flask|
|**Database**|SQLite|
|**AI/ML**|NumPy, Pandas — Risk Scorer, Behaviour Anomaly Detection, Prediction Batching|
|**Security / Digital ID**|Ethereum Blockchain, Web3.js, Web3Modal, WalletConnect|
|**IoT**|LoRa modules, Smart Bands|
|**Networking**|Hybrid Mesh Network, GSLB (Global Server Load Balancing)|

## 💡 Innovation \& Approach

* **Hybrid approach** — combines ethical security scanning with public-data analysis for risk detection
* **Privacy-first** — strictly follows legal and ethical data-handling rules
* **Unique stack** — integrates AI, blockchain, IoT wearables, and mesh networking in one system
* **Resilience** — mesh networking keeps alerts flowing even in low-connectivity or crowded areas

## 🚧 Feasibility \& Challenges

**Feasible with:** low-energy sensors, GPS, and blockchain-backed digital ID integrated into a wearable device for real-time monitoring and alerts.

**Key challenges:** battery life, connectivity, and security at scale when many users rely on the wearable simultaneously.

**Mitigations:** energy-efficient design, intelligent data sharing, and continuous security hardening.

## 🌍 Impact

|Area|Benefit|
|-|-|
|**Social**|Enhanced safety, reduced crime, peace of mind for tourists and families|
|**Economic**|Boosts tourism confidence and supports local economies|
|**Environmental**|AI-driven monitoring reduces unnecessary patrols and resource waste|
|**Technological**|Drives adoption of smart, secure digital infrastructure|

## 🚀 Getting Started

Currently a single-file front-end prototype.

```bash
git clone <this-repo-url>
cd <repo-folder>
# simply open the app in your browser
open terava\_5.html
```

> ⚠️ Some features (blockchain wallet connect, live maps, voice assistant) require browser permissions (camera, microphone, location) and an internet connection for CDN-hosted libraries (Leaflet, Chart.js, Web3.js).

## 👥 Team — Cognita

Built for **Smart India Hackathon 2025**, Problem Statement ID **SIH25002**, Theme: **Travel \& Tourism**.

## 📚 References

* Peng, L. \& Chen, Y. (2021). *Tourism safety monitoring information service system based on internet of things and block-chain.* Journal of Intelligent \& Fuzzy Systems.
* Cilfone, A.; Davoli, L.; Belli, L.; Ferrari, G. (2019). *Wireless Mesh Networking: An IoT-Oriented Perspective Survey on Relevant Technologies.* Future Internet, 11, 99.

## 📄 License

<div align="center">
Made with ⚡ by Team Cognita for Smart India Hackathon 2025
Continuously improving Terava to make travel safer for everyone.
</div>

