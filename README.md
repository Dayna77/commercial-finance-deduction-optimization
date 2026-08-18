# 📊 GlobalTech 客户费用及异常扣款流程优化方案 | Channel Expense & Deduction Optimization

> 本项目为一个可交互的在线 Case Study 展示页，专注于渠道财务（Channel Finance）中的存量扣款清理、内控体系重构（DOA 矩阵）与 Power BI 可视化看板设计。
> An interactive web-based Case Study presentation focusing on Channel Finance backlog clearance, internal control matrix (DOA) restructuring, and Power BI visualization.

👉 **[🇨🇳 点击此处预览中文版 (Live Demo - Chinese)](https://dayna77.github.io/commercial-finance-deduction-optimization/)**  
👉 **[🇬🇧 Click here for English Version (Live Demo - English)](https://dayna77.github.io/commercial-finance-deduction-optimization/index_en.html)**

---

## 🎯 项目背景与核心痛点 (Executive Summary)

* **中文**：针对欧洲渠道销售中出现的 **145 万欧元** 历史异常扣款积压问题，诊断出数据断链、缺乏防重与权责模糊三大根因。
* **English**: Facing a **€1.45M historical deduction backlog** across EU channels, identifying three systemic root causes: disconnected cross-system data, lack of pre-event controls, and blurred accountability.

---

## 🛠️ 治理路径 (Strategic Roadmap)

* **Phase 1: Quick Win (存量止血 / Backlog Clearance)**
  * 以 `Customer ID + Invoice ID + SKU` 为统一主键，制定 4 条分类核销与追讨路径，设置 14 天限期响应机制。
* **Phase 2: Process Control (内控重构 / Internal Controls)**
  * 设置全生命周期“三道锁”（Promo ID 源头锁、Accrual Ceiling 财务锁、单次核销锁），构建 Sales & Finance 双线 DOA 授权矩阵。
* **Phase 3: Enablement (数字化赋能 / Digital Enablement)**
  * 搭建 Power BI 仪表盘，实现 GM（商业视角）与 FM（风控视角）“一屏双读”。

---

## 💻 技术栈与交互设计 (Tech Stack)

* **前端展示**：HTML5, CSS3 (Variables, Flexbox/Grid), Modern JavaScript
* **交互体验**：中英双语无缝切换、双模式（在线实时编辑 / 预览模式）、响应式 16:9 幻灯片布局、支持一键导出 PDF
* **商业智能**：Power BI DAX & 数据建模逻辑

---

## 👤 作者与版权说明 (Notice)

* **作者**：Dayna77
* **说明**：本仓库内容仅作为个人作品集 (Portfolio) 展示使用，文中数据及敏感信息均已做脱敏处理。
* **Disclaimer**: This repository is created exclusively for portfolio demonstration. All corporate names and financial data have been anonymized.
