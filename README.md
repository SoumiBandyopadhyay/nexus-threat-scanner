# 🛡️ NEXUS Intel - Advanced Threat Intelligence System

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**NEXUS Intel** is a web-based heuristic scanner designed to combat the rising threat of digital scams and fake news on messaging platforms like WhatsApp. It allows users to paste suspicious messages or links and analyzes them in real-time for potential threats.

---

## 🚀 Live Demo

Experience the live application here: **[NEXUS Intel Live](https://curious-speculoos-4628bd.netlify.app)**
*(Replace the link above with your actual Netlify/GitHub Pages URL)*

---

## ✨ Key Features

- **Real-time Threat Scanning:** Instantly analyzes text for scam keywords, fake news patterns, and malicious URL domains.
- **Advanced Heuristic Engine:** Detects aggressive capitalization (common in scams) and blacklisted URL shorteners (e.g., bit.ly, .xyz).
- **Dynamic Threat Meter:** Provides a 0-100% risk score with an animated, conic-gradient radar meter.
- **Interactive Terminal UI:** Displays scan results in a simulated terminal environment with typewriter-style log outputs.
- **3D Particle Globe Background:** A highly interactive, performance-optimized 3D canvas background that reacts to mouse/touch movements.
- **Fully Responsive:** Meticulously designed to provide an identical, premium experience on both desktop and mobile devices.

---

## 🧠 How It Works

1. **Input Analysis:** The user pastes a suspicious message, email, or URL into the payload input area.
2. **Heuristic Scanning:** The JavaScript engine scans the input for:
   - Known scam signatures (e.g., "lottery", "KBC", "OTP", "urgent").
   - Fake news patterns (e.g., "forward this", "miracle cure").
   - Suspicious URL structures (blacklisted TLDs and shorteners).
   - Aggressive capitalization (ALL CAPS).
3. **Scoring & Output:** A weighted score is calculated (capped at 100%). The UI dynamically changes its theme (Safe = Green, Suspicious = Yellow, Critical = Red) and outputs a detailed analysis log.

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 (Glassmorphism, Flexbox, CSS Grid)
- **Logic:** Vanilla JavaScript (ES6+)
- **Graphics:** HTML5 Canvas API (Custom 3D Particle Engine)
- **Fonts:** Google Fonts (Rajdhani, Share Tech Mono)

---

## 📂 Project Structure

```text
nexus-threat-scanner/
│
├── index.html      # Main application file (Contains HTML, CSS, and JS)
└── README.md       # Project documentation
