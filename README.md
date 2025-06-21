# 🧪 Solubility Prediction Using Machine Learning

This project predicts the aqueous solubility (`logS`) of molecules using classical machine learning models on the **Delaney ESOL dataset**. The entire ML pipeline is written from scratch in Python — including data processing, model training, evaluation, and visualization.

---

## 📂 Dataset

- **Source:** [Delaney ESOL Dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)
- **Description:** Contains molecular descriptors and the target solubility values (`logS`) for each molecule.

---

## 🧠 Models Used

- **Linear Regression**
- **Random Forest Regressor** (`max_depth=2` for experimentation)

---

## 📈 Metrics Evaluated

Each model is evaluated on:

- **Mean Squared Error (MSE)**
- **R² Score (Coefficient of Determination)**

---

## 🖼️ Visualizations

- Scatter plot of **predicted vs experimental `logS` values**
- Best-fit line to assess model trend
- Comparison table of model metrics (Train/Test MSE & R²)

---

## 🚀 Project Highlights

- Self-coded end-to-end ML pipeline
- Clean evaluation of underfitting and model limitations
- Learning-focused approach, not just accuracy-focused
- Demonstrates practical regression modeling for molecular properties

---

## 🛠️ Technologies Used

- Python
- pandas
- scikit-learn
- matplotlib
- NumPy

---

## 📚 How to Run

```bash
# Install required packages
pip install pandas scikit-learn matplotlib numpy

# Run the notebook or script
python solubility_prediction.py

<br>
author -- Tanvi Diwakar
