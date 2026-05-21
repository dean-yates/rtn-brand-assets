# RTN Brand Assets

Canonical home for the Run The Numbers® brand system. The full spec lives in [`DESIGN.md`](./DESIGN.md) in this repo (raw URL: <https://raw.githubusercontent.com/dean-yates/rtn-brand-assets/main/DESIGN.md>). This repo also hosts the visual files — logos, icons, covers — referenced across rtn.digital, the RTN Notion workspace, and automated deliverables.

> **Canonical source.** `DESIGN.md` in this repo is the single source of truth for the RTN brand system. The `rtn-branding` skill in `dean-yates/rtn-cowork` is a fast-loading cache of this spec; if anything in the skill contradicts `DESIGN.md`, the canonical wins.

Moved from Notion to GitHub on 20 May 2026. The old Notion `DESIGN.md` sub-page in the RTN Brand Guide teamspace is now a redirect stub pointing here.

## V2 Ledger design system (13 May 2026)

Primary accent: Ledger Blue `#2B4A7C`. Dark surface `#142544`. Canvas `#FAF7F2` (warm cream, never pure white). Text `#1B1A17` (warm near-black, never pure black). Replaces V1 (green / gunmetal / Nourd).

## Logo files

Three transparent-background SVGs of the RTN wordmark (21 May 2026 redesign). Source: "RTN" hand-set in Fraunces, finalised after the logo-redesign exploration and signed off as canonical. SVG keeps the mark crisp at every size — no fixed PNG exports.

| Variant | Hex | Use on |
|---|---|---|
| Blue | `#2B4A7C` | Warm cream / white surfaces. Default. |
| Cream | `#FAF7F2` | Dark surfaces (accent-deep navy, near-black ink) |
| Ink | `#1B1A17` | Monochrome contexts (single-colour print, plain correspondence) |

Aspect ratio: 5047×1581 (3.19:1). Export to PNG at the size needed if a tool requires raster.

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
- Full spec in [`DESIGN.md`](./DESIGN.md).

## License

© 2026 RTN Digital Ltd. "Run The Numbers" and the RTN logo are registered trademarks (Company No. 16200602). Public hosting for technical purposes only; use requires permission.
