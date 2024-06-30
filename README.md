

Titanic Survival Prediction

Overview
This project uses machine learning to predict the survival of passengers on the Titanic based on various features such as age, gender, class, and more.

Dataset
The dataset used is the Titanic Dataset from Kaggle, which contains information on 891 passengers, including:
- Demographic features (age, gender, class)
- Travel features (cabin, embarkation port)
- Outcome (survived or not)

Step 1: Data Loading and Exploration
Loaded the dataset using Pandas and explored the data using various functions such as head(), info(), and describe().

Step 2: Feature Engineering
Created new features:
- Family Size: calculated the size of each passenger's family
- Title: extracted the title (Mr, Mrs, Miss, etc.) from the name column

Step 3: Data Preprocessing
Handled missing values:
- Dropped rows with missing values in the Age column
- Filled missing values in the Embarkation Port column with the most frequent value

Encoded categorical variables:
- Gender (male/female)
- Class (1st, 2nd, 3rd)
- Embarkation Port (Cherbourg, Queenstown, Southampton)

Step 4: Model Selection and Training
Split the data into training and testing sets (80% training, 20% testing)

Trained four different models:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Step 5: Model Evaluation
Evaluated each model using various metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

Step 6: Model Deployment
Used the best-performing model (Random Forest) to make predictions on new data.

Usage
- Run the notebook titanic_survival_prediction.ipynb to explore the dataset and train the models.
- Use the predict function to make predictions on new data.
- Evaluate the models using the evaluation metrics.

Requirements
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn


Author
Prachi Kumari
prachikumari2804@gmail.com
