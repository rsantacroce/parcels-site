# Parcels website

Landing page, manual and 3D asset list for [Parcels](https://github.com/rsantacroce/parcels),
served by GitHub Pages at https://rsantacroce.github.io/parcels-site/.

Plain HTML and CSS, no build step. Preview with `python3 -m http.server` in this folder.

- `index.html`: landing page. Download buttons resolve to the latest release's archives through the GitHub API.
- `manual.html`: how to play.
- `assets.html`: the model list with Meshy prompts. It loads `assets/catalog.json` from the game
  repo's `main` branch and falls back to the copy in this folder.
- `img/`: screenshots taken with the game's `--shot` flag.
