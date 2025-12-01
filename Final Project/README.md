# **Lending Club Loan Default Prediction Project**

## Overview

This project analyzes the **LendingClub** loan dataset to identify factors associated with loan default and build machine learning models that predict the likelihood of loan default.
The project includes:

* **Exploratory Data Analysis (EDA)**
* **Interactive dashboard** (Plotly dropdown histogram comparison)
* **Machine learning models**

  * Logistic Regression
  * Random Forest
  * Tuned XGBoost

The final goal is to understand what borrower and loan characteristics drive default risk and to compare different ML algorithms using accuracy, precision, recall, F1-score, and ROC-AUC.

---

# **Environment Setup**

To ensure reproducibility, follow these steps to create a Python virtual environment and install all dependencies.

---

## 1. **Install Python**

This project uses **Python 3.10+**.

Check your Python version:

```bash
python3 --version
```

If needed, install Python from: [https://www.python.org/downloads/](https://www.python.org/downloads/)

---

## 2. **Create a Virtual Environment**

Navigate to your project folder:

```bash
cd term-project-vizvisionaries
```

Create the virtual environment:

```bash
python3 -m venv .venv
```

Activate it:

### macOS / Linux:

```bash
source .venv/bin/activate
```

### Windows (PowerShell):

```powershell
.venv\Scripts\Activate
```

---

# **3. Install Required Libraries**

Install all dependencies:

```bash
pip install -r requirements.txt
```
```
python-dateutil
```

---

# **4. Running the Notebook**

To launch the notebook environment:

```bash
jupyter notebook
```

Open:

```
Final Project/final.ipynb
```

and run all cells in order.

---

# References

LendingClub Loan Data — [https://www.kaggle.com/datasets/wordsforthewise/lending-club](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
Preprocess Lending Club Data: https://github.com/nateGeorge/preprocess_lending_club_data
EDA notebook on Kaggle: https://www.kaggle.com/wordsforthewise/eda-with-python
Sci-kit Learn Documentation for ML model selection: https://scikit-learn.org/stable/

Course: **CS133 — Data Visualization**
Team: Diya Doshi, Athish Kumar, Fnu Hasham


