# stones

A small browser art prototype with flat Othello/Reversi-like stones and simple physics.

Built with a single `index.html` file using HTML, CSS, JavaScript, Matter.js, and the Web Audio API.

## Features

- Drag stones with the mouse.
- Release to throw them with momentum.
- Stones collide with each other and bounce off the canvas edges.
- Soft generated collision sounds, with no external audio files.
- Sliders for changing the number of black and white stones.
- Press `R` to reset the board with the current stone counts.

## Usage

Open `index.html` in a browser.

The prototype loads Matter.js from a CDN, so an internet connection is required unless you replace the CDN script with a local copy.

## Notes

This is an art prototype, not a game implementation. It does not include Reversi rules, turns, scoring, or board logic.
