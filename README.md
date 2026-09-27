# Fokus

A borderless Obsidian theme with 18 color schemes (light + dark each) and a distraction-free focus window.

![Fokus](screenshots/fokus.jpg)

## Features

- Borderless panes separated by tone; floating menus and modals by shadow.
- 18 color schemes, each with light and dark variants, all meeting WCAG AA contrast.
- AMOLED black option for dark mode.
- Follows Obsidian's **Settings → Appearance → Accent color**; each scheme uses its own accent until one is set.
- Rounded editor and settings corners beside the ribbon and sidebars.
- Optional colored headings and colored bold / italic (inside notes only).
- Uses your own fonts.

## Focus window

Install the companion plugin **[Fokus Window Mode](https://github.com/ike-V/obsidian-fokus-window-mode)** to hide the ribbon, sidebars, tab bar, title bar and status bar with ⌘+\ or a tab-bar chevron.

![Focus window across color schemes](screenshots/focus-window.jpg)

![Writing in the focus window](screenshots/writing.jpg)

## Install

**Settings → Appearance → Themes → Manage → search "Fokus" → Install and use.**

Manual: copy `theme.css` and `manifest.json` into `.obsidian/themes/Fokus/`.

## Settings

Requires the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.

| Setting | Options |
|---|---|
| Color scheme | Ayu, Catppuccin, Dracula, Everforest, Flexoki, Fokus (default), Fokus (muted), Gruvbox, Kanagawa, Nord, One, Paper, Placidity, Primer, Rosé Pine, Solarized, Tokyo Night, Violentz |
| AMOLED black | Pure black backgrounds (dark mode) |
| Line length | Text column width; needs Readable line length on |
| Corner radius | 0–40 px |
| Colored headings | On / off |
| Colored bold & italic | On / off |
| Hide the ribbon / tab bar / title bar / status bar | What the focus window hides |
| Hide the chevron buttons | Use ⌘+\ only |

## Credits

Unofficial ports of these open-source palettes (all MIT):

| Scheme | Palette | Author |
|---|---|---|
| Ayu | [ayu](https://github.com/ayu-theme/ayu-colors) | Konstantin Pschera |
| Catppuccin | [Catppuccin](https://github.com/catppuccin/catppuccin) | Catppuccin |
| Dracula | [Dracula](https://github.com/dracula/dracula-theme) | Zeno Rocha |
| Everforest | [Everforest](https://github.com/sainnhe/everforest) | sainnhe |
| Flexoki | [Flexoki](https://github.com/kepano/flexoki) | Steph Ango |
| Gruvbox | [gruvbox](https://github.com/morhetz/gruvbox) | Pavel Pertsev |
| Kanagawa | [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) | Tommaso Laurenzi |
| Nord | [Nord](https://github.com/nordtheme/nord) | Sven Greb |
| One | [One Dark / One Light](https://github.com/atom/atom) | Atom |
| Placidity | [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss) indigo and gray | Tailwind Labs |
| Primer | [Primer](https://github.com/primer/primitives) | GitHub |
| Rosé Pine | [Rosé Pine](https://github.com/rose-pine/rose-pine-theme) | Rosé Pine |
| Solarized | [Solarized](https://github.com/altercation/solarized) | Ethan Schoonover |
| Tokyo Night | [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) | enkia |

Some colors were adjusted to meet contrast requirements.

## License

[MIT](LICENSE)
