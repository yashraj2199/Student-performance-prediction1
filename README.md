# Student Performance Prediction Using Linear Regression and PCA

**B.Tech CSE Mini Project | Intermediate Level**

## Team Members
- Yashraj Sahu
- Aditya Malviya
- Riya Mane
- Saish Uplenchwar

## Project Overview
This project predicts a student's final Mathematics grade (`G3`, on a 0–20 scale) using the Kaggle Student Performance dataset. It applies data preprocessing, Principal Component Analysis (PCA) for dimensionality reduction, and Linear Regression for prediction.

**Scope note:** The model includes `G1` and `G2` (earlier-period grades) among its inputs. It therefore predicts the final grade after earlier grades are known, rather than making a prediction before any assessments.

## Dataset
Download the dataset from:
https://www.kaggle.com/datasets/uciml/student-alcohol-consumption

1. Download and extract the Kaggle ZIP file.
2. Copy `student-mat.csv` into the same folder as the notebook.
3. The notebook reads this semicolon-separated file using `sep=';'`.

The Mathematics file contains 395 student records and 33 columns (including the target `G3`).

## Files
- `student_performance_prediction.ipynb` — complete Jupyter Notebook code.
- `project_report.docx` — short college-ready project report.
- `requirements.txt` — Python dependencies.

## Run in Jupyter Notebook
1. Install Python and Jupyter Notebook.
2. Install dependencies: `pip install -r requirements.txt`
3. Download `student-mat.csv` from Kaggle and place it beside the notebook.
4. Open `student_performance_prediction.ipynb`.
5. Run cells from top to bottom.
6. Record the actual MAE, RMSE, R², PCA component count, and charts shown by your run in the report.

Alternatively, upload the notebook and CSV to Google Colab and run the cells there.

## Algorithms and Libraries
- Linear Regression
- Principal Component Analysis (PCA)
- pandas, NumPy, Matplotlib, scikit-learn, joblib

## Evaluation
The notebook calculates:
- MAE — mean absolute error
- RMSE — root mean squared error
- R² — coefficient of determination

No performance numbers are hard-coded. They are calculated from the dataset when the notebook is run.

## GitHub Upload
Create a public repository named `Student-Performance-Prediction`, then upload this folder's files. Copy the repository URL from the browser address bar to share it with your faculty.

## Team
Yashraj Sahu | Aditya Malviya | Riya Mane | Saish Uplenchwar
