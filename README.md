# 🔨 Forge Studio

**A lightweight, fast 2D and 3D game creator for Windows, macOS and Linux.**

Forge Studio is a desktop editor for building 2D and 3D games. Create levels, add gameplay, write scripts and test your game in one workspace. It is free to download and use, and the games you make are yours to sell and share.

[Visit the website](https://forgestudio-engine.neoncove32.chatgpt.site) · [Download Forge Studio](https://github.com/kinsocial1-del/ForgeStudio/releases/latest) · [Send feedback](https://github.com/kinsocial1-del/ForgeStudio/issues/new/choose)

[![Forge Studio 3D editing workspace](https://forgestudio-engine.neoncove32.chatgpt.site/assets/editor-3d.png)](https://forgestudio-engine.neoncove32.chatgpt.site/#workspace)

---

## 🚀 Downloads (Latest Release: v0.112.1)

| Platform | Direct Download | Notes |
| :--- | :--- | :--- |
| **Windows Installer** | [**Forge.Studio.Setup.0.112.1.exe**](https://forge-studio-downloads.forgestudio.workers.dev/v0.112.1/Forge.Studio.Setup.0.112.1.exe) | Recommended. Standard setup with in-app updates and desktop integration |
| **Windows Portable** | [**Forge.Studio.exe**](https://github.com/kinsocial1-del/ForgeStudio/releases/latest/download/Forge.Studio.exe) | Single file; run from any folder or USB drive. No in-app updates |
| **macOS** (Intel & Apple Silicon) | [**Forge.Studio-0.112.1-mac.dmg**](https://github.com/kinsocial1-del/ForgeStudio/releases/download/v0.112.1/Forge.Studio-0.112.1-mac.dmg) | Drag into Applications. See [first launch on Mac](#-first-launch-on-macos) |
| **Linux** (x64) | [**Forge.Studio-0.112.1-linux.AppImage**](https://forge-studio-downloads.forgestudio.workers.dev/v0.112.1/Forge.Studio-0.112.1-linux.AppImage) | `chmod +x` the file, then run it. Updates in-app |

> **Already installed?** Get new features and fixes inside the app with **Help → Check for updates**. Release notes and older versions are on the [Releases page](https://github.com/kinsocial1-del/ForgeStudio/releases).

### 🍎 First launch on macOS

v0.103.13 and newer Mac releases are signed with an Apple Developer ID and notarized by Apple. Open the disk image, drag Forge Studio into **Applications**, then launch it.

If you have an older unsigned Mac copy, install the signed app once to enable future in-app updates. Your projects are kept. After that, use **Help → Check for updates** to download and restart into newer signed versions.

### 💻 System requirements

| | Minimum |
| :--- | :--- |
| **Windows** | Windows 10 or 11, 64-bit |
| **macOS** | A recent macOS version, Intel or Apple Silicon |
| **Linux** | 64-bit distribution that runs AppImages (some need `libfuse2`) |
| **Graphics** | A GPU with WebGL2 support for 3D levels (most GPUs from the last decade). 2D works everywhere |

---

## ✨ What's new

* **v0.112.1:** Keep the follow camera clear above ramp slopes, including rotated ramps, while preserving collision protection and smooth recovery in Play and exported games.

* **v0.112.0:** Build while playing now places additions on supported terrain, ramps and rotated box floors. Footprint, slope, edge, height and obstacle checks improve placement; temporary or moved supports are excluded so saved additions retain their ground after Play stops.

* **v0.111.0:** Browse all 23 supported game starters with dimension and objective previews. More responsive jumping in new walking starters, with editable early-input buffering and late-edge grace. Refined project hub, description and Play builders, conversion cards and import reports keep controls visible through long content.

* **v0.110.0:** Import complete model packs with clear per-file results and single-step Undo. Convert Unity source artwork/audio without Unity, or Blender scenes through an installed Blender 3.6+ using Add asset → Convert assets…. Native prefab logic and Unreal packages still require rebuilding or source-engine export.

* **v0.109.0:** Original Expedition and Foundry art kits, looping props and seven editable themed scores improve generated adventures. Smoother third-person camera recovery and readable, locked-aim enemy firing warnings improve movement and combat. Better robot-count prompts, mixed-environment previews and animation restart reliability.

* **v0.108.0:** Create editable prototypes across 23 game types. Improved adventure scenery, animated actors, melee combos and dash; detailed briefs, exclusions, separate sword/Fireball abilities and ordered relative edits such as “double enemies, then remove two.” Review supported settings and preset limitations before creating.

* **v0.107.0:** Build with descriptions during editor Play mode. Preview and add monsters, crystals, healing pickups and scenery near your player, then continue without resetting gameplay. Keep additions in saved projects and exports, with Undo after stopping.

* **v0.106.0:** Create 1–5 level adventures from a description, with ordered environments, winding trails, varied enemy patrols, ranged combat and live objectives. Carry health and XP between levels; every generated scene remains editable.

* **v0.105.1:** Review exactly what each description refinement changes and undo earlier edits before creating a game. Keep health potion counts separate from player health and understand “two more monsters.”

* **v0.105.0:** Build richer offline games with seven recipes, editable creation plans and follow-up instructions. Generate dressed RPG/shooter/exploration worlds, quests, bosses and pickups; improve platformer placement and prompt interpretation.

* **v0.104.0:** Create editable RPGs and platformers from a description using free offline recipes. Preview the plan, then build with bundled characters, combat, health and XP. Also improves scene/hierarchy keyboard controls and command search.

* **v0.103.13:** Protect unsaved scripts when switching projects, save scripts with a keyboard shortcut, read clearer errors and debugger watch instructions, and receive signed Mac updates.

* **v0.103.8:** A refined editor interface, clearer search and asset workflows, unsaved script protection, and improved keyboard and screen-reader accessibility.

* **v0.103.7:** Send feedback from Help to the public GitHub issue form, plus improved script indentation and selected-line Tab/Shift+Tab editing.

* **v0.103.6:** Offline Python and Lua scripting, an experimental GDScript syntax subset, and GPU/frame-rate diagnostics. See the script editor references for runtime and compatibility limits.

* **v0.103.1:** GPU geometry caches retain recently drawn models, terrain and meshes, reducing unnecessary uploads when other assets enter the cache.

* **v0.103.0:** Faster imported-model startup, shared per-frame asset preparation, indexed lookup, reliable asset replacement, configurable CPU cache budgets and profiler cache diagnostics.

* **v0.102.2:** Fixed imported PBR-only model UVs, shared texture sampler interference, per-map glTF wrapping and zero normal-map strength.

* **v0.102.1:** Fixed first-sound mixer routing, stale imported audio after replacement, decode retry handling, cache growth and boosted music volume errors.

* **v0.102.0:** Material-aware glossy reflections with roughness blur and metallic tint, correct PBR maps on instanced objects, working emissive maps on primitives, and reduced reflection overhead when disabled.

* **v0.101.1:** Corrected triplanar normal maps, reflection camera projection and sharpening halos, with real WebGL rendering regression checks.

* **v0.101.0:** Contrast-Adaptive Sharpening (CAS) for razor-sharp micro-textures without halo artifacts, cinematic anamorphic bloom lens streaks, and physical solar limb darkening with high-density corona and ice-crystal halo.
* **v0.100.9:** Ground-Truth Ambient Occlusion (GTAO) with multi-bounce interreflections, Screen-Space Contact Shadows (SSCS), Toksvig specular anti-aliasing, and golden-hour Rayleigh atmosphere scattering.
* **v0.100.8:** Full PBR texture map pipeline (Normal with strength scaling, ORM with AO extraction, Emissive glow) and enhanced Modern visual style with volumetric mist, god rays, and SSR.
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
  * **Python and Lua:** Offline gameplay scripting through bundled Skulpt (Python 3 mode) and Fengari (Lua 5.3), with language-specific examples and the Forge gameplay API.
  * **Experimental GDScript subset:** Familiar syntax for Forge behaviours; Godot APIs and addons require porting.
  * **Plain JavaScript:** Full object lifecycle scripting (`onStart`, `onUpdate`, `onTouch`, `onKey`, `onHit`, `onMessage`) with live code reloading during Play mode and a built-in script debugger.
  * **Visual Node-Graphs:** Blueprint-style visual scripting linking events, conditions, and actions with wired value pins.
  * **No-Code Rules:** Rapid event-driven triggers (`WHEN ... ONLY IF ... DO ...`).
* **A fast editor:** Command palette that finds any command, object or setting; undo history; drag-to-scrub and math in number fields; prefabs; terrain sculpting; timeline and cutscene tools.
* **Batteries Included:**
  * 400+ built-in CC0 3D models and 2D sprites.
  * Rigged FBX and glTF skeletal animation with Mixamo support, animation layers, foot-placement and look-at IK.
  * 2D/3D physics, capsule character controllers, continuous collision (no wall tunnelling), springs, hinges, ragdolls and destructible props.
  * NPC behaviours (chase, patrol, flee, guard) with 3D multi-floor navigation meshes.
  * Branching dialogue, quests, decals, particles and ribbon trails.
  * Built-in 32-player online multiplayer with encrypted connections.
  * One-click export to a standalone HTML game that runs in a web browser, or a Windows executable (exported from the Windows version).

---

## 🔒 About Software Distribution

Forge Studio is distributed as a compiled desktop application for Windows, macOS and Linux.

* **Proprietary Engine Core:** GitHub automatically attaches generic *"Source code"* links to release tags, but those contain only this page. The engine core and editor are proprietary software and are not published.
* **Game Scripting & Creation:** You do **not** need the engine's source code to create games. Build gameplay inside Forge Studio using **JavaScript, Python or Lua**, visual node-graphs and event rules. An experimental GDScript syntax subset is also available; Godot APIs and addons require porting.

---

## License

Forge Studio is proprietary software. It is free to download and use, and the games you make with it are yours to sell and share. Copying, redistributing or modifying Forge Studio itself is not permitted. See [LICENSE](LICENSE) for the full terms.
