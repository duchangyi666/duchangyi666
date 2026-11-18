<p align="center">
  <img src="./profile-banner.png" width="100%" alt="杜昌亿 — AI Application Engineer · Agent、Memory、RAG、Evals" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Nunito&weight=600&size=22&duration=3600&pause=1400&color=3B91C8&center=true&vCenter=true&width=820&height=52&lines=Building+reliable+AI+agents+for+real+work.;Memory,+RAG,+tools,+and+evals." alt="Building reliable AI agents for real work." />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-AI%20Application%20Engineer-2563eb?style=for-the-badge" alt="正在寻找 AI 应用开发工程师机会" />
  <img src="https://img.shields.io/badge/Focus-AI%20Agent-0f766e?style=for-the-badge" alt="专注 AI Agent" />
  <a href="mailto:1396075859@qq.com"><img src="https://img.shields.io/badge/EMAIL-1396075859%40qq.com-e85d4a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=b83d35" alt="Email" /></a>
</p>

## 👋 关于我

你好，我是 **杜昌亿**，河南农业大学 **数据科学与大数据技术** 专业，目前正在寻找 **AI 应用开发工程师** 相关机会。

我关注 **Agent 应用落地**：多智能体如何稳定编排，记忆和知识如何被可靠写入与召回，工具调用如何守住边界，以及怎样用评测和可观测性验证系统确实可用。我在个人项目里实践了基于 LangGraph 的客服与审批 Agent 平台，以及金融场景的 FAQ + RAG 级联问答；同时也向上游开源项目贡献修复，覆盖 Agent 记忆去重、MCP 观察性和工具选择边界。

欢迎通过 [邮箱](mailto:1396075859@qq.com) 交流。

🌱 我会持续参与开源协作，在真实的 Agent 工程问题里打磨可靠性。

[![已合并 PR：2](https://img.shields.io/badge/MERGED%20PRs-2-2ea44f?style=for-the-badge&labelColor=25364a&logo=github&logoColor=white)](https://github.com/search?q=is%3Apr+author%3Aduchangyi666+is%3Amerged+-user%3Aduchangyi666+is%3Apublic&type=pullrequests)
[![上游仓库：3](https://img.shields.io/badge/UPSTREAM%20REPOS-3-397ac4?style=for-the-badge&labelColor=25364a&logo=github&logoColor=white)](https://github.com/search?q=is%3Apr+author%3Aduchangyi666+is%3Amerged+-user%3Aduchangyi666+is%3Apublic&type=pullrequests)
[![开放中 PR：1](https://img.shields.io/badge/OPEN%20PRs-1-168b83?style=for-the-badge&labelColor=25364a&logo=github&logoColor=white)](https://github.com/search?q=is%3Apr+author%3Aduchangyi666+is%3Aopen+-user%3Aduchangyi666+is%3Apublic&type=pullrequests)

Cygnux-Labs **1** · mcp-memory-service **1** · basic-memory **1**（由维护者带原署名合入）　<sub>截至 2026-11-18 · 公开上游仓库</sub>

## 🛠️ 技术栈

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,fastapi,nextjs&theme=dark&perline=4" alt="Python, TypeScript, FastAPI, Next.js" />
  <img src="https://skillicons.dev/icons?i=postgres,docker,redis,git&theme=dark&perline=4" alt="PostgreSQL, Docker, Redis, Git" />
</p>

---

## 🔧 上游贡献

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      🧠 <strong>记忆与知识召回</strong><br>
      修复语义去重误拒已更新事实的问题，并解决 MCP 中带斜杠的章节标题无法被选中。<br>
      <a href="https://github.com/doobidoo/mcp-memory-service/pull/1954">mcp-memory-service #1954</a> · <a href="https://github.com/basicmachines-co/basic-memory/pull/2095">basic-memory #2095</a>（源自 <a href="https://github.com/basicmachines-co/basic-memory/pull/2087">#2087</a>）
    </td>
    <td width="50%" valign="top">
      🔍 <strong>可观测与 MCP</strong><br>
      让 MCP 客户端观察 <code>list_tools</code> / <code>list_resources</code> / <code>list_prompts</code>，便于审计工具发现过程。<br>
      <a href="https://github.com/Cygnux-Labs/Tracekit/pull/685">Tracekit #685</a>（已进入 <a href="https://github.com/Cygnux-Labs/Tracekit/releases/tag/v1.7.1">v1.7.1</a>）
    </td>
  </tr>
</table>

进行中：[deer-flow #7550](https://github.com/bytedance/deer-flow/pull/7550) — 在 skill-creator 聚合评分前校验 grading duration，避免空值中断评测。

## 项目实践

- **[金融客户运营与服务 Agent 平台](https://github.com/duchangyi666/ecop-agent-platform)** — 基于 LangGraph 的多智能体客服与工单平台；包含输入安全 Guard、RAG 知识库、退款审批闭环，以及客户 / 客服 / 管理三门户，并配有检索与安全评测。
- **[FinRAG · 金融智能问答](https://github.com/duchangyi666/rag)** — 金融领域问答系统；采用 FAQ 快查、意图分类和 RAG 检索的三级级联路由，在保证回答质量的同时降低大模型调用成本。

---

<p align="center">
  <a href="https://github.com/search?q=is%3Apr+author%3Aduchangyi666+is%3Amerged+-user%3Aduchangyi666+is%3Apublic&type=pullrequests"><img src="./footer-merged.svg" width="188" height="56" alt="已合并 PR" /></a>
  <a href="https://github.com/search?q=is%3Apr+author%3Aduchangyi666+is%3Aopen+-user%3Aduchangyi666+is%3Apublic&type=pullrequests"><img src="./footer-open.svg" width="188" height="56" alt="开放中的 PR" /></a>
  <a href="mailto:1396075859@qq.com"><img src="./footer-email.svg" width="188" height="56" alt="联系我" /></a>
</p>
