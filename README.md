# ⚡ Tibo Codex 额度重置历史归档库 (Tibo Reset Archive)

> 本仓库由 **[Tibo 额度监控](https://tibo.rowkin.xyz)** 自动化系统驱动。用于实时沉淀 OpenAI Codex 工程负责人 **Thibault Sottiaux (`@thsottiaux`)** 发布的 Codex / ChatGPT Work 额度重置记录。

---

<!-- STATUS:START -->
### ⚡ 最近一次重置记录
- **北京时间**: `2026年10月29日 11:52:07`
- **推文链接**: [https://x.com/thsottiaux](https://x.com/thsottiaux)
- **宣布正文**: > *"【并行架构实测】OpenAI Codex & ChatGPT 额度已由双并发 Job 极速刷新归档！"*
<!-- STATUS:END -->

---

## 📌 归档与通知机制说明

每当监控系统捕获到 `@thsottiaux` 发布包含 `reset` / `quota` / `rate limit` / `codex` / `work` 等关键词的推文时，将通过 GitHub API 触发本仓库的 `repository_dispatch` 事件，自动执行以下两种处理方式：

1. **方式 1：自动在仓库创建 Issue 记录历史（台账归档）**
   - 自动生成带有 `codex-reset`、`automated-alert` 标签的 Issue；
   - 包含重置时间（北京时间）、原推文直达链接与推文正文。

2. **方式 2：自动更新仓库文件并提交 Git Commit**
   - 自动更新根目录下的结构化数据文件 [`latest-reset.json`](./latest-reset.json)；
   - 自动更新上方 `最近一次重置记录` 看板，并由 GitHub Actions 机器人自动提交 commit 到 `main` 主干分支。

---

## 🔗 相关站点与资源
- 🌐 **在线监控站点**: [https://tibo.rowkin.xyz](https://tibo.rowkin.xyz)
- 🐦 **@thsottiaux 推特主页**: [https://x.com/thsottiaux](https://x.com/thsottiaux)
