# MadStory - Seedance 2.0 影视级分镜助手

[![GitHub](https://img.shields.io/badge/GitHub-RoboErgo%2Fmadstroy-blue?logo=github)](https://github.com/RoboErgo/madstroy)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**MadStory** 是一款专为 Seedance 2.0 打造的创意导演与分镜助手。它能将模糊的创意构思，通过结构化的导演访谈，转化为专业级别的视频生成提示词与技术规格。

---

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

### 3. 生成分镜
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

- `index.html`: 核心展示与交互单页。
- `SKILL.md`: 技能定义文件，包含详细的 Persona 与 Workflow。
- `references/seedance_guide.md`: Seedance 2.0 技术规格参考指南。
- `verify_madstory.py`: 基于 Playwright 的自动化测试脚本。

## 🤝 贡献指南

1. Fork 本仓库。
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)。
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)。
4. 推送到分支 (`git push origin feature/AmazingFeature`)。
5. 开启一个 Pull Request。

## 📄 开源协议

本项目采用 [MIT](LICENSE) 协议。

---
*由 RoboErgo 团队开发。让创意触手可及。*
