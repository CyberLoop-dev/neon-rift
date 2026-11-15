<div align="center">

<img src="assets/banner.svg" alt="Neon Rift animated banner" width="100%"/>

# Neon Rift

**A one-file neon arcade game. No build step, no dependencies.**

![HTML5](https://img.shields.io/badge/HTML5-Canvas-ff3d9a?style=for-the-badge)
![Zero deps](https://img.shields.io/badge/dependencies-0-3df5ff?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-ffc83d?style=for-the-badge)

</div>

## Play

Open `index.html` in any modern browser. Or host it for free with GitHub Pages: **Settings → Pages → Deploy from branch → `main` / root**.

## How to play

| Input | Action |
|---|---|
| Mouse / touch drag | Steer the ship |
| `←` `→` or `A` `D` | Steer with keyboard |

- Collect **cyan shards** to build a combo (up to ×10).
- Dodge **pink blocks**. One hit ends the run.
- Missing a shard resets your combo. Speed rises the longer you survive.
- Best score is saved in your browser.

## Project layout

```
neon-rift/
├── index.html        # the entire game (HTML + CSS + JS)
├── assets/banner.svg # animated README banner
├── docs/
│   ├── DESIGN.md     # UI/UX decisions and tokens
│   └── SKILLS.md     # AI-assisted workflow notes
├── LICENSE
└── README.md
```

## Tweak it

Constants live at the top of the script in `index.html`: ship size (`r`), starting speed (`sp`), spawn rate and acceleration (`step()`). Colors are CSS variables in `:root`.

## Roadmap

- [ ] Sound effects (WebAudio)
- [ ] Power-ups (shield, slow-mo)
- [ ] Online leaderboard

## License

MIT, see [LICENSE](LICENSE).
