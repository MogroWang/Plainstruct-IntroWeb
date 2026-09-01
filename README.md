# 素构 Plainstruct · 介绍页

[素构 Plainstruct](https://github.com/MogroWang/Plainstruct) 的产品介绍单页。纯静态实现:一个 `index.html` 加静态资源,没有构建步骤,没有外部依赖,直接打开就能用。

> 素构是一个本地运行的静态文档网站创建器——在文件夹里写 Markdown,一键构建、本地预览、发布到 GitHub Pages。不需要命令行,不需要后端。

## 本地预览

直接双击打开 `index.html` 即可;也可以起一个本地静态服务器:

```bash
# 任选其一
python -m http.server 8000
npx serve .
```

然后访问 `http://localhost:8000`。

## 目录结构

```
index.html                          页面全部内容(结构、样式、脚本内联)
assets/
  favicon.svg                       标签页图标(白色圆形底、黑色 logo 居中)
  plainstruct-logo.svg              品牌 mark(图形部分)
  plainstruct-logo-full.svg         完整组合 logo(浅色背景用)
  plainstruct-logo-full-dark.svg    完整组合 logo(深色背景用)
  mogrowang-studio.svg              MogroWang Studio 署名
  preview-*.png                     产品界面截图
```

## 版本

版本号按日期取数,格式 `YYYYMMDD`,更新记录见 [changelog.md](changelog.md)。当前版本:**20260901**,展示于页面底部。

## 相关链接

- 素构 Plainstruct 主仓库:<https://github.com/MogroWang/Plainstruct>
- 版本发布:<https://github.com/MogroWang/Plainstruct/releases>
- MogroWang Studio:<https://www.mogrowangstudio.top/>

---

© 2026 MogroWang Studio · Plainstruct
