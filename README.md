🧠 Support Vector Machine (SVM) — Classification
This project is part of an AI & ML Internship focused on binary classification using SVMs.

📄 Objective
To classify tumors as malignant or benign using the Breast Cancer dataset with Support Vector Machine (SVM) models, including both linear and RBF kernels.

📋 Steps:
1. Loaded the Breast Cancer dataset using Pandas.
2. Displayed top rows and basic info using head() and info().
3. Checked for missing values and data types.
4. Converted target column diagnosis into binary labels (M = 1, B = 0).
5. Dropped unnecessary columns (id, Unnamed: 32).
6. Standardized features using StandardScaler.
7. Split data into training and testing sets.
8. Trained SVM model using linear kernel.
9. Trained SVM model using RBF kernel.
10. Tuned hyperparameters C and gamma using GridSearchCV.
11. Evaluated performance using confusion matrix and classification report.
12. Performed cross-validation to check model stability.

🛠 Tools Used
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn

✅ Files
breast-cancer.csv
Task_07.ipynb
README.md
