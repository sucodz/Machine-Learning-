# Titanic Survival Predictor

This project uses the famous Titanic dataset from Kaggle to build a survival prediction model using Logistic Regression.

## Objective
Predict whether a passenger survived the Titanic disaster using features such as age, sex, class, and more.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

## Model
- **Algorithm**: Logistic Regression
- **Accuracy Validation**: Test set accuracy and 10-fold cross-validation to check for overfitting/underfitting

## Features Used
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

## Steps
1. Load and clean the data
2. Encode categorical variables
3. Normalize numerical features
4. Train Logistic Regression
5. Evaluate accuracy and generalization

## How to Run
1. Install dependencies:
pip install -r requirements.txt

markdown
Copy
Edit

2. Run the notebook or Python script to train and evaluate the model.

## Results
- Outputs classification report, confusion matrix, and accuracy.
- Validates generalization using cross-validation scores.

## License
This project is for educational purposes.
