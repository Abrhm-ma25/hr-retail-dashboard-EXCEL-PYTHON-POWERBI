# Interactive HR Retail Dashboard

<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Dashboard%20view.png" width="900"/>

###### 📥 Download the interactive dashboard [hr-retail-dashboard](https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/hr-retail-dashboard.pbix?raw=true)

---

## 🎯 Business Context

In a multi-site retail organization, efficiently managing human capital is critical. Factors such as frequent absenteeism,  overtime, gender imbalance, and high turnover can negatively impact performance, customer satisfaction, and profitability.

This dashboard supports **strategic HR decision-making** by providing insights on:


**- Workforce distribution across stores**

**- Employee mobility between store locations**

**- Absenteeism patterns and analysis**

**- Gender equality insights**

**- Workforce evolution trends**

**- Employee loyalty and tenure / years of service by age group**

---

## 📊 Dataset used

- **Title**: Absenteeism Dataset  
- **Source**: [HR Analytic Repository via Kaggle](https://www.kaggle.com/datasets/HRAnalyticRepository/absenteeism-dataset)
- **Description**: Fictitious synthetic dataset with employee absence hours, work department, age, education, and more.

---

## ⚠️ Dataset limitations

- No date/timestamp  
- No salary/overtime data  
- No hiring/termination history  
- Limited geographic data (only city and store location)  
- No diversity markers (ethnicity, etc.)
- No long-term career tracking  

---
## 🛠️ Tools & Technologies used

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
  - Filter by store location
  - Workforce KPIs
  - Absence, gender, mobility visuals

---

## 📌 Notable Findings

### 🏙️ Employee Mobility Across Stores
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Mobility%20Insight.png" width="600"/>

- 2020: 28% (918/3282) lived outside city
- 2025: 29% (2403/8304) stable despite workforce growth

**Insights:**
- Suburban expansion
- Transport policy optimization

---

### 🧭 Absenteeism patterns & Gender Analysis
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Absenteeism1.png" width="300"/> <img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/AbsenteeismM.png" width="294"/> <img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/AbsenteeismF.png" width="300"/>

- **Balanced gender**: 50.63% M / 49.37% F
- **Absenteeism**:
  - Overall: 0.71%
  - Female: 0.77%
  - Male: 0.65%

**Insights:**
- Overall poor work-life balance
- Higher family responsibilities for female employees?
- Potential workload disparity?
  
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Gender%20distribution%20by%20department.png" width="300"/>

**Insights:**
- Leadership slightly male-biased, gender gaps in:
  - IT: 9M vs 1F  
  - Legal: 2M vs 1F  
  - Investment: 6M vs 3F 


---

### 📈 Workforce Evolution (2020–2025)
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Trends%20in%20Workforce%20Evolution.png" width="600"/>

- 2020–2022: Workforce grew from 3,282 to 7,070 employees (+115%)  
- 2023–2025: Slowing → mature phase?

---

### ⏳ Tenure & Loyalty
<img src="https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Employees%20by%20age%20group%20and%20years%20of%20service.png" width="600"/>

- 50%+ employees have 2+ years of service  
- Strong mid-career retention (35–54 yrs)  
- High tenure among 65+ → post-retirement roles  

---

## ✅ Recommendations

- Flexible work programs (e.g., parental leave), support work-life balance instead of solely targeting absenteeism reduction.

- Improve gender equality in technical roles, address gender gaps in departments like IT and Legal through targeted hiring and promotion policies.

- Focus on retention, with workforce growth slowing, invest in engagement and long-term career development.

- Engage young cohorts (training/career paths), provide clear progression paths to retain younger employees and nurture future talent.

- Plan succession for aging workforce, anticipate retirements by building internal leadership pipelines and knowledge transfer plans.


## 📂 Repository Structure

<img src= "https://github.com/Abrhm-ma25/hr-retail-dashboard-EXCEL-PYTHON-POWERBI/blob/main/Images/Project%20Structure.png" width="300"/>
