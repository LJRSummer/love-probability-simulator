# 恋爱概率模拟器 · Love Probability Simulator

> 忽冷忽热，欲拒还迎...暧昧让人受尽委屈，但如果这种不确定性能被量化呢？


![version](https://img.shields.io/badge/version-1.0.0-ff69b4)
![license](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ 它能做什么

输入crush/暧昧对象的相关信息，帮你计算目前的攻略进度，以及分析她/他目前的想法。

输入：
- 📱 聊天记录（微信 / QQ / txt 导出 / 截图）
- 🌅 朋友圈 / 微博 / 小红书 截图
- 📸 照片（含 EXIF 元数据）
- 💬 用户的口述补充

输出：
- 🎲 好感概率 / 关系推进概率 / 当前趋势
- 📖 关系时间线（剧情化叙事）
- 🧠 对方心理解读
- 🎯 具体可执行的行动建议
- 🗣️ TA 视角模拟（第一人称内心独白）

---

## 🧪 触发场景

当用户说这些话时，会自动加载：

- "他是不是喜欢我？"
- "帮我看看这段聊天记录"
- "我们是不是变淡了"
- "我该不该表白 / 继续 / 放弃"
- "分析一下他最近的朋友圈"
- "暧昧期 / 拉扯 / 冷战分析"

---

## 📂 目录结构

```
love-probability-simulator/
├── SKILL.md                         # 核心规范（skill 主文件）
├── README.md                        # 本文件
├── references/
│   ├── data_extraction.md           # 多源数据提取指引
│   ├── persona_modeling.md          # 5 层人物画像建模
│   ├── output_templates.md          # 输出模板 & 风格示例
│   └── probability_heuristics.md    # 概率计算启发式（内部）
└── examples/
    └── sample_analysis.md           # 一份完整示例
```

---

## 🚀 安装 & 使用

### 方式 1：放入 skills 目录
将整个 `love-probability-simulator/` 文件夹解压到你 AI Agent 的 skills 目录下，
AI 会在匹配触发词时自动加载。

### 方式 2：直接作为 prompt 使用
把 `SKILL.md` 的内容作为 system prompt 的一部分，
然后把用户数据粘进去就能跑。


---

## ⚠️ 使用限制

- 本 skill 是**娱乐 + 洞察**性质，不是专业心理咨询
- 涉及 PUA、家暴、自残等严肃议题 → 会自动拒绝进入模拟流程，建议寻求专业帮助
- 不对任何实际关系决策承担责任



> "你别管——
>  我有我自己恋爱的节奏。"
