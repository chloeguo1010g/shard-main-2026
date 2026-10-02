# Shard — A C# Game Engine

Shard is a lightweight game engine developed collaboratively as part of
the Game Engine Architecture course. Building on the course-provided
Shard foundation, our team expanded its functionality and integrated
additional systems for creating playable 2D game demos.

The project explores how engine subsystems work together, from
rendering and input handling to physics, animation, UI, and audio.

## Features

- **Rendering and assets**
  SDL3-based rendering, text rendering, and asset loading.

- **Game objects and physics**
  Game-object lifecycle management, transforms, collision detection,
  and basic physics simulation.

- **Scene management**
  Scene lifecycle handling and transitions between menus, gameplay,
  and result screens.

- **Animation**
  Sprite animation with configurable clips, playback modes,
  and playback speed.

- **User interface**
  Reusable UI elements, including buttons, labels, panels, and
  dropdowns, with asset-driven layouts and event handling.

- **Audio**
  Music and sound-effect playback through SDL3_mixer, with volume
  controls and audio resource management.

- **Score persistence**
  JSON-based score storage and per-game leaderboard queries.

## Demo Games

The repository includes several demos that illustrate how games can
use the engine's systems, including:

- Missile Command
- Breakout
- Space Invaders
- Manic Miner
- Animation and scoring demos

Some demos originate from the course framework and are retained
alongside the team's extensions.

### UI Demo

The default configuration launches `GameMissileCommand` with a
UI-driven start menu.

The menu includes an animated sprite demonstration. The Settings
screen provides a frame-limit dropdown with `30`, `60`, `120`, and
`Unlimited` options, applied during the current session.

## Technology

- C#
- .NET 9
- SDL3
- SDL3_image
- SDL3_mixer
- SDL3_ttf

## Repository Structure

- `ConsoleApp1/Shard/` — Engine subsystems
- `ConsoleApp1/Shard/UI/` — UI components and interaction handling
- `ConsoleApp1/GameTest/` — Gameplay and scene demonstrations
- `ConsoleApp1/` — Additional demo games
- `Assets/` — Game assets and associated credits

## Project Background

This version of Shard is the result of a collaborative student
project. Team members contributed to engine extensions, subsystem
integration, and demonstration content.

The engine builds on the Shard teaching framework provided for the
Game Engine Architecture course. The original framework's release
history and credits are preserved in
[Upstream Changelog](docs/UPSTREAM_CHANGELOG.md).

## Scope and Limitations

Shard is an educational engine rather than a production-ready
framework. It is not feature-complete and may contain bugs.

Its purpose is to support experimentation with engine architecture
and provide a foundation for small demonstration games.

## Credits

Thanks to the course instructor and the original Shard contributors
for providing the teaching framework.

Third-party assets remain subject to their respective licenses and
credits. Please refer to the accompanying asset documentation.
