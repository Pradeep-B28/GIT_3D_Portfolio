<div align="center">

# 🎨 git-viz — 3D GitHub Skyline, Galaxy, Archipelago & Duel

### *Transform Any GitHub Profile into an Immersive 3D Universe with Three.js, Custom Shaders & Procedural Web Audio*

[![Live Demo](https://img.shields.io/badge/Demo-Live%20on%20GitHub%20Pages-7C3AED?style=for-the-badge&logo=githubpages&logoColor=white)](https://pradeep-b28.github.io/GIT_3D_Portfolio/)
[![Three.js](https://img.shields.io/badge/Render%20Engine-Three.js%20r163-000000?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/Codebase-Vanilla%20ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Audio-Procedural%20Web%20Audio-FF6C37?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Backend](https://img.shields.io/badge/Architecture-100%25%20Client--Side-238636?style=for-the-badge&logo=github)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-4-interactive-3d-visual-modes">4 3D Modes</a> •
  <a href="#-cinematic-features--mechanics">Cinematic Features</a> •
  <a href="#-color-palettes--shaders">Themes & Shaders</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-controls-guide">Controls Guide</a> •
  <a href="#-license--copyright">License & Copyright</a>
</p>

</div>

---

## 🌟 Overview

**git-viz** is a zero-dependency, GPU-accelerated 3D data visualization web application built with **Three.js** and **Modern Vanilla JavaScript**. By pulling live public data directly from the GitHub REST API, **git-viz** turns code contributions, repository stars, and language distributions into an interactive, spatial visual experience.

Whether visualizing annual contribution history as a futuristic neon city skyline, inspecting repositories as an orbital planetary galaxy, surveying language ecosystems across floating archipelago islands, or sparring with a developer friend in side-by-side split-skyline duels, **git-viz** brings developer metrics to life.

---

## 🎮 4 Interactive 3D Visual Modes

| Mode | Visual Paradigm | Core Interactive Features |
| :--- | :--- | :--- |
| 🏙️ **3D City Skyline** | A 7×52 contribution matrix mapping 365 days of activity into 3D architectural skyscrapers. | • Procedural window illumination & rooftop antennas<br>• Holographic username billboards & 3D trophy monuments<br>• **12-Month Interactive Timeline Scrubber & Melodic Audio Playback** |
| 🌌 **Repo Galaxy** | An orbital planetary star system revolving around a central avatar sun. | • Language-coded laser orbits & gravitational star nodes<br>• **Floating 3D billboard text sprites** with star & fork stats<br>• Single-click warp jump directly into GitHub repositories |
| 🏝️ **Tech Archipelago** | Floating biome islands procedurally shaped and grouped by programming language. | • Low-poly floating terrain with rim-lit atmospheric glow<br>• Repository crystal monoliths scaled by star metrics<br>• Dynamic oceanic levitation physics |
| ⚔️ **Developer Duel** | Real-time split-screen 3D skyline battle comparing two developer profiles. | • Cyan vs. Crimson competitive 3D grid layout<br>• Live center laser divider & stat comparisons<br>• **Dynamic Star & Commit Leaderboard Trophy** awarding victor |

---

## ✨ Cinematic Features & Mechanics

- 🌀 **Futuristic Glassmorphic Preloader:** Animated cyberpunk multi-ring spinner with live status updates and smooth blur reveal.
- 🎬 **Staggered 3D Entrance Reveal:** 3D skyscrapers and galaxy stars sprout upward with ease-out bounce animations, paired with spring-animated UI panels.
- 🖱️ **3D Perspective Card Tilt & Glare:** Real-time mouse gyro tilt with dynamic radial glare reflections on profile cards and modal dialogs.
- 📐 **3D Camera & Multi-Plane Parallax:** Subtly drifting 3D perspective and layered depth shifts on floating UI controls tied to cursor coordinates.
- ✨ **Interactive Raycast Hover & Scale Pop:** 3D raycast hover with mesh scale popping, emissive pulsing, click ripples, and Web Audio SFX.
- 🌊 **Fluid Harmonic Levitation:** Sinusoidal ocean-swell floating on archipelago islands, orbiting galaxy stars, and spinning golden obelisk monuments.
- 🚶 **WASD Drone Street View:** Press **`🚶 Drone`** to enter ground-level flight controls (**WASD** to move, **Q/E** to adjust altitude, mouse drag to look around).
- 💫 **Three.js Post-Processing Bloom:** Built-in `UnrealBloomPass` shader for neon glows on rooftop antennas, lasers, and spires.
- 🎶 **Melodic Code Synthesizer:** Procedural Web Audio API synth playing harmonic scale arpeggios as the 12-month timeline builds.
- 🎆 **3D Particle Fireworks:** Launch interactive multi-colored particle fireworks over the city skyline with sound effects.
- 🎥 **WebM Video Exporter:** One-click **"🎥 Record Video"** button captures a 5-second 360° auto-rotating webm animation directly in-browser.
- 📸 **High-Res PNG Screenshots:** Export crisp high-definition PNG renders for portfolio READMEs or social sharing.
- 🛡️ **API Rate Limit Protection & Demo Mode:** Built-in PAT token setting + automatic mock profile fallback if GitHub API limits are met.

---

## 🎨 Color Palettes & Shaders

| Theme | Aesthetic | Visual Tone & Weather Particles |
| :--- | :--- | :--- |
| 🐙 **GitHub Dark** | Signature GitHub contribution greens (`#0e4429` → `#39d353`) | Floating ambient star dust |
| 🌌 **Cyberpunk Neon** | Vibrant synthwave magenta, electric violet, and cyan glow | Floating neon ash & embers |
| 🟢 **Matrix Emerald** | Terminal green phosphor aesthetics with dark stone towers | Falling digital rain particles |
| 🌅 **Sunset Gold** | Warm twilight violet with golden amber illumination | Glowing ember fireflies |
| ⚡ **Obsidian Silver** | Ultra-clean monochrome glass, steel, and arctic white highlights | Subtle monochrome drifting dust |

---

## 🚀 Quick Start

### Option 1: Live Web Deployment
Experience it immediately with zero setup on GitHub Pages:  
👉 **[Launch Live git-viz](https://pradeep-b28.github.io/GIT_3D_Portfolio/)**

### Option 2: Local Deployment
1. Clone the repository:
   ```bash
   git clone https://github.com/Pradeep-B28/GIT_3D_Portfolio.git
   cd GIT_3D_Portfolio
   ```
2. Open [`index.html`](index.html) directly in any modern browser, or spin up a quick local web server:
   ```bash
   # Using Python
   python -m http.server 8080

   # Or using Node.js
   npx serve .
   ```
3. Navigate to `http://localhost:8080`.

---

## 🕹️ Controls Guide

- **Rotate / Orbit**: Left-click and drag across the canvas.
- **Pan View**: Right-click (or two-finger drag) across the canvas.
- **Zoom In / Out**: Mouse scroll wheel or pinch gesture.
- **Drone Street View**: Click **`🚶 Drone`**, fly with **`W` `A` `S` `D`**, elevate with **`Q`** / **`E`**, aim with mouse.
- **Timeline Melodic Playback**: Drag the bottom timeline slider or press **Play (▶)**.
- **Celebrate**: Click the **`🎆 Fireworks`** button to detonate celebratory particles above the skyline.
- **Export Artifacts**: Click **`📸 Save PNG`** for high-resolution snapshots or **`🎥 Record Video`** for animated WebM captures.

---

## 📄 License & Copyright

```
Copyright (c) 2026 Pradeep (Pradeep-B28). All Rights Reserved.

Licensed under the MIT License. You may freely use, modify, and distribute
this project under the terms of the MIT license. See the LICENSE file for details.
```

Crafted with 🚀 by **[Pradeep](https://github.com/Pradeep-B28)**.
