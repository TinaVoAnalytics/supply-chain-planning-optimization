# 📊 Power BI Dashboard — Supply Chain Planning & Operations Intelligence

This folder contains four Power BI dashboard screenshots and two data-model screenshots for Project #4. The dashboard integrates **12 Gold analytical tables and 4 optimization scenario tables** to support demand, capacity, allocation, and scenario analysis.

## 📊 Dashboard Report Pages

### 1. Executive S&OP Overview

![Executive S&OP Overview](01_Executive_S%26OP_Overview.png)

Monitors planned demand, modeled fulfillment, processing hours, implied overtime, and planning trends. 

### 2. Capacity & Bottlenecks

![Capacity & Bottlenecks](02_Capacity_Bottlenecks.png)

Identifies machine-level capacity pressure, remaining capacity, and constrained machine-period combinations.

### 3. Demand & Allocation

![Demand & Allocation](03_Demand_Allocation.png)

Examines product demand, modeled fulfillment, and workload distribution across packing machines.

### 4. Scenario Analysis

![Scenario Analysis](04_Scenario_Analysis.png)

Compares **Min Processing, Min Overtime, and Threshold Capacity** to evaluate processing-hour, overtime, and machine-allocation trade-offs.

---

## 🏗️ Power BI Data Model

![Power BI Data Model](05_Data_Model.png)

**12 Gold Analytical Tables:** 4 Dimensions • 4 Facts • 4 Bridges

**4 Optimization Scenario Tables:** `machine_period_summary` • `scenario_allocations` • `scenario_assumptions` • `scenario_summary`

### 🔗 Relationship Details

![Relationship Details](06_Relationship_Details.png)

The analytical model supports integrated reporting across demand, products, machines, planning periods, capacity, and optimization scenarios.

---

## 🔍 Key Findings

- **100% modeled fulfillment:** All three scenarios allocate 3,071,692 meters of planned demand.
- **Localized capacity pressure:** Threshold Capacity shows 62.31% aggregate permitted-capacity utilization, while 14 machine-period combinations reach 100%.
- **Resource dependency:** Machine 921 reaches 100% modeled utilization across P3–P8 under Threshold Capacity.
- **Scenario trade-offs:** Different optimization objectives change processing hours, implied overtime, and machine-level workload distribution.

---

[⬅️ Back to Main Project README](../README.md)
