# Water Cleaner 💧

A drag-and-drop browser game themed around [charity: water](https://www.charitywater.org). Sort the pollutants out of the water before time runs out.

**▶ Play it here:** https://un-alln.github.io/Water-Cleaner-Game-/

## How to play

1. Pick a difficulty and press **Play**.
2. After a 3-second countdown, pollutants appear in the water.
3. Drag each one into the matching bucket:
   - 🟤 **Debris**
   - 🟢 **Bacteria**
   - 🟣 **Chemical** (shows up from level 5 on)
4. Sort them all before the timer hits zero to clear the level and unlock the next one.

### Scoring

- **+100** for each correct sort
- A wrong bucket costs points, depending on the difficulty

| Difficulty | Time per level | Wrong-bucket penalty |
|---|---|---|
| Easy | 15s | none |
| Normal | 10s | −10 |
| Hard | 7s | −20 |

There are **12 levels**. Each level adds more pollutants, starting at 6 and going up to 12.

## Features

- Title, level select, gameplay and end screens
- Works with a mouse or touch, using pointer events
- Countdown, live timer, progress counter and milestone banners as you sort
- Sound effects and confetti when you clear a level
- A charity: water footer with a **Donate** link on every screen
- A responsive layout that works on phones and desktops

## Built with

Plain **HTML, CSS and JavaScript**: no frameworks, no build step.

```
index.html      screens and layout
styles.css      styling (Montserrat + Nunito Sans)
script.js       game logic: levels, drag and drop, timer, scoring
assets/         logo and sound effects
```

## Run it locally

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/UN-ALLN/Water-Cleaner-Game-.git
cd Water-Cleaner-Game-
```

> Note: level progress resets when you refresh the page.
