<div align="center">

<img src="./assets/images/icon.svg" width="192" height="192" alt="应用图标">

# 哈兔拼图打印

**仓库**：
[![Gitee 主仓库](https://img.shields.io/badge/Gitee-主仓库-C71D23?logo=gitee)][repository-gitee]
[![GitHub 副仓库](https://img.shields.io/badge/GitHub-副仓库-0969da?logo=github)][repository-github]

**平台**：
[![Windows 10+](https://img.shields.io/badge/Windows_10+-0078D4?logo=windows)][release-gitee]
[![ChromeOS](https://img.shields.io/badge/ChromeOS-4285F4?logo=googlechrome&logoColor=f5f5f5)][web-app]
[![Web (PWA)](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=f5f5f5)][web-app]

**语言**：
**中文** |
<small>期待您的翻译！</small>

_该应用程序目前仅支持中文_。

</div>

在一张纸张上自由打印多张图片。

## 特性

- 批量添加图片
- 添加网格，方便裁切
- 支持在线使用
- 支持离线使用
- 支持 PWA

## 软件截图

TODO

## 下载与安装

您可以直接使用 Web 版。该应用为 PWA，如果您的浏览器支持 PWA 功能，您还可以将该应用安装到桌面。

<!-- [![添加到 Chromebook](https://chromeos.dev/badges/zh-CN/secondary.svg)][web-app] -->

- [进入 Web 版][web-app]

您也可以下载本地版。

- [Gitee 发行版][release-gitee]
- [GitHub 发行版][release-github]

## 使用方法

1. 点击图片面板右上角 **添加图片**。
2. 在调整面板中调整参数。
3. 点击 **打印**。
4. 调整打印参数
5. 点击打印对话框内的 **打印** 按钮。

## 兼容性

### Web 版兼容性

本应用需要在支持打印功能的浏览器中打开，建议使用 Chrome v88 或者 Edge v88 更高版本浏览器打开本应用，**不支持在微信、QQ 中使用**。

具体兼容性如下表：

| 操作系统 | 应用（浏览器）                                                                                                                    | 特性 | 详情                                       | 解决方案           |
| -------- | --------------------------------------------------------------------------------------------------------------------------------- | ---- | ------------------------------------------ | ------------------ |
| Android  | 微信、QQ、飞书、360 极速浏览器、夸克、X 浏览器、UC 浏览器、QQ 浏览器、小米浏览器、百度浏览器、百度、搜狗浏览器极速版、OPPO 浏览器 | 打印 | **无法使用打印功能**                       | 更换其他浏览器     |
| Android  | FireFox、Iceraven 等 FireFox 的分支                                                                                               | 打印 | 始终带有页头与页脚，页面方向、布局尺寸错误 | 更换其他浏览器     |
| Android  | Chrome、Edge、Chromium、Cromite、华为浏览器、花瓣浏览器等 Chromium 的分支、荣耀浏览器、Via                                        | 打印 | 页面方向、纸张尺寸错误                     | 打印时手动选择参数 |
| Windows  | FireFox                                                                                                                           | 打印 | 纸张尺寸错误                               | 打印时手动选择参数 |

### Tauri 版兼容性

| 操作系统 | 特性     | 详情                                | 解决方案            |
| -------- | -------- | ----------------------------------- | ------------------- |
| Windows  | 应用启动 | 需要 WebView2 v88.0.0.0 或 更高版本 | 安装或更新 WebView2 |

## 开发与贡献

请参阅[《开发指南》](./docs/dev/README.md)与[《贡献指南》](./docs/CONTRIBUTING.md)。

## 许可证

本项目以 Apache 2.0 许可证授权，详情请参阅 [许可证文件](./LICENSE)。

## 开源声明

请参见 [《开源声明》](./docs/legal/os_notices.md)

## 法律声明

- Chromebook、ChromeOS 和 ChromeOS 徽标是 Google LLC 的商标

---

<div align="center">
版权所有 © 2025-2026 杰西 205
</div>

[repository-gitee]: https://gitee.com/HelloTool/SnapProofPrintHelperForPWA
[repository-github]: https://github.com/HelloTool/SnapProofPrintHelperForPWA
[release-gitee]: https://gitee.com/HelloTool/SnapProofPrintHelperForPWA/releases
[release-github]: https://github.com/HelloTool/SnapProofPrintHelperForPWA/releases
[web-app]: https://hellotool.github.io/SnapProofPrintHelperForPWA/
