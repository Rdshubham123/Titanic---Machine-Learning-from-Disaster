# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Overview
This project predicts whether a passenger survived the Titanic disaster using
machine learning classification techniques. The goal is to analyze passenger
attributes and build a model that can accurately predict survival outcomes.

## 📊 Dataset
- **Titanic: Machine Learning from Disaster**
- Source: Kaggle
- The dataset contains passenger information such as age, gender, ticket class,
  family relationships, fare, and embarkation port.

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🔍 Methodology
1. Data loading and inspection
2. Handling missing values (Age, Embarked)
3. Feature engineering:
   - FamilySize
   - IsAlone
   - Title extraction from passenger names
4. Encoding categorical variables
5. Model training using **Random Forest Classifier**
6. Model evaluation using accuracy and confusion matrix

## 📈 Results
- Logistic Regression baseline accuracy: ~83%
- Random Forest with feature engineering achieved approximately **83% accuracy**

## 📂 Project Structure
