# Golden Gate Sprint

Model: GPT-5.4-Pro Extended

## Prompt

```text
Create a visually clean, high-impact arcade racing sprint on the Golden Gate Bridge. Start in motion immediately; no blocker screen, no click-to-start.

If you use Three.js, add an import map (before the module script) mapping "three" and "three/addons/" to the same pinned version, and import only via those names. Never reuse identifiers in the same scope; use descriptive variable names.

#### VISUAL TARGET

- Opening shot: full-speed run under a tower with International Orange dominating frame.
- Dense but readable traffic, bright lane highlights, clear bay horizon and cable silhouette.
- Near-miss effects should be punchy and short, never blinding.

#### GAME LOOP (10-20s)

- Survive a 15-second speed burst while chaining near-misses and boost gates.
- Crash reduces speed and combo but does not stop the run.
- Final score = distance + near-miss chain + clean tower pass bonus.

#### CONTROLS

- Steer left/right.
- Brake for precision threading.
- Boost (refills from near-miss streaks).

#### CAMERA

- Default: chase camera with stable horizon.
- Toggle: hood camera.

#### TECHNICAL

- Use InstancedMesh for traffic and repeated bridge props.
- Adaptive traffic count to sustain >=55 FPS.
- Clamp devicePixelRatio <= 2.
- UI compact/collapsible: timer, score, combo only.
- No extra overlays, no tutorials, no start modal.
```
