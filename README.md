# HouseSales-Prediction


*  Goal is to develop a model that has the capacity of predicting the value of houses, we will split the dataset into features and the target variable and store them in features and prices variables.
*  The first problem was where can we get the data to build a large enough dataset since we want to be able to predict the price for a given house according to the real estate agency chosen.Firstly, we tried to find a dataset already done on the web and we gathered the data from kaggle.com .We have done this in  a python 3 Jupyter Notebook and executed the code snippet to load the dataset and remove the non-essential features. Receiving a success message if the actions were correctly performed.
*  Next, we tried to figure out what kind of chart we could use and it turns out that each one has its own advantage depending on what we want to visualize. We have started by creating some plots that will  allow us to visualize the pair-wise relationships and correlations between the different features. For our project we have used linear regression model and we have trained and tested our data for predicting the prices.
*  Here the object is to discuss the major factors that affect housing price and make precise predictions for it. We use 22  explanatory variables including almost every aspect of residential homes in King county, Usa.
*  Methods of both statistical regression models and machine learning regression models are applied and further compared according to their performance to better estimate the final price of each house. 
*  The model provides price prediction based on similar comparables of people’s dream houses, which allows both buyers and sellers to better negotiate home prices according to market trend.


 - - - -
 
 ## Data Source
 * https://www.kaggle.com/harlfoxem/housesalesprediction 
 * https://nominatim.openstreetmap.org/search/  
 ---------------------------------------

## Terms that are mainly used in project
 
* ### Preprocessing
   \- Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model. It is the first and crucial step while creating a machine learning model.

* ### Regression:
   \- Regression in machine learning consists of mathematical methods that allow data scientists to predict a continuous outcome (y) based on the value of one or more predictor variables (x). 
   
   \- Linear regression is probably the most popular form of regression analysis because of its ease-of-use in predicting and forecasting.

* ### Heat map:
   \- A heat map is a two-dimensional representation of information with the help of colors. Heat maps can help the user visualize simple or complex information.

* ### KDE plot:
   \- KDE Plot described as Kernel Density Estimate is used for visualizing the Probability Density of a continuous variable. 
   
   \- It depicts the probability density at different values in a continuous variable. We can also plot a single graph for multiple samples which helps in more efficient data visualization.
   
* ### Residual plot:
   \- A residual is a measure of how far away a point is vertically from the regression line. Simply, it is the error between a predicted value and the observed actual value.
   
* ### Pipeline:
   \- A machine learning pipeline is used to help automate machine learning workflows. 
   
   \- They operate by enabling a sequence of data to be transformed and correlated together in a model that can be tested and evaluated to achieve an outcome, whether positive or negative.
   
---------------------------------------

## Visualizations 
 * ### CountPlot
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Count%20plot.png)
    
    \- The above graph is Count plot between bedrooms,bathrooms,floors and grade. We use countplot rather scatter plot for easy understanding.
    
 
 * ### Regression Plot
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Scatter%20plot.png)
    
    \- These are  Regression plots for all the sqft area columns with respect to price. It is used here to observe and show the relationship between numerical values. In the above plots , dots represents actual data points.
    
 
 * ### Heat Map
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Heat_Map.png)
    
    \- This is a heatmap is drawn only between selected columns which are having high correlation values. 
 
 * ### KDE plot for price vs probability density function using Linear Regression
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Actual%20vs%20Fitted%20data%20using%20Linear%20Regression.png)
    
 * ### KDE plot for price vs probability density function using Pipeline Parameters
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Actual%20vs%20Fitted%20data%20using%20Pipeline.png)
  
 * ### Residual plot for price vs probability density function.
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Residual%20plot%20for%20price%20vs%20Probability%20Density%20function.png)
    
 * ###  final regression plot which got accuracy upto 80%
    ![Alt text](https://github.com/Ajay482/HouseSales-Prediction/blob/fc9263269f2fb94c5ecd2db6e65db60494780457/Visualization/Regression%20plot.png)
    

 ## CONCLUSION
 * The accurate prediction model would allow investors or house buyers to determine the realistic price of a house as well as the house developers to decide the affordable house price. 
 * This  addressed the attributes used by previous researchers to forecast a house price using various prediction models. The models were developed based on several input attributes and they work significantly positive with house price. 
 * In conclusion, the impact of this research was intended to help and assist other researchers in developing a real model which can easily and accurately predict house prices. Further work on a real model needs to be done with the utilization of our findings to confirm them. 

