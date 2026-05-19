# RTN icon set — V2 Ledger

34 icons rendered with rough.js to match the hand-drawn aesthetic of the cover artwork.

## Settings used

| Param | Value |
|---|---|
| Roughness | 1.1 |
| Bowing | 1.6 |
| Stroke width | 2.9 |
| Stroke colour | `#2B4A7C` (accent) |
| Multi-stroke | disabled (single pass) |
| viewBox | 64 × 64 |

## Structure

```
teamspace/   — 7 icons used on teamspace home pages and sidebar
database/    — 7 icons used on database titles
wiki/        — 10 icons used on top-level wiki sections
record/      — 10 icons used on individual records inside databases
```

## File naming

Files are slug-cased matches of the brief. The numeric ID from the brief lives in the SVG comment, not the filename, so you can rename freely without losing traceability.

## Notion usage

Notion icon upload takes any PNG/JPG/SVG. Upload one SVG per icon. Recolouring inside Notion isn't supported — the accent blue is baked in. If you need a neutral variant, find-and-replace `#2B4A7C` with `#1B1A17`.

## Regeneration

Each SVG includes the rough.js settings and seed in its header comment, so any icon can be reproduced or re-rolled with a different seed. The generator script lives in `icon-gen/generate.js` in the working session — keep it alongside this set if you want to tune later.

## Known limitations

These are vector approximations of hand-drawn icons. Three places where a real Procreate pass would beat them:

1. **Stroke weight variation** along a single line (downstroke vs lift)
2. **Brush texture / grain** — rough.js gives wobble, not paper feel
3. **Personality on organic shapes** — the leaf (1.7), the pen nib (1.6), the quote marks (3.4) would benefit most from a human hand

If you want to upgrade those six over time, the rest of the set will still hold together.
