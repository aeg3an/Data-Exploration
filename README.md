# Placement Data Analysis

## Project Overview
This project performs **Bivariate and Multivariate Analysis** on a placement dataset to explore relationships between **categorical and numerical variables**. Various visualization techniques are used to understand the impact of factors like gender, academic performance, work experience, and specialization on salary and placement status. This is a part of the assignment given in the course **DAI-101**.

## Dataset
The dataset being used is the placement statistics of 200 randomly selected students of a college. It contains information like percentages in SSC, HSC, Degree Type, Gender, Specialisation, Work Experience and Placement Status.

## Features Analyzed
### **Categorical Variables**
- Gender
- SSC Board (`SSC_B`)
- HSC Board (`HSC_B`)
- HSC Specialization (`HSC_S`)
- Degree Type (`DEGREE_T`)
- Work Experience (`WORKEX`)
- Specialization (`SPECIALISATION`)
- Placement Status (`STATUS`)

### **Numerical Variables**
- Secondary Education Percentage (`SSC_P`)
- Higher Secondary Percentage (`HSC_P`)
- Degree Percentage (`DEGREE_P`)
- Employability Test Percentage (`ETEST_P`)
- MBA Percentage (`MBA_P`)
- Salary (if placed, else Salary = 0)

## Exploratory Data Analysis (EDA)
### **Univariate Analysis**
- **Data Description**: Mean, Median, Mode, and Interquartile ranges of all the numerical variables.
- **Skewness**: Skewness of all the numerical variables used.
- **Frequency Distribution**: Pie charts representing the frequency distribution of all the categorical variables.
- **Histograms**: Histograms representing all the numerical variables is used.
  
### **Bivariate Analysis**
- **Bar Plots**: Compare numerical variables across different categories.
- **Violin Plots**: Visualize distribution and density of numerical variables.
- **Box Plots**: Identify outliers and distribution differences.
- **Scatter Plots**: Understand relationships between numerical variables.

### **Multivariate Analysis**
- **Pair Plots**: Visualize multiple variable relationships simultaneously.
- **Heatmap**: Analyze correlation among numerical features.
- **Grouped Comparisons**: Compare multiple categorical features against a numerical variable (e.g., salary by specialization, work experience, and gender).
