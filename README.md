## 📄 **README – Task 3: Data Preprocessing & Model Building**

---

### 🔹 **Task Objective**

> Perform **data preprocessing** (encoding, scaling, splitting) and build a **classification model** using the provided dataset (`bank.csv`).
> Evaluate the model’s performance using appropriate metrics.

---

### 🗂 **Dataset Used**

We are using the **Bank Marketing Dataset** (`bank.csv`), which contains information about clients contacted in a marketing campaign.
Our goal is to predict whether a client will **subscribe to a term deposit**.

**Key Characteristics:**

* **Categorical Variables:** job, marital status, education, etc.
* **Numerical Variables:** age, balance, duration, campaign, etc.
* **Target Variable:** `y` (yes/no)

---

### 📌 **What We'll Do in Task 3**

1. **Load and Inspect Dataset**

   * Read CSV file and check its shape, datatypes, and null values.

2. **Encode Categorical Variables**

   * Use **Label Encoding** for categorical columns.
   * Store encoders in a dictionary for future decoding if needed.

3. **Save Encoded Dataset**

   * Create a folder `bank_dt_outputs`.
   * Save encoded dataset as `bank_encoded.csv`.

4. **Split Dataset**

   * Train/Test split (e.g., 80/20).

5. **Model Training**

   * Train a **Decision Tree Classifier** (or other algorithms).
   * Fit the model on the training set.

6. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

7. **Insights**

   * Interpret feature importance.
   * Discuss model strengths and limitations.

---

### ⚙ **Expected Outputs**

* Encoded CSV file: `bank_dt_outputs/bank_encoded.csv`
* Classification metrics in console output.
* Feature importance plot (optional).

---

### 📂 **Folder Structure**

```
project/
│── bank.csv
│── task3_script.py
│── README_Task3.md
└── bank_dt_outputs/
    └── bank_encoded.csv
```
