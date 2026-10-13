# 陈平安

用可视化工具看清 AI 编码过程与代码改动

[English](README.md) / [简体中文](README.zh-CN.md)

## [Agent Rewind](https://github.com/chenpingan-dev/agent-rewind)

**给 Codex 会话加一个回放键**

回到失败的调用，看输入和结果，找到重复执行的步骤，再和下一次运行对照

[打开会话回放 →](https://chenpingan-dev.github.io/agent-rewind/) · [安装使用](https://github.com/chenpingan-dev/agent-rewind/blob/main/README.zh-CN.md#安装使用) · Python

[![Agent Rewind 会话回放](https://raw.githubusercontent.com/chenpingan-dev/agent-rewind/main/assets/screenshot.zh-CN.png)](https://chenpingan-dev.github.io/agent-rewind/)

## [Patch Orbit](https://github.com/chenpingan-dev/patch-orbit)

**看清一处 Go 改动，连着哪些包**

从 Git 改动出发，沿 import 链查看关联包，每条连线都有文件和行号依据，再把复查清单带进代码评审

[打开依赖地图 →](https://chenpingan-dev.github.io/patch-orbit/) · [下载工具](https://github.com/chenpingan-dev/patch-orbit/releases) · Go

[![Patch Orbit 依赖地图](https://raw.githubusercontent.com/chenpingan-dev/patch-orbit/main/assets/screenshot.zh-CN.png)](https://chenpingan-dev.github.io/patch-orbit/)

两款工具在本地分析，可保存单文件离线报告，在线页面使用明确标注的合成数据，支持中英文切换

<details>
<summary>其他工具</summary>

- [JSON Lens](https://github.com/chenpingan-dev/json-lens)：浏览 JSON 结构、指针与差异 · [打开工作台](https://chenpingan-dev.github.io/json-lens/)
- [Flow Atlas](https://github.com/chenpingan-dev/flow-atlas)：规划任务依赖、关键路径与排期 · [打开规划器](https://chenpingan-dev.github.io/flow-atlas/)
- [Task Weaver](https://github.com/chenpingan-dev/task-weaver)：按依赖执行 Java 任务并处理失败传播 · [运行任务编排](https://github.com/chenpingan-dev/task-weaver#run-a-workflow)

</details>

个人独立项目 · MIT · AI 辅助开发
