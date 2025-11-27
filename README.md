# LeetCode 评论数排行榜

## 数据来源

`[`data.json`](data.json)` 中的数据通过以下工具全量爬取获得：

[LeetCode 讨论数全量爬取工具 (幂等 + 本地缓存版)](https://gist.github.com/CHENJIAMIAN/155a7f8a9499e5bf65a046c1c5054870)

该工具支持幂等爬取和本地缓存，确保数据可靠性和效率。

## 文件说明

- [`data.json`](data.json): LeetCode 问题讨论数原始数据（JSON 格式）。
- [`LeetCode-讨论数-Top-排行榜.html`](LeetCode-讨论数-Top-排行榜.html): 基于 data.json 生成的 Top 排行榜 HTML 文件，可直接在浏览器中打开查看。

## 使用方法

1. 运行爬取工具获取最新的 [`data.json`](data.json)。
2. 打开 [`LeetCode-讨论数-Top-排行榜.html`](LeetCode-讨论数-Top-排行榜.html) 查看排行榜。

## 许可证

本项目采用 [MIT License](LICENSE)，详见 [LICENSE](LICENSE) 文件。

## GitHub Pages 部署

这是一个静态网页项目，可轻松部署到 GitHub Pages：

1. 将代码推送到 GitHub 仓库的 `main` 分支。
2. 进入仓库 **Settings > Pages**。
3. 设置 **Source** 为 `Deploy from a branch`，选择 `main` 分支和 `/ (root)` 文件夹。
4. 保存后，GitHub 将自动构建并部署，访问 `https://你的用户名.github.io/仓库名` 查看在线排行榜。

**注意**：`data.json` 文件较大，首次推送可能需等待；若超过 GitHub 文件限制，可考虑压缩或使用 Releases 分发数据。

## 贡献指南

欢迎贡献！

1. Fork 本仓库。
2. 创建 `feature/你的功能` 分支。
3. Commit 更改（`git commit -m "feat: 描述"`）。
4. Push 到分支（`git push origin feature/你的功能`）。  
5. 在 GitHub 上创建 Pull Request。

**常见贡献方向**：
- 更新数据爬取工具。
- 优化排行榜 UI/UX。
- 添加新过滤/排序功能。
- 改进数据可视化（图表等）。

感谢所有贡献者！