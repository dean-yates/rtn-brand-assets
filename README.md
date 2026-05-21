# RTN Brand Assets

Canonical home for the Run The NumbersÂ® brand system. The full spec lives in [`DESIGN.md`](./DESIGN.md) in this repo (raw URL: <https://raw.githubusercontent.com/dean-yates/rtn-brand-assets/main/DESIGN.md>). This repo also hosts the visual files â logos, icons, covers â referenced across rtn.digital, the RTN Notion workspace, and automated deliverables.

> **Canonical source.** `DESIGN.md` in this repo is the single source of truth for the RTN brand system. The `rtn-branding` skill in `dean-yates/rtn-cowork` is a fast-loading cache of this spec; if anything in the skill contradicts `DESIGN.md`, the canonical wins.

Moved from Notion to GitHub on 20 May 2026. The old Notion `DESIGN.md` sub-page in the RTN Brand Guide teamspace is now a redirect stub pointing here.

## V2 Ledger design system (13 May 2026)

Primary accent: Ledger Blue `#2B4A7C`. Dark surface `#142544`. Canvas `#FAF7F2` (warm cream, never pure white). Text `#1B1A17` (warm near-black, never pure black). Replaces V1 (green / gunmetal / Nourd).

## Logo

V2 wordmark â decision recorded in Notion: [Logo design â V2 wordmark (decided)](https://www.notion.so/3678c4a62c3b8181b8a9d5187a2562c4). The mark is a single stacked lockup of "RTN" in Fraunces display cut with "RUN THE NUMBERSÂ®" tracked underneath in Geist Mono. Two SVG variant sets are provided:

- **Monogram** (`rtn-wordmark-*.svg`) — RTN glyphs only, no descriptor text. The descriptor is rendered live as type when room allows.
- **Full lockup** (`rtn-lockup-*.svg`) — RTN glyphs + "RUN THE NUMBERS®" descriptor, stacked. For contexts where live type isn't available.

Canonical files live in [`logo-redesign/svg/`](./logo-redesign/svg/):

| File | Hex | Use on |
|---|---|---|
| `rtn-wordmark-ink.svg` | `#1B1A17` | Monogram — Warm Ink, default for Canvas / light surfaces |
| `rtn-wordmark-blue.svg` | `#2B4A7C` | Monogram — Ledger Blue, brand-forward, hero sections |
| `rtn-wordmark-cream.svg` | `#FAF7F2` | Monogram — Canvas Cream, reversed-out |
| `rtn-lockup-ink.svg` | `#1B1A17` | Full lockup — Warm Ink |
| `rtn-lockup-blue.svg` | `#2B4A7C` | Full lockup — Ledger Blue |
| `rtn-lockup-cream.svg` | `#FAF7F2` | Full lockup — Canvas Cream |](./DESIGN.md) in this repo (raw URL: <https://raw.githubusercontent.com/dean-yates/rtn-brand-assets/main/DESIGN.md>). This repo also hosts the visual files â logos, icons, covers â referenced across rtn.digital, the RTN Notion workspace, and automated deliverables.

> **Canonical source.** `DESIGN.md` in this repo is the single source of truth for the RTN brand system. The `rtn-branding` skill in `dean-yates/rtn-cowork` is a fast-loading cache of this spec; if anything in the skill contradicts `DESIGN.md`, the canonical wins.

Moved from Notion to GitHub on 20 May 2026. The old Notion `DESIGN.md` sub-page in the RTN Brand Guide teamspace is now a redirect stub pointing here.

## V2 Ledger design system (13 May 2026)

Primary accent: Ledger Blue `#2B4A7C`. Dark surface `#142544`. Canvas `#FAF7F2` (warm cream, never pure white). Text `#1B1A17` (warm near-black, never pure black). Replaces V1 (green / gunmetal / Nourd).

## Logo

V2 wordmark â decision recorded in Notion: [Logo design â V2 wordmark (decided)](https://www.notion.so/3678c4a62c3b8181b8a9d5187a2562c4). The mark is a single stacked lockup of "RTN" in Fraunces display cut with "RUN THE NUMBERSÂ®" tracked underneath in Geist Mono. The SVG assets contain only the RTN portion â the descriptor is rendered live as type when room allows.
| File | Hex | Use on |
|---|---|---|
| `rtn-wordmark-ink.svg` | `#1B1A17` | Warm Ink â default for Canvas / light surfaces |
| `rtn-wordmark-blue.svg` | `#2B4A7C` | Ledger Blue â brand-forward, hero sections, primary marketing |
| `rtn-wordmark-cream.svg` | `#FAF7F2` | Canvas Cream â reversed-out on Ledger Blue, Warm Ink, or photographs |

See [`logo-redesign/README.md`](./logo-redesign/README.md) for the working summary and outstanding refinement items, and [`logo-redesign/test-bench.html`](./logo-redesign/test-bench.html) ([live preview](https://htmlpreview.github.io/?https://github.com/dean-yates/rtn-brand-assets/blob/main/logo-redesign/test-bench.html)) for every variant rendered against the real V2 type system.

Favicon (RTN on a Ledger Blue rounded square, two cuts) lives alongside in `logo-redesign/svg/favicon-display.svg` and `logo-redesign/svg/favicon-small.svg`, with PNG fallbacks in `logo-redesign/png/`.

## Icons

34 hand-drawn-style SVG icons in Ledger Blue (`#2B4A7C`), rendered with rough.js to match the cover artwork. 64Ã64 viewBox, single-pass strokes, slug-cased filenames.

| Folder | Count | Use on |
|---|---|---|
| `icons/teamspace/` | 7 | Notion teamspace home pages and sidebar |
| `icons/database/` | 7 | Notion database titles |
| `icons/wiki/` | 10 | Top-level wiki sections |
| `icons/record/` | 10 | Individual records inside databases |

Notion accepts SVG icon uploads directly. The accent blue is baked in â for a neutral variant, find-and-replace `#2B4A7C` with `#1B1A17` (text). See `icons/README.md` for regeneration settings and known limitations.

## Rules

- Never stretch, distort, recolour outside the three variants, add effects, or use below 80px wide.
- Full spec in [`DESIGN.md`](./DESIGN.md).

## License

Â© 2026 RTN Digital Ltd. "Run The Numbers" and the RTN logo are registered trademarks (Company No. 16200602). Public hosting for technical purposes only; use requires permission.
