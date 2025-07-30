# 🩺 Diabetes Prediction Using Machine Learning

This project utilizes **Support Vector Machine (SVM)** to develop a model that predicts whether a person is likely to have diabetes, based on medical diagnostic data.

---

# 📊 Dataset Info

This dataset includes diagnostic data for female patients of at least 21 years of age. It contains the following features:

| Feature Name            | Description                                  |
|-------------------------|----------------------------------------------|
| Pregnancies             | Number of times pregnant                     |
| Glucose                 | Plasma glucose concentration                 |
| BloodPressure           | Diastolic blood pressure (mm Hg)             |
| SkinThickness           | Triceps skin fold thickness (mm)             |
| Insulin                 | 2-Hour serum insulin (mu U/ml)               |
| BMI                     | Body Mass Index                              |
| DiabetesPedigreeFunction| Diabetes likelihood based on family history  |
| Age                     | Age of the patient                           |
| Outcome                 | 1 = Diabetic, 0 = Non-diabetic (Target)      |



# Key Steps

1. **Data Cleaning**: Loaded the dataset and checked for missing or unusual values.
2. **Feature Scaling**: Used `StandardScaler` to scale input features — important for SVM performance.
3. **Train-Test Split**: Divided the data into training and test sets.
4. **Model Training**: Trained a **Support Vector Machine (SVM)** model.
5. **Prediction**: Used the model to predict diabetes on new/unseen data.
6. **Evaluation**: Evaluated using accuracy score.



# Tech Stack & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn (SVM, preprocessing, metrics)
- Jupyter Notebook


# Author
Tanya Chauhan
