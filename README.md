# machine-learning-first-principles

A record of my self-study in classical machine learning and the Python data stack, built up while learning the fundamentals.

**What this is, plainly:** every notebook here was written while following public tutorials, courses and books (for example CampusX, Krish Naik, and the housing example from *Hands-On Machine Learning* by Géron). It is a learning log, not original research or a set of independent projects. Some notebooks are rough practice or scratch work.

## Contents

| Folder | What's in it |
|---|---|
| `01-python-numpy-pandas/` | Python basics, NumPy, Pandas (IPL and Fortune 500 data analysis, group-by, concat) |
| `02-visualization/` | Matplotlib, Seaborn, Plotly |
| `03-eda/` | Exploratory data analysis on several public datasets, including pandas profiling |
| `04-preprocessing-and-feature-engineering/` | Feature scaling, encoding, column transformers, pipelines, imputation, outliers, feature construction and selection, power transforms, cross-validation, imbalanced data, multicollinearity, stacking and blending, grid search |
| `05-ml-algorithms-and-evaluation/` | Linear, polynomial, ridge, lasso and logistic regression, KNN, Naive Bayes, SVM, decision trees, bagging, random forest, AdaBoost, gradient boosting, XGBoost, k-means, hierarchical clustering, PCA, gradient descent; evaluation metrics (accuracy, confusion matrix, R²) |

Not covered here yet: deep learning and neural networks.

## Running the notebooks

```bash
pip install -r requirements.txt
jupyter notebook
```

Large datasets were removed to keep the repository small. See [`DATA.md`](DATA.md) for which files are missing and what to do about them. Notebooks that depend on them will not run until the files are added back.

## Applied work

My project work (robotics, controls, embedded systems) is in a separate portfolio: [Subhanjal_Pant_CV](https://github.com/Subhanjal-Pant/Subhanjal_Pant_CV).
