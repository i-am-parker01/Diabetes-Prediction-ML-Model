# Diabetes-Prediction-ML-Model
An ML model that predicts you have diabetes or not.

🧠 Diabetes Prediction using Support Vector Classifier (SVC)

This project is a machine learning application that predicts whether a person is likely to have diabetes based on 8 key health-related features. The prediction is performed using a Support Vector Classifier (SVC) trained on a medical dataset (e.g., PIMA Indian Diabetes dataset).



---

 🧪 Features Used for Prediction

The following 8 features are used as input for the model:

1. Number of Pregnancies
2. Glucose Level
3. Blood Pressure
4. Skin Thickness
5. Insulin Level
6. BMI (Body Mass Index)
7. Diabetes Pedigree Function
8. Age

---

 ✅ Model Details

- Algorithm: Support Vector Machine (SVC)
- Library: scikit-learn
- Model Exported Using: `joblib`


model.fit(X_train, y_train)
joblib.dump(model, 'classifier.pkl')
