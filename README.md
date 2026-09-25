# agent-workflow-orchestration

一套 agent 编排自身工作的元工作流：把复杂请求拆解、并行、验证、收敛，并管理长任务与技能。分两层——**通用工作法**（跨工具成立的方法论内核，主体）与 **DSH 工具落地层**（四维度可操作用法）。

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 需要编排复杂多步任务、管理长任务与多智能体协作的 agent

## 目录结构

    agent-workflow-orchestration/
    ├── SKILL.md    技能入口与工作流
    ├── evals.yaml

## 安装

    # GitHub
    git clone https://github.com/hpsks416/agent-workflow-orchestration.git "$env:USERPROFILE\.dsh\skills\agent-workflow-orchestration"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/agent-workflow-orchestration.git "$env:USERPROFILE\.dsh\skills\agent-workflow-orchestration"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
