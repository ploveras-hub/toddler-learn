# 🦁 Wild Animal Explorer

A colourful, single-file web app for toddlers. Tap a wild animal to hear its
name spoken aloud, earn a point, and hear a fun sound effect.

**▶ Live site:** https://ploveras-hub.github.io/toddler-learn/

## Features
- 20 wild animals in a bright, responsive, tap-friendly grid (2 columns on phones).
- Cute cartoon/vector illustrations, with an automatic emoji fallback if an image can't load.
- Taps use the browser's built-in speech synthesis to say the animal's name slowly and clearly.
- A point counter (`⭐ Points`) that ticks up on every tap.
- Playful pastel design with rounded cards, soft shadows, and a gentle press animation.

## Sound effects
Speech works out of the box. For real animal sound effects, drop `.mp3` files into
the [`sounds/`](sounds/) folder named to match each animal (e.g. `lion.mp3`,
`elephant.mp3`). Until then, the app plays a soft chime so every tap still gives
audio feedback — see [`sounds/README.txt`](sounds/README.txt) for the full list.

## Run locally
It's a single static file — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8971
# then open http://localhost:8971
```

No build step, no dependencies.
