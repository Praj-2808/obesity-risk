
# Obesity Risk Prediction

**Overview:**
This project aims to predict obesity risk levels in individuals based on various factors such as age, gender, family history, lifestyle, and more. The target variable, NObeyesdad, represents different obesity categories, and the goal is to classify individuals into one of these categories using machine learning models.

**Features Obesity Risk Categories:** 
The target variable, NObeyesdad, includes categories like:
- Obesity_Type_III
- Obesity_Type_II
- Obesity_Type_I
- Normal_Weight
- Insufficient_Weight
- Overweight_Level_II
- Overweight_Level_I

**Features:** Includes demographic, lifestyle, and health-related factors, such as:
- Age
- Gender 
- Height 
- Weight
- Family history of overweight
- Smoking habits
- Physical activity 
- Food consumption patterns
- Mode of transportation 

**Requirements:**
Python 3 Libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- sklearn.metrics
- sklearn.preprocessing
- sklearn.model_selection
- sklearn.ensemble
- sklearn.tree
- xgboost


**Project Workflow**
1. Data Preprocessing:

- Cleaning the data by handling missing values, duplicates, and encoding categorical variables.
- Feature scaling using MinMaxScaler.
- Splitting the data into training and testing sets.
2. Modeling:

- Training machine learning models to predict obesity risk based on the preprocessed data.
- Models used: Random Forest classifier.
3. Evaluation:

- Evaluating the performance of the trained models using confusion matrix, accuracy, and other metrics.
- Visualization of the confusion matrix and performance metrics.
4. Predictions:
- For each individual in the test set, predict the obesity risk category based on their feature values.
- This will train the model and evaluate its performance on the test set.

**Data:**
The dataset used for this project includes health-related information and obesity categories, which is available in train_data.csv.

**Conclusion:**
This project demonstrates how machine learning can be used to predict obesity risk based on various factors. The model can be further optimized and extended to include more features or use advanced algorithms for improved predictions.

**License:**
This project is licensed under the MIT License.


