# 我的网站

CYRickyArAr 的个人网站导航，集中展示五个已配置 GitHub Pages 的小网站。

## 本地预览

直接用浏览器打开 `index.html`。页面使用纯 HTML 和 CSS，不需要安装依赖或构建，也不依赖 JavaScript、第三方字体或统计服务。

## 文件

- `index.html`：网站名称、简介和链接。
- `styles.css`：桌面和手机布局。
- `favicon.svg`：导航页自己的站点图标。
- `assets/icons/`：从原网站保存的图标。
- `.nojekyll`：使 GitHub Pages 直接发布静态文件。

## 发布

目标仓库：`CYRickyArAr/CYRickyArAr.github.io`。

1. 将本目录文件提交到目标仓库的 `main` 分支。
2. 在仓库的 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支、`/ (root)` 目录，保存并等待部署完成。
4. 访问 `https://cyrickyarar.github.io/`。

发布这个导航页不需要修改原有五个网站的仓库。不要添加全站 Service Worker 或自定义域名，以免改变现有项目站点的访问行为。

## 更新网站列表

在 `index.html` 的 `.site-list` 中编辑相应的 `<li class="site">`。新增时复制一个完整条目，修改图标、名称、简介、分类、访问链接、源码链接及 `aria-label`，并同步更新“5 个网站”和本说明中的数量。

站点链接与源码链接均在新标签页打开，保留 `target="_blank"` 和 `rel="noopener noreferrer"`。所有图标和样式均保存在本地。

## 图标来源与维护

优先沿用原网站的 favicon 或首页标识；确实没有现成标识时才自绘。图标文件保存到本仓库，不依赖第三方图标服务或原站发布目录的长期可用性。

- 智能练习：沿用首页 `.cube-mark` 的 `▦` 符号及黑底白字样式。
- ZBLL：`assets/icons/zbll.svg` 原样来自 https://cyrickyarar.github.io/zbll_site_static/images/icons/zbll-icon.svg 。
- WCA：`assets/icons/wca.svg` 原样来自首页声明的 https://cyrickyarar.github.io/wca-statistics/releases/bcb6386d0ba43036/cube.svg 。后续更新时重新查看首页 favicon 地址，不要依赖旧发布版本号。
- VisualCube：沿用原站标题中的 `🧊`，显示样式随操作系统而异。
- 词语记忆测试：`assets/icons/verbal-memory.svg` 提取自原站首页 `.icon` 中的 SVG，保留图形与颜色；导航页使用蓝色底衬使白色图案清晰可见。

原站更换图标后，手动更新相应本地文件。以上调整不修改原网站。

## 收录网站

- [智能练习](https://cyrickyarar.github.io/cube-training-stats/)
- [ZBLL 公式库](https://cyrickyarar.github.io/zbll_site_static/)
- [WCA 连续平均统计](https://cyrickyarar.github.io/wca-statistics/)
- [VisualCube](https://cyrickyarar.github.io/visualcube/)
- [词语记忆测试](https://cyrickyarar.github.io/verbal_memory_test/)

`ChillPass` 未查询到 GitHub Pages 配置，暂未收录。
