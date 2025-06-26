# DecisionTree
🩺 Heart Disease Classification using Decision Tree with Pruning
This project builds a Decision Tree classifier to predict the presence of heart disease using the UCI Heart Disease Dataset. It includes data preprocessing, model training, cost complexity pruning, and model evaluation with cross-validation.

📁 Dataset
Source: UCI Machine Learning Repository – Heart Disease Dataset

Features: 13 features such as age, sex, chest pain type, blood pressure, cholesterol, etc.

Target: num (0 = no heart disease, 1 = presence of disease)

📌 Objectives
Load and explore the dataset

Preprocess the data (handle missing values, encode categoricals)

Train a base Decision Tree classifier

Evaluate using accuracy and confusion matrix

Apply Cost Complexity Pruning to reduce overfitting

Use cross-validation to find the best ccp_alpha

Visualize the impact of pruning on model performance

🧪 Key Techniques
DecisionTreeClassifier from sklearn.tree

Cost Complexity Pruning: using cost_complexity_pruning_path()

Cross-validation: using cross_val_score()

One-hot encoding: with pd.get_dummies()

Performance metrics: accuracy, confusion matrix

📊 Visualizations
Decision Tree plot (before pruning)

Accuracy vs. ccp_alpha curve

Cross-validation accuracy for best alpha with error bars

✅ Final Results
Best alpha (found via cross-validation): 0.02202

Test set accuracy with pruned model: 81.33%
