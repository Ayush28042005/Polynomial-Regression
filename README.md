# Polynomial Regression - Position Salary Prediction

Predicting salaries based on job position levels using Polynomial Regression. Built to understand why linear models fail on curved data and how polynomial feature transformation fixes it.


## Dataset

- **Position_Salaries.csv** - 10 records with Position Level (1–10) and corresponding Salary


## What I Did

- Visualised the data to confirm non-linear salary growth
- Trained a Linear Regression model as a baseline
- Applied Polynomial feature transformation (degree 4)
- Trained a Polynomial Regression model on transformed features
- Compared both models visually - polynomial curve vs straight line


## Key Insight

Linear regression severely underfits this dataset — salary grows exponentially at higher levels, not linearly. Polynomial regression captures this curve and predicts far more accurately.


## Tech Stack

Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook


## How to Run

```bash
git clone https://github.com/Ayush28042005/Polynomial-Regression.git
cd Polynomial-Regression
pip install pandas numpy matplotlib scikit-learn
jupyter notebook polynomial-regression.ipynb
```


## Author

Ayush Saini


