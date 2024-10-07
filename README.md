本项目 fork 自 [favourhong/Awesome-Marp: 🤙 Easy replacement for LaTeX Beamer! 🥂 custom Marp templates with a selection of over a dozen themes](https://github.com/favourhong/Awesome-Marp) , 删除了一些不必要的资源。使用案例见 `Awesome-Marp/files` 。

# Awesome Marp：轻松取代 LaTeX Beamer！

总结一下，像上面的这样的自定义样式，目前 Awesome Marp 1.3 版本一共支持 38 个！使用时只需要在页面指定局部指令，比如： `<!-- _class: trans -->`）

![38 种自定义样式](./images/38种自定义样式.png)

不光如此，我还设计了 6 种主题色，想要切换 theme，只需要可在 YAML 区定义 `theme: <theme_name>`：

![6种主题颜色](./images/6种主题颜色.png)

## 如何使用 Awesome Marp？

- 如何使用：

  - **搭配 VS Code**：直接使用 VS Code 打开 `Awesome-Marp` 文件夹
    - 如果你想「拿来即用」，直接根据我分享的 Markdown 源码文件，对照修改就好了~
    - 如果你对部分效果不满意、期望简单微调的话，目前在 `Awesome-Marp/themes` 下有 6 个 CSS 文件，这些 CSS 文件决定了 Markdown 源码的最终渲染效果，可以试着改一改~
    - 如果你能够自行定制个性化 CSS 文件，渲染前，别忘在 `Awesome-Marp/.vscode/settings.json` 里加上你的 CSS 文件路径~
  - **搭配 Obsidian**：安装 [Marp Slides 插件](https://github.com/samuele-cozzi/obsidian-marp-slides)，并配置相应 CSS 路径
- 字体：因担心版权问题，需自行下载字体并安装，Awesome Marp 用到的字体有：

  - 正文字体：`Latin Modern Math`、`方正宋刻本秀楷简体`，如果未安装，默认将使用 `Calibri` 和 `楷体`
  - 标题字体：`Optima LT Medium`、`方正苏新诗柳楷简体`，如果未安装，默认将使用 `Arial` 和 `黑体`
  - 脚注字体：`Charm` 和 `叶根友毛笔行书修正版`，如果未安装，默认将使用 `Calibri` 和 `楷体`
  - 代码字体：`Fira Code` 和 `霞鹜文楷等宽`，如果未安装，默认将使用 `Consolas` 和 `华文中宋`
