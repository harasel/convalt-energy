# Convalt Energy — 3D Storytelling Mockup

This prototype is a contest/design-direction mockup based on the supplied DigiCollect SOW and the current Convalt Energy information architecture.

## Concept
- One calm, full-screen WebGL storytelling canvas.
- Scroll changes narrative chapters and transforms the 3D composition.
- Four visual motifs represent Manufacturing, Power Generation, Data Centers and Recycling.
- Minimal UI, generous negative space, neutral palette and restrained lime energy accent.
- Responsive/mobile fallback behavior is included through reduced scene scale and simplified composition.

## Run
Open `index.html` in a modern browser with internet access. Three.js is loaded from jsDelivr CDN.

For local development:
1. `python -m http.server 8080`
2. Open `http://localhost:8080`

## Production direction
Replace the procedural placeholder geometry with optimized GLB assets, add real chapter-specific camera choreography, lazy-load heavier assets, and connect the 2D internal-page theme to the same design tokens.
