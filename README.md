# Heart Disease Prediction

Machine learning project for predicting heart disease using clinical and patient-related features.

## Dataset

- File: `heart.csv`
- Records: 303
- Features: 13
- Target: `target`

## Workflow

1. Data inspection and exploratory data analysis
2. Categorical feature handling and preprocessing
3. Outlier treatment
4. RobustScaler feature scaling
5. Stratified train/test split
6. Classification model comparison
7. ROC curve and classification evaluation
8. 10-fold cross-validation
9. Logistic Regression hyperparameter tuning with GridSearchCV

## Models

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

## Results

Test-set accuracy:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 84% |
| SVM | 77% |
| Decision Tree | 77% |
| Random Forest | 81% |

10-fold cross-validation accuracy:

| Model | CV Accuracy |
|---|---:|
| Logistic Regression | 84.1% |
| SVM | 83.4% |
| Decision Tree | 72.8% |
| Random Forest | 78.5% |

GridSearchCV selected Logistic Regression with L1 regularization and the `liblinear` solver; its tuned cross-validation accuracy was approximately 84.1%.

## Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy

## How to Run

1. Install dependencies from `requirements.txt`.
2. Open `Heart_Disease_Prediction.ipynb`.
3. Run the notebook cells from top to bottom.
