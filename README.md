# GoMind Releases

Official release artifacts for [GoMind](https://gomind.app), including installers, portable packages, and platform builds when they are available.

## GoMind 是什么？

GoMind 是一个跨平台的可视化思维工作台。它把思维导图、知识整理、富文本笔记和内容导出放在同一个可编辑空间中，适合整理想法、学习资料、研究内容、会议记录、产品规划和工作流程。

GoMind 的核心特点：

- 用节点和多种布局组织复杂信息；
- 在节点中添加 Markdown、HTML、代码、Mermaid、LaTeX、图片和链接；
- 导入 XMind、FreeMind、Markdown、YAML、OPML 和纯文本；
- 导出 PNG、JPG、SVG、PDF、Markdown 和 OPML；
- 支持 Windows、macOS、Linux、iOS、Android 和 Web；
- 可选连接本机 AI / MCP，让兼容的 AI 工具读取和整理当前导图。

## 如何使用发布版本

1. 打开 [Releases](https://github.com/gomindApp/gomind-releases/releases) 页面。
2. 选择需要的版本。标记为 **Latest** 的版本是当前推荐的稳定版本。
3. 在该版本的 **Assets** 中选择与你的平台和用途匹配的文件。
4. Windows 普通用户优先选择 Installer；需要免安装运行时选择 Portable ZIP（如果该版本提供）。
5. 下载后按照发布说明安装或解压运行。

也可以直接访问：

- [GoMind 官网](https://gomind.app)
- [下载页面](https://gomind.app/download.html)
- [在线应用](https://gomind.app/app/)
- [用户指南](https://gomind.app/user-guide/en/)
- [中文用户指南](https://gomind.app/user-guide/zh-CN/)

## 发布文件说明

每个版本只展示实际上传并可用的文件。某个平台或格式没有提供时，不会放置指向其他文件的虚假下载链接。

| 类型 | 适用场景 |
| --- | --- |
| Installer | Windows 普通安装，适合大多数用户 |
| Portable ZIP | Windows 免安装运行；仅在版本明确提供时使用 |
| macOS / Linux / Mobile builds | 对应平台的安装包或构建产物；以版本 Assets 为准 |
| Checksums | 用于核对下载文件完整性；仅在版本提供校验文件时使用 |
| Cloudflare R2 mirror | 可选镜像；只有镜像实际可用时才会出现在下载页 |

MSIX 或其他签名相关格式只有在能够提供对应构建和签名时才会发布。没有提供的格式不会被标记为可下载。

## 版本与下载页

- GitHub Releases 是本仓库的版本文件来源。
- 官网下载页展示当前可用的安装文件和镜像状态。
- “Latest” 只表示当前推荐版本，不代表所有平台和格式都一定存在。
- 版本说明、文件名、大小和 SHA-256 以对应 Release 的实际内容为准。

## 安全与完整性

只从 GoMind 官网或本仓库的 GitHub Releases 下载。下载后如 Release 提供 SHA-256 校验值，请核对文件摘要；如果文件名、大小或摘要与 Release 信息不一致，请不要运行，并通过项目渠道反馈。

## English

GoMind is a cross-platform visual workspace for mind mapping and knowledge organization. It combines an editable canvas, rich node notes, import/export workflows, and optional local AI/MCP integrations.

Use the [GitHub Releases](https://github.com/gomindApp/gomind-releases/releases) page to choose a version and download an artifact from that release. Windows users should normally choose the Installer; choose Portable ZIP only when it is present. Other platforms and formats are published only when the corresponding artifact is available.

For product information and documentation, visit the [GoMind website](https://gomind.app), the [download page](https://gomind.app/download.html), or the [user guide](https://gomind.app/user-guide/en/).

## License

GoMind is proprietary software. The release files and product are provided under the applicable GoMind terms.
