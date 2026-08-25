# Student Habits & Academic Performance Predictive Modeling

An analytical data science project developed in collaboration with the **Cal Poly Pomona (CPP) Data Science & AI Club**. 

## The Core Question
**Do extreme habits—such as studying too much or too little, or using social media too much or too little—directly affect college grades?** 

This project explores student behavioral, digital, and lifestyle metrics from the `student_digital_life.csv` dataset to identify the exact thresholds and inflection points where daily habits begin to hurt or help academic performance.

## Project Overview
The objective was to move beyond simple linear correlations and uncover the hidden patterns in how student lifestyles dictate success. The team built and benchmarked a regression baseline alongside a binned classification pipeline to observe how behavioral metrics group together to predict performance.

## Key Features & Workflow
- **Exploratory Data Analysis (EDA):** Leveraged Seaborn and Matplotlib to map out Pearson, Spearman, and Kendall rank correlations to catch both linear and non-linear behavioral dependencies.
- **Data Cleaning & Engineering:** Managed anomalies and isolated extreme behavioral traits using the Interquartile Range (IQR) threshold. Prepared categorical inputs via one-hot encoding (`pd.get_dummies`).
- **Model Development:** 
  - Implemented a baseline **Linear Regression** model to track continuous final exam score trends.
  - Developed a **K-Nearest Neighbors (KNN)** Classifier to group similar student habit profiles and segment them into performance brackets (`failing`, `okay`, `good`).

## Technologies Used
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

## Final Conclusion

This project explored how students' daily habits, digital behavior, and academic routines relate to their overall academic performance. Rather than treating any single behavior as the deciding factor in student success, the analysis shows that academic performance is influenced by a combination of factors such as study habits, class attendance, assignment completion, motivation, sleep, and digital activity.

The exploratory analysis also highlights why looking beyond simple correlations is important. Student behavior is complex, and habits such as smartphone use, social media, gaming, studying, and sleep can interact with one another rather than affecting grades independently. By examining these relationships and preparing the data for predictive modeling, the project provides a foundation for identifying behavioral patterns associated with different levels of academic performance.

Ultimately, the project demonstrates how data science can be used to transform everyday student habits into measurable patterns. These insights could be expanded in future work with additional models, feature engineering, and larger or real-world datasets to better determine which combinations of habits are most strongly associated with academic success.
