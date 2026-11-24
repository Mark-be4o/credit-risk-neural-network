# Credit Risk Neural Network

Multiclass credit score prediction (Good/Standard/Poor) with a Keras neural network.

## What it does

Predicts customer credit score class from a credit profile dataset. Covers data-quality checks (100,000 rows collapse to 12,500 unique customers), handling of the imbalanced target and a neural network classifier.

## Files

- `credit_risk_neural_network.ipynb`

## Tools

TensorFlow/Keras, pandas, numpy, scikit-learn, matplotlib, seaborn

## Dataset

Customer credit profiles CSV (not included; add your own copy and update the path in the notebook).

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Accuracy 0.659, balanced accuracy 0.725, macro F1 0.659, macro ROC-AUC (OVR) 0.861.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
