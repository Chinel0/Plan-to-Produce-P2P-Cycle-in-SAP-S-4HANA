# 🚲 Plan-to-Produce (P2P) Cycle in SAP S/4HANA – Global Bike Inc. Case Study

This project simulates the complete **Plan-to-Produce (P2P)** business process cycle within SAP S/4HANA using the fictional company Global Bike Inc. The scenario demonstrates how a production order is planned, executed, and settled — from sales forecasting and demand planning to order settlement and variance analysis.

---

## 📑 Table of Contents
- [🎯 Project Objective](#-project-objective)
- [🏢 Business Case](#-business-case)
- [🔧 Process Overview](#-process-overview)
- [🧩 SAP Tools & Modules Used](#-sap-tools--modules-used)
- [📊 Key Screens & Evidence](#-key-screens--evidence)
- [📈 Results & Insights](#-results--insights)
- [🧠 Learnings & Takeaways](#-learnings--takeaways)
- [📎 Appendix](#-appendix)

---

## 🎯 Project Objective

To simulate and document the end-to-end production process in SAP S/4HANA — covering planning, execution, cost monitoring, and production order settlement — with real business logic applied to a manufacturing scenario.

---

## 🏢 Business Case

**Company**: Global Bike Inc.  
**Product**: Men’s Off-Road and Deluxe Touring Bicycles  
**Challenge**: The company must efficiently manage bicycle production while balancing material requirements, machine capacity, and labor, ensuring timely delivery and minimal cost variance.

---

## 🔧 Process Overview

This project follows the full **Plan-to-Produce (P2P)** process:

1. **Sales & Operations Planning (SOP)**  
   → Forecasted demand generated for finished bicycles  
2. **Material Requirements Planning (MRP)**  
   → System checks stock/requirements and generates procurement proposals  
3. **Production Order Creation**  
   → Orders scheduled based on BOM and routing  
4. **Execution & Confirmation**  
   → Shop floor tasks completed, order confirmed  
5. **Goods Movement**  
   → Finished bikes moved to stock  
6. **Order Settlement**  
   → Costs reviewed and settled, including variance analysis

---

## 🧩 SAP Tools & Modules Used

| Module         | SAP App / T-Code                  | Purpose                                  |
|----------------|-----------------------------------|-------------------------------------------|
| PP (Production Planning) | `MD01`, Fiori apps         | MRP run, routing, BOM, PIRs               |
| CO (Controlling)         | `KKBC_ORD`, `CO88`         | Order cost analysis & settlement          |
| MM (Materials Management) | `MB31`, `MIGO`            | Goods movement, inventory confirmation    |
| Fiori Launchpad          | P2P Tiles                  | MRP, Production Orders, Order Confirmation, Actual/Plan Analysis |

---

## 📊 Key Screens & Evidence

### 🛠️ Production Order Management
![Production Orders](assets/production_orders.png)  
Orders executed and delivered, showing progress % and issue logs.

---

### 💸 Actual vs Plan Cost Variance
![Cost Variance](assets/actual_plan_variance.png)  
- High variance due to underused planned services (e.g. subcontracting).
- Positive balance due to higher output delivery than planned.

---

### 🧭 Fiori Launchpad – Plan to Produce
![Fiori P2P Overview](assets/fiori_p2p_launchpad.png)  
Key entry points for BOM, routing, SOP planning, and MRP scheduling.

---

## 📈 Results & Insights

- ✅ **Total Orders Delivered**: 25
- ✅ **Storage Movement Completed**: 100%
- ⚠️ **Plan/Actual Cost Variance**:  
  - Labor: +28%  
  - SF Consumption: −86.5%  
  - Material Overhead: −100%
- 📦 **Final Balance**: +123% over planned cost due to excess settlement

---

## 🧠 Learnings & Takeaways

- Gained hands-on experience with **SAP P2P processes** from planning to cost control.
- Understood the **impact of real-time cost variance** in production operations.
- Practiced **capacity planning, MRP execution, BOM creation, routing**, and **cost analysis**.
- Strengthened understanding of **inter-module integration** across PP, MM, and CO.

---

## 📎 Appendix

| Screenshot              | Description                         |
|-------------------------|-------------------------------------|
| `production_orders.png` | Production orders and delivery logs |
| `actual_plan_variance.png` | Cost settlement and variance data |
| `fiori_p2p_launchpad.png` | Main SAP tiles for P2P process     |

---

> **🎓 Academic Context:**  
This project was completed as part of the ERP Systems and Management Accounting modules in my International Business Information Systems degree at Furtwangen University.

> **🛠 Tools Used:**  
SAP S/4HANA | SAP Fiori | PP, MM, CO Modules | Excel

🙋‍♀️ Author & Contact
Chinelo Lydia Nweke
📍 Business Informatics Student | SAP Learner | Data Enthusiast
🔗 LinkedIn | Portfolio | GitHub
📬 Email: Nwekecl16046@gmail.com
