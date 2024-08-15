# Heart-Disease-Prediction
## Data Loading and Initial Exploration:
1. Pandas was used to load the dataset into a DataFrame using the read_csv function, which allowed for easy manipulation and exploration of the data.
2. The first few rows of the dataset were displayed using the head() function to get an initial sense of the data structure, including the columns and their respective data types.
3. Performed a summary of the dataset using info() to check for missing values, data types, and overall dataset structure. This step helped us confirm that the data types were appropriate for the subsequent analysis.
## Data Visualization:
1. Seaborn and Matplotlib were employed for visualizing the data.
2. A histogram was generated which provided insights into the distribution of each numerical feature in the dataset. This helped in identifying the distribution patterns, potential skewness, and presence of outliers in the data.
3. A count plot of the target variable was created.This visualization allowed us to observe the distribution of the target variable, helping to assess whether the dataset was balanced or imbalanced.
## Data Transformation:
1 I used the select_dtypes() method from Pandas to identify categorical columns in the dataset. This method filtered the columns based on their data type, specifically looking for those with an object data type, which typically represents categorical data.
2. I cheked regarding the presence of categorical variables obj. There is no 'obj' data type variables in the dataset. So, there is no need of doing One-Hot Encoding.

