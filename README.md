# cofounder.new — Christine Variation 2 (Boardroom Briefing) [DEMO]

Static prototype of the cofounder.new founder app, built on Variation B (Boardroom Briefing) of the experience modulator set.

Single-file HTML/CSS/JS. No build step, no dependencies. Opens directly in a browser.

## Live preview
Deployed via GitHub Pages from `main`. The site is `index.html`.

## What this is
A clickable demo of:

- Sidebar with live AI status sentence + heartbeat
- Command Center as Today's Briefing (ranked cards, "Show the work" expand, inline Approve / Redirect / Defer)
- Business Detail (one-page memo + 7 tabs + curated right rail + controls)
- Chat (full canvas + global drawer)
- Activity Log (filterable monospace table + CSV export confirm)
- Settings (Account / Billing / Notifications / API / Integrations / Data Export / Danger Zone)
- Decision flow with quoted-action confirmation modal
- Toasts, drawers, modals — all keyboard-accessible (Esc closes overlays)

## Source-safety
All demo values are visibly tagged `[DEMO]`. Integrations not yet launched show `[NOT YET AVAILABLE]`. No fabricated revenue, funding, or outcome claims. Chat replies are clearly labeled as demo.

## Local dev
```
python3 -m http.server 3000
```
Then open `http://localhost:3000`.
