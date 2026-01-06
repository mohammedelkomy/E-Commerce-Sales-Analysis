# 📈 End-to-End E-Commerce Data Analytics Pipeline

A sophisticated data project demonstrating the full lifecycle of business intelligence—transforming raw Turkish e-commerce transactional data into actionable executive insights using **Python** and **Power BI**.

---

## 🏗️ The Tech Stack
* **Data Engineering:** Python (Pandas, NumPy) for ETL and data sanitization.
* **Statistical Analysis:** Python (Matplotlib) for exploratory data analysis (EDA).
* **Business Intelligence:** Power BI (DAX, Data Modeling) for interactive reporting.

---

## 🛠️ Phase 1: Data Engineering & EDA (Python)
The analysis within `Analysis_Pytohn.ipynb` involved rigorous data manipulation to prepare for BI modeling:

* **ETL & Cleaning:** Automated the conversion of temporal data and handled multi-format features.
* **Advanced Feature Engineering:**
    * Synthesized a **Revenue** metric (`Unit_Price * Quantity`) to quantify financial performance.
    * Engineered **Age_Group** segments to identify core customer cohorts.
    * Calculated **Discount_Rate** impacts to analyze promotional elasticity.
* **Key Discovery:** Identified that **88.2% of orders** originate from returning customers, signaling high brand loyalty but highlighting a potential need for more aggressive new customer acquisition.

---

## 📊 Phase 2: Strategic Visualization (Power BI)
The `Visualization.pbix` dashboard was architected to provide a "Single Source of Truth" for executive decision-makers:

* **Revenue Optimization:** Granular breakdown of sales by category (with **Electronics** dominating at 10.4M TL).
* **Logistics Efficiency:** Analyzed the correlation between **Delivery_Time_Days** and **Customer_Rating** to pinpoint operational bottlenecks.
* **Channel Analysis:** Visualized device-specific behavior, revealing **Mobile** as the primary driver of traffic (9,500+ orders).
* **Geospatial Insights:** mapped regional performance across Turkey, identifying **Istanbul** and **Ankara** as high-density revenue hubs.

---

## 📂 Project Structure
| Module | File | Purpose |
| :--- | :--- | :--- |
| **Analysis** | `Analysis_Pytohn.ipynb` | Data cleaning, Feature engineering, & Statistical EDA. |
| **Business Intelligence**| `Visualization.pbix` | Interactive executive dashboard. |
| **Processed Data** | `cleaned_data_for_visual.csv` | The "Gold" layer dataset ready for BI consumption. |

---

## 💡 Strategic Recommendations
1.  **Retention Focus:** Implement a loyalty program to further capitalize on the 88% returning customer rate.
2.  **Logistics:** Optimize shipping in cities where delivery time exceeded 5 days, as it showed a direct negative impact on ratings.
3.  **Marketing:** Prioritize Mobile-first advertising campaigns given the high mobile conversion rate compared to desktop.

---