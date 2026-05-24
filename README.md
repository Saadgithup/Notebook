Step 1 — Dataset Collection — downloads a GB-scale dataset from Kaggle (CICIDS 2017 ~2.2 GB is the example), verifies the file size in GB, and lists all data files found.
Step 2 — Read Dataset — handles single CSVs, multiple CSVs merged together, and falls back to synthetic data for testing if no files are found yet.
Step 3 — Preprocessing — checks and fills missing values, removes duplicates, encodes categorical columns, splits features/target, and applies StandardScaler.
Step 4 — Classification Models — trains 5 models (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, KNN), times each one, and prints a detailed classification report for the best.
Step 5 — Graphs (7 total)
Class distribution (bar + pie)
Model accuracy comparison
Confusion matrices
Feature importance (Random Forest)
Correlation heatmap
ROC curves for all models
Full results dashboard
Step 6 — GitHub — auto-creates README.md, requirements.txt, and .gitignore, then prints the exact git commands to push. Includes a one-click auto-push cell too.
Step 7 — Share link — includes the formatted template to paste in your group.

1 Class Distribution (Bar + Pie)
2 Model Accuracy Comparison
3 Feature Importance (Top 10)
4 ROC Curves (AUC scores)
5 Radar Chart (multi-metric)
6 Training Time
7 Full Dashboard
