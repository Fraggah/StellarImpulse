# StellarImpulse

<img width="3839" height="2159" alt="image" src="https://github.com/user-attachments/assets/80ada1e5-4e72-4340-9093-d77ec9f6fa23" />

<img width="3839" height="2157" alt="image" src="https://github.com/user-attachments/assets/2227caf8-f066-4159-bb24-2669bb133bb4" />

<img width="3839" height="2159" alt="image" src="https://github.com/user-attachments/assets/1e4bdbdc-d59b-4665-bd97-88a8e68d52a3" />

**Genre:** Endless Runner (Spaceship)  
**Engine:** Unreal Engine 5 (Blueprints)  
**Platform:** PC (Windows) — scalable to others

Neon-styled endless runner where you pilot a spaceship through procedurally generated obstacle fields. Master horizontal positioning and ship roll to thread tight gaps while the world streams forward infinitely. Includes a graphics settings menu for quick performance tuning.

---

## ✨ Key Features

- **Procedural Obstacle System**
  - Chunk-based spawning with deterministic random seeds.
  - Weighted obstacle archetypes (walls, rotating gates, moving pillars).
  - Difficulty ramps via spawn density, gap size, and obstacle velocity curves.

- **Tight Flight Controls**
  - Horizontal lane/analog drift (A/D or Left/Right).
  - **Roll/Bank** on turn input for readable motion (auto-level with dampening).
  - Acceleration curve + speed caps to keep the flow readable at high speeds.

- **Endless Level Streaming**
  - Fixed-length “track chunks” pooled and recycled ahead of the player.
  - Kill volume + safe despawn behind camera to keep memory stable.

- **Neon Aesthetic**
  - Emissive materials + bloom/post-process for glow.
  - Niagara trails, engine thrusters, impact sparks.
  - Color palette driven by Material Instances (easy theme swaps).

- **Graphics Settings Menu**
  - Resolution, fullscreen/windowed, VSync.
  - Scalability presets (ViewDistance, Shadows, Post, Effects, Foliage).
  - Motion blur toggle, AA method, bloom intensity slider.

- **Game Loop & UX**
  - Start → Run → Score/Distance tracking → Game Over → Restart.
  - Die on collision or time-out in “survival challenges”.
  - Basic leaderboard stub (local; ready for backend hook).
 
  - **Niagara Particles Systems**
