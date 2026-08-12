# dance-brief

> Latin social dance skill brief, prepared for a private assessment.

## Current brief

### `bachata-dance-private-lesson-brief.html`

Third brief, prepared for **Cece and Carlitos** (Bachata) for two private lessons: **Sat Aug 15 and Sat Aug 22, 2026, 12:00 PM**. Direction brief, not a repair list: Urban Bachata Fusion in three lanes (salsachata, footwork and shines, sensual control), a progress update since Brief I (two privates + 6-8 Cavallo group classes; follow-reading fixed), and a 4-clip bachata appendix from late July. Prep for Hawaii Salsa Bachata Paradise, Sep 3-6.

**Theme:** this brief does NOT use the forest system. It wears the Hawaii "Road to Waikiki" site theme (night navy, coral / gold / teal, Bricolage Grotesque + Space Grotesk + Caveat, `assets/tropical.svg` background, sand-colored centerpiece section, live countdown that rolls Lesson 1 &rarr; Lesson 2 &rarr; the Sep 3 flight). OG image is `assets/hawaii-og.png` (copied from the hawaii-bachata-2026 repo along with `tropical.svg`).

**Live URL:** `https://elijahcarimbocas.github.io/dance-brief/bachata-dance-private-lesson-brief.html`

**Video set**, 8 clips (from the Hawaii folder; IMG_5911 was excluded - it is the same footage as Brief II's `2026-07-28.mp4`):

Sources live in the Hawaii folder's `site/clips/`, which was mass-renamed 8-12-26 to "[Month] [day] [year].MOV" from QuickTime creation dates (was IMG_xxxx):

```
assets/videos/
├── 2026-07-27a.mp4   "July 27 2026.MOV" (was IMG_5909) · follows' styling drill
├── 2026-07-27b.mp4   "July 27 2026 - 2.MOV" (was IMG_5910) · my drill (forward fold at 1:40)
├── 2026-07-28a.mp4   "July 28 2026.MOV" (was IMG_5912) · class demo (drop at 0:40)
├── 2026-07-28b.mp4   "July 28 2026 - 2.MOV" (was IMG_5914) · showcase run
├── 2025-08-23.mp4    "August 23 2025.MOV" (was IMG_3797) · archive studio demo (drop at 0:28; "August 23 2025 - 2.MOV" is his phone trim of it)
├── 2025-08-30.mp4    "August 30 2025.MOV" (was IMG_3806) · archive performance run (landscape)
├── 2025-09-12.mp4    "September 12 2025.MOV" (was IMG_3841) · archive rooftop social run (landscape)
└── 2025-09-30.mp4    "September 30 2025.MOV" (was IMG_3894) · archive Moonlight-room demo
```

## Previous briefs

### `dance-brief-2.html`

Second brief, prepared for **Leela Fazzuoli and Daniele at Cavallo Dance AZ** for the Aug 10 private lesson. No history or level chart this time. Seven Salsa On1 clips from Cavallo classes (Mar 23 → Jul 30, 2026), each timestamped to the second where the lead breaks: the duck under the follow's left arm, the pretzel (which collapses into Setenta / Setenta Tres), crossbody into the Titanic, lasso into the Titanic with the left kick, the shoulder-check transfer, and the crossbody hold that reads as a travel. Two more spots are unnamed and left for the instructor to identify. Red timestamp buttons seek the inline video.

**Live URL:** `https://elijahcarimbocas.github.io/dance-brief/dance-brief-2.html`

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

Source: 12 `.MOV` files (1080p60, ~2.9 GB total) compressed with ffmpeg to **720p / H.264 CRF 30 / AAC 96k, faststart** - ~56 MB total (~98% smaller), audio kept. Re-encode command lives in the session notes; each output is well under GitHub's 100 MB file cap.

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
- **v2.0** · 08.10.2026 · *dance-brief-2* · Seven Cavallo class clips, six named breakdowns plus two unnamed, for the Aug 10 lesson with Leela and Daniele
- **v3.0** · 08.12.2026 · *bachata-dance-private-lesson-brief* · Urban Bachata Fusion direction brief for Cece and Carlitos, two privates Aug 15 + Aug 22, four bachata clips

## Brief II video set

Filenames are ISO shoot dates, pulled from the source `.MOV` creation timestamps (the mp4 file dates are compression dates, not shoot dates). `2026-03-23` and `2026-07-30` were compressed from raw here; the other five were already 720p.

```
assets/videos/
├── 2026-03-23.mp4  2026-07-14.mp4  2026-07-16.mp4
├── 2026-07-21.mp4  2026-07-23.mp4  2026-07-28.mp4
└── 2026-07-30.mp4
```
