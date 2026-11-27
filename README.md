# Saffron Coast

**A browser-based open-world driving game**

Saffron Coast is a driving game that runs in a modern web browser. Explore the city, drive vehicles, follow missions, and use the in-game map and garage.

## Play

Open the game through the project's GitHub Pages deployment, when enabled. You can also run it locally with a static HTTP server.

> The game needs a modern browser with WebGL support. An internet connection may be required for externally hosted assets and libraries.

## Controls

The exact available actions can vary by device and the current game screen.

| Action | Control |
|---|---|
| Move / drive | **WASD** or **Arrow keys** |
| Pause / menus | Use the in-game menu controls |
| Mobile | Use the on-screen touch controls |

Check the in-game help screen for the complete control list.

## Game features

- Open city environment to explore
- Drivable vehicles
- Garage and vehicle options
- Missions and objectives
- Traffic and police systems
- In-game map and minimap
- Vehicle progression and upgrades
- Keyboard and mobile touch controls
- Browser-based progress saving

## Run locally

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Start a local static server:

   ```bash
   python -m http.server 8000
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

You can also use the Live Server extension in Visual Studio Code.

## Project files

- `index.html` — main game page
- `classic.html` — alternate/legacy game page
- `manifest.webmanifest` — web app metadata
- `sw.js` — service worker
- `icon-192.png` and `icon-512.png` — app icons

## Compatibility

For the best experience, use an up-to-date desktop or mobile browser with WebGL enabled. On mobile, rotate or resize your device as needed and use the on-screen controls.

## Development status

This README describes the current browser game. Platform-specific integrations, including any third-party game portal SDK, should only be considered complete after they have been added to the game and tested in that platform's environment.

## Credits

Created by **Sahil**.
