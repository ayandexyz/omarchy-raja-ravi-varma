# Ancient Indian Theme

An Omarchy theme inspired by the pigments, stones, and textiles of the Indian subcontinent — temple sandstone, sindoor vermillion, turmeric gold, peepal green, indigo, and lotus pink on a charred-temple dark canvas.

## Palette at a glance

- **Background:** charred temple interior, deep sandstone
- **Foreground:** aged parchment / manuscript ink
- **Accent:** turmeric gold (`#e6a23c`)
- **Highlights:** sindoor red, marigold yellow, peepal green, indigo blue, lotus magenta

## Install (local development)

```bash
cp -r omarchy-ancient-indian-theme ~/.config/omarchy/themes/
```

Then pick it from the Omarchy theme menu (Super + Alt + Space → Style → Theme).

## Install (from repo, once published)

```
Super + Alt + Space → Install → Style → Theme → <repo URL>
```

Recommended name: `omarchy-ancient-indian-theme` (becomes `ancient-indian` in the menu).

## What's included

- `colors.toml` — base palette (regenerates terminal, Hyprland, btop, Chromium, Neovim, Helix, VSCode, Obsidian, Omarchy shell)
- `icons.theme` — Yaru-wartybrown (earthy icon set)
- `backgrounds/` — drop your own wallpapers here

## Things to add later

- `unlock.png` + `preview-unlock.png` for Plymouth (transparent PNG preferred for unlock)
- Run `omarchy plymouth preview` to regenerate the unlock preview
- App-specific overrides (`btop.theme`, `chromium.theme`, `shell.toml`) if you want to fine-tune

## Distributing

The name follows the `omarchy-<themename>-theme` convention so it shows as `ancient-indian` in the menu. Don't ship `.lua`, terminal configs, or `vscode.json` — those get stripped on install for security. Build the theme around colors only.
