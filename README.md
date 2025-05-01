# 🌳 Decision Trees and Random Forests Project

## 📌 Objective
This project demonstrates the use of **Decision Trees** and **Random Forests** for classification using the popular **Iris dataset**. It includes model training, tree visualization, overfitting analysis, feature importance, and evaluation using cross-validation.

---

## 🛠️ Tools & Libraries
- Python
- [Scikit-learn](https://scikit-learn.org/)
- [Graphviz](https://graphviz.org/) (for tree visualization)
- Pandas, Matplotlib

---

## 📁 Dataset
We use the classic [Iris dataset](https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv), which includes:
- Features: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`
- Target: `species` (setosa, versicolor, virginica)

---

## 🚀 Project Steps

### 1. Load and Explore Dataset
- Load dataset using `pandas`
- Preprocess and encode target labels

### 2. Train Decision Tree Classifier
- Fit a `DecisionTreeClassifier` from Scikit-learn
- Evaluate accuracy on test data

### 3. Visualize the Tree
- Use `export_graphviz` + `Graphviz` to render a visual tree diagram

### 4. Avoid Overfitting
- Limit tree depth using `max_depth` parameter
- Compare pruned tree accuracy

### 5. Train Random Forest Classifier
- Fit a `RandomForestClassifier` and compare performance

### 6. Feature Importance
- Plot feature importances from Random Forest

### 7. Cross-Validation
- Use `cross_val_score` to evaluate generalization

---

## 📷 Output Examples
- Decision Tree Visualization (`iris_decision_tree.png`)
- Feature Importance Bar Chart

---

