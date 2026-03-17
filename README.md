# 📚 5-Day AI Agents Intensive Course with Google 学习笔记

这是我对 Google 5-Day AI Agents Intensive Course 的学习记录与实操笔记仓库。

目标是按天整理 Agent 开发核心知识，从基础构建到生产部署，形成可复现、可回顾的 Notebook 学习路径。

## ✨ 仓库内容

本仓库当前包含以下 Notebook：

- day-1a-from-prompt-to-action.ipynb
- day-1b-agent-architectures.ipynb
- day-2a-agent-tools.ipynb
- day-2b-agent-tools-best-practices.ipynb
- day-3a-agent-sessions.ipynb
- day-3b-agent-memory.ipynb
- day-4a-agent-observability.ipynb
- day-4b-agent-evaluation.ipynb
- day-5a-agent2agent-communication.ipynb
- day-5b-agent-deployment.ipynb

## 🧭 学习路径（建议顺序）

1. Day 1：Agent 基础与多智能体架构
2. Day 2：工具接入与工程最佳实践
3. Day 3：Session 与 Memory 管理
4. Day 4：可观测性与评估
5. Day 5：A2A 通信与部署上线

## 🚀 如何使用

1. 克隆仓库到本地。
2. 使用 Jupyter Notebook 或 VS Code 打开对应 .ipynb 文件。
3. 按顺序运行各章节代码单元。
4. 根据 Notebook 提示配置必要凭据（如 API Key、Google Cloud 配置）。

## ⚙️ 环境建议

- Python 3.10+
- Jupyter Notebook / JupyterLab / VS Code (Notebook)
- 建议提前安装并配置：
  - google-adk
  - Vertex AI / Google Cloud 相关依赖

> 提示：部分 Notebook 运行依赖 Kaggle 环境能力（如 Kaggle Secrets、代理访问等），在本地运行时需做对应替换。

## 🔐 凭据与安全

- 不要在代码中硬编码 API Key、Access Token、项目密钥。
- 建议通过环境变量或 Secrets 管理工具注入凭据。
- 提交前请检查 Notebook 输出，避免敏感信息泄露。

## 📌 仓库定位

- 这是学习笔记仓库，偏重“课程内容复现 + 个人理解整理”。
- 如果后续加入扩展示例（如自定义工具、评估基准、部署模板），会继续按模块补充。

## 🙌 致谢

感谢 Google 与 Kaggle 提供高质量课程内容，帮助系统学习 AI Agent 的设计、开发与部署流程。
