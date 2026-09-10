# 🌌 V O I D // Zero-G Kinetic Canvas

<p align="center">
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=220x220&amp;margin=8&amp;data=https://wani012.github.io/V-O-I-D/" alt="Scan to Play V-O-I-D" width="180" />
  <br>
  <sub><b>📱 Scan to Play Instantly on Mobile</b></sub>
</p>

<p align="center">
  <a href="https://wani012.github.io/V-O-I-D/">
    <img src="https://img.shields.io/badge/Play%20Live-GitHub%20Pages-00f0ff?style=for-the-badge&amp;logo=github&amp;logoColor=black" alt="GitHub Pages Live Demo" />
  </a>
  <a href="https://void-kinetic.vercel.app">
    <img src="https://img.shields.io/badge/Play%20Live-Vercel-ff007f?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Vercel Live Demo" />
  </a>
  <img src="https://img.shields.io/badge/Physics-Matter.js-blue?style=for-the-badge" alt="Matter.js" />
  <img src="https://img.shields.io/badge/Audio-Web%20Audio%20API-purple?style=for-the-badge" alt="Web Audio API" />
</p>

---

## 🎮 Play Live in Browser

- 🚀 **GitHub Pages (Direct GitHub Web):** [https://wani012.github.io/V-O-I-D/](https://wani012.github.io/V-O-I-D/)
- ⚡ **Vercel Mirror:** [https://void-kinetic.vercel.app](https://void-kinetic.vercel.app)

---

## ✨ Features

### 1. 🎵 Procedural Ambient Chimes (Web Audio API)
- Pure native Web Audio API synthesizer — zero external audio clips or network requests.
- Dual-oscillator bell synthesizer (fundamental sine + 2.76x harmonic overtone).
- Collisions trigger soothing pentatonic harmonic notes scaled by impact velocity.

### 2. 💥 Shockwave / Kinetic Blast
- **PC:** Right-Click or Double-Click anywhere on the canvas.
- **Mobile:** Double-Tap anywhere.
- Emits an explosive neon shockwave ripple (300px radius) with particle sparks and radial kinetic impulse that violently repels nearby physics bodies.

### 3. ⏳ Time-Dilation / Bullet Time (0.1x Slow Motion)
- **PC:** Press & Hold `Spacebar`.
- **Mobile:** Long-Press & Hold anywhere on the screen.
- Physics engine slows to `0.1x` speed in real-time, audio drops one octave down into deep resonance, and background renders a sleek holographic space-grid ripple. Release to resume normal speed (`1.0x`).

### 4. 🧲 Zero-G Interactive Physics & Force Fields
- 35–50 sleek frosted glass and neon geometric bodies floating with rotational inertia and realistic collisions powered by Matter.js.
- Interactive cursor Attractor / Repulsor force fields.
- Slingshot drag throwing with preserved velocity.
- Gravity switcher: **Zero-G**, **Earth (9.8m/s²)**, and **Invert**.

---

## 🕹️ Controls Guide

| Input | Desktop (PC) | Mobile / Touch |
| :--- | :--- | :--- |
| **Move / Attract** | Move Mouse | Single Finger Drag |
| **Slingshot Throw** | Left Click + Drag + Release | Drag object + Release |
| **Kinetic Shockwave** | Right-Click / Double-Click | Double-Tap |
| **Bullet Time (0.1x)** | Hold `Spacebar` | Long Press & Hold |
| **Force Field Toggle** | Press `F` or Click HUD pill | Tap HUD Attract/Repel |
| **Spawn Objects** | Click anywhere | Tap empty canvas space |
| **Audio Mute/Unmute** | Click Sound button or `M` | Tap Sound pill in top HUD |

---

## 🛠️ Tech Stack

- **Physics Engine:** [Matter.js](https://brm.io/matter-js/)
- **Styling:** [Tailwind CSS CDN](https://tailwindcss.com/)
- **Audio Synthesizer:** Native HTML5 Web Audio API
- **Fonts:** Space Grotesk, Inter, JetBrains Mono
- **Architecture:** Zero-build single-file `index.html`
