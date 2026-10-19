🎗️ Breast Cancer Classification Using SVM

📌 Project Overview

This project uses Machine Learning to classify breast cancer tumours as Benign (B) or Malignant (M) using the Support Vector Machine (SVM) algorithm.

The model is built using Python and Scikit-learn, with data preprocessing, feature scaling, kernel comparison, and hyperparameter tuning.

🎯 Objectives

- Explore and preprocess the dataset.
- Apply feature scaling using StandardScaler.
- Train an SVM classification model.
- Compare Linear and RBF kernels.
- Tune hyperparameters using GridSearchCV.
- Evaluate performance using classification metrics and a confusion matrix.

🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

📂 Dataset

The Breast Cancer Wisconsin dataset contains:

- 569 records
- 30 numerical input features
- 1 target column: "diagnosis"

Target labels:

- "B" — Benign
- "M" — Malignant

Features include measurements such as radius, texture, perimeter, area, smoothness, and symmetry.

⚙️ Project Workflow

1. Load and explore the dataset using Pandas.
2. Check for missing values and remove unnecessary columns.
3. Separate the features and target variable.
4. Split the data into 80% training and 20% testing sets.
5. Standardize features using StandardScaler.
6. Train SVM models using Linear and RBF kernels.
7. Compare model performance.
8. Tune hyperparameters using GridSearchCV with 5-fold cross-validation.
9. Evaluate the tuned model on the test set.
10. Save the trained pipeline using Joblib.

📊 Results

Metric| Result
Linear SVM test accuracy| 96.49%
RBF SVM test accuracy| 97.37%
Tuned SVM test accuracy| 97.37%
Tuned model CV accuracy| 97.58%
Best "C"| 10
Best "gamma"| "scale"

The tuned model achieved 97.37% test accuracy on 114 test records.

For the malignant class, recall was approximately 92.86%, meaning the model identified 39 of the 42 malignant records in the test set.

🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab.
3. Upload the dataset CSV file.
4. Run the notebook cells in order.
5. Review the predictions, evaluation metrics, and confusion matrix.

🔮 Future Improvements

- Explore additional SVM hyperparameter combinations.
- Compare SVM with Logistic Regression and Random Forest.
- Evaluate performance on independent datasets.
- Build a simple interface for educational demonstrations.

⚠️ Disclaimer

This project is for educational purposes only. The model is not clinically validated and must not be used for medical diagnosis or treatment decisions.

👩‍💻 Author

Sreyarag k

Machine Learning Project | Python | Scikit-learn
