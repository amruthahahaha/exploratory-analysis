Project 2: Exploratory Data Analysis on Titanic Dataset

Overview
The objective of this project is to carry out Exploratory Data Analysis (EDA) on the Titanic dataset (`titanic2.csv`). The purpose is to get to know the dataset through descriptive statistics and plots. The analysis aids in recognizing patterns, trends, relationships, and outliers prior to any model-building process.

Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

Steps Performed

1. Data Loading
Imported the Titanic dataset (`titanic2.csv`) into a Pandas DataFrame.

2. Data Cleaning  
   - Completed missing data in the `Age` and `Embarked` columns.
   - Removed the `Cabin` column and the rest of the null values.

3. Descriptive Statistics  
   - Calculated measures like mean, median, and standard deviation.

4. Data Visualization  
   - Histograms for data distribution
- Boxplots to identify outliers
- Heatmap for the correlation matrix
- Pairplot to visualize feature relationships
- Bar plots for comparisons based on categories (e.g., survival by gender and class)

5. Observations
   - More female passengers survived compared to males.
   - Passengers in the 1st class had greater survival prospects.
- `Pclass` and `Fare` were found to be correlated with `Survived`.
- `Age` and `Fare` had outliers as shown in boxplots.


 Files in This Repository

| File Name         | Description                                 |
|-------------------|---------------------------------------------|
| `project_2.ipynb` | Jupyter Notebook with the EDA steps         |
| `titanic2.csv`    | Dataset used for analysis                   |
| `README.md`       | Documentation and project summary           |


Status
Completed. The project includes all required steps for EDA and is ready for evaluation or future extensions.
