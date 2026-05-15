# 🔧 投研方法论 | Methodology

> 核心目标：掌握分析工具和思维框架，能独立做出投资判断。

---

## 方法论全景

```mermaid
graph TB
    subgraph "自上而下 Top-Down"
        A1[宏观经济分析] --> A2[行业选择]
        A2 --> A3[个股/资产选择]
    end
    
    subgraph "自下而上 Bottom-Up"
        B1[发现好公司] --> B2[验证行业逻辑]
        B2 --> B3[确认宏观环境]
    end
    
    subgraph "量化方法 Quant"
        C1[因子模型] --> C2[回测验证]
        C2 --> C3[组合构建]
    end
    
    A3 --> D[投资决策]
    B3 --> D
    C3 --> D
    D --> E[风险管理]
    E --> F[持续跟踪与调整]
```

---

## 模块导航

| 目录 | 内容 | 适合阶段 |
|------|------|----------|
| [valuation/](./valuation/) | 估值方法（DCF、相对估值、DDM） | Level 2-3 |
| [technical/](./technical/) | 技术分析基础（趋势、量价） | Level 2 |
| [quant/](./quant/) | 量化入门（因子、回测） | Level 3-4 |
| [risk/](./risk/) | 风险管理（仓位、止损、相关性） | Level 2+ |
| [frameworks/](./frameworks/) | 经典框架（美林时钟、全天候等） | Level 2-3 |

---

## 核心框架速览

### 美林时钟 (Merrill Lynch Clock)

```mermaid
graph TB
    subgraph "经济周期与资产轮动"
        A["🌱 复苏<br/>GDP↑ CPI↓<br/>→ 股票"] --> B["☀️ 过热<br/>GDP↑ CPI↑<br/>→ 大宗商品"]
        B --> C["🍂 滞胀<br/>GDP↓ CPI↑<br/>→ 现金"]
        C --> D["❄️ 衰退<br/>GDP↓ CPI↓<br/>→ 债券"]
        D --> A
    end
```

### 达里奥全天候策略 (All Weather)

```mermaid
pie title 全天候配置比例
    "长期国债 40%" : 40
    "股票 30%" : 30
    "中期国债 15%" : 15
    "大宗商品 7.5%" : 7.5
    "黄金 7.5%" : 7.5
```

核心思想：不预测未来，而是**在任何经济环境下都能活下来**。

### 估值三板斧

| 方法 | 适用 | 核心逻辑 |
|------|------|----------|
| DCF (现金流折现) | 稳定盈利公司 | 公司值 = 未来所有现金流的现值 |
| 相对估值 (P/E, P/B) | 有可比公司时 | 和同行比贵不贵 |
| DDM (股利折现) | 高分红公司 | 公司值 = 未来所有分红的现值 |

---

## 学习路径建议

1. 先学 [frameworks/](./frameworks/) → 建立全局观
2. 再学 [valuation/](./valuation/) → 会给资产定价
3. 然后 [risk/](./risk/) → 知道怎么保护自己
4. 最后 [quant/](./quant/) → 用数据验证想法
5. [technical/](./technical/) 选学 → 辅助择时（不要迷信）
