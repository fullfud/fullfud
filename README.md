<h1 align="center">fullfud</h1>

<p align="center">
  Game engines, real-time physics, rendering and the servers behind them.<br>
  Java · Rust · Linux
</p>

<p align="center">
  <a href="https://modrinth.com/user/fullfud"><img src="https://img.shields.io/badge/Modrinth-fullfud-1bd96a?style=flat-square&logo=modrinth&logoColor=white" alt="Modrinth"></a>
  <a href="https://www.curseforge.com/members/fullfud/projects"><img src="https://img.shields.io/badge/CurseForge-fullfud-f16436?style=flat-square&logo=curseforge&logoColor=white" alt="CurseForge"></a>
  <img src="https://img.shields.io/badge/mod%20downloads-58k%2B-2b2b2b?style=flat-square" alt="58k+ downloads">
</p>

---

### What I do

- **Game mods and engines.** Minecraft mods on Forge, NeoForge and Fabric, and a voxel engine written from scratch in Rust.
- **Physics and rendering.** Flight and vehicle dynamics on the Jolt engine, client-side prediction for networked vehicles, GLSL post-processing (FXAA, TAA, upscaling, lighting and shadows).
- **Servers and infrastructure.** Linux services behind nginx and systemd, automated deploys with GitHub Actions, TLS, signed update manifests and security reviews.
- **Measuring everything.** Profilers, frame-time and memory benchmarks, differential test harnesses against a reference implementation. A change counts only when the numbers move.
- **AI as a power tool.** I work with coding agents (Claude Code) the way a lead works with a team: I design the system, split the work, review every change and prove it with tests and measurements.

### Featured

<table>
<tr>
<td width="50%" valign="top">
<a href="https://modrinth.com/mod/shaded-war"><img src="https://cdn.modrinth.com/data/NLOHh3Kg/images/a198b2f5758c79bfdee8d34b45585eb7b1bb4f47_350.webp" alt="Shaded War" width="100%"></a>
<h4><a href="https://modrinth.com/mod/shaded-war">Shaded War</a></h4>
FPV drone mod for Forge 1.20.1: flight physics, goggles and first-person control, gamepad support with in-game calibration, signal jamming, custom HUD and post-processing shaders, server-authoritative drones that stay controllable across unloaded chunks.<br><br>
<a href="https://modrinth.com/mod/shaded-war"><img src="https://img.shields.io/modrinth/dt/shaded-war?style=flat-square&logo=modrinth&label=Modrinth&color=1bd96a" alt="Modrinth downloads"></a>
<a href="https://www.curseforge.com/minecraft/mc-mods/shaded-war-3-0"><img src="https://img.shields.io/curseforge/dt/1774202?style=flat-square&logo=curseforge&label=CurseForge&color=f16436" alt="CurseForge downloads"></a>
</td>
<td width="50%" valign="top">
<a href="https://modrinth.com/mod/dirtyaliasing"><img src="https://cdn.modrinth.com/data/kKmFt5JM/images/b0f7f5692179d86460abe1bda4a0ed20b440319b_350.webp" alt="DirtyAliasing" width="100%"></a>
<h4><a href="https://modrinth.com/mod/dirtyaliasing">DirtyAliasing</a></h4>
Anti-aliasing (FXAA and TAA) and CAS upscaling as a lightweight post-processing pass. One code base for Fabric, Forge and NeoForge.<br><br>
<a href="https://modrinth.com/mod/dirtyaliasing"><img src="https://img.shields.io/modrinth/dt/dirtyaliasing?style=flat-square&logo=modrinth&label=Modrinth&color=1bd96a" alt="Modrinth downloads"></a>
<a href="https://www.curseforge.com/minecraft/mc-mods/dirtyaliasing"><img src="https://img.shields.io/curseforge/dt/1402087?style=flat-square&logo=curseforge&label=CurseForge&color=f16436" alt="CurseForge downloads"></a>
</td>
</tr>
</table>

**Server plugins (Paper / Spigot):**
[RandomLoot](https://github.com/fullfud/RandomPlugin), randomized chest loot ·
[LightSelector](https://github.com/fullfud/LightSelector), save and toggle light blocks

### In progress (closed source for now)

| Project | What it is | Built with |
|---|---|---|
| **Ruxel** | Voxel game engine written from scratch, checked against the reference game by 281 differential test harnesses. Runs on Linux, macOS and Windows. 700+ commits. | Rust, wgpu, CI |
| **Varr** | Game launcher with its own backend: signed content and update manifests, certificate pinning, device attestation, admin panel. Deployed to a Linux VPS behind nginx and systemd through GitHub Actions. | Rust, Tauri, TypeScript, Linux |
| **Trainworks** | Metro and train mod: own track system, block-built tunnels, Jolt physics, real-time lighting and shadows, NPC system. 600+ commits. | Java, GLSL, Jolt |
| **Vehicle physics** | Contributor to a Jolt-based vehicle mod: client-side prediction, aircraft flight models, damage, native physics libraries built for Windows and Linux. | Java, C++, JNI |

### Toolbox

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/GLSL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="GLSL">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <br>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="nginx">
  <img src="https://img.shields.io/badge/systemd-30D475?style=flat-square&logo=linux&logoColor=black" alt="systemd">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
</p>
