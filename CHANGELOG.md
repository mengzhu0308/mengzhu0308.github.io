# Changelog

本文件记录本站点的所有重要变更。

格式遵循 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)，按日期分段（站点随 push 持续部署，不使用版本号）。

## [Unreleased]

（暂无）

## [2026-08-30]

### Changed
- 全站中文化收尾：导航、页面标题、作者侧边栏（name: 朱梦、bio: 江西财经大学讲师、移除 pronouns）、启动页 about.md 中文化并删除 about-me-zh；术语统一（"发表物→论文"等）
- `_config.yml` 的 `url`/`repository` 更新为改名后的仓库；README 发布说明去除已废弃的 project-publish 镜像描述

### Fixed
- `paperurl` 等 `*url` 字段残留的旧绝对 URL 改写为相对路径（仓库改名前置）

## [2026-08-29]

### Added
- 新增 3 篇 publications，页面与 README 中文化

### Changed
- 头像 profile.jpg 替换为 profile.png

### Fixed
- 修正 adamnx 的 arXivurl 笔误

## [2025-03-22]

### Added
- 基于 academicpages 模板初始化个人学术博客站点（早期模板调整与内容搭建提交从略）
