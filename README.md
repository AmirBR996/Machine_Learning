A collection of hands-on Jupyter notebooks covering core machine learning concepts, algorithms, and techniques — implemented and explained step by step.

---

## 📚 Contents

| Notebook | Topic |
|---|---|
| [Logistic_Regression.ipynb](Logistic_Regression.ipynb) | Binary classification with logistic regression on a synthetic dataset |
| [Polynomial_Regression.ipynb](Polynomial_Regression.ipynb) | Fitting non-linear data using polynomial features |
| [Batchgradient_descent.ipynb](Batchgradient_descent.ipynb) | Implementing batch gradient descent on the Diabetes dataset |
| [Stochastic_gradient_descent.ipynb](Stochastic_gradient_descent.ipynb) | Stochastic gradient descent (SGD) optimization |
| [Mini_batch_gradient_descent.ipynb](Mini_batch_gradient_descent.ipynb) | Mini-batch gradient descent for faster convergence |
| [Ridge_from_stratch.ipynb](Ridge_from_stratch.ipynb) | Ridge (L2) regression implemented from scratch |
| [Rigde_regression_vs_linear_regression.ipynb](Rigde_regression_vs_linear_regression.ipynb) | Comparing Ridge and Linear regression on the Diabetes dataset |
| [ridge_regression_key_understandings.ipynb](ridge_regression_key_understandings.ipynb) | Deep dive into how Ridge regression affects model coefficients |
| [L1_VS_L2_regularization.ipynb](L1_VS_L2_regularization.ipynb) | Side-by-side comparison of Lasso (L1) and Ridge (L2) regularization |
| [ElasticNet.ipynb](ElasticNet.ipynb) | ElasticNet regularization combining L1 and L2 penalties |
| [K_nearest_neighbour.ipynb](K_nearest_neighbour.ipynb) | K-Nearest Neighbors classifier on the Breast Cancer dataset (Kaggle) |
| [Naive_Bayes_Classifier.ipynb](Naive_Bayes_Classifier.ipynb) | Naive Bayes classifier with Laplace smoothing on the Play Tennis dataset |
| [SVM_with_kernel.ipynb](SVM_with_kernel.ipynb) | Support Vector Machine with RBF kernel on non-linearly separable data |
| [Bagging_Ensemble.ipynb](Bagging_Ensemble.ipynb) | Bagging with Decision Trees and SVM on a synthetic classification dataset |
| [Voting_Ensemble.ipynb](Voting_Ensemble.ipynb) | Hard and soft voting ensemble classifiers |
| [classification_metrics.ipynb](classification_metrics.ipynb) | Evaluation metrics (accuracy, precision, recall, F1) on the Breast Cancer dataset |
| [ROC_Curve.ipynb](ROC_Curve.ipynb) | ROC curve and AUC analysis on the Pima Indians Diabetes dataset |

---

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Common packages: `numpy`, `pandas`, `matplotlib`, `scikit-learn`
- Some notebooks also use `kagglehub` to download datasets from Kaggle

Install dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn kagglehub
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/AmirBR996/Machine_Learning.git
cd Machine_Learning
jupyter notebook
```

Then open any notebook from the Jupyter file browser to explore the topic.

---

## 📂 Topics Covered

- **Regression**: Linear, Polynomial, Ridge, Lasso, ElasticNet
- **Regularization**: L1, L2, and ElasticNet; understanding coefficient shrinkage
- **Optimization**: Batch, Stochastic, and Mini-batch Gradient Descent
- **Classification**: Logistic Regression, KNN, Naive Bayes, SVM (with kernels)
- **Ensemble Methods**: Bagging, Hard Voting, Soft Voting
- **Model Evaluation**: Classification metrics, ROC Curve, AUC
