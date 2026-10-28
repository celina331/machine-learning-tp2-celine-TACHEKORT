
# Python for Standardized PCA

## Objective
Implement Principal Component Analysis (PCA) from scratch using Python and compare the results with the implementation provided by Scikit-learn.

## Dataset
The dataset contains the grades of six students in four subjects:

- Mathematics
- Statistics
- Programming
- Algorithms

## Part A: Standardized PCA from Scratch
1. Load the dataset into a Pandas DataFrame.
2. Display the dataset dimensions and descriptive statistics.
3. Standardize the numerical variables.
4. Compute the correlation matrix.
5. Calculate eigenvalues and eigenvectors using NumPy.
6. Sort eigenvalues in descending order.
7. Select the first two principal components.
8. Project the standardized data onto the selected components.
9. Calculate explained variance ratios and cumulative explained variance.

## Part B: Standardized PCA Using Scikit-learn
10. Apply PCA using `sklearn.decomposition`.
11. Reduce the dataset to two principal components.
12. Display the transformed coordinates of the students.
13. Calculate explained variance ratios and cumulative explained variance.

## Part C: Comparison and Interpretation
14. Compare the principal component coordinates from both implementations.
15. Compare eigenvalues and explained variance ratios.
16. Plot the students in two dimensions using both implementations.
17. Explain differences, particularly possible sign changes in the principal components.
18. Determine the percentage of total variance retained by the first two components.

## Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Installation
Install the required libraries with:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Deliverables
- Manual PCA implementation.
- Scikit-learn PCA implementation.
- Comparison of numerical results.
- Visualizations and interpretation.

## Conclusion
This practical work demonstrates the implementation of standardized PCA from scratch and using Scikit-learn. It helps understand dimensionality reduction, eigenvalues, eigenvectors, and explained variance. Comparing both implementations also illustrates why principal component coordinates may have opposite signs while representing equivalent results.
