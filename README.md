# Grok Themes for Orca

Grok Night and Grok Day for [Orca](https://github.com/stablyai/orca): app colors, code colors and terminal colors in one data-only plugin.

The palette comes from the GrokNight and GrokDay themes in xai-org/grok-build, the same colors as [promptegrity/grok-themes](https://github.com/promptegrity/grok-themes) for Ghostty and Neovim.

## Install

Requires Orca 1.4.245 or newer.

1. Open **Settings > Plugins** and add a plugin from Git: `https://github.com/prabowosd/orca-grok-themes#v1.0.2` (Orca needs a tag or commit pin)
2. Pick **Grok Night** (or **Grok Day**) as the app theme.
3. Pick **Grok Night** (or **Grok Day**) as the terminal theme.

For local development, clone the repo and add the folder as a development plugin.

## Write-up

How the plugin is built and how its contrast measures: [Grok Night and Grok Day: a data-only theme plugin for Orca](https://sdp.im/blog/grok-night-and-grok-day-a-data-only-theme-plugin-for-orca).

## Palette

| Role | Night | Day |
|---|---|---|
| Frame (sidebar, tab bar) | `#161616` | `#eeeeee` |
| Editor and terminal | `#0e0e0e` | `#f5f5f5` |
| Cards, popovers | `#1a1a1a` | `#f0f0f0` |
| Selection | `#2a2a2a` | `#dedede` |
| Text | `#e1e1e1` | `#262626` |
| Primary | `#7aa2f7` | `#2F64D2` |
| Cursor | `#e0af68` | `#A27612` |

Grok Night keeps the frame a step lighter than the editor and terminal, so the work area sits recessed, like Herdr.

## Contents

- `orca-plugin.json`: manifest, format 2, `data` execution profile.
- `themes/`: app themes with TextMate `tokenColors`.
- `terminal-themes/`: terminal palettes.

## License

MIT for the plugin files. The colors are derived from grok-build's public palette definitions.
