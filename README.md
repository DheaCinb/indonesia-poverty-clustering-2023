# indonesia-poverty-clustering-2023
**Project Overview**
**This project analyzes poverty data across cities and regencies in Indonesia using clustering techniques.**
**Two clustering algorithms, K-Means and Bisecting K-Means, are implemented and compared to identify patterns and characteristics of poverty across regions. The results are visualized through statistical charts and geographic maps of Indonesia.**
**The insights from this analysis aim to support data-driven decision-making, particularly in understanding regional poverty profiles for policy evaluation and planning.**

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
