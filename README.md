# BlackFridaySales-PricePrediction

![image](https://user-images.githubusercontent.com/83939313/118355541-23784480-b58e-11eb-958d-5d7b1b6e55c6.png)


1. INTRODUCTION ABOUT DATA SET

A retail company “ABC Private Limited” wants to understand the customer purchase behavior (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high-volume products from last month.
The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category), and Total purchase_amount from last month.
The data set has 12 features of 5891 users accounting for total data of 550068. 

2. Objective
To build a model to predict the purchase amount of customers against various products which will help them to create personalized offers for customers against different products.

3. REGRESSION TECHNIQUE
   Multiple Linear Regression
It is an extension of Simple linear regression(SLR) where we use one dependent variable with one independent variable but in multiple linear regression(MLR) we can multiple independent variables. 
MLR is more useful in comparison with the SLR because even in real-world scenarios, predicting about one thing is based upon multiple factors.

4. Variables
   Dependent Variable:
Purchase - Predicting the purchase amount of customers against various products. It is a continuous variable. 
   Independent Variables:
Gender: indicates the gender of the person making the transaction.
Age: indicates the age group of the person making the transaction.
Occupation: shows the occupation of the user, already labeled with numbers 0 to 20.
City_Category: User's living city category. Cities are categorized into 3 different categories 'A', 'B', and 'C'.
Stay_In_Current_City_Years: Indicates how long the users have lived in this city.
Marital_Status: is 0 if the user is not married and 1 otherwise.
Product_Category_1 to _3: Category of the product. All 3 are already labeled with numbers.
