### README

## Employee Data Analysis Project

This project involves analyzing a dataset from ABC Company to gain insights into various aspects of the company's workforce. The dataset consists of 458 rows and 9 columns, including details such as name, team, number, position, age, height, weight, college, and salary. The project includes preprocessing the data, performing several analysis tasks, and presenting the findings graphically.

### Project Structure

- **data/**: Contains the dataset file (`employee_data.csv`).
- **employee_data_analysis.ipynb**: Contains the Jupyter Notebook file.
- **README.md**: Comprehensive overview of the project.

### Preprocessing

1. **Height Correction**: The `Height` column was replaced with random numbers between 150 and 180 to ensure consistency and integrity.

### Analysis Tasks

1. **Distribution of Employees Across Teams**:
    - Calculated the number and percentage of employees in each team.
    - Visualized the distribution using a bar chart.

2. **Segregation by Positions**:
    - Determined the number of employees in each position.
    - Visualized the distribution using a bar chart.
    - **Insight**: The position `SG` has the highest number of employees, with over 100 employees, followed closely by `PF`. The position with the fewest employees is `C`, with 80 employees.

3. **Predominant Age Group**:
    - Identified the most common age groups among employees.
    - Visualized the age distribution using a bar chart.
    - **Insight**: The most common age group is 20-30, with fewer than 50 employees in the 10-20 age group. There are no employees above 40 years of age.

4. **Highest Salary Expenditure**:
    - Determined which teams and positions have the highest salary expenditures.
    - Visualized the salary expenditures using bar charts.
    - **Insight**: The team with the highest salary expenditure is the `Cleveland Cavaliers`. The position with the highest salary expenditure is `C`.

5. **Correlation Between Age and Salary**:
    - Investigated the relationship between age and salary.
    - Visualized the correlation using a scatter plot.
    - Calculated the correlation coefficient.
    - **Insight**: The correlation coefficient is 0.214, indicating a weak positive correlation between age and salary. Salaries tend to peak around the age of 30.

### Visualizations

The project includes several visualizations to effectively present the findings:

- **Bar Chart**: Distribution of employees across teams.
- **Bar Chart**: Distribution of employees by position.
- **Bar Chart**: Age group distribution of employees.
- **Bar Chart**: Salary expenditure by team.
- **Bar Chart**: Salary expenditure by position.
- **Scatter Plot**: Correlation between age and salary.

### Insights Gained

- **Team Distribution**: Helps in understanding team sizes and resource allocation.
- **Position Segregation**: Highlights critical roles and potential areas for hiring.
- **Age Demographics**: Informs decisions on training, development, and retirement planning.
- **Salary Expenditure**: Aids in budget allocation and financial planning.
- **Age-Salary Correlation**: Ensures equitable pay practices and understanding of pay scales.

### Conclusion

This project demonstrates proficiency in Python programming, data analysis, and the ability to communicate insights from real-world data effectively. The findings provide valuable information for human resource management, financial planning, and ensuring fair compensation within the company.
