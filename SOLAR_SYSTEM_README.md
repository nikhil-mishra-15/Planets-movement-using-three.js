# 🪐 3D Solar System — Three.js

![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

> A simple 3D solar system simulation built with Three.js — featuring all 8 planets with adjustable orbital speeds, pause/resume controls, and Saturn's rings.

---

## ✨ Features

- ☀️ Sun at the center with realistic lighting
- 🪐 All 8 planets with relative sizes and colors
- 🎛️ Adjustable orbital speeds for each planet using sliders
- ⏯️ Pause / Resume animation
- 💍 Saturn with rings (simplified)
- 📱 Responsive design — works on mobile and desktop

---

## 🚀 Getting Started

No installation or build step required.

```bash
git clone https://github.com/your-username/solar-system.git
cd solar-system
```

Open `index.html` in any modern web browser and you're good to go.

> For best experience, use a local server:
> ```bash
> npx serve .
> ```

---

## 🕹️ How to Use

1. Open `index.html` in your browser
2. Use the **control panel at the bottom** to:
   - Adjust each planet's orbital speed with its slider
   - Hit **Pause / Resume** to stop or continue the animation
3. Watch the planets orbit the sun at your chosen speeds!

---

## 🌍 Planet Speed Controls

Each planet has its own speed slider with a default value relative to Earth's baseline:

| Planet  | Default Speed |
|---------|--------------|
| ☿ Mercury | 4.1x |
| ♀ Venus   | 1.6x |
| 🌍 Earth  | 1.0x *(baseline)* |
| ♂ Mars   | 0.5x |
| ♃ Jupiter | 0.08x |
| ♄ Saturn  | 0.03x |
| ⛢ Uranus  | 0.01x |
| ♆ Neptune | 0.006x |

---

## 🛠️ Technical Details

- **Three.js** — 3D scene rendering
- **`requestAnimationFrame`** — smooth animation loop
- **Simple orbital physics** — circular orbits with configurable angular speed
- **Vanilla JavaScript** — no frameworks, no dependencies
- **Responsive CSS** — adapts to any screen size
- **CDN** — Three.js loaded via CDN, no npm needed

---

## 📁 Project Structure

```
solar-system/
├── index.html       # Entry point
├── style.css        # Layout & control panel styles
└── main.js          # Scene setup, planets, sliders, animation loop
```

---

## ✅ Requirements

- Modern web browser — Chrome, Firefox, Safari, or Edge
- Internet connection (to load Three.js from CDN)

---

## 🖼️ Preview

> _Add a screenshot or GIF of the simulation here_

![Preview](./screenshots/preview.png)

---

## 📄 License

[MIT](./LICENSE)

---

## 👤 Author

**Your Name** — [@your-username](https://github.com/your-username)

---

> ⭐ If you liked this project, drop a star on GitHub!
