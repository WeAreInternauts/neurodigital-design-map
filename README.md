# Neurodigital Design Map

A liquid-glass concept map visualizing the philosophy behind Neurodigital Design — fusing behavior, cognition, and brand experience into one interface.

## Live preview

GitHub Pages: see the site URL in the repo's About section once Pages finishes building (usually within a minute of the first push).

## Embedding in Framer

1. In Framer, insert an **Embed** component
2. Choose **URL** mode
3. Paste the GitHub Pages URL above
4. Set the frame to `100% × 820px` (or `100vh`) — the layout is fully responsive

## Stack

- Single static `index.html` (HTML + inline CSS + a small JS auto-anchor script)
- Space Grotesk via Google Fonts
- Container queries (`cqh`/`cqw`) for proportional scaling
- Conic-gradient rims for the violet-mint glow

No build step, no dependencies.
