# 🌸 Iris Flower Classification Project

This project involves building a machine learning model to classify Iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — using the popular Iris dataset. We use various data science and machine learning techniques to explore, visualize, and model the data.

---

## 🧠 Objective

- Develop a classification model to identify flower species based on sepal and petal measurements.
- Identify the most significant features influencing the classification.
- Evaluate the model using accuracy score, classification report, and confusion matrix.

---

## 📊 Dataset Description

The dataset used contains the following features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**
- **Species** (Target Variable)

📁 Dataset Source: [Kaggle - Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)

---

## 🚀 Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded CSV using pandas.
- Basic statistics and data info explored.

### 2️⃣ Preprocessing
- Feature/target split.
- Train/test split (80/20).
- Feature scaling using `StandardScaler`.

### 3️⃣ Model Training
- Trained using **Random Forest Classifier**.

### 4️⃣ Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix (visualized with heatmap)

### 5️⃣ Feature Importance
- Identified using `.feature_importances_` from Random Forest.
- Visualized using Seaborn bar plot.

---

## 📈 Model Performance

### ✅ Accuracy: `100%`

### 🧾 Classification Report:

| Class            | Precision | Recall | F1-score | Support |
|------------------|-----------|--------|----------|---------|
| Iris-setosa      | 1.00      | 1.00   | 1.00     | 10      |
| Iris-versicolor  | 1.00      | 1.00   | 1.00     | 9       |
| Iris-virginica   | 1.00      | 1.00   | 1.00     | 11      |

---

## 🔍 Feature Importance

| Feature        | Importance |
|----------------|------------|
| Petal Length   | 0.4400     |
| Petal Width    | 0.4215     |
| Sepal Length   | 0.1081     |
| Sepal Width    | 0.0304     |

✳️ Clearly, **petal features** are most influential in classifying the flower species.

---

## 🎯 Conclusion

- The model achieved **100% accuracy** on the test set.
- Petal measurements are more significant for species identification than sepal measurements.
- The Random Forest Classifier proved to be highly effective for this classification task.

---

## 🛠️ Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` (train_test_split, StandardScaler, RandomForestClassifier, metrics)

---

## 📌 Author

**Kamini** 

---



