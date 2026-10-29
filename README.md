<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/keel-lockup-dark.png">
    <img src="assets/keel-lockup-light.png" alt="Keel" width="360">
  </picture>
</p>

<p align="center">你的另一个 Arc 浏览器</p>

<p align="center">
  <a href="https://github.com/kilingzhang/keel-releases/releases/latest"><img alt="最新版本" src="https://img.shields.io/github/v/release/kilingzhang/keel-releases?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC&color=173E64"></a>
  <img alt="macOS 14 或更新版本" src="https://img.shields.io/badge/macOS-14%2B-173E64">
  <img alt="Apple 芯片" src="https://img.shields.io/badge/Apple%20%E8%8A%AF%E7%89%87-arm64-173E64">
  <img alt="Developer ID 签名并公证" src="https://img.shields.io/badge/Developer%20ID-%E7%AD%BE%E5%90%8D%E5%B9%B6%E5%85%AC%E8%AF%81-2F7D4F">
</p>

<p align="center">
  <a href="https://github.com/kilingzhang/keel-releases/releases/download/v0.2.1/Keel-0.2.1-macOS-arm64.dmg"><strong>下载 Keel 0.2.1</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/kilingzhang/keel-releases/releases/latest">版本说明</a>
  &nbsp;·&nbsp;
  <a href="INSTALL.md">安装与更新说明</a>
</p>

---

## Keel 是什么

Keel 是一款 macOS 原生浏览器。网页由真正的 Chromium 渲染（通过 CEF），界面用原生 AppKit 搭建，与 Arc、Dia 同构设计。

Arc 将在 2026 年 12 月 22 日停止工作，Keel 是你的第一选择。取 Arc 和 Dia 两边的长处。Arc 的日常习惯可以直接沿用：Space、收藏、固定标签、文件夹、标签组、分屏和 Peek 都有对应入口，侧栏的收起、浮出与调宽也按 Arc 的手感实现。

项目从维护者自己的日常浏览需求出发：先把一个浏览器做到自己天天用、细节顺手，再把验证过的浏览能力沉淀成可复用的 SDK（KeelKit）。

## 现在能做什么

0.2.1 是早期公开版本，已经可以日常使用。

**侧栏与 Space**

- 多个 Space，各自独立的固定标签、收藏、主题、图标与顺序
- 收藏最多 12 项，随侧栏宽度自适应网格
- 固定标签、任意嵌套的文件夹、临时标签与归档
- 侧栏连续调宽，⌘S 收起，移到窗口左边缘临时浮出
- 标签组：从来源页打开的新标签自动归组，也可以手动建组

**标签与网页**

- ⌘T 打开命令栏：切换已有标签，或输入网址、搜索词
- 拖拽排序、多选、行内重命名
- 同窗两到三栏分屏
- Peek 轻量预览窗口，可直接升级为标签
- 页内查找
- Chromium 扩展：可加载本地扩展，也可从 Chrome 应用商店安装、固定与管理

## 路线图

顺序会随实际使用调整，不承诺具体时间。

| 阶段 | 方向 |
| --- | --- |
| 近期 | 历史与下载的完整页面、设置补全、首次使用引导 |
| 接下来 | 按 Arc 补齐侧栏与 Space 的剩余行为，按 Dia 补齐浏览与命令栏细节，站点权限等页面工具 |
| 方向 | 分屏与拖拽的手感打磨、扩展兼容性、iCloud 多设备同步、本地 AI 工作台 |
| 长期 | 把浏览能力整理成可复用的 SDK（KeelKit） |

## 版本号

版本采用「主.次.修订」三段数字，当前 `0.x` 表示仍在早期迭代：

- 修订号：缺陷、隐私或安全修复，保持已有数据与使用方式不变。
- 次版本号：兼容的新能力或较大改进。
- 主版本号：需要迁移的不兼容变化。

已发布的版本和安装包不会被覆盖，修复发布错误时会发一个更高的新版本。

## 这个仓库是什么

这里只放安装包、版本说明和自动更新文件。产品源码和构建流程保留在维护者本地，不在此仓库发布。

下载页面上 GitHub 自动生成的 `Source code (zip)` 和 `Source code (tar.gz)` 只包含本仓库的分发说明，不是浏览器安装包。

问题、建议和兼容性反馈请开 Issue。

## 第三方组件

安装包内含 Chromium、CEF 等第三方组件，版权与许可说明随每个版本的 `THIRD-PARTY-NOTICES.txt` 提供。应用自身的源码不在本仓库，也不随安装包提供。
