# Between Worlds — High-detail Three.js edition

This version improves the scene with 2K procedural surface textures for planets and terrain, more detailed planetary geometry, layered Saturn rings, denser galaxy particles, and higher device-pixel-ratio rendering (up to 2.5, depending on the device).

## Run it
Use a local web server or deploy the folder to GitHub Pages / Netlify. The site loads Three.js from jsDelivr and Google Fonts, so it needs an internet connection.

## Story controls
- **Yes** starts the cosmic journey.
- **No** dodges the pointer for the first five attempts, then activates the melancholy/rain scene.
- **Continue** advances through Saturn, the solar system, and the Milky Way.
- Tap Saturn/rings to move to the solar system; tap the starfield in the solar-system scene to reveal the Milky Way.
- **Start again** resets the experience.

Note: “near 4K” depends on the screen, GPU, and browser. Procedural textures are generated at 2048×2048 and the renderer uses up to 2.5× device pixel ratio; the browser may limit this on mobile to avoid overheating or slow performance. These are procedural visual textures, not NASA photographic maps.
