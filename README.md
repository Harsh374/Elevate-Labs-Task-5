# 🩺 Elevate Labs - Task 5: Decision Trees and Random Forests

## 📘 Objective
This task demonstrates the use of tree-based models — **Decision Trees** and **Random Forests** — for classification on the **Heart Disease Dataset**. It includes model training, pruning to prevent overfitting, evaluation with cross-validation, and interpretation of feature importances.

---

## 📂 Contents

- `heart.csv` – Cleaned Heart Disease dataset
- `decision_tree_model.ipynb` – Training, pruning, visualization of a Decision Tree
- `random_forest_model.ipynb` – Building and evaluating a Random Forest
- `README.md` – Project overview and instructions
- Tree visualization outputs (PDF/PNG if available)

---

## 🛠️ Tools Used

- Python 3.x
- `scikit-learn`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `graphviz` for tree visualization

---

## 📊 Dataset: Heart Disease

- Binary classification: `target` column (0 = no disease, 1 = disease)
- Features include age, cholesterol, blood pressure, ECG results, and more
- No missing values; categorical features are one-hot encoded

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Harsh374/Elevate-Labs-Task-5.git
   cd Elevate-Labs-Task-5
2. Install dependencies:
    ```bash
   pip install -r requirements.txt
4. Launch the notebooks:
    ```bash
   jupyter notebook

## 📈 Key Tasks
✅ Decision Tree
- Trained and visualized with Graphviz
- Overfitting addressed using max_depth (optimal: 12)
- Accuracy: ~98.5%

✅ Random Forest
- Trained with 100 estimators
- Outperformed the standalone tree in generalization
- Cross-validation accuracy: ~99.7%

✅ Feature Importance
- Identified top features influencing heart disease prediction
- Visualized using matplotlib

 ## ❓ Interview Concepts Covered
 - Entropy and Information Gain
 - Overfitting & Pruning
 - Bagging and Ensemble Learning
 - Feature Importance
 - Advantages and limitations of Random Forests

## 📌 Author
Harsh374
GitHub Profile

## 📄 License
This project is for educational purposes and follows MIT License
 ```bash
This project is for educational purposes and follows MIT License
