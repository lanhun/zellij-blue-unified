# Blue Unified - Zellij Theme

A bright blue dark theme for [Zellij](https://zellij.dev/) terminal multiplexer (v0.44+).

## Preview

- Deep navy background (`22, 30, 46`)
- Bright blue accents (`80, 195, 255`)
- Blue highlighted borders (`0, 85, 165`)
- Clean white/black ribbon contrast
- Full coverage of all 15 theme color groups

## Color Palette

| Role | Color |
|------|-------|
| Background | `rgb(22, 30, 46)` |
| Bright Blue (accent) | `rgb(80, 195, 255)` |
| Medium Blue (borders) | `rgb(0, 85, 165)` |
| Muted Blue (text) | `rgb(140, 170, 200)` |
| Success | `rgb(80, 200, 160)` |
| Error | `rgb(230, 100, 100)` |

## Installation

Copy the theme block from `blue-unified.kdl` into your `~/.config/zellij/config.kdl`:

```kdl
// Add inside your config.kdl
themes {
    // ... paste theme content here
}

theme "blue-unified"
```

Or copy the file to your Zellij themes directory:

```bash
mkdir -p ~/.config/zellij/themes
cp blue-unified.kdl ~/.config/zellij/themes/
```

Then set in `config.kdl`:

```kdl
theme "blue-unified"
```

## License

MIT
