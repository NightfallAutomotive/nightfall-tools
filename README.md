# Nightfall Tools

The home page for Nightfall Automotive's free tools, at
**https://www.nightfalltools.co.uk**.

| Tool | Address | Repository |
|---|---|---|
| BIN Analyser (beta) | https://bin.nightfalltools.co.uk | [nightfall-vehicle-bin-analyser](https://github.com/NightfallAutomotive/nightfall-vehicle-bin-analyser) |
| QR Code Generator | https://qr.nightfalltools.co.uk | [qrcodegen](https://github.com/NightfallAutomotive/qrcodegen) |
| Nightfall Compress | https://compress.nightfalltools.co.uk | [compression_for_website](https://github.com/NightfallAutomotive/compression_for_website) |

It is a static page (HTML, CSS and a little JavaScript) with no build step,
deployed as a Cloudflare Workers static site from `wrangler.jsonc`. Files
listed in `.assetsignore` are not uploaded.

To add a tool, add a card to the `tools` list in `index.html`.
