# MIS-Sales-SLA-Reconciliation-Suite
# Multi-Region Sales, SLA & Variance Reconciliation MIS Suite

## Project Overview
An automated Excel MIS reporting workbook designed to consolidate multi-region sales performance, monitor Turnaround Time (TAT) SLA compliance, and audit Purchase Order (PO) vs. Warehouse GRN discrepancies.

## Dashboard Preview
(Paste your screenshot here using Ctrl + V while editing on GitHub)

## Workbook Architecture
- **Executive_MIS_Dashboard:** Dynamic KPI summary cards (`SUM`, `AVERAGE`, `COUNTIF`), Regional & Monthly performance tables (`SUMIFS`, `COUNTIFS`, `AVERAGEIFS`), and a clustered column chart tracking Target vs. Actual Revenue.
- **Monthly_Sales_SLA_Data:** 240 regional order records (Jan–Jun 2026) with automated variance formulas, `IF`-based SLA status tracking (`Met` vs. `Breached`), and conditional formatting.
- **Variance_Reconciliation:** 40 Purchase Order vs. Warehouse GRN audit records automatically flagging `Matched`, `Short-Supply Variance`, and `Missing GRN / Duplicate` entries.
