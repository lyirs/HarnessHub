# 工作流与执行模式

这里收录的是更偏“怎么组织执行流程与日常协作”的 harness 项目，不再把技能包和配置仓库混在这里。

[English](README.md) | [返回首页](../README_ZH.md)

| 序号 | 项目 | GitHub | Stars | 许可 | 侧重点 | 备注 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | deer-flow | [Repo](https://github.com/bytedance/deer-flow) | [![Stars](https://img.shields.io/github/stars/bytedance/deer-flow?style=flat-square)](https://github.com/bytedance/deer-flow) | MIT | 长时程 superagent harness | 强调研究、编码、创作和子代理协作，适合长链路任务。 |
| 2 | learn-claude-code | [Repo](https://github.com/shareAI-lab/learn-claude-code) | [![Stars](https://img.shields.io/github/stars/shareAI-lab/learn-claude-code?style=flat-square)](https://github.com/shareAI-lab/learn-claude-code) | MIT | 极简 Bash harness | 如果你想从第一性原理理解 claude-code-like harness，它很有帮助。 |
| 3 | spec-kit | [Repo](https://github.com/github/spec-kit) | [![Stars](https://img.shields.io/github/stars/github/spec-kit?style=flat-square)](https://github.com/github/spec-kit) | MIT | Spec-driven development 工作流工具包 | 它把规划、规格和可预测交付串成一套可复用的软件工程工作流。 |
| 4 | CLI-Anything | [Repo](https://github.com/HKUDS/CLI-Anything) | [![Stars](https://img.shields.io/github/stars/HKUDS/CLI-Anything?style=flat-square)](https://github.com/HKUDS/CLI-Anything) | Apache-2.0 | Agent-native CLI 体系 | 它强调把普通软件工具改造成 agent 更容易调用的 CLI 形态。 |
| 5 | claude-code-harness | [Repo](https://github.com/Chachamaru127/claude-code-harness) | [![Stars](https://img.shields.io/github/stars/Chachamaru127/claude-code-harness?style=flat-square)](https://github.com/Chachamaru127/claude-code-harness) | MIT | Plan-Work-Review 开发 harness | 通过明确的 Plan -> Work -> Review 循环来组织编码任务。 |
| 6 | safe-agentic-workflow | [Repo](https://github.com/bybren-llc/safe-agentic-workflow) | [![Stars](https://img.shields.io/github/stars/bybren-llc/safe-agentic-workflow?style=flat-square)](https://github.com/bybren-llc/safe-agentic-workflow) | MIT | SAFe 风格工作流 harness | 把可重复的多 agent 工作流结构扩展到软件之外的团队流程中。 |
| 7 | oh-my-agent | [Repo](https://github.com/first-fluke/oh-my-agent) | [![Stars](https://img.shields.io/github/stars/first-fluke/oh-my-agent?style=flat-square)](https://github.com/first-fluke/oh-my-agent) | MIT | 可移植多智能体 harness | 把前端、后端、QA 等角色拆成专门 agent，并适配多种 AI IDE / CLI。 |
| 8 | metaswarm | [Repo](https://github.com/dsifry/metaswarm) | [![Stars](https://img.shields.io/github/stars/dsifry/metaswarm?style=flat-square)](https://github.com/dsifry/metaswarm) | MIT | 自增强多智能体 SDLC 编排 | 它把 spec-driven 流程、递归编排、评审闸门和 git-native 知识库揉成一套执行系统。 |
| 9 | AutoAgent | [Repo](https://github.com/kevinrgu/autoagent) | [![Stars](https://img.shields.io/github/stars/kevinrgu/autoagent?style=flat-square)](https://github.com/kevinrgu/autoagent) | Unknown | 自主演化 harness | 让 agent 自己迭代 prompt、工具和配置，更像 overnight harness 优化器。 |
| 10 | OpenHarness-For-Codex | [Repo](https://github.com/thu-nmrc/OpenHarness-For-Codex) | [![Stars](https://img.shields.io/github/stars/thu-nmrc/OpenHarness-For-Codex?style=flat-square)](https://github.com/thu-nmrc/OpenHarness-For-Codex) | Unknown | 面向 Codex 的 OpenHarness 变体 | 针对 AI 驱动软件开发场景裁剪的 OpenHarness 分支。 |
| 11 | symphony | [Repo](https://github.com/openai/symphony) | [![Stars](https://img.shields.io/github/stars/openai/symphony?style=flat-square)](https://github.com/openai/symphony) | Apache-2.0 | 团队级 autonomous implementation workflow | 把项目工作切成隔离的 autonomous runs，更像团队级实现编排器。 |
| 12 | oh-my-claudecode | [Repo](https://github.com/Yeachan-Heo/oh-my-claudecode) | [![Stars](https://img.shields.io/github/stars/Yeachan-Heo/oh-my-claudecode?style=flat-square)](https://github.com/Yeachan-Heo/oh-my-claudecode) | MIT | 团队优先多智能体编排 | 更强调团队协作、角色拆分和 Claude Code 的多 agent 组织方式。 |

- 技能包、设置模板和可复用配置仓库现已单独拆分到 [Skills & Configs](../skills-configs/README_ZH.md)。
