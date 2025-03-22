# Polynomial Regression

## Overview
This project demonstrates the implementation of **Polynomial Regression** using Python and Scikit-Learn. It predicts salaries based on job levels by fitting a polynomial regression model to the dataset.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

## Dataset
The dataset used in this project contains job positions, levels, and corresponding salaries.

### Sample Data:
```
            Position  Level   Salary
0   Business Analyst      1    45000
1  Junior Consultant      2    50000
2  Senior Consultant      3    60000
3            Manager      4    80000
4    Country Manager      5   110000
5     Region Manager      6   150000
6            Partner      7   200000
7     Senior Partner      8   300000
8            C-level      9   500000
9                CEO     10  1000000
```

## Steps Implemented
1. **Import Libraries**: Loaded necessary Python libraries.
2. **Load Dataset**: Read dataset from a CSV file.
3. **Data Visualization**: Plotted the dataset to understand the relationship between job level and salary.
4. **Polynomial Regression Model**:
   - Transformed the features to polynomial form.
   - Fitted the model using `LinearRegression`.
5. **Model Evaluation**:
   - Calculated RMSE (Root Mean Squared Error) and R² score.
   - Extracted model coefficients and intercept.
6. **Prediction**:
   - Predicted salary for a job level of 11.
   
## Results
- **Model Equation**: `f(x) = 232166.67 + 0.00*x^0 - 132871.21*x^1 + 19431.82*x^2`
- **RMSE**: `82212.12`
- **R² Score**: `0.9162`
- **Predicted Salary for Level 11**: `1121833.33`

## Visualizations
- Scatter plot of job levels vs. salaries.
- Polynomial regression fit overlayed on the dataset.

## How to Run
1. Clone the repository:
   ```sh
   git clone <repo_url>
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Run the script:
   ```sh
   python script.py
   ```

## Conclusion
Polynomial Regression is a powerful technique for modeling non-linear relationships. The model achieved a high R² score, indicating a good fit to the data.

## Author
**Hamza Aslam**

---
Feel free to contribute or raise issues! 🚀

