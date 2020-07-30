# hexo-patch-load-highlight-style

automatically load hexo code highlighting style, support highlight and prismjs

![npm](https://img.shields.io/npm/v/@jiangtj/hexo-patch-load-highlight-style.svg)
![hexo](https://img.shields.io/badge/hexo-5+-blue.svg)

## install

```bash
yarn add @jiangtj/hexo-patch-load-highlight-style
```

## config

add `theme` and `theme_dark` to the corresponding configuration, `theme_dark` will be applied when your system theme is dark

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

- support all [highlight](https://github.com/highlightjs/highlight.js/tree/master/src/styles) styles (e.g. {theme:a11y-light} load a11y-light.css)
- support all [prismjs](https://github.com/PrismJS/prism/tree/master/themes) and [prism-themes](https://github.com/PrismJS/prism-themes/tree/master/themes) styles (e.g. {theme:coy} load prism-coy.css)
- support auto load prism line_number plugin styles
- support auto load prism js when preprocess is false

## tutorials

- use it in default theme (landscape)
  1. install it, and then you can use multiple styles
- use it in theme
  1. [add dependencies](https://github.com/jiangtj/hexo-theme-cake/blob/d32b4d5174b0edca2a16c669e62f60fe150d765f/package.json#L44)
  2. [load it as hexo plugin](https://github.com/jiangtj/hexo-theme-cake/blob/d32b4d5174b0edca2a16c669e62f60fe150d765f/lib/load.js#L26) ([utils](https://github.com/jiangtj/hexo-theme-cake/blob/d32b4d5174b0edca2a16c669e62f60fe150d765f/lib/utils.js#L34))
  3. [adapt hljs layout](https://github.com/jiangtj/hexo-theme-cake/blob/a4644ff0081177d6c84a2f6becb568ed28e5799c/source/css/_styles/code.styl) (this plugin only loads colors and does not define layout)
