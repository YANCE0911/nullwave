# NULLWAVE

Hand-controlled, real-time visual effects in your browser. No plugins, no installs.

**Try it: https://yance0911.github.io/nullwave/**

## How it works

Your hands become the controller (via MediaPipe hand tracking):

- Show both hands — a rectangle spans between your palms
- Move your hands — the rectangle resizes and follows
- **Pinch (thumb + index)** — freezes the current square in place, and your hands get the next effect
- Build a collage of frozen effect panels across the screen

## Controls

| Input | Action |
|-------|--------|
| Pinch | Freeze the current square, cycle to next effect |
| `X` | Clear all frozen squares |
| `M` | Toggle mic input (audio-reactive effects) |
| `R` | Record the canvas to a WebM file |

## Effects

quadtree mosaic / mondrian / cyanotype print / rutt-etra scanlines / datamosh / neon contour / thermal / chromatic split / halftone / edge glow / ice

## Tech

- 100% browser-native: JavaScript + Canvas 2D
- [MediaPipe Hand Landmarker](https://developers.google.com/mediapipe) for hand tracking
- No TouchDesigner, no WebGL, no build step — one HTML file

## Privacy

All processing happens locally in your browser. Camera and mic data never leave your device.
