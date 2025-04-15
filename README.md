
## Statistical Insights into Global Mortality: A Business Decision Processing Perspective

## 📌 Project Description
This project explores historical global mortality data with a specific focus on analyzing causes of death across various countries using fundamental statistical techniques. The dataset includes over 6,000 records and 36 variables detailing causes of death across age groups, geographies, and time.

The project utilizes business decision tools learned in the course, including confidence intervals, hypothesis testing, ANOVA, and multiple regression models, to extract actionable insights about global health trends.

---

## 🧾 Dataset Information

**Dataset Name**: Cause of Deaths 
**Source**: [Our World in Data via Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/cause-of-deaths-around-the-world)  
**Structure**:
- Rows: 6,091
- Columns: 36

### Overview
The dataset includes mortality data categorized by cause of death, year, country, and age group. It includes significant contributors to disease burden such as cardiovascular diseases, cancers, respiratory infections, and more. DALYs (Disability-Adjusted Life Years) are used as a key measurement metric in evaluating health outcomes.

---

## 🧮 Statistical Modules Implemented

### 📦 Module 1: Central Limit Theorem & Distribution of Sample Mean
- Calculated the probability that the mean cardiovascular disease rate for the U.S. would differ by more than 1,000 from the population mean.
- Sample Size: 20  
- Tools Used: Z-Distribution

### 📦 Module 2: Estimating the Population Mean (σ Unknown)
- Confidence interval (95%) estimation for Tuberculosis cases in Australia.
- Sample Size: 25  
- Tools Used: t-distribution, T.INV.2T function in Excel

### 📦 Module 3: Hypothesis Testing (σ Unknown)
- Tested the claim that the average female life expectancy in India is less than 68 years.
- Used left-tailed t-test with α = 0.05
- Tools Used: t-distribution, hypothesis formulation, p-value comparison

### 📦 Module 4: ANOVA - Comparison of Means
- Compared male vs. female life expectancy in Italy from 2010–2019.
- Used F-statistic from ANOVA table to determine statistical significance.
- Conclusion: Significant difference found at α = 0.01

### 📦 Module 5: Multiple Regression Model
- Created a regression model to estimate Tuberculosis rates based on male and female life expectancy in Thailand.
- Regression Equation:  
  `Estimated Tuberculosis = 82342.5858 + 1564.6339(Female LE) - 2642.4062(Male LE)`
- Model Evaluation:  
  - R² = 0.97063  
  - Adjusted R² = 0.96846  
  - Significance F (p-value) < 0.05  
- Conclusion: Statistically significant model with strong explanatory power.

---

## 🛠 Tools and Technologies Used
- **Microsoft Excel**: For data preprocessing, formula computation, and regression modeling.
- **SAS**: For statistical analysis and ANOVA outputs.
- **GitHub**: For project versioning and collaboration.
- **Markdown**: For documentation.

---

## 📁 Repository Structure

- Dataset
- Project Report
- SAS File


---

## 🧠 Key Learnings
- Practical application of business decision-making tools
- Understanding and applying statistical inference techniques
- Real-world insights using mortality and health outcome data
- Regression modeling with multiple independent variables

---

## 🧾 Citation

> Our World In Data, Kaggle Dataset: "Cause of Deaths Around the World"  
> https://www.kaggle.com/datasets/iamsouravbanerjee/cause-of-deaths-around-the-world
