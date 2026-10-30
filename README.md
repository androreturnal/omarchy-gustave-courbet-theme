# Gustave Courbet — Omarchy Theme

A dark, elegant Omarchy theme built from the **Gustave Courbet** palette. Dark canvas with cream text, desaturated olive/teal/slate accents, and bright green focus rings.

![Gustave Courbet](assets/themes/gustave-courbet.webp)

## Palette

| Role | Hex |
|------|-----|
| Background | `#070301` |
| Foreground | `#d6d19f` |
| Accent | `#69885c` |
| Selection | `#201c1a` |
| Muted | `#69645f` |
| Darker background | `#040201` |
| Lighter background | `#201c1a` |
| Bright cyan | `#e6fa96` |
| Bright yellow | `#fff293` |
| Bright white | `#e0ddb7` |
| Cyan | `#d0e192` |
| Green | `#c8c385` |
| Yellow | `#ffefa4` |
| Brown | `#6e5f4a` |
| Red | `#ab8e64` |
| Blue | `#69885c` |

## Features

- **Semantic CSS variables** — uses `--background`, `--foreground`, `--red`, `--green`, `--blue`, `--yellow`, `--cyan`, `--magenta`, `--brown`, `--bright_red`, `--bright_yellow`, `--bright_green`, `--bright_cyan`, `--bright_blue`, `--bright_magenta`, `--bright_foreground`, `--dark_background`, `--darker_background`, `--lighter_background`, `--selection`, `--accent`.
- **JetBrains Mono** font for the terminal and UI.
- **Glass panels** — `backdrop-filter: blur(2px)` on panels (via Hyprland/Ooma theme).
- **Compact mode support** — color sidebar and color toolbar.

## Installation

### Option 1: Install via Omarchy menu (recommended)

1. Open the Omarchy menu (`Super + Space`)
2. Go to **Settings → Themes**
3. Select **Gustave Courbet** from the list

### Option 2: Manual install

1. Clone this repository:
   ```bash
   git clone https://github.com/androreturnal/omarchy-gustave-courbet-theme.git
   ```

2. Copy the theme files to your Omarchy config:
   ```bash
   cp -r * ~/.config/omarchy/themes/gustave-courbet/
   ```

3. Set it as your active theme:
   ```bash
   omarchy theme set gustave-courbet
   ```

### Option 3: Custom colors.toml

Place your own `colors.toml` in `~/.config/omarchy/themes/gustave-courbet/` with your palette values.

## Files

- `README.md` — this file
- `assets/themes/gustave-courbet.webp` — theme screenshot
- `colors.toml` — palette source (931 chars)
- `colors.css` — generated semantic color definitions
- `userChrome.css` — browser UI overrides (font, compact mode, compact-mode colors)
- `userContent.css` — web content styling (removed for Zen Browser)

## Credits

Palette designed by the Omarchy community. Omarchy is Beautiful, Fun & Agentic Linux by DHH.

## License

MIT
