# Lotus & Willow · 一池莲柳

An interactive botanical web experience combining imagery, motion, and sound around a lotus pond.

**[Enter the experience](https://rainscyy.github.io/lotus/)**

This project explores the web as an atmospheric, interactive environment rather than a sequence of conventional pages. The repository includes the browser experience and video documentation.

## Run locally

With Python 3 installed, run from the repository root:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open `http://localhost:8000`. No package installation or build step is required. On macOS, `start.command` provides an alternative launcher when Python is available.

## Repository guide

- `index.html` — interface, styling, animation, and interaction logic.
- `img/` — visual assets.
- `audio/` — sound assets.
- Root `.mp4` files — video assets and project documentation; these account for much of the download size.

## Viewing notes

Sound playback may require a click or tap because of browser autoplay policies. Allow time for media to load. Cross-device performance, reduced-motion behavior, and keyboard accessibility are areas for further testing.

By Chunyu (Raine) Sha · [Portfolio](https://rainesha.my.canva.site/)
