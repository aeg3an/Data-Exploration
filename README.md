# Placement Data Analysis

## Project Overview
This project performs **Bivariate and Multivariate Analysis** on a placement dataset to explore relationships between **categorical and numerical variables**. Various visualization techniques are used to understand the impact of factors like gender, academic performance, work experience, and specialization on salary and placement status.

## Dataset
The dataset used contains multiple numerical and categorical variables representing students' academic details, work experience, and placement status.

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
- Salary (if placed)

## Exploratory Data Analysis (EDA)
### **Bivariate Analysis**
- **Bar Plots**: Compare numerical variables across different categories.
- **Violin Plots**: Visualize distribution and density of numerical variables.
- **Box Plots**: Identify outliers and distribution differences.
- **Scatter Plots**: Understand relationships between numerical variables.

### **Multivariate Analysis**
- **Pair Plots**: Visualize multiple variable relationships simultaneously.
- **Heatmap**: Analyze correlation among numerical features.
- **Grouped Comparisons**: Compare multiple categorical features against a numerical variable (e.g., salary by specialization, work experience, and gender).

## How to Run the Code
1. Install dependencies:
   ```sh
   pip install pandas seaborn matplotlib
   ```
2. Load the dataset (`Placement_Data_Full_Class.csv`).
3. Run the script to generate visualizations.

## Visualizations
This project generates multiple visualizations that help in understanding placement trends and key influencing factors.

## License
This project is open-source and free to use.

## Author
Megh Bhavesh Shah

