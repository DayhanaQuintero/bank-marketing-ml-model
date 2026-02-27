# bank-marketing-ml-model
End-to-end ML workflow: data cleaning, feature prep, train/test split, model evaluation, and insights visualization.
# Bank Marketing — Machine Learning Model

## Overview
Machine learning notebook built to analyze marketing campaign data, identify patterns, and generate predictions.

## Steps
- Data exploration and cleaning
- Preprocessing and feature preparation
- Train/test split
- Model training and evaluation
- Visualizations to communicate results

## Tools
Python, Pandas, NumPy, scikit-learn, Matplotlib/Seaborn

## Dataset

This project uses the Bank Marketing dataset available on Kaggle:

🔗 [Bank Marketing Dataset – Kaggle](https://www.kaggle.com/datasets/volodymyrgavrysh/bank-marketing-campaigns-dataset)

Please download the dataset manually and place it in:

`data/bank-additional-full.csv`

Note: The dataset is not included in this repository due to licensing and size considerations.

## How to run
Open the notebook and ensure the dataset is available at:

`data/bank-additional-full.csv`

Make sure the file is loaded using:

```python
pd.read_csv("data/bank-additional-full.csv", sep=";")
