<p align="center">
  <img src="./icon.png" alt="logo" height="125" />
</p>
<h1 align="center">
  <br>Logseq One Theme<br>
</h1>

<p align="center">
  <a href="#screenshots">📸 Screenshots</a>
   | 
  <a href="#whats-changed">✨ What's changed</a>
   | 
  <a href="#install">📦 Install</a>
   | 
  <a href="#how-to-build">🔨 How to build</a>
   | 
  <a href="#credits">🙏 Credits</a>
</p>

<p align="center">A clean theme for <a href="https://github.com/logseq/logseq">Logseq</a> inspired by One Dark Pro.<br><b>Supports native accent colors!</b><br>Up-to-date and compatible to latest Logseq v0.10.5!</p>

## Screenshots
![](./preview.png)

| Dark | Light |
| --------------- | ---------------- |
| ![](./dark.png) | ![](./light.png) |

## What's changed

### Features

- included page property icons
- improved block reference style
- header labels
- included task and admonition block styles (as can be found in plugin logseq-awesome-content)
- integrated support for banners plugin
- support for new accent color selection (introduced in Logseq v0.10.0)
- numerous improvements & fixes to color scheme and polished header styles (compared to original Atmos theme)

### Inspired by: Atmos Theme

The Logseq One Theme in its first iteration is strongly inspired by [logseq-atmos-theme](https://github.com/Mat4m0/logseq-atmos-theme). Its stylesheet has been largely rewritten and this new theme aims to provide a cleaner experience and set some different accents.

<details>
  <summary>Basic differences</summary>

> This list might be outdated and there may be more differences now as this project is evolving. Probably there are more to come as the theme will go in another direction.

- scrollbar: less obtrusive
- headings
  - reduced weight of font
  - slightly less underlining thickness
  - restored normal case
- dark theme: accentuated bold and italic font color
- page & block properties: restyled with borders
- selection: better background color for selected blocks
- tasks: dim done or canceled elements (instead of strike through)
- journal: changed header icon
- links: adjusted hover style for external links
- Fix: invisible PDF annotation pages title
- Fix: missing hover style for PDF asset links
- Fix: inconsistent menu and header button styling and hover animations
- Fix: readability of light codemirror theme
- Fix: unwanted gradient background in left sidebar bottom area
- Fix: banners integration in wide mode
- Fix: unused variables, invalid CSS selectors / rules from Atmos
- Refactor: use standard Logseq variables to prevent redundant CSS rules
</details>

### Known issues / Roadmap

- [x] table styles
- [x] page tooltip layout
- [ ] complete accent color support (WIP)
- [ ] dark theme: mixture of bold and italic styles (consistency)
- [ ] light code mirror theme inconsistency

## Install

### Official marketplace

Find the One Theme in the Logseq in-app theme marketplace:
- Search for 'One Theme' in `Menu` → `Plugins` → `Marketplace` → `Themes`
- To select theme: `Menu` → `Themes` (or press `t` `i`)

### Manual installation

Copy `main.css` [contents](https://raw.githubusercontent.com/femto-code/logseq-one-theme/master/main.css) into `<graph_base>/logseq/custom.css`

## How to build

> Install [node](https://nodejs.org/)
1. Clone repo
  ```shell
  git clone https://github.com/femto-code/logseq-one-theme.git && cd logseq-one-theme
  ```
2. Install (development) dependencies (sass)
  ```shell
  npm install
  ```
3. Run build
  ```shell
  npm run build
  ```

## Credits

This is a theme for [Logseq](https://github.com/logseq/logseq) - a privacy-first, open-source platform for knowledge management and collaboration under [AGPL-3.0 license](https://github.com/logseq/logseq/blob/master/LICENSE.md).

Thanks to the following creators for inspiration and reference:

- [logseq-atmos-theme](https://github.com/Mat4m0/logseq-atmos-theme): `Copyright (c) 2022 Matthias A.` ([MIT License](https://github.com/Mat4m0/logseq-atmos-theme/blob/main/LICENSE))
  - (especially) banners integration, color palette, headers and dark code mirror theme
- [logseq-bujo-theme](https://github.com/stdword/logseq-bujo-theme): `Copyright (c) 2022 Sergey Kolesnik (@stdword)` ([MIT License](https://github.com/stdword/logseq-bujo-theme/blob/main/LICENSE))
  - block-ref style and page-property icons
- [logseq-awesome-content](https://github.com/yoyurec/logseq-awesome-content): `Copyright (c) 2022 Yuriy Piskun` ([MIT License](https://github.com/yoyurec/logseq-awesome-content/blob/main/LICENSE))
  - task and admonition block styles
- [logseq-ozean-theme](https://github.com/hisea/logseq-ozean-theme): `Copyright (c) 2022 Yinghai Zhao` ([MIT License](https://github.com/hisea/logseq-ozean-theme/blob/main/LICENSE))
  - light codemirror theme
- [logseq-mocha-theme](https://github.com/blueteafrog/logseq-mocha-theme): `Copyright (c) 2021 BlueTeaFrog` ([MIT License](https://github.com/blueteafrog/logseq-mocha-theme/blob/main/LICENSE))
  - page/block property container style and external link decoration

## Issues & Feedback
Feel free to submit an [issue](https://github.com/femto-code/logseq-one-theme/issues). Contributions and suggestions to improve the theme are welcome!

---
<div align="center">
Copyright © 2023 <a href="https://github.com/femto-code">femto-code</a>

[MIT License](./LICENSE)
</div>
