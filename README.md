# Grok Themes for Orca

Grok Night and Grok Day for [Orca](https://github.com/stablyai/orca): app colors, code colors and terminal colors in one data-only plugin.

The palette comes from the GrokNight and GrokDay themes in xai-org/grok-build, the same colors as [promptegrity/grok-themes](https://github.com/promptegrity/grok-themes) for Ghostty and Neovim.

## Install

Requires Orca 1.4.245 or newer.

1. Open **Settings > Plugins** and add a plugin from Git: `https://github.com/prabowosd/orca-grok-themes`
2. Pick **Grok Night** (or **Grok Day**) as the app theme.
3. Pick **Grok Night** (or **Grok Day**) as the terminal theme.

For local development, clone the repo and add the folder as a development plugin.

## Palette

| Role | Night | Day |
|---|---|---|
| Background | `#141414` | `#eeeeee` |
| Editor surface | `#0a0a0a` | `#f5f5f5` |
| Sidebar | `#0c0c0c` | `#f0f0f0` |
| Border, selection | `#242424` | `#dedede` |
| Text | `#e1e1e1` | `#262626` |
| Primary | `#7aa2f7` | `#2F64D2` |
| Cursor | `#e0af68` | `#A27612` |

## Contents

- `orca-plugin.json`: manifest, format 2, `data` execution profile.
- `themes/`: app themes with TextMate `tokenColors`.
- `terminal-themes/`: terminal palettes.

## License

MIT for the plugin files. The colors are derived from grok-build's public palette definitions.
