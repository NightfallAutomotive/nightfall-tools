# Nightfall Tools

The home page for Nightfall Automotive's tools, at
**https://www.nightfalltools.co.uk**.

| Tool | Address | Repository |
|---|---|---|
| BIN Analyser (beta) | https://bin.nightfalltools.co.uk | [nightfall-vehicle-bin-analyser](https://github.com/NightfallAutomotive/nightfall-vehicle-bin-analyser) |
| QR Code Generator | https://qr.nightfalltools.co.uk | [qrcodegen](https://github.com/NightfallAutomotive/qrcodegen) |
| Nightfall Compress | https://compress.nightfalltools.co.uk | [compression_for_website](https://github.com/NightfallAutomotive/compression_for_website) |
| Statement Bridge | https://sumupconvert.nightfalltools.co.uk | [sumup-freeagent-converter](https://github.com/NightfallAutomotive/sumup-freeagent-converter) |
| Inkwell (Linux notes app, AppImage download) | [v1.0.0 release](https://github.com/NightfallAutomotive/inkwell/releases/tag/v1.0.0) | [inkwell](https://github.com/NightfallAutomotive/inkwell) |

It is a static page (HTML, CSS and a little JavaScript) with no build step,
deployed as a Cloudflare Workers static site from `wrangler.jsonc`. Files
listed in `.assetsignore` are not uploaded.

To add a tool, copy one of the cards in the `tools` list in `index.html` and give it two
screenshots in `assets/shots/`: `<name>-desktop.webp` (1280×800) and `<name>-mobile.webp`
(390×780 at 1.5×).
