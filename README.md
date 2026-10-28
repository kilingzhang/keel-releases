# Keel

适用于 macOS 的浏览器。

此仓库仅维护安装包、版本说明及自动更新文件。产品源码和构建流程保留在维护者本地，不在此仓库发布。

## 下载与安装

[下载 0.2.1 安装包](https://github.com/kilingzhang/keel-releases/releases/download/v0.2.1/Keel-0.2.1-macOS-arm64.dmg) · [查看版本说明](https://github.com/kilingzhang/keel-releases/releases/latest)

当前稳定版为 **0.2.1**，适用于 Apple 芯片 Mac，macOS 14 或更新版本。安装包已完成 Developer ID 签名和 Apple 公证。打开 `.dmg`，将 Keel 拖入“应用程序”再打开。

GitHub 自动显示的 `Source code (zip)` 和 `Source code (tar.gz)` 只包含本仓库的分发说明，不是浏览器安装包。

## 自动更新

支持更新的正式版本会定期检查新版，也可通过“Keel → 检查更新…”手动检查。

发现新版后，点击“下载并安装，完成后重启”。Keel 下载并验证更新，保存浏览数据后退出，安装完成后重新打开。如果网页需要确认离开、下载尚未处理或数据保存失败，Keel 会等待你处理，不会强制退出。

“设置 → 更新”可关闭自动检查。关闭后仍可手动检查。

稳定更新 feed 随正式版公开，应用会自动使用。首次使用请下载安装包；本地开发包使用独立数据目录，不能直接通过此仓库切换为正式版。0.2.0 → 0.2.1 已通过独立副本的安装、自动重启与测试数据保持验证；公开原包的下载及签名另行核对，原样正式包跨公开版本升级尚未实测。

## 版本与文件

每个正式版本提供：

- `Keel-<版本>-macOS-arm64.dmg`：首次安装。
- `Keel-<版本>-macOS-arm64.zip`：自动更新使用的完整应用包。
- `appcast.xml`：带签名的更新索引。
- `SHA256SUMS`：下载文件的校验和。
- `release-notes.md`：本次版本说明。
- `THIRD-PARTY-NOTICES.txt`：该发行版的第三方版权与许可说明。
- `release-manifest.json`：版本、制品大小、校验和及公证记录。

第三方版权与许可说明随安装包及各版本的 `THIRD-PARTY-NOTICES.txt` 提供。
