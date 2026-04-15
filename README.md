# roller

This is a software demo of a piece of hardware I intend to make. The device would certainly be the smallest e-reader ever made, it'd just be the size of a word. The biggest problem with the user experience is velocity. Small letters fly by too fast, and long letters fly by too slowly. This could be solved in hardware with a haptic scroll wheel, in software it is solved with a velocity slider.

## Features

- **Zero Setup**: Single-file HTML/JS app that runs anywhere.
- **Format Support**: Drag and drop `.epub` or `.txt` files.
- **Velocity-Weighted Scrolling**: Scroll effort is proportional to word length (CPM-based).
- **Adaptive RSVP**: Auto-play speed scales with word complexity.
- **Focus Anchor**: Stationary red pivot character for rapid reading.
- **Chunking**: Group words together to reduce the number of "scrolls" needed to read a sentence.

## Controls

- **Mouse Wheel**: Roll through the text.
- **Space**: Toggle auto-play.
- **Velocity Slider**: Tune your reading speed and scroll sensitivity.
- **Arrows**: Navigate word by word.
- **R**: Reset to the beginning.

## Getting Started

1. Open `roller.html` in your browser.
2. Drag in a book or use the default `prideandprejudice.txt`.
3. Scroll to start "rolling."
