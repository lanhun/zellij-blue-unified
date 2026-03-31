# Blue Unified - Terminal Theme

A bright blue dark theme for [Zellij](https://zellij.dev/) and [Ghostty](https://ghostty.org/), colors unified across both tools.

## Color Palette

| Role | Color | Contrast |
|------|-------|----------|
| Background | `#161e2e` `rgb(22, 30, 46)` | - |
| Foreground (text) | `#c0d5e8` `rgb(192, 213, 232)` | 11.1:1 (AAA) |
| Bright Blue (accent) | `#50c3ff` `rgb(80, 195, 255)` | - |
| Medium Blue (borders) | `#0055a5` `rgb(0, 85, 165)` | - |
| Selection | `#50c3ff` on `#161e2e` | - |
| Success | `rgb(80, 200, 160)` | - |
| Error | `rgb(230, 100, 100)` | - |

## Zellij Theme

Copy the theme from `blue-unified.kdl` into `~/.config/zellij/config.kdl`:

```kdl
themes {
    // ... paste content from blue-unified.kdl
}

theme "blue-unified"
```

Or copy to themes directory:

```bash
mkdir -p ~/.config/zellij/themes
cp blue-unified.kdl ~/.config/zellij/themes/
```

Requires Zellij 0.44+. Full coverage of all 15 theme color groups.

## Ghostty Config

Copy `ghostty-config.ghostty` to your Ghostty config location:

```bash
# macOS
cp ghostty-config.ghostty ~/Library/Application\ Support/com.mitchellh.ghostty/config
```

Uses Dracula as base theme with color overrides to match Zellij.

## License

MIT
