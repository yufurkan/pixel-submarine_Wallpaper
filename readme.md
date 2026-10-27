# Pixel Submarine Wallpaper 🌊

A lightweight, zero-dependency web simulation written in vanilla JavaScript and HTML5 Canvas. It procedurally renders a Type VIIC submarine navigating through shifting ocean swells, multi-layered parallax waves, realistic rain, and lightning storms across a continuous day-night cycle.

![HTML5 Canvas](https://img.shields.io/badge/Canvas-HTML5-orange?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

## ✨ Features

- **Procedural Pixel Art Rendering:** The submarine, hull details, cloud structures, and lighting are dynamically calculated and rendered pixel-by-pixel without external image assets.
- **Dynamic Day/Night Cycle:** Smooth, mathematical transition of sky and underwater color palettes based on time progression.
- **Advanced Weather System:** Multi-layered swells, shifting wind/wave intensities, realistic rain simulation, and random lightning flashes.
- **Parallax Ocean Layers:** Multi-depth water layers creating a rich 3D illusion on a 2D canvas.

## 🎮 Controls

| Key | Action |
|     |        |
| **`T` (Hold)** | Accelerate time and speed up the simulation. |
| **`W` (Press)** | Force a change in weather conditions/phases. |

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone [https://github.com/yufurkan/pixel-submarine-2310.git](https://github.com/yufurkan/pixel-submarine-2310.git)
    ```

Open index.html in any modern web browser. (No build tools or local servers required!) 

Performance: Optimized requestAnimationFrame loop with dynamic sprite caching to maintain a steady 60 FPS.

📄 License
This project is open-source and available under the MIT License.