# boston_house_pred
### Boston House Pricing Prediction Model
## Software and Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment
...
conda create -p venv python==3.7 -y

...

Step for data preprocessing, data visualization, model building and coamparing of deifferent models:

1. Import important libraries
2. Open dataset
3. Read the dataset by checking their info, summary and checking null values
4. Check Correlation of the features
5. Visualize the different features with scatter plot, regression plot to identify any significant pattern
6. Split the dataset for training and testing
7. Scale the dataset by using standard scaler
8. Train the data by Linear Regression model
9. Check coefficient, intercept and parameters of the model
10. Predict the model on testing data
11. Visualize the predicted result by scatter plot
12. Check the residuals and visualize them by scatter and displot
13. Evaluating the model by checking R^2, adjusted R^2, Mean squared error and MEan absolute error
14. Predict for new dataet
15. Repeat these steps for Random Forest, XGBoost Regressor and SVM Regressor
16. Compare all the models on the basis of R^2
17. Pickle the model for deployment


