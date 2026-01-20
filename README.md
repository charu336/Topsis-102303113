# Topsis-102303113
# TOPSIS Assignment Submission (Task 1 + Task 2 + Task 3)

**Name:** Charu  
**Roll Number:** 102303113  

This repository contains the complete implementation of **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** in three formats as required in the assignment:

✅ Task 1: Command Line Program  
✅ Task 2: Python Package uploaded to PyPI  
✅ Task 3: Web Application (Flask) with Email Output  

---

## 📌 What is TOPSIS?
TOPSIS is a Multi-Criteria Decision Making (MCDM) technique used to rank alternatives based on multiple criteria.  
It selects the best alternative by comparing each option's distance from:

- **Ideal Best Solution** (best values for each criterion)
- **Ideal Worst Solution** (worst values for each criterion)

The alternative with the **highest TOPSIS score** is ranked **1**.

---

## ✅ Methodology (Steps Used)
The TOPSIS procedure implemented in all tasks follows these steps:

1. Read the decision matrix from input CSV  
2. Normalize the criteria values  
3. Multiply normalized values with weights  
4. Determine ideal best and ideal worst based on impacts (`+`/`-`)  
5. Calculate distances from ideal best and ideal worst  
6. Compute TOPSIS score  
7. Rank alternatives (Rank 1 = best)

---

## 📁 Repository Structure

### ✅ Task 1: CLI Program
📂 `Task-1_CLI/`

Contains:
- `topsis.py` (Command line program)
- `input.csv`
- `output.csv`
- `TOPSIS_Task1.ipynb` (Colab notebook)
- `README.md` (Task 1 documentation)

---

### ✅ Task 2: PyPI Package
📂 `Task-2_Package_PyPI/`

Contains:
- `topsis_charu_102303113/` (package code)
- `setup.py`
- `LICENSE`
- `README.md` (User Manual for package)
- `TOPSIS_Task2.ipynb` (Colab notebook)
- `input.csv`
- `output.csv`

📌 **PyPI Package Name:** `Topsis-Charu-102303113`  
📌 **PyPI Link:** *(paste your PyPI link here)*

---

### ✅ Task 3: Web Application
📂 `Task-3_WebApp/`

Contains:
- `app.py`
- `requirements.txt`
- `templates/index.html`
- `screenshots/` (proof images)
- `README.md` (Task 3 documentation)

---

## ✅ How to Run Each Task

---

# 🟦 Task 1: Run TOPSIS as CLI Program

### 📌 Command
Open terminal inside `Task-1_CLI/` and run:

```bash
python topsis.py input.csv "1,1,1,1" "+,+,-,+" output.csv
