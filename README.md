# RGB Screen Simulator

**One-line summary:** An interactive website that shows how a screen makes every colour from only red, green and blue light, and why your eyes are fooled.

**Live website:** https://Mauveinn.github.io/RGB-Screen-Simulator/

## What it does

A phone, computer or TV screen has no yellow, white or pink light inside it. Every pixel is just three small lights: red, green and blue. This website lets you see that for yourself.

**Page 1: How a screen makes colour (about 2 minutes)**

1. **A screen is made of tiny dots.** Magnify a picture until it breaks into red, green and blue stripes.
2. **Each dot has only three lights.** Move three sliders to change one giant pixel and see the colour it makes.
3. **The lights never mix. Your eyes do the mixing.** Shrink the pixels until the stripes blend into one colour.

**Page 2: Go deeper (optional)**

Shows why your eyes are fooled. Your eye has only three kinds of colour sensors (cones), so your brain cannot tell a pure light from a mix of red, green and blue.

## How to run it

Open `index.html` in any web browser. There is nothing to install and nothing to build.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole website: the page, its styling and its JavaScript |
| `README.md` | This description |

## How the code works

All the JavaScript is at the bottom of `index.html`, in seven numbered sections. The most important part is the function `drawStripes`. It goes through every dot of the canvas, works out whether that dot is in the red, green or blue stripe of its pixel, and switches on only that one colour.

The model of the eye on page 2 uses simplified curves for the eye's sensors and the screen's lights, so its results are approximate.

## Built with

Plain HTML, CSS and JavaScript. No libraries and no build step. The font is loaded from Google Fonts.

## Team

- studzwaung-bot
- 2826588
- rainkiiii
- Mauveinn
