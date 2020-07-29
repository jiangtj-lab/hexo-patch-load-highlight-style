# hexo-patch-load-highlight-style

自动加载hexo代码高亮的样式，支持highlight与prismjs

Automatically load hexo code highlighting style, support highlight and prismjs

## install

```bash
yarn add @jiangtj/hexo-patch-load-highlight-style
```

## config

对应的配置中新增 `theme` 与 `theme_dark`, `theme_dark` 会在你的系统主题为深色时应用

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

可用的样式见[highlight](https://github.com/highlightjs/highlight.js/tree/master/src/styles) [prismjs](https://github.com/PrismJS/prism/tree/master/themes)

See the available styles: [highlight](https://github.com/highlightjs/highlight.js/tree/master/src/styles) [prismjs](https://github.com/PrismJS/prism/tree/master/themes)
