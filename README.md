# 220153_DT

## Project Overview
This project implements the Decision Tree Classification algorithm using Python and Scikit-Learn. The objective is to build a classification model, optimize its hyperparameters, evaluate its performance, and visualize the decision-making process of the trained model.

## Dataset

### Dataset Used
File: dataset/dataset.csv

Purpose:
- Training and evaluating the Decision Tree classifier.
- Predicting class labels based on input features.


## Data Preprocessing

- Dataset loaded using Pandas
- Missing values handled
- Categorical features encoded (if applicable)
- Numerical features standardized
- Training and testing sets created
- Features and target variable separated


## Model Training

### Algorithm
- Decision Tree Classifier

### Hyperparameter Tuning
The model was optimized using hyperparameter tuning to find the best combination of:

- max_depth
- min_samples_split
- min_samples_leaf
- criterion

### Best Model
The optimized Decision Tree model was selected based on validation performance.

## Model Evaluation

The performance of the optimized model was evaluated using multiple metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

## Visualizations

### 1. Decision Boundary Plot

This visualization shows how the Decision Tree classifier separates different classes in the feature space.

![image alt](https://github.com/aronnaiqbal/220153_DT/blob/25d19958e83065ace9591a2d7361c968602d55bc/Screenshot/Screenshot%202026-06-14%20183638%20-%20Copy.png)
![image alt]

### 2. Confusion Matrix Heatmap

The confusion matrix visualizes correct and incorrect classifications made by the model.

![image alt](https://github.com/aronnaiqbal/220153_DT/blob/e37e102e6e146d20797379238692d06e0e0ed4cd/Screenshot/Screenshot%202026-06-14%20210909.png)

### 3. ROC Curve Plot

The ROC curve demonstrates the classification performance across different threshold values.

![image alt](https://github.com/aronnaiqbal/220153_DT/blob/3258d6018a39ab076fd86d3d4f74858ce8ee4248/Screenshot/Screenshot%202026-06-14%20210918.png)

### 4. Evaluation Metrics Bar Chart

This chart compares the major evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
![image alt](https://github.com/aronnaiqbal/220153_DT/blob/3258d6018a39ab076fd86d3d4f74858ce8ee4248/Screenshot/Screenshot%202026-06-14%20210918.png)


### 5. Decision Tree Structure Visualization

The optimized Decision Tree structure was visualized to understand how decisions are made at each node.
![image alt](https://github.com/aronnaiqbal/220153_DT/blob/445142622532960a0b40adb05109e6e0145fb4b5/Screenshot/Screenshot%202026-06-14%20211004.png)


## Model Interpretation

The Decision Tree classifier learns a sequence of decision rules from the training data. Each internal node represents a feature-based decision, while each leaf node represents a final class prediction. The optimized tree successfully separates the classes by selecting the most informative features and splitting points.


## Conclusion

The Decision Tree model achieved strong classification performance and provided interpretable decision rules. The visualizations helped analyze model behavior, classification accuracy, and feature-based decision making.
