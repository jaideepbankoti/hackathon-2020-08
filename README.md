# hackathon-2020-08
## Machine Learning project repository for hackathon (august, 2020)

### Part-A
>I used the XGBoost model to predict the stock price on 10th August. I first preprocessed and cleaned the data. There were no significant outliers, and some of the features were correlated so, this way I was able to impute missing values for some features. I removed the ‘Index’ feature as it doesn’t seem to have any significant importance. I imputed the numerical features by first combining the whole train and test data then, using mean imputation strategy as the box-plots suggest uniform symmetric distribution.
After all the preprocessing, I split the data to train and validation set, and proceeded to train the model. The model is an XGBRegressor with parameters set in such a way that it doesn’t overfit to the train set and give decent rmse measure for validation set. I also save this model as ‘HackPrice.model’ to use it further in solution 2. I also saved the preprocesseed test data.

### Part-B
>For the Time series prediction, I used an XGBoost model. I first formatted the data and further created features(datetime features) for each stock. I have also plotted them to visualize the trends the stocks are following. Once I have done that I created a function ‘model_predictor(args**)’ that defines model for each stock and predicts the PCR (put to call ratio) values of 16th August.
After that I loaded the saved test data from part one and replaced the PCR column, assuming the other values doesn’t change much. Then I feed this test set to ‘HackPrice.model’ from part 1 of the problem, and predict stock prices for 16th August.

# Flipr Hackathon 5.0 | Machine Learning


### Hackathon Problem Statement

>Stock market prediction is the act of trying to determine the future value of a company stock or other financial instrument traded on an exchange. The successful prediction of a stock's future price could yield significant profit. The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not based on newly revealed information thus are inherently unpredictable. Others disagree and those with this viewpoint possess myriad methods and technologies which purportedly allow them to gain future price information.
Ever since COVID 19 strike, markets loom under fear as uncertainty prevails. lt has sent markets around the world crashing to levels not witnessed since the Global Financial Crisis of 2008. Following the strong correlation with the trends and indices of the global market as BSE Sensex and Nifty 50 fell by 38 per cent.
The challenge of the stock price forecast is the most crucial component for companies and equity traders to predict future revenues. A successful and accurate prediction to the future stock prices ultimately results in profit maximization.


## Detailed Report Card

#### Name : Jaideep Singh Bankoti

#### College : Indian Institute of Technology, Gandhinagar

### Prediction Algorithm

### Rating: A+

### Remarks: Well researched and optimized choice of algorithm

### Time-series Algorithm

### Rating: A+

### Remarks: Well researched and optimized choice of algorithm

### Overall Accuracy

### Rating: A+

### Remarks: Optimum accuracy

## ML for beginners

#### ML Books

1. Machine Learning For Absolute Beginners by Oliver Theobald
2. Machine Learning (in Python and R) by John Paul Mueller
3. Machine Learning for Hackers by Drew Conway & John Myles
4. Basic Econometrics by Damodar N. Gujarati

#### ML Competitions

1. Flipr Hackathons : https://flipr.ai/hackathon/
2. Kaggle Competitions : https://www.kaggle.com/competitions
3. Driven Data : https://www.drivendata.org/

#### ML Websites to learn

1. Edx : https://www.edx.org/
2. Coursera : https://www.coursera.org/
3. Udemy : https://www.udemy.com/
4. Upgrad : https://www.upgrad.com/
5. Youtube Tutorials : https://www.youtube.com/watch?v=9f-GarcDY
