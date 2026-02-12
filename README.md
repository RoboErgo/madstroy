# MadStory - Seedance 2.0 影视级分镜助手 (SKILLS 技能包 / SKILLS Package)

[![GitHub](https://img.shields.io/badge/GitHub-RoboErgo%2Fmadstroy-blue?logo=github)](https://github.com/RoboErgo/madstroy)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[中文](#中文) | [English](#english)

---

## 中文

**MadStory** 是一个基于 **Seedance 2.0 使用手册** 深度定制并打包的 **SKILLS 技能包**。它旨在通过 AI Agent 的能力，将复杂的影视制作规范转化为可交互的创作流程。

### 📦 SKILLS 技能包定义

本项目遵循 [Claude's skills](https://github.com/anthropics/skills) 的规范进行组织，通过结构化的 `SKILL.md` 定义 Agent 的行为边界：

- **基于手册**：核心逻辑严格参考 [Seedance 2.0 技术规格指南](references/seedance_guide.md)。
- **能力内化**：将 5 维度控制（镜头、光影、色彩、动作、声音）内化为 Agent 的导演思维。
- **即插即用**：支持在兼容 Claude Skills 规范的 AI 环境中直接加载使用。

### 🌟 核心特性

- **结构化访谈**：采用 3 阶段导演式对话，从视觉基础、氛围塑造到声音节奏，全方位挖掘创意细节。
- **5 维度控制**：精准覆盖镜头运动、光影氛围、色彩基调、主体动作及声音设计。
- **Seedance 2.0 深度优化**：
  - 默认输出 **15 秒** 专业片段时长。
  - 支持**多模态参考**（图像/视频/音频）提示。
  - 提示词结构完美契合 Seedance 2.0 的生成引擎。
- **双语支持**：内置完善的中英文切换逻辑，适配国际化创作环境。

### 🚀 快速开始

#### 1. 安装 (CLI)
```bash
npm install madstory-seedance2 -g
```

#### 2. 初始化
```bash
madstory init --provider seedance2
madstory auth --token YOUR_TOKEN
```

#### 3. 使用技能
在 AI 助手（如 Trae, Claude 等）中加载此技能包，或通过 CLI 生成：
```bash
madstory generate "一名宇航员在火星发现发光的石碑" --duration 15
```

### 📂 文件结构

- `SKILL.md`: **核心技能定义**，包含详细的 Persona 与 Workflow 规范。
- `references/seedance_guide.md`: Seedance 2.0 原始技术手册参考。
- `verify_madstory.py`: 技能交互逻辑自动化验证脚本。

---

## English

**MadStory** is a **SKILLS package** deeply customized based on the **Seedance 2.0 User Manual**. It leverages AI Agent capabilities to transform complex film production standards into an interactive creative workflow.

### 📦 SKILLS Package Definition

This project is organized following the [Claude's skills](https://github.com/anthropics/skills) specification, defining Agent behavioral boundaries through a structured `SKILL.md`:

- **Manual-Based**: Core logic strictly references the [Seedance 2.0 Technical Specifications Guide](references/seedance_guide.md).
- **Inherent Capabilities**: Internalizes 5-dimensional controls (Camera, Lighting, Color, Action, Sound) into the Agent's directorial mindset.
- **Plug-and-Play**: Supports direct loading in AI environments compatible with the Claude Skills specification.

### 🌟 Key Features

- **Structured Interviews**: Uses a 3-phase directorial dialogue to extract creative details across visual foundations, atmosphere, and rhythm.
- **5-Dimensional Control**: Precisely covers camera movement, lighting atmosphere, color tone, subject action, and sound design.
- **Seedance 2.0 Deep Optimization**:
  - Default output duration of **15 seconds**.
  - Supports **multimodal reference** (image/video/audio) prompting.
  - Prompt structures perfectly aligned with the Seedance 2.0 generation engine.
- **Bilingual Support**: Built-in logic for seamless switching between Chinese and English, catering to global creators.

### 🚀 Quick Start

#### 1. Installation (CLI)
```bash
npm install madstory-seedance2 -g
```

#### 2. Initialization
```bash
madstory init --provider seedance2
madstory auth --token YOUR_TOKEN
```

#### 3. Using the Skill
Load this skills package in AI assistants (e.g., Trae, Claude) or generate via CLI:
```bash
madstory generate "An astronaut discovers a glowing monolith on Mars" --duration 15
```

### 📂 File Structure

- `SKILL.md`: **Core Skill Definition**, containing detailed Persona and Workflow specifications.
- `references/seedance_guide.md`: Original Seedance 2.0 technical manual reference.
- `verify_madstory.py`: Automated validation script for skill interaction logic.

---

### 📄 License

This project is licensed under the [MIT](LICENSE) License.

---
*Developed by the RoboErgo team. Built based on the SKILLS specification.*
