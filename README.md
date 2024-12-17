# Data Transformation and Analysis of a Startup

## Project Overview
In this project, we perform data analysis and transformation for a tech startup seeking to optimize its operations after a global pandemic. The analysis addresses critical business questions such as:
- Is the company in good financial health?
- Does the company need to restructure its workforce?
- Should the company transition to permanent remote work for employees?

By examining six months of financial and employee data, the project provides actionable insights to assist the company's management team in making informed decisions.

---

## Dataset Details
The analysis involves two key datasets:

### 1. Financial Data
- **Columns**:
  - `Month`: Month number.
  - `Revenue`: Total revenue earned in a month.
  - `Expenses`: Total expenses incurred in a month.
- **Purpose**: Assess the financial health of the company and identify trends.

### 2. Employee Data
- **Columns**:
  - `Name`: Name of the employees.
  - `Salary`: Employee's salary.
  - `Productivity`: Productivity count.
  - `Commute Time`: Time takes for an employee to reach the office.
- **Purpose**: Evaluate workforce productivity and determine suitability for remote work.

---

## Key Questions Explored
1. How does the company's revenue compare to its expenses over time?
2. Are there employees that are underperforming?
3. Should the company adopt permanent remote work based on employee productivity?

---

## Tools and Libraries Used
- **Python**
  - Libraries: Pandas, Matplotlib, Seaborn, NumPy.
- **Jupyter Notebook** for interactive analysis and visualization.

---

## Key Techniques Applied
1. **Data Cleaning**:
   - Handled missing values and ensured consistency across datasets.
   - Processed categorical data for analysis.

2. **Data Transformation**:
   - Applied log transformation to normalize skewed revenue and expense data.
   - Used scaling techniques (Min-Max and Standardization) for employee productivity data.

3. **Visualization**:
   - Created line plots to visualize revenue vs. expenses trends.
   - Created pie charts to visualize expenses
   - Generated histograms for commute time.

---

## Insights and Recommendations
1. **Financial Health**:
   - Revenue consistently outpaces expenses, indicating positive financial health.
   - Notable expense spikes in specific months suggest areas for cost optimization.

2. **Workforce Analysis**:
   - Departments with low productivity were identified for potential restructuring.
   - Remote employees logged higher work hours on average, supporting a shift toward permanent remote work for certain roles.

3. **Future Strategies**:
   - Focus on reducing unnecessary expenses in high-spike months.
   - Provide training and tools for underperforming departments to boost efficiency.

---

## Future Work
- Incorporate additional datasets (e.g., customer satisfaction, market trends) to enrich analysis.
- Develop predictive models to forecast revenue and expenses for upcoming quarters.
- Create interactive dashboards for real-time monitoring of financial and workforce metrics.

---

## Author
**Ata Shaikh**
- Data Science Enthusiast
- Connect with me on [LinkedIn](https://www.linkedin.com/in/theatashaikh) or [GitHub](https://github.com/theatashaikh).

---

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
