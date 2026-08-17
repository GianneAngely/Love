# Love ❤️

A beating heart made of particles, drawn on a canvas in the middle of a black screen.

![The heart animation](screenshot.png)

## Why does this exist?

I wanted to see whether I could draw a heart with math instead of an image file. Turns out you can, and it looks much nicer when it pulses.

## What it does

- The heart shape comes from a parametric equation, so every point is calculated rather than loaded from a picture.
- Hundreds of particles scatter and settle back into the shape, which gives it that soft glowing edge.
- A CSS keyframe animation scales the whole canvas on a 1.5 second loop, so the heart looks like it is beating.
- The canvas fills the viewport, so it works as a full screen background.

## Built with

HTML, CSS, and vanilla JavaScript on a `<canvas>` element. No libraries and no build step, just open the file.

The animation loop uses `requestAnimationFrame` with a polyfill fallback, so it still runs on older browsers instead of freezing.

## Live demo

[gianneangely.github.io/Love](https://gianneangely.github.io/Love/)
