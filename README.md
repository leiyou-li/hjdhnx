

# DRPY-Node 自动同步器

这个项目使用 GitHub Actions 自动同步 [drpy-node](https://github.com/hjdhnx/drpy-node) 仓库的完整内容到根目录。

## 功能

- 每天自动同步 drpy-node 项目的最新完整代码
- 支持手动触发同步
- 完整复制所有文件到根目录

## 配置说明

1. Fork 这个仓库
2. 无需修改配置文件，已经预设为同步 drpy-node 项目
3. 确保 GitHub Actions 已启用（在仓库的 Actions 标签页中确认）

## 使用方法

### 自动同步
- 系统会在每天 UTC 0:00（北京时间 8:00）自动运行同步
- 同步后，所有文件将直接保存在仓库根目录

### 手动同步
1. 进入仓库的 Actions 标签页
2. 选择 "Daily Repository Sync" workflow
3. 点击 "Run workflow" 按钮

## 注意事项

- 每次同步会完全覆盖除了 .git 和 .github 目录外的所有文件
- 如果您对原始文件有修改，请注意备份，因为同步会覆盖这些修改
- 建议定期检查同步状态
