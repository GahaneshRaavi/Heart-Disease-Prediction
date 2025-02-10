# Heart-Disease-Prediction

       1.Data Preprocessing with Pandas & NumPy
       • Loaded the heart_disease.csv dataset using Pandas.
       •Handled missing values by replacing them with the median to improve data quality.
  
	2.Exploratory Data Analysis (EDA) with Seaborn & Matplotlib
	•	Used .describe() and .info() for dataset insights.
	•	Created a correlation matrix and visualised it using a Seaborn heatmap to understand feature relationships.
 
	3.Feature Selection & Data Splitting with Scikit-Learn
	•	Dropped the target column (heart_disease) to define feature (X) and label (y) variables.
	•	Split the dataset into 80% training and 20% testing using train_test_split().
 
	4.Model Selection & Training using Decision Tree Classifier
	•	Implemented a Decision Tree Classifier (DecisionTreeClassifier) with the ‘entropy’ criterion.
	•	Trained the model on the training dataset.
 
	5.Model Visualization with Matplotlib & Scikit-Learn
	•	Used plot_tree() from Scikit-Learn to visualise the trained decision tree structure.
	•	Displayed decision paths and feature importance.
 
	6.Performance Evaluation using Scikit-Learn Metrics
	•	Predicted outcomes on the test dataset.
	•	Measured accuracy using accuracy_score() and generated a classification report.
