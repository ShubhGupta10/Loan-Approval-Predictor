# 🏦 Loan Approval Predictor

This project predicts whether a loan should be approved or not using a machine learning model called **Linear Support Vector Classifier (LinearSVC)**.

It’s built to help banks or loan officers make quick decisions based on user information like income, education, credit history, and more.

---

## 📌 What This Project Does

✅ Takes loan application data (like income, credit history, etc.)  
✅ Trains a machine learning model on historical data  
✅ Predicts whether a new applicant is eligible for a loan or not

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – for data handling
- **NumPy** – for calculations
- **scikit-learn** – for building the machine learning model
- **Jupyter Notebook** – to run and test the code interactively

---

## 📂 Files Included

| File Name                  | Purpose                                  |
|---------------------------|-------------------------------------------|
| `Loan_Approval.ipynb`     | Jupyter Notebook containing all code and explanations |
| `train_ctrUa4K.csv`       | Training dataset                          |
| `test_lAUu6dG.csv`        | Test dataset                              |
| `loan_predictions_output.csv` | Final predictions on test data      |
| `README.md`               | You're reading it!                        |
| `requirements.txt`        | List of required packages      |

---

## 🚀 How to Use This Project

1. **Clone the repository** or download the ZIP
2. Make sure you have Python installed (version 3.7 or above recommended)
3. Install required packages:

```bash
pip install -r requirements.txt
```
## 🚀 How to Run

Make sure you have `jupyter` and required libraries installed.

```bash
jupyter notebook Loan_Approval.ipynb
```

#Then go through the notebook to explore:

- ✅ **How the data is cleaned**
- 🧪 **How the model is trained**
- 🔮 **How predictions are made**

---

## 🧠 Why LinearSVC?

After experimenting with various models, **LinearSVC** was chosen because:

- It's **fast** and **efficient**
- Works well for **binary classification**
- Offers a **good trade-off** between speed and accuracy on this dataset

---

## 📈 Model Performance

Results from the validation set:

- **Accuracy:** ~80–88%
- **Precision / Recall / F1 Score:** _See notebook for detailed metrics_

---

## 🔧 What Can Be Improved

If you're looking to extend or improve this project:

- ✅ Try other models like **Random Forest**, **XGBoost**, etc.
- 🧹 Improve data preprocessing and handle missing values differently
- ➕ Add new or engineered features for smarter predictions
- 🖥️ Build a **simple UI** for real-time interaction with the model

---

## 💬 Feedback & Collaboration

This project is designed to help beginners learn and grow. If you find something that can be improved:

- ⭐ Star this repository
- 🐛 [Open an issue](#)
- 🤝 Submit a pull request

---

## 👤 Author

**Shubh Gupta**

- 📫 [LinkedIn](#)
- 💻 [GitHub](#)
