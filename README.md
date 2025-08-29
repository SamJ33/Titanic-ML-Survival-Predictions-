# Titanic ML Survival Predictions:

Analyzing the data of the people on the titanic and predicting who survived through Advanced Machine Learning.


## Overview  
This project predicts survival on the Titanic dataset (Kaggle competition).  
The workflow includes:  
- **Exploratory Data Analysis (EDA)**  
- **Feature Engineering with One-Hot Encoding**  
- **Modeling with Random Forest and AdaBoost**  
- **Hyperparameter Tuning using GridSearchCV**  

---

## Steps  

### 1. EDA  
- Checked dataset structure and missing values.  
- Explored survival patterns (by gender, age, passenger class).  
- Visualized key insights with plots.  

### 2. Feature Engineering  
- Handled missing values in `Age`,`Embarked`, 'Cabin' and more.
- Applied **one-hot encoding** for categorical features (`Sex`, `Embarked`, etc.).  
- Scaled numerical features where necessary.  

### 3. Modeling  
- Used two ensemble classifiers:  
  - **Random Forest Classifier**  
  - **AdaBoost Classifier**  

### 4. Hyperparameter Tuning  
- Applied **GridSearchCV** and **RandomizedSearchCV** to optimize model parameters.  
- Compared best models from each algorithm.  

### 5. Evaluation  
- Metrics: **Accuracy**, **Precision**, **Recall**, **F1-score**.  
- Identified most important features influencing predictions.  

---

## Results  
- **Random Forest**: strong performance with key features (`Sex`, `Pclass`, `Fare`).  
- **AdaBoost**: competitive and generalized well.  
- Best accuracy after tuning: **~80–83%**.  

---

## Usage
- Clone the repository:

- git clone https://github.com/your-username/titanic-ml.git
  cd titanic-ml


- Run the notebook:

jupyter notebook Titanic.ipynb
