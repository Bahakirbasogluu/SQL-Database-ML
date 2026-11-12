# SQL-Database-ML

Five introductory data science assignments by Baha Kırbaşoğlu, covering pandas, SQL queries through SQLite, exploratory analysis, and basic regression, classification and clustering with scikit-learn. The notebooks read CSV files that are not included in the repository.

| File | Task | Methods | Dataset |
| --- | --- | --- | --- |
| `Assignment1-b21992976.ipynb` | DataFrame basics and SQL queries | pandas filtering, derived columns, concatenation and group-by; an in-memory SQLite table queried with SELECT, WHERE, SUM, ORDER BY, GROUP BY and UPDATE | `cars.csv`, `Hotels1.csv`, `Hotels2.csv`, and a small course table entered by hand |
| `Assignment2-V2.ipynb` | Exploratory analysis of country happiness data | Sorting, null removal, labelling by rank, correlation table and heatmap, grouped bar charts, random sampling with replacement, pie charts | `happiness.csv` |
| `Assignment3-V2.ipynb` | Predicting item outlet sales | Min-max scaling, 80:20 train/test split, k-NN regression, mean squared error over k = 1..40 for Euclidean and Manhattan distance | `sales.csv` |
| `Assignment4_v3.ipynb` | Predicting passenger satisfaction and comparing two classifiers | Logistic regression and k-NN classification, 70:10:20 train/validation/test split, 10-fold cross-validation, choice of k on the validation set, confusion matrix, precision-recall curves | `data.csv` |
| `Assignment5_v2.ipynb` | Clustering customers | Feature cleaning and encoding, standard scaling, K-Means with elbow method, agglomerative clustering with dendrogram, silhouette scores | `data.csv` |

Requirements: Python 3, Jupyter, numpy, pandas, matplotlib, seaborn, scikit-learn, scipy, yellowbrick (sqlite3 comes with Python).
