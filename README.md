# 📊 GlobalTech 客户费用及异常扣款流程优化方案 (Case Study)

> 本项目为一个可交互的在线 Case Study 展示页，专注于渠道财务（Channel Finance）中的存量扣款清理、内控体系重构（DOA 矩阵）与 Power BI 可视化看板设计。

👉 **[点击此处在线预览演示文稿 (Live Demo)](https://dayna77.github.io/commercial-finance-deduction-optimization/)**

---

## 🎯 项目背景与核心痛点 (Executive Summary)

针对欧洲渠道销售中出现的 **145 万欧元** 历史异常扣款积压问题，系统性诊断出以下三大根因：
1. **数据断链**：SAP 系统与 Forecast/Policy 数据未打通，缺乏统一追踪主键。
2. **缺乏防重**：缺乏事前 Promo ID 预警机制，导致重复立项与二次套扣。
3. **权责模糊**：缺乏清晰的双线审批授权矩阵 (DOA)，小额与大额处理效率低下。

---

## 🛠️ 三段式治理路径 (Project Architecture)

* **Phase 1: Quick Win (存量止血)**
  * 以 `Customer ID + Invoice ID + SKU` 为数据主键，拉通四大系统。
  * 制定 4 条分类核销与追讨路径，设置 14 天限期响应机制。
* **Phase 2: Process Control (内控重构)**
  * 设置全生命周期“三道锁”：源头锁（Promo ID）、财务锁（Accrual Ceiling）、核销锁。
  * 构建 Sales & Finance 双线 DOA 授权矩阵，实现 80% 小额预算自动化流转。
* **Phase 3: Enablement (数字化赋能)**
  * 搭建 Power BI 仪表盘，实现 GM（商业视角）与 FM（风控视角）的“一屏双读”。

---

## 💻 技术栈与实现 (Tech Stack)

* **前端展示**：HTML5, CSS3 (CSS Variables, Flexbox/Grid), Modern JavaScript
* **交互设计**：内嵌双模式切换（在线实时编辑 / 预览模式），响应式幻灯片布局，支持一键 PDF 导出
* **商业智能**：Power BI 逻辑模型架构

---

## 👤 作者与版权说明 (Notice)

* **作者**：Dayna
* **说明**：本仓库内容仅作为个人作品集 (Portfolio) 展示使用，文中涉及的公司名称、财务数据及敏感客户名称均已做脱敏与模糊化处理。
