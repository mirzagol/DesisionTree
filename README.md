# 🌳 Decision Tree Classifier from Scratch

A hands-on, educational implementation of a Decision Tree classifier in Python, built and visualized step-by-step in a Jupyter Notebook.

---

## 📋 Overview

- **Custom Decision Tree Implementation:** Build and visualize decision trees from scratch using Gini index or Entropy as the splitting criterion.
- **Flexible Data Preprocessing:** Handles missing values, categorical encoding, and outlier removal.
- **Visualization:** Easily plot the constructed decision tree for interpretability.
- **Cross-Validation:** Evaluate model performance using k-fold cross-validation.

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/decision-tree-classifier.git
```

Navigate to the project directory:

```bash
cd decision-tree-classifier
```

Install dependencies (if needed):

```bash
pip install numpy pandas matplotlib scikit-learn
```
# 🚀 Usage
Open the Jupyter notebook:
```bash
jupyter notebook [DesisionTree.ipynb](http://_vscodecontentref_/0)
```
Or open DesisionTree.ipynb in VS Code.

# 🕹️ Instructions
1. **Load Data:** The notebook loads data.csv and displays basic info.
2. **Preprocessing:** Cleans missing values, encodes categorical features, and removes outliers.
3. **Build Tree:** Choose Gini or Entropy as the splitting criterion.
4. **Train/Test Split:** Use the provided trainTestSplit function.
5. **Train Model:** Build the tree with buildDecisionTree.
6. **Evaluate:** Use crossValidation for k-fold accuracy.
7. **Visualize:** Plot the tree with plot_decision_tree.

# ⚙️ How It Works
- **Splitting Criteria:** Selects the best split using either Gini index or Entropy.
- **Recursive Tree Building:** Recursively splits data until pure or stopping criteria are met.
- **Categorical Encoding:** Converts string categories to numeric codes for processing.
- **Cross-Validation:** Uses k-fold cross-validation for robust accuracy estimation.

# 🧠 Key Concepts
- **Gini Index & Entropy:** Measures of impurity to select the best splits.
- **Recursive Partitioning:** Data is split recursively to form a tree.
- **Categorical Encoding:** Converts categorical features to numeric codes.
- **Cross-Validation:** Ensures the model generalizes well to unseen data.

# 🧩 Example: Gini vs. Entropy
- **Gini Index:** Favors larger partitions and is faster to compute.
- **Entropy:** More sensitive to class imbalance, can lead to different splits.
- **Try Both:** Experiment with both criteria to see their effect on accuracy and tree structure.

# 👨‍💻 Contributing
Contributions are welcome! If you find a bug or have a feature request, feel free to open an issue or submit a pull request.
