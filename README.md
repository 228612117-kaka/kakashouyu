
# 手语通 (SignLanguage-AI-Dictionary) 🖐️📖

一个基于 Google Gemini AI 驱动的智能中文手语词典。输入中文词汇，AI 将自动生成手势描述、动作要领及视觉参考图。

## ✨ 特性

- **智能生成**：通过 Google Gemini 3 Flash 模型实时生成精准的手语打法解析。
- **视觉参考**：利用 Gemini 2.5 Flash Image 自动绘制手势示意图。
- **后台管理**：支持管理员登录，可手动修改文案或上传自定义演示图。
- **本地存储**：自定义词条优先存储于本地浏览器，支持离线查看（已缓存内容）。
- **数据迁移**：内置导入/导出功能，方便备份和迁移自定义词条库。

## 🛠️ 技术栈

- **前端**：React 19 + TypeScript + Tailwind CSS
- **AI 引擎**：@google/genai (Gemini API)
- **部署/运行**：ESM.sh 模块导入，无需复杂的构建步骤

## 🚀 快速开始

1. **设置环境变量**：
   确保您的运行环境配置了 `API_KEY` (Google AI Studio 申请)。

2. **管理后台凭据**：
   - **账号**：`admin`
   - **密码**：`123456`

## 📂 项目结构

- `App.tsx`: 主程序逻辑与状态管理
- `services/`: AI 调用与本地存储逻辑
- `components/`: UI 布局组件
- `types.ts`: 全局类型定义

## 📝 贡献

欢迎提交 Issue 或 Pull Request 来改进手语描述的准确性或 UI 体验。

---
© 2024 手语通团队
