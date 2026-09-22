# Meck Care Finder

A mobile-first web app that helps Mecklenburg County, NC residents find mental health
resources. English and Spanish. No account, nothing saved.

## Run it
Open `index.html` in any browser (phone or computer). No install or build step.

## Put it online
Upload `index.html` to any static host (GitHub Pages, Netlify, Cloudflare Pages, etc.).

## Edit it
Everything is in `index.html`:
- `CONFIG` near the top of the script: app name and the email that
  "Report a problem" sends to (`reportEmail`).
- `RES`: the list of resources. Copy an existing entry to add one.
  Only mark a flag (`free`, `spanish`, `h24`, ...) true when a source confirms it.
- `T`: all English and Spanish interface text.

## Before public launch
- Re-verify every phone number, address and hour in `RES`.
- Set `reportEmail` so reports reach a real inbox.
- Assign someone to re-check listings on a schedule (quarterly is a common start).
- Have a Spanish speaker review the Spanish text.
