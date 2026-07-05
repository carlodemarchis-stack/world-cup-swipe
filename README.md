# World Cup 2026 — Swipe

A mobile-first, swipe-based companion to the [radial bracket](https://carlodemarchis-stack.github.io/world-cup-bracket/).

A 2D swipe grid: swipe **left/right** between teams, **up** for a team's matches, **down** for its squad. Each list-bearing card (matches, squad) is the *home* of a deeper list — swipe **right** to browse into it (matches → match detail, squad → player profiles).

- Self-contained `index.html` (vanilla JS), no build step.
- Data is fetched live from the bracket's GitHub Pages: `data.json` (teams, groups, knockout, squads) + `fantasy.json` (FPL points) — so it inherits the bracket's hourly FIFA auto-updates.
- Design ported from the bracket (Barlow / Barlow Condensed, light theme).

**Live:** https://carlodemarchis-stack.github.io/world-cup-swipe/
