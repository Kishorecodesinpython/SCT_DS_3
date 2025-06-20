# SCT_DS_3

# 🧠 Bank Marketing - Decision Tree Classifier

This project uses the [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) from the UCI Machine Learning Repository to build a Decision Tree Classifier that predicts whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

## 📁 Files Included

- `bank_marketing_decision_tree.ipynb` – Jupyter Notebook with full step-by-step implementation.
- `bank-full.csv` – Dataset (not included here due to size; please download it from the [UCI Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)).

## 📊 Dataset Description

- **Attributes:** Age, Job, Marital status, Education, Default, Balance, Housing, Loan, Contact type, Day, Month, Duration, Campaign, Pdays, Previous, Poutcome, etc.
- **Target:** `y` — Whether the client subscribed to a term deposit.

## 🚀 Steps Performed

1. Loaded the dataset
2. Encoded categorical variables
3. Split the data into train and test sets
4. Trained a Decision Tree Classifier
5. Evaluated the model using accuracy and classification report
6. Visualized the decision tree

## 🔧 How to Run

1. Download the dataset from the UCI repository: `bank-full.csv`
2. Place it in the same directory as the notebook
3. Open the notebook using Jupyter and run all cells

## 📦 Requirements

- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

Install with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## ✨ Output Example

- **Accuracy:** ~88% (varies per run)
- **Tree Visualization:** Provided at the end of the notebook

## 📬 Author

This project was created as a part of a machine learning task for educational purposes.

