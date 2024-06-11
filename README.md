# Performance Evaluation of Classification Models
This repository contains the code for classigying GDM from first trimester Data. The evaluation metrics include accuracy, precision, recall, F1 score, and specificity across different random states.

# Dataset
The dataset used for this analysis is private. To make it work with you, ensure your dataset is located in the correct path.

# Features Selection
The features are selected based on their mutual information scores, and the top features are used for the classification tasks.

# Models Used
The following machine learning models are evaluated:
- RandomForestClassifier
- GradientBoostingClassifier
- AdaBoostClassifier
- DecisionTreeClassifier
- LogisticRegression
- SVC
- GaussianNB
- KNeighborsClassifier
- CatBoostClassifier
- XGBClassifier
- LGBMClassifier

# Performance Metrics
The following performance metrics are calculated for each model:
- Accuracy
- Precision
- Recall
- F1 Score
- Specificity
- AUC (Area Under the Curve)

# Code Structure
The code is structured as follows:

1. **Data Preparation:**
   - Load the dataset
   - Map labels
   - Scale features
   - Calculate mutual information scores

2. **Feature Selection:**
   - Select top features based on mutual information scores

3. **Model Training and Evaluation:**
   - Split the data into training and testing sets
   - Train models on the training set
   - Evaluate models on the testing set
   - Calculate and store performance metrics

4. **Visualization:**
   - Plot the mutual information scores
   - Generate pair plots
   - Plot correlation heatmaps
   - Plot performance metrics using bar plots, box plots, and radar charts

# Usage
To run the code, ensure you have the required libraries installed.

# Results
The results of the model evaluations are displayed through various plots, including:
- Bar plots for accuracy, precision, recall, and F1 score
- Box plots for performance metrics across random states
- Radar chart for average performance metrics

# License
This project is open to public.
