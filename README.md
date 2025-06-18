# HR Retail Dashboard

<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Dashboad%20view.png" width="900"/>

---

## 🎯 Business Context

In a multi-site retail organization, efficiently managing human capital is critical. Factors such as frequent absenteeism, overtime, unequal gender distribution, and high turnover can significantly affect performance, customer satisfaction, and profitability.

This dashboard supports **strategic HR decision-making** by providing insights on:

**- Real-time workforce performance monitoring**
**- Workforce distribution across stores**
**- Employee mobility between store locations**
**- Absenteeism patterns and analysis**
**- Gender equality insights**
**- Workforce evolution trends**
**- Employee loyalty and tenure by age group and years of service**

---

## 📊 Dataset Used

- **Title**: Absenteeism Dataset  
- **Source**: [HR Analytic Repository via Kaggle](https://www.kaggle.com/datasets/HRAnalyticRepository/absenteeism-dataset)
- **Description**: Synthetic dataset with employee absence hours, work department, age, education, and more.

---

## ⚠️ Limits during data processing

- No date/timestamp  
- No salary/overtime data  
- No hiring/termination history  
- Limited geo data (City, Store only)  
- No diversity markers (ethnicity, etc.)  
- No long-term career tracking  

---
## 🛠️ Tools & Technologies

**Python**
- Data cleaning, normalization, feature prep

**Excel**
- Feature Engineering:  
  - Tenure categories: `<1`, `1–2`, `2–5`, `≥5 years`  
  - Age grouping: `15–24`, `25–34`, ..., `65+`  
  - Standardized Gender  
  - Absenteeism Rate (%) calculation  
  - Presence Tagging  

**Power BI**
- Interactive dashboards with:
  - Filters by store/geo
  - Workforce KPIs
  - Absence, gender, mobility visuals

---

## 📌 Notable Findings

### 🏙️ Employee Mobility Across Stores
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Mobility%20Insight.png" width="600"/>

- 2020: 28% (2364/3282) lived outside city  
- 2025: 29% (5901/8304) — stable despite workforce growth  

Implications:
- Suburban expansion
- Transport/hybrid policy optimization

---

### 🧭 Absenteeism patterns & Gender Analysis
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Absenteeism1.png" width="300"/> <img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/AbsenteeismM.png" width="294"/> <img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/AbsenteeismF.png" width="300"/>

<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Gender%20distribution%20by%20department.png" width="300"/>

- **Balanced gender**: 50.63% M / 49.37% F  
- **Absenteeism**:
  - Female: 0.77%
  - Male: 0.65%

Insights:
- Family responsibilities/workload disparity?
- Gender gaps in:
  - IT: 9M vs 1F  
  - Legal: 2M vs 1F  
  - Investment: 6M vs 3F  
  - Leadership slightly male-biased

---

### 📈 Workforce Evolution (2020–2025)
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Trends%20in%20Workforce%20Evolution.png" width="600"/>

- 2020–2022: +115% growth  
- 2023–2025: Slowing → mature phase?

---

### ⏳ Tenure & Loyalty
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Employees%20by%20age%20group%20and%20years%20of%20service.png" width="600"/>

- 50%+ employees have 2+ years of service  
- Strong mid-career retention (35–54 yrs)  
- High tenure among 65+ → post-retirement roles  

---

## ✅ Recommendations

- Flexible work programs (e.g., parental leave)
Support work-life balance and don't just focus on reducing absenteeism.

- Improve gender equity in technical roles
Address gender gaps in departments like IT and Legal through targeted hiring and promotion policies.

- Focus on retention, not just growth
With workforce growth slowing, invest in engagement and long-term career development.

- Engage young cohorts (training/career paths)
Provide clear progression paths to retain younger employees and nurture future talent.

- Plan succession for aging workforce
Anticipate retirements by building internal leadership pipelines and knowledge transfer plans.


## 📂 Repository Structure

<img src= "https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Project%20Structutre.png" width="300"/>
