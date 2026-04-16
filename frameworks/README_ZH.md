# 框架与运行时

这里聚焦那些把 harness 当成运行时、SDK 或平台来构建的项目，更接近真正可执行的 agent system。

[English](README.md) | [返回首页](../README_ZH.md)

| 序号 | 项目 | GitHub | Stars | 许可 | 侧重点 | 备注 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | OpenHarness | [Repo](https://github.com/HKUDS/OpenHarness) | [![Stars](https://img.shields.io/github/stars/HKUDS/OpenHarness?style=flat-square)](https://github.com/HKUDS/OpenHarness) | MIT | 开放式 agent harness 运行时 | 它是目前最明确把自己定义成 open agent harness 的代表性项目之一。 |
| 2 | deepagents | [Repo](https://github.com/langchain-ai/deepagents) | [![Stars](https://img.shields.io/github/stars/langchain-ai/deepagents?style=flat-square)](https://github.com/langchain-ai/deepagents) | MIT | 基于 LangGraph 的 harness | 把规划、文件系统工具和子代理组合起来，适合长任务链。 |
| 3 | hive | [Repo](https://github.com/aden-hive/hive) | [![Stars](https://img.shields.io/github/stars/aden-hive/hive?style=flat-square)](https://github.com/aden-hive/hive) | Apache-2.0 | 多智能体生产 harness | 更偏生产系统形态，强调多 agent 协作与线上落地。 |
| 4 | Trellis | [Repo](https://github.com/mindfold-ai/Trellis) | [![Stars](https://img.shields.io/github/stars/mindfold-ai/Trellis?style=flat-square)](https://github.com/mindfold-ai/Trellis) | AGPL-3.0 | 通用 agent harness | 它更像一个通用 harness 平台，而不是单一 benchmark 仓库。 |
| 5 | Yuxi | [Repo](https://github.com/xerrors/Yuxi) | [![Stars](https://img.shields.io/github/stars/xerrors/Yuxi?style=flat-square)](https://github.com/xerrors/Yuxi) | MIT | 知识驱动 harness 平台 | 把知识库、知识图谱和 agent runtime 结合得比较紧。 |
| 6 | nexent | [Repo](https://github.com/ModelEngine-Group/nexent) | [![Stars](https://img.shields.io/github/stars/ModelEngine-Group/nexent?style=flat-square)](https://github.com/ModelEngine-Group/nexent) | MIT | 零代码 harness-first 平台 | 强调工具、记忆、编排和控制面的零代码组合。 |
| 7 | revfactory/harness | [Repo](https://github.com/revfactory/harness) | [![Stars](https://img.shields.io/github/stars/revfactory/harness?style=flat-square)](https://github.com/revfactory/harness) | Apache-2.0 | Agent 团队生成 meta-skill | 它把 harness 看成“生成领域化 agent 团队”的方法，思路很特别。 |
| 8 | open-harness | [Repo](https://github.com/MaxGfeller/open-harness) | [![Stars](https://img.shields.io/github/stars/MaxGfeller/open-harness?style=flat-square)](https://github.com/MaxGfeller/open-harness) | MIT | 可组合 Agent SDK | 比大型平台更轻，更像代码优先的 composable SDK。 |
| 9 | auto-harness | [Repo](https://github.com/neosigmaai/auto-harness) | [![Stars](https://img.shields.io/github/stars/neosigmaai/auto-harness?style=flat-square)](https://github.com/neosigmaai/auto-harness) | MIT | 自改进 harness 优化器 | 会围绕失败样本、回归门禁和自动优化来改进 agent harness。 |
| 10 | AutoHarness | [Repo](https://github.com/aiming-lab/AutoHarness) | [![Stars](https://img.shields.io/github/stars/aiming-lab/AutoHarness?style=flat-square)](https://github.com/aiming-lab/AutoHarness) | MIT | 自动化 harness engineering | 项目目标非常直接，就是自动化 AI agent 的 harness engineering。 |
| 11 | Archon | [Repo](https://github.com/coleam00/Archon) | [![Stars](https://img.shields.io/github/stars/coleam00/Archon?style=flat-square)](https://github.com/coleam00/Archon) | MIT | AI coding harness builder | 把 AI coding 流程定义成 YAML workflow，适合把开发过程做成可复用 harness。 |
| 12 | kweaver-core | [Repo](https://github.com/kweaver-ai/kweaver-core) | [![Stars](https://img.shields.io/github/stars/kweaver-ai/kweaver-core?style=flat-square)](https://github.com/kweaver-ai/kweaver-core) | Apache-2.0 | 企业级 harness-first foundation | 更强调受控上下文、策略约束和可验证反馈回路，适合企业决策 agent。 |
| 13 | lacp | [Repo](https://github.com/0xNyk/lacp) | [![Stars](https://img.shields.io/github/stars/0xNyk/lacp?style=flat-square)](https://github.com/0xNyk/lacp) | MIT | 控制面式 agent harness | 本地优先，强调 policy gate、验证循环、分层记忆和可审计执行。 |
| 14 | OpenSpace | [Repo](https://github.com/HKUDS/OpenSpace) | [![Stars](https://img.shields.io/github/stars/HKUDS/OpenSpace?style=flat-square)](https://github.com/HKUDS/OpenSpace) | MIT | 自进化 agent runtime | 更强调低成本、自改进和环境交互，像一个持续演化的 agent runtime。 |
| 15 | nanoclaw | [Repo](https://github.com/qwibitai/nanoclaw) | [![Stars](https://img.shields.io/github/stars/qwibitai/nanoclaw?style=flat-square)](https://github.com/qwibitai/nanoclaw) | MIT | 轻量容器化 agent infrastructure | 把记忆、定时任务和多通讯入口打包进一个更轻量的 agent 基础设施。 |
