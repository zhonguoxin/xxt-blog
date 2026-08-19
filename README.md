# xxt-blog

基于 [Hugo](https://gohugo.io/) + [GitHub Pages](https://pages.github.com/) 的个人博客。

- 主题：[PaperMod](https://github.com/adityatelange/hugo-PaperMod) (v8.0)
- 部署：GitHub Actions 自动部署

## 目录结构

- `content/posts/` — 文章（Markdown）
- `config.toml` — 站点配置
- `archetypes/default.md` — 新文章模板
- `.github/workflows/deploy.yml` — 自动部署工作流

## 发布文章

1. 在 `content/posts/` 下新建 `.md` 文件，frontmatter 需包含 `title` / `date` / `tags` / `author` 四个字段；
2. 提交 Pull Request；
3. 合并到 `main` 分支后自动部署。

## 本地预览

```bash
hugo server -D
```
