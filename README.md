# 🩺 Diabetes Risk Prediction using Machine Learning

## 📌 Problem Statement

Diabetes is a rapidly growing global health concern. Early detection is key to managing and mitigating complications like cardiovascular diseases and nerve damage. This project aims to build a machine learning model that can predict whether an individual is at risk of developing diabetes, based on clinical and lifestyle data.

## 🎯 Objective

To develop a classification model that identifies individuals at risk of diabetes using health-related metrics from the **Pima Indians Diabetes Dataset** provided by the **National Institute of Diabetes and Digestive and Kidney Diseases**.

## 🧾 Dataset

- **Source**: `pima-indians-diabetes.csv`
- **Features**:
  - `Pregnancies`: Number of times pregnant
  - `Glucose`: Plasma glucose concentration
  - `BloodPressure`: Diastolic blood pressure (mm Hg)
  - `SkinThickness`: Triceps skinfold thickness (mm)
  - `Insulin`: 2-Hour serum insulin (mu U/ml)
  - `BMI`: Body mass index (weight in kg/(height in m)^2)
  - `DiabetesPedigreeFunction`: Diabetes pedigree function (likelihood based on family history)
  - `Age`: Age in years
  - `Outcome`: Target variable (1 = Diabetic, 0 = Non-Diabetic)

## 🧪 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Checked for missing and anomalous values (e.g., zero entries for glucose or BMI).
   - Visualized distributions and relationships between features and target variable.

2. **Data Preprocessing**  
   - Replaced invalid zero values with `NaN` and imputed using mean/mode.
   - Standardized/normalized continuous features.

3. **Modeling**  
   - Split data into training and testing sets.
   - Tested multiple classifiers: Logistic Regression, KNN, Decision Tree, Random Forest, and SVM.
   - Tuned hyperparameters using cross-validation.

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

5. **Model Insights**  
   - Feature importance analyzed for interpretability.
   - Best-performing model selected for deployment.

## 🏆 Results

- **Best Model**: (e.g., Random Forest or SVM depending on the notebook outcome)
- **Accuracy**: ~X%
- **Precision / Recall / F1-Score**: Provided in notebook
- **AUC Score**: ~Y

## 🔍 Key Takeaways

- Glucose, BMI, and Age were among the most influential predictors.
- Preprocessing and imputation were critical due to missing/invalid values.
- The model can assist clinicians or public health programs in identifying high-risk individuals.

## 📁 Repository Structure

├── Case_Study_DiabetesRisk_Prediction.ipynb
├── pima-indians-diabetes.csv
├── README.md


## 📌 Future Enhancements

- Deploy the model via a Flask API or Streamlit app.
- Incorporate more diverse demographic features.
- Test additional ensemble models (e.g., XGBoost, LightGBM).

## 🧠 Author

**[Suhaib Khalid]**  
ML Enthusiast | Public Health Advocate
