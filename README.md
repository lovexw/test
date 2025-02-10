# 静态页面示例

这是一个简单的静态页面示例项目，用于演示如何使用 GitHub 和 Cloudflare Pages 进行自动化部署。

## 部署步骤

1. 将代码推送到 GitHub 仓库
2. 在 Cloudflare Pages 中创建新项目
3. 选择对应的 GitHub 仓库
4. 设置部署配置：
   - 构建命令：不需要
   - 输出目录：/
   - 环境变量：无需设置

## 自动部署

每次推送代码到 GitHub 主分支时，Cloudflare Pages 都会自动触发新的部署。

## 本地开发

由于是纯静态页面，可以直接在浏览器中打开 index.html 文件进行预览。