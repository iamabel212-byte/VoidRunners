# Void Runners Sprite Style

All new Void Runners sprites must use an early-1990s SNES-era pixel-art treatment, even when supplied reference art is smoother or more polished.

- Build silhouettes on a deliberately low-resolution grid and scale with nearest-neighbor sampling.
- Use chunky, clearly visible square pixels and hard stair-stepped edges.
- Use small, limited palettes with flat color clusters and no smooth gradients.
- Describe materials with two or three shade levels plus selective pixel dithering.
- Favor strong mobile-readable silhouettes over fine surface detail.
- Avoid antialiasing, subpixel smoothing, bloom, glossy rendering, soft shadows, painterly texture, and modern high-resolution polish.
- Treat reference art as design inspiration; translate it into this SNES visual language before implementation.
- Keep animation assets modular and economical when practical (for example, reusable body segments).

The approved Leviathan Field worm atlas is the current style reference: `assests/images/leviathan-worm-snes-atlas-v1.png`.
