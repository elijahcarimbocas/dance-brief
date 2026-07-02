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

## Video appendix — TODO

The §04 appendix has **13 placeholder slots** (`#v1`…`#v13`). For each clip:

1. Drop the clip into `.vid-frame` — either a local `<video>` file or an unlisted **YouTube / Vimeo** `<iframe>` embed. (Prefer unlisted embeds; 13 raw video files bloat the repo and hit GitHub's 100MB file cap.)
2. Set the `.vid-time` timestamp and the `.vid-title` combo name.
3. Fill the "What broke down" note and tag it to §3.1 / 3.2 / 3.3 / 3.4.

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
