# Techsavia_Project

## 📘 Comprehensive Data Analysis & Insights Report  
### Based on: `COPY OF TECHSAVIIA1.xlsx`  
### **Date:** October 2025  
### **Prepared by:** ChatGPT Data Analysis Assistant  

---

## 1. Overview of the Workbook
The workbook contains **6 worksheets**, each representing different stages or views of employee-related data, likely used for HR analytics or business intelligence purposes.

| Sheet Name | Description | Status / Content Summary |
|-------------|--------------|---------------------------|
| **Page001** | Raw employee data (unrefined form) | Contains early data version with missing fields and unaligned entries |
| **Cleaned Sheet** | Finalized HR dataset | Clean, structured dataset ready for reporting and analysis |
| **Section 1 & Section 2** | Supporting or intermediate worksheets | Contain minimal usable data, possibly placeholders or pivot data |
| **Dashboard** | Visualization/summary layer | Likely contains charts or slicers for management dashboard |
| **Dashboard 2** | Alternate dashboard view | Supplementary visual summaries |

The **primary analytical dataset** is *“Cleaned Sheet.”*  
It is structured, complete, and free of missing values — suitable for deriving meaningful insights.

---

## 2. Dataset Profile: “Cleaned Sheet”

### 2.1 Structure
- **Rows:** 30  
- **Columns:** 10  
- **Fields:**  
  Employee ID, Full Name, Job Title, Department, Hire Date, Length of Stay, Salary, Years of Experience, Country, City

### 2.2 Data Types & Quality
- No missing data across all columns.  
- `Hire Date` properly formatted as datetime.  
- `Salary`, `Length of Stay`, and `Years Experience` are numeric.  
- Column naming is consistent and readable.

This sheet represents **clean HR data** containing demographic, salary, and experience information for each employee.

---

## 3. Key Descriptive Statistics

| Metric | Mean | Minimum | Maximum | Interpretation |
|---------|------|----------|----------|----------------|
| **Length of Stay (yrs)** | 8.23 | 3 | 13 | Employees tend to stay long-term; good retention. |
| **Salary ($)** | 96,711 | 58,201 | 134,801 | Competitive salary structure with moderate variation. |
| **Years of Experience** | 8.17 | 1 | 15 | Mid-to-senior level professionals dominate. |

---

## 4. Core Analytical Insights

### 4.1 Workforce Composition
- The **IT department** has the highest representation — suggesting that the organization is either technology-focused or relies heavily on IT operations.  
- The **most frequent job title** is *Developer*.  
- The **most represented country** is *Canada*, implying either headquarters or core operations there.
<img width="1243" height="572" alt="CHIDOZIE 1" src="https://github.com/user-attachments/assets/6e8e8b5a-2621-4b34-a0c6-b079843ea21d" />

### 4.2 Salary Analysis
- **Average salary:** ₦96,711  
- **Salary range:** ₦58,201 – ₦134,801  
- Indicates a **balanced pay structure** with no extreme disparities.  
- Suggests that employee remuneration is fairly consistent across departments and roles.

### 4.3 Experience and Retention
- **Average experience:** 8.2 years — showing a mature and stable workforce.  
- **Correlation (0.89)** between *Length of Stay* and *Years of Experience* shows that the longer employees stay, the more experienced they become within the organization — a sign of effective retention and growth.
<img width="1248" height="596" alt="CHIDOZIE 2" src="https://github.com/user-attachments/assets/62a0a5ef-c48e-4500-a66d-38c87bfdb0ee" />

### 4.4 Departmental Insights
- Dominance of IT roles aligns with global organizational trends emphasizing digitization.  
- Other departments like HR, Finance, and Sales appear smaller, possibly serving as support functions.

### 4.5 Country and Diversity
- Majority of staff are based in *Canada*, with minor representation in other countries (e.g., UK, Germany).  
- Suggests either a global company with headquarters in Canada or a Canadian-based operation expanding abroad.

---

## 5. Data Quality Evaluation
| Area | Observation | Recommendation |
|-------|--------------|----------------|
| **Page001 Sheet** | Contains raw/unrefined data, missing entries, inconsistent column placement | Retain as backup only; use “Cleaned Sheet” for analytics |
| **Section Sheets** | Low data density | Review purpose; possibly remove if not used for dashboards |
| **Dashboard Sheets** | Contain Excel slicers (unsupported by some tools) | Rebuild visuals in Power BI or Tableau for maintainability |
| **Overall** | “Cleaned Sheet” is complete and reliable | Use this as master dataset for HR analysis |

---

## 6. Managerial & Strategic Insights

### 6.1 Human Capital Retention
- Long average tenure (8+ years) signals **strong employee retention** and job satisfaction.  
- Management should **leverage this loyalty** to build mentorship and knowledge transfer programs.

### 6.2 Workforce Experience Mix
- Majority of employees fall within **mid to senior experience** range.  
- Organization could consider **succession planning** and **graduate trainee recruitment** to maintain generational balance.

### 6.3 Pay and Motivation
- Salaries are **within a stable range**, showing good equity.  
- However, consider **performance-based differentiation** to reward high performers.

### 6.4 Departmental Strength
- **IT Department** leads in representation — an asset for digital transformation.  
- Recommend periodic **skills audits** and **upskilling programs** to sustain competitiveness.

### 6.5 Geographic Insight
- Predominant Canadian presence.  
- Opportunity to **diversify workforce locations** for cost optimization and market presence.

---

## 7. Recommendations

| Area | Action Step | Expected Outcome |
|-------|--------------|------------------|
| **HR Analytics System** | Develop centralized dashboard (Power BI/Tableau) tracking salary, tenure, attrition, and performance metrics. | Real-time HR insights |
| **Talent Management** | Initiate training programs for low-experience employees. | Increase productivity and retention |
| **Pay Review Policy** | Introduce salary bands aligned with experience and performance. | Equity and motivation |
| **Data Governance** | Maintain “Cleaned Sheet” as the single source of truth; set monthly data updates. | Reliable, current HR reporting |
| **Diversity & Inclusion** | Expand recruitment beyond Canada. | Broader talent pipeline |

---

## 8. Conclusion
The workbook demonstrates a **well-maintained HR dataset** ready for analytics integration.  
Insights reveal:
- A stable and experienced workforce  
- Balanced salary structure  
- High employee retention  
- IT-centric organizational design  

With proper dashboarding and HR analytics strategy, management can translate this data into **predictive workforce planning, cost optimization, and talent development decisions.**


