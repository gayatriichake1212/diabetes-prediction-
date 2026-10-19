# Diabetes Prediction

## Project Description
Diabetes Prediction is a Machine Learning project that predicts whether a person may have diabetes based on medical information. It uses a trained machine learning model to analyze input data and generate a prediction.

## Objectives
- Predict the possibility of diabetes using machine learning.
- Analyze medical data to identify patterns.
- Build a simple application for diabetes prediction.
- Understand how machine learning can be used in healthcare.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit (if used in the application)
- Jupyter Notebook

## Dataset
The project uses a diabetes dataset containing medical features such as:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Project Files
- `app.py` – Application code.
- `diabetes.csv` – Dataset used for the project.
- `diabetes_model.pkl` – Saved machine learning model.
- `diabetes_features.pkl` – Saved feature information.
- `diabetes_prediction.ipynb` – Jupyter Notebook for data analysis and model development.
- `prediction_history.csv` – Stores prediction history, if used by the application.

## How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas numpy scikit-learn streamlit
   ```

3. Open the project folder.
4. Run the application:

   ```bash
   streamlit run app.py
   ```

   If your application does not use Streamlit, run it according to the framework used in `app.py`.

## Applications
- Healthcare data analysis
- Diabetes risk prediction
- Machine learning education
- Basic health prediction systems

## Disclaimer
This project is intended for educational purposes only. Its predictions are not a medical diagnosis and should not replace professional medical advice.
