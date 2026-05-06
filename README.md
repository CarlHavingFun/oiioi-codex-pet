# oiioi Codex Pet

Custom Codex pet based on the OIIA/OIIAI spinning cat meme.

The final behavior keeps the meme timing:

- Idle/static states use the standing gray tabby cat with visible short feet.
- Running/spinning states use the round body version where the feet are hidden while the cat spins.

## Files

- `pet/pet.json` - Codex pet manifest.
- `pet/spritesheet.webp` - Final 8x9 Codex pet atlas.
- `qa/contact-sheet.png` - Full atlas contact sheet.
- `qa/idle-preview.gif` - Static/idle preview with visible feet.
- `qa/spin-preview.gif` - Spinning preview with round body and hidden feet.
- `source/` - ChatGPT web image sources used to build the final pet.

## Install

Copy the contents of `pet/` into your Codex pets directory:

```bash
mkdir -p ~/.codex/pets/oiioi
cp pet/pet.json pet/spritesheet.webp ~/.codex/pets/oiioi/
```

## Preview

Idle:

![Idle preview](qa/idle-preview.gif)

Spin:

![Spin preview](qa/spin-preview.gif)

Full atlas:

![Contact sheet](qa/contact-sheet.png)
