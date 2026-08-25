# Student Academic Performance & Habits Predictive Modeling

An analytical data science project developed in collaboration with the **Cal Poly Pomona (CPP) Data Science & AI Club**. This project explores behavioral, lifestyle, and study habits from the `student_digital_life.csv` dataset to identify the inflection point where specific habits impact a student's final exam scores.

## Project Overview
The objective was to predict student academic outcomes by evaluating variables like daily study hours, caffeine intake, and digital usage. The team built and benchmarked a regression baseline alongside a binned classification pipeline to observe how behavioral metrics correlate with performance.

## Key Features & Workflow
- **Data Cleaning & Engineering:** Managed missing values and engineered outlier filtering using the Interquartile Range (IQR) threshold. Performed feature engineering via one-hot encoding for categorical variables.
- **Exploratory Data Analysis (EDA):** Leveraged Seaborn and Matplotlib to map out Pearson, Spearman, and Kendall rank correlations to identify key non-linear dependencies.
- **Model Development:** 
  - Implemented a baseline **Linear Regression** model to predict raw final exam scores.
  - Developed a **K-Nearest Neighbors (KNN)** Classifier to segment students into granular academic performance brackets (`failing`, `okay`, `good`).

## Technologies Used
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

## How to Run
1. Clone this repository.
2. Ensure you have the required packages installed: `pip install pandas numpy scikit-learn seaborn matplotlib`
3. Run the Jupyter Notebook or Python script to view the EDA plots and model evaluation metrics.


