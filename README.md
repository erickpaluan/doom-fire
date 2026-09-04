# Doom Fire Algorithm

A small JavaScript implementation of the classic **Doom fire effect**, recreated as a visual programming exercise.

The project generates the fire frame by frame using a grid of intensity values, propagating and cooling pixels to create the animated flame effect.

## What it explores

- array and matrix manipulation
- procedural animation
- state propagation
- palette-based rendering
- direct DOM rendering
- translating a visual effect into simple algorithmic rules

## Tech stack

JavaScript · HTML · CSS

## How it works

At a high level, the effect uses a two-dimensional fire buffer.

Each frame:

1. the bottom row acts as the heat source
2. heat values propagate upward
3. values are randomly reduced to simulate cooling
4. horizontal displacement creates the irregular flame movement
5. each intensity value maps to a color in the fire palette

The result is the characteristic animated fire effect associated with Doom.

## Running locally

No build step is required.

Clone the repository and open `index.html` in a browser, or serve the directory using any local HTTP server.

## Status

**Completed experiment.**

The project has a deliberately small scope and is kept as a compact example of algorithmic and visual programming.

## License

MIT
