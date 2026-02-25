# 🎲 Rubik's Cube Collection

Fully interactive 3D Rubik's Cube simulators — from **3x3x3** to **15x15x15** — built with **Three.js**. Runs entirely in the browser, zero installations.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

**[Play Online](https://cskgcskg.github.io/3D-rubic-cube-/)**

---

## 🧊 The Cubes

| Cube | Name | File |
|---|---|---|
| **3x3x3** | Classic Rubik's Cube | `index.html` |
| **4x4x4** | Rubik's Revenge | `4x4x4.html` |
| **5x5x5** | Professor's Cube | `5x5x5.html` |
| **6x6x6** | V-Cube 6 | `6x6x6.html` |
| **7x7x7** | V-Cube 7 | `7x7x7.html` |
| **8x8x8** | V-Cube 8 | `8x8x8.html` |
| **15x15x15** | Monster Cube | `15x15x15.html` |

Navigate between cubes using the top menu bar.

---

## ✨ Features

- **True 3D rendering** with Three.js, realistic lighting, and sticker geometry
- **Drag-to-rotate** — click and drag any face to rotate that layer naturally
- **All layer moves** — outer faces, inner layers, and middle slices
- **Scramble** — animated random scramble
- **Solve** — watch the cube solve itself with smooth animated visualization
- **Auto solve detection** — detects when you solve it manually
- **Timer & move counter**
- **Undo** — Ctrl+Z
- **Orbit camera** — right-click drag
- **Zoom** — scroll wheel or pinch on mobile
- **Touch support** — full mobile support with pinch-to-zoom
- **Performance optimized** — only surface cubies rendered for large cubes
- **Zero install** — single HTML files, just open in a browser

---

## 🚀 Getting Started

### Play online
**https://cskgcskg.github.io/3D-rubic-cube-/**

### Run locally
```bash
git clone https://github.com/cskgcskg/3D-rubic-cube-.git
cd 3D-rubic-cube-
open index.html
```

---

## 🎮 Controls

| Action | Desktop | Mobile |
|---|---|---|
| Rotate a layer | Left-click + drag | Tap + drag |
| Orbit camera | Right-click + drag | Drag empty space |
| Zoom | Scroll wheel | Pinch |
| Face moves | `U` `D` `R` `L` `F` `B` | — |
| Inverse | `Shift` + key | — |
| Undo | `Ctrl+Z` | — |
| Scramble | `Space` | Button |

---

## 📁 Project Structure

```
3D-rubic-cube-/
├── index.html       # 3x3x3 Classic (landing page)
├── 4x4x4.html      # Rubik's Revenge
├── 5x5x5.html      # Professor's Cube
├── 6x6x6.html      # V-Cube 6
├── 7x7x7.html      # V-Cube 7
├── 8x8x8.html      # V-Cube 8
├── 15x15x15.html   # Monster Cube
├── README.md
└── LICENSE
```

---

## 📄 License

MIT — see [LICENSE](LICENSE).
