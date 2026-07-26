<div align="center">
  <h1>waning</h1>
  <p><strong>把自托管里的真实麻烦，做成可部署、可验证、可恢复的工具。</strong></p>
  <p>Turning real homelab problems into dependable, testable tools with AI.</p>
  <p>
    <a href="https://hub.docker.com/r/waning/unraid-icon-manager"><img src="https://img.shields.io/docker/pulls/waning/unraid-icon-manager?style=flat-square&label=Icon%20Manager%20pulls" alt="Unraid Icon Manager Docker pulls"></a>
    <a href="https://hub.docker.com/r/waning/onesync"><img src="https://img.shields.io/docker/pulls/waning/onesync?style=flat-square&label=OneSync%20pulls" alt="OneSync Docker pulls"></a>
    <a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/actions/workflows/validate.yml"><img src="https://img.shields.io/github/actions/workflow/status/Wning-ady/MoviePilot-Plugins-repair-shop/validate.yml?style=flat-square&label=MoviePilot%20tests" alt="MoviePilot plugin validation status"></a>
  </p>
</div>

---

## 我在做什么 / About

我从家庭服务器上的真实痛点出发，用 AI 协作把需求变成**能部署、能观察、能恢复**的开源工具。目前聚焦 Unraid、媒体自动化、云端文件与 Docker 工作流。

I build small, maintainable tools for Unraid, media automation, cloud files, and Docker workflows, with careful defaults and clear recovery paths.

## 精选项目 / Featured Projects

### [Unraid Icon Manager](https://github.com/Wning-ady/unraid-icon-manager)

为当前已部署的 Unraid Docker 容器管理图标，提供持久图库、修改审计和可回滚同步；只重建明确选中的容器或 Compose 服务。

`TypeScript` · `Docker` · `MIT` · [安装文档](https://github.com/Wning-ady/unraid-icon-manager#在-unraid-安装) · [Docker Hub](https://hub.docker.com/r/waning/unraid-icon-manager) · [Releases](https://github.com/Wning-ady/unraid-icon-manager/releases)

### [OneSync](https://github.com/Wning-ady/OneSync)

在 Unraid 上可控、选择性同步 Microsoft OneDrive，支持目录树选取、双设备代码授权，以及先 dry-run 再执行的受控重同步。

`Python` · `FastAPI` · `Docker` · `Microsoft Graph` · [快速部署](https://github.com/Wning-ady/OneSync#快速部署) · [Docker Hub](https://hub.docker.com/r/waning/onesync) · [Issues](https://github.com/Wning-ady/OneSync/issues)

### [MoviePilot Plugins Repair Shop](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop)

发布经过针对性修复和回归测试的 MoviePilot V2 插件。当前包含媒体库刮削增强版与清理媒体文件修复版，使用独立插件 ID，不覆盖上游插件。

`Python` · `Pytest` · `GPL-3.0` · [安装说明](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop#安装) · [自动验证](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/actions/workflows/validate.yml) · [Issues](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/issues)

## 工作原则 / Principles

- **先验证，再写入 / Verify before write**：预演、小范围测试和自动化回归先于实际变更。
- **默认可恢复 / Recoverable by default**：关键操作保留日志、备份、dry-run 或回滚路径。
- **文档属于功能 / Docs are product**：安装、安全边界、升级与故障恢复跟随代码更新。

## 技术方向 / Stack

`Python` · `TypeScript` · `FastAPI` · `Pytest` · `Docker` · `GitHub Actions` · `Microsoft Graph`

## 联系与反馈 / Contact

最有效的反馈方式是直接提交带有运行环境、复现步骤和日志片段的 Issue：

[OneSync](https://github.com/Wning-ady/OneSync/issues) · [Unraid Icon Manager](https://github.com/Wning-ady/unraid-icon-manager/issues) · [MoviePilot Plugins Repair Shop](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/issues)

提交前请移除令牌、账号和其他敏感信息。

<div align="center">
  <sub>Built around real homelab needs · verified before release · documented for the next reboot</sub>
</div>
