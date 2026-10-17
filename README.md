# Between Worlds — A Cosmic Journey

> An atmospheric interactive story built with Three.js: ancient forest ruins, a playful **YES / NO** choice, a rainy melancholic path, Saturn with a ring of hearts, the solar system, and a spiral-galaxy finale.

## Visual preview

![Between Worlds visual preview — mystical ruins, Saturn, solar system, Milky Way and TikTok showcase](assets/between-worlds-preview.png)

The image above is a **concept preview** of the intended visual direction and the project's story scenes. It is a showcase image, not a live screenshot of the running site.

## Story scenes

1. **The Ancient Grove** — moonlit ruins, stone pillars, foliage, fireflies and atmospheric lighting.
2. **The Melancholic Path** — a stormy, blue-grey version of the grove with animated rain and lightning flashes.
3. **Saturn & the Ring of Hearts** — a 3D planet, layered rings, hundreds of glowing heart shapes and shooting-star streaks.
4. **The Solar System** — the Sun and eight animated planets moving along orbital paths.
5. **The Milky Way** — a wide spiral galaxy made from thousands of colored particles.

## How to interact

- Select **Yes** to begin the cosmic journey.
- Try **No**; it dodges the pointer at first, then becomes selectable and opens the rain scene.
- Use **Continue** to move through Saturn, the solar system, and the galaxy.
- In the Saturn scene, tap the planet or ring to reveal the solar system.
- In the solar-system scene, tap the starfield to reveal the galaxy.
- Choose **Start again** to return to the beginning.

## Technology

- Three.js (WebGL)
- HTML, CSS and JavaScript modules
- Procedural 2048 × 2048 surface textures
- Responsive rendering with a device-dependent pixel ratio
- Google Fonts: Cinzel and Manrope

> **Quality note:** the renderer and procedural textures aim for a sharper, more detailed presentation, but the result is not a literal 4K photographic render. Final sharpness and frame rate depend on the device and browser. Planet textures in this build are procedural approximations rather than official space-agency imagery.

## Run the project

Because the page uses JavaScript modules, run it through a web server rather than opening the HTML file directly:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

You can also deploy the folder to GitHub Pages, Netlify, or another static host. An internet connection is required to load Three.js and the web fonts.

## Creator

**TikTok:** [@dope__pain](https://www.tiktok.com/@dope__pain)  
**Display name:** Dope Pain • Official

Follow the creator for more projects, creative experiments, and updates.

---

**BETWEEN WORLDS — DREAM • CREATE • EXPLORE**
