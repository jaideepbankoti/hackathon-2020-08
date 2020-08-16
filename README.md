# hackathon-2020-08
## Machine Learning project repository for hackathon (august, 2020)

### Part-A
>I used the XGBoost model to predict the stock price on 10th August. I first preprocessed and cleaned the data. There were no significant outliers, and some of the features were correlated so, this way I was able to impute missing values for some features. I removed the ‘Index’ feature as it doesn’t seem to have any significant importance. I imputed the numerical features by first combining the whole train and test data then, using mean imputation strategy as the box-plots suggest uniform symmetric distribution.
After all the preprocessing, I split the data to train and validation set, and proceeded to train the model. The model is an XGBRegressor with parameters set in such a way that it doesn’t overfit to the train set and give decent rmse measure for validation set. I also save this model as ‘HackPrice.model’ to use it further in solution 2. I also saved the preprocesseed test data.

### Part-B
>For the Time series prediction, I used an XGBoost model. I first formatted the data and further created features(datetime features) for each stock. I have also plotted them to visualize the trends the stocks are following. Once I have done that I created a function ‘model_predictor(args**)’ that defines model for each stock and predicts the PCR (put to call ratio) values of 16th August.
After that I loaded the saved test data from part one and replaced the PCR column, assuming the other values doesn’t change much. Then I feed this test set to ‘HackPrice.model’ from part 1 of the problem, and predict stock prices for 16th August.
