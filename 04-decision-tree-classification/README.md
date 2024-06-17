# Decision Tree Classification Model

## Project Overview
This project involves building and evaluating a decision tree model to classify species of Iris flowers using the Iris dataset.

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
The dataset used in this project is the Iris dataset, which contains measurements of iris flowers from three different species.

## Steps Performed
1. Import the Libraries
2. Data Loading
3. Data Exploration
4. Data Visualization
5. Feature Engineering
6. Data Preprocessing and Model Training
7. Hyperparameter Tuning
8. Cross-Validation
9. Comparison with Other Models
10. Visualize the Decision Tree
11. Confusion Matrix for All Models
12. Model Persistence
13. Overall Results and Conclusion

## Results
- **Decision Tree Accuracy:** 0.9667
- **KNN Accuracy:** 1.0
- **Logistic Regression Accuracy:** 1.0
- **Mean Cross-Validation Score for Decision Tree:** `dt_cv_scores.mean()`
- **Mean Cross-Validation Score for KNN:** 0.96
- **Mean Cross-Validation Score for Logistic Regression:** 0.953

## Conclusion
The decision tree model effectively classified iris species with an accuracy score of 0.9667. Cross-validation scores further validated the model's robustness with a mean cross-validation score of `dt_cv_scores.mean()`.

The KNN and Logistic Regression models achieved perfect accuracy on the test set, but their cross-validation scores (KNN: 0.96, Logistic Regression: 0.953) indicate that they are slightly overfitting to the training data. The confusion matrices indicate that all models handle each class well.

Future improvements could include advanced feature engineering, more comprehensive cross-validation, and exploring other classification algorithms.

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install pandas scikit-learn matplotlib seaborn`.
3. Run the Jupyter Notebook: `decision_tree_classification.ipynb`.

## Project Files
- `decision_tree_classification.ipynb`: The Jupyter Notebook with the complete analysis.
- `README.md`: This README file.
- `decision_tree_model.joblib`: The saved model.
- Visualizations:
  - `pairplot_features.png`
  - `distribution_sepal length (cm).png`
  - `distribution_sepal width (cm).png`
  - `distribution_petal length (cm).png`
  - `distribution_petal width (cm).png`
  - `decision_tree.png`
  - `decision_tree_confusion_matrix.png`
  - `knn_confusion_matrix.png`
  - `logistic_regression_confusion_matrix.png`
