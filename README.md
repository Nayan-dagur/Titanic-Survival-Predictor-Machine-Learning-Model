# Titanic Survival Predictor-Machine Learning Model
A beginner machine learning project based on the Kaggle Titanic dataset. This project demonstrates an end-to-end ML workflow including data cleaning, exploratory data analysis (EDA), feature encoding, model training, and evaluation.<br>
<br>
Project Overview<br>
The objective of this project is to predict passenger survival on the Titanic using demographic and travel-related features.

Key Tasks Performed

* Loaded and explored the Titanic dataset using Pandas.
* Cleaned the dataset by handling missing values and removing irrelevant features.
* Performed Exploratory Data Analysis (EDA) to identify patterns affecting passenger survival.
* Applied Label Encoding to categorical variables.
* Split the dataset into training and testing sets.
* Trained and evaluated multiple Machine Learning models.
* Compared model performance using accuracy metrics.



🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook



🧹 Data Preprocessing

Removed Features

The following columns were removed as they were not used in the baseline model:

* Cabin
* Ticket
* PassengerId
* Name

Missing Value Treatment

* Filled missing values in Age using the median value.
* Filled missing values in Embarked using the mode (most frequent category).

Feature Encoding

Categorical features were converted into numerical values using LabelEncoder:

* Sex
* Embarked



📊 Exploratory Data Analysis (EDA)

The analysis focused on understanding the relationship between passenger survival and important features such as:

* Gender (Sex)
* Passenger Class (Pclass)
* Age 

Key Observations

* Female passengers had significantly higher survival rates than male passengers.
* Passengers traveling in higher classes were more likely to survive.
* Age showed a moderate influence on survival outcomes.
* Passenger class and gender emerged as strong predictors of survival.



🤖 Machine Learning Models

Logistic Regression

A baseline linear classification model used to predict passenger survival.

Decision Tree Classifier

A tree-based classification model used for comparison against Logistic Regression.



📈 Results

Model	Accuracy
Logistic Regression	79%
Decision Tree	78%

Conclusion

Logistic Regression achieved the highest accuracy among the tested models and slightly outperformed the Decision Tree classifier on the test dataset.



📂 Project Workflow

Data Collection
      ↓
Data Cleaning
      ↓
Missing Value Treatment
      ↓
Exploratory Data Analysis
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation



🎯 Key Learnings

* Data cleaning and preprocessing techniques.
* Handling missing values in real-world datasets.
* Exploratory Data Analysis (EDA).
* Feature encoding using LabelEncoder.
* Training classification models using Scikit-learn.
* Model evaluation and comparison.
* Building a complete Machine Learning workflow from scratch.



🚀 Future Improvements

* Feature engineering using passenger titles and family information.
* Hyperparameter tuning.
* Cross-validation.
* Random Forest Classifier.
* XGBoost and ensemble learning methods.
* Feature importance analysis.



📁 Repository Structure

Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── README.md
└── dataset/



👨‍💻 Author

Nayan Dagur

Machine Learning Learning Journey 🚀
