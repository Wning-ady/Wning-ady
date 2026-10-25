<div align="center">
  <h1>waning</h1>
  <p><strong>从日常需求出发，用 AI 把想法做成工具。</strong></p>
  <p>macOS 效率工具 · Unraid 自托管 · OneDrive 同步 · 媒体自动化</p>
  <p>
    <a href="#项目">项目</a> ·
    <a href="#构建方式">构建方式</a> ·
    <a href="#反馈与参与">反馈与参与</a> ·
    <a href="https://hub.docker.com/u/waning">Docker Hub</a>
  </p>
</div>

---

你好，我是 **waning**。我关注那些不大、却会每天反复出现的问题：更快地找到应用，只同步需要的文件，让容器图标保持整齐，或修好影响媒体库使用的插件。

我不会编程，这些项目由我提出需求、在日常使用中验证，再借助 AI 完成代码、界面、测试和文档。项目持续迭代，使用前请查看各仓库的安装说明与当前限制。

<a id="项目"></a>

## 项目

| 你想解决的问题 | 对应工具 |
| --- | --- |
| 在 Mac 上快速搜索、启动和整理应用 | [LaunchPoint](https://github.com/Wning-ady/LaunchPoint) |
| 为 Unraid 容器和虚拟机管理图标 | [Unraid Icon Manager](https://github.com/Wning-ady/unraid-icon-manager) |
| 将选定的 OneDrive 文件夹同步到 Unraid | [OneSync](https://github.com/Wning-ady/OneSync) |
| 修复 MoviePilot 媒体刮削与文件清理行为 | [MoviePilot Plugins Repair Shop](https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop) |

### 项目详情

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/LaunchPoint">LaunchPoint</a></h3>
      <p>原生 macOS 应用启动器。支持拼音搜索、拖拽与文件夹整理、收藏、自定义网格和触控板手势，内置更新检查。</p>
      <p><sub>macOS 14+ · Apple Silicon / Intel · Beta，安装包尚未公证</sub></p>
      <p><code>Swift 6</code> · <code>AppKit</code> · <code>SwiftUI</code></p>
      <p><a href="https://github.com/Wning-ady/LaunchPoint">查看项目</a> · <a href="https://github.com/Wning-ady/LaunchPoint/releases">下载</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/unraid-icon-manager">Unraid Icon Manager</a></h3>
      <p>为当前部署的 Unraid 容器批量管理图标，支持 Compose Manager、图标与壁纸图库、审计回滚，以及可选的虚拟机图标管理。</p>
      <p><sub>Unraid · 自托管 Web 界面 · 仅限可信局域网</sub></p>
      <p><code>TypeScript</code> · <code>Docker</code> · <code>Unraid</code></p>
      <p><a href="https://github.com/Wning-ady/unraid-icon-manager">查看项目</a> · <a href="https://hub.docker.com/r/waning/unraid-icon-manager">Docker</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/OneSync">OneSync</a></h3>
      <p>通过目录树选择 OneDrive 文件夹，在 Unraid 保存真实本地副本。支持手动同步与受控重同步，先预演再调整同步范围。</p>
      <p><sub>Unraid / Docker · Microsoft 设备代码授权</sub></p>
      <p><code>Python</code> · <code>FastAPI</code> · <code>Docker</code></p>
      <p><a href="https://github.com/Wning-ady/OneSync">查看项目</a> · <a href="https://hub.docker.com/r/waning/onesync">Docker</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Wning-ady/MoviePilot-Plugins-repair-shop">MoviePilot Plugins Repair Shop</a></h3>
      <p>维护 MoviePilot V2/V3 独立插件：媒体库刮削（魔改版）与清理媒体文件（修复版），重点验证元数据写入和删除联动。</p>
      <p><sub>V2 / V3 独立实现 · 小范围验证后再启用</sub></p>
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

<a id="反馈与参与"></a>

## 反馈与参与

欢迎在对应项目的 **Issues** 提交问题或建议。附上版本、运行环境、复现步骤和预期结果，能更快定位问题；日志和截图请先移除 Token、Cookie、账号等敏感信息。

如果工具对你有帮助，欢迎 Star、分享使用经验，或提交 Pull Request。

## 贡献轨迹

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake.svg">
    <img alt="waning 的 GitHub 贡献轨迹动画" src="https://raw.githubusercontent.com/Wning-ady/Wning-ady/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
  <br>
  <sub>持续构建，也为下一次重启做好准备。</sub>
</div>
