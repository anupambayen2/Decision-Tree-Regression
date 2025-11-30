Project Summary: Salary Prediction Using Decision Tree Regression

This project applies a Decision Tree Regression model to predict an employee’s salary based on their position level. It is part of my daily machine learning practice and GitHub uploads.

📌 Objective

To understand how decision trees split data into regions and use them to model non-linear salary trends.

📊 Dataset

The dataset (Position_Salaries.csv) contains:

Position

Level (1–10)

Salary

The salary pattern is clearly non-linear, making it suitable for tree-based models.

🛠️ Steps Performed

Loaded and explored the dataset

Trained a Decision Tree Regression model

Visualized the predictions vs actual salary

Showed how decision trees produce a step-wise prediction curve

Predicted salary for a specific level (e.g., 6.5)

📈 Key Insight

Decision Trees divide the data into intervals and predict constant values within each interval.

Results in a step function, unlike smooth curves from linear, polynomial, or SVR models.

Works well for non-linear datasets but can overfit if not tuned properly.

🧪 Outputs

Step-wise decision tree regression plot

Scatter plot of actual salary data

Predicted salary at a chosen level

🚀 Conclusion

Decision Tree Regression provides an intuitive, rule-based approach to modeling non-linear relationships. Although simple and interpretable, it requires careful tuning to avoid overfitting, especially with small datasets.
