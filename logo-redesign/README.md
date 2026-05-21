# Logo — V2 wordmark (decided)

The V2 logo system. Canonical decision record lives in Notion: [Logo design — V2 wordmark (decided)](https://www.notion.so/3678c4a62c3b8181b8a9d5187a2562c4). This README is a working summary; if it ever drifts from the Notion page, Notion wins.

## What's here

- `svg/rtn-wordmark-blue.svg` — Ledger Blue `#2B4A7C`. Brand-forward placement, hero sections, primary marketing surfaces.
- `svg/rtn-wordmark-ink.svg` — Warm Ink `#1B1A17`. Default for Canvas or light surfaces — the everyday version.
- `svg/rtn-wordmark-cream.svg` — Canvas Cream `#FAF7F2`. Reversed-out for use on Ledger Blue, Warm Ink, or photographic backgrounds.
- `test-bench.html` — single-file HTML test bench. Open in any browser to see Stacked Lockup D at proper scale with live Fraunces and Geist Mono from Google Fonts. Renders the master lockup, size cascade, monogram-only variants, favicons at 16/32/64/180px, a mock browser tab, and background context tests across Canvas, Ledger Blue, Warm Ink, and pure white. [View live via htmlpreview.github.io](https://htmlpreview.github.io/?https://github.com/dean-yates/rtn-brand-assets/blob/main/logo-redesign/test-bench.html).

## The mark in one paragraph

A single stacked lockup. "RTN" set big in Fraunces display cut (opsz 144, weight 500), with "RUN THE NUMBERS®" set small underneath in Geist Mono uppercase, generously tracked (+200 to +250). RTN cap height roughly 5x the descriptor cap height. Optical spacing between lines is about half the descriptor cap height. ® lives on the full descriptor string, never on the three-letter mark. No border, no container.

## Asset structure

The three SVGs in `svg/` contain only the RTN glyphs — the recognition mark. They're the right file to drop into image slots in Webflow, presentations, documents, anywhere the brand needs a single bitmap-style asset.

The full lockup (RTN + descriptor) is rendered as live HTML/CSS using Fraunces + Geist Mono webfonts on surfaces that have room for the descriptor — hero sections, document covers, large marketing placements. It's not flattened into a single SVG because the descriptor is part of the typographic system and needs to scale and reflow live.

The favicon is a separate asset (still to be produced — see Outstanding) using the same RTN letters in Canvas cream on a Ledger Blue rounded square.

## Outstanding (known work)

Tracked against the Notion decision page. Status as of last commit:

- [ ] Regenerate the three SVGs using Fraunces variable with the opsz axis pinned to 144 — current export is the static 500 cut at body weight (opsz 9), which renders chunky in live nav and footer use
- [ ] Re-upload corrected SVGs to Webflow assets and re-swap on Navbar / Footer / Logo Component
- [ ] Produce the two favicon exports (small-cut for 16-32px with hand-tightened letterforms, display-cut for 64-180px with proper Fraunces display forms) on Ledger Blue rounded square
- [ ] Optional — produce print-ready PDF/EPS variants for any future physical kit

## Working docs (Notion)

- [Logo design — V2 wordmark (decided)](https://www.notion.so/3678c4a62c3b8181b8a9d5187a2562c4) — the canonical decision record
- [Logo redesign — working doc](https://www.notion.so/3668c4a62c3b813cb44ce26fff206506) — exploration history, kept as record of how we got here
- [Brand & Visual System](https://www.notion.so/3658c4a62c3b81048a3dd04e16c0859a) — parent index
- [Mascot — working doc](https://www.notion.so/3668c4a62c3b816fa985e6dbd7b95888) — companion exploration for the optional brand mascot, kept separate from the logo system

## What was explicitly rejected

A separable symbol alongside the wordmark. A stamp or seal motif. A numerical or chart-derived element embedded in one of the letters. The V1 green and Nourd Bold weight. See the Notion page for the reasoning on each.
