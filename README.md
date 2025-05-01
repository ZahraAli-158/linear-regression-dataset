# linear-regression-dataset
  1.	Library Imports & Data Loading
	•	Imported essential libraries: pandas, numpy, matplotlib, and seaborn.
	•	Loaded the dataset from a CSV file using pandas.
	2.	Exploratory Data Analysis (EDA)
	•	Performed initial inspection with .head(), .tail(), .sample(), .shape, .describe(), and .info().
	•	Checked for missing values using df.isnull().sum(); none were found.
	•	Removed duplicate records and verified the updated shape of the dataset.
	3.	Outlier Detection and Removal
	•	Identified outliers using the IQR (Interquartile Range) method.
	•	Visualized data distribution before and after outlier removal using boxplots.
	4.	Feature Scaling
	•	Applied Min-Max Scaling and Standard Scaling on numerical features.
	•	These transformations normalized feature values for improved model performance.
