# Keys & Strings

An interactive music course, from the first note to advanced harmony, with full methods for the grand piano, the electronic keyboard and the guitar.

**Open the course:** https://rakeshnaik1109-cloud.github.io/RNKey-String/

- 32 chapters in seven parts, plus appendices (chord dictionary, scales and keys, glossary, practice room)
- Playable scores: every example can be heard, slowed down, looped and played on an on-screen keyboard or guitar neck
- Labs: harmonics mixer, metronome and rhythm tapper, note-reading cards, circle of fifths, scale and chord explorers, progression player, ear trainer, synthesiser, arranger keyboard, guitar tuner and fretboard explorer
- All sound is synthesised in the browser with the Web Audio API; nothing is recorded or uploaded

## Running it

It is a single static page. Open `index.html` in a browser, or serve the folder with any static web server:

```sh
python3 -m http.server
```

Notation is drawn with [VexFlow](https://www.vexflow.com/) 4.2.2, loaded from jsDelivr; fonts come from Google Fonts. Reading progress, the last chapter opened and the volume setting are stored in the browser's `localStorage`.

## Publishing

To host it with GitHub Pages, enable Pages for this repository (Settings → Pages → Deploy from a branch → `main`, root folder). The `.nojekyll` file makes Pages serve the files as they are.
