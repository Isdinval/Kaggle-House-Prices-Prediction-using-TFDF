# Kaggle-House-Prices-Prediction-using-TFDF

## Competition Description
![alt text](https://github.com/Isdinval/Kaggle-House-Prices-Prediction-using-TFDF/blob/main/housesbanner.png?raw=true)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

## Practice Skills
+ Creative feature engineering 
+ Advanced regression techniques like random forest and gradient boosting

## Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

Photo by Tom Thain on Unsplash.

## My Message
Welcome to my GitHub repository!

In this project, I had the exciting opportunity to participate in the Kaggle House Prices - Advanced Regression Techniques competition. The goal was to predict sales prices and gain practical experience in feature engineering, random forests, and gradient boosting.

Throughout the project, I employed various regressor models to tackle the challenge. I explored the classic TensorFlow Decision Forest and experimented with different variations, including the GradientBoostedTreesModel and the CART model. Additionally, I utilized powerful regressors such as Lasso, Elastic Net, Kernel Ridge, Gradient Boosting Regressor, XGBoost, and LightGBM to enhance my predictions.

My overall approach to this problem was designed to be concise yet effective. Here's an overview of the feature engineering process I employed:
- Sequentially imputing missing values: I addressed missing data points in a step-by-step manner, ensuring that each variable was appropriately handled.
- Treating numerical variables as categorical: For certain numerical variables that exhibited categorical behavior, I transformed them to capture their underlying nature accurately.
- Label encoding for ordered categorical variables: Categorical variables that conveyed ordered information were encoded using a label encoding technique, preserving their inherent order.
- Box Cox Transformation for skewed features: Instead of a standard log-transformation, I applied the Box Cox Transformation to skewed features. This approach proved to yield slightly better results in both the leaderboard and cross-validation stages.
- Creating dummy variables: Categorical features were transformed into dummy variables, allowing the models to effectively capture their impact on the target variable.

By following this approach, I was able to build a robust and efficient solution for the Kaggle House Prices competition. I hope that the techniques and models showcased in this repository will be valuable to fellow data enthusiasts and inspire further exploration in the field of regression analysis.

Feel free to explore the code and documentation provided here. If you have any questions or suggestions, please don't hesitate to reach out. Happy coding and happy predicting!
