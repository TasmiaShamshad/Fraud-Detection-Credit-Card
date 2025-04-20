# 💳 Credit Card Fraud Detection

## 🔍 Overview

This project tackles the challenge of detecting fraudulent credit card transactions using a logistic regression model. Due to class imbalance in the dataset, under-sampling was applied to create a balanced dataset for training.

---

## 📁 Files

- `Task3_FraudDetection.ipynb`: Main Jupyter notebook containing the full workflow.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression, train/test split, metrics)
- Seaborn & Matplotlib

---

## 📊 Dataset & Preprocessing

- Dataset: `creditcard.csv` (Kaggle, highly imbalanced)
- Class 0 = Legit, Class 1 = Fraud
- Sampled 1000 legitimate transactions + all fraud cases to balance
- Split data into train and test sets using stratified sampling

---

## 🧠 Model & Evaluation

- Trained a logistic regression classifier
- Evaluated using:
  - Accuracy Score
  - F1 Score (to handle class imbalance better)

---

## 🖥️ Interactive Prediction Tool

An index-based prediction tool is implemented to:
- Input a row index
- Predict whether the transaction is fraud or not
- Show predicted and actual results along with fraud probability

---

## 🚀 How to Use

1. Open the notebook in Jupyter or Colab.
2. Ensure the `creditcard.csv` file is available.
3. Run all cells to train the model.
4. Use the interactive checker at the end by entering index numbers.

---

## 📬 Contact

For issues or suggestions, feel free to open an issue or contribute.

---

## 📝 License

This project is for educational and learning purposes only.
