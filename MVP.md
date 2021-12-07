# Aqar

Due to the information gap about house prices and the difference in house prices from one neighborhood to another, the individual may face a problem estimating house prices and may be subject to deception by real estate owners.
Therefore, we will build a model that predicts house prices in various neighborhoods in Saudi Arabia's capital Riyadh based on several features . Which are a Price of house , size of house , number of rooms , number of bathrooms and Districts . 
In the beginning, we have to know the most expensive neighborhoods so that we can be sure later that the model is able to predict prices based on the given data

![c11](https://user-images.githubusercontent.com/71217830/145083390-c63bc617-ea83-45cb-8ee4-64e82f6e270d.png)

As shown in the picture, the most expensive neighborhoods are :Al-hamra , Al-Aqiq , Al-malga and A-Narjes. And we solved the dummies and now the number of features is : 13868 rows and 27 columns

![corr](https://user-images.githubusercontent.com/71217830/145083648-586cc4ea-4ecd-4252-88f0-af3a453dce6b.png)

As shown in the picture , there is high correlation between Price and size(Area) and between Price , neighborhood Al-hamra , as what we say above Al-hamra the most expensive neighborhood, and neighborhoods is the  most important feature that affects the price.
We will make a CV to determine the best model for the project to predict the prices of houses in different neighborhoods of  Riyadh city.
