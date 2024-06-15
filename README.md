# PREDICTING-STROKE-PROBABILITY-BASED-ON-MEDICAL-HISTORY-AND-HEALTH-PARAMETERS
Investigate the correlation relationship between the attributes in the dataset and the predictive attribute, and build a predictive model for stroke probability based on the attributes that have a significant correlation relationship.
- Data Collection: In this study, we will collect information on gender, history of cardiovascular disease, hypertension, and work environment of individuals. We will also record whether they have had a stroke before.

- Data Collection Method: We are using the data files provided on the Kaggle platform - the leading platform for data repositories and online data science competitions. We will conduct data analysis by drawing charts using the Seaborn library.

- Data Balancing Method: In this study, the team used adding target data to balance the data. However, the results were not favorable, so the team has strengthened the SMOTE technique to perform data balancing. This is a method of creating random data that does not completely overlap with the existing data, so it does not affect the prediction results.

- Data Validation Methods: The authors use two data validation methods, ANOVA and Chi-square, to evaluate the independent attributes, find significant correlation relationships between the attributes and the predictive attribute.

- Model Evaluation Methods: Use the confusion matrix to get an overview of the model's prediction results. The decision evaluation criteria of the topic are based on the Receiver Operating Characteristic (ROC) curve. The ROC curve represents the correlation between the True Positive Rate and the False Positive Rate of the predictive model at different thresholds.

- Procedure: Analyze the basic data from the data file, perform preliminary assessments, predict data balancing, investigate the relationship of attributes using statistical methods, select appropriate attributes to build the prediction model, train the data set, check the prediction results and perform model evaluation.
