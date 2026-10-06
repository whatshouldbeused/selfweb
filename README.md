# 阿舟的个人网站

纯 HTML + CSS + JS，无框架、无构建、无外部依赖，双击 `index.html` 即可预览。

## 文件

- `index.html`：全部内容
- `style.css`：样式（颜色变量在文件开头 `:root`，改 `--acc` 即可换主题色）
- `script.js`：主题切换、导航高亮、滚动淡入、页脚年份

## 修改内容

打开 `index.html`，搜索 **「占位」** 或 **【占位】**，逐个替换：

1. 社交链接：把 `your-username`、`you@example.com` 换成你的
2. 关于我：改成你自己的介绍
3. 项目：每个 `<article class="card">` 是一个项目，改标题、描述、标签和链接 `href`，复制或删除即可增减
4. 技能：增删 `<li>`
5. 部署后把 `og:url` 改成你的网址

本地预览（可选）：`python3 -m http.server`，然后打开 http://localhost:8000

## 免费部署

**GitHub Pages**：新建仓库 → 上传本文件夹里的所有文件 → Settings → Pages → Source 选 `main` 分支根目录 → 保存，几分钟后访问 `https://用户名.github.io/仓库名/`。

**Netlify**：打开 https://app.netlify.com/drop ，把整个文件夹拖进去，立即获得网址。

**Vercel**：登录 https://vercel.com → Add New → Project，导入 GitHub 仓库（框架选 Other，无需构建命令）；或安装 CLI 后在文件夹里运行 `npx vercel`。
