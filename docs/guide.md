
# 使用指南

## 1. 编写 Markdown 文档

在 docs 目录下创建或修改 Markdown 文件。

## 2. 配置 MkDocs

通过 mkdocs.yml 文件设置网站名称、主题和导航菜单。

## 3. 提交代码

使用 Git 将修改提交到 GitHub：

```bash
git add .
git commit -m "Update documentation"
git push origin main
```

## 4. 自动构建与部署

当代码推送到 main 分支后，GitHub Actions 自动执行以下操作：

1. 检出仓库代码。
2. 配置 Python 环境。
3. 安装 MkDocs 及 Material 主题。
4. 构建静态网站。
5. 将生成的网站文件部署到 GitHub Pages。

## 5. 访问文档网站

部署成功后，可通过 GitHub Pages 提供的地址访问网站。
