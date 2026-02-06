# MNIST / Digits PCA Analysis Project

## 📌 Project Overview

This project demonstrates dimensionality reduction using **Principal
Component Analysis (PCA)** on an MNIST-style digits dataset and compares
model performance before and after reduction.

The workflow includes data loading, feature scaling, PCA application,
visualization of explained variance, dataset reduction, and
classification using Logistic Regression.

------------------------------------------------------------------------

## 📂 Dataset

-   **Type:** MNIST / Digits (CSV format)
-   **Features:** Flattened pixel values
-   **Target column:** `label` (digits 0--9)

------------------------------------------------------------------------

## ⚙️ Tools & Libraries Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Scikit-learn

------------------------------------------------------------------------

## 🔄 Workflow Steps

1.  Load MNIST/Digits dataset from CSV.
2.  Flatten images into feature vectors.
3.  Scale features using `StandardScaler`.
4.  Apply PCA with multiple component values.
5.  Plot cumulative explained variance.
6.  Reduce dataset using optimal PCA components (30).
7.  Train Logistic Regression on original dataset.
8.  Train Logistic Regression on PCA-reduced dataset.
9.  Compare accuracy of both models.
10. Visualize PCA 2D scatter plot.

------------------------------------------------------------------------

## 📊 Results

-   **Optimal PCA Components:** 30
-   **Accuracy (Original Dataset):** \~95.6%
-   **Accuracy (PCA Reduced Dataset):** \~95.6%

✔ PCA significantly reduced dimensionality without performance loss.

------------------------------------------------------------------------

## 📁 Generated Files

-   `mnist_reduced_pca_30.csv` -- PCA reduced dataset
-   `accuracy_comparison_report.csv` -- Model accuracy comparison
-   Explained variance plot (visual output)

------------------------------------------------------------------------

## ▶️ How to Run

``` bash
pip install numpy pandas matplotlib scikit-learn
```

Run the Python script in Jupyter Notebook, Colab, or VS Code.

------------------------------------------------------------------------

## ✅ Conclusion

PCA is effective for dimensionality reduction in image-based datasets
like MNIST, maintaining high accuracy while reducing computational
complexity.

------------------------------------------------------------------------

## 👤 Author

Machine Learning Assignment
