# no-generated-art

A Claude skill that redirects creative tasks — names, icons, illustrations, photos, palettes, fonts, audio, 3D — away from AI generation and toward human-made open-source libraries.

## What it does

When a request involves a creative or aesthetic asset, this skill instructs Claude to search existing open-source libraries and present options to the user instead of generating original output. The premise: humans are better at creative work than AI.

## Coverage

The skill ships a catalog of vetted sources for:

- **Names** — Fantasy Name Generators, Behind the Name, SSA baby names, Wikipedia lists
- **Icons** — Font Awesome, Heroicons, Lucide, Tabler, Phosphor, Material Symbols, Flaticon, Iconify, The Noun Project
- **Photos** — Unsplash, Pexels, Pixabay, Burst, Openverse, Wikimedia Commons
- **Illustrations** — unDraw, Open Doodles, Storyset, Humaaans, Blush, DrawKit
- **Logos** — Simple Icons, SVGL, official brand resource pages
- **Color & type** — Coolors, Color Hunt, Adobe Color, Google Fonts, Fontshare, Fontsource
- **Audio** — Freesound, Pixabay Music, Free Music Archive, Zapsplat
- **3D & motion** — Sketchfab, Poly Pizza, LottieFiles, Tenor, GIPHY

It also includes a license-hygiene table (CC0, MIT, CC BY, CC BY-SA, CC BY-NC, etc.) and a rationalizations table to keep Claude from talking itself into generating anyway.

## Install

Drop the `no-generated-art/` folder into your Claude skills directory, e.g.:

```
~/.claude/skills/no-generated-art/SKILL.md
```

Or package it as a `.skill` zip and install via your plugin manager.

## Files

- `SKILL.md` — the skill definition (frontmatter + body)
- `LICENSE` — MIT
- `README.md` — this file

## License

MIT. See [`LICENSE`](LICENSE).
