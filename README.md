## 🚢 Titanic Survival Exploratory Data Analysis (EDA)
##### 📌 Project Overview
This project analyzes the famous Titanic dataset to explore key survival factors using Exploratory Data Analysis (EDA). The dataset includes passenger details such as age, class, gender, fare, and survival status. Through data visualization and statistical insights, we uncover patterns that influenced survival outcomes.

#### 🗂️ Dataset Information
Total Rows: `891`
Total Columns: `15`
##### Column Types:
`Numerical`: Age, Fare
`Categorical:` Survived, Class, Sex, SibSp, Parch, Embarked, Who
`Boolean:` Adult Male, Alive, Alone
#### 🔎 Key Analysis Performed
##### Data Exploration
- Loaded the dataset using Seaborn
- Checked missing values, data types, and statistical summaries
- Identified numerical and categorical variables
##### Univariate Analysis
- Distribution of Age (Normal distribution, 19% missing values)
- Fare distribution and outliers
##### Bivariate Analysis
- Relationship between Survival & Gender
- Impact of Passenger Class on Survival
- Correlation between Fare and Survival
#### Visualizations Used
- Histograms & KDE plots for numerical distributions
- Count plots & Bar charts for categorical data
- Box plots & Violin plots for outlier detection
- Heatmap for correlation analysis
#### 🛠️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook for implementation
#### 🎯 Key Takeaways
- Higher survival rates for women and children.
- First-class passengers had a significantly higher survival rate.
- Fare prices influenced survival chances.
- The dataset contains missing values, requiring imputation strategies.
#### 📌 Future Improvements
- Handle missing values for improved analysis.
- Apply Machine Learning models for survival prediction.
- Implement interactive visualizations using Plotly.