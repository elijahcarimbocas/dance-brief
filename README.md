# dance-brief

> Latin social dance skill brief, prepared for a private assessment.

## Current brief

### `dance-brief.html`

Lead skill profile prepared for a private assessment with **Leela at Cavallo Dance AZ**. Covers training history (Brenda Smith / Salsa On1 / Rueda, Carlitos & Cece / Bachata, Lawrence Garcia / Salsa On1, Felix / Rueda), current level per style, four specific sticking points (adapting to a follow's level, salsa footwork gaps, clarity-vs-aggression, hand-toss technique), a 13-clip timestamped video appendix, and questions for the instructor.

**Live URL:** `https://elijahcarimbocas.github.io/dance-brief/dance-brief.html`

## File structure

```
dance-brief/
├── README.md
├── dance-brief.html
└── assets/
    └── forest-bg.png     (misty-forest background / OG image)
```

Single-file HTML with embedded CSS. Google Fonts (Source Serif 4, Inter, JetBrains Mono) load from CDN at view time. Misty-forest background, green headers. Print-friendly (hero hidden, sheet flattened).

## Video appendix

§04 holds **12 lesson clips** (`#v1`…`#v12`), Jan → Jun 2026 in date order, each with the dancer's own read (comfortable / mixed / got rolled) and a §3.x ref tag. Clips stream inline via `<video>` from `assets/videos/`.

Source: 12 `.MOV` files (1080p60, ~2.9 GB total) compressed with ffmpeg to **720p / H.264 CRF 30 / AAC 96k, faststart** — ~56 MB total (~98% smaller), audio kept. Re-encode command lives in the session notes; each output is well under GitHub's 100 MB file cap.

```
assets/videos/
├── jan28.mp4  feb04.mp4  feb11.mp4  feb18.mp4
├── mar23.mp4  mar25.mp4  apr01.mp4  apr22.mp4
└── apr29.mp4  may06.mp4  may20.mp4  jun03.mp4
```

## Deployment

GitHub Pages, deploy from `main` branch root.

1. **Settings → Pages**
2. Source: **Deploy from branch**
3. Branch: **main** · Folder: **/ (root)**

## Design

Nature / editorial aesthetic. Misty-forest hero and fixed background (the Mac wallpaper), forest-green headers and accents, warm paper sheet floating over the trees.

- Background image `assets/forest-bg.png`
- Paper `#EEF1E9` / `#FCFDFB`
- Ink `#1B241C`
- Forest green `#2F5D3A` (headers, primary accent)
- Moss `#6F8F4E`, bark `#8A6B45` (secondary)
- Level indicators: forest `#2F5D3A`, moss `#6F8F4E`, gold `#B0954F`

Typography: Source Serif 4 (display), Inter (body), JetBrains Mono (labels and codes).

## Version history

- **v1.0** · 07.02.2026 · *dance-brief* · Initial lead skill profile for Cavallo Dance assessment
