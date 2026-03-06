# Ancient Athens: Acropolis

Model: GPT-5.4-Pro Extended

## Prompt

```text
Create Ancient Athens' Acropolis with a recognizable Parthenon and surrounding rock plateau, in warm Mediterranean light.
If you use Three.js, add an import map (before the module script) mapping "three" and "three/addons/" to the same pinned version, and import only via those names. Never reuse identifiers in the same scope - use descriptive variable names.

#### SCENE (instant recognition)

- Parthenon with correct "temple" proportions: colonnade, pediment, stepped stylobate.
- Pale marble material with subtle warm tint; columns cast crisp shadows.
- Rocky Acropolis hill with carved steps/paths.
- Olive trees scattered (instanced) and distant city massing below (simple).

#### ATMOSPHERE

- Warm sun + blue sky; slight haze in distance.
- Optional: a few small human figures in robes for scale (instanced).

#### CONTROLS

- Time slider: morning -> high noon -> golden hour (color temperature and shadow softness change).
- Haze slider.
- Crowd toggle + density slider.
- Camera: Classic postcard (default), Close architectural inspection, Flyover path.

#### TECHNICAL

- Instanced trees/people.
- Procedural textures for marble variation (subtle).
- Target >=55 FPS; clamp DPR <= 2; minimal UI.

#### FINAL OUTPUT

Generate the full output now.

---
```
