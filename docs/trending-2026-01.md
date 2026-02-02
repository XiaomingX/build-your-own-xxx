# 2026年1月 GitHub 热门开源项目盘点

这是一份关于 2026 年 1 月份表现突出的 GitHub 开源项目的详细汇总。

---

## 重点推荐项

### 01 AI 金融分析 Agent: Dexter
**Dexter** 是一个专门搞金融研究的 AI Agent。它像个初级分析师一样去干活，你甩给它一个复杂的金融问题，比如分析某公司这季度的利润率变化原因，它能自己拆解任务去查数据。

它接入了实时的市场数据源，能翻阅财报、损益表这些硬数据，并且有一套自我检查的机制。如果它发现查到的数据不对劲，还会自己反思重查，直到拿出一个有数据支撑的结论。

- **开源地址**：[virattt/dexter](https://github.com/virattt/dexter)

### 02 无向量的 RAG: PageIndex
**PageIndex** 主要是为了解决传统 RAG 方案中向量化匹配的局限性。它模仿人类看书的方式，给文档建立一个像目录一样的树状结构。

这样 AI 在找资料的时候，能顺着逻辑结构一层层往下找，特别适合处理那些逻辑性很强的长文档，比如财报或者技术手册。它强调的是推理而不是简单的相似度匹配。

- **开源地址**：[VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex)

### 03 为 AI 编程增加记忆: Beads
**Beads** 是由 Steve Yegge 开发的一个给 AI 写代码增加持久记忆的工具。它本质上是一个基于 Git 的任务管理系统，但它是专门给 AI 读的。

它会把任务拆解得很细，存成 JSON 格式放在仓库里，让 AI 随时知道当前进度和后续计划，哪怕任务跨越数日也不会丢失上下文。

- **开源地址**：[steveyegge/beads](https://github.com/steveyegge/beads)

### 04 手搓 AI Agent 教程: learn-claude-code
**learn-claude-code** 旨在教你从零开始编写 AI Agent。它从一个最简单的 Bash 脚本开始，一步步添加工具调用、任务规划等核心功能。

作者去掉了繁琐的工程包装，让你看清 Agent 运行的真谛：思考、执行、再思考。

- **开源地址**：[shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code)

### 05 一体化 OSINT 工具: Web-Check
**Web-Check** 是 Web 开发和安全审计的一把利器。只需输入网址，它就能分析服务器位置、DNS 记录、SSL 证书、技术栈甚至是碳排放量。

它将所有公开信息整合在一个漂亮的仪表盘中，大大节省了调研竞品或检查自身漏洞的时间。

- **开源地址**：[Lissy93/web-check](https://github.com/Lissy93/web-check)

---

## 其它优质开源项目

这些项目在本月也获得了极高的关注，值得关注：

1. **[UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)** (字节跳动)
   - 桌面端 AI Agent，能看懂屏幕并操作鼠标键盘，实现真正的自动化控制。
   
2. **[awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)**
   - 包含文档处理、开发工具等 9 大类共 70 多个 Claude Skill 的集合。

3. **[remotion](https://github.com/remotion-dev/remotion)**
   - 使用 React 代码编写视频，就像写组件一样灵活，适合自动化和批量视频生成。

4. **[opencode](https://github.com/anomalyco/opencode)**
   - Claude Code 的开源平替，终端里的 AI 编程助手，支持多种大模型。

5. **[superpowers](https://github.com/obra/superpowers)**
   - 强迫 AI 在写代码前先写设计文档和 TDD 测试的框架，提高代码质量。

6. **[anthropics/skills](https://github.com/anthropics/skills)** (Anthropic 官方)
   - 官方提供的标准能力实现，如完美读取 PDF、操作 Google 文档等，代码质量极高。

7. **[vibe-kanban](https://github.com/BloopAI/vibe-kanban)**
   - 专门为管理 AI 任务流设计的看板工具，适合多智能体协作。

8. **[memos](https://github.com/usememos/memos)**
   - 轻量、隐私优先的开源随手记工具，支持自部署，类似于私有的 Flomo。
