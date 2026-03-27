# ames-housing-analysis
# Ames Housing Analysis

## 📊 Project Overview
This project explores the Ames Housing dataset to understand the key factors that influence house prices. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and a final dashboard.

## 🧹 Phase 1: Data Cleaning
- Handled missing values using median and mode
- Removed duplicates
- Treated outliers using capping
- Ensured data consistency with validation checks

## ⚙️ Phase 2: Feature Engineering
- Applied one-hot encoding for categorical variables
- Standardised numerical features using StandardScaler
- Created new features such as:
  - `price_per_sqft`
  - `total_bathrooms`
  - `quality_x_area`
- Applied log transformation to reduce skewness

## 📈 Phase 3: Exploratory Data Analysis
- Visualised distributions using histograms and KDE
- Compared categories using boxplots
- Analysed relationships using scatter plots
- Used heatmaps to identify correlations
- Performed groupby analysis for deeper insights

## 🧠 Math Analysis
- Computed mean and standard deviation manually
- Applied standardisation using z-score
- Calculated cosine similarity between records
- Estimated probability for high-quality houses

## 📊 Dashboard
A combined visual dashboard showing key insights:
- Distribution of house prices
- Relationship between size and price
- Price comparison across categories
- Top correlated features

## 🔑 Key Insights
- House size and quality strongly influence price
- Larger houses tend to have higher prices
- House style affects price distribution
- Some features show strong correlation with SalePrice

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📌 Conclusion
This project demonstrates how data preprocessing and analysis can reveal meaningful patterns in real-world datasets and support better decision-making.
