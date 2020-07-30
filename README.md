# hexo-patch-load-highlight-style

Automatically load hexo code highlighting style, support highlight and prismjs

![npm](https://img.shields.io/npm/v/@jiangtj/hexo-patch-load-highlight-style.svg)
[![Theme](https://img.shields.io/badge/hexo-5+-blue.svg)](https://theme-next.org)

## install

```bash
yarn add @jiangtj/hexo-patch-load-highlight-style
```

## config

Add `theme` and `theme_dark` to the corresponding configuration, `theme_dark` will be applied when your system theme is dark

```yml
highlight:
  # ...
  theme: default
  theme_dark: default
prismjs:
  # ...
  theme: default
  theme_dark: default
```

## feature

- Support all [highlight](https://github.com/highlightjs/highlight.js/tree/master/src/styles) styles (e.g. {theme:a11y-light} load a11y-light.css)
- Support all [prismjs](https://github.com/PrismJS/prism/tree/master/themes) and [prism-themes](https://github.com/PrismJS/prism-themes/tree/master/themes) styles (e.g. {theme:coy} load prism-coy.css)
- Support auto load prism line_number plugin styles
- Support auto load prism js when preprocess is false


