# 静态网站部署说明

## 第一步：注册 GitHub 账号

1. 访问 https://github.com
2. 注册一个新账号，登录后点击右上角 "+" → New repository
3. 仓库命名如：`yukii-sylus`
4. 勾选 Initialize with README

## 第二步：开发网站

使用 HTML + CSS 创建网站（已在本目录中完成 `index.html`、`about.html`、`style.css`）

## 第三步：注册云服务并部署网站

以腾讯云轻量应用服务器为例：

1. 访问 https://cloud.tencent.com 注册账号
2. 获取免费轻量服务器（一般为 1 核 1G 25GB SSD）
3. 创建实例并设置公网 IP （49.234.26.70）和开放 80 端口
4.使用浏览器访问你的公网 IP，即可访问网站主页！


## ✅ 项目结构：

```
site/
├── index.html
├── about.html
├── style.css
└── README.md
```

## 📢 效果展示：

通过浏览器访问：http://49.234.26.70/

---

欢迎改进网站页面，添加更多内容。
