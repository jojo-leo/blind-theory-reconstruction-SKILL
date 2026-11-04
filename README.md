# Blind Theory Reconstruction / 盲理论重建

**A spoiler-controlled theory-building exercise for social-science students and researchers.**

[中文说明](#中文说明) · [English](#english)

## 中文说明

### 项目是什么？

读社科理论经典时，我们常常直接接触到作者已经完成的概念体系与理论结论，却缺少亲自把经验材料抽象为理论的训练。**Blind Theory Reconstruction** 让读者暂时扮演原作者：先获得书中的研究问题和作者使用的经验材料，再在不知道作者理论框架的情况下自行建构解释，最后与原作者对照并接受结构化反馈。

面向社会学、政治学、经济学、人类学、法学等重视理论构建的社会科学学习者和研究者。

### 三个阶段

1. **经验材料呈现（防剧透）**：上传理论著作的 PDF，AI 读出研究问题、历史背景、案例、访谈、档案、统计资料或作者的一手发现，并标注章节或页码；**隐藏作者的理论模型与分析框架**。
2. **读者独立建构**：读者根据材料提出自己的概念、解释机制、理论命题与适用边界。AI 不提前提供标准答案。
3. **理论对照与评价**：读者提交之后，AI 揭示原作者的理论，将两种框架逐项比较，按五个维度评分并提出具体改进意见，同时指出原理论自身可能存在的局限。

### 评分维度

| 维度 | 权重 |
|---|---:|
| 理论问题识别 | 15 |
| 概念抽象与清晰度 | 20 |
| 因果机制解释或解释性论证 | 25 |
| 一般化与适用边界 | 20 |
| 竞争解释、可证伪性与原创性 | 20 |

评分用于形成性反馈，并非标准化学术能力测量。解释性研究不强制套用因果主义或狭义可证伪性标准。

### 使用方法

1. 在支持 Agent Skills 的 AI 客户端中安装 `blind-theory-reconstruction/SKILL.md`（按照客户端的技能目录、导入或安装说明操作）。
2. 上传一本社科理论著作的 PDF，或提供可以访问的授权文本。
3. 输入：**“运用盲理论重建skill来处理这本书。”**
4. 完成自己的理论框架后，将回答发给模型，再查看原著解释、逐项比较与评分。

> 安装方式因 ChatGPT、Codex 或其他 Agent Skills 客户端而不同；此仓库不声称可在所有客户端中一键安装，也不包含书籍PDF。

### 文件结构

```text
blind-theory-reconstruction/
├── README.md
├── blind-theory-reconstruction/
│   └── SKILL.md
└── examples/
    └── sample-session.md
```

### 学术规范

- 案例和数据必须来自可读的原文，并尽可能标记页码；不能凭书名编造材料。
- 必须区分作者的一手材料、引述的他人资料以及作者的分析与解释。
- 解锁理论之前不能通过标题、提示、概念词或评论提前剧透。
- 原作者不是“标准答案”；比较的目的是提高独立理论思考能力。
- 用户需遵守书籍版权和所使用模型的上传政策。仓库不收录受版权保护的书籍全文。

## English

### Why this skill?

Readers of classic social-science theory often encounter polished explanations without practicing the intermediate work of theory construction. This skill temporarily removes the author's theoretical answer while keeping the research question and the actual empirical materials available for independent reasoning.

**Audience:** students and researchers in sociology, political science, economics, anthropology, law, and adjacent social sciences.

**Workflow:**

1. **Evidence first:** The AI extracts the research question and source-located empirical cases from the uploaded book, without revealing the author's theory.
2. **Independent theory building:** The reader proposes concepts, mechanisms or interpretive logic, propositions, and boundaries.
3. **Reveal and evaluate:** The AI reconstructs the author's framework, compares it with the reader's, scores five dimensions (15/20/25/20/20), and gives actionable feedback.

**Trigger:** `运用盲理论重建skill来处理这本书` or `Use the blind theory reconstruction skill on this book.`

The canonical workflow is in [`blind-theory-reconstruction/SKILL.md`](blind-theory-reconstruction/SKILL.md). See the [fictional example](examples/sample-session.md). This repo deliberately excludes book PDFs, note-taking integrations, and unrelated engineering workflows.

### License

No open-source license has been selected yet. The copyright holder should add an explicit `LICENSE` file **before inviting reuse or redistribution**. Without an explicit license, ordinary copyright restrictions apply to the repository's original text.
