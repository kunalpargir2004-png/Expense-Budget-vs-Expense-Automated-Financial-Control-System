📊 Project: Expense Budget vs Expense – Automated Financial Control System

I recently developed a fully automated Expense Budget & Profit Monitoring Dashboard designed to simulate a real-world corporate financial control environment.
This solution integrates structured data modeling, Power Query transformation, Power Pivot relationships, KPI tracking, and VBA-driven email automation into a single intelligent reporting framework.

🔎 Business Problem Solved
In many organizations:
Budget overruns are detected late
Profit thresholds are not proactively monitored
Reports require manual consolidation
Email communication is repetitive and time-consuming
This project eliminates manual dependency and builds a self-refreshing financial control system.

🧠 Data Architecture
Dimension Tables (4):
Dim Date
Dim Department
Dim Category
Dim Region
Fact Tables (3):
Fact Expense
Fact Sales
Fact Expense Budget
Structured using a proper Star Schema Model inside Power Pivot to ensure scalable analytics.

⚙️ Automation Logic
✔ Expense % of Budget calculated dynamically
 ✔ Threshold Rule: Expense must not exceed 75% of total allocated budget
 ✔ Profit % calculated from Sales & Expense
 ✔ Profit Threshold: Minimum 15%
Conditional Alerts:
If Expense > 75% → 🚨 “Budget is Above the Limit – Attention Required”
If Expense ≤ 75% → ✅ “Expense in Limit”
If Profit < 15% → ⚠ “Profit is Low – Attention Required”
If Profit ≥ 15% → ✅ “Healthy Profit”
KPIs auto-update instantly when raw data is refreshed.

📩 Smart Email Automation
Integrated VBA button:
Opens Outlook automatically
Pre-populates dynamic alert message
Pulls live KPI values (Expense % & Profit %)
Ensures zero manual drafting
This bridges reporting with real-time executive communication.

📩 Smart Email Automation
Integrated VBA button:
Opens Outlook automatically
Pre-populates dynamic alert message
Pulls live KPI values (Expense % & Profit %)
Ensures zero manual drafting
This bridges reporting with real-time executive communication.

🛠 Tools & Skills Used
Advanced Excel
Power Query (ETL logic)
Power Pivot (Data Modeling)
DAX Measures
VBA Automation
Financial KPI Design
Threshold-based Alert Systems

💼 Corporate Impact
Strengthens financial governance
Enables proactive decision-making
Reduces reporting turnaround time
Minimizes human error
Improves executive visibility

This project reflects how Excel, when combined with data modeling and automation, can function as a lightweight ERP-style monitoring solution for budget control.
