# Will you survive the Titanic?

I used the Titanic passenger list to build a predictive model that calculates the chances of survival of a new passanger given we have the age, sex, and travel class of that passanger. 

Frist, I explored the data (Exploratory Data Analysis.ipynb) and then trained a logistic regression classification model. I also did some feature engineering, like one-hot encoding and calculated the train and test accuracy. 


Since not all passangers have their age recorded in the data, I tried several methodes to fill in the gaps. I dropped the rows with the age missing, replaced nan with the mean of the age column, and tried the median as well. Eventually, I used the mean of the age column to fill in the nan. 
