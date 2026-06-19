# 4x4rt Drops

Interactive art for the #Art4LifeTez event.

## Project structure

- `index.html` — main page (open in a browser to view the artwork).
- `LICENSE` — project code license (MIT).
- `ARTWORK_LICENSE` — license for artwork and visual outputs (CC BY-NC 4.0).

## Usage

Open `index.html` in your browser (double-click or serve from a static host).

## GitHub Pages

This repository includes a GitHub Pages workflow that publishes the site from the repository root on each push to `main`.

Once the workflow runs, the preview will be available at:

https://PixelSushiRobot.github.io/4x4rt-Drops/

## Contributing

Contributions are welcome. Please open issues or pull requests on the
repository. Respect the artwork license when reusing visual assets.

## Interaction

- The artwork is a 4x4-style puzzle made from 16 interlocking blocks. Each block is a pointer target — press and hold (mouse, stylus, or touch) on a block to increase its red/lightness value.
- Releasing the hold drains the accumulated value outward to the other blocks, reducing their lightness. The goal is to balance all blocks to an equal color value.
- When blocks are balanced (within a small threshold) a celebration animation runs and a new randomized board is generated.
- Keyboard shortcuts (when the artwork has focus):
  - `i` — toggle the project metadata overlay
  - `r` — force a new randomized board
  - `p` — download a 2000×2000 PNG export
  - `s` — download a 1000×1000 SVG export
  - `Enter` / `Space` — simulate a block press (random cell)

The SVG is focusable and uses pointer events so mouse, touch, and keyboard all work.

## License

Code is licensed under the MIT License. See [LICENSE](LICENSE).

Artwork and visual outputs are licensed under the Creative Commons
Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See
[ARTWORK_LICENSE](ARTWORK_LICENSE).
