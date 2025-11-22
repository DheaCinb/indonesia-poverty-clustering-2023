# indonesia-poverty-clustering-2023
**This project is an implementation of an undergraduate thesis that aims to analyze poverty data in Indonesia, build clustering models using K-Means and Bisecting K-Means, compare the performance of both algorithms, and visualize the results through charts and geographic maps of Indonesia. The clustering results are intended to help understand the characteristics and patterns of poverty across cities/regencies, supporting government decision-making.**

**Tools :**
- Excel (initial data processing)
- Python: Pandas, NumPy, Scikit-learn
- Tableau (geographic visualization)

**Analysis Steps :**
1. Data Collection :
   Data was sourced from BPS publications in PDF tables, converted to Word, and then extracted to Excel.
3. Data Cleaning :
   - Imputed missing values.
   - Converted - values to NaN, then applied imputation.
   - Converted data types from object to integer.
   - Selected relevant attributes by removing redundant or duplicate features.
   - Normalized data using Robust Scaler.
4. Correlation Analysis :
   Examined relationships between attributes to identify potential redundancy.
6. Dimensionality Reduction :
   Applied PCA to address high correlations and reduce data complexity.
8. Clustering :
   Performed clustering using K-Means and Bisecting K-Means.
10. Clustering Evaluation :
    Evaluated cluster quality using the Silhouette Coefficient to select the best clustering result.
12. Cluster Characterization :
    Identified profiles of each cluster based on grouped data.
14. Visualization :
    Created geographic maps of Indonesia and charts representing the clusters using Tableau.
