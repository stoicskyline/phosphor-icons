<img src="/meta/phosphor-mark-tight-yellow.png" width="192" align="right" />

# phosphor-icons

A clear, playful, and adaptable icon family for web. A complete list of icons can be found on [our website](https://phosphoricons.com).

[![NPM](https://img.shields.io/npm/v/phosphor-icons.svg?style=flat-square)](https://www.npmjs.com/package/phosphor-icons) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](https://standardjs.com) [![Travis](https://img.shields.io/travis/com/rektdeckard/phosphor-icons.svg?style=flat-square)](https://travis-ci.com/github/rektdeckard/phosphor-icons)

[![GitHub stars](https://img.shields.io/github/stars/phosphor-icons/phosphor-icons?style=flat-square&label=Star)](https://github.com/phosphor-icons/phosphor-icons)
[![GitHub forks](https://img.shields.io/github/forks/phosphor-icons/phosphor-icons?style=flat-square&label=Fork)](https://github.com/phosphor-icons/phosphor-icons/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/phosphor-icons/phosphor-icons?style=flat-square&label=Watch)](https://github.com/phosphor-icons/phosphor-icons)
[![Follow on GitHub](https://img.shields.io/github/followers/rektdeckard?style=flat-square&label=Follow)](https://github.com/rektdeckard)

## Usage

### Getting Started

We use a similar approach as many other icon sets out there, providing icons as a webfont that uses Unicode's Private Use Area character codes to map normally non-rendering characters to icons. But you don't need to know that. All you need to do is add the script to the document `<head>`, and drop in icons with an `<i/>` tag and the appropriate class:

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://unpkg.com/phosphor-icons"></script>
  </head>
  <body>
    <i class="ph-smiley"></i>
    <i class="ph-heart-fill" style="color: hotpink"></i>
    <i class="ph-cube-thin"></i>
  </body>
</html>
```

> **Note:** For stability, you may choose to source a specific version of Phosphor by adding the version to the script URL, for example: `https://unpkg.com/phosphor-icons@0.5.0`. The CDN supports version ranges.

### Styling

Since the icons are just text under the hood, they can be colored and styled with CSS like any other font, including `font-size`, `color`, etc. We include several helper classes to provide easy sizing if you need it:

```css
.ph-xxs { font-size: 0.5em; }
.ph-xs { font-size: 0.75em; }
.ph-sm { font-size: 0.875em; }
.ph-lg { font-size: 1.3333em; line-height: 0.75em; vertical-align: -0.0667em; }
.ph-xl { font-size: 1.5em; line-height: 0.6666em; vertical-align: -0.075em; }
.ph-1x { font-size: 1em; }
.ph-2x { font-size: 2em; }
.ph-3x { font-size: 3em; }
.ph-4x { font-size: 4em; }
.ph-5x { font-size: 5em; }
.ph-6x { font-size: 6em; }
.ph-7x { font-size: 7em; }
.ph-8x { font-size: 8em; }
.ph-9x { font-size: 9em; }
.ph-10x { font-size: 10em; }
.ph-fw { text-align: center; width: 1.25em; }
```

> **Note:** Overriding the `font-family`, `font-style`, `font-weight`, `font-variant`, or `text-transform` may break the icons and render unprintable characters. Don't do it.

> **Note:** The `duotone` weight is not yet available for this implementation, as fonts do not support baked-in alpha/opacity. In future we plan to move to an SVG-based approach with full support for all icon weights.

## Related Projects
- [phosphor-react](https://github.com/phosphor-icons/phosphor-react) ▲ Phosphor icon component library for React
- [phosphor-vue](https://github.com/phosphor-icons/phosphor-vue) ▲ Phosphor icon component library for Vue
- [phosphor-figma](https://github.com/phosphor-icons/phosphor-figma) ▲ Phosphor icons Figma plugin

## License

MIT © [Phosphor Icons](https://github.com/phosphor-icons)
