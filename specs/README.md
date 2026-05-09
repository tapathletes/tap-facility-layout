# Architectural specs

Authoritative dimensional + code-required input for the facility build.
**Different from `reference/`** — that folder is design-time mood-board
material; this folder is what suppliers and the city actually need to see.

When the 3D rebuild starts (Stage 2 of Track A), this folder is the source
of truth for measurements. If a dimension here disagrees with the
procedural Three.js geometry, the geometry is wrong, not the spec.

## Naming convention

- **Notes:** `<area>-<YYYY-MM-DD>.md` — one markdown file per area, per
  capture date. Revisions get a new dated file rather than overwriting.
- **Images:** `<area>-<descriptor>-<YYYY-MM-DD>.{jpg,png,pdf}` — multiple
  images can belong to the same notes file when the architect's plan is
  cropped/framed differently across them. Examples:
  `bathroom-mopsink-2026-05-09.jpg`, `bathroom-interior-2026-05-09.jpg`.

## Files

- [`bathroom-2026-05-09.md`](bathroom-2026-05-09.md) — unisex bathroom
  (architect-sourced). Two image crops referenced; image files pending.
