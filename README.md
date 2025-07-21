# HR-Data-Analytics-using-PowerBI
Interactive HR Analytics Dashboard to visualize and analyze employee attrition trends and insights.


Situation  
Employee attrition remains a major challenge for organizations. Understanding the reasons why employees leave is critical to improving workforce stability, reducing rehiring costs, and building a strong employee engagement strategy. This project was undertaken to provide HR leadership with data-driven insights into attrition across different dimensions like age, gender, job role, salary, education, and experience.

---

## Task  
As the lead data analyst, my responsibility was to design and develop a powerful yet user-friendly HR dashboard in Power BI that visualizes key trends and patterns in employee attrition. The objective was to uncover hidden insights and enable HR stakeholders to take proactive steps in reducing employee turnover.

---

##  Action  

### Data Preparation:  
- Used an Excel-based dataset containing 4 interconnected tables:  
  - HR_Data (main fact table)  
  - Education (lookup)  
  - Jobs (lookup)  
  - Departments (lookup)  
- All data transformation and preprocessing were handled using Power Query, including column cleanup, relationship creation, and value standardization.

### Dashboard Development:  
- Built using Power BI with a clean, consistent design and optimized layout.  
- Implemented 2 slicers: Department, Gender  
- Created calculated DAX measures for:  
  - Total Attrition  
  - Attrition Rate  
  - Average Age  
  - Average Salary  
  - Average Years of Experience

### Visualizations Included:  
- **KPI Cards (Top):** Employee Count, Attrition Count, Attrition Rate (%), Avg Age, Avg Salary, Avg Exp  
- **Pie & Bar Charts:** Attrition by Education Field, Salary Group, and Gender; Attrition by Age Group  
- **Line & Area Chart:** Attrition by Years of Experience  
- **Matrix Table:** Attrition by Job Role and Performance Rating  
- **Stacked Bar:** Attrition by Job Role  

All visuals are color-coded and interactive, with slicer-driven dynamic updates across the report.

---

## Result  
The final dashboard provided actionable insights to HR stakeholders, enabling them to:  
- Identify high-risk attrition segments by role, salary, and age.  
- Discover that Research Scientists, HR, and Sales Reps were the most affected roles.  
- Pinpoint salary below 5k, experience < 1 year, and ages 26–35 as leading attrition indicators.  
- Recognize that even top performers (Performance Rating 4) were leaving — indicating broader engagement or satisfaction issues.  

---

#### Attrition Insights

| Category    | Key Insight                                         | India-Specific Reasoning                                                                                                           |
|-------------|----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Age         | Majority of attrition is among 26–35 age group     | In India, this age group typically includes employees in their 1st to 2nd job, often looking for rapid career growth, better packages, or overseas opportunities. Many also pursue higher education (MBA, MS abroad), leading to high voluntary attrition. |
| Salary      | Over 68% of attrition comes from employees earning below ₹5K/month | This band likely represents interns, support staff, or entry-level roles. In India, cost of living pressures and competitive entry-level hiring (especially in metro cities) drive frequent job switches in this segment. Also, expectations rise quickly post-training or probation. |
| Experience  | Attrition peaks during the first year of employment | Early exits are common in India due to poor onboarding, training-to-project mismatch, or last-minute better offers (common in fresher hiring cycles). Lack of role clarity or late allocation to projects can frustrate new hires. |
| Job Role    | Highest attrition seen in Research Scientists, HR, and Sales Representatives | In India, Sales roles have high burnout due to target pressure and variable pay. HR professionals often face limited growth without MBA/PG qualifications. R&D roles may lack structured career paths or clear performance incentives in non-tech sectors. |
| Education   | Most attrition comes from Life Sciences and Medical backgrounds | Many Life Sciences grads in India are placed in support or lab roles with lower pay and limited upward mobility. Without further specialization (Pharma, Clinical Research, etc.), these professionals often look for better-paying options in other industries. |
| Gender      | Male employees show higher attrition                | In India, male employees dominate certain attrition-prone fields like Sales and Tech Support. Cultural norms may also lead to higher female retention due to job stability preference or lower mobility, though this is changing in metros. |
| Performance | Even high performers (Rating 4) are leaving         | In Indian firms, high performers often get better offers or are headhunted quickly. Without proper reward mechanisms, promotions, or learning pathways, they don’t stay long. A lack of transparent career planning is a common retention gap. |


---
