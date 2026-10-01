# Solari Split-Flap Display Board

An authentic mechanical split-flap display board (inspired by *Solari di Udine* airport and train station departure boards), crafted in a single zero-dependency HTML file.

Each character is rendered with realistic 3D hinged top/bottom plastic flaps that physically flip forward with mechanical precision and procedural acoustic feedback.

![Split-Flap Display](https://img.shields.io/badge/Design-Solari_di_Udine-black?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%203D%20%7C%20Web%20Audio-orange?style=flat-square)

---

## Features

- **Realistic 3D Mechanical Flaps**:
  - Precision 3D CSS perspective transforms simulating the physical split-flap leaf mechanism.
  - Authentic matte leaf textures, subtle highlight reflections, central hinge slit, and chassis retention screws.
  - Stepped character drum traversal: characters flip forward sequentially through the alphabet wheel until reaching their target.

- **Acoustic Engineering**:
  - Real-time procedural mechanical audio synthesized via the **Web Audio API**.
  - Dual-component sound simulation: high-frequency leaf slap transient + low-frequency plastic thud.
  - Micro-randomized pitch variations ensure no two clicks sound identical.

- **4 Operating Modes**:
  - **Airport Departures**: Live flight schedules with rotating status updates (`ON TIME`, `BOARDING`, `LAST CALL`, `DELAYED`).
  - **Departure Clock & Calendar**: Retro train station calendar clock displaying Day, Month, Date, Year, and live flipping local time.
  - **Custom Announcement Composer**: Type any announcement or message and trigger a synchronized cascade across the entire board.
  - **Famous Quotes**: Rotating inspirational quotes flipping row by row.

- **4 Visual Themes**:
  - **Classic Noir**: Signature matte black flaps with crisp white lettering.
  - **Geneva Railway**: Vintage Swiss/European amber-yellow typography on warm slate.
  - **Grand Central Bronze**: Patinated bronze-green chassis with antique ivory flaps.
  - **Cyberpunk**: Luminous neon cyan on deep navy.

- **Fully Responsive**:
  - Dynamic scaling from high-resolution 4K displays down to mobile screens.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| <kbd>Space</kbd> | Trigger Full-Board Shuffle Cascade |
| <kbd>T</kbd> | Cycle Visual Themes |
| <kbd>M</kbd> | Toggle Mechanical Sound |
| <kbd>F</kbd> | Toggle Fullscreen Mode |

---

## Quick Start

Open `index.html` directly in any web browser. No compilation, external scripts, or dependencies needed.

```bash
open index.html
```

---

## License

MIT License. Created as an interactive creative coding homage to the mechanical engineering of *Solari di Udine*.
