# Monokai Dark Vibrant 2 Theme

![GitHub license](https://img.shields.io/github/license/Nekitoz/monokai-dark-vibrant-2.svg)

[![GitHub stars](https://img.shields.io/github/stars/Nekitoz/monokai-dark-vibrant-2.svg?style=social&label=Star&maxAge=2592000)](https://github.com/Nekitoz/monokai-dark-vibrant-2)

> This is a fork of [larscom/monokai-dark-vibrant](https://github.com/larscom/monokai-dark-vibrant) by Lars Kniep, updated for modern VS Code: semantic highlighting, bracket pair colors, terminal ANSI colors, inlay hints, sticky scroll, git decorations and other UI elements added since 2019.
>
> Fork: https://github.com/Nekitoz/monokai-dark-vibrant-2

## Introduction

This theme is optimized for TypeScript/JavaScript and HTML/CSS but other languages should work as well. This theme does not have any italic/bold fonts.

## Installing

Download the latest `.vsix` file from [GitHub Releases](https://github.com/Nekitoz/monokai-dark-vibrant-2/releases/latest), then either:

- in VS Code open the Extensions view, click `...` → **Install from VSIX...** and pick the file, or
- run in a terminal:

```
code --install-extension monokai-dark-vibrant-2-<version>.vsix
```

Then select the theme: `Ctrl+K Ctrl+T` → **Monokai Dark Vibrant 2**.

## Building

```
npx @vscode/vsce package
```

Pushing a tag `v<version>` (matching `version` in `package.json`) builds the `.vsix` and attaches it to a GitHub Release automatically.

## Preview

### TypeScript

![](https://raw.githubusercontent.com/Nekitoz/monokai-dark-vibrant-2/master/screenshots/typescript.png)

### HTML

![](https://raw.githubusercontent.com/Nekitoz/monokai-dark-vibrant-2/master/screenshots/html.png)

### JSX/TSX

![](https://raw.githubusercontent.com/Nekitoz/monokai-dark-vibrant-2/master/screenshots/react.png)

## Customization

You can override any color of this theme in your settings with `workbench.colorCustomizations` and `editor.tokenColorCustomizations`. More info [here](https://code.visualstudio.com/docs/getstarted/theme-color-reference).

## Questions/suggestions?

Create an issue on [GitHub](https://github.com/Nekitoz/monokai-dark-vibrant-2/issues)
