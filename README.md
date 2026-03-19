# XiaoceDai.github.io

个人主页仓库，使用 GitHub Pages 静态托管。

## 网站地址

- 主地址: [https://daixc.cn](https://daixc.cn)
- GitHub Pages: [https://xiaocedai.github.io](https://xiaocedai.github.io)

## 当前结构

- `index.html`: 主页入口文件
- `CNAME`: 自定义域名配置（当前为 `daixc.cn`）

## 本地预览

这是纯静态页面，可直接双击 `index.html` 打开。  
如果你希望更接近线上效果，建议在仓库根目录启动一个本地静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 发布方式

本仓库默认通过 `main` 分支自动发布到 GitHub Pages。

常用发布步骤：

```bash
git add .
git commit -m "Update homepage"
git push origin main
```

推送后通常等待几十秒到几分钟即可生效。

## 自定义域名说明

- 自定义域名由 `CNAME` 文件控制
- 当前内容为：

```txt
daixc.cn
```

- 域名 DNS 需要正确指向 GitHub Pages（A 记录 / CNAME 记录）

## 后续可扩展

- 增加 `projects`、`about`、`contact` 等页面
- 引入 `assets/` 目录管理图片与样式文件
- 添加 SEO 元信息（Open Graph、favicon、sitemap）