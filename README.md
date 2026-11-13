# HueMatch

A hue matching game. A target colour sits in the middle of a ring of eight swatches. Pick the swatch whose hue is closest to the target, measured as the OKLCH hue angle. Lightness and chroma are decoys: the closer a swatch's hue, the further its lightness and chroma are pushed, so the right answer often looks the most different.

## Play

Open `index.html` in a browser. There is no build step and nothing to install.

- **Modes:** Easy, Medium and Hard set how close the hues are and how strong the lightness/chroma decoys are. Custom has sliders for the hue spread, how close the right answer sits, and the decoy size. Each mode (and each custom setup) keeps its own best score in the browser.
- **Rounds:** a game is 10 rounds. Hues move closer together as your streak grows.
- **Scoring:** closest hue 10, second 7, third 4.5, any other up to 4. Subtle calls (hue gaps under 4°) earn a bonus of up to +5, +3 and +2 for the top three.
- **After a pick:** the swatches line up in a row by hue, with the target in its place. Tap any swatch (in the ring or the row) to see its OKLCH values and its difference from the target.
- **Keys:** 1–8 pick clockwise from the top; Enter moves on.
