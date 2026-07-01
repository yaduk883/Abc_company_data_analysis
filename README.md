
# ABC Company Employee Analysis

## Project Overview

This project provides a comprehensive data analysis of the ABC Company employee dataset (458 rows, 9 columns) using Python. The primary objective is to thoroughly examine the workforce demographics and financial distribution. This README summarizes the preprocessing steps applied to clean the data, the specific analysis tasks conducted, the graphical representations used to visualize the findings, the key insights gained, and additional technical information required to run the project.

---

## Preprocessing Steps

Before conducting the analysis, the dataset required cleaning to ensure data consistency and integrity:

* **Height Data Correction:** Inconsistent and incorrect entries in the `Height` column were replaced with random integers between 150 and 180 using `numpy.random.randint()`.
* **Handling Missing Values:** Any rows containing missing data in the `Age` or `Salary` columns were dropped from the dataset to prevent skewed analytical results.

---

## Analysis Tasks

The data was processed to answer specific questions regarding the workforce:

1. **Team Distribution:** Calculated the total headcount and the relative percentage of employees within each team.
2. **Position Segregation:** Grouped the workforce by their specific playing positions (PG, SG, SF, PF, C).
3. **Age Demographics:** Categorized employees into distinct age bins (18–24, 25–29, 30–34, 35–39, 40+) to identify the predominant age group.
4. **Salary Expenditure:** Evaluated the total salary spend distributed across different teams and individual positions.
5. **Age vs. Salary Correlation:** Computed the Pearson correlation coefficient to determine the mathematical relationship between an employee's age and their salary.

---

## Graphical Representations

To effectively communicate the findings, the following visualizations were generated using Matplotlib and Seaborn:

| Analysis Task | Chart Type |

| **Team Distribution** | Bar Chart with percentage labels |
| **Position Segregation** | Seaborn Count Plot |
| **Age Demographics** | Seaborn Bar Chart |
| **Salary Expenditure** | Side-by-side Horizontal and Standard Bar Charts |
| **Correlation Analysis** | Scatter Plot overlaid with a Trend Line |

---

## Insights 

The analysis yielded several key takeaways about ABC Company's workforce:

* **Demographics:** The workforce is predominantly young, with the 25–29 age bracket making up the largest segment of employees.
* **Structural Balance:** Hiring is highly structured, reflected by a relatively even distribution of employees across both teams (roughly 1–4% of the workforce per team) and positions (with SG and PF being the most common, and Center being the least represented).
* **Compensation Drivers:** Age is not the primary driver of compensation, demonstrated by a weak positive correlation between the two variables. Younger talent can command premium salaries based on skill and position.
* **Financial Allocation:** The Small Forward (SF) position and specific teams, notably the Cleveland Cavaliers, command the highest salary budgets, indicating targeted financial investment in specific talent pools.

---

### Repository Structure

* `ABC_Company_Analysis.ipynb`: Main Jupyter Notebook containing the Python code and visualizations.
* `abc_company.xlsx`: The source dataset.
* `README.md`: Project documentation.

* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab
##Colab link
https://colab.research.google.com/drive/1B2yzswfHLchzzvySk56yMLM1r0gtXwtC?usp=sharing
