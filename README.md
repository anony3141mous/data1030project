Overview
This repository contains the code and data used to predict ad clicks based on user features, including device type, gender, and time of day, using various machine learning models. The main objective is to predict whether a user will click on an advertisement, a crucial task in digital marketing for personalized advertising strategies. This project employs four popular classification algorithms—Random Forest Classifier (RFC), XGBoost (XGB), Support Vector Classifier (SVC), and K-Nearest Neighbors (KNN)—to build and evaluate prediction models, with performance measured using the F1 score.

The project also investigates the importance of various features through SHAP (SHapley Additive exPlanations) values and permutation testing to explain the model’s predictions.

├── data/          # Directory containing the dataset used for training and testing
├── figures/       # Directory for saving generated plots and visualizations
├── results/       # Directory to store results like model performance metrics, confusion matrices, etc.
├── report/        # Directory for storing project report and documents
├── src/           # Source code for data preprocessing, model training, evaluation, and interpretation
├── .gitignore     # Git ignore file to exclude unnecessary files from version control
├── LICENSE        # License for the project
└── README.md      # This file, describing the project

Installation
To run this project locally and reproduce the results, ensure you have the correct environment. The project is built using Python, and the required packages and versions are listed below.

Python Version
This project is developed using Python 3.8.

Required Packages
The main Python libraries used in this project include:

pandas: Data manipulation and analysis.
numpy: Numerical computations.
scikit-learn: Machine learning algorithms and tools.
xgboost: For XGBoost models.
matplotlib: Plotting and visualization.
shap: For model interpretability.
seaborn: For statistical data visualization.


Results
The trained models and evaluation metrics will be stored in the results/ folder, including:

F1 scores for each model.
Confusion matrix visualizations.
SHAP values for model interpretability.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Scikit-learn for providing the machine learning models and utilities.
XGBoost for the efficient gradient boosting model.
SHAP for the interpretable machine learning framework.
Matplotlib and Seaborn for the beautiful visualizations.
