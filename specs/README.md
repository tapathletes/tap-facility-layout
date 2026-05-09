# Architectural specs

Authoritative dimensional + code-required input for the facility build.
**Different from `reference/`** — that folder is design-time mood-board
material; this folder is what suppliers and the city actually need to see.

When the 3D rebuild starts (Stage 2 of Track A), this folder is the source
of truth for measurements. If a dimension here disagrees with the
procedural Three.js geometry, the geometry is wrong, not the spec.

## Naming convention

`<area>-<YYYY-MM-DD>.{md,jpg,pdf}` — e.g. `bathroom-2026-05-09.jpg`,
`bathroom-2026-05-09.md`. The dated suffix lets us add revisions without
overwriting earlier captures.

## Files

- [`bathroom-2026-05-09.md`](bathroom-2026-05-09.md) — first bathroom
  spec capture (dimensions + city-required grate). Image to be added.
