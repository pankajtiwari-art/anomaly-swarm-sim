# 🌌 Cosmic Anomalies (Anomaly Swarm Sim)
An interactive, sci-fi inspired web visualization that lets users explore various deep-space phenomena. The project features a dynamic particle swarm background and a sleek telemetry interface to display structural and dynamic data of cosmic anomalies like Pulsars.
![Status](https://img.shields.io/badge/status-live-brightgreen)
[**Live Demo**](https://pankajtiwari-art.github.io/anomaly-swarm-sim/)
---
## 🚀 Features
* **Dynamic Particle Swarm:** A visually stunning background container that renders interactive cosmic dust and anomaly simulations.
* **Sci-Fi Telemetry UI:** An expandable information panel that displays real-time telemetry data including:
  * **Structure:** The physical composition of the anomaly.
  * **Emissions:** Radiation and color palette data.
  * **Dynamics:** Motion and rotational mechanics.
* **Seamless Navigation:** Built-in target cycling controls to easily switch between different cosmic anomalies.
* **Atmospheric Styling:** Uses a dark vignette overlay and futuristic typography to create an immersive space-exploration vibe.
---
## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Structure** | HTML5 (Semantic Layout) |
| **Styling** | CSS3 (Variables, Flexbox, Transitions) |
| **Logic & Rendering** | Vanilla JavaScript (ES6 Modules) |
| **Graphics** | Canvas API / WebGL (via `script.js`) |
| **Hosting** | GitHub Pages |

---
## 📁 Project Structure
```text
anomaly-swarm-sim/
├── index.html          # Main application UI and layout
├── style.css           # Styling for telemetry UI and vignette effects
└── script.js           # Particle swarm logic and data handling
```
---
## ⚙️ Getting Started
### 1. Clone the repository
```bash
git clone [https://github.com/pankajtiwari-art/anomaly-swarm-sim.git](https://github.com/pankajtiwari-art/anomaly-swarm-sim.git)
cd anomaly-swarm-sim
```
### 2. Run locally
Since this project uses ES6 modules (`type="module"` in the script tag), you will need to run it through a local web server to avoid CORS issues. 
**Using VS Code:**
* Install the **Live Server** extension.
* Right-click `index.html` and select "Open with Live Server".
**Using Python:**
```bash
python -m http.server 8000
# Open http://localhost:8000 in your browser
```
---
## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/pankajtiwari-art/anomaly-swarm-sim/issues).
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewAnomaly`)
3. Commit your Changes (`git commit -m 'Add new Black Hole anomaly'`)
4. Push to the Branch (`git push origin feature/NewAnomaly`)
5. Open a Pull Request
---
## 📜 License
Distributed under the GPL 3.0 License. See `LICENSE` for more information.
---
## 🌐 Links
* **Live Demo:** [View Here](https://pankajtiwari-art.github.io/anomaly-swarm-sim/)
* **GitHub Repository:** [Source Code](https://github.com/pankajtiwari-art/anomaly-swarm-sim)
---
<p align="center">Made with ❤️ and cosmic stardust by Pankaj Tiwari</p>
