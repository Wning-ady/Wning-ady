<div align="center">
  <h1>waning</h1>
  <p><strong>把自托管的日常问题，做成可靠工具。</strong></p>
  <p>Reliable tools for the self-hosted life.</p>
  <p>
    <a href="https://hub.docker.com/r/waning/unraid-icon-manager"><img src="https://img.shields.io/docker/pulls/waning/unraid-icon-manager?style=flat-square&label=Icon%20Manager%20pulls" alt="Unraid Icon Manager Docker pulls"></a>
    <a href="https://hub.docker.com/r/waning/onesync"><img src="https://img.shields.io/docker/pulls/waning/onesync?style=flat-square&label=OneSync%20pulls" alt="OneSync Docker pulls"></a>
    <a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/actions/workflows/validate.yml"><img src="https://img.shields.io/github/actions/workflow/status/Wning-ady/MoviePilot-Plugins-repair-shop/validate.yml?style=flat-square&label=MoviePilot%20tests" alt="MoviePilot plugin validation status"></a>
  </p>
</div>

## 现在在做 / Now

`Unraid` · `Media automation` · `Cloud sync` · `Docker`

用 AI 协作做小而可靠的自托管工具，重视清晰默认值、可观察运行和恢复路径。

## 核心项目 / Work

### [MoviePilot Plugins Repair Shop](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop)

为 MoviePilot V2 提供经过修复与回归测试的插件。

`Python` · `Pytest` · [安装](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop#安装) · [验证](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop/actions/workflows/validate.yml)

### [OneSync](https://github.com/Wning-ady/OneSync)

在 Unraid 上选择性同步 Microsoft OneDrive，支持目录选取和受控重同步。

`Python` · `FastAPI` · `Docker` · [部署](https://github.com/Wning-ady/OneSync#快速部署) · [Docker Hub](https://hub.docker.com/r/waning/onesync)

### [Unraid Icon Manager](https://github.com/Wning-ady/unraid-icon-manager)

为当前 Docker 容器管理图标，带审计记录与可回滚同步。

`TypeScript` · `Docker` · [安装](https://github.com/Wning-ady/unraid-icon-manager#在-unraid-安装) · [Docker Hub](https://hub.docker.com/r/waning/unraid-icon-manager)

## 做事方式 / Principles

- **先验证，再写入**：预演与回归测试先于实际变更。
- **默认可恢复**：关键操作保留日志、备份或回滚路径。
- **文档跟随代码**：部署、升级与故障恢复写进项目本身。

<div align="center">
  <sub>Open source · built for the next reboot</sub>
</div>
