[English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)

# ChatGPT Outline 社区版：为 ChatGPT 长对话生成可点击目录

轻量级、源码可查看的 Chrome 扩展。为 ChatGPT 对话生成目录，点击问题直接定位，不必反复滚动寻找旧回答。

![ChatGPT Outline community demo](./jump-ezgif.com-crop.gif)

**[前往 Chrome 商店安装 Outlinesave](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[在线体验 HTML 导出效果](https://wisteriasoftware.uk/demo)**

> **注意：** 社区演示版仅前 15 条目录可跳转。下文 Outlinesave 功能属于单独发布的正式版扩展。

## 为什么需要 ChatGPT 对话目录？

长对话积累几十甚至几百轮后，找回以前的问题、技术方案和关键回答会越来越困难。目录让对话更容易导航和回顾。

## 社区版包含什么？

- 为 ChatGPT 对话生成可点击目录
- 对话增长时自动刷新目录
- 支持左右侧边栏位置切换
- 演示版限制：只有前 15 条目录可以点击跳转

## 需要更完整的功能？了解 Outlinesave

Outlinesave 是持续维护的正式版浏览器扩展，支持 ChatGPT、Gemini、Claude、DeepSeek 的长对话导航、检索、标注和导出。

### 完整两级目录与目录标题检索

用户提问作为一级目录，AI 回答标题作为二级目录。可以搜索问题与标题，并跳转到匹配位置。ChatGPT 超长对话支持逐步加载目录；已测试 400 轮以上的场景，但加载需要时间，实际表现取决于平台。

### 低打扰阅读：折叠、浮动入口、快捷键

根据需要展开侧边栏、收起为紧凑工具栏或小浮动入口，暂时隐藏目录，并调整支持的面板宽度或位置。J/K 可用于目录导航，Esc 可关闭面板；不同 AI 平台的交互略有差异。

### 可搜索、可筛选、适配手机的离线 HTML 知识页

将对话导出为独立的单文件 HTML，保存后可在本地离线打开，也能在手机浏览器阅读。保留目录、全文搜索、书签、四色高亮筛选、备注和标注；支持代码、数学公式及 Mermaid 流程图。阅读已导出的文件不需要重新打开 ChatGPT，也不需要安装扩展。

**[在线体验 HTML 导出效果](https://wisteriasoftware.uk/demo)**

### 四色高亮、备注、书签及其他导出格式

用四色高亮标记重点、添加下划线与备注，收藏有价值的章节，并按条件筛选。还支持 Markdown、JSON 导出。

### 本地优先，无需注册 Outlinesave 账号

对话内容默认在浏览器本地处理，不会上传 AI 对话正文到 Outlinesave 服务器。无需注册 Outlinesave 用户账号。商店正式版包含最小匿名运行统计；主动激活、Google Drive 手动备份或向本地 Inbox 发送内容时会连接相应服务。

### 手动备份到自己的 Google Drive

用户自行决定何时将 Markdown 内容备份到自己的 Google Drive；不是后台自动同步，也不会默认上传聊天内容。

### 配合 Inbox Local 长期管理 AI 知识

Inbox Local 是独立的本地优先知识工作台。Outlinesave 可以向已运行的本地 Inbox 发送 Markdown 或富 HTML 内容；Inbox 提供文件夹、标签、标题与正文搜索、阅读和标注，并支持手动备份与恢复。

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local)

## 社区版与 Outlinesave 正式版对比

| 功能 | 社区演示版 | Outlinesave |
|---|---|---|
| ChatGPT 对话目录 | 支持（仅前 15 条可跳转） | 支持 |
| 两级目录与标题检索 | 不包含 | 支持 |
| 高亮、备注、书签 | 不包含 | 支持 |
| 离线 HTML / Markdown / JSON | 不包含 | 支持 |
| Gemini、Claude、DeepSeek | 不包含 | 支持 |

## 常见问题 FAQ

### ChatGPT 如何生成完整对话目录？

社区版提供轻量目录演示；Outlinesave 正式版提供更完整的两级目录与目录检索。

### 如何搜索很长的 ChatGPT 对话？

Outlinesave 可以搜索在线对话的目录标题；导出为 HTML 后，还能在离线文件内进行全文搜索。

### ChatGPT 能导出成一个离线 HTML 文件吗？

可以。Outlinesave 支持单文件、响应式 HTML 导出，保留目录、搜索、书签、高亮与备注。

### Outlinesave 需要注册账号或上传聊天记录吗？

不需要注册 Outlinesave 账号；对话正文默认本地处理。Google Drive 备份由用户手动触发。

### 如何统一管理多个 AI 对话导出？

可以使用独立的 Inbox Local，将 Markdown 或富 HTML 内容整理到本地知识工作台。

## 本地安装社区演示版

打开 chrome://extensions，开启开发者模式，点击「加载已解压的扩展程序」，选择本仓库文件夹。

## 许可证与源码说明

社区演示版采用仓库 LICENSE 中的自定义许可证，属于源码可查看版本，不是 MIT 或 Apache-2.0 开源授权。品牌和商业权利请参阅 NOTICE。

**[前往 Chrome 商店安装 Outlinesave](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[在线体验 HTML 导出效果](https://wisteriasoftware.uk/demo)**

[English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)
