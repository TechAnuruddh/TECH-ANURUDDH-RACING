# TECH ANURUDDH RACING

**A browser-based Formula racing game built with Three.js, TypeScript and Vite. Experience high-speed racing with realistic vehicle physics, intelligent AI drivers, dynamic weather, procedural 3D cars, multiple circuits and immersive audio.**

Live Play Game:= https://techanuruddh.github.io/TECH-ANURUDDH-RACING/?utm_source=chatgpt.com

TECH ANURUDDH RACING is a customized, rebranded version of the original APEX FORMULA project. The game runs directly in a modern web browser using WebGL2. Cars, circuits, textures, sounds and voice lines are generated procedurally at runtime, with no external asset files required.

**Project Branding:** TECH ANURUDDH RACING  
**Version:** v1.0.0  
**Developer / Project Branding:** Tech Anuruddh  
**Game Engine:** Three.js

---

## About the Project

TECH ANURUDDH RACING brings a Formula racing experience to the browser without requiring a separate game installation.

The original game was built by Claude Fable 5.1 working as a lead agent with ten parallel sub-agents, each responsible for a specific module of the codebase under a shared architecture contract.

The original architecture documentation is available in [ARCHITECTURE.md](ARCHITECTURE.md).

## Game Features

- **Six Racing Circuits:** Kingsmere Circuit, Porto Azzurro Street Circuit, Al Sahra International, Circuit de la Riviera, Schwarzwald Ring and Autodromo Velocità.
- **Ten Teams and Twenty Drivers:** Procedural liveries, driver decals, helmets, personalities and pace profiles.
- **Advanced Vehicle Physics:** 120 Hz physics simulation, independent suspension, tyre temperature and wear, aerodynamic downforce, drag, DRS, ERS, gearbox and collision systems.
- **Intelligent AI Drivers:** Racing lines, overtaking, defending, pit strategies, qualifying laps and difficulty-based driving behaviour.
- **Race Director:** Formation lap, starting lights, lap timing, penalties, flags, pit stops, weather evolution, team radio and race results.
- **Procedural 3D Cars:** Detailed car models featuring wings, halo, suspension, steering wheel, driver, tyres and damage states.
- **Broadcast-Style HUD:** Timing tower, speed, gear, RPM, ERS, DRS, minimap, sector times, race-control ticker and weather information.
- **Multiple Camera Modes:** Chase, cockpit, T-cam, nose, trackside TV, helicopter and cinematic cameras.
- **Instant Replay:** Replay the last 90 seconds with scrubbing and playback speed controls.
- **Procedural Audio:** Engine sounds, turbo, gear shifts, tyre squeal, collisions, crowd, menu music and team radio.
- **Visual Effects:** Tyre smoke, sparks, rain, spray, skid marks, debris, confetti and other racing effects.
- **Graphics Settings:** Quality presets ranging from low to ultra.

## Game Modes

- Quick Race
- Time Trial
- Grand Prix Weekend

Grand Prix Weekend includes an eight-minute qualifying session to determine the starting grid.

Additional gameplay options include dry, wet and dynamic weather, with up to 19 AI drivers.

## Controls

| Action | Keyboard | Gamepad |
|---|---|---|
| Throttle / Brake | W / S or Up / Down | RT / LT |
| Steering | A / D or Left / Right | Left Stick |
| Shift Up / Down | E / Shift / Q / Ctrl | A / B |
| DRS | Space | X |
| ERS Overtake | R | Y |
| Cycle ERS Mode | V | — |
| Pit Limiter | L | — |
| Request Pit Stop | P | — |
| MFD Toggle / Previous / Next | Tab / , / . | D-pad |
| Change Camera | C | RB |
| Look Back | B | LB |
| Reset Car | Backspace | Right Stick Click |
| Instant Replay | I | Back |
| Toggle HUD / Mute | H / M | — |
| Team Radio | T | — |
| Pause | Esc | Start |

**Menu Navigation:** Use Arrow Keys, WASD or D-pad to navigate. Press Enter, Space or A to confirm and Esc or B to go back.

## Technologies Used

| Technology | Purpose |
|---|---|
| TypeScript 7 | Main programming language |
| Three.js 0.185 | 3D graphics and rendering |
| Vite 8 | Development server and build tool |
| WebGL2 | Browser-based graphics rendering |
| HTML5 / CSS3 | User interface and styling |

**Runtime Dependencies:** Three.js only.

## Run Locally

### Prerequisites

- Node.js
- npm
- A modern browser supporting WebGL2
- VS Code (recommended)

### Installation

1. Download or clone the project repository.
2. Open the project folder in VS Code.
3. Open the integrated terminal.
4. Install dependencies:

```bash
npm install
```

5. Start the development server:

```bash
npm run dev
```

6. Open the local URL printed by Vite. By default:

```text
http://localhost:5200/
```

### Available Commands

| Command | Description |
|---|---|
| `npm run dev` | Start the development server with hot reload |
| `npm run typecheck` | Run TypeScript type checking |
| `npm run build` | Generate the production build in `dist/` |
| `npm run preview` | Preview the production build |

## Project Architecture

The original project uses a modular architecture where different systems are separated by responsibility.

| Module | Responsibility |
|---|---|
| Render | HDR pipeline, sky, lighting, shadows and post-processing |
| Track | Circuit geometry, kerbs, barriers, scenery and grandstands |
| Car | Procedural F1 car models, liveries, animation and damage |
| Physics | Vehicle dynamics, tyres, aerodynamics and collisions |
| AI | Racing lines, overtaking, racecraft and difficulty |
| Race | Timing, positions, flags, penalties, pit stops and weather |
| UI | Menus, HUD, settings and replay controls |
| Audio | Engine sounds, effects, music and radio |
| Input / Camera / Replay | Keyboard, gamepad, camera modes and replay |
| VFX | Particles, weather, skid marks and visual effects |

For more information, see [ARCHITECTURE.md](ARCHITECTURE.md).

## Project Structure

```text
TECH-ANURUDDH-RACING/
│
├── src/
│   ├── core/
│   ├── render/
│   ├── track/
│   ├── car/
│   ├── physics/
│   ├── ai/
│   ├── race/
│   ├── ui/
│   ├── audio/
│   ├── input/
│   └── vfx/
│
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
├── ARCHITECTURE.md
└── README.md
```

*Note: The folder listing above is a simplified overview of the original project architecture.*

## Development Notes

- The game is designed to run in a modern browser.
- WebGL2 support is required.
- Most visual and audio elements are procedurally generated.
- The original game architecture and gameplay systems are retained in this rebranded version.

## Credits and License

TECH ANURUDDH RACING is based on the original **APEX FORMULA** project by BridgeMind.

The original project credits Claude Fable 5.1 and its parallel sub-agent architecture.

Original Repository: https://github.com/bridge-mind/apex-formula

This project retains the original MIT License and attribution.

**Copyright © 2026 BridgeMind.**

See the [LICENSE](LICENSE) file for the complete license terms.

---

**TECH ANURUDDH RACING**  
*Twenty Cars. One Apex. No Mercy.*
