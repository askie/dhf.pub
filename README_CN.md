# DHF Agent - AI 驱动的自动化 Web 代理

![DHF Agent Logo](icon.png)

**下一代 AI 驱动的智能流程自动化平台，智能理解并执行您的业务流程。**

[English](README.md) | [简体中文](README_CN.md) | [日本語](README_JA.md) | [Deutsch](README_DE.md) | [Français](README_FR.md) | [Español](README_ES.md) | [Português](README_PT.md) | [Русский](README_RU.md) | [한국어](README_KO.md)

---

## 🚀 简介 | Introduction

**DHF Agent** 是一款革命性的浏览器 RPA（机器人流程自动化）工具。它利用先进的 AI 技术来理解网页，帮助用户构建自动化工作流。

与其他 AI Agent 不同的是，DHF Agent 采用 **"AI 生成，本地运行"** 的模式。一旦工作流构建完成，它将转变为高效的固定代码运行，**不再消耗 Token**，既保证了执行的准确性，又实现了零成本运行。无论你是希望摆脱重复劳动的白领，还是寻求高效 Web 接口的开发者，DHF Agent 都是你的最佳伙伴。

---

## 🎯 为什么选择 DHF Agent？ | Who is this for?

我们为不同的人群量身定制了解决方案：

### 1. 👩‍💼 办公白领 & 行政人员 (Office Workers)
**告别重复点击，把时间留给创造。**
*   **痛点：** 每天要在浏览器上重复填写表单、抓取数据、点击按钮。
*   **DHF 方案：** 告诉 AI 你想做什么，它会自动生成操作流程。配合内置的**定时任务**，你可以让电脑在深夜自动帮你完成报表下载或数据录入，早上上班直接看结果。

### 2. 👨‍💻 AI 极客 & 程序员 (Developers & Geeks)
**零成本、高精度的网页操作方案。**
*   **痛点：** 纯 LLM 驱动的网页操作极其消耗 Token，且容易产生幻觉（Hallucination），不稳定。
*   **DHF 方案：** 利用 AI 辅助编写 Playwright 脚本，一旦调试通过，后续运行**Token 消耗为 0**。将不确定的 AI 推理转化为确定的代码执行，准确、可靠、免费。

### 3. 🦄 一人公司 & 独立开发者 (Solopreneurs)
**一个人就是一支队伍。**
*   **痛点：** 分身乏术，雇佣员工成本高。
*   **DHF 方案：** 创建不同的 DHF Agent 角色（如：客服助理、社媒运营、财务专员）。它们就像你的数字员工，并在后台独立完成各自的网页工作，让你的业务 24/7 运转。

### 4. 🔗 MCP & OpenClaw 用户 (Ecosystem Users)
**连接一切的超级触手。**
*   **痛点：** 大模型无法精准操作网页，或者操作成本过高。
*   **DHF 方案：** 完美支持 **MCP (Model Context Protocol)**。DHF Agent 可以挂载为 OpenClaw 或其他 AI 工具的 "手"，将自然语言指令转化为精准的 Playwright 动作，极大节省 Token 并提升操作成功率。

---

## ✨ 核心特性 | Key Features

### ⚡ 10 倍效率提升
将繁琐重复的 Web 操作交给 DHF Agent，实现效率的 10 倍飞跃。让机器做机器的事，让人做人的事。

### 🧠 AI 驱动与辅助调试
告别繁琐代码。AI 智能辅助生成和调试工作流，让自然语言驱动流程构建。自动化开发从未如此简单，即使不懂代码也能上手。

### 💸 零运行成本 (Zero Runtime Cost)
这是我们最大的优势。调试完成后，工作流无需 AI 介入即可独立运行。**没有持续的 API Token 成本**，实现真正的经济性。

### 🔒 隐私优先
完全本地运行，数据加密存储。浏览器数据、账号密码都在你自己的设备上，您拥有完全控制权，确保绝对安全。

### 🌐 MCP 生态互联
支持标准 MCP 协议，无缝连接 **n8n**、**Dify**、**OpenClaw** 等外部生态系统。打破应用孤岛，构建超级自动化工作流。

### 🤝 工作流分享
支持一键导出和分享任务流。将你的“自动化经验”转化为文件分享给同事或社区，实现能力的快速复用。

### ⏱️ 智能任务调度
内置专业级 Cron 调度引擎，支持秒级定时配置。完全自动化您的周期性工作（如：每天上午 9 点自动打卡、每周五自动发送周报）。

---

## 🛠️ 技术集成 (For Developers)

DHF Agent 不仅仅是一个工具，更是一个基础设施。

*   **作为 MCP Server:**  可以将 DHF Agent 挂载为 Cursor、Claude Desktop 或其他 AI Code 工具的 MCP Server。这使得您的 AI 编程助手具备了直接操作真实浏览器的能力。
*   **Playwright 转换器:** 它可以将不稳定的自然语言意图，沉淀为稳定的 Playwright 脚本。
*   **API 触发:** 支持本地 API 调用，轻松集成到您现有的 Python/Node.js 项目中。

---

## 📥 下载与安装 | Download

支持 Windows, macOS 和 Linux。

[**点击这里下载最新版本**](https://dhf.pub/)

---

## 🚀 快速开始 | Quick Start

1.  **下载并安装** DHF Agent。
2.  **创建任务**：点击 "新建任务"，输入目标网址。
3.  **AI 录制**：在对话框中告诉 AI "帮我登录，并下载最近的订单Excel"，AI 将自动生成步骤。
4.  **保存并运行**：确认步骤无误，保存任务。设置定时器，以后它将自动为您工作。

---

## 社区与支持

*   提交 Issues: [GitHub Issues](https://github.com/askie/dhf.pub/issues)

---

**DHF Agent** - Redefining Browser Automation with AI.

---
