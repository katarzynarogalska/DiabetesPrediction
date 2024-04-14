# DiabetesPrediction
# Main Info
In this repository you will find a machine learning project, which aim is to predict the risk of diabetes. 
Data frame for predictions is from [Kaggle diabetes health indicators](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data?select=diabetes_012_health_indicators_BRFSS2015.csv).

# Milestones
* **Data understanding** : the first part is columns description, feature number, checking for missing values, checking types of features, size of data frame
* **Train Validation Test split** : Splitting the data frame into 3 frames. Train_df is for us to train our models, Val_df is also for us to check the scores after creating models, Test_df is only for validation team to independently validate our project at the end
* **EDA** : Data Analysis part, which involves correlation matrix, target characteristics, target vs other features plots, first thought about most and least relevant features
* **Feature importance** : In this part we use feature importance methods like chi2, mutual information and random forest to see which features seem to be the most relevant, and which we can potentailly drop
* **Feature engineering**: Using observations from previous parts we bin, drop but also create new features and once again check their importance
* **Modeling**: We experiment with different models using different variations of our original dataframe, tune parameters and see which models have the best score
* **Final model selectiom**: in this part we will choose our final model, pass the notebook to the validation team and write a report 

# Authors 
1) [Katarzyna Rogalska](https://github.com/katarzynarogalska)
2) [Nazarii Bihniak](https://github.com/nazaribih)