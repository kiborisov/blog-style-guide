# Blog Style Guide

A clean editorial blog style, distilled from a custom Ghost theme (serif throughout). Warm paper background, one centered serif column, blue links, typewriter-style UI chrome. Editorial and book-like, almost no boxes or shadows.

## Color palette (light mode)

| Token | Hex | Use |
| --- | --- | --- |
| Page background | `#e8e7e3` | Warm greige paper |
| Content sheet | `#f3f2ee` | Cards, embeds |
| Ink | `#1c1b22` | Headings, bold, near-black with a blue tint |
| Body text | `#3a3844` | Soft dark gray — body is *not* pure black |
| Muted | `#65626f` | Meta, captions, secondary text |
| Hairline rules | `rgba(28,27,34,.14)` | Borders, dividers |
| Accent | `#2a45c8` | Blue — links, list markers, blockquote border, footnote refs |

Dark mode: ground `#08090e`, sheet `#0e0f16`, ink `#ebe6da`, body `#cfc9bc`, muted `#9a97a6`, accent `#8aa4ff`.

## Fonts

- **Body + headlines: Literata** (serif). Body ~18–19px, line-height **1.68**, color `#3a3844`.
- **Headline:** Literata ~700, sentence case (not uppercase), ~48–56px, line-height ~1.05–1.1.
- **Section heads (H2):** Literata ~700, ~28–30px, line-height ~1.2, large top margin (~2.1em), small bottom margin (.6em).
- **UI chrome: VT323** (typewriter) — nav links (19px, letterspaced), meta labels, table-of-contents rail, footer, the "— END —" marker, footnote refs.
- **Mono: Fira Code** — inline code, code blocks.
- **Supporting (base theme):** Archivo (headings), Fira Sans (body), Caveat (handwritten).
- **Bold:** weight 700 *and* color shifts from soft body gray to full ink.

## Layout

- Content column: **680px** max-width, centered, 16px side padding on the body.
- Header area: 900px max-width. Whole page wrap: 1180px.
- Header: no border, no background change. Left: wordmark (Archivo, uppercase, 14px). Nav: VT323 links in muted gray; current page gets an inverted pill (ink background, paper text). Right: boxed theme button.
- Left rail: table of contents in VT323 muted gray, current item in ink/bold.
- Spacing rhythm: 1.15em between body blocks, 1.8–2em around figures/code, big top margins on headings.

## Components

- **Links:** ink-colored text, 1.5px blue underline, 3px offset. Hover only thickens the underline to 3px — no color change.
- **Lists:** default discs, markers in accent blue. Items spaced .3em apart.
- **Blockquote:** ~3px solid blue left border, no background, serif body-size text, ~20px left padding. No big decorative quote marks.
- **Images:** full column width, 3px border-radius, soft shadow, click-to-zoom. Captions in 14.5px Fira Sans muted, with a small blue "▲" marker.
- **Footer:** "— END —" in VT323 muted, then an author block (52px circular avatar, 15.5px muted text) with hairline rules above and below. Site footer: hairline top border, VT323 links.
- **Code:** inline code is mono .84em on a faint rule-colored background, 3px radius. Code blocks: near-black `#14151c` background, light text, 14.5px/23.2px, 6px radius, VT323 header bar with the language label.
- **Text selection:** blue-tinted (accent at 24% opacity).
- **HR:** no line — a row of `▚▞▚▞▚` glyphs in VT323 muted.

## Why it feels clean

1. Two grays for text (soft body, ink headings) instead of pure black on white.
2. One serif for reading, one typewriter font for UI — nothing else competes.
3. A single accent color (blue) used sparingly: links, markers, one border.
4. Generous, consistent spacing — 680px column, 1.68 line-height, big heading top margins.
5. Almost no boxes, shadows, or backgrounds — the page is basically paper + type + hairlines.
