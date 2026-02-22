# 🧬 Skill Spore

> OpenClaw Skill 进化框架 - 让 Skill 进化得更深、更稳

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)

## 🎯 核心理念

Skill 孢子专门用于进化 OpenClaw Skills，专注于：

- **工程性**：代码规范、错误处理、边界情况
- **Workflow**：逻辑清晰、一次通过、稳定可靠
- **全新范式**：意想不到的 Skill 组织方式
- **黑盒效果**：无法解释但效果爆炸的实现

## 🚀 快速开始

```python
from skill_spore import SkillSpore, EvolutionConstraints

spore = SkillSpore(llm_client)

constraints = EvolutionConstraints(
    core_function_must_keep="保留什么功能",
    usage_pattern_must_keep="使用方式不变"
)

new_skill = spore.evolve_skill(
    skill=my_skill,
    feedback="问题反馈...",
    constraints=constraints,
    focus="工程性"  # 或 "workflow"
)
```

---

## 📁 架构

```
skill-spore/
├── skill_spore.py       # 核心引擎
├── requirements.txt     # 依赖
└── README.md
```

---

## 🎯 进化目标

### 约束（不变）

- ✅ 核心功能保持
- ✅ 使用方式不变
- ✅ 不引入新依赖

### 进化方向

| 方向 | 目标 |
|------|------|
| **deep_dive** | 深入而非广博 |
| **one_shot** | 一次通过 |
| **robustness** | 稳定可靠 |
| **clarity** | 清晰明确 |

### 终极目标

1. **全新范式** - 涌现出人类设计不出的 Skill 模式
2. **黑盒效果** - 无法解释但效果爆炸
3. **一次通过** - 稳定、可靠、不需要调试

---

## 📝 License

MIT License
