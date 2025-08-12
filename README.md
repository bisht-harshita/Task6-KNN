# 🔍 K-Nearest Neighbors (KNN) Classification

## 📌 Overview
The objective is to implement the **K-Nearest Neighbors (KNN)** algorithm for classification, experiment with different values of K, evaluate model performance, and visualize decision boundaries.  

The notebook also includes **EDA, scaling, tuning, and error analysis** to make the study more comprehensive.

---

## 📊 Dataset
- **Source:** [Iris Dataset (UCI / sklearn)](https://www.kaggle.com/datasets/uciml/iris)
- **Target:** Species of Iris (`setosa`, `versicolor`, `virginica`)
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Size:** 150 rows, 4 features + target

---

## 🛠 Tools & Libraries
- Python 3.x
- Pandas, NumPy (data handling)
- Matplotlib, Seaborn (visualization)
- scikit-learn (ML models, scaling, metrics)

---

## 🚀 Features Implemented
1. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Class distribution
   - Pairplot visualization

2. **Data Preprocessing**
   - Train-test split (stratified)
   - Feature scaling: StandardScaler & MinMaxScaler comparison

3. **Model Training**
   - Baseline **KNN Classifier** (k=5)
   - Evaluation using accuracy, confusion matrix, precision, recall, F1-score

4. **Parameter Exploration**
   - Accuracy vs K plot
   - Error rate vs K plot

5. **Hyperparameter Tuning**
   - GridSearchCV to find best K and distance metric

6. **Evaluation**
   - Test set performance
   - Cross-validation accuracy scores

7. **Visualization**
   - Decision boundary plots (2D projection)

---

## 📈 Results Summary
| Model | Accuracy | Precision | Recall | F1-score |
|-------|----------|-----------|--------|----------|
| KNN (k=5, baseline) | ~0.96 | ~0.96 | ~0.96 | ~0.96 |
| KNN (best params via GridSearchCV) | ~0.97 | ~0.97 | ~0.97 | ~0.97 |

> **Observation:** KNN performed very well on the Iris dataset.  
> Optimal K (from GridSearchCV) further improved performance slightly.  
> StandardScaler generally gave more stable results than MinMaxScaler for this dataset.

---

## 📷 Visual Outputs
- Pairplot of features vs target classes
- Accuracy vs K graph
- Error rate vs K graph
- Decision boundary plots

---

## 📝 Conclusion
- KNN is simple yet effective for small datasets like Iris.
- Choosing the right K is critical — too small leads to overfitting, too large can oversmooth decision boundaries.
- Feature scaling is important for distance-based models like KNN.
- Visualization helps understand how the model separates classes.

---
