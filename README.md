# Quiet Orb

A free, open-source breathing meditation for Meta Quest (2, 3, 3S, Pro) and any modern browser.

**Use it:** open <https://doktorigi.github.io/quiet-orb/> in the Quest browser and pick a length. No install, no account, no tracking.

Breathe in as the orb grows, hold, breathe out as it shrinks (4s / 2s / 6s). The drone opens up on the in-breath, so you can follow the pace with your eyes closed. A bell marks the start and the end.

## Develop

It is one file, `index.html`, with no build step. three.js loads from a CDN and all sound is synthesised.

    python -m http.server 8765

Open <http://localhost:8765/>. Add `#test` to the URL to run the breathing-pace self-check (the tab title becomes "tests ok").

WebXR needs HTTPS, so to try changes in a headset, push to GitHub Pages.

## License

MIT
