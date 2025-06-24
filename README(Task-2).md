Task 2-Exploratory Data Analysis (EDA) on Titanic Dataset

Objective:
The goal of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the structure, distributions, patterns, relationships, and anomalies within the data using statistical methods and visualizations.
Key Steps Performed
1. Loaded the Titanic dataset
2. Generated summary statistics (mean, median, std, min, max)
3. Plotted histograms to understand distributions of numerical features
4. Used boxplots to detect outliers in features like Age and Fare
5. Created a correlation matrix using a heatmap to study feature relationships
6. Built pairplots for multi-feature visualization grouped by survival
7. Detected skewness in numerical columns
8. Visualized survival rate by passenger class (Pclass)

Tools & Libraries Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (optional interactive visualizations)

Dataset Source:
Kaggle: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

Output Highlights:
- Age and Fare distributions are right-skewed
- Outliers are present in `Fare` and `Age` columns
- Pclass and Sex have a strong correlation with survival
- Passengers in 1st class had a significantly higher survival rate
What I Learned:
- Effective use of statistical summaries
- Visualization methods for numeric and categorical data
- Understanding feature interactions and preparing for feature engineering