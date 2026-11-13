# HueMatch

A colour matching game. A target colour sits in the middle of a ring of ten swatches. Each swatch trades hue against lightness and chroma: the closer its hue is to the target, the further its lightness and chroma are. Pick the swatch closest to the target, measured as ΔE in OKLab (the Cartesian form of OKLCH).

## Play

Open `index.html` in a browser. There is no build step and nothing to install.

- **Modes:** Easy, Medium and Hard set how close the swatches are. Custom has sliders for the spread, how close the right answer sits, and how far hue may drift. Each mode (and each custom setup) keeps its own best score in the browser.
- **Rounds:** a game is 10 rounds. Swatches move closer together as your streak grows.
- **Scoring:** closest 10, second 7, third 4.5, any other up to 4. Subtle calls (small ΔE gaps) earn a bonus of up to +5, +3 and +2 for the top three.
- **After a pick:** tap any swatch to see its OKLCH values and its difference from the target.
- **Keys:** 1–9 and 0 pick clockwise from the top; Enter moves on.
