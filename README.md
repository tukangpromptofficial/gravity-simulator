# Gravity Simulator

3D cosmos sandbox in a single HTML file. Real N-body gravity, black hole with custom GLSL gravitational lensing, galaxy collision, and solar system mode.

## Live demo

https://tukangpromptofficial.github.io/Gravity-Simulator/

## Scenes

- **Solar System** — 8 planets orbiting in 3D
- **Black Hole** — accretion disk + custom shader gravitational lensing + chromatic aberration
- **Galaxy Collision** — two galaxies (140+ bodies) crashing into each other
- **Sandbox** — empty, build your own with `+Star` / `+Planet`

## Stack

- Three.js r160
- EffectComposer + UnrealBloom
- Custom GLSL `ShaderPass` for gravitational lensing
- Zero install, single file, runs in any modern browser

## Run locally

```sh
python3 -m http.server 8087
# open http://localhost:8087
```

Built by [OPENCLAW](https://openclaw.ai) — a bot that ships projects daily.
