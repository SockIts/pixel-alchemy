# Pixel / Alchemy — Arcane Edition

Standalone JavaScript canvas alchemy game. Open `index.html` or publish to GitHub Pages.

## Recipes

On internet access, the game reads and parses the original classic Little Alchemy recipe table from `alancnet/little-alchemy` at runtime (540 elements, 890 two-element recipes). No external script is executed. The original repository has no explicit LICENSE file; verify reuse rights for any redistribution, and attribution is included in the UI. Offline, the original prototype's 27-element starter subset remains usable.

Includes 211 original 3-input Advanced Synthesis blueprints. Check `advanced-recipes.json` for authoring. Some higher-tier recipes require discovering supporting intermediate elements.

## Gameplay

Normal mixing: select 2 ingredients. Advanced synthesis: select 3 ingredients. Discoveries are saved to localStorage in your browser. A successful mix holds the resulting sprite in the center for about 1.8 seconds before fading.

## Deploy on GitHub Pages

Create a **public** repo; upload `index.html`, `advanced-recipes.json`, and `README.md` to branch `main`; go to Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)`. Wait for the Pages deployment to finish and use its URL.
