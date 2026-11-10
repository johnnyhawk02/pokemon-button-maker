# Pokémon Button Maker

A single-page web app for making printable A4 PDFs of circular Pokémon button images.

**Live app:** https://johnnyhawk02.github.io/pokemon-button-maker/

## Features
- Pick Pokémon from [HybridShivam/Pokemon](https://github.com/HybridShivam/Pokemon) (1194 px Sugimori art, including Mega/Gmax/regional forms) or PokéAPI artwork. You can also upload your own images.
- Button sizes: 7 cm, 4.5 cm and 3.5 cm faces, plus a custom size.
- Drag, zoom, rotate and set a background colour for each image inside its circle.
- Works on iPad: drag to move, pinch to zoom, twist with two fingers to rotate.
- **Share design link** puts the whole design in a link (no server needed). Whoever opens it gets the same buttons, ready to tweak and print. Uploaded images can't go in a link.
- **Send PDF** opens the share sheet (AirDrop, Messages, Mail) with the finished PDF.
- Exports A4 PDFs at 300 dpi with grey cut lines, packed as tightly as possible (6 / 15 / 24 per sheet).

## Sizes
The 7 / 4.5 / 3.5 cm sizes are the visible **button face**. Each paper disc is cut larger (84 / 55 / 46 mm) so the image wraps round the edge and covers slightly-off placement in the press. The artwork also runs 1 mm past the cut line as bleed. You can change the cut diameter in Print settings to suit your machine. **Print at 100% / Actual size.**

## Running it
Open `index.html` in a browser. Everything is in that one file, with [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 (MIT) inlined.

Pokémon artwork belongs to Nintendo / Game Freak / The Pokémon Company. This is a fan tool for personal use.
