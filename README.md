# pokemon_programming

A minimal, dependency-free starting point for a 2D browser game.

## Run

Open `index.html` directly, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Build brief

- Keep the game web-based and easy to deploy as a static site.
- Target iPad Safari and desktop browsers.
- Support touch, pointer, and keyboard input.
- Work in both landscape and portrait orientations.
- Use Canvas 2D or Phaser; prefer Canvas 2D unless Phaser earns its weight.
- Unlock audio from the first user interaction before playing sound.
- Keep rendering and assets lightweight for reliable performance on mid-range iPads.

The current `index.html` only provides a responsive canvas, safe-area handling, a render loop, and placeholder touch controls. Replace it with the game implementation.
