# qazdcc.github.io

个人主页，纯静态单文件站点（`index.html`），由 GitHub Pages 直接托管：<https://qazdcc.github.io>

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 修改内容

所有文案、项目与链接都在 `index.html` 内，按区块注释定位即可：

- Hero 自我介绍、数据条：`<section id="home">`
- 关于与技能：`<section id="about">`、`<section id="skills">`
- 项目卡片：`<section id="projects">`（替换标题、描述、标签与 `href`）
- 联系方式：`<section id="contact">`（邮箱、GitHub）
- 配色：`<style>` 开头的 `:root` 变量

## 部署

推送到 `main` 分支后，在仓库 Settings → Pages 中选择 `Deploy from a branch` → `main` / `/ (root)`。
