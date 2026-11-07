# TypenTeX

面向平板的 LaTeX 编辑器与编译器：本地编译、即时预览、离线可用。

本仓库是 TypenTeX 的**发布页**，用于发布安装包与版本说明；程序源码不公开
（详见 [LICENSE](LICENSE)）。所用第三方开源组件的版权与许可声明见
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

## 下载

安装包发布在 [Releases](https://github.com/Both-Edward/TypenTeX/releases) 页面，
下载 `TypenTeX-<版本号>.apk` 后直接安装。

- 当前版本：**0.0.2**
- 系统要求：Android 7.0（API 24）及以上，arm64-v8a 设备
- 安装包未经应用商店分发，首次安装需在系统设置中允许「安装未知来源应用」

为确保拿到未被改动的原始安装包，请只从本仓库的 Releases 页面下载。

## 功能

**编辑器**

- LaTeX 语法高亮；软换行时左侧行号与视觉行精确对齐
- 按 `\section` / `\subsection` 等层级折叠代码，折叠状态下保存与编译不会丢内容
- 内置文件树：新建、重命名、复制、删除、拖拽移动；「文件过滤」开关可只显示
  `.tex` / `.bib` / 图片 / PDF 等工程文件，隐藏编译产物与杂物

**编译**

- Tectonic 引擎（内置 XeTeX + Xdvipdfmx + BibTeX），本地编译，本地保存
- 首次编译自动下载所需宏包并缓存，之后可完全离线编译
- 编译日志实时输出，失败时给出具体报错行

**PDF 预览**

- 编译完成后即时预览，支持双指缩放与 25%–200% 快捷缩放
- 页码输入 + 「转到」跳转；自适应宽度 / 自适应高度不改变当前阅读位置
- 记住阅读位置：重新编译或重启应用后，仍停在原来的页码、缩放比例与页内位置

## 第三方组件与开源许可

本软件包含 Tectonic、Flutter、pdfx、flutter_code_editor 等第三方开源组件，
其版权声明与许可证全文见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
（清单与统计）与 [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt)
（各组件许可证原文），也可在应用内「TypenTeX 菜单 → 开源许可」查看。

其中 `flutter_code_editor`（Apache-2.0）与 `pdfx`（MIT）以修改后的版本内置
编译进安装包，修改范围在该文档与应用内许可证页中说明。

各第三方组件的名称、标识与商标归其各自所有者所有，本项目的使用不构成
其所有者对本软件的授权或背书。

## 版权声明

TypenTeX 为专有软件，版权所有，保留一切权利。软件的复制、分发、修改、
反向工程等行为须事先取得著作权人书面许可，完整条款见 [LICENSE](LICENSE)。

如需转载、镜像或再分发安装包，请先通过 [Issue](https://github.com/Both-Edward/TypenTeX/issues)
取得授权。

## 隐私

本地编译，本地保存：编译与文件读写都在设备上完成，无统计埋点、无广告 SDK。
「检查更新」「首次编译下载宏包」以及你主动使用的 AI 助理会联网，明细见 [PRIVACY.md](PRIVACY.md)。

## 问题反馈

使用中遇到问题或有功能建议，请在本仓库提交
[Issue](https://github.com/Both-Edward/TypenTeX/issues)。反馈编译问题时，
附上应用内编译日志的最后若干行会更容易定位。

## 后续计划

- AI 辅助的 LaTeX 编辑与写作（Agent 形态）
- 适配 iPadOS、HarmonyOS Pad、Windows、Linux、macOS
