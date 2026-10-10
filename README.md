# Student Performance Prediction

A beginner-friendly machine learning project that explores a **synthetic dataset of 500 students** and uses Linear Regression to estimate final scores from study hours and previous scores.

> **Important:** This is an educational demonstration using synthetic data, not real student records. Predictions are not guarantees and should not be used to make real educational decisions.

## Dataset

File: `student_performance_500_synthetic.csv`

Columns:
- `Student_ID`: synthetic student identifier
- `Name`: synthetic student name
- `Study_Hours_Per_Day`: study hours per day
- `Previous_Score`: previous exam score
- `Final_Score`: sample final score (target)

Rows: 500

## Model

- Algorithm: Linear Regression (`scikit-learn`)
- Features: `Study_Hours_Per_Day`, `Previous_Score`
- Target: `Final_Score`
- Split: 80% training, 20% testing (`random_state=42`)
- Metrics: Mean Absolute Error (MAE), R² score

## Run in Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Upload `student_performance_500_synthetic.csv` using the file upload cell.
4. Run the notebook cells in order.

## Libraries

- pandas
- matplotlib
- scikit-learn

## Future Improvements

- Add more exploratory data analysis
- Compare Linear Regression with other regression models
- Add cross-validation and residual analysis
- Build a simple prediction interface

## Responsible Use

The data is synthetic and may not reflect real student outcomes. The model is for learning only and is not suitable for evaluating or ranking real students.
