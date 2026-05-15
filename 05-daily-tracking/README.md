# 📡 每日事件追踪与分析

> 核心目标：记录重要经济事件，分析影响面，训练"事件 → 推演 → 验证"的能力。

---

## 工作流

```mermaid
graph LR
    A[事件发生] --> B[记录事实]
    B --> C[分析影响链]
    C --> D[预判市场反应]
    D --> E[观察实际结果]
    E --> F[复盘偏差原因]
    F --> G[更新认知框架]
```

## 目录结构

```
05-daily-tracking/
├── README.md              ← 你在这里
├── indicators/            ← 重要经济指标解读模板
│   ├── cpi.md
│   ├── pmi.md
│   ├── employment.md
│   └── ...
├── central-banks/         ← 央行会议纪要与解读
│   ├── fed-fomc.md
│   ├── pboc.md
│   └── ...
├── templates/             ← 日志模板
│   ├── daily-template.md
│   └── weekly-template.md
└── 2026/
    ├── 05/
    │   ├── 2026-05-14.md  ← 每日记录
    │   └── ...
    └── ...
```

## 追踪什么？

### 高优先级事件

| 类型 | 例子 | 影响面 |
|------|------|--------|
| 央行决议 | FOMC 加息/降息、PBOC 降准 | 全资产 |
| 重要数据 | 非农就业、CPI、PMI | 利率预期 → 资产价格 |
| 地缘事件 | 战争、制裁、贸易摩擦 | 避险资产、供应链 |
| 政策变化 | 财政刺激、监管新规 | 相关行业/市场 |
| 市场异动 | 单日暴跌 >3%、流动性危机 | 情绪传染 |

### 日常关注指标

```mermaid
graph TB
    subgraph "每日看"
        D1[美股三大指数]
        D2[美元指数 DXY]
        D3[10Y 美债收益率]
        D4[黄金/原油]
        D5[BTC]
        D6[A 股主要指数]
        D7[北向资金]
    end
    
    subgraph "每周看"
        W1[初请失业金]
        W2[央行公开市场操作]
        W3[资金利率 DR007]
    end
    
    subgraph "每月看"
        M1[CPI / PPI]
        M2[PMI]
        M3[社融/M2]
        M4[非农就业]
    end
    
    subgraph "每季看"
        Q1[GDP]
        Q2[企业财报季]
        Q3[央行货币政策报告]
    end
```

## 分析模板

每条事件记录包含：

1. **事实** (What)：发生了什么？数据是多少？
2. **预期差** (vs Expectation)：比市场预期好还是差？
3. **影响链** (Impact Chain)：顺着传导链推演
4. **市场反应** (Market Reaction)：实际怎么走的？
5. **我的判断** (My Take)：我怎么看？
6. **后续跟踪** (Follow-up)：接下来关注什么？

---

## 数据源推荐

| 数据 | 免费来源 | 付费来源 |
|------|----------|----------|
| 美国经济数据 | [FRED](https://fred.stlouisfed.org/) | Bloomberg |
| 中国经济数据 | 国家统计局、央行官网 | Wind、CEIC |
| 全球市场行情 | TradingView、Yahoo Finance | Bloomberg |
| 加密货币 | CoinGecko、Glassnode (部分免费) | Nansen |
| 财经日历 | Investing.com、金十数据 | — |
| 央行声明 | 各央行官网 | — |

---

→ 开始记录：[2026 年 5 月](./2026/05/)
