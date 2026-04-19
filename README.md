# DPSC Spring 2026 Volleyball Tournament

Single-page web app for tracking the DPSC Spring 2026 volleyball tournament — schedule, standings, match results, bracket, teams, and an admin view.

## What's in here

- `index.html` — the entire site, in a single self-contained file (HTML + CSS + JS).

## Running it

No build step. Just open `index.html` in a browser:

```bash
open index.html
```

Or serve the folder locally if you prefer:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Sections

- Home — tournament overview and sponsor strip
- Schedule — match-by-match day plan
- Standings — points table
- Matches — live/recent match cards
- Bracket — playoff bracket view
- Teams — roster by captain
- Admin — (password-gated) score entry and management
