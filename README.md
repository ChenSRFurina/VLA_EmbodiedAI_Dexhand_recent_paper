# 2026 Embodied AI / VLA / DexHand 论文阅读指南

公开阅读地址：**https://chensrfurina.github.io/VLA_EmbodiedAI_Dexhand_recent_paper/**

按 2026 年会议归属精选 20 篇论文，覆盖 ICLR、ICML、NeurIPS、CVPR、ECCV、RSS、ICRA 和 CoRL。每篇包含问题、方法步骤、实验依据、局限、精读建议和原始来源。

核查日期：2026-10-13。会议官方收录和作者录用声明分别标注；优先级为阅读建议，不是官方排名。

## 使用

打开网页即可阅读，支持关键词搜索、方向／会议／优先级筛选、浏览器内的已读标记，以及打印保存 PDF。已读标记保存在当前设备的浏览器中，不跨设备同步。

## 发布

- `index.html`：完全独立的静态网页，无需安装依赖或构建。
- `papers.json`：结构化论文资料。
- `.nojekyll`：让 GitHub Pages 原样发布静态文件。
- `main`：源文件分支；`gh-pages`：公开网站的发布分支。

修改后，将同一提交推送到两个分支即可更新：

```sh
git push origin main main:gh-pages
```

GitHub Pages 使用 `gh-pages` 分支根目录。部署状态可在仓库的 Actions 页面查看。
