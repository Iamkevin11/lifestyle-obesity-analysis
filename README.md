# Lifestyle and Obesity Analysis

## 📌 Project Overview

This project explores the relationship between lifestyle habits, demographic characteristics, and obesity levels using Exploratory Data Analysis (EDA). The goal is to identify patterns in body mass index (BMI), age, physical activity, eating habits, and other lifestyle indicators through data analysis and visualization.

The project uses the **Estimation of Obesity Levels Based on Eating Habits and Physical Condition** dataset from the UCI Machine Learning Repository.

## 🎯 Objectives

- Clean and preprocess the dataset.
- Calculate Body Mass Index (BMI) using height and weight.
- Group individuals into age categories for analysis.
- Analyze the distribution of obesity levels.
- Compare BMI, weight, and physical activity across obesity categories.
- Explore relationships between numerical variables using correlation analysis.
- Present insights through clear and informative visualizations.

## 🛠️ Tools and Technologies

- **Python** — Data analysis and preprocessing
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical calculations
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive analysis environment

## 📂 Project Structure

```text
lifestyle-obesity-analysis/
│
├── README.md
├── obesity_lifestyle_preprocessed.csv
├── Lifestyle_and_Obesity_Analysis_Preprocessing.ipynb
├── Final Visualization(2).ipynb
└── Lifestyle_and_Obesity_Analysis_Report.pdf
```

## 📊 Dataset

**Source:** UCI Machine Learning Repository

**Dataset title:** Estimation of Obesity Levels Based on Eating Habits and Physical Condition

The dataset contains demographic information, eating habits, physical activity indicators, and obesity-level categories.

Key variables include:

- Age
- Gender
- Height
- Weight
- BMI
- Vegetable consumption
- Number of main meals
- Water consumption
- Physical activity
- Technology usage
- Obesity level

**Note:** The source dataset includes both collected and synthetic records. Therefore, findings should be interpreted as exploratory and should not automatically be generalized to the wider population.

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Inspected the dataset structure and data types.
- Checked for missing values and duplicate records.
- Reviewed categorical values for consistency.
- Prepared the dataset for exploratory analysis.

### 2. Feature Engineering
- Calculated BMI using the formula:

  `BMI = Weight (kg) / Height (m)²`

- Created age groups to compare obesity-level distributions across different age ranges.

### 3. Exploratory Data Analysis
The analysis includes:

- Distribution of obesity levels
- BMI distribution
- Age distribution
- Weight distribution by obesity level
- BMI distribution by obesity level
- Physical activity across obesity categories
- Obesity-level composition by age group
- Correlation analysis of numerical variables
- Relationship between weight and BMI
- Comparison of vegetable consumption and physical activity

### 4. Data Visualization
Charts were created using Matplotlib to make patterns, differences, and relationships easier to understand.

## 🔍 Key Areas of Analysis

- How obesity-level categories are distributed in the dataset
- How BMI and weight distributions differ across obesity categories
- How age groups contribute to the observed category distribution
- How physical activity and selected eating habits vary across records
- Which numerical variables show stronger or weaker linear relationships

The analysis describes patterns in the dataset and does not establish causal relationships between lifestyle factors and obesity.

## 📈 Results and Insights

The project provides a structured overview of obesity categories and related demographic and lifestyle variables. It demonstrates how data preprocessing, feature engineering, descriptive statistics, and visualization can be combined to investigate a real-world analytical question.

Refer to the project notebooks and PDF report for the detailed charts, interpretations, and findings.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/lifestyle-obesity-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd lifestyle-obesity-analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the preprocessing or visualization notebook and run the cells in order.

## ⚠️ Limitations

- The dataset contains synthetic as well as collected records.
- Some lifestyle variables use coded or ordinal values.
- Correlation does not imply causation.
- BMI is a derived measure based on height and weight and is not a complete measure of individual health.
- The findings describe this dataset and should not be interpreted as clinical conclusions.

## 👨‍💻 Author

**Kevin M Saleel**

Data Analytics Project

---

If you find this project useful, feel free to explore the notebooks and visualizations.

