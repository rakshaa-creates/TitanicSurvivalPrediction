# TitanicSurvivalPrediction
This is my first Git Repository.
# 🚢 Titanic: Machine Learning from Disaster
An end-to-end Machine Learning project to predict passenger survival on the Titanic. This project demonstrates the full data science workflow: from data cleaning and exploration to model evaluation.

## 🎯 Project Objective
The goal is to build a predictive model that answers the question: “What sorts of people were more likely to survive?” using passenger data (ie. name, age, gender, socio-economic class, etc.).

## 📊 Exploratory Data Analysis (EDA)
During the analysis, I discovered several key patterns:
* **The "Gender Gap":** Female passengers had a significantly higher survival rate than males.
* **The "Class Effect":** Passengers in 1st Class (Pclass 1) had a much higher survival probability than those in 3rd Class.
* **Age Priority:** Children under the age of 10 were prioritized during the evacuation process.

## 🛠️ Technical Implementation
* **Language:** Python 3.x
* **Primary Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Visualization)
    * `Scikit-Learn` (Model Building & Evaluation)
* **Model Used:** [Enter Model Name, e.g., Logistic Regression or Random Forest]
* **Validation:** Used a train-test split to evaluate model performance on unseen data.

## 📈 Key Results
* **Accuracy Score:** [Enter your score, e.g., 81.5%]
* **Top Features:** The model relied most heavily on `Sex`, `Age`, and `Pclass` to make its predictions.

---

## 📂 Project Structure
* `final.py`: The main script containing the data processing and ML pipeline.
* `train.csv`: The training dataset with survival outcomes.
* `test.csv`: The test dataset used for making final predictions.

## 🚀 How to Use
1. Clone this repository.
2. Ensure you have Python installed.
3. Run `python final.py` to see the model results.
