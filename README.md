> ⚠️ **本仓库已废弃**：内容已并入 [agent-deploy](https://github.com/hpsks416/agent-deploy) 的 skills/agent-workflow-orchestration/ 子目录，请以 agent-deploy 为准。本仓库保留仅供历史归档。

# agent-workflow-orchestration

一套 agent 编排自身工作的元工作流：把复杂请求拆解、并行、验证、收敛，并管理长任务与技能。分两层——**通用工作法**（跨工具成立的方法论内核，主体）与 **DSH 工具落地层**（四维度可操作用法）。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

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

