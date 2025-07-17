Exploratory Data Analysis (EDA) on Student Performance Dataset
🚀 Prodigy Infotech – Data Science Internship Task 2
🎯 Project Objective
The objective of this project is to perform a comprehensive Exploratory Data Analysis (EDA) on a Student Performance dataset to:

Understand the key factors influencing student academic performance

Identify patterns and relationships across various demographic and academic variables

Derive actionable insights that may assist in improving educational outcomes or identifying students at academic risk

📁 Dataset Description
Dataset Title: Student Performance in Exams

Number of Rows: 1000 (approx.)

Number of Columns: 8

📌 Key Features/Columns:
gender: Gender of the student (male/female)

race/ethnicity: Group classification of students

parental level of education: Highest education level of the parent

lunch: Type of lunch (standard/free-reduced)

test preparation course: Whether the student completed a test prep course

math score: Score in mathematics

reading score: Score in reading

writing score: Score in writing

🔍 Key Analysis Steps Performed
📥 1. Data Loading and Initial Inspection
Loaded dataset using pandas

Viewed first few records, checked shape and data types

🚫 2. Handling Missing Values
Checked for missing/null values

Confirmed that dataset had no missing entries

📊 3. Descriptive Statistics
Generated summary statistics for numerical features

Analyzed categorical columns using value counts

📈 4. Univariate Analysis
Plotted histograms, boxplots for math, reading, and writing scores

Examined distributions and score ranges

Countplots for categorical features like gender, race/ethnicity, parental level of education, etc.

🔗 5. Bivariate/Multivariate Analysis
Analyzed score distributions across:

Gender

Parental education level

Lunch type

Test preparation course

Used:

Box plots

Violin plots

Bar plots

Calculated and visualized correlation matrix using heatmap

⚠️ 6. Outlier Detection
Identified score outliers using boxplots

🛠️ Tools and Libraries Used
Language: Python

Environment: Jupyter Notebook

🧰 Libraries:
pandas – Data manipulation

numpy – Numerical computations

matplotlib – Basic data visualization

seaborn – Advanced statistical plots and styling

📌 Conclusion
This EDA provided insights into how demographic and background variables impact student performance. Some key findings included:

Female students showed slightly higher average reading and writing scores

Students who completed test preparation performed better across all subjects

Parental education level positively influenced scores

