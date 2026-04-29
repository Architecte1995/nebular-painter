# Nebular Painter v5

Generative art & fractal drawing tool with multi-layer canvas.

## Features

- 8 drawing modes: Brush, Fractal (Julia set stamps), Rosace, Kaléido, Mandala, Nebula (particles), Ink Bleed, Orbital
- Multi-layer canvas with screen compositing
- Symmetry engine (1/3/4/6/8/12 axes) with radial & mirror reflection
- Procedural arabesques (spirograph curves)
- Constellation auto-connect from gesture history
- Random nebula generator (Perlin noise + radial gradients + starfield)
- Undo per layer (20 states)
- Import image, export PNG
- Fullscreen double-tap
- Mobile-friendly (touch + pointer events, safe-area insets)

## Tech Stack

- Pure HTML5 Canvas 2D / CSS3 / Vanilla JavaScript
- No external libraries, no WebGL, no frameworks
- Custom inline Perlin noise implementation (domain-public algorithm, Ken Perlin 1983)
- Web APIs: Pointer Events, FileReader, Fullscreen, Blob/URL

## Authors

- **Architecte1995** — concept, palette design, generative algorithms, UI architecture
- **Kimi K 2.6 Thinking** (Moonshot AI) — code generation & refactoring

## Integrity

| Property | Value |
|----------|-------|
| Version | v5 |
| SHA-256 | `ec6428ef5aa3965d0136f05f0dd69320ca6d7e5092783d8c1d7a415e36e58a45` |
| File size | 27437 bytes |

## License

MIT License — Copyright (c) 2026 Architecte1995 & Kimi K 2.6 Thinking (Moonshot AI)
