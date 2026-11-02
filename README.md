# 高校科研实验室团队展示网站

清新、简约的高校科研实验室官网模板。纯 HTML、CSS、JavaScript，无需安装依赖，可部署到 GitHub Pages / GitLab Pages。

## 文件
- `index.html`：页面内容
- `style.css`：视觉样式与响应式布局
- `script.js`：移动端导航交互

## 本地预览
直接用浏览器打开 `index.html`。

## 部署到 GitHub Pages
1. 在 GitHub 新建仓库。
2. 上传以上三个文件到仓库根目录。
3. 打开仓库 Settings → Pages。
4. Source 选择 Deploy from a branch。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。
6. 等待 GitHub Pages 发布完成，使用页面显示的网址访问。

## 需要替换的内容
在 `index.html` 中搜索并替换：
- `实验室名称`、`某某大学`、`某某学院`
- 实验室简介、研究方向、导师和成员姓名
- 论文、项目、新闻、邮箱和地址
- `20XX`、`XX+` 等统计数据

## 添加成员照片
将照片放进仓库的 `images` 文件夹，例如 `images/member-01.jpg`。
将相应 `.portrait` 区域中的占位文字替换为：
`<img src="images/member-01.jpg" alt="成员姓名">`
并在 `style.css` 中增加：
`.portrait img{width:100%;height:100%;object-fit:cover;display:block}`
导师照片可使用相同方式。

## 添加更多成员或成果
复制现有的 `<article class="person">...</article>` 或 `.output-list` 中的 article，并修改内容即可。
