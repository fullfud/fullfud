<h1 align="center">fullfud</h1>

<p align="center">
  I make games and game mods work the way they would in real life.<br>
  Mostly Java and Rust, usually on Linux
</p>

<p align="center">
  <a href="https://modrinth.com/user/fullfud"><img src="https://img.shields.io/badge/Modrinth-fullfud-1bd96a?style=flat-square&logo=modrinth&logoColor=white" alt="Modrinth"></a>
  <a href="https://www.curseforge.com/members/fullfud/projects"><img src="https://img.shields.io/badge/CurseForge-fullfud-f16436?style=flat-square&logo=curseforge&logoColor=white" alt="CurseForge"></a>
  <img src="https://img.shields.io/badge/mod%20downloads-58k%2B-2b2b2b?style=flat-square" alt="58k+ downloads">
</p>

---

### About me

I started with small server plugins and ended up writing physics, renderers and whole engines. Most of my time goes into Minecraft mods for Forge, NeoForge and Fabric, and lately into a voxel engine I'm building from scratch in Rust.

I like the parts most people skip. Flight and vehicle physics on Jolt, client prediction so driving feels smooth on a laggy server, shaders for anti-aliasing and lighting. I also run my own Linux server for one of my projects with nginx and systemd, and it deploys itself through GitHub Actions.

I don't trust a change until I've measured it. Profilers, frame time and memory benchmarks, tests that compare my engine against the original game. If the numbers didn't move, the change didn't happen.

I use AI coding agents (Claude Code) a lot, and I'm the one in charge. I know how the system has to work, I split the job into pieces, read what comes back and throw out what's wrong. It lets me build much bigger things than I could alone, but it doesn't replace understanding the code.

### Things people actually use

<table>
<tr>
<td width="50%" valign="top">
<a href="https://modrinth.com/mod/shaded-war"><img src="https://cdn.modrinth.com/data/NLOHh3Kg/images/a198b2f5758c79bfdee8d34b45585eb7b1bb4f47_350.webp" alt="Shaded War" width="100%"></a>
<h4><a href="https://modrinth.com/mod/shaded-war">Shaded War</a></h4>
An FPV drone mod for Forge 1.20.1. You put on the goggles and fly with real drone physics, and a gamepad works too after a quick calibration in game. There is signal jamming, a custom HUD with camera shaders, and drones keep flying even when you fly them far into unloaded chunks.<br><br>
<a href="https://modrinth.com/mod/shaded-war"><img src="https://img.shields.io/modrinth/dt/shaded-war?style=flat-square&logo=modrinth&label=Modrinth&color=1bd96a" alt="Modrinth downloads"></a>
<a href="https://www.curseforge.com/minecraft/mc-mods/shaded-war-3-0"><img src="https://img.shields.io/curseforge/dt/1774202?style=flat-square&logo=curseforge&label=CurseForge&color=f16436" alt="CurseForge downloads"></a>
</td>
<td width="50%" valign="top">
<a href="https://modrinth.com/mod/dirtyaliasing"><img src="https://cdn.modrinth.com/data/kKmFt5JM/images/b0f7f5692179d86460abe1bda4a0ed20b440319b_350.webp" alt="DirtyAliasing" width="100%"></a>
<h4><a href="https://modrinth.com/mod/dirtyaliasing">DirtyAliasing</a></h4>
Minecraft without the jagged edges. FXAA or TAA plus CAS upscaling in one light post-processing pass, and the same code runs on Fabric, Forge and NeoForge.<br><br>
<a href="https://modrinth.com/mod/dirtyaliasing"><img src="https://img.shields.io/modrinth/dt/dirtyaliasing?style=flat-square&logo=modrinth&label=Modrinth&color=1bd96a" alt="Modrinth downloads"></a>
<a href="https://www.curseforge.com/minecraft/mc-mods/dirtyaliasing"><img src="https://img.shields.io/curseforge/dt/1402087?style=flat-square&logo=curseforge&label=CurseForge&color=f16436" alt="CurseForge downloads"></a>
</td>
</tr>
</table>

For Paper and Spigot servers I also made [RandomLoot](https://github.com/fullfud/RandomPlugin), which fills chests with random loot, and [LightSelector](https://github.com/fullfud/LightSelector) for saving and toggling light blocks.

### What I'm working on now

The source for these is closed for now.

**Ruxel** is a voxel game engine I'm writing from scratch in Rust with wgpu. It runs on Linux, macOS and Windows, and 281 test harnesses check that it behaves exactly like the original game. Over 700 commits so far.

**Varr** is a game launcher with its own backend. The server runs on a Linux VPS behind nginx and systemd and deploys through GitHub Actions. Updates and content are signed, the client pins certificates and checks that it hasn't been tampered with, and there's an admin panel for managing builds.

**Trainworks** is a metro and train mod with its own track system, tunnels built from blocks, Jolt physics, real-time lights and shadows and NPCs. Over 600 commits.

I also help on a vehicle mod built on Jolt. I did client-side prediction, aircraft flight models and damage there, and I build the native physics libraries for Windows and Linux myself.

### What I work with

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
