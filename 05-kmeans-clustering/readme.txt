# Customer Segmentation with K-means Clustering

## Project Overview
This project involves performing customer segmentation using K-means clustering on the Mall Customer Segmentation dataset.

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
The dataset used in this project is the Mall Customer Segmentation dataset, which contains information about customers, including their annual income and spending score. It was obtained from Kaggle and saved as `Mall_Customers.csv`.

## Steps Performed
1. **Data Loading:**
   - Loaded the Mall Customer Segmentation dataset.
   - Displayed the first few rows of the dataset.

2. **Data Exploration:**
   - Checked the data types and missing values.
   - Displayed basic statistical summaries.

3. **Data Visualization:**
   - Visualized the distribution of Age.
   - Visualized the distribution of Annual Income.
   - Visualized the distribution of Spending Score.
   - Created a pair plot to visualize relationships between features.
   - Created a correlation heatmap to analyze feature correlations.
   - Used box plots to examine the spread and outliers in the data.
   - Analyzed the distribution of gender.

4. **Data Preprocessing:**
   - Selected the features for clustering.
   - Standardized the features.

5. **K-means Clustering and Model Training:**
   - Determined the optimal number of clusters using the elbow method.
   - Trained the K-means model with the optimal number of clusters.
   - Added the cluster labels to the original dataset.

6. **Model Evaluation:**
   - Calculated the silhouette score.

7. **Cluster Visualization:**
   - Visualized the customer segments.

## Results
- **Silhouette Score:** 0.5547

## Visualizations
- **Distribution of Age:** `distribution_age.png`
- **Distribution of Annual Income:** `distribution_annual_income.png`
- **Distribution of Spending Score:** `distribution_spending_score.png`
- **Pair Plot:** `pairplot_features.png`
- **Correlation Heatmap:** `correlation_heatmap.png`
- **Box Plot of Income by Gender:** `boxplot_income_gender.png`
- **Box Plot of Spending by Gender:** `boxplot_spending_gender.png`
- **Gender Distribution:** `gender_distribution.png`
- **Elbow Method:** `elbow_method.png`
- **Customer Segments:** `customer_segments.png`

## Future Improvements
- Experiment with different clustering algorithms.
- Feature engineering to improve clustering performance.
- Cross-validation to ensure model robustness.

## Project Files
- `kmeans_clustering.ipynb`: The Jupyter Notebook with the complete analysis.
- `README.md`: This README file.
- Visualizations:
  - `distribution_age.png`
  - `distribution_annual_income.png`
  - `distribution_spending_score.png`
  - `pairplot_features.png`
  - `correlation_heatmap.png`
  - `boxplot_income_gender.png`
  - `boxplot_spending_gender.png`
  - `gender_distribution.png`
  - `elbow_method.png`
  - `customer_segments.png`

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install pandas scikit-learn matplotlib seaborn`.
3. Run the Jupyter Notebook: `kmeans_clustering.ipynb`.
