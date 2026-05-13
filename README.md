# Diagnosing Breast Cancer
A ML project that uses clinical tumor measurements to predict whether a breast cancer diagnosis is malignant or benign (dataset from kaggle)

## Dataset
The "data.csv" contains measurements from breast cancer biopsies, including features such as:
- radius_mean, perimeter_mean, area_mean
- compactness_mean, concavity_mean, concave_points_mean
- radius_se, area_se, radius_worst, perimeter_worst, compactness_worst
- diagnosis (the target variable (M = Malignant, B = Benign))

## Models
Four classifiers were trained and compared:
- Logistic Regression
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine (SVM)

## Requirements
- Python
- numpy
- pandas
- matplotlib
- scikit-learn

## Install dependencies with:
pip install numpy pandas matplotlib scikit-learn

## How to Run
- Place "data.csv" in the same folder as the notebook
- Open "Diagnosing Breast Cancer.ipynb" in Jupyter Notebook
- Run all cells from top to bottom
