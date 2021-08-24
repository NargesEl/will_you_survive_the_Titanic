# Will you survive the Titanic?

I used the Titanic passenger list to build a predictive model that calculates the chances of survival of a new passanger. To predict the wether or not the new passanger will survive we need the following data:
1. age
2. sex
3. travle class
4. traveling with a spouse and /or number of siblings travelling with
5. number of children treavling with

Results are with a 81% accuracy. 

Frist, I explored the data (Exploratory Data Analysis.ipynb) and then trained a logistic regression classification model. I also did some feature engineering, like one-hot encoding and calculated the train and test accuracy. Since not all passangers have their age recorded in the data, I tried several methodes to fill in the gaps. I dropped the rows with the age missing, replaced nan with the mean of the age column, and tried the median as well. Eventually, I used the mean of the age column to fill in the nan. I also trained a random forest classifiction model, and used the model and feature engineering that gave the highest accuracy to predict survival of a new passanger.

Once the Jupyter Notebook is run, input fields will appear at the bottom.

![Screenshot 2021-08-24 at 10 54 48](https://user-images.githubusercontent.com/80095773/130588655-0b65e0d7-fee2-47eb-8f5e-65ec62c2ba0d.png)

![Screenshot 2021-08-24 at 10 59 38](https://user-images.githubusercontent.com/80095773/130588660-1c7c7218-76ad-451d-815f-46018b61cd1b.png)

