Supernova Particle Engine 🌌

An interactive WebGL experiment using **Three.js** and **MediaPipe Hand Landmarker**. This project tracks hand movement and velocity to manipulate a system of 20,000 particles in real-time.

## 📂 Project Structure

The repository is organized into stages, showing the progression from a basic setup to a full-speed particle engine:

* **`index.html`**: The initial framework and system setup.
* **`Particles.html`**: Implementation of the core 3D particle system.
* **`Update.html`**: Added hand-tracking logic and real-time interaction.
* **`Supernova.html`**: The **final version** featuring velocity-based explosions, shape morphing, and HSL color shifting.

## ✨ Features

* **2-Hand Velocity Tracking:** Uses your webcam to detect hand distance and speed.
* **Supernova Trigger:** Rapidly spreading your hands triggers a high-velocity particle explosion.
* **Geometric Morphing:** Particles transition between shapes like Jupiter, Saturn, and Heart forms.
* **Dynamic Scaling:** Use a pinch gesture to grow or shrink the particle field.
* **Performance Optimized:** Runs on GPU-accelerated MediaPipe vision tasks for low-latency feedback.

## 🚀 Getting Started

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/your-repo-name.git](https://github.com/YOUR_USERNAME/your-repo-name.git)
    ```
2.  **Run a Local Server:**
    Because the project uses ES Modules and requires webcam permissions, open the folder using a local server (like VS Code's **Live Server** extension or `python -m http.server`).
3.  **Launch:**
    Open `Supernova.html` in your browser for the full experience.

## 🎮 Interaction Guide

| Gesture | Effect |
| :--- | :--- |
| **Hand Spread** | Scales the particle formation larger |
| **Fast Expansion** | Triggers the **Supernova** explosion effect |
| **Vertical Move** | Shifts the particle color spectrum |
| **Horizontal Move** | Switches between different gravitational shapes |

## 🛠️ Built With

* [Three.js](https://threejs.org/) - 3D Rendering
* [MediaPipe](https://google.github.io/mediapipe/) - Hand Tracking ML
* [Orbitron Font](https://fonts.google.com/specimen/Orbitron) - Sci-fi UI Aesthetics

---
*Note: This project requires a webcam and a browser that supports WebGL.*
