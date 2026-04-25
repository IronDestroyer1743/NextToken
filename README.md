# NextToken

A free, customizable digital token economy board for ABA sessions and similar use. Set 1 to 40 token slots, choose from 16 built-in icons or upload your own, and pick from five visual and five audio reward effects (each toggleable). Clean interface, all settings saved locally, no dependencies. Just one HTML file.

## Live Demo

[your-username.github.io/nexttoken](https://your-username.github.io/nexttoken)

## Features

- **Flexible board size** — 1 to 40 token slots, auto-arranged into a balanced grid that fits the viewport
- **16 built-in icons** — star, heart, smile, check, sun, moon, cloud, bolt, flower, leaf, rocket, crown, diamond, paw, fish, dino
- **Custom icon upload** — PNG, JPEG, WebP, or SVG, auto-resized and stored locally in your browser
- **5 visual effects** — confetti, star burst, fireworks, bubbles, rainbow rings (plus off)
- **5 audio effects** — chime, fanfare, sparkle, coin, ta-da (plus off), synthesized via Web Audio API
- **Independent toggles** for visual and audio rewards
- **Editable session label** above the board
- **Persistent state** — all settings, custom icons, and mid-session progress save to localStorage
- **Single self-contained HTML file** with zero dependencies

## Usage

Tap any empty slot to fill it. Tap a filled slot to unfill. Fill them all to trigger the reward effect. The settings cog (top right) opens a slide-out panel for all customization. The reset button clears the board.

## Hosting

Drop `index.html` on any static host: GitHub Pages, Netlify, Vercel, Cloudflare Pages, or even open it locally from your file system. No build step required.

## Privacy

Everything runs client-side. No analytics, no network requests, no data leaves your device. Custom icons and settings live in your browser's localStorage.

## License

MIT License

Copyright (c) 2026 Carter Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE DEALINGS IN THE SOFTWARE.
