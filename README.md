# Health-Care-Cost-Analysis-
🏥 Medical Insurance Cost Prediction
This project analyzes a health insurance dataset to explore how different factors affect medical charges. The dataset includes the following features:

age: Age of the primary beneficiary

sex: Gender of the individual (male, female)

bmi: Body Mass Index – a measure of body fat based on height and weight

children: Number of children covered by the insurance

smoker: Smoking status (yes, no)

region: Residential area in the US (northeast, northwest, southeast, southwest)

charges: Medical costs billed by the insurance

🔍 Objectives
Perform exploratory data analysis (EDA)

Visualize relationships using data visualization tools

Build a predictive model to estimate insurance charges

Understand the impact of lifestyle and demographic variables on insurance costs

🛠 Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (Linear Regression, Decision Tree, etc.)

Jupyter Notebook


health insurance cost analysis script is detailed and covers key areas of exploratory data analysis (EDA), including:

Data Loading & Cleaning

Outlier Detection & Handling

Univariate and Bivariate Analysis

Visualizations using matplotlib and seaborn

Here’s a quick summary of what’s good and a few improvements you could consider:

✅ Strengths
**Clear Preprocessing**

Renaming columns for better readability.

Rounding off numerical values for consistency.

Good use of .copy() to preserve original data.

**Outlier Handling**

Provides both removal and replacement strategies.

Uses IQR method correctly for detecting outliers.

Visualizes boxplots before and after cleaning—great for verification.

**Comprehensive EDA**

Histograms, boxplots, scatter plots, and correlation heatmaps all provide strong insight into the data distribution and relationships.

Categorical analysis via bar plots and pd.crosstab() is well done.

**Comments & Readability**

Clear and educational inline comments explain each step.

Logical flow from loading data → preprocessing → EDA.
