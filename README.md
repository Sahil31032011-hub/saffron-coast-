# LIVORA — Live Your Virtual Life

**BUILT BY SAHIL**

LIVORA is a browser-based 3D open-world life simulator built with HTML, CSS and JavaScript. The project uses Three.js as a JavaScript 3D rendering library from a CDN; no game engine or build step is required.

## Play
Open the GitHub Pages site after Pages finishes deploying. Use a modern browser with WebGL enabled and an internet connection for the Three.js CDN.

## Controls
- **WASD / Arrow keys:** Move and steer
- **Shift:** Sprint / faster driving
- **Space:** Jump
- **E:** Interact with nearby home, market, job or vehicle
- **F:** Enter or exit your car
- **Esc:** Pause
- **Mobile:** Use the on-screen joystick and action buttons

## Phase 1 currently implemented
- 3D city scene with roads, buildings, trees, distant hills, lighting and fog
- Controllable third-person avatar with two selectable avatar styles
- Walking, sprinting and jumping
- Drivable starter car with steering and acceleration
- Home, market and job interaction points
- Virtual wallet, simple grocery purchase and paid shift
- Responsive touch controls
- Local autosave of player name, avatar, wallet and location
- Animated LIVORA welcome and player setup screens

## Legacy build
The previous Saffron Coast driving game is preserved at [classic.html](./classic.html).

## Run locally
Serve this folder with any static HTTP server (ES modules require HTTP):
- VS Code Live Server, or
- `python -m http.server 8000` (only as a local static server; game code remains HTML/CSS/JS)

Then open `http://localhost:8000`.

## Roadmap
This is the first playable 3D foundation. Interior buildings, detailed character rigs, supermarket checkout, expanded jobs, traffic AI, property ownership, weather and richer save slots are future phases. The current prototype should not be mistaken for the complete AAA-scale vision.
