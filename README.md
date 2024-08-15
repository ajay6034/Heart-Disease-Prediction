# Heart-Disease-Prediction
### Data Loading and Initial Exploration:
1. Pandas was used to load the dataset into a DataFrame using the read_csv function, which allowed for easy manipulation and exploration of the data.
2. The first few rows of the dataset were displayed using the head() function to get an initial sense of the data structure, including the columns and their respective data types.
3. Performed a summary of the dataset using info() to check for missing values, data types, and overall dataset structure. This step helped us confirm that the data types were appropriate for the subsequent analysis.
### Data Visualization:
1. Seaborn and Matplotlib were employed for visualizing the data.
2. A histogram was generated which provided insights into the distribution of each numerical feature in the dataset. This helped in identifying the distribution patterns, potential skewness, and presence of outliers in the data.
3. A count plot of the target variable was created.This visualization allowed us to observe the distribution of the target variable, helping to assess whether the dataset was balanced or imbalanced.
### Data Transformation:
1. I used the select_dtypes() method from Pandas to identify categorical columns in the dataset. This method filtered the columns based on their data type, specifically looking for those with an object data type, which typically represents categorical data.
2. I cheked regarding the presence of categorical variables obj. There is no 'obj' data type variables in the dataset. So, there is no need of doing One-Hot Encoding.

## Model Building
1. I splitted the dataset using train_test split which is avialbale from the sklearn library.
After I applied StandardScalar on the X_train,X_test for the standardization of the data.
2. After Logistic Regression model is fitted on X_train, y_train. After that predicted using X_test.
3. If there is any point which lies exactly at the center of the line. In this this if we want to know what is the probability for the point to which class it belongs to, We can use logistic.predict_proba(X_test).
4. Peformed the metrics like accuracy score, Confusion matrix, classification report which tells about F-1 score, precision, recall.
5. Finally I got around 0.89 on test data from the model

