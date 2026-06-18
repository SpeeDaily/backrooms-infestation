# THE BACKROOMS: INFESTATION

[![The Backrooms Infestation Gameplay](https://img.youtube.com/vi/k1GIXhuJYQE/maxresdefault.jpg)](https://www.youtube.com/watch?v=k1GIXhuJYQE)

**A procedurally generated liminal horror survival game built in a single 84.38 KB file.** No external libraries, no game engines, no image assets. Pure Vanilla JavaScript, HTML, and CSS.

🚀 [**PLAY THE GAME INSTANTLY IN YOUR BROWSER**](https://speedaily.github.io/backrooms-infestation/)

🎬 [**WATCH THE OFFICIAL GAMEPLAY & DEVLOG PLAYLIST**](https://www.youtube.com/playlist?list=PLHipl9G75ssTckIwqD7sHWlI5wYVYDZfD)

📦 [**DOWNLOAD THE RELEASE TO PLAY 100% OFFLINE**](https://github.com/SpeeDaily/backrooms-infestation/releases)

---

## THE DESCENT
You are trapped. Escape the procedurally generated corridors. Beware the anomalies. They emit radioactive signatures and will hunt you down if they gain line of sight. Do not let them close.

---

## SURVIVAL PROTOCOLS (CONTROLS)
* **W, A, S, D / ARROW KEYS:** Move and slide along corridors.
* **SHIFT:** Hold to sprint and escape anomalies.
* **MOUSE DRAG:** Rotate look direction.
* **LEFT CLICK:** Locks cursor to screen & fires hitscan railgun.
* **ANOMALIES (🎃, 😡, 👿):** Sidestep your crosshairs if you shoot. Distance < 2m emits heavy radiation that drains health.
* **MEDKITS:** Stand over the green crosses to restore 40 HP.

---

## TECHNICAL ARCHITECTURE
This project is an exercise in extreme optimization and zero-dependency web development.
* **Zero External Assets:** All rendering, textures, and UI elements are generated via raw code or HTML Canvas elements. 
* **Custom Raycaster:** A scratch-built 2.5D rendering engine running natively in the browser viewport.
* **Procedural Generation:** Infinite level scaling using a DFS recursive backtracker maze algorithm.
* **Procedural Audio:** Footsteps, deep hum drones, basslines, and heartbeat effects are synthesized in real-time using the native Web Audio API.
* **Offline Capable:** Because the entire game logic lives inside `index.html`, it can be downloaded and played natively on any desktop without an internet connection.

---

## LOCAL INSTALLATION
Want to run the raw code offline?
1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Brave).
3. Survive.

---

## LICENSE
Created by **SpeeDaily**.
This project is open-source and licensed under the MIT License. Feel free to fork, modify, and learn from the architecture.
