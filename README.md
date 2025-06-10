# 静态个人博客部署说明

## 第一步：注册 GitHub 账号

1. 访问 https://github.com
2. 注册一个新账号，登录后点击右上角 "+" → New repository
3. 仓库命名如：`personal-blog`
4. 勾选 Initialize with README

## 第二步：开发博客网站

使用 HTML + CSS 创建网站（已在本目录中完成 `index.html`、`about.html`、`style.css`）

## 第三步：注册云服务并部署网站

以腾讯云轻量应用服务器为例（支持华为云/阿里云相似操作）：

1. 访问 https://cloud.tencent.com 注册账号
2. 获取免费轻量服务器（一般为 1 核 1G 25GB SSD）
3. 创建实例并设置公网 IP 和开放 80 端口
4. 使用 SFTP 工具（如 FileZilla）连接服务器，将网站文件上传到 `/var/www/html` 或 `/usr/share/nginx/html`
5. 使用浏览器访问你的公网 IP，即可访问网站主页！

## 第四步：上传项目到 GitHub

1. 在本地使用 Git 初始化项目目录：

```bash
git init
git remote add origin https://github.com/你的用户名/personal-blog.git
git add .
git commit -m "init blog site"
git push -u origin master
```

## ✅ 项目结构：

```
blog-site/
├── index.html
├── about.html
├── style.css
└── README.md
```

## 📢 效果展示：

通过浏览器访问：https://monumental-sundae-9aa984.netlify.app/

---

欢迎改进博客页面，添加更多内容，如：文章列表、分类页、留言板等。
