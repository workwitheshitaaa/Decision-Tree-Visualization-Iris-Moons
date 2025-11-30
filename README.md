# Decision Tree Classification & Visualization

This project demonstrates **Decision Tree classification** on two datasets:

1. Synthetic **moons dataset** (non-linear, 2D)
2. Classic **Iris dataset** (multiclass)

The project covers **tree training, evaluation, and visualization** using both Gini and Entropy criteria.

---

## Project Workflow

### 1. Impurity Visualization
- Plotted **Gini vs Entropy** vs class probability  
- Helps understand **how trees split nodes**

### 2. Moons Dataset
- Created with `make_moons` (400 samples, noisy)
- Train-test split (70:30)
- Built Decision Trees with `criterion="gini"` and `criterion="entropy"`
- Visualized **decision boundaries**
- Evaluated with **accuracy**

### 3. Iris Dataset
- Multiclass classification (3 classes)
- Train-test split (75:25)
- Built Decision Tree (`max_depth=2`)  
- Evaluated with **accuracy & classification report**
- Extracted **feature importances**
- Plotted full **tree structure**

---

## Key Concepts
- Decision Tree algorithm (Gini vs Entropy)
- Feature importance in tree-based models
- Decision region visualization
- Handling binary and multiclass classification

---

## Results
- Moons dataset: Decision boundaries show non-linear splits  
- Iris dataset: Accuracy and classification report printed; important features identified  
- Gini vs Entropy criteria comparison

---

## Technologies Used
- Python
- NumPy, Matplotlib
- Scikit-learn (DecisionTreeClassifier)
- Pandas

---

## Key Learnings
- How Decision Trees split data  
- Difference between Gini and Entropy  
- Visualizing model decisions and importance of features  
- Applying trees to binary and multiclass datasets

