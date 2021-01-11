# Credit-card-fraud-detection

Business challenge of this capstone project is to detect potential frauds so that customers are not wrongly charged for items that they did not purchase. We know that credit card fraud has become more & more rampant in recent years. So there is a dire need to improve risk management level in an effective way. This can be achieved by building an accurate & easy credit card risk monitoring system. There are many Machine learning algorithms that can be used for this purpose. The main aim of this project is to build a user model that best identifies fraud cases.

The project pipeline can be briefly summarized in the following four steps:
1. Data Understanding: We 1st loaded the data and observed the features present in it

2. Exploratory data analytics (EDA): We performed univariate and bivariate analyses of the data to observe relationship between Amout and Time with class. Dataset is checked for skewness and power tranform is used to mitigate the same, as it might cause problems during the model-building phase.

3. Train/Test Split: We performed train/test split, to check the performance of our models with unseen data. Here, for validation, you have use the Stratified k-fold cross-validation method. 

5. Model-Building/Hyperparameter Tuning: This is the final step at which we tried different models and fine-tuned their hyperparameters until we g0t the desired level of performance. For hyperparameter tuning, random and grid search are the two popular methods available in scikit-learn in the form of RandomiszedSearchCV and GridSearchCV, respectively.
