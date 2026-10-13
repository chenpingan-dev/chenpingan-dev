<div align="center">

![Replay the session. Trace the change.](assets/profile-banner.svg)

### Tools for debugging AI coding sessions and reviewing Go changes

AI 编码会话复盘 · Go 改动影响分析

[![Python](https://img.shields.io/badge/Python-1b2532?style=flat-square&logo=python)](https://github.com/chenpingan-dev/agent-rewind) [![Go](https://img.shields.io/badge/Go-1b2532?style=flat-square&logo=go)](https://github.com/chenpingan-dev/patch-orbit) [![Java](https://img.shields.io/badge/Java-1b2532?style=flat-square&logo=openjdk)](https://github.com/chenpingan-dev/task-weaver) [![JavaScript](https://img.shields.io/badge/JavaScript-1b2532?style=flat-square&logo=javascript)](https://github.com/chenpingan-dev/json-lens)

</div>

## Working on / 重点项目

| Project / 项目 | Purpose / 用途 | Open / 开始使用 |
| --- | --- | --- |
| **[Agent Rewind](https://github.com/chenpingan-dev/agent-rewind)** · Python | Codex users: replay an exported session, locate repeated/failed tool calls and compare two runs / 从日志定位 AI 编码的重复执行与失败调用 | [打开会话复盘 / Open replay](https://chenpingan-dev.github.io/agent-rewind/) · [安装工具 / Install](https://github.com/chenpingan-dev/agent-rewind#replay-a-session) |
| **[Patch Orbit](https://github.com/chenpingan-dev/patch-orbit)** · Go | Go reviewers: map committed changes to dependent packages, with import files and line numbers / 沿 import 链查看改动涉及哪些 Go 包 | [查看影响地图 / Open map](https://chenpingan-dev.github.io/patch-orbit/) · [下载工具 / Download](https://github.com/chenpingan-dev/patch-orbit/releases) |

Both tools work locally, without a model API key or backend service. Reports are portable HTML files. The online workspaces use clearly labeled synthetic data and support 中文 / English

两款工具都能在本地生成报告，定位依据可以在界面中查看

<details>
<summary>More tools / 其他工具</summary>

| Project / 项目 | Purpose / 用途 | Open / 开始使用 |
| --- | --- | --- |
| [JSON Lens](https://github.com/chenpingan-dev/json-lens) | Explore JSON trees, pointers and structural differences / 浏览 JSON 结构与差异 | [打开 JSON 工作台 / Open workbench](https://chenpingan-dev.github.io/json-lens/) |
| [Flow Atlas](https://github.com/chenpingan-dev/flow-atlas) | Explore dependency paths and worker schedules / 规划任务依赖与排期 | [打开流程规划器 / Open planner](https://chenpingan-dev.github.io/flow-atlas/) |
| [Task Weaver](https://github.com/chenpingan-dev/task-weaver) · Java | Dependency-aware task execution and failure propagation / 按依赖执行 Java 任务 | [运行任务编排 / Run a workflow](https://github.com/chenpingan-dev/task-weaver#run-a-workflow) |

</details>

Independent personal projects · MIT · Synthetic data · AI-assisted development
