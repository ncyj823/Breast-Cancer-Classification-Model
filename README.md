# 🧠 Breast Cancer Classification using Logistic Regression

This project uses **Logistic Regression** to classify breast cancer tumors as **Malignant** or **Benign** based on the **Wisconsin Breast Cancer Dataset**. It demonstrates how data preprocessing and a simple ML model can be used to solve a real-world healthcare problem.


## 📂 Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Data Set
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Samples:** 569
- **Features:** 30 numeric features (mean, standard error, worst value)
- **Target classes:**  
  - `0`: Malignant  
  - `1`: Benign


## ⚙️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- scikit-learn



## 🧹 Data Preprocessing

The following preprocessing steps were applied:

- Handled missing values (if any)
- Converted dataset to NumPy arrays
- Scaled the features using `StandardScaler`
- Split data into training and test sets (typically 80/20)
- Trained a logistic regression model using `LogisticRegression`



## 📈 Model

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
model.fit(X_train, Y_train)
