# The-Future-Value-of-Homes
Incorporates machine learning and predicts the future values of homes for the next few decades based off of previous values for the state of Maryland. Implements the use of Bayesian regression due to our dataset not being tremendously large. A model is also created for visualization. 
Files Included:

1) AverageHomeValues.csv - Data table containing median price values for homes in Maryland from 1940-2020
2) Code.py - Raw python code created to obtain our model
3) Display of Model.png - Screenshot of model 


**Step 1)**
Import the necessary libraries


![ImportHomes](https://user-images.githubusercontent.com/60532479/82376624-6392fe80-99f0-11ea-90d0-89a179e3ca1d.png)


**STEP 2)**

Now I am grabbing the csv file attached within this repository. Due to me implementing more than just an integer for certain columns ($), I needed to then use pandas' "astype()" function to essentially pass my columns as a float in order for the program to execute properly.

![Grab dataset](https://user-images.githubusercontent.com/60532479/82469086-92ad7c80-9a91-11ea-8e1a-d2553e8f6a43.png)



**STEP 3)**

Set your size, titles, and fonts for the plot.

![Scale](https://user-images.githubusercontent.com/60532479/82469505-1d8e7700-9a92-11ea-842f-d567529298ee.png)


**STEP 4)**

Set your training and test sets. In this case I am training the model on all median values from 1940 to 2020. 

![Data](https://user-images.githubusercontent.com/60532479/82470381-45320f00-9a93-11ea-9830-e9119b45e9c8.png)


**STEP 5)**

Reshape and fit the data with the use of Bayesian Regression. 

![Reshape](https://user-images.githubusercontent.com/60532479/82472137-b4a8fe00-9a95-11ea-899c-b7710c1d698c.png)


**STEP 6)**


Predict up until the year 2050 and create print lines in order to display our training and test accuracy. 


![Pred](https://user-images.githubusercontent.com/60532479/82472744-a6a7ad00-9a96-11ea-85e4-8fe5a041ecf3.png)


**STEP 7)**

Set up plot and label the training data, test data, and prediction. Lastly, show the plot and accuracy.

![PltData](https://user-images.githubusercontent.com/60532479/82473922-44e84280-9a98-11ea-8309-c045652c6b74.png)

![FinalPlot](https://user-images.githubusercontent.com/60532479/82474914-be346500-9a99-11ea-8e5b-0e1a863652b4.png)











