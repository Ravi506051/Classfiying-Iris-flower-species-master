# Iris Flower Species Classification

A supervised machine-learning project that classifies Iris flowers into Setosa, Versicolor or Virginica using four measurements.

## Input features
- Sepal length
- Sepal width
- Petal length
- Petal width

## Workflow
1. Load and inspect the Iris dataset.
2. Explore feature distributions and class balance.
3. Prepare a stratified train/test split.
4. Train a classification model.
5. Evaluate predictions with a classification report and confusion matrix.
6. Test predictions using four numeric measurements in the training feature order.

## Technology
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook

## Run
```bash
git clone https://github.com/Ravi506051/Classfiying-Iris-flower-species-master.git
cd Classfiying-Iris-flower-species-master
python -m venv .venv
# Windows: .venv\\Scripts\\activate
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

## Evaluation
Use a stratified split and report per-class precision, recall and F1-score alongside accuracy. Record the random seed and measured results; do not publish unverified performance claims.

## Future improvements
Compare Logistic Regression, K-Nearest Neighbours and tree-based baselines. Persist preprocessing with the estimator and validate that inputs contain exactly four finite numeric values.

## Maintainer
**Ravi Kumar Rao** · [GitHub](https://github.com/Ravi506051)

## Skills Demonstrated

- Supervised classification
- exploratory analysis
- feature visualization
- model comparison
- per-class evaluation.

## Portfolio Context

This project is part of my hands-on learning portfolio. The repository documents the workflow and implementation; results should be reproduced from the included code and data before being used in reports or professional claims.
