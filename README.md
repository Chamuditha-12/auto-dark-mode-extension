# Auto Dark Mode Extension

A simple, lightweight browser extension for Microsoft Edge that automatically forces dark mode on every website you visit.

## Features

- Automatically applies dark mode to all websites
- No button clicks needed — works instantly on every page
- Images and videos stay looking normal (double-inverted back to natural colors)
- Only 2 files — no JavaScript, no bloat
- Works on any HTTP/HTTPS website

## How It Works

The extension injects a single CSS file into every webpage that applies:
- `filter: invert(1)` — inverts all colors (white becomes black)
- `hue-rotate(180deg)` — corrects colors back to natural tones
- Images, videos, and canvases get double-inverted so they look normal

## Installation

1. Clone or download this repository
2. Open Microsoft Edge and go to `edge://extensions/`
3. Turn on **Developer mode** (top left toggle)
4. Click **Load unpacked**
5. Select the downloaded folder
6. Done — every website is now automatically dark

## Files

| File | Purpose |
|------|---------|
| `manifest.json` | Extension configuration |
| `dark.css` | CSS that makes pages dark |

## Browser Support

- Microsoft Edge (Manifest V3)
- Google Chrome (Manifest V3)

## License

MIT License — free to use and modify
