# Domain-Aware Product Research

**Discover what you didn't know you needed to research.**

*Built for designers. Useful across product teams.*

English | [简体中文](#简体中文)

---

# English

## Product Introduction

An open-source AI research partner that helps UX and Product Designers uncover hidden features, behaviours, business rules, dependencies, and edge cases when designing products in unfamiliar or complex domains.

## Why This Exists

**Entering a new domain means facing design questions you don't yet know to ask.**

A designer entering futures trading, healthcare, or enterprise finance may only have a basic understanding of the domain. Yet when beginning to design a product, they need to explore a much wider range of potential features, interactions, constraints, and exceptional scenarios — many of which they may not even know exist.

When entering a new domain, the challenge isn't simply learning its terminology. It's knowing which product capabilities to investigate, which assumptions to challenge, and which questions you haven't thought to ask.

Traditional desk research often starts with what the designer already knows to search for.

**But what about everything they don't know exists?**

## How It Helps

Domain-Aware Product Research helps uncover these unknowns by connecting domain knowledge to potential product capabilities, behaviours, edge cases, and research questions.

It doesn't replace domain learning or professional design judgement. Instead, it gives designers a more structured starting point for exploring what might otherwise be overlooked.

## What It Helps You Do

- **Feature Discovery** — Discover potential features and sub-features beyond your initial assumptions.
- **Domain-Aware Research** — Investigate behaviours, business rules, dependencies, and edge cases.
- **Competitor UI Research** — Explore real competitor UI references alongside research findings.
- **Designer-Contributed Research** — Incorporate screenshots and annotated research from Figma, FigJam, or Miro.
- **Research Questions & Validation** — Identify what still needs validation and who to ask.
- **Role-Aware Exploration** — Explore findings from Designer, Product Manager, and Developer perspectives.

## The Outcome

The result is an interactive, evidence-informed **Research Explorer HTML** designed to support better questions and more informed design decisions.

**The goal isn't to tell designers exactly what to build. It's to help them discover what they need to investigate before deciding what to build.**

## Demo
<img width="1409" height="960" alt="截屏2026-11-20 20 28 57" src="https://github.com/user-attachments/assets/ccbe2bf4-25bd-43dc-a4e9-5b3e451512dc" />
<img width="1189" height="968" alt="截屏2026-11-20 20 29 44" src="https://github.com/user-attachments/assets/de68d0b5-bf1a-4d09-a1e5-e10b5e736d57" />


## Installation

Domain-Aware Product Research follows the open [Agent Skills specification](https://agentskills.io/specification).

You can use it with AI agents that support custom Agent Skills, including Codex and Claude Code.

### Option 1 — Install with your AI Agent

1. Copy this repository URL:
   `https://github.com/Cindyzhan1/domain-aware-product-research-skill`
2. Open your AI Agent.
3. Ask your Agent to install the Skill from this GitHub repository, using its supported Skill installation method.
4. Confirm that the `domain-aware-product-research` Skill is available.

**Note:** Installation methods vary by Agent. Some agents may require you to download and install the Skill folder manually.

### Option 2 — Manual installation

1. Download this repository using **Code → Download ZIP**.
2. Extract the ZIP file.
3. Place the extracted Skill folder in your Agent's supported Skills directory, preserving `SKILL.md` and the `assets/` folder.
4. Restart or refresh your Agent if necessary.

For platform-specific guidance, see the [Codex documentation](https://developers.openai.com/codex/skills) or [Claude Code documentation](https://code.claude.com/docs/en/skills).

## How to Use

Once installed, try this prompt:

> Use the domain-aware-product-research Skill to help me explore the features, behaviours, business rules, edge cases, and real UI patterns involved in designing a XX feature in XX platform/product.

The Skill will guide you through optional research inputs and generate an interactive Research Explorer HTML when your Agent supports local file creation.

## Optional Integrations

The Skill can work with public research sources alone. Additional integrations may enrich the research:

- **Mobbin MCP** — Discover existing product UI patterns and screenshots.
- **Figma / FigJam MCP** — Import your own annotated competitor research.
- **Miro MCP** — Incorporate visual research boards.
- **Screenshot uploads** — Contribute your own UI references.

These integrations are optional and must be configured in your own AI Agent environment.

## Limitations

- AI-generated research may be incomplete or inaccurate. Validate important findings against reliable sources and domain experts.
- Feature candidates are research opportunities, not confirmed product requirements.
- Third-party and private screenshots may have redistribution restrictions.
- Available integrations and output capabilities vary between AI Agents.

---

# 简体中文

**发现那些你甚至不知道自己需要研究的问题。**

*为设计师而打造，也能帮助整个产品团队。*

## 产品介绍

Domain-Aware Product Research 是一个开源的 AI Research Partner，帮助 UX / Product Designers 在设计陌生或复杂领域的产品时，发现原本可能忽略的功能、交互行为、业务规则、依赖关系和边界情况。

## 为什么做这个 Skill？

**进入一个陌生领域，意味着你将面对许多自己甚至不知道应该提出的设计问题。**

一位刚接触期货交易、医疗或企业金融领域的设计师，可能仅仅对这个领域有了初步了解。但当真正开始设计产品时，他们需要探索大量潜在的 Features、Interactions、Constraints 和 Edge Cases——而其中很多内容，可能是他们此前根本不知道存在的。

进入陌生领域时，真正的挑战不只是学习专业术语，而是知道应该研究哪些产品能力、质疑哪些假设，以及还有哪些自己从未想到的问题。

传统的 Desk Research 往往从设计师已经知道的关键词和问题开始。

**但那些设计师根本不知道存在的功能和问题呢？**

## 它如何帮助设计师？

Domain-Aware Product Research 将领域知识与潜在的产品功能、交互行为、Edge Cases 和 Research Questions 联系起来，帮助设计师发现这些 Unknown Unknowns。

它并不是代替设计师学习领域知识，也不替代专业设计判断，而是提供一个结构化的研究起点，让那些原本容易被遗漏的问题变得可见。

## 核心能力

- **Feature Discovery · 功能发现** — 探索超出初始认知范围的 Features 和 Sub-features。
- **Domain-Aware Research · 领域研究** — 理解交互行为、业务规则、系统依赖与边界情况。
- **Competitor UI Research · 竞品 UI 研究** — 将真实产品截图与研究结论关联起来，帮助理解已有设计方案。
- **Designer-Contributed Research · 设计师参与研究** — 导入设计师自己的截图、Figma / FigJam / Miro 标注，让已有研究进一步丰富 Feature Map。
- **Research Questions & Validation · 研究问题与验证** — 发现尚未确认的问题、应该询问的角色，以及下一步验证方式。
- **Role-Aware Exploration · 跨职能研究** — 从设计师、产品经理和开发者的不同专业视角探索同一领域。

## 最终产出

最终生成一个交互式、由研究证据支持的 **Research Explorer HTML**，帮助设计师系统地探索产品功能、发现未知问题，并在开始设计前做出更有依据的判断。

**我们的目标不是告诉设计师应该做出什么产品，而是帮助他们在决定如何设计之前，发现自己还需要研究什么。**

## 效果展示
<img width="1292" height="941" alt="截屏2026-11-20 20 41 42" src="https://github.com/user-attachments/assets/58dbadb7-ebca-40fa-97ce-5bb49e1ce904" />
<img width="1189" height="964" alt="截屏2026-11-20 20 42 01" src="https://github.com/user-attachments/assets/38ce658b-3786-46a0-b8be-209652dce731" />


## 安装方法（Installation）

Domain-Aware Product Research 采用开放的 [Agent Skills 规范](https://agentskills.io/specification)。

只要你的 AI Agent 支持自定义 Agent Skills，就可以尝试安装和使用，例如 Codex、Claude Code 等。

### 方式一：通过 AI Agent 安装

1. 复制本项目的 GitHub 地址：

   `https://github.com/Cindyzhan1/domain-aware-product-research-skill`

2. 打开你使用的 AI Agent。
3. 告诉 Agent：请按照它所支持的 Skill 安装方式，从上述 GitHub 仓库安装这个 Skill。
4. 确认 `domain-aware-product-research` 已成功安装并可以调用。

**注意：** 不同 Agent 的安装方法可能不同。有些 Agent 需要手动下载并放置 Skill 文件夹。

### 方式二：手动安装

1. 在 GitHub 项目首页点击 **Code → Download ZIP**。
2. 解压下载的 ZIP 文件。
3. 将解压后的 Skill 文件夹放到你的 AI Agent 支持的 Skills 目录中，并保留 `SKILL.md` 和 `assets/` 文件夹。
4. 如果需要，重新启动或刷新 AI Agent。

具体安装路径和方法，请参考 [Codex 官方文档](https://developers.openai.com/codex/skills) 或 [Claude Code 官方文档](https://code.claude.com/docs/en/skills)。

## 如何使用（How to Use）

安装完成后，可以尝试输入：

> 请使用 domain-aware-product-research Skill，帮助我研究设计一个XXX产品/平台的 XX功能所涉及的潜在功能、交互行为、业务规则、边界情况，以及现有产品的真实 UI 设计。

Skill 会先引导你选择是否提供已有研究资料。如果 AI Agent 支持本地文件创建，它会进一步生成交互式的 **Research Explorer HTML**。

## 可选集成（Optional Integrations）

即使没有额外集成，Skill 也可以利用公开资料进行研究。

如果你的 AI Agent 支持相应的 MCP 连接，还可以使用：

- **Mobbin MCP** — 搜索真实产品的 UI 截图和交互模式。
- **Figma / FigJam MCP** — 导入自己在 Figma 或 FigJam 中完成的竞品研究和设计标注。
- **Miro MCP** — 导入可视化研究板。
- **上传截图** — 直接提供自己收集的竞品界面作为研究资料。

这些集成都不是必需的，需要用户根据自己的 Agent 环境和账户权限单独配置。

## 使用限制（Limitations）

- AI 生成的研究可能不完整或存在错误。重要结论应通过可靠资料和领域专家进一步核实。
- Skill 发现的 Feature Candidates 是值得探索的设计方向，**不代表已经确认的产品需求**。
- 第三方产品截图和私人研究资料可能受到版权或传播限制，公开分享前应确认使用权限。
- 不同 AI Agent 支持的工具、MCP 集成及 HTML 生成功能可能有所差异。
