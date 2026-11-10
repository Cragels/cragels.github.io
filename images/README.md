# Images folder

Drop your pictures in here using these exact file names (or edit the names in `index.html` / `style.css`):

| File | Used for |
|---|---|
| `profile.jpg` | Profile photo (top left) |
| `bg-grey.jpg` | Grey cloudy background (header + About) |
| `bg-wood.jpg` | Wood texture background (Portfolio + Contact) |
| `art.jpg` | Art tile |
| `code.jpg` | Code tile |
| `vega-logo.png` | Vega School logo |
| `linkedin-icon.png` | LinkedIn icon |
| `itch-icon.png` | itch.io icon |
| `email-icon.png` | Email icon |

Tip: keep images under ~500 KB each so the site loads quickly.
Names are case sensitive on GitHub Pages (`Profile.jpg` is not `profile.jpg`).

## Sub-page folders

Put gallery images for the Art page in `images/art/` (blacksmith1-4.jpg, hammer1-4.jpg, forge1-4.jpg). The video on that page is a YouTube embed set in `art.html`.
and project screenshots for the Code page in `images/code/` (project1.jpg, project2.jpg, project3.jpg).
Edit titles, captions and links directly in `art.html` and `code.html`; copy a block to add more items.

## Background tiles

`bg-grey.jpg` and `bg-wood.jpg` repeat (tile) across the page. Use seamless tiles around 256-512px square and keep each under ~100 KB.
To change how zoomed in they look, edit `--tile-size` at the top of `style.css` (e.g. `250px` for smaller, `auto` for real size).

## Game Projects page

All game cover images sit directly in `images/games/` (no sub folders), named after the game's `id` in `games.html`: `2skate.jpg`, `guiding-light.jpg`, `garden-growers.jpg`, `tower-defense.jpg`, `mecha-rush.jpg`, `finding-yarnitjie.jpg`.
Covers should be 630 x 500 px. Clicking a cover opens the game's itch.io link.
The Game Projects tile on the home page still uses `images/code.jpg` (rename it if you like, and update `index.html`).
The old `images/code/` folder is no longer used.


CV: put your CV PDF in the main website folder (next to index.html) and name it `CraigHarrod-CV.pdf`. The Download CV button on the home page links to it.
