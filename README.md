# 🧠 HR Analytics Dashboard (Tableau)

### 📌 Project Overview

The **HR Analytics Dashboard** is an interactive **Tableau visualization project** developed to help HR teams monitor workforce demographics, attrition trends, and employee satisfaction.
The dashboard provides a **comprehensive overview of key HR metrics**—including attrition rate, employee distribution by age and department, gender-based analysis, and job satisfaction—enabling data-driven decisions to reduce employee turnover and improve retention strategies.
<img width="1576" height="801" alt="Screenshot 2025-10-23 013045" src="https://github.com/user-attachments/assets/6d707a0e-3a0c-4b82-93fb-c72ca1be720c" />

---

## 🎯 Objective

To analyze workforce data and identify key **drivers of employee attrition**, patterns across **departments, age groups, gender, and education fields**, and actionable insights that can guide HR policies and employee engagement initiatives.

---

## 🧾 Dataset Description

The dashboard is powered by the dataset **`HR Data.xlsx`**, which contains detailed employee-level information across multiple demographic and performance dimensions.

| **Column Name**   | **Description**                                                              |
| ----------------- | ---------------------------------------------------------------------------- |
| `EmployeeNumber`  | Unique ID for each employee                                                  |
| `Department`      | Department to which the employee belongs (HR, R&D, Sales)                    |
| `Age`             | Age of the employee                                                          |
| `EducationField`  | Area of educational specialization (Life Sciences, Medical, Marketing, etc.) |
| `Gender`          | Gender of the employee                                                       |
| `Attrition`       | Indicates whether the employee has left the company                          |
| `JobRole`         | Employee’s current position or role                                          |
| `JobSatisfaction` | Employee satisfaction level (1–4 rating scale)                               |
| `YearsAtCompany`  | Total years spent in the organization                                        |
| `MonthlyIncome`   | Employee’s monthly salary                                                    |
| `OverTime`        | Indicates if the employee works overtime                                     |

---

## ⚙️ Data Preparation

Before visualization, the following **data cleaning and transformation** steps were performed:

1. **Data Cleaning (Excel):**

   * Removed nulls and standardized categorical fields (e.g., Gender, EducationField).
   * Converted text-based age ranges and attrition flags into numerical categories.
2. **Feature Engineering (Tableau):**

   * Calculated key metrics such as Attrition Rate, Active Employees, and Average Age.
   * Created bins for Age Groups and Job Satisfaction levels.
   * Applied calculated fields to segregate attrition data by gender and department.

---

## 📊 Dashboard Components

### 1️⃣ **Top KPIs**

* **Employee Count:** 1,470 total employees in the dataset.
* **Attrition Count:** 237 employees left the organization.
* **Active Employees:** 1,233 employees retained.
* **Average Age:** 37 years.
* **Attrition Rate:** 16.12%.

These indicators provide a quick overview of workforce scale and turnover health.

---

### 2️⃣ **Department-Wise Attrition**

* **Visualization:** Pie Chart
* **Insight:** The **Sales Department** experienced the highest attrition (56%), followed by **R&D (39%)** and **HR (5%)**.
* This helps HR focus retention programs where turnover impact is greatest.

---

### 3️⃣ **Employee Distribution by Age Group**

* **Visualization:** Histogram
* **Insight:** Most employees fall between **27 and 36 years**, indicating a mid-career workforce.
* Attrition is notably higher among employees aged **25–34**, highlighting potential stress or dissatisfaction in early professional stages.

---

### 4️⃣ **Education Field-Wise Attrition**

* **Visualization:** Bar Chart
* **Insight:** Employees with **Life Sciences** and **Medical** backgrounds show higher attrition counts.
* Suggests need for tailored engagement strategies for employees with technical education.

---

### 5️⃣ **Attrition Rate by Gender and Age Group**

* **Visualization:** Donut Charts
* **Insight:**

  * Males show slightly higher attrition (150 vs 87 females).
  * Attrition peaks for males aged **25–34**, while female attrition is more evenly distributed.
* HR can use this insight to design gender- and age-specific retention policies.

---

### 6️⃣ **Job Satisfaction Rating by Job Role**

* **Visualization:** Heat Map
* **Insight:**

  * **Sales Executives** and **Research Scientists** report higher satisfaction levels (3–4 ratings).
  * **Managers** and **Human Resources** roles show relatively lower satisfaction.
* Highlights roles that may benefit from targeted engagement or work-life initiatives.

---

## 💡 Key Insights

* **Overall attrition rate:** 16.12% — higher in Sales and R&D departments.
* **Peak attrition age group:** 25–34 years, aligning with early-career transitions.
* **Male attrition:** Higher than female, particularly in younger age brackets.
* **Education factor:** Employees from Life Sciences and Medical fields contribute the most to turnover.
* **Job satisfaction:** Uneven across roles, indicating potential for role-specific HR improvements.

---

## 🧠 Business Impact

The dashboard equips HR leaders to:

* Identify **high-risk segments** for attrition by age, department, and education field.
* Prioritize **retention programs** and **employee engagement strategies** for vulnerable groups.
* Use **data-driven storytelling** to communicate workforce trends to leadership.
* Continuously track attrition patterns and satisfaction levels to improve organizational health.

---

## 🛠️ Tools & Technologies

| **Tool**                                       | **Purpose**                                                           |
| ---------------------------------------------- | --------------------------------------------------------------------- |
| **Tableau Desktop**                            | Interactive dashboard creation and visualization                      |
| **Microsoft Excel**                            | Data preparation and cleaning                                         |
| **Calculated Fields**                          | Derived metrics such as Attrition %, Employee Count, Active Employees |
| **Filters & Parameters**                       | Interactivity for Education, Gender, and Age selection                |
| **Heatmaps, Donut, Histogram, and Pie Charts** | Data storytelling and trend visualization                             |

---

## 🧩 Skills Demonstrated

* Data Cleaning & Transformation
* Tableau Dashboard Design
* KPI and Metric Development
* Interactive Filtering & Parameter Controls
* HR Analytics and Attrition Trend Analysis
* Visual Storytelling for Business Insights

---

## 📁 Deliverables

* **Tableau Workbook:** `HR Dashboard.twbx`
* **Dataset:** `HR Data.xlsx`

---

## 🚀 Outcome

This project demonstrates how HR data can be transformed into actionable insights through analytics and visualization.
By integrating demographic, satisfaction, and attrition data, organizations can proactively identify employee pain points, strengthen engagement, and improve overall retention strategy.

---

## 👨‍💻 Author

**Puneeth Vijay Krishna Samarla**
M.S. in Information Science (Machine Learning), University of Arizona
📧 [puneethvks9@email.com](mailto:puneethvks9@email.com)
🔗 [LinkedIn](https://www.linkedin.com/in/puneeth-samarla)
