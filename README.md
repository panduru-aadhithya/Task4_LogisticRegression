# Task 4: Breast Cancer Classification Using Logistic Regression

## Description
This project is part of Task 4. The goal is to classify breast cancer tumors as **Malignant (M)** or **Benign (B)** using the dataset provided (`data (1).csv`).  
We use **Logistic Regression** for classification, with preprocessing and evaluation included.

---

## Dataset
- File: `data (1).csv`
- Columns include features like `radius_mean`, `texture_mean`, `perimeter_mean`, etc.
- Target column: `diagnosis` (M = Malignant, B = Benign)

---

## Folder Structure
ask4_LogisticRegression/
│
├─ data (1).csv # Dataset provided
├─ Task4_LogisticRegression.ipynb # Jupyter Notebook with code
├─ predictions.csv # Optional: predicted values
└─ README.md # Project description

---

## Steps Performed
1. **Data Exploration**  
   - Checked for missing values and basic statistics.

2. **Preprocessing**  
   - Dropped irrelevant columns (`id`, `Unnamed: 32`).  
   - Encoded target column: `M → 1`, `B → 0`.

3. **Model Training**  
   - Split dataset into train (80%) and test (20%) sets.  
   - Trained a **Logistic Regression** classifier.

4. **Predictions & Evaluation**  
   - Predicted on test set.  
   - Evaluated using **Accuracy**, **Confusion Matrix**, and **Classification Report**.  
   - Visualized actual vs predicted labels.

5. **Optional**  
   - Saved predictions to `predictions.csv`.

---

## How to Run
1. Open the notebook: `Task4_LogisticRegression.ipynb`  
2. Run all cells sequentially  
3. Check evaluation metrics and visualization  
4. Predictions (optional) are saved as `predictions.csv`

---

## Results
- The classifier predicts breast cancer diagnosis accurately based on the given features.  
- Confusion matrix and classification report provide detailed performance metrics.

---

## Libraries Used
- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Logistic Regression, train/test split, evaluation metrics  

---

## Notes
- Only the dataset provided is used.  
- Target encoding ensures compatibility with the classifier.  
- This notebook is ready to run without any external dependencies.
