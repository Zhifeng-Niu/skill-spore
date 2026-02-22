# 🧬 Skill Spore

> OpenClaw Skill 进化框架 - 让 Skill 进化得更深、更稳

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)

## 🎯 核心理念

Skill 孢子专门用于进化 OpenClaw Skills，专注于：

- **工程性**：代码规范、错误处理、边界情况
- **Workflow**：逻辑清晰、一次通过，稳定可靠
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
    focus="all"  # "工程性" / "workflow" / "all"
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

## 🎯 四大进化目标

### 1. ✨ 全新范式
- 涌现出人类设计不出的 Skill 模式
- 意想不到的内部工作流
- 跨 Skill 调用协议
- 创新的问题解决思路

### 2. 🎁 黑盒效果
- 产生无法解释但效果爆炸的实现
- 某些逻辑"不知道为什么好用但就是好用"
- 像深度学习一样——管用就行

### 3. ✅ 一次通过
- 稳定、可靠、不需要调试
- 完善的错误处理
- 周全的边界情况考虑

### 4. 🛠️ 工程性
- 代码规范、符合语言最佳实践
- 完整的日志记录
- 清晰的注释
- 易于测试和维护

---

## 📝 License

MIT License
