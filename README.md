# Super Mario Clone

A browser platformer built with JavaScript and Kaboom.js, following [Ania Kubów's tutorial](https://youtu.be/2nucjefSr6I).

This learning project explores sprite loading, collision behavior, level maps, and keyboard-driven gameplay. The tutorial foundation is credited below.

## Play locally

Open `index.html` in a browser. An internet connection is required because the page loads Kaboom.js 0.5.0 from `kaboomjs.com`.

For a local HTTP server, run from the repository root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`. If the external Kaboom script is unavailable, the game cannot initialize.

## Controls

| Key | Action |
| --- | --- |
| Left / right arrow | Move |
| Space | Jump |

Jump onto enemies, hit question blocks, collect mushrooms, and use pipes to move between levels. Mushrooms temporarily increase Mario's size.

## Level previews

### Level 1

![Level 1 gameplay](gameplay_screenshots/level1.jpg)

### Level 2

![Level 2 gameplay](gameplay_screenshots/level2.jpg)

### Level 3

![Level 3 gameplay](gameplay_screenshots/level3.jpg)

## Code map

- `index.html` loads Kaboom and the game.
- `mario.js` defines sprites, scenes, level maps, and gameplay.
- `mario.css` contains page styling.
- `sprites/` contains game assets.

## Credits

The base was created by coding along with [Ania Kubów / @kubowania](https://github.com/kubowania)'s [YouTube tutorial](https://youtu.be/2nucjefSr6I). Mario characters and branding belong to their respective owners. This is an educational fan project.
