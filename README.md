# House Price Prediction using Machine Learning

AI/ML project for Odd Semester (3rd Sem) internship/project work.

**Name:** Ayush Ranjan
**Roll No:** 25SCS1003004921
**Section:** BTECHCSE-003-CSE3
**University:** IILM University

## Problem Statement
Predict the median house value of California districts from census features such as median income, house age, rooms and location.

## Dataset
California Housing dataset (scikit-learn built-in): 20,640 rows, 8 input features, 1 target (MedHouseVal, in units of $100,000). No missing values.

## Approach
1. Data cleaning and EDA
2. Train-test split (80/20)
3. Models: Linear Regression and Random Forest
4. Evaluation using RMSE and R2

## Results
| Model | RMSE | R2 |
|---|---|---|
| Linear Regression | 0.746 | 0.576 |
| Random Forest | 0.505 | 0.805 |

Random Forest performed better and was selected as the final model.

## Files
- ml_project.ipynb: Colab notebook with full code and outputs
- Report_Ayush_Ranjan.pdf: project report
- Graph images: EDA histograms and actual vs predicted plot

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib
