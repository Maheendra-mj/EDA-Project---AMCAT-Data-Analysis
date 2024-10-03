# EDA-Project---AMCAT-Data-Analysis
In this the complete EDA was performed on the dataset having the AMCAT Data

# Graduate Salary Analysis and Career Insights

## Project Overview

This project is a comprehensive analysis of graduate salary data, job placements, and various factors that influence career opportunities for fresh graduates. The dataset contains information about graduates' academic performance, job roles, salary, and demographic details, allowing us to draw meaningful insights regarding salary patterns, gender disparities, and the relationship between academic specializations and job market outcomes.

The project aims to answer key research questions, such as:
- **Does specialization in Computer Science lead to higher salaries in specific job roles?**
- **Is there a relationship between gender and choice of specialization?**
- **What are the factors that influence salary differences among fresh graduates?**

Through univariate and bivariate analyses, as well as hypothesis testing, we seek to explore these questions and provide actionable insights.

## Key Features

- **Univariate Analysis:** 
  - Distribution plots (histograms, PDFs, boxplots) to understand individual variables such as salary, academic scores, etc.
  - Outlier detection for key numerical columns.
  
- **Bivariate Analysis:** 
  - Scatter plots, hexbin plots, and pair plots to discover relationships between numerical variables (e.g., salary and academic performance).
  - Swarm plots and box plots to investigate the interaction between categorical and numerical variables.
  
- **Hypothesis Testing:** 
  - Test claims about graduate salaries (e.g., Times of India article claim regarding Computer Science graduates' salary).
  - Chi-square tests to examine relationships between categorical variables such as gender and specialization.

## Dataset

The dataset consists of 3998 records and 39 columns, covering information such as:
- **Academic Performance:** Grade 10 & 12 percentages, College GPA, scores in AMCAT sections (English, Logical, Quantitative, etc.).
- **Job Details:** Job designation, job city, salary.
- **Demographics:** Gender, date of birth, college tier, and more.

## Research Questions

1. **Salary Analysis for Computer Science Graduates:**
   - Are the salaries of Computer Science graduates in roles such as Programming Analyst, Software Engineer, Hardware Engineer, and Associate Engineer between 2.5 and 3 lakhs, as claimed by a Times of India article?
   
2. **Relationship between Gender and Specialization:**
   - Does the preference for specialization depend on gender?

3. **Additional Insights:**
   - Does college tier influence starting salary?
   - Is there a gender pay gap for fresh graduates?
   - Do higher AMCAT scores lead to better job placements?

## Project Structure

- `notebooks/`: Contains Jupyter notebooks with exploratory data analysis (EDA) and hypothesis testing.
- `data/`: Includes the dataset used for analysis.
- `images/`: Visualizations generated during the analysis.
- `scripts/`: Python scripts for running the analysis and creating visualizations.
- `README.md`: Project documentation.

## How to Use

1. **Clone the repository:**
   ```bash
   https://github.com/Maheendra-mj/EDA-Project---AMCAT-Data-Analysis.git
