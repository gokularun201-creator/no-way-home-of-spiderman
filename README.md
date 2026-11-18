# 🕷️ Spider-Man: No Way Home — Ultimate 3D Web Experience

An interactive 3D WebGL showcase of Spider-Man inspired by *Spider-Man: No Way Home*, built with Three.js, WebGL PBR shaders, dynamic camera controls, suit switching, and interactive canvas particle systems.

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-e62429?style=for-the-badge&logo=github)](https://gokularun201-creator.github.io/no-way-home-of-spiderman/)
[![Three.js](https://img.shields.io/badge/Three.js-r160-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🌟 Live Demo
Experience the site directly in your browser:
🔗 **[https://gokularun201-creator.github.io/no-way-home-of-spiderman/](https://gokularun201-creator.github.io/no-way-home-of-spiderman/)**

---

## 🚀 Features

- **🎮 Real-Time 3D WebGL Model**: High-fidelity 3D Spider-Man GLB model rendered with full PBR materials and environment reflections.
- **🎥 Dynamic Camera Controls**:
  - **Orbit / Drag**: 360-degree interactive camera orbit.
  - **Zoom / Pinch**: Smooth zoom with constrained bounding.
  - **🕸 Web-Swing Cam**: Cinematic swaying swing motion.
  - **Auto-Rotate**: Smooth showcase carousel turntable mode.
- **👕 Suit Selection**:
  - **Red & Blue (Classic)**
  - **Black Suit (Symbiote)**
  - **Iron Spider (Stark Nanotech)** with dynamic lighting and stage ring transitions.
- **⚡ Interactive Visuals**:
  - Procedural web canvas in the background reacting to mouse/pointer movement.
  - Atmospheric floating ember particles and 3D web geometry threads.
  - S.H.I.E.L.D. file animated counter stats.
  - Fully responsive mobile & desktop UI.

---

## 🛠️ Tech Stack

- **HTML5 & Modern CSS3** (Custom glassmorphism, responsive grid, dynamic gradients)
- **JavaScript (ES Modules)**
- **Three.js (r160)**
  - `OrbitControls`
  - `GLTFLoader`
  - `RoomEnvironment` & `PMREMGenerator`
  - PBR standard materials & shadow maps

---

## 💻 Local Development

Run locally using any static web server:

```bash
# Using Python
python -m http.server 8000

# Or using Node.js / npx
npx serve .
```

Then open `http://localhost:8000` in your web browser.

---

## 📜 Disclaimer
Fan-made tribute project. Spider-Man and all related characters and elements are © Marvel Characters, Inc. and Sony Pictures.
