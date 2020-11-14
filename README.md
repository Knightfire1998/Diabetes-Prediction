# Diabetes-Prediction
# Dataset - 
The dataset consist of 8 attributes and 1 output variable as follows:  
1.'Pregnancies'- No of pregnancies the person had  
2.'Glucose'- Glucose level of the person  
3.'BloodPressure'- Bp of the person  
4.'SkinThickness'-Thickeness of skin  
5.'Insulin' - Insulin level of the person  
6.'BMI'- Represents the body mass index of a person  
7.'DiabetesPedigreeFunction'- data on diabetes mellitus history in relatives and the genetic relationship of those relatives to the patient   
8.'Age'- Age of the person    
9.'Outcome'- whether the person is suffering from diabetes (1) or not (0)  
# Some Insights in the dataset 
Dataset had no missing values  
Outliers were handled by visualizing them using box plot   
Data was skewed so log tranformation was applied to the data  

# Steps 
#### 1. Data was visualized using seaborn and all the outliers and skewed data was handled 
#### 2. After that Correlation between attributes was calculated 
#### 3. A simple random forest classifier was used to determine if a person is suffering from diabetes or not
#### 4. A RandomizedSearchCV was used to optimize hyperparameters of RandomForest classifier

# Results
RandomForest Classifier - 95.33 %  
RandomForest Classifier (Hpyertuned) - 97.98 %  

# Requirements 
#### Python 3.*  
#### Pandas  
#### Matplotlib   
#### Seaborn  
#### sklearn  

# Links
![Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
