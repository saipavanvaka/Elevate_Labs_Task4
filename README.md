# Task 4: Feature Encoding and Scaling

## Project Overview
This project focuses on **Feature Engineering** using the Adult Income Dataset. The goal was to transform raw data into a machine-learning-ready format by encoding categorical variables and scaling numerical features.

##  Feature Engineering Steps
1. **Identification**: Separated features into Categorical (text) and Numerical (numbers).
2. **Label Encoding**: Applied to ordinal data (like Education) where a specific rank exists.
3. **One-Hot Encoding**: Applied to nominal data (like Gender and Relationship) to prevent the model from assuming a mathematical order.
4. **Standard Scaling**: Used `StandardScaler` to normalize features like 'age' and 'hours-per-week', ensuring they share a similar scale.



##  Interview Questions & Answers
* **Label vs One-Hot Encoding?** Label encoding is for ordered data (1st, 2nd, 3rd). One-Hot encoding is for data with no order (Red, Blue, Green) to avoid biased weights.
* **Why is scaling required?** To prevent features with large ranges (like Capital Gain) from dominating features with small ranges (like Age).
* **What is Feature Engineering?** It is the process of selecting and transforming raw variables to create more effective inputs for a model.

##  Deliverables
* `Task4_Preprocessing.ipynb`: Complete Python code.
* `Processed_Adult_Income.csv`: The final dataset ready for model training.
