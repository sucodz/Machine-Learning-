# Diabetes Predictor

This project builds a machine learning model to predict diabetes using the Pima Indians Diabetes Dataset.

## Dataset
The dataset contains several health metrics:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target variable)

## Installation
1. Clone this repository
2. Install the required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook diabetes_predictor.ipynb`

## Usage
The trained model can be used to predict diabetes risk based on health metrics. Load the saved model and scaler:

```python
import joblib

# Load the model and scaler
model = joblib.load('diabetes_predictor_model.pkl')
scaler = joblib.load('scaler.pkl')

# Prepare new data (example)
new_data = [[6, 148, 72, 35, 0, 33.6, 0.627, 50]]

# Scale the data
new_data_scaled = scaler.transform(new_data)

# Make prediction
prediction = model.predict(new_data_scaled)
probability = model.predict_proba(new_data_scaled)

print(f"Prediction: {'Diabetic' if prediction[0] == 1 else 'Not Diabetic'}")
print(f"Probability: {probability[0][1]*100:.2f}%")
```

---

###  Contact Me

Feel free to reach out or follow me on social media:

- 📸 Instagram: [@su_codz](https://www.instagram.com/su_codz/)
- 🌐 porfolio: [Soulef Bentorki](https://soulefbentorki.netlify.app)
- 💼 Shop: [education shop](https://ko-fi.com/soulefbentorki)
- 💻 Github: [sucodz](https://github.com/sucodz)


_Thank you for checking out this notebook!_
---
