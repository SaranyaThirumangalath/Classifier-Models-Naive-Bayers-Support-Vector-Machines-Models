# Titanic Survival Prediction

This repository contains a machine learning project aimed at predicting the survival of passengers from the Titanic shipwreck. 
The project utilizes supervised learning techniques, including Naive Bayes and Support Vector Machines (SVM), to classify passengers as survivors or non-survivors based on their characteristics.

## Dataset

The project uses the Titanic dataset provided by [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data). This dataset contains information about passengers such as:

- Passenger Class (Pclass)
- Sex
- Age
- Number of Siblings/Spouses Aboard (SibSp)
- Number of Parents/Children Aboard (Parch)
- Ticket Fare (Fare)
- Embarkation Port (Embarked)
- Survival Status (Survived)

Key libraries include:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Model Training

### Naive Bayes
A probabilistic classifier that assumes features are conditionally independent given the class label.

### Support Vector Machine (SVM)
A powerful algorithm that finds the optimal hyperplane to separate classes in a high-dimensional space.

## Evaluation

The SVM model's performance is evaluated using the following metrics:

- **Accuracy:** Measures the percentage of correctly classified instances.
- **Confusion Matrix:** Displays the count of true positives, true negatives, false positives, and false negatives.
- **F1 Score:** Provides a balance between precision and recall.
- **AUC-ROC:** Evaluates the model's ability to distinguish between classes; the ROC curve is plotted to visualize this performance.

