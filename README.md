# Niulai Codex Pet

A custom Codex v2 animated pet inspired by a playful orange Chinese animated calf character. Niulai has a soft early-CG toy look, sleepy expressive eyes, a pale muzzle, tiny ears, and a gentle little-work-buddy personality.

## Preview

<img src="./contact-sheet-extended.png?raw=true" alt="Niulai contact sheet" width="640">

## Actions

| Action | Idle | Waving | Running | Waiting | Review |
| --- | --- | --- | --- | --- | --- |
| Preview | <img src="./previews/idle.gif?raw=true" alt="Idle" width="96"> | <img src="./previews/waving.gif?raw=true" alt="Waving" width="96"> | <img src="./previews/running.gif?raw=true" alt="Running" width="96"> | <img src="./previews/waiting.gif?raw=true" alt="Waiting" width="96"> | <img src="./previews/review.gif?raw=true" alt="Review" width="96"> |

## Files

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - v2 animated spritesheet, `1536x2288`.
- `contact-sheet-extended.png` - full QA contact sheet.
- `look-directions.png` - 16-direction gaze QA sheet.
- `previews/` - selected action GIF previews.

## Install

Copy this folder into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets/niulai
cp pet.json spritesheet.webp ~/.codex/pets/niulai/
```

The manifest uses `spriteVersionNumber: 2`.
