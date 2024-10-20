# Employee Data Analysis Project

## Overview
This project analyzes employee data to uncover insights on team distribution, positions, salary expenditure, and age demographics. It includes data preprocessing, analysis tasks, and visualizations to help understand the dataset.

## Preprocessing Steps
- **Height Correction**: Replaced incorrect heights with random values between 150-180 cm.
- **Data Cleanup**: Ensured consistency and accuracy in the dataset.

## Analysis Tasks and Visualizations

### 1. Team Distribution:
- Counted employees in each team and calculated their percentage.
- **Visualizations**: Bar and pie charts.

### 2. Position Segregation:
- Counted employees by position.
- **Visualization**: Bar graph.

### 3. Age Group Breakdown:
- Identified the predominant age group.
- **Visualization**: Bar graph.

### 4. Salary Expenditure:
- Found the team and position with the highest salary.
- **Visualization**: Stacked chart.

### 5. Age-Salary Correlation:
- Analyzed the relationship between age and salary.
- **Visualization**: Heatmap.

## Insights Gained from the Analysis

### Key Trends:
1. **New Orleans Pelicans** have the most employees, while **Minnesota Timberwolves** and **Orlando Magic** have the fewest.
2. The most common positions are **Shooting Guard (SG)** and **Power Forward (PF)**, while **Center (C)** has the fewest employees.
3. Most employees are in the **20-30 age group**, with very few over 30.

### Key Patterns & Correlations:
1. Most employees are under 30, while older age groups are almost absent.
2. The **Los Angeles Lakers** and **Small Forward (SF)** position have the highest salary expenditure.
3. A **positive correlation (0.21)** exists between age and salary, meaning older employees tend to earn more, but the link is weak.

### Key Insights:
1. The company focuses on hiring **younger talent**, as seen in the large number of employees under 30.
2. High salaries are concentrated in key teams like the **Los Angeles Lakers** and in positions like **Small Forward (SF)**.
3. Although older employees tend to have higher salaries, **age alone does not strongly influence salary**.

## Tools Used
- Python (`pandas`, `matplotlib`, `seaborn`)
