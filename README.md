# Perfect Profile — Spatial Clue Preview

GitHub Pages-ready prototype generated from `Perfect_Profile_100_Levels_Theme_Designed_Spatial_Wording_Fixed(1).xlsx`.

## What is simulated
- Immediate correct placement: yellow pulse, accepted into the grid.
- Wrong placement: red/pink cell shake, value rejected, one of two lives removed.
- Out of lives modal and QA refill.
- Progressive clue state machine: initial clues, fact/clue-completion unlock, 1–2 clue reveal batch, phase/progress gate, manual Reveal.
- Completed clue turns green with a check; new clue slides into the clue tray.
- “Fill the grid to get more clues” gate.
- Level Complete modal and final reveal.

## GitHub Pages
Upload every item inside this folder to the repository root. Keep `index.html`, `app.js`, `style.css`, and `data/levels.json` at the same relative paths. Enable Settings → Pages → Deploy from branch → main → /(root).

## Notes
The reveal graph for the redesigned 100 levels is inferred from each machine constraint, dependency, authored clue order, phase, and grid progress. The exact original runtime trigger graph is only directly observable for the provided Level 1–10 walkthrough.
