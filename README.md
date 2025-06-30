# Task 5: Decision Trees and Random Forests

## Objective
The goal of this task is to implement and understand tree-based machine learning models—specifically Decision Trees and Random Forests—for classification using the Heart Disease dataset.

---

## Tools and Libraries Used
- **Pandas** for dataset loading and manipulation.
- **Scikit-learn** for training models, evaluation, and cross-validation.
- **Matplotlib** and **Seaborn** for visualization of feature importances.
- **Graphviz** (optional) for visualizing decision trees.

---

## Dataset Description
The dataset used is the **Heart Disease dataset**, which includes medical attributes such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG results
- Max heart rate achieved
- Exercise-induced angina
- Oldpeak
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia
- **Target** variable indicating presence (1) or absence (0) of heart disease

---

## Step-by-Step Process

### 1. Data Loading and Preprocessing
- Load the dataset using pandas.
- Separate features and the target variable.
- Perform an 80-20 train-test split to evaluate model performance.

### 2. Training a Decision Tree Classifier
- Train a decision tree on the training data.
- Predict on the test data.
- Evaluate model performance using accuracy and a classification report (precision, recall, F1-score).

### 3. Analyzing Overfitting and Controlling Tree Depth
- Retrain the decision tree with a maximum depth constraint to reduce overfitting.
- Evaluate how performance changes with pruning.

### 4. Training a Random Forest Classifier
- Train a random forest with multiple decision trees (ensemble learning).
- Predict and evaluate its performance on the test data.
- Random Forest typically improves generalization and accuracy by reducing model variance.

### 5. Interpreting Feature Importances
- Extract feature importance scores from the trained random forest.
- Visualize the importance of each feature using a bar chart.
- Identify which features most influence the prediction of heart disease.

### 6. Model Evaluation Using Cross-Validation
- Perform 5-fold cross-validation on both models.
- Calculate the mean cross-validation accuracy to assess model stability and reliability.

---

## Summary
- **Decision Trees** provide clear model interpretability but can overfit easily.
- **Random Forests** offer better generalization and performance through ensembling.
- **Feature importance** helps in understanding which input variables contribute most to the prediction task.
- **Cross-validation** ensures robustness by validating model performance across multiple data splits.

---

## Optional Extensions
- Use **Graphviz** to visually represent the structure of the decision tree.
- Experiment with hyperparameter tuning for both models to optimize performance further.
