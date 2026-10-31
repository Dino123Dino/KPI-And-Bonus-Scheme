Telecom Sales Incentive & KPI Commission Model

Project Overview
This project presents an automated Excel-based operational model designed to calculate sales commissions, performance points, and KPI-driven bonuses for telecom sales representatives. By structuring product catalogs, transaction logs, and dynamic KPI logic, this tool streamlines the monthly incentive payout calculation and performance tracking.

---

Tech Stack & Tools
Microsoft Excel: Advanced lookup formulas, logical functions, dynamic tables, data structuring, and KPI performance modeling.
Git & GitHub: Documentation and repository management.

---

Model Architecture & Structure
The Excel workbook is organized into four dedicated operational tabs:

Package: Product catalog storing core telecom offerings (Mobile, Fixed, TV, Fixed Line) alongside value-added services (Add-ons) and standard pricing.
Sale Type: Reference matrix mapping transaction categories (Gross Adds, Upgrades, Pre2Post migrations, Activations) and device price bands to specific monetary bonuses and sale points.
Bonus Scheme: Transaction-level sales ledger automatically assigning commission payouts and points per contract ID and sold device.
KPI Target: Executive calculation engine evaluating agent operational metrics (Customer Review Score, Average Handling Time - AHT, Extra Time, and Sale Points) against MIN/MAX performance caps (70%–130%) to generate the final monthly commission payout.

---

Key Features & Calculations
Dynamic Commission Mapping: Automatic pairing of sold products and transaction types with defined monetary incentive tiers.
Performance Threshold Capping: Implementation of MIN/MAX operational limits (70% minimum threshold, 130% payout cap) to maintain budget control.
Combined Incentive Payout: Seamless aggregation of direct sales commission (Total Incentive) and operational target achievement (Performance Bonus) into a final compensation total.

---

Repository Structure
excel — Workbook file (`Telecom_Incentive_KPI_Model.xlsx`) containing full logic, catalogs, and dynamic formulas.