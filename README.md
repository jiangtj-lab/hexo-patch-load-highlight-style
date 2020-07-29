# hexo-patch-load-highlight-style

自动加载hexo代码高亮的样式，支持highlight与prismjs

## install

```bash
yarn add @jiangtj/hexo-patch-load-highlight-style
```

## config

对应的配置中新增 `theme` 与 `theme_dark`, `theme_dark` 会在你的系统主题为深色时应用

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
