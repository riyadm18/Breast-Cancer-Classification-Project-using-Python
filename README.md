# Breast-Cancer-Classification-Project-using-Machine Learning

This project uses the **Breast Cancer Wisconsin Diagnostic dataset** to classify tumors as **malignant** or **benign** using several machine learning algorithms. It compares their performance using accuracy and classification metrics.

---

## Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Features**: 30 numerical features (e.g., mean radius, texture, perimeter, etc.)
- **Target**: 
  - `0` = Malignant  
  - `1` = Benign

##  Workflow

### 1. Load and Explore the Dataset
- Loaded data using `scikit-learn`
- Converted it to a Pandas DataFrame
- Checked basic statistics and shape

### 2. Preprocessing
- Checked for null values (no missing data)
- Scaled features using `StandardScaler`

### 3. Train-Test Split
- 80% Training, 20% Testing using `train_test_split`

### 4. Model Building
Trained and evaluated five classifiers:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbors (k-NN)


##  Results

| Model               | Accuracy   |
|--------------------|------------|
| Logistic Regression| **97.37%** |
| Decision Tree      | 93.86%     |
| Random Forest      | 96.49%     |
| SVM                | **97.37%** |
| k-NN               | 94.74%     |

