# 🏭 Supplier Quality Analysis Dashboard 2014

## 📊 Project Overview

This project involved developing a comprehensive Power BI dashboard to evaluate and benchmark supplier performance in terms of **product quality**, **delivery efficiency**, and **defect rates**. It helps supply chain and quality control teams to:

- Identify top and bottom-performing suppliers
- Pinpoint materials and defects responsible for major losses
- Optimize supplier selection and quality assurance practices

> 🔍 Focused KPIs include defected quantity, downtime hours, and defect categories by type, material, and geography.

---

## 👥 Team Role

As part of a collaborative team project, I worked on:
- Data modeling and DAX measures in Power BI
- Visual storytelling and layout design
- Extracting insights for supplier benchmarking
- Highlighting top defect types and suppliers

---

## 🎯 Objectives

- Monitor supplier performance using quality metrics
- Visualize defect distribution by material, plant, and vendor
- Identify root causes (defect types, materials, categories)
- Support data-driven decisions in supplier selection

---

## 📌 Key Metrics & Visuals

| Metric                  | Description                                     |
|-------------------------|-------------------------------------------------|
| 📦 Defected Quantity     | 2.8M units (↑152.5% vs last month)              |
| ⏱️ Downtime Hours        | 106 hours (↓90.5% vs last month)               |
| 🚩 Top Defect Types      | Not Certified, Out of Spec, Incorrect Dimensions |
| 🏭 Defect by Plant       | Map-based and bar visualizations by location   |
| 🧪 Defect by Material    | Tree map showing electrolytes, cartons, etc.   |
| 🧰 Defect by Category    | Impact, No Impact, Rejected                    |
| 📉 Worst 3 Vendors       | Hotity, O-ace, Plextech                        |
| 💡 Worst Defects         | Dirty Containers, Split Hinges, Bad Dimensions |

---

## 🌐 Dashboard Features

- ✅ **Interactive Filters** (Defect Qty / Downtime toggle)
- 🌍 **Geospatial Map** of defected units per plant
- 🧾 **Treemaps & Bar Charts** to drill down material types and defect categories
- 📆 **Comparative Analysis** to previous month

<img width="739" alt="Dashboard8" src="https://github.com/user-attachments/assets/932fd949-8d68-4f1d-80b4-dbb79a803a87" />
<img width="753" alt="Dashboard9" src="https://github.com/user-attachments/assets/295e0c00-63fc-4950-becd-5040f1c349af" />


---

## 🛠️ Tools Used

- **Power BI** – Interactive dashboards, DAX formulas
- **Microsoft Excel** – Data cleaning and transformation
- **OpenStreetMap** – Map visual integration
- **DAX Measures** – For KPI calculations and trends

---

## 🧮 DAX Measures Examples

```DAX
DefectedQty = SUM('Defects'[Quantity])
DowntimeHours = SUM('Production'[Downtime])
DefectRate = DIVIDE(SUM('Defects'[Quantity]), SUM('Orders'[Total]))


## 🔍 Data Source

Datasource are exist in the repositry files 
---

## 📬 Contact

For questions, feedback, or collaboration:
**Mohamed Rabea** – [LinkedIn](https://www.linkedin.com/in/mohamed-rabea-991373261/) | [Email](mailto:mhmdrby769@email.com)



