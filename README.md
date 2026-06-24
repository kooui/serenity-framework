# Serenity Framework (白毛股神的供应链瓶颈分析框架)

[English](#english) | [中文](#中文)

<a name="english"></a>
## English

### 📖 Description

A supply-chain bottleneck investment framework based on Serenity's (@aleabitoreddit) trading methodology. Serenity is a semiconductor day trader who uses supply chain analysis to find investment opportunities.

**Core Philosophy:**
> "The entire AI industry will likely be bot-driven, cloud-dependent, and memory-starved. The bottleneck is not demand, it's supply chain."

**Key Features:**
- ✅ 5-Layer Analysis Framework (Macro → Bottleneck → Company → Position → Execution)
- ✅ Supply Chain Mapping (from downstream to upstream)
- ✅ Position Sizing Framework (Core/Swing/Lottery)
- ✅ Risk Management (Stop-Thesis, not Stop-Loss)
- ✅ Day Trading Strategy (around core positions)

### 🚀 Quick Start

#### 1. Understand the 5-Layer Framework

```
Layer 1: Macro Capex Guidance (demand ceiling)
   ↓
Layer 2: Bottleneck Identification (find the narrowest link)
   ↓
Layer 3: Company Screening (which companies capture margin)
   ↓
Layer 4: Position Sizing (Core/Swing/Lottery)
   ↓
Layer 5: Day Trading Execution (around core positions)
```

For details, see [framework/](framework/).

#### 1.5 Visual Overview

![Serenity Framework Pyramid](framework_pyramid.svg)

#### 2. Apply to a Stock

Use the [analysis template](examples/template.md) to analyze any stock:

1. Draw the supply chain map
2. Identify the bottleneck
3. Screen companies
4. Size your position
5. Set thesis validation checkpoints

#### 3. Study the Case

Read the [$AAOI Case Study](examples/aaoi_case_study.md) to see how Serenity applied this framework in practice.

### 📊 Framework Overview

| Layer | Focus | Key Question |
|-------|-------|--------------|
| 1 | Macro Capex | What's the demand ceiling? |
| 2 | Bottleneck | Where is the narrowest link? |
| 3 | Company | Which company captures margin? |
| 4 | Position | How much to allocate? |
| 5 | Execution | When to buy/sell? |

### ⚠️ Risk Warning

**Serenity's words:**
> "My framework is high-risk. I've had 50% drawdowns. If you can't handle volatility, don't copy me."

This framework is:
- ✅ Suitable for experienced investors with risk tolerance
- ❌ NOT suitable for risk-averse investors
- ❌ NOT suitable for passive investing

### 📁 Project Structure

```
serenity-framework/
├── README.md                    # This file
├── LICENSE                      # MIT License
├── framework/                   # Framework documentation
│   ├── layer1_macro.md         # Macro Capex Guidance
│   ├── layer2_bottleneck.md    # Bottleneck Identification
│   ├── layer3_company.md       # Company Screening
│   ├── layer4_position.md      # Position Sizing
│   └── layer5_execution.md     # Execution Strategy
├── examples/                    # Case studies
│   ├── aaoi_case_study.md      # $AAOI complete analysis
│   └── template.md             # Analysis template
└── docs/                        # Additional documentation
    ├── methodology.md          # Methodology explanation
    └── serenity_background.md  # Serenity's background
```

### 📝 License

MIT License

---

<a name="中文"></a>
## 中文

### 📖 简介

基于 Serenity (@aleabitoreddit) 交易方法的供应链瓶颈投资框架。Serenity 是一位半导体日内交易员，使用供应链分析寻找投资机会。

**核心理念：**
> "整个 AI 行业将是机器人驱动、云依赖、内存饥渴的。瓶颈不是需求，而是供应链。"

**核心功能：**
- ✅ 五层分析框架（宏观 → 瓶颈 → 公司 → 仓位 → 执行）
- ✅ 供应链地图（从下游到上游）
- ✅ 仓位管理框架（核心/摆动/彩票）
- ✅ 风险管理（Stop-Thesis，不是 Stop-Loss）
- ✅ 日内交易策略（围绕核心仓位）

### 🚀 快速开始

#### 1. 理解五层框架

```
第一层：宏观 Capex 指引（需求上限）
   ↓
第二层：瓶颈识别（找到最窄的环节）
   ↓
第三层：公司筛选（哪些公司捕获利润）
   ↓
第四层：仓位管理（核心/摆动/彩票）
   ↓
第五层：执行策略（何时买卖）
```

详细说明请查看 [framework/](framework/) 目录。

#### 1.5 可视化概览

![Serenity 框架金字塔](framework_pyramid.svg)

#### 2. 应用到股票

使用[分析模板](examples/template.md)分析任何股票：

1. 画出供应链地图
2. 识别瓶颈环节
3. 筛选公司
4. 确定仓位大小
5. 设置 thesis 验证检查点

#### 3. 学习案例

阅读[$AAOI 案例分析](examples/aaoi_case_study.md)，看看 Serenity 如何在实践中应用这个框架。

### 📊 框架概览

| 层级 | 重点 | 关键问题 |
|------|------|----------|
| 1 | 宏观 Capex | 需求上限是多少？ |
| 2 | 瓶颈识别 | 最窄的环节在哪里？ |
| 3 | 公司筛选 | 哪家公司捕获利润？ |
| 4 | 仓位管理 | 分配多少仓位？ |
| 5 | 执行策略 | 何时买卖？ |

### ⚠️ 风险警告

**Serenity 的原话：**
> "我的框架是高风险的。我曾经有 50% 的回撤。如果你无法承受波动性，不要复制我。"

这个框架：
- ✅ 适合有风险承受能力的经验丰富的投资者
- ❌ 不适合风险厌恶型投资者
- ❌ 不适合被动投资

### 📁 项目结构

```
serenity-framework/
├── README.md                    # 本文件
├── LICENSE                      # MIT 许可证
├── framework/                   # 框架文档
│   ├── layer1_macro.md         # 宏观 Capex 指引
│   ├── layer2_bottleneck.md    # 瓶颈识别
│   ├── layer3_company.md       # 公司筛选
│   ├── layer4_position.md      # 仓位管理
│   └── layer5_execution.md     # 执行策略
├── examples/                    # 案例分析
│   ├── aaoi_case_study.md      # $AAOI 完整分析
│   └── template.md             # 分析模板
└── docs/                        # 额外文档
    ├── methodology.md          # 方法论说明
    └── serenity_background.md  # Serenity 背景介绍
```

### 📝 许可证

MIT 许可证

---

## ⭐ Star History

If this project helps you, please consider giving it a star!

如果这个项目对你有帮助，请考虑给它一个星标！
