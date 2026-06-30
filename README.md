# PRODIGY_DS_02

## Task 02: Data Cleaning and Exploratory Data Analysis (EDA)

### Objective

Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to identify patterns, trends, and relationships between different features.

---

## Dataset

**Titanic Dataset**

The dataset contains passenger information such as age, gender, passenger class, fare, embarkation port, and survival status.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Project Workflow

- Imported the required libraries.
- Loaded the Titanic dataset using Pandas.
- Explored the dataset structure and checked data types.
- Identified missing values and inconsistencies.
- Cleaned the dataset by handling missing values and removing unnecessary columns.
- Performed exploratory data analysis (EDA).
- Created visualizations to understand relationships between different variables.
- Interpreted the findings and summarized key insights.

---

## Visualizations

### 1. Missing Values Heatmap

Visualizes missing values across different features in the dataset.

### 2. Survival Distribution

Shows the overall distribution of passengers who survived and those who did not.

### 3. Survival by Gender

Compares survival rates between male and female passengers.

### 4. Survival by Passenger Class

Analyzes how passenger class influenced survival.

### 5. Age Distribution

Displays the distribution of passenger ages using a histogram.

### 6. Correlation Matrix

Illustrates correlations among numerical variables using a heatmap.

---

## Key Findings

- Female passengers had a significantly higher survival rate than male passengers.
- Passengers traveling in First Class were more likely to survive.
- Most passengers were between 20 and 40 years of age.
- Missing values in the Age and Embarked columns were handled during preprocessing.
- Passenger Class and Gender showed a strong relationship with survival.

---

## Results

### Missing Values Analysis

The missing values heatmap revealed that the **Age** column contained several missing values, while the **Cabin** column had a significant number of missing entries. The **Embarked** column contained only a few missing values. Appropriate preprocessing techniques were applied to handle these missing values before performing the analysis.

### Survival Distribution

The survival distribution showed that the number of passengers who did not survive was higher than those who survived, indicating an imbalanced target variable.

### Survival by Gender

The visualization demonstrated that female passengers had a considerably higher survival rate than male passengers, suggesting that gender played a significant role in survival.

### Survival by Passenger Class

Passengers traveling in First Class had the highest survival rate, whereas Third Class passengers experienced the lowest survival rate.

### Age Distribution

The age distribution indicated that most passengers were between **20 and 40 years** of age, with relatively fewer elderly passengers.

### Correlation Analysis

The correlation matrix highlighted positive and negative relationships among numerical variables. Passenger class showed a noticeable relationship with survival, while age exhibited only a weak correlation.
---

## Project Structure

```
PRODIGY_DS_02/
│
├── data/
│   └── titanic.csv
│
├── images/
│   ├── missing_values_heatmap.png
│   ├── survival_distribution.png
│   ├── survival_by_gender.png
│   ├── survival_by_class.png
│   ├── age_distribution.png
│   └── correlation_matrix.png
│
├── notebook/
│   └── Task_02.ipynb
│
└── README.md
```

---

## Conclusion

This project demonstrates the importance of data cleaning and exploratory data analysis in preparing data for further analysis and machine learning. By handling missing values and visualizing important relationships, meaningful insights were extracted from the Titanic dataset.

---

## Author

**Chetan Jadhav**

GitHub: https://github.com/chetan-23012006


---

## Internship

**Prodigy InfoTech – Data Science Internship**
