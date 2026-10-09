# 明睿杰 · 个人简介

基于 GitHub Pages 发布的个人简介网页。

## 功能

- 单文件自包含（`index.html`），无任何构建依赖，打开即用
- 深浅色主题切换、响应式布局（桌面 / 平板 / 手机）
- 内容全部由页面内置数据驱动，方便直接维护

## 自定义内容

编辑 `index.html` 顶部的 `CONFIG` 对象（姓名、技能、经历、项目、联系方式等），提交后重新部署即可，所有访客都会看到新内容。

## 本地运行

直接双击 `index.html` 用浏览器打开即可，无需服务器。

## 发布

```bash
git add -A
git commit -m "update profile"
git push
```

推送后 GitHub Actions / Pages 自动构建，约 1 分钟内生效。
