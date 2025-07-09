
![banner](https://capsule-render.vercel.app/api?type=waving&color=ffb6c1&height=200&section=header&text=KNN%20Classification%20Model&fontSize=40&fontColor=ffffff)

## 📌 Project Overview

This project focuses on using the **K-Nearest Neighbors (KNN)** algorithm to classify whether a person is a **defaulter** based on their **balance** and **income**.

---

## 🚀 Workflow Summary

Here's a breakdown of the process followed:

- ✅ **Loaded** the dataset using `pandas`
- ✅ **Normalized** numerical values using `MinMaxScaler` to balance the scale between income and balance
- ✅ **Split** the dataset into training and testing sets with `train_test_split`
- ✅ **Trained** the KNN classifier — a simple algorithm that predicts based on the *k* closest data points
- ✅ **Tuned** the hyperparameter *k* using `GridSearchCV` to identify the best performing model

---

## 🔍 Key Insight

- 🧠 When `k = 1`, the model gave high accuracy  
- 📉 As `k` increased, the model's accuracy **decreased**  
- 🎯 Conclusion: Smaller values of *k* perform better for this specific classification problem

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `pandas` | Data handling |
| `scikit-learn` | ML modeling & preprocessing |
| `matplotlib` / `seaborn` | Visualization (optional) |

---

## 📁 Folder Structure

```bash
├── knn_classifier.ipynb   # Main notebook
├── dataset.csv            # Input data
├── README.md              # Project summary
````

---

## 💡 What's Next?

* Try adding more features to improve prediction
* Compare KNN with other classification models like Logistic Regression or SVM

---

> 🧩 Simplicity is the ultimate sophistication – and KNN nails it by staying simple and interpretable.

---

![footer](https://capsule-render.vercel.app/api?type=waving\&color=ffb6c1\&height=100\&section=footer)

