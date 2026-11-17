# RStudio — Creative Studio & Interactive Motion Showcase

A single-file, multi-experience interactive web showcase featuring scroll-driven 3D WebGL motion, fluid video interactions, and typography-rich editorial sections.

## Sections Overview

1. **Vante — Scroll-Driven Portfolio Hero**
   - 900vh scroll-driven 3D CatmullRom ribbon path powered by Three.js 0.170.0.
   - Dual-track sliding headline (`CRAFT IN` / `MOTION`) that glides across opposite directions.
   - Custom shader material with analytic rounded rectangles, linear color passthrough, and fragment backface un-mirroring.
   - Smooth card departure transition from the ribbon into a calm 3×2 grid with dynamic pointer-following designer badge.

2. **Wild — Travel Hero**
   - Clean opening sequence revealing a stadium-shaped pill that separates "WI" and "LD".
   - Looping aerial floating island video with sunset clouds and waterfall.
   - Sweeping white background paper curves and "Let's Get Wild" interactive replay.

3. **Kolibrie — Short-Form Social Film Studio**
   - Warm golden-hour hero with looping video background and cursor-following photo card.
   - Pinned "Latest drops" section with a 3D peeling card stack.
   - Fixed-centre "Meet the flock" dark team section with 12 parallax photos rising at varying speeds.

4. **Reelmark — Video Creator Marketplace**
   - 1440×1080 framed hero with a 10-card cylindrical video carousel.
   - Continuous right-to-left marquee with 1:1 drag and 95%/s velocity coasting.
   - Hand-drawn SVG doodle annotations and arrows.

## Tech Stack

- **Vanilla HTML5, CSS3, & Modern ES Modules**
- **Three.js 0.170.0** (WebGL 3D ribbon path & video textures)
- **GSAP 3.13.0 & ScrollTrigger**
- **Lenis 1.3.17** (Smooth momentum scrolling)
- **Zero build tools required** — fully self-contained.

## Running Locally

Serve the directory with any local HTTP server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

Open `http://localhost:8000` in your browser.
