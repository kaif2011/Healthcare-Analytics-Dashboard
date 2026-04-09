# Healthcare-Analytics-Dashboard
An interactive clinical performance dashboard designed to monitor patient volume, optimize treatment costs, and evaluate operational efficiency in healthcare delivery.

## 📌 Project Overview

This project focuses on transforming raw clinical data into actionable healthcare insights. The primary objective was to provide hospital administrators and medical leads with a 360-degree view of Patient Care Lifecycle—from admission trends to treatment cost analysis.
By leveraging healthcare datasets, I built this dashboard to identify peaks in Patient Visits (10K) and analyze the financial impact of various treatments, which totaled $25.41M in costs. The project highlights key metrics like Average Treatment Cost ($2.54K) and Average Patient Age (48.94) to help healthcare providers make data-backed decisions for resource allocation and clinical staffing.

## 🛠️ Tech Stack & Tools

The dashboard was built using the following tools and technologies:
- 📊 Power BI Desktop: Used for building an interactive healthcare clinical dashboard to monitor patient outcomes and operational costs.
- 🔄 Power Query (ETL): Handled complex data cleaning, including demographics and treatment name normalization.
- 🧠 DAX (Data Analysis Expressions): Developed custom measures for Avg Treatment Cost, Total Visits, and YOY Growth.
- 🔗 Data Modeling: Established a Star Schema between Patients, Doctors, and Treatment datasets for seamless filtering.
- 📁 File Format – .pbix (Project Development) and .png (Performance Preview).

## 📂 Data Source
This project utilizes a clinical dataset featuring 10K Patient Records, including demographics, visit history, and detailed treatment costs. The data simulates a real-world healthcare environment, allowing for analysis of treatment trends, doctor efficiency, and hospital revenue drivers across different quarters and years.

### 🔸 The Business Problem:
Healthcare administrators often struggle to align clinical workload (patient visits) with financial performance (treatment costs). Without proper data visualization, it is nearly impossible to identify patient flow bottlenecks, evaluate doctor efficiency, or track high-cost treatments accurately. The core challenge of this project was to synthesize raw hospital data to optimize resource allocation and improve the overall quality of patient care delivery.

---

### 🔸 Goal of the Dashboard:

The objective was to develop an interactive analytical tool for hospital management that:

- Operational Visibility: Tracks patient traffic trends (10K visits) on a monthly and quarterly basis to manage staffing requirements.

- Financial Oversight: Monitors total treatment costs ($25.41M) and average cost per patient ($2.54K) to identify budgetary gaps.

- Resource Optimization: Analyzes doctor-wise patient distribution to ensure a balanced workload and reduce clinical burnout.

- Patient Profiling: Leverages age demographics (Avg 48.94) and gender distribution to develop geriatric-focused healthcare strategies.

---

### 🔸 Walkthrough of Key Visuals:

- Executive Clinical KPIs (Top Section): Provides an immediate snapshot of hospital performance with metrics like Total Patients (10K), Total Cost ($25.41M), and Avg Treatment Cost ($2.54K).

- Quarterly Visit Trends (Bar Chart): Analyzes patient load across different quarters (Q1 & Q2). This helps management understand long-term growth and year-over-year admission patterns.

- Monthly Patient Volume (Line Chart): Specifically tracks the flow of patients throughout the year, identifying major surges in August and October (approx 890+ visits) for proactive bed management.

- Financial Analysis by Treatment (Bar Chart): Ranks medical treatments by their cost impact. Antibiotics and Ibuprofen emerge as top cost-drivers ($5.2M each), highlighting areas for procurement optimization.
- Doctor Workload Distribution (Bar Chart): Visualizes the total patients handled by each physician (e.g., Elaine, Mic). This is crucial for evaluating staff efficiency and preventing burnout.

- Patient Demographics (Pie Chart): Segments the hospital’s reach by Gender, showing a near-equal distribution (approx 33-34% each), which aids in tailoring health programs for diverse patient groups.

---

### 🔸 Business Impact & Insights:
Operational Resource Planning: By identifying high-traffic months (August and October), hospital administration can proactively optimize staffing levels and bed availability to handle patient surges.

Strategic Financial Management: Analyzing the revenue contribution of top treatments allows for better pricing strategies and more efficient pharmacy procurement policies.

Specialized Geriatric Care: With an average patient age of 48.94, the facility can justify increased investment in elderly care services and specialized medical staff to cater to the dominant demographic.

Clinical Workflow Efficiency: The doctor-wise patient distribution enables transparent performance tracking and ensures a fair workload distribution, reducing clinical burnout and improving patient care quality.

## 📸 Dashboard Preview
![Healthcare Analytics Dashboard Preview](https://github.com/kaif2011/Healthcare-Analytics-Dashboard/blob/main/Healthcare%20Dashboard.png)



