# Placement Data Analysis

## Project Overview
This project performs **Bivariate and Multivariate Analysis** on a placement dataset to explore relationships between **categorical and numerical variables**. Various visualization techniques are used to understand the impact of factors like gender, academic performance, work experience, and specialization on salary and placement status.

## Dataset
The dataset used contains multiple numerical and categorical variables representing students' academic details, work experience, and placement status.

## Features Analyzed
### **Categorical Variables**
- Gender
- SSC Board (`ssc_b`)
- HSC Board (`hsc_b`)
- HSC Specialization (`hsc_s`)
- Degree Type (`degree_t`)
- Work Experience (`workex`)
- Specialization (`specialisation`)
- Placement Status (`status`)

### **Numerical Variables**
- Secondary Education Percentage (`ssc_p`)
- Higher Secondary Percentage (`hsc_p`)
- Degree Percentage (`degree_p`)
- Employability Test Percentage (`etest_p`)
- MBA Percentage (`mba_p`)
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

