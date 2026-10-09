# xjt-skills

团队共用的 Agent Skills 集合，全部取自上游 GitHub 开源仓库的原始版本，未做本地修改。

## 使用方式

**CC Switch**：技能 → ⋯ → 仓库管理 → 仓库 URL 填 `denglei886/xjt-skills`，分支 `main`，技能路径填 `skills`。
**Claude Code / 其他工具**：把需要的技能目录复制到 `~/.claude/skills/`（或对应应用的 skills 目录）即可。

每个技能都是一个含 `SKILL.md` 的独立目录，目录名即技能名。

## 技能清单

| 技能 | 来源仓库 | 上游路径 |
| --- | --- | --- |
| brainstorming | [obra/superpowers](https://github.com/obra/superpowers) | `skills/brainstorming` |
| diagnosing-superpowers | obra/superpowers | `skills/diagnosing-superpowers` |
| dispatching-parallel-agents | obra/superpowers | `skills/dispatching-parallel-agents` |
| executing-plans | obra/superpowers | `skills/executing-plans` |
| finishing-a-development-branch | obra/superpowers | `skills/finishing-a-development-branch` |
| receiving-code-review | obra/superpowers | `skills/receiving-code-review` |
| requesting-code-review | obra/superpowers | `skills/requesting-code-review` |
| subagent-driven-development | obra/superpowers | `skills/subagent-driven-development` |
| systematic-debugging | obra/superpowers | `skills/systematic-debugging` |
| test-driven-development | obra/superpowers | `skills/test-driven-development` |
| using-git-worktrees | obra/superpowers | `skills/using-git-worktrees` |
| using-superpowers | obra/superpowers | `skills/using-superpowers` |
| verification-before-completion | obra/superpowers | `skills/verification-before-completion` |
| writing-plans | obra/superpowers | `skills/writing-plans` |
| writing-skills | obra/superpowers | `skills/writing-skills` |
| openspec-apply-change | [Fission-AI/OpenSpec](https://github.com/Fission-AI/OpenSpec) | `skills/openspec-apply-change` |
| openspec-archive-change | Fission-AI/OpenSpec | `skills/openspec-archive-change` |
| openspec-bulk-archive-change | Fission-AI/OpenSpec | `skills/openspec-bulk-archive-change` |
| openspec-continue-change | Fission-AI/OpenSpec | `skills/openspec-continue-change` |
| openspec-explore | Fission-AI/OpenSpec | `skills/openspec-explore` |
| openspec-ff-change | Fission-AI/OpenSpec | `skills/openspec-ff-change` |
| openspec-new-change | Fission-AI/OpenSpec | `skills/openspec-new-change` |
| openspec-onboard | Fission-AI/OpenSpec | `skills/openspec-onboard` |
| openspec-propose | Fission-AI/OpenSpec | `skills/openspec-propose` |
| openspec-sync-specs | Fission-AI/OpenSpec | `skills/openspec-sync-specs` |
| openspec-update-change | Fission-AI/OpenSpec | `skills/openspec-update-change` |
| openspec-verify-change | Fission-AI/OpenSpec | `skills/openspec-verify-change` |
| create-adaptable-composable | [vuejs-ai/skills](https://github.com/vuejs-ai/skills) | `skills/create-adaptable-composable` |
| vue-best-practices | vuejs-ai/skills | `skills/vue-best-practices` |
| vue-debug-guides | vuejs-ai/skills | `skills/vue-debug-guides` |
| vue-jsx-best-practices | vuejs-ai/skills | `skills/vue-jsx-best-practices` |
| vue-options-api-best-practices | vuejs-ai/skills | `skills/vue-options-api-best-practices` |
| vue-pinia-best-practices | vuejs-ai/skills | `skills/vue-pinia-best-practices` |
| vue-router-best-practices | vuejs-ai/skills | `skills/vue-router-best-practices` |
| vue-testing-best-practices | vuejs-ai/skills | `skills/vue-testing-best-practices` |
| grill-me | [mattpocock/skills](https://github.com/mattpocock/skills) | `skills/productivity/grill-me` |
| code-review | mattpocock/skills | `skills/engineering/code-review` |
| frontend-design | [anthropics/skills](https://github.com/anthropics/skills) | `skills/frontend-design` |

共 38 个技能：superpowers 15、openspec 12、vuejs-ai 8、mattpocock 2、anthropics 1。

## 许可

各上游仓库的原始 LICENSE 见 `licenses/`。技能版权归各自作者所有，本仓库仅做汇集分发。
