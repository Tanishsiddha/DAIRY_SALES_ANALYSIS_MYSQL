# Dairy Supply Chain Data Engineering & Advanced Analytics

An end-to-end data analytics and database design project mapping agricultural outputs, shelf-life vulnerability risk vectors, and multi-brand distribution metrics in the dairy sector.

## 📁 Repository Structure
* `dairy_dataset.csv`: Clean structured master transactional ledger tracking 23 attributes of logistics and product parameters.
* `dairy_data.sql`: Production-grade database schema script featuring 22 tailored analytical queries tracking inventory buffers, expiration risk, and net profits.

## ⚡ Core Insights & Use Cases
1. **Automated Replenishment**: Identifies structural stock deficits where `Quantity_in_Stock` falls below safety metrics (`Min_Stock_Threshold`).
2. **Waste Mitigation**: Locates non-liquidated expired products through custom time-delta operations comparing system timestamps against `Expiration_Date`.
3. **Margin Contribution Analysis**: Shifts focus from surface-level gross revenue tracking to true net profitability metrics using actual cost-of-goods-sold differences.

## 🛠️ Tech Stack
* **SQL Dialect**: MySQL / PostgreSQL Relational Engine
* **Data Models**: Time Series Sales Logs, Cross-Sectional Farm Output Matrices 
