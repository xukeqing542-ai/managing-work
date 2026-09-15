# 徐苛清｜ERP Business Finance Model

**Budget · Forecast · PVM · Cash Flow · Management Dashboard**

> 一个基于校内 ERP 实训扩展与个人建模的 Business Finance / FP&A 可复算作品，用于展示预算编制、预算跟踪、经营差异分析、现金流联动及管理层表达能力。

## Business Question

如何把业务端的**销量、价格、产品组合、成本、资本开支和营运资金变化**，转化为可解释的收入、毛利和现金流结果，并进一步支持预算跟踪与经营决策？

## Model Structure

模型按 12 个月搭建，并串联：

**Volume → Price → Revenue → Variable / Fixed Cost → Gross Profit → CapEx → Working Capital → Ending Cash**

同时保留月度 Budget、Actual、Variance 与经营驱动指标，便于追踪预算执行情况。

## Key Outputs

| Metric | Result |
|---|---:|
| Annual Budget Revenue | RMB 3,672,000 |
| Annual Actual Revenue | RMB 3,642,495.53 |
| Revenue Variance | RMB -29,504.47 |
| Annual Budget Gross Profit | RMB 1,031,771 |
| Annual Actual Gross Profit | RMB 1,012,733.43 |
| Gross Profit Variance | RMB -19,037.57 |
| Ending Cash | RMB 1,189,243.43 |

## Analysis Modules

### 1. Budget vs Actual
- 比较月度预算与实际收入、毛利及现金表现。
- 快速定位偏差月份与偏差方向，为管理层跟踪预算完成情况提供结构化输入。

### 2. Price-Volume-Mix (PVM)
- 将收入变化拆分为 **Price / Volume / Mix** 驱动。
- 避免仅停留在“收入下降/上升”，进一步解释变化由价格、销量还是产品组合造成。

### 3. Gross Profit Bridge
- 将收入与成本变化连接到毛利结果。
- 用于判断收入增长是否真正转化为利润改善，并识别成本端压力。

### 4. Working Capital & Cash Flow
- 将应收、应付、库存等营运资金变量与经营现金联动。
- 结合 CapEx 和经营结果滚动跟踪 Ending Cash，训练利润与现金流的双重视角。

### 5. Management Dashboard
- 以月度收入、预算差异、毛利和现金为核心 KPI 形成经营看板。
- 输出逻辑遵循：**结果 → 驱动 → 风险 → 建议**。

## Tools

- **Excel:** PivotTable, XLOOKUP/VLOOKUP, SUMIFS/COUNTIFS, scenario analysis, charts
- **Power BI / Power Query:** basic dashboard and data-preparation concepts
- **Python / AI:** used as auxiliary tools for repetitive data processing, formula/code drafting and validation support

## What This Demonstrates

- 年度预算与月度预算跟踪
- 经营分析与财务BP思维
- Budget vs Actual / PVM / Gross Profit Bridge
- 营运资金与现金流分析
- 数据敏感性与管理层表达
- 从“业务问题”到“财务指标”再到“行动建议”的转换能力

## Project Boundary

本作品为**校内 ERP 实训扩展 + 个人独立建模**，数据为模拟经营数据，用于展示财务分析方法、模型结构和问题解决能力，不代表真实企业生产数据或真实雇主项目。

---

**Candidate:** Xu Keqing / 徐苛清  
**Target roles:** Financial Analysis · FP&A · Business Finance · Finance BP
