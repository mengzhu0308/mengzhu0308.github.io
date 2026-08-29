# 朱梦的个人学术博客

这是朱梦（江西财经大学讲师）的个人学术博客站点仓库，基于 [Jekyll](https://jekyllrb.com/) 与 [academicpages](https://github.com/academicpages/academicpages.github.io) 模板构建。

![站点截图](images/homepage.png "站点截图")

**在线地址**：https://mengzhu0308.github.io

## 仓库结构

| 目录 | 内容 |
| ---- | ---- |
| `_posts/` | 博客文章 |
| `_publications/` | 论文发表 |
| `_talks/` | 学术报告 |
| `_teaching/` | 教学信息 |
| `_portfolio/` | 作品集 |
| `_pages/` | 静态页面 |
| `_drafts/` | 草稿 |
| `files/` | PDF 等附件（线上路径为 `/files/...`） |
| `images/` | 图片资源 |

## 本地预览

### Docker（推荐）

已安装 [Docker](https://www.docker.com/) 时，在仓库根目录执行：

```bash
docker compose up
```

启动后访问 `localhost:4000`。

### 原生环境

1. 安装基础依赖（Debian/Ubuntu）：

   ```bash
   sudo apt install ruby-dev ruby-bundler nodejs
   ```

   macOS：

   ```bash
   brew install ruby node
   gem install bundler
   ```

2. 安装 Ruby 依赖：

   ```bash
   bundle install
   ```

   如遇 gem 写入权限错误，先把依赖安装到本地目录再重试：

   ```bash
   bundle config set --local path 'vendor/bundle'
   ```

3. 启动本地服务：

   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

   访问 `localhost:4000`，页面会随文件修改自动重建并刷新。

## 内容更新流程

1. 新内容先放入 `_drafts/` 草稿目录
2. 进入 `_posts/` 之前，在父仓库运行 frontmatter 检查：

   ```bash
   python3 scripts/blog_admin.py lint-posts
   python3 scripts/blog_admin.py lint-publications
   ```

   发布前门禁使用 `--strict`，存在 error 时不发布。
3. 在本仓库提交变更
4. 站点公开发布由父仓库 `project-publish/main.py` 编排，镜像推送到用户页仓库 [mengzhu0308/mengzhu0308.github.io](https://github.com/mengzhu0308/mengzhu0308.github.io)

## 致谢

本站点基于 [academicpages](https://github.com/academicpages/academicpages.github.io) 模板构建（MIT License，详见 `LICENSE`）；该模板由 Stuart Geiger 自 [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) 派生，当前由 Robert Zupko 维护。
