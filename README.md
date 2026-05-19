# RTN Brand Assets

Public hosting for Run The Numbers® brand assets, referenced across rtn.digital, the RTN Notion workspace, and automated deliverables.

The canonical brand spec lives in the private RTN Notion workspace. This repo only hosts the visual files.

## V2 Ledger design system (13 May 2026)

Primary accent: Ledger Blue `#2B4A7C`. Dark surface `#142544`. Canvas `#FAF7F2` (warm cream, never pure white). Text `#1B1A17` (warm near-black, never pure black). Replaces V1 (green / gunmetal / Nourd).

## Logo files

Nine transparent-background PNGs across three variants and three sizes. Source: V1 green logo from rtn.digital, recoloured by alpha-preserved RGB replacement.

| Variant | Hex | Use on |
|---|---|---|
| Blue | `#2B4A7C` | Warm cream / white surfaces. Default. |
| White | `#FFFFFF` | Accent-deep dark surfaces |
| Dark | `#1B1A17` | Monochrome contexts |

Sizes per variant: full (2560x1345), 1200px wide (1200x630), 600px wide (600x315).

## Icons

34 hand-drawn-style SVG icons in Ledger Blue (`#2B4A7C`), rendered with rough.js to match the cover artwork. 64×64 viewBox, single-pass strokes, slug-cased filenames.

| Folder | Count | Use on |
|---|---|---|
| `icons/teamspace/` | 7 | Notion teamspace home pages and sidebar |
| `icons/database/` | 7 | Notion database titles |
| `icons/wiki/` | 10 | Top-level wiki sections |
| `icons/record/` | 10 | Individual records inside databases |

Notion accepts SVG icon uploads directly. The accent blue is baked in — for a neutral variant, find-and-replace `#2B4A7C` with `#1B1A17` (text). See `icons/README.md` for regeneration settings and known limitations.

## Rules

- Never stretch, distort, recolour outside the three variants, add effects, or use below 80px wide.
- Full spec in the RTN Notion workspace.

## License

© 2026 RTN Digital Ltd. "Run The Numbers" and the RTN logo are registered trademarks (Company No. 16200602). Public hosting for technical purposes only; use requires permission.
