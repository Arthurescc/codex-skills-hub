# Codex Skills Hub

<p align="center">
  <img src="assets/hub-icon.svg" alt="Codex Skills Hub icon" width="140" />
</p>

这是一个面向多智能体生态的技能导航仓库，用来集中展示高价值 skill，并让别人更快理解它们的定位、价值和试用方式。

虽然仓库名里还保留了 `Codex`，但这里收录的 skill 实际上并不只服务于 Codex，也适合 OpenClaw、Claude Code、Hermes Agent 等支持 `SKILL.md` 风格工作流的工具。

## 当前收录

### Harness Creator

- 仓库地址：[harness-creator](https://github.com/Arthurescc/harness-creator)
- 适用场景：coding agent、CLI runtime、tool orchestration、MCP assistant、planning/subagent 体系
- 核心价值：把模糊的 “做一个 agent” 收束成真正可实施的架构、实施顺序和安全规则

### Agent Teams Creator

- 仓库地址：[agent-teams-creator](https://github.com/Arthurescc/agent-teams-creator)
- 适用场景：coordinator/worker runtime、共享 task board、多 agent 协作协议、verifier 流程
- 核心价值：明确拆开 task board、mailbox、coordinator、isolation 之间的边界，避免泛化 swarm 设计

### Stitch UI Bridge

- 仓库地址：[stitch-ui-bridge](https://github.com/Arthurescc/stitch-ui-bridge)
- 适用场景：前端 UI 原型生成、Stitch 浏览器自动化、Codex/Claude Code/Cursor 设计链路、原始导出回传
- 核心价值：把已登录的 Stitch 浏览器会话变成一个可复用、本地隐私安全、带阶段感知的设计后端

### Google Design Fusion

- 仓库地址：[google-design-fusion](https://github.com/Arthurescc/google-design-fusion)
- 适用场景：landing page、app shell、设计系统方向、UI audit、anti-AI-slop 设计审查
- 核心价值：把检索驱动的设计判断、风格融合和显式 guardrails 带进前端生成流程

## 为什么要做这个导航页

这些仓库不是普通 prompt 模板，而是经过测试和迭代的技能包。这个导航页的作用是：

- 让人一眼看懂每个 skill 是做什么的
- 快速找到适合自己的技能
- 提高试用和安装意愿
- 为后续继续扩展更多技能留出统一入口

## 开发说明

这些项目均为自研开发，并通过实际测试持续迭代，目标是提升：

- 输出质量
- 架构清晰度
- 工程可实施性
- 事实与推断边界
- 安全与验证深度
- 前端设计链路速度

## 安装方式

### Harness Creator

```bash
git clone https://github.com/Arthurescc/harness-creator \
  "${HOME}/.codex/skills/harness-creator"
```

### Agent Teams Creator

```bash
git clone https://github.com/Arthurescc/agent-teams-creator \
  "${HOME}/.codex/skills/agent-teams-creator"
```

### Stitch UI Bridge

```bash
git clone https://github.com/Arthurescc/stitch-ui-bridge \
  "${HOME}/.codex/skills/stitch-ui-bridge"
```

### Google Design Fusion

```bash
git clone https://github.com/Arthurescc/google-design-fusion \
  "${HOME}/.codex/skills/google-design-fusion"
```

常见目录：

```text
Codex:       ~/.codex/skills/<skill-name>
Claude Code: ~/.claude/skills/<skill-name>
OpenClaw:    ~/.openclaw/skills/<skill-name>
Hermes:      ~/.hermes/skills/<skill-name>
```

Windows 下把 `${HOME}` 换成 `%USERPROFILE%` 即可。

安装后重启或刷新对应智能体，让技能列表刷新。

## 页面文件

这个仓库还带了一个独立的 [index.html](index.html) 落地页，可以本地打开，也可以继续通过 GitHub Pages 作为在线导航页使用。

## 为什么现在要统一口径

你账号里有些仓库最早是按 Codex 视角发布的，但 skill 本身已经具备跨工具复用价值。这个导航页现在明确把它们写成“通用 agent skills”，这样访客不会误以为只能在单一产品里使用。

## License

MIT
