# Games hub: games.johnslagboom.com

This repo is the GitHub Pages **user site** for JBoom380. Its `CNAME` is `games.johnslagboom.com`, so every other JBoom380 repo that has Pages turned on is also served under that domain at `/<repo>/`.

## Add a game
1. Put the game in its own repo, then turn on Pages (Settings, then Pages, then deploy from `main`, root).
2. The game is now at `https://games.johnslagboom.com/<repo>/`.
3. Add one entry to the `GAMES` array in `index.html`, and add a 640x360 JPG thumbnail to `img/`.

## Rules
- **Any repo with Pages turned on is public at this domain.** Never turn on Pages for a private or campaign repo.
- Put adult games (violence, gore) in `section: 'adult'`. The hub then shows them in their own section behind an 18+ check. The game page itself must ALSO have its own 18+ check on first load, because direct links skip the hub.
- Never list adult games in the kids section, and never link to them from a kids game.
- Plain HTML, CSS, and JS. No build step, no external requests.
