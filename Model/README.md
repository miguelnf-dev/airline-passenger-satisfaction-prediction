# Overview
This notebook presents a comprehensive approach to applying Supervised Learning (SL) models and evaluates the enhancement of classification results using Unsupervised Learning (UL) strategies.

## Contents

1. **Library and Data Importation**: Essential libraries for data manipulation, visualization, and model creation are imported. The dataset "Airline-Passenger-Satisfaction_m2.csv" is loaded for analysis.

2. **Data Preprocessing**: Includes transformations using `StandardScaler`, `MinMaxScaler`, and `OneHotEncoder` for numerical and categorical data.

3. **Model Training and Evaluation**:
    - Supervised Learning Models: Includes Logistic Regression, SVM, K-Nearest Neighbors, Decision Trees, Naive Bayes, Random Forest, and ANN, each with hyperparameter tuning using GridSearchCV.
    - ROC Curve Plotting: Function to plot ROC curves for model evaluation.
    - Unsupervised Learning as Preprocessing: Utilizing clustering techniques (KMeans) combined with SL models to examine performance improvements.
    - Unsupervised Learning : Explores clustering algorithms like BIRCH, visualizations using t-SNE, and performance assessment using silhouette scores and other relevant metrics.

4. **Result Comparisons**: Compares the performance of different models using accuracy, precision, recall, and F1 scores.



