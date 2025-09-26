🎥 Demo Video

To δείγμα της υλοποίησης (βίντεο παρουσίασης του project) είναι διαθέσιμο εδώ:

👉 Παρακολούθησε το βίντεο στο [Google Drive](https://drive.google.com/drive/folders/1DoWhSFj73ScNqHoEtMAnOWqRe_NFwI3m?usp=sharing)


# Dungeon Unity Game 🎮

This is a 3D Dungeon Crawler game created in Unity as part of the **Computer Graphics final assignment** (AUEB, 2024-2025).

The game allows a player to control a hero navigating through a custom-built dungeon environment, collecting treasures and avoiding traps. The project demonstrates fundamental principles of 3D scene composition, character navigation, camera handling, lighting, physics-based interactions, and collision detection in Unity.

---

## 🧩 Assignment Description

The objective was to build an interactive dungeon crawler in Unity, where:

- The hero must **collect all treasures** in a maze-like dungeon.
- The dungeon contains **deadly traps** that reduce the player's life.
- The player controls the hero via keyboard/mouse (or gamepad).
- The dungeon is completed when all treasures are collected.
- The game ends if the hero's life reaches zero.

---

## ✅ Key Features Implemented

### ✔️ Static Scene Composition
- A custom 3D dungeon was created using Unity **prefabs**, combining multiple **rooms, corridors, and walls**.
- The scene includes **at least 4 distinct rooms**, **2 treasures**, and **2 traps** as required.

### ✔️ Hero Control & Camera
- Implemented a controllable **hero avatar**.
- The camera follows the hero dynamically, providing smooth navigation and tracking.

### ✔️ Traps & Treasures
- **Traps** cause damage when the hero collides with them (e.g. spike traps).
- **Treasures** are collectible — once collected, they are removed from the scene and the score is updated.
- The level is marked complete when all treasures are found.

### ✔️ Collision Detection
- Implemented Unity physics and **NavMesh** to handle movement constraints (walls, obstacles).
- Treated traps and collectables using collision events.

### ✔️ Lighting & Environment
- Dynamic and baked lighting added using:
  - Point lights, torches
  - Reflection probes and lightmaps
- Shadows are selectively used to optimize performance.

---

## ✨ Bonus Features (Optional Add-ons)

- 🚪 **Animated components** like opening doors and pressure plates.
- ⬆️ **Multilevel design** with ramps and stairs.
- 🔄 Dynamic interaction of traps (e.g. rotating spike traps).

---

## 📁 Project Structure

Key folders and files in the Unity project:
DungeonUnity/
├── Assets/ # Main game assets (models, materials, prefabs, scripts)
├── ProjectSettings/ # Unity project settings
├── Packages/ # Unity package dependencies
├── Library/ # Auto-generated files (ignored in Git)
├── Logs/ # Build or runtime logs (ignored)
├── .gitignore # Git ignore rules for Unity
├── DungeonUnity.sln # Visual Studio solution
└── README.md # You're here!

> ✅ Note: `Library/`, `Logs/`, `Temp/`, and other generated files are ignored via `.gitignore`.

---

## 🚀 How to Run

1. Open the project with **Unity Hub**.
2. Use Unity version **2022.3.x or later**.
3. Open the `Dungeon.unity` scene from `Assets/`.
4. Click ▶️ Play to run the game in editor mode.

---

## 🛠️ Tools Used

- **Unity Engine**
- **C# scripting**
- **Unity Prefabs**
- **NavMesh**
- **Git & GitHub**

