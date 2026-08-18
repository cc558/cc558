# Hi, I'm cc558 👋

### AI 应用开发工程师｜8 年互联网研发经验  
### AI Application Engineer | 8 Years of Software Engineering Experience

我致力于把真实业务需求转化为可运行、可维护、可持续迭代的 AI 产品，重点关注 **AI Agent、RAG 检索与智能工作流**。

I turn real-world business requirements into maintainable and continuously evolving AI products, with a focus on **AI Agents, RAG systems, and intelligent workflows**.

---

## 🚀 About Me

- 8 年互联网软件研发经验，经历通信、电商和制造等业务领域
- 参与 CRM、财务及 ERP 等核心业务系统的开发与重构
- 相关业务覆盖 6000 万级通信用户和年度 GMV 10 亿级电商场景
- 从 Java 业务系统开发走向 AI 应用工程，关注 AI 技术在真实业务中的可靠落地

<br>

- 8 years of software engineering experience across telecommunications, e-commerce, and manufacturing
- Core development and system refactoring experience in CRM, finance, and ERP systems
- Worked on business systems serving over 60 million telecom users and e-commerce scenarios with annual GMV exceeding RMB 1 billion
- Now focused on bringing mature software engineering practices into real-world AI application development

---

## 🛠️ 我能做什么 · What I Do

- 从业务需求分析到 AI 应用方案设计与实现
- AI Agent 与多步骤智能工作流开发
- 企业知识库、RAG 与混合检索系统
- Java / Python 后端开发、系统集成与重构
- AI 应用评测、检索效果优化与工程化落地

<br>

- End-to-end AI application design and implementation
- AI Agents and multi-step intelligent workflows
- Enterprise knowledge bases and RAG systems
- Java / Python backend development, integration, and refactoring
- AI application evaluation and retrieval optimization

---

## 代表项目 · Selected Projects

### [交通法律智能助手 · Traffic Law Agent](https://github.com/cc558/traffic-law-agent)

个人独立设计并实现的 Agentic RAG 应用，用于从权威来源检索全国及地方性交通法规，目前可以在本地完整运行。

主要实现：

- 基于 LangGraph 构建可自主调用检索工具的 Agent
- 结合 Dense Retrieval 与 BM25 的混合检索
- 使用查询改写、MMR 和 Reranker 优化检索结果
- 支持国家法律法规数据库、地方性法规与联网权威来源
- 根据用户所在地匹配相关地方性法规

为了验证检索效果，我建立了包含 30 个问题的内部测试集。经过多种检索方案对比，最终采用 **Dense + BM25 + Reranker** 的组合，其中 29 个测试用例达到预期检索结果，测试用例达标率为 **96.7%**。

An independently designed and developed Agentic RAG application for retrieving national and regional traffic regulations from authoritative sources.

The project combines Dense Retrieval, BM25, query rewriting, MMR, and reranking. In an internal evaluation set of 30 legal questions, 29 test cases returned the expected retrieval results, achieving a **96.7% test-case success rate**.

---

### [真实透明背景转换 Skill · Real Transparent Background Skill](https://github.com/cc558/real-transparent-background-skill)

针对部分图像生成模型只能生成灰白棋盘格“伪透明背景”的问题，开发了一个确定性的本地图像处理工具。

它能够识别与画布边缘相连的背景区域，将其转换为真实 Alpha 通道，同时尽可能保留主体、文字和边缘细节。

- 支持 PNG、JPG、JPEG 和 WebP
- 支持单文件及批量处理
- 默认保留原图，不进行覆盖
- 提供 Alpha 通道和透明像素验证结果
- 已用于个人实际工作流
- SkillHub 下载量超过 100 次

A deterministic local image-processing tool that converts fake checkerboard transparency into a real PNG alpha channel while preserving foreground details.

It has been used in real personal workflows and has received over **100 downloads on SkillHub**.

---

## 📈 技术方向 · Technical Focus

**AI Application Engineering**

`AI Agent` · `RAG` · `LangGraph` · `Hybrid Retrieval` · `Reranker` · `Milvus` · `Chainlit`

**Backend Engineering**

`Java` · `Python` · `Business Systems` · `System Integration` · `System Refactoring`

**Business Domains**

`Telecommunications` · `E-commerce` · `Manufacturing` · `CRM` · `Finance` · `ERP`

---

## 🔗 联系与合作 · Contact

我愿意交流：

- AI 应用及企业智能化项目合作
- AI Agent、RAG 与工作流自动化
- AI 应用开发相关的职业机会
- 开源项目与技术交流

I'm open to AI application projects, technical collaboration, open-source work, and career opportunities related to AI application engineering.

📮 **Email:** [chencheng-kyle@foxmail.com](mailto:chencheng-kyle@foxmail.com)
