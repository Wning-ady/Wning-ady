<div align="center">
  <h1>waning</h1>
  <p><strong>把日常摩擦，做成简单、可靠、可恢复的开源工具。</strong></p>
  <p>macOS 效率工具 · Unraid · Docker · 云端同步 · 媒体自动化</p>
  <p>
    <a href="#项目">项目</a> ·
    <a href="#构建方式">构建方式</a> ·
    <a href="https://hub.docker.com/u/waning">Docker Hub</a>
  </p>
</div>

---

我关注那些不大、却会每天反复出现的问题：更快地找到一个应用，只同步真正需要的文件，让容器图标保持整齐，或让失修的插件重新可靠运行。

这些项目从真实使用场景出发，由 AI 深度参与设计与实现，并尽可能提供清楚的文档、自动化测试和安全的恢复路径。

<a id="项目"></a>

## 项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/LaunchPoint">LaunchPoint</a></h3>
      <p>原生 macOS 应用启动器。支持即时搜索、应用整理、自定义网格、触控板手势与个性化背景。</p>
      <p><code>Swift 6</code> · <code>AppKit</code> · <code>SwiftUI</code></p>
      <p><a href="https://github.com/Wning-ady/LaunchPoint">查看项目</a> · <a href="https://github.com/Wning-ady/LaunchPoint/releases">下载</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/unraid-icon-manager">Unraid Icon Manager</a></h3>
      <p>批量管理当前 Unraid Docker 容器与虚拟机图标，支持图库、审计记录和可回滚同步。</p>
      <p><code>TypeScript</code> · <code>Docker</code> · <code>Unraid</code></p>
      <p><a href="https://github.com/Wning-ady/unraid-icon-manager">查看项目</a> · <a href="https://hub.docker.com/r/waning/unraid-icon-manager">Docker</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/OneSync">OneSync</a></h3>
      <p>在 Unraid 上可控地选择并同步 Microsoft OneDrive 文件，使用真实本地副本而非虚拟挂载。</p>
      <p><code>Python</code> · <code>FastAPI</code> · <code>Docker</code></p>
      <p><a href="https://github.com/Wning-ady/OneSync">查看项目</a> · <a href="https://hub.docker.com/r/waning/onesync">Docker</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop">MoviePilot Plugins Repair Shop</a></h3>
      <p>修复和维护 MoviePilot V2 插件，并用面向安全性的回归测试验证关键行为。</p>
      <p><code>Python</code> · <code>Pytest</code> · <code>MoviePilot</code></p>
      <p><a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop">查看项目</a> · <a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop#安装">安装</a></p>
    </td>
  </tr>
</table>

<a id="构建方式"></a>

## 构建方式

```text
先验证，再写入  ·  默认可恢复  ·  文档跟随代码  ·  为真实场景设计
```

- 危险操作需要明确确认，失败时尽量保持原状态。
- 把部署、升级、回滚和排障视为产品体验的一部分。
- 用自动化测试守住关键行为，用清晰文档降低使用门槛。
- AI 参与代码、界面、测试与文档；最终目标始终是解决真实问题。

## 贡献轨迹

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution animation" src="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake.svg">
  </picture>
  <br>
  <sub>持续构建，也为下一次重启做好准备。</sub>
</div>
