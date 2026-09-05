# Discovery One

A dark, architectural Omarchy theme inspired by the clean geometry, practical
futurism, and quiet unease of *2001: A Space Odyssey*.

![Discovery One preview](preview.png)

## Character

Graphite spacecraft panels, warm ivory text, cool instrument shadows, and one
HAL-like signal-red indicator. The terminal palette adds restrained amber,
phosphor teal, blue, and diagram magenta without turning the desktop into a
neon or gamer theme.

## Install

```bash
omarchy theme install https://github.com/Devis99/omarchy-discovery-one-theme.git
omarchy theme set discovery-one
```

To remove it, delete `~/.config/omarchy/themes/discovery-one` and select another
theme.

## Palette

![Discovery One signal palette](assets/discovery-one-palette.png)

| Role | Hex | Description |
|---|---|---|
| Background | `#111d1f` | Graphite teal-black |
| Foreground | `#d6d1bf` | Warm ivory |
| Signal | `#e85854` | HAL signal red |
| Telemetry | `#daa843` | Instrument amber |
| Phosphor | `#2d9570` | Phosphor green |
| Instrument | `#39abab` | Cool instrument teal |
| Display | `#2d7db9` | CRT display blue |
| Diagram | `#c274a9` | Diagram magenta |

## Included

![Discovery One cinematic wallpaper collection](assets/discovery-one-wallpapers-mosaic.png)

- `colors.toml` — Omarchy colour definitions and ANSI terminal palette
- `vencord.theme.css` — compact System24 spacecraft-instrument styling for Vencord/Vesktop
- `icons.theme` — Yaru icon theme
- `backgrounds/` — 24 curated 3840×1760 *2001* spacecraft, station, and
  computer-interface frames
- `DESIGN.md` — visual direction and role rules
- `backgrounds/SOURCES.md` — wallpaper frame references

Discovery One is intentionally quiet: red is reserved for focus and warning,
while the wallpapers and window layout provide most of the depth.

The Discord stylesheet is applied automatically when the THPM Discord
integration is enabled. Otherwise, copy `vencord.theme.css` into your Vencord or
Vesktop themes directory and enable it in Discord's **Settings → Themes**.

## Image credits

The wallpaper frames are from *2001: A Space Odyssey* (1968), sourced from
[Movie-Screencaps](https://www.movie-screencaps.com/2001-a-space-odyssey-1968-4k/)
and hosted by [Screencaps](https://imgs.screencaps.us/196/4k-8-spaceodyssee/full/).
Individual frame references are listed in
[`backgrounds/SOURCES.md`](backgrounds/SOURCES.md).
