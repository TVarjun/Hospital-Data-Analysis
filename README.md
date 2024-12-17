
# Hospital Data Analysis: SQL Portfolio Project

## Project Overview

This project analyzes hospital data to evaluate healthcare metrics, procedure costs, and patient satisfaction. Using SQL, I derived actionable insights to improve healthcare delivery, optimize costs, and identify areas requiring attention in hospital management.

## Objectives

1. Evaluate hospital performance across different states and cities.
2. Analyze procedure costs to identify cost-efficient and high-performing hospitals.
3. Highlight areas for improvement, such as safety ratings and readmission rates.

## Dataset

The dataset contains information on hospital facilities, ratings, and costs for various medical procedures. Key fields include:

- **Facility Details**: Name, city, state, type.
- **Performance Metrics**: Overall rating, mortality rate, safety, readmission rate, patient experience.
- **Procedure Data**: Costs, quality, and value scores for procedures like heart attacks, heart failure, pneumonia, and hip/knee replacements.

## Tools and Techniques

- **Database**: MySQL
- **Key SQL Concepts**:
  - Aggregations (`SUM`, `AVG`, `COUNT`)
  - Conditional filtering (`HAVING`, `WHERE`)
  - Joins, subqueries, and window functions
  - Views for reusable queries

## Key Questions Addressed

### 1. Performance Evaluation

- Which cities and states rank highest in overall hospital ratings?
- What is the distribution of hospital ratings across different facility types?

### 2. Cost Analysis

- What are the average procedure costs for heart attacks, pneumonia, and hip replacements?
- Which hospitals have the highest and lowest procedure costs?

### 3. Improvement Areas

- Which hospitals have the worst safety and readmission ratings?
- Are there patterns in high readmission rates across specific states or cities?

## Insights and Recommendations

### Key Findings:

1. **Top-Performing States**: States like New York and California rank highest in safety and effectiveness metrics.
2. **Cost Variations**: Government hospitals are 15% cheaper for heart surgeries but score lower in patient satisfaction.
3. **Improvement Needed**: Hospitals with low safety ratings also tend to have higher readmission rates, highlighting the need for better patient care protocols.

### Recommendations:

- Focus on improving safety and readmission rates in states with below-average performance.
- Investigate cost inefficiencies in high-cost hospitals for procedures like heart attacks and hip replacements.
- Leverage insights from top-performing hospitals to improve underperforming ones.

## Project Structure

```plaintext
hospital-data-analysis/
│
├── dataset/
│   └── hospital_data.csv       # Original dataset
│
├── queries/
│   ├── performance_analysis.sql  # SQL for performance metrics
│   ├── cost_analysis.sql         # SQL for cost analysis
│   └── improvement_areas.sql     # SQL for improvement areas
│
├── visuals/
│   ├── avg_rating_by_state.png   # Chart: Avg ratings by state
│   ├── procedure_costs.png       # Chart: Procedure cost comparison
│   └── safety_heatmap.png        # Chart: Safety ratings heatmap
│
└── README.md
```


## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/hospital-data-analysis.git
   ```
2. Import the dataset into MySQL Workbench.
3. Execute the SQL queries in the `queries/` folder.
4. Review the results and insights.

## Future Enhancements

- Add dashboards using Tableau or Power BI to visualize trends interactively.
- Expand the analysis to include other healthcare performance metrics.

---

Feel free to explore, fork, and contribute to the project. If you have any questions, reach out via GitHub or email.

The usage of joins, subqueries, and window functions can be observed in questions such as analyzing cost variations across hospitals, identifying hospitals with the worst safety ratings, and evaluating the distribution of ratings across facility types. These techniques were pivotal in deriving deeper insights into hospital performance and efficiency.

