<div align="center">
  <img src="https://raw.githubusercontent.com/Wning-ady/OneSync/main/docs/assets/onesync-logo.png" width="124" alt="OneSync logo">
  <h1>waning</h1>
  <p><strong>把真实需求做成可部署、可恢复的自托管工具。</strong></p>
  <p>Building dependable self-hosted tools for Unraid, cloud storage, and home labs.</p>
  <p>
    <a href="https://github.com/Wning-ady/OneSync"><img src="https://img.shields.io/github/stars/Wning-ady/OneSync?style=flat-square&label=OneSync%20stars" alt="OneSync stars"></a>
    <a href="https://github.com/Wning-ady/OneSync/actions"><img src="https://img.shields.io/github/actions/workflow/status/Wning-ady/OneSync/publish.yml?style=flat-square&label=build" alt="OneSync build status"></a>
    <a href="https://hub.docker.com/r/waning/onesync"><img src="https://img.shields.io/docker/pulls/waning/onesync?style=flat-square&label=OneSync%20pulls" alt="OneSync Docker pulls"></a>
    <a href="https://github.com/Wning-ady/unraid-icon-manager"><img src="https://img.shields.io/github/stars/Wning-ady/unraid-icon-manager?style=flat-square&label=Icon%20Manager%20stars" alt="Unraid Icon Manager stars"></a>
  </p>
  <p>
    <a href="#精选项目">精选项目</a> ·
    <a href="#技术方向">技术方向</a> ·
    <a href="#联系与反馈">联系与反馈</a>
  </p>
</div>

---

## 我在做什么

我从家用服务器上的真实痛点出发，用 AI 协作把想法做成**能部署、能观察、能恢复**的开源工具。现在主要围绕 Unraid、云端文件和 Docker 工作流，偏好小而明确的服务、谨慎的默认值，以及可以直接复制的文档。

I turn real homelab pain points into small, deployable open-source tools with AI. My current focus is Unraid, cloud files, and Docker workflows with careful defaults and recovery paths.

## 精选项目

| 项目 | 解决什么问题 | 技术与入口 |
| --- | --- | --- |
| [OneSync](https://github.com/Wning-ady/OneSync) | 在 Unraid 上可控、选择性同步 Microsoft OneDrive；支持目录树选取、双设备代码授权和 dry-run 重同步。 | Python · FastAPI · Docker · [部署文档](https://github.com/Wning-ady/OneSync#快速部署) |
| [Unraid Icon Manager](https://github.com/Wning-ady/unraid-icon-manager) | 为当前已部署的 Unraid Docker 容器管理图标，支持图库、审计记录和可回滚同步。 | TypeScript · Docker · [安装说明](https://github.com/Wning-ady/unraid-icon-manager#在-unraid-安装) |

## 技术方向

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Microsoft%20Graph-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Graph">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

- **Self-hosted first**：优先支持 Docker / Compose 和可信局域网部署。
- **可恢复优先**：修改前预览，关键操作保留日志、备份或 dry-run 路径。
- **文档跟着功能走**：安装、安全边界、升级和故障恢复都写进项目 README。

## 联系与反馈

最有帮助的交流方式是直接在项目里留下可复现的 Issue 或建议：

- [OneSync Issues](https://github.com/Wning-ady/OneSync/issues)
- [Unraid Icon Manager Issues](https://github.com/Wning-ady/unraid-icon-manager/issues)

欢迎带上运行环境、复现步骤和日志片段；请先移除令牌、账号和其他敏感信息。

<div align="center">
  <sub>Built around real homelab needs · documented for the next reboot</sub>
</div>
