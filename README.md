# Excel-business-analytics-optimization
Advanced business analytics project utilizing the Excel Solver engine to run prescriptive optimization modeling (Linear Programming, Transportation, and Assignment networks). Features an automated One-Way Data Table sensitivity matrix to evaluate bottom-line risk and drive data-backed operational decisions.
# Corporate Optimization & Prescriptive Business Analytics (Excel)

## 📊 Project Overview
This project showcases an advanced administrative decision-making workflow using prescriptive analytics frameworks within Microsoft Excel. The analysis applies mathematical optimization, resource allocation algorithms, and risk sensitivity analysis to resolve operational bottlenecks and maximize corporate net income for a manufacturing and supply network.

---

## 🛠️ Software Tools & Technical Methodologies Used
To build these models, advanced features within the Microsoft Excel data ecosystem were utilized:
* **Optimization Engine:** Microsoft Excel Solver Add-in.
* **Algorithmic Model Settings:** Simplex LP (Linear Programming) for continuous linear constraints, and GRG Nonlinear/Evolutionary engines where applicable.
* **Integer Constraints:** Applied Binary (`bin`) parameters to establish strict boolean logic (`0` or `1`) for mutual exclusion.
* **Decision Calculations:** Integrated multi-variable array logic using structural syntax expressions like `=SUMPRODUCT()` to link matrix coefficients instantly.
* **What-If Simulation Engine:** Built-in Excel Data Table tools to compute rapid vertical substitutions.

---

## ⚙️ Core Analytical Frameworks & Case Studies

### 1. Linear Programming (Product Mix Optimization)
* **Objective:** Maximize weekly operational profits by identifying the optimal production volume combination of product lines under strict asset limitations.
* **Methodology:** Implemented the Excel Solver (Simplex LP) engine. Constrained parameters included raw material availability ceilings (1,200 gallons) and total manual production line labor hours (600 hours).
* **Business Outcome:** Determined an absolute optimal product yield, resulting in an optimized operational ceiling profit of $15,000/week.

### 2. Transportation Problem (Logistics Cost Minimization)
* **Objective:** Minimize total supply chain distribution costs across a multi-node shipping network.
* **Methodology:** Mapped out a network logistics matrix matching plant distribution output constraints (700 units total capacity) against variable regional warehouse consumption demands. 
* **Business Outcome:** Executed linear constraints inside Solver to discover the lowest-cost shipping route parameters, safeguarding supply metrics while minimizing overhead expenses.

### 3. Assignment Problem (Task Allocation Optimization)
* **Objective:** Achieve maximum machine-line efficiency by assigning specialized technical staff to appropriate machinery processing tracks at minimal cost.
* **Methodology:** Applied Binary Decision Variables (0 or 1 boolean parameters) to enforce mutually exclusive conditions (1 operator to exactly 1 processing machine line).
* **Business Outcome:** Resolved structural staffing overlaps and minimized workforce overhead costs through calculated algorithmic scheduling matching.

### 4. What-If Analysis (One-Way Data Table Sensitivity)
* **Objective:** Measure bottom-line vulnerability and structural profitability parameters under volatile raw material cost adjustments.
* **Methodology:** Constructed an automated One-Way Data Table dynamically referencing core multi-variable Net Income expressions (`=((B3*B4)+(C3*C4))-((B3+C3)*B27)`) by swapping vertical scenario inputs directly into the base cost cell (`B27`). 
* **Business Outcome:** Generated a strategic pricing sensitivity index to guide executive decisions, displaying automated profit fluctuations across a scale of alternative cost scenarios.

---

## 📁 Repository Structure & Deliverables
All final calculated analytical assets and visual proofs are hosted as individual files within this project folder:
* `Business_Analytics_Optimization_Models.xlsx`: The finalized multi-tab Excel workbook containing completed Solver configurations, operational grids, and working data table simulations.
* `Data_Table_Execution_Proof.png`: Step-by-step screenshot validating the successful runtime parameters and output of the What-If analysis sensitivity matrix.
