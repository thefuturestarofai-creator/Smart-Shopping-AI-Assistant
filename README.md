# 智能好物推荐与识物记账小程序 (Smart-Shopping-AI-Assistant)

本项目为“字节跳动2026年AI全栈挑战赛”第一志愿课题的敏捷全栈原型。通过全量拥抱 AI Coding 工具，在极短时间内完成了端到端的 UI 设计与前端部署。

## 🚀 项目在线演示
- **Live Demo:** [https://v0-project-one-hazel-36.vercel.app/]

## 🛠️ 核心开发工具链
- **AI IDE:** Trae (字节自研 AI 编程工具) & Cursor
- **UI Generator:** Vercel v0.dev
- **Deployment:** Vercel Cloud

## ✨ 核心功能规划
1. **多模态识物比价：** 用户上传商品图片，调用多模态大模型 API 自动识别品类，并全网检索同款/相似款历史低价。
2. **AI 消费合理性评估：** 结合用户历史记账账单，由 AI 给出“高性价比”或“冲动消费”的智能评估，帮助用户理性消费。
3. **抖音电商生态联动：** 智能推荐抖音电商高性价比同款商品，实现“识物-比价-种草”闭环。

## 📈 技术演进路线
- [x] Phase 1: 移动端 UI 视觉原型构建与公网部署 (v0.dev)
- [ ] Phase 2: 基于 Trae 进行本地代码重构，接入后端 FastAPI 框架
- [ ] Phase 3: 对接豆包大模型 (Doubao API) 实现多模态识别逻辑
