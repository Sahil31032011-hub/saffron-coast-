# Saffron Coast — CrazyGames build

This folder is the standalone HTML5 build of **Saffron Coast**. The repository root currently hosts the separate LIVORA project; keep the two builds separate.

## Run locally

Serve this folder over HTTP, then open it in a modern browser:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` from this folder. For CrazyGames SDK local testing, use `localhost` or `127.0.0.1`.

## Controls

- **W / Up Arrow:** Accelerate
- **S / Down Arrow:** Brake / reverse
- **A / D or Left / Right Arrows:** Steer
- **Space:** Handbrake
- **Shift:** Nitro (when unlocked)
- **P:** Pause / resume
- **N:** World map
- **G:** Garage
- **M:** Sound toggle
- **C:** Camera view
- **H:** Headlights
- **B:** Horn
- **Mobile / tablet:** On-screen driving controls

Escape is not captured by the game so the browser/platform can use it for fullscreen behavior.

## CrazyGames integration included

- CrazyGames HTML5 SDK v3 script and guarded asynchronous initialization
- SDK environment check: platform calls run only in `local` and `crazygames` environments
- Gameplay start/stop events follow the game's play/menu/pause state
- SDK device info selects mobile/tablet controls where available
- Platform `muteAudio` setting overrides the in-game sound toggle
- No external advertisements or ad requests are included

## Existing gameplay

- Open-city driving sandbox with city, desert and winter zones
- Selectable vehicles and garage customization/upgrades
- Traffic, police pursuit, missions, fuel, damage and repair
- World map, minimap, destinations and travel points
- Tutorial coach, pause screen and adjustable touch controls
- Local progress saving

## Before submitting

This is a **CrazyGames integration build candidate**, not a guarantee of approval. Complete these manual checks in the CrazyGames Preview/QA tool:

1. Start from the game menu and confirm the first Gameplay Start event occurs only after pressing **START DRIVING**.
2. Confirm Gameplay Stop/Start around pause, map, garage, mission dialogue and end-of-run screens.
3. Test keyboard and mouse on Chrome/Edge, including Escape/fullscreen behavior.
4. Test touch controls on an actual phone/tablet and confirm desktop players do not get mobile controls.
5. Test sound mute/unmute, including the platform mute setting.
6. Test all missions, vehicle purchases, upgrades, fuel, map travel, respawn and save persistence.
7. Check loading time, frame rate, console errors, small screens and landscape layout.
8. Prepare the final CrazyGames cover, screenshots, description, category and submission metadata in the Developer Portal.

CrazyGames SDK reference: https://docs.crazygames.com/sdk/intro/
CrazyGames technical requirements: https://docs.crazygames.com/requirements/technical/
CrazyGames gameplay events: https://docs.crazygames.com/sdk/game/
