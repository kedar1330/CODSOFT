# CODSOFT
These are my datascience projects
Titanic Survival Prediction Project
Project Overview
This project is focused on predicting the survival of passengers on the Titanic using machine learning techniques. The Titanic dataset includes various features such as age, gender, ticket class, fare, and more, which we use to build a predictive model. This project is a common beginner-level task that provides insights into the steps involved in data preprocessing, exploratory data analysis (EDA), and model building.

Dataset
The dataset used in this project is the Titanic Dataset, typically available on Kaggle's Titanic Competition.

Key Features in the Dataset:
Survived: Outcome variable, indicating if a passenger survived (1) or not (0).
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings or spouses aboard.
Parch: Number of parents or children aboard.
Fare: Ticket fare.
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Project Structure
The project contains the following files:


Titanic-Survival-Prediction/
├── Titanic-Dataset.csv            # Dataset used in the project
├── titanic_survival_notebook.ipynb # Jupyter Notebook with code and analysis
├── titanic_survival_notebook.pdf   # PDF export of the Jupyter Notebook
└── README.md                       # Project overview and instructions
Getting Started
Prerequisites
To run this project, you'll need Python and the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can install these packages via pip:


pip install pandas numpy matplotlib seaborn scikit-learn
Running the Project
Clone the repository or download the files.
Open titanic_survival_notebook.ipynb in Jupyter Notebook.
Run each cell sequentially to perform data preprocessing, EDA, model training, and evaluation.
Results
The notebook evaluates multiple machine learning models, including:

Logistic Regression
Decision Tree
Random Forest
The best-performing model was  Random Forest, achieving an accuracy of 0.8212290502793296% on the test data.

Key Findings
Gender and Ticket Class showed strong correlations with survival, with females and higher-class passengers having higher survival rates.
Feature engineering, such as combining SibSp and Parch into FamilySize, helped improve model performance.
Conclusion
This project demonstrates the process of building a predictive model, from data cleaning and visualization to model selection and evaluation. The results provide insight into which features most influenced survival on the Titanic, and the models created can be further improved with advanced techniques such as hyperparameter tuning.

License
This project is for educational purposes and may use data made publicly available by Kaggle and other sources.
