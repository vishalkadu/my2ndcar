# My2ndCar

The My2ndCar Price Prediction Service App is built using Flask, Python, ML algorithms., which predicts the selling price of a car based on given independent features such as Car_Name, Year, Selling_Price, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, and Owner.

## About the Dataset

This dataset can be used for a lot of purposes, such as price prediction to exemplify the use of Regression in Machine Learning. The columns in the given dataset are as follows:

1. Car_Name
2. Year
3. Selling_Price
4. Present_Price
5. Kms_Driven
6. Fuel_Type
7. Seller_Type
8. Transmission
9. Owner

## Algorithm

After applying different Machine Learning algorithms, we get different model accuracies and R2 Score such as:

- Linear Regression with the Accuracy: 80.40% and R2 Score (Coefficient of determination) is 0.8517983059778264
- Random Forest Regressor with the Accuracy: 83.22% and the R2 Score is 0.8693858585024029
- Decision Tree Regressor with the Accuracy: 87.10% and R2 Score is 0.913621047690589

Thus, the Decision tree regression algorithm gave us the best accuracy and score on the training dataset in comparison with other algorithms.

## Usage

1. Docker:

Clone this repository,

build docker image from from Dockerfile in the main directory. 

$docker build -t my2ndcar .

then run 

$docker run -p 5000:5000 -it --name My2ndCar my2ndcar

2. System:

Clone this repository, 

then install requirements

$pip install -r requirements.txt

to run

$python3 app.py

make sure you are in main directory.



## Application Preview

![image](https://user-images.githubusercontent.com/86619476/157186601-7f0db898-06ad-4a93-9fc6-a8ccf5d3b81f.png)


### Thank You!
