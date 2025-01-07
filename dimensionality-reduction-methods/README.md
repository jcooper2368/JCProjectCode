# Customer Data Analysis with PCA

## Overview
This project applies Principal Component Analysis (PCA) to a telecommunications customer dataset to uncover key patterns and structures driving variability in customer behaviors. PCA is a dimensionality reduction technique that helps simplify complex, high-dimensional data while retaining its most important features.

[Churn Clean Dataset](https://github.com/jcooper2368/JCProjectCode/raw/main/dimensionality-reduction-methods/churn_clean_pres.csv)

[Churn PCA Analysis Notebook](dimensionality-reduction-methods/Churn%20PCA%20Analysis%20%283%29.ipynb)

[Dimensionality Reduction Methods Documentation](https://github.com/jcooper2368/JCProjectCode/raw/main/dimensionality-reduction-methods/Dimensionality%20Reduction%20Methods.docx)


The goal of the project is to use PCA to:
- Identify significant variables driving customer behaviors.
- Reduce the dimensionality of the dataset for easier analysis and interpretation.
- Extract insights that can support data-driven decision-making for business strategies in telecommunications.

## Methodology
1. **Data Preparation:**
   - Conducted exploratory data analysis (EDA) to inspect the dataset and ensure data quality.
   - Standardized the dataset to prepare for PCA by ensuring that all variables are on the same scale.

2. **PCA Implementation:**
   - Applied PCA to the dataset and determined the principal components explaining the most variance.
   - Used the elbow rule to select the optimal number of components (retaining 4 components based on the scree plot).

3. **Analysis and Results:**
   - Explained variance for each principal component and the total variance captured by the retained components.
   - Visualized the reduction in dimensionality, highlighting how the principal components simplify the dataset while retaining crucial variability.

## Results
- The first four principal components captured 40.2% of the total variance in the dataset.
- The analysis revealed that the retained components help in reducing the complexity of the dataset, making it more interpretable for strategic decision-making.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- PCA for dimensionality reduction
- Elbow rule for component selection
