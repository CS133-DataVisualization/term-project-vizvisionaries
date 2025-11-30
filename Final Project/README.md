# 📄 **README.md — Lending Club Loan Default Prediction Project**

## 📌 Overview

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

# 🖥️ **Environment Setup**

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

# 📚 **3. Install Required Libraries**

Install all dependencies:

```bash
pip install -r requirements.txt
```
```
python-dateutil
```

---

# ▶️ **4. Running the Notebook**

To launch the notebook environment:

```bash
jupyter notebook
```

Open:

```
Project Assignments/final.ipynb
```

and run all cells in order.

---

# 📊 **5. Running the Interactive Dashboard**

The interactive Plotly dashboard is generated inside the notebook.
It does **not** require a separate server — it runs inside Jupyter automatically.

To view the interactive chart:

1. Open the notebook (`final.ipynb`)
2. Run the **Interactive Component** cell:

   ```python
   fig.show()
   ```
3. The dropdown histogram visualization appears in your browser.

If you want to export it manually:

```python
fig.write_html("interactive_dashboard.html")
```

Then open the file:

```bash
open interactive_dashboard.html   # macOS
start interactive_dashboard.html  # Windows
```

# 🧠 **Modeling Summary**

We trained and compared:

* Logistic Regression
* Random Forest
* Tuned XGBoost

After removing leakage features and applying preprocessing, **XGBoost** achieved:

* **Accuracy:** 0.928
* **AUC:** 0.966
* Strong balance between precision/recall

This model was selected as the final classifier.

---

# 🙌 Credits

Dataset:
LendingClub Loan Data — [https://www.kaggle.com/datasets/wordsforthewise/lending-club](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
Course: **CS133 — Data Visualization**
Team: Diya Doshi, Athish Kumar, Fnu Hasham

-
