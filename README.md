# 🏫 Schoolblox — Live 3D Science Inquiry & Drone World

An interactive 3D open-world science inquiry game with **real-time multiplayer** and **FPV/3rd-person drone flight**, built with Three.js and Firebase Realtime Database.

🎮 **Play Live:** [https://codedamol.github.io/schoolblox/](https://codedamol.github.io/schoolblox/)

---

## ✨ Features

- **🔬 6 Interactive Science Quests:** Explore the world and solve mysteries using the 5-step scientific method (*Observe → Question → Hypothesis → Experiment → Conclusion*).
- **🌐 Real-Time Multiplayer:** See other explorers walking, flying drones, and chatting live with floating speech bubbles and a live radar minimap.
- **🚁 Drone Flight Mode:** Equip a 4-rotor quadcopter anytime to fly across the map in either **3rd-Person** or **FPV** camera mode with live telemetry OSD (speed, altitude, throttle, and artificial horizon).
- **📱 Cross-Platform Controls:** Works on both desktop (keyboard + mouse) and mobile/tablet (touch joystick + tap-to-move).

---

## 🎮 Controls

| Action | Desktop | Mobile / Touch |
| :--- | :--- | :--- |
| **Walk / Fly Horizontally** | `W` `A` `S` `D` or Arrow Keys | Left Virtual Joystick / Tap Ground |
| **Toggle Drone Flight** | `F` | Tap **`🚁 Drone`** button |
| **Ascend / Descend (Drone)** | `Space` / `Shift` | **`▲ Up`** / **`▼ Down`** buttons |
| **Yaw Left / Right (Drone)** | `Q` / `E` | **`↺`** / **`↻`** buttons |
| **Talk to Quest NPC** | Walk close + Click **`TALK`** | Tap NPC directly |

---

## 🛠️ Tech Stack

- **3D Engine:** Three.js (`r128`)
- **Multiplayer & Live Chat:** Firebase Realtime Database (REST + Server-Sent Events)
- **Hosting:** GitHub Pages (Single-file `index.html` architecture)
