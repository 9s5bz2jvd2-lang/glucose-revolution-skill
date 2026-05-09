# 🩺 控糖革命 Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/yourusername/glucose-revolution-skill)
[![Platform](https://img.shields.io/badge/platform-WorkBuddy%20%7C%20灵台%20AI-green.svg)]()

> 基于《控糖革命》(Glucose Revolution) 的血糖管理教学专家 Skill
> 
> 支持**自然对话交互**，像和专家聊天一样获得个性化的血糖管理建议

---

## ✨ 核心特性

### 🗣️ 对话式交互
- **自测评估** — 通过对话完成症状自测（30秒）
- **症状咨询** — 描述困扰，获得针对性建议
- **场景指导** — 聚餐、便利店、外食等具体场景
- **跟进反馈** — 尝试后反馈效果，调整方案
- **多轮对话** — 记住上下文，持续优化建议

### 📚 知识深度
- **80个TKP** — 完整的控糖知识体系
- **三级教学** — 初学者/进阶者/专家级自动适配
- **10个窍门** — 从饮食顺序到餐后运动的实用技巧
- **三条因果链** — 疾病链、果糖链、策略链

---

## 🚀 快速开始

### 安装

```bash
# 方式1：自动安装
git clone https://github.com/yourusername/glucose-revolution-skill.git
cd glucose-revolution-skill
bash install.sh  # 或 Windows 双击 install.bat

# 方式2：手动复制到 WorkBuddy
cp -r glucose-revolution-skill ~/.workbuddy/skills/custom/

# 方式3：手动复制到 灵台 TUI
cp -r glucose-revolution-skill ~/.lingtai/custom/
```

### 使用

安装后，像聊天一样和 Skill 对话：

```
你：你好

Skill：你好，我是控糖导师。我可以帮你：
• 做血糖波动自测（30秒）
• 针对你的情况给出控糖建议
• 解答具体食物/场景的控糖方法

想从哪里开始？或者直接告诉我你的困扰。
```

---

## 💬 对话示例

### 示例1：餐后困倦
```
你：我总是午饭后很困

Skill：这是典型的血糖波动症状...
[解释原因 + 立即改善建议 + 预期效果]

你：我一般吃盖浇饭

Skill：盖浇饭可以这样吃：先吃菜，最后吃米饭...
```

### 示例2：减肥困难
```
你：想减肥但少吃多动也不瘦

Skill：这可能和胰岛素有关...
[解释机制 + 突破点 + 具体行动]

你：早餐吃什么？

Skill：早餐改为鸡蛋+牛油果...
```

### 示例3：自测评估
```
你：我想做个自测

Skill：以下7个症状，你中了几个？
1. 餐后困倦
2. 饿怒症
3. 对甜食渴望...

你：1, 2, 4

Skill：你命中了3项...
[评估结果 + 建议路径]
```

更多对话示例见 [EXAMPLES.md](EXAMPLES.md)

---

## 📖 文档

| 文档 | 说明 |
|------|------|
| [QUICK_REFERENCE.md](QUICK_REFERENCE.md) | 5分钟上手，一日示范，症状-对策速查 |
| [EXAMPLES.md](EXAMPLES.md) | 10个完整对话示例 |
| [CONVERSATION_GUIDE.md](CONVERSATION_GUIDE.md) | 对话流程设计，交互模式说明 |
| [METHODOLOGY.md](METHODOLOGY.md) | TKP→Skill转化方法论 |

---

## 🎯 能力清单

### 症状-对策映射

| 症状 | Skill 回应 |
|------|-----------|
| 餐后困倦 | 饮食顺序 + 餐前醋 + 饭后运动 |
| 减肥困难 | 胰岛素机制 + 平稳早餐 + 停止少食多餐 |
| 皮肤痘痘 | 戒糖饮料 + 饮食顺序 + Omega-3 |
| 饿怒症 | 平稳早餐 + 咸香零食替代 |
| 脑雾 | 饮食顺序 + 避免血糖过山车 |

### 场景化指导

- **聚餐/应酬** — 先吃菜、喝酒前垫肚子、选择干型葡萄酒
- **便利店** — 茶叶蛋+蔬菜沙拉、烤鸡腿+关东煮
- **想吃甜食** — 放在正餐后吃、先吃蛋白质缓冲
- **早餐设计** — 鸡蛋+牛油果+少量全麦

---

## 🔑 触发关键词

- "控糖" / "血糖" / "血糖峰值"
- "饮食顺序" / "胰岛素" / "葡萄糖"
- "餐后困倦" / "饿怒症" / "减肥困难"
- "怎么控糖" / "控糖建议" / "控糖自测"

---

## 📂 文件结构

```
glucose-revolution-skill/
├── skill.yaml              # Skill 配置
├── system_prompt.md        # 核心系统提示词
├── README.md               # 本文件
├── QUICK_REFERENCE.md      # 快速参考卡
├── CONVERSATION_GUIDE.md   # 对话交互指南
├── EXAMPLES.md             # 对话示例集
├── METHODOLOGY.md          # 方法论文档
├── install.sh              # Linux/Mac 安装脚本
├── install.bat             # Windows 安装脚本
├── LICENSE                 # MIT 许可证
└── .gitignore              # Git 忽略文件
```

---

## 🧠 知识来源

- **书名**：《控糖革命》(Glucose Revolution)
- **作者**：Jessie Inchauspé
- **TKP数量**：80个教学知识点
- **总字符数**：约 270,000 字符
- **方法论**：Teaching Meta-Methodology（改编自impersonate-meta）

---

## ⚠️ 免责声明

本 Skill 提供的建议基于《控糖革命》一书的研究成果，仅供参考，不构成医疗建议。如有健康问题，请咨询专业医生。

---

## 📄 许可证

[MIT](LICENSE) © 2025 WorkBuddy / 灵台 AI

---

## 🤝 贡献

欢迎提交 Issue 和 PR！

如果你有：
- 新的对话场景建议
- 控糖窍门的实践经验
- 教学方法的改进意见

都可以通过 Issue 分享。

---

## 🙏 致谢

- [《控糖革命》](https://www.amazon.com/Glucose-Revolution-Life-Changing-Power-Balancing/dp/1982179414) — Jessie Inchauspé 的突破性研究
- [impersonate-meta](https://github.com/huangzesen/impersonate-meta) — 方法论启发
- Teaching Meta-Methodology — 教材蒸馏方法论
