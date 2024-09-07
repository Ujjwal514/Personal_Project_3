# CAR PRICE PREDICTOR
![demo](https://github.com/user-attachments/assets/ef03fc8f-c178-4e92-bd1e-591fce50ad31) 
AIM:-
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

![predict](https://github.com/user-attachments/assets/04807620-20a8-4d44-adcc-5d80d5b204ff)

REQUIREMENTS:-
1.Install the required packages in "requirements.txt" file.
Some packages are:

A.numpy
B.pandas
C.scikit-learn
2.Run the "application.py" file And you are good to go.

DESCRIPTION:-

What this project does?

This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10.

![predict (1)](https://github.com/user-attachments/assets/6486f67a-3658-46bc-97d3-39e7d50cb9c2)

How this project does?

1.First of all the data was scraped from Quikr.com (https://quikr.com) 

2.The data was cleaned (it was super unclean :( ) and analysed.

3.Then a Linear Regression model was built on top of it which had 0.92 R2_score.

4.This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

