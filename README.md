# 💳 # 💳 Credit Card Fraud Detection – Task 1 (Internship)

# 💳 Credit Card Fraud Detection – Task 1 (Internship)

This repository contains **Task 1** of my internship, implemented as a Jupyter Notebook: **`Task 1(inter).ipynb`**.
The task focuses on building a **machine learning model to detect fraudulent credit card transactions** using Python and scikit-learn.
## 📖 Table of Contents

* About the Task
* Dataset Description
* Objective
* Technologies Used
* Workflow
* Model Used
* Results
* How to Run the Notebook
* Folder Structure
* Conclusion
## 🧠 About the Task

Credit card fraud detection is a critical real‑world problem due to highly **imbalanced data** and the need for accurate classification.
In this task, a supervised learning approach is used to classify transactions as **legitimate** or **fraudulent**.

The entire implementation, from data loading to model evaluation, is documented in the Jupyter Notebook.
## 📊 Dataset Description

* **Dataset:** Credit Card Transactions Dataset
* **Source:** Commonly used Kaggle credit card fraud dataset
* **Records:** 284,807 transactions
* **Features:** 30 numerical features (V1–V28, Amount, Time)
* **Target Column:**

  * `Class = 0` → Legitimate transaction
  * `Class = 1` → Fraudulent transaction

⚠️ The dataset is **highly imbalanced**, with very few fraud cases compared to legitimate ones.
## 🎯 Objective

* Load and explore the credit card transaction dataset
* Handle class imbalance
* Split the data into training and testing sets
* Train a machine learning model
* Evaluate the model performance using accuracy
## 🛠 Technologies Used

* **Python 3**
* **NumPy** – numerical computations
* **Pandas** – data manipulation
* **Scikit-learn** – machine learning models and evaluation
* **Jupyter Notebook**
## 🔄 Workflow

1. Import required libraries
2. Load the credit card dataset
3. Perform basic data exploration (`head`, `tail`, `info`)
4. Separate legitimate and fraudulent transactions
5. Handle class imbalance
6. Split data into training and test sets
7. Train the model
8. Evaluate model accuracy
## 🤖 Model Used

* **Logistic Regression**

Reasons for choosing Logistic Regression:

* Simple and interpretable
* Works well for binary classification
* Efficient for large datasets
## ✅ Results

* The model successfully classifies transactions
* Accuracy is calculated using `accuracy_score`
* Demonstrates the challenges of fraud detection on imbalanced datasets
*(Exact accuracy may vary depending on data sampling)*
 ▶️ How to Run the Notebook
### Prerequisites

* Python 3 installed
* Jupyter Notebook / Jupyter Lab

### Install Dependencies
```bash
pip install numpy pandas scikit-learn
### Run
1. Open Jupyter Notebook
2. Load `Task 1(inter).ipynb`
3. Update dataset path if required
4. Run cells sequentially
## 📁 Folder Structure
├── Task 1(inter).ipynb
├── README.md
## 🧾 Conclusion

This task demonstrates a **practical machine learning application** in fraud detection. It highlights the importance of data preprocessing, handling imbalanced datasets, and choosing an appropriate model.
