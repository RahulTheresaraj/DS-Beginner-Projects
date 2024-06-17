# Exploratory Data Analysis (EDA) on the Titanic Dataset

## Project Overview
This project involves performing exploratory data analysis (EDA) on the Titanic dataset to understand its structure, identify patterns, and generate insights.

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

## Dataset
The dataset used in this project is the Titanic dataset, which is loaded using Seaborn's `sns.load_dataset('titanic')` function. This dataset contains information about the passengers on the Titanic.

## Steps Performed
1. Import LibrariesSS
2. Data Loading
3. Data Cleaning
4. Data Visualization
5. Insights and Findings

## Visualizations and Insights
### Basic Visualizations
- **Distribution of Age**: Shows the age range of the passengers.
  - **Insight**: The majority of passengers were between 20 and 40 years old. There are fewer children and elderly passengers.
- **Survival Rate by Sex**: Shows survival rates for males and females.
  - **Insight**: Females had a significantly higher survival rate compared to males.
- **Survival Rate by Class**: Shows survival rates for different passenger classes.
  - **Insight**: First-class passengers had the highest survival rate, followed by second and third-class passengers.
- **Survival Rate by Age Group**: Shows survival rates across different age groups.
  - **Insight**: Children (age < 16) had a higher survival rate compared to adults and elderly passengers.
- **Fare Distribution by Class**: Shows the fare distribution across different passenger classes.
  - **Insight**: First-class passengers paid the highest fares, followed by second and third class.
- **Pair Plot of Selected Features**: Shows relationships between age, fare, passenger class, and survival.
  - **Insight**: Highlights how different features interact with each other and affect survival rates.

### Advanced Visualizations
- **Correlation Matrix Heatmap**: Shows correlations between features.
  - **Insight**: Helps to identify features with strong correlations.
- **Facet Grid of Survival Rate by Age and Sex**: Visualizes age distribution across gender and survival.
  - **Insight**: Younger passengers, especially females, had higher survival rates.
- **Violin Plot of Fare by Passenger Class and Survival**: Fare distribution across classes and survival status.
  - **Insight**: First-class passengers paid higher fares and had higher survival rates.
- **Pair Plot with Additional Variables**: Relationships between age, fare, class, and survival.
  - **Insight**: Reveals how multiple features relate to survival.
- **Swarm Plot of Age by Passenger Class and Survival**: Age distribution within classes and survival status.
  - **Insight**: Highlights age distribution and survival within each class.
- **Catplot of Survival Rate by Class and Sex**: Distribution of survivors across different classes and genders.
  - **Insight**: First-class females had the highest survival count.
- **KDE Plot of Age and Fare by Survival**: Density distributions of age and fare for survivors and non-survivors.
  - **Insight**: Younger passengers and those who paid higher fares had higher survival densities.
- **Joint Plot of Age and Fare**: Relationship between age and fare, colored by survival.
  - **Insight**: Higher fares and younger ages are associated with higher survival rates.
- **Boxen Plot of Age by Class and Survival**: Detailed age distribution within each class and survival status.
  - **Insight**: First-class passengers have a wider age range with higher survival rates.

## Future Improvements
- Integrate more advanced visualizations.
- Perform deeper statistical analysis.
- Build predictive models based on the findings.

## Project Files
- `eda_titanic.ipynb`: The main analysis notebook.

## How to Run
1. Clone the repository.
2. Install the required libraries: `pip install pandas matplotlib seaborn`.
3. Run the notebook.
