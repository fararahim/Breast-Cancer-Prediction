# Diagnosing Brest Cancer
A ML project that uses clinical tumor measurements to predict whether a breast cancer diagnosis is malignant or benign.

# Dataset
The data.csv contains measurements from breast cancer biopsies, including features such as:
- radius_mean, perimeter_mean, area_mean
- compactness_mean, concavity_mean, concave points_mean
- radius_se, area_se, radius_worst, perimeter_worst, compactness_worst
- diagnosis — the target variable (M = Malignant, B = Benign)

# Requirements
- Python
- pandas
- matplotlib
- scikit-learn

Install dependencies with:
pip install pandas matplotlib scikit-learn

# How to Run
- Place data.csv in the same folder as the notebook
- Open Diagnosing Brest Cancer.ipynb in Jupyter Notebook
- Run all cells from top to bottom

# Model
This project uses a Random Forest Classifier from scikit-learn. Other classifiers imported for potential comparison include KNeighbors, SVC, and MLPClassifier.
