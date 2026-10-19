# 🔨 Forge Studio

**A lightweight, fast 2D and 3D game creator for Windows, macOS and Linux.**

Forge Studio gives solo creators and indie game developers the power to build, script, and publish rich 2D and 3D games with zero bloat and batteries included. It is free to download and use, and the games you make are yours to sell and share.

---

## 🚀 Downloads (Latest Release: v0.100.7)

| Platform | Direct Download | Notes |
| :--- | :--- | :--- |
| **Windows Installer** | [**Forge.Studio.Setup.0.100.7.exe**](https://forge-studio-downloads.forgestudio.workers.dev/v0.100.7/Forge.Studio.Setup.0.100.7.exe) | Recommended. Standard setup with in-app updates and desktop integration |
| **Windows Portable** | [**Forge.Studio.exe**](https://github.com/kinsocial1-del/ForgeStudio/releases/latest/download/Forge.Studio.exe) | Single file; run from any folder or USB drive. No in-app updates |
| **macOS** (Intel & Apple Silicon) | [**Forge.Studio-0.100.7-mac.dmg**](https://github.com/kinsocial1-del/ForgeStudio/releases/download/v0.100.7/Forge.Studio-0.100.7-mac.dmg) | Drag into Applications. See [first launch on Mac](#-first-launch-on-macos) |
| **Linux** (x64) | [**Forge.Studio-0.100.7-linux.AppImage**](https://forge-studio-downloads.forgestudio.workers.dev/v0.100.7/Forge.Studio-0.100.7-linux.AppImage) | `chmod +x` the file, then run it. Updates in-app |

> **Already installed?** Get new features and fixes inside the app with **Help → Check for updates**. Release notes and older versions are on the [Releases page](https://github.com/kinsocial1-del/ForgeStudio/releases).

### 🍎 First launch on macOS

The Mac app is not yet signed with an Apple Developer ID, so macOS asks before opening it the first time:

1. Open **Applications**, right-click **Forge Studio** and choose **Open**.
2. Click **Open** in the dialog.
3. If macOS still blocks it, go to **System Settings → Privacy & Security** and click **Open Anyway**.

You only need to do this once. Mac copies show where to download each new version until in-app installs are available on Mac.

### 💻 System requirements

| | Minimum |
| :--- | :--- |
| **Windows** | Windows 10 or 11, 64-bit |
| **macOS** | A recent macOS version, Intel or Apple Silicon |
| **Linux** | 64-bit distribution that runs AppImages (some need `libfuse2`) |
| **Graphics** | A GPU with WebGL2 support for 3D levels (most GPUs from the last decade). 2D works everywhere |

---

## ✨ What's new

* **v0.100.7:** Fixed Level settings navigation in the hierarchy panel, revealing inspector fields and game rules directly.
* **v0.100.6:** Fixed mouse activation across all workspace menus, direct User guide access, and narrow-window preview controls.
* **v0.100.5:** Reorganized the editor into menus, grouped editing controls, a simpler asset dock, and a larger scene workspace.
* **v0.100.4:** Fixed engine graph IF checks ignoring wired values and random formulas mishandling reversed bounds.
* **v0.100.3:** Fixed clipboard asset isolation and reused matching assets when pasting between projects.
* **v0.100.2:** Fixed stuck firing/camera input, music carrying into silent levels, and saved games staying frozen after a win or game over.

* **v0.100.1:** Chasing enemies jump straight up low ledges, never walk off the edge of the level, and round wall corners smoothly.
* **v0.100.0:** Smart duplicate (copies repeat your last move) and one-click fixes in Project check.
* **v0.99.0:** Trauma-based screen shake, directional camera recoil and distance-based explosion shakes.
* **v0.98.0:** Time scale, audio mixer buses and stylized scene transitions.
* **v0.97.1:** Mac and Linux polish: platform badge, and clearer export options.
* **v0.97.0:** Forge Studio for **macOS and Linux**.
* **v0.96.0:** Updated license terms. Games you make are yours to sell.
* **v0.95.0:** Cinematic camera splines, destructible mesh fracturing, weapon slash arcs and vehicle suspension.
* **v0.94.0:** Dynamic point and spot lights with radius falloff and flashlight cones.
* **v0.93.0:** Branching dialogue trees with player choices, condition gates and quest hooks.
* **v0.92.0:** Math in every number field (`16*3`, `+=2`), an undo history panel, and settings search in **Ctrl+K**.

See every change on the [Releases page](https://github.com/kinsocial1-del/ForgeStudio/releases).

---

## ⚡ Why Forge Studio?

* **Small and self-contained:** No huge downloads and no external SDKs to install. Open it and start building.
* **Full 3D & 2D Engines:** Custom WebGL2 renderer with PBR materials, soft shadows, dynamic point and spot lights, bloom, screen-space reflections, depth of field, volumetric fog and ACES tone mapping, plus authentic retro displays (CRT, Game Boy, NES, SNES, PS1 vertex wobble).
* **Code Your Way:**
  * **Plain JavaScript:** Full object lifecycle scripting (`onStart`, `onUpdate`, `onTouch`, `onKey`, `onHit`, `onMessage`) with live code reloading during Play mode and a built-in script debugger.
  * **Visual Node-Graphs:** Blueprint-style visual scripting linking events, conditions, and actions with wired value pins.
  * **No-Code Rules:** Rapid event-driven triggers (`WHEN ... ONLY IF ... DO ...`).
* **A fast editor:** Command palette that finds any command, object or setting; undo history; drag-to-scrub and math in number fields; prefabs; terrain sculpting; timeline and cutscene tools.
* **Batteries Included:**
  * 400+ built-in CC0 3D models and 2D sprites.
  * Rigged FBX and glTF skeletal animation with Mixamo support, animation layers, foot-placement and look-at IK.
  * 2D/3D physics, capsule character controllers, continuous collision (no wall tunnelling), springs, hinges, ragdolls and destructible props.
  * AI brains (chase, patrol, flee, guard) with 3D multi-floor navigation meshes.
  * Branching dialogue, quests, decals, particles and ribbon trails.
  * Built-in 32-player online multiplayer with encrypted connections.
  * One-click export to a standalone HTML game that runs in a web browser, or a Windows executable (exported from the Windows version).

---

## 🔒 About Software Distribution

Forge Studio is distributed as a compiled desktop application for Windows, macOS and Linux.

* **Proprietary Engine Core:** GitHub automatically attaches generic *"Source code"* links to release tags, but those contain only this page. The engine core and editor are proprietary software and are not published.
* **Game Scripting & Creation:** You do **not** need the engine's source code to create games. You write all game logic, behaviors and gameplay inside Forge Studio using **standard JavaScript (ES6+)**, visual node-graphs and logic rules.

---

## License

Forge Studio is proprietary software. It is free to download and use, and the games you make with it are yours to sell and share. Copying, redistributing or modifying Forge Studio itself is not permitted. See [LICENSE](LICENSE) for the full terms.
