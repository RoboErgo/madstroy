# MadStory - Seedance 2.0 影视级分镜助手 (SKILLS 技能包)

[![GitHub](https://img.shields.io/badge/GitHub-RoboErgo%2Fmadstroy-blue?logo=github)](https://github.com/RoboErgo/madstroy)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**MadStory** 是一个基于 **Seedance 2.0 使用手册** 深度定制并打包的 **SKILLS 技能包**。它旨在通过 AI Agent 的能力，将复杂的影视制作规范转化为可交互的创作流程。

---

## 📦 SKILLS 技能包定义

本项目遵循 [servasyy_skills](https://github.com/huangserva/servasyy_skills) 的规范进行组织，通过结构化的 `SKILL.md` 定义 Agent 的行为边界：

- **基于手册**：核心逻辑严格参考 [Seedance 2.0 技术规格指南](references/seedance_guide.md)。
- **能力内化**：将 5 维度控制（镜头、光影、色彩、动作、声音）内化为 Agent 的导演思维。
- **即插即用**：支持在兼容 SKILLS 规范的 AI 环境中直接加载使用。

## 🌟 核心特性

- **结构化访谈**：采用 3 阶段导演式对话，从视觉基础、氛围塑造到声音节奏，全方位挖掘创意细节。
- **5 维度控制**：精准覆盖镜头运动、光影氛围、色彩基调、主体动作及声音设计。
- **Seedance 2.0 深度优化**：
  - 默认输出 **15 秒** 专业片段时长。
  - 支持**多模态参考**（图像/视频/音频）提示。
  - 提示词结构完美契合 Seedance 2.0 的生成引擎。
- **双语支持**：内置完善的中英文切换逻辑，适配国际化创作环境。

## 🚀 快速开始

### 1. 安装 (CLI)
```bash
npm install madstory-seedance2 -g
```

### 2. 初始化
```bash
madstory init --provider seedance2
madstory auth --token YOUR_TOKEN
```

### 3. 使用技能
在 AI 助手（如 Trae, Claude 等）中加载此技能包，或通过 CLI 生成：
```bash
madstory generate "一名宇航员在火星发现发光的石碑" --duration 15
```

## 🛠 技术实现

本项目包含一个交互式的介绍与演示页面 [index.html](index.html)，实现了以下功能：
- **响应式设计**：完美适配 PC、平板与手机端。
- **实时演示区**：可交互的参数选择器，模拟 MadStory 的核心输出流程。
- **性能优化**：首屏加载时间 < 3s，Lighthouse 评分 90+。
- **一键复制**：所有生成的提示词与示例命令均支持一键拷贝。

## 📂 文件结构

- `SKILL.md`: **核心技能定义**，包含详细的 Persona 与 Workflow 规范。
- `index.html`: 技能介绍与交互演示单页。
- `references/seedance_guide.md`: Seedance 2.0 原始技术手册参考。
- `verify_madstory.py`: 技能交互逻辑自动化验证脚本。

## 📄 开源协议

本项目采用 [MIT](LICENSE) 协议。

---
*由 RoboErgo 团队开发。基于 SKILLS 规范构建。*
