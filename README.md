<div align="center">

# Lattice

### Local couch co-op for Windows games

Give extra local players their own keyboard, mouse, cursor, and game window on one PC.

[![Downloads](https://img.shields.io/badge/Downloads-files.bide.cx-00cce4?style=for-the-badge)](https://files.bide.cx/)
[![GitHub Release](https://img.shields.io/badge/GitHub-release-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bideco/lattice-weaver/releases/latest)
[![Minecraft on Modrinth](https://img.shields.io/badge/Modrinth-latticework-00af5c?style=for-the-badge&logo=modrinth&logoColor=white)](https://modrinth.com/mod/latticework)
[![Buy License](https://img.shields.io/badge/Buy%20license-%2414.99-f59e0b?style=for-the-badge&logo=polar&logoColor=white)](https://buy.polar.sh/polar_cl_qnTeBhgJpeI7j7WgCHctmznEsHK9W5wrLsQaV33itbu)

</div>

---

<p align="center">
  <img src="assets/minecraft-dual-instance-coop.png" alt="Two Minecraft instances controlled by two local players on one PC" width="900">
</p>

## What Lattice Does

Lattice is a Windows companion app plus game-side adapters for local multi-player setups that normally need multiple PCs.

- Player 0 keeps native Windows control.
- Additional players use selected keyboards and mice assigned through Lattice Weaver.
- Supported game windows receive the right player's input through their adapter.
- Each player can have an independent cursor, settings profile, and slot status.
- Setup is handled through Weaver's guided device flow.

## Supported Games

| Game | Status | Notes |
| --- | --- | --- |
| Minecraft Java | Supported | Fabric builds for Minecraft `1.20` through `26.1.2`. |
| Paralives | Supported | Plugin adapter for routed second-player mouse and keyboard input. |
| Developer adapters | Public devkit | SDKs, schemas, and sample manifests for adapter developers. |

Experimental adapters are not listed here until they are release-ready.

## Lattice Weaver

<p align="center">
  <img src="assets/weaver-dashboard.png" alt="Lattice Weaver dashboard showing player slots and device status" width="780">
</p>

Weaver is the Windows companion app. It handles player slots, guided setup, device assignment, profile selection, and game-adapter connections.

Download Weaver and current game files from:

**https://files.bide.cx/**

## Minecraft

<p align="center">
  <img src="assets/minecraft-master-settings-screen.png" alt="Minecraft master settings screen for controlling routed player instances" width="780">
</p>

The Minecraft adapter adds the in-game side of Lattice:

- Per-slot HUD and virtual cursor.
- P0 master controls for routed player instances.
- Audio, video, resource-pack, profile, and selected mod-config controls.
- Lockable settings for routed players where supported.
- MultiMC-style JVM setup support through Weaver.

Minecraft users can also install through Modrinth:

**https://modrinth.com/mod/latticework**

## Paralives

<p align="center">
  <img src="assets/paralives-routed-input.jpg" alt="Paralives receiving routed second-player input from Lattice" width="780">
</p>

The Paralives adapter routes an additional player's mouse and keyboard into the game while Player 0 remains native.

## Developer Devkit

<p align="center">
  <img src="assets/devkit-package.png" alt="Lattice Devkit package" width="720">
</p>

The public devkit includes adapter schemas, sample manifests, Java and C# SDK surfaces, and adapter contract notes.

Weaver remains closed-source. The devkit exposes only the public adapter surface for supported-game integrations.

Download the devkit from:

**https://files.bide.cx/Lattice-Devkit.zip**

## Links

| Destination | Link |
| --- | --- |
| Downloads | https://files.bide.cx/ |
| Latest GitHub release | https://github.com/bideco/lattice-weaver/releases/latest |
| Minecraft mod | https://modrinth.com/mod/latticework |
| License purchase | https://buy.polar.sh/polar_cl_qnTeBhgJpeI7j7WgCHctmznEsHK9W5wrLsQaV33itbu |
| Support | support@bide.cx |
| Orders | orders@bide.cx |

---

<div align="center">

### bideco

solo maker · Windows tooling · game adapters

</div>
