# Color Mixer!

A fun, interactive color-mixing app for learning how colors combine. Works entirely in the browser — no install, no dependencies, just one HTML file.

**[Try it live](https://apsamajdwar.github.io/ColorMixer/)**

---

## Features

### Mix
Pick two (or three) colors from the palette and drop them into the mixing bowl to see what they make. Supports primary → secondary → tertiary color chains, tints (+ white), shades (+ black), and RGB blending for combinations without a named result. Drag and drop or tap to pick colors.

### Quiz
Guess which two colors mix to make the target. Earn stars for correct answers — a streak counter tracks consecutive correct guesses.

### Paint
A free-draw canvas with:
- **Color palette** — all base and mixed colors available as brush colors
- **Eyedropper** (💉) — click any spot on the canvas to sample and reuse that color
- **Current color swatch** — circle next to the brush preview always shows the active color
- **Brush size** slider with live preview
- **Eraser**
- **Undo / Redo** (also Ctrl+Z / Ctrl+Y)
- **Expand canvas** to fill the screen
- **Save** — downloads the painting as a PNG

### Free Mix
RGB sliders to dial in any color you want. A shade row shows tints and shades. Hit **Use in Paint** to load the color straight into the Paint tab.

### Collection (Sticker Book)
Tracks every color combination you've discovered across Mix and Quiz. Each unlocked color shows its emoji, name, and recipe.

---

## Color combinations

The app knows 30+ named mixes:

| Type | Examples |
|------|---------|
| Primary → Secondary | Red + Yellow = Orange, Red + Blue = Purple, Yellow + Blue = Green |
| Tints (+ White) | Red → Pink, Blue → Light Blue, Purple → Lavender |
| Shades (+ Black) | Red → Maroon, Blue → Navy, Green → Forest Green |
| Tertiary | Yellow + Green = Lime, Blue + Green = Teal, Blue + Purple = Indigo |
| Neutrals | Black + White = Gray |

Combinations outside the named list fall back to RGB blending.

---

## Usage

Open `index.html` in any modern browser. No build step, no server required.

```
git clone https://github.com/APSamajdwar/ColorMixer.git
cd ColorMixer
open index.html   # or just double-click it
```

---

## Tech

- Vanilla HTML, CSS, and JavaScript — single file, no frameworks
- Web Audio API for sound effects
- Canvas API for painting
- CSS custom properties for light/dark theme
