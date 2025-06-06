# Machine-learning-project
**Lung cancer prediction project**
**I. Objective**
The main objective of this project is to:
- Analyze a dataset related to lung cancer
- Visualize and understand key patterns in the data
- Clean the data by handling outliers
- Train machine learning models to predict the presence of lung cancer

**II. Dataset Description**
The dataset includes several features such as:
- AGE: Age of the individual
- SMOKING, ALCOHOL CONSUMING, AIR POLLUTION, GENETIC RISK, etc.: Lifestyle and environmental factors
- LUNG_CANCER: Target variable (1 = Yes, 2 = No)

**III. Data Preprocessing**
Steps taken:
- Handled missing or inconsistent values (if any)
- Encoded categorical values appropriately
- Removed outliers using the Interquartile Range (IQR) method (for features like AGE)

**IV. Data Visualization**
To better understand the dataset:
- Boxplot: Created to visualize the distribution of AGE by LUNG_CANCER status and detect outliers
- Scatterplot: Can be added to explore correlations between features

**V. Model Building**
**Several machine learning models were explored:**
- Logistic Regression
- Random Forest Classifier
- SVC
- XGBoost Classifier

**Evaluation metrics used:**
- Accuracy
- Confusion matrix
- Classification report
- Highest model accuracy achieved: 96%

**VI. How to Run**
- Open the notebook in Google Colab 
- Run cells step-by-step to:
- Load the dataset
- Clean and visualize the data
- Train and evaluate models

**VII. Notes**
- This project is intended for educational purposes only
- The model is trained on a relatively small dataset and should not be used for actual medical diagnosis
