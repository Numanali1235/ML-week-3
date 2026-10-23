# Week 3: Supervised Models (KNN, Decision Tree, Logistic Regression)

**Dataset:** DATASET NAME (source: LINK)

## Summary
1. I cleaned the data (missing values, duplicates, encoding), split it 80/20 with `stratify=y`, and scaled it without data leakage.
2. I trained KNN, Decision Tree and Logistic Regression and compared them with accuracy, confusion matrix and F1-score.
3. I explain which model fits my problem best and which mistake (false positive or false negative) is worse.

## Best model
**MODEL NAME**, accuracy = **XX.XX%** (best K = X, best max_depth = X)

## How to run
**Google Colab:** upload `week3_supervised_models.ipynb`, set `TARGET` in the first code cell, run all cells, and upload the CSV when asked.

**Locally:**
```
pip install -r requirements.txt
jupyter notebook week3_supervised_models.ipynb
```
Put the CSV next to the notebook and set `DATA_PATH` and `TARGET` in the first code cell.
