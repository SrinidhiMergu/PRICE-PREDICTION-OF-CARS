# Price Prediction of Used Cars 

Predicted the costs of used cars for given data collected from various locations in India.

#### FEATURES:
- Name: The brand and model of the car.
- Location: The location in which the car is being sold or is available for purchase.
- Year: The year or edition of the model.
- Kilometers_Driven: The total kilometres driven in the car by the previous owner(s) in KM.
- Fuel_Type: The type of fuel used by the car.
- Transmission: The type of transmission used by the car.
- Owner_Type: Whether the ownership is Firsthand, Second hand or other.
- Mileage: The standard mileage offered by the car company in kmpl or km/kg
- Engine: The displacement volume of the engine in cc.
- Power: The maximum power of the engine in bhp.
- Seats: The number of seats in the car.
- Price: The price of the used car in INR Lakhs.

#### TASKS PERFORMED:
- Clean Data (Null value removal, Outlier identification)
- Null Values (Dropping the rows /Columns and what is the reason or how you are imputing the null).
- Performed Exploratory Data Analysis
- Handled categorical variables (label encoding/one hot encoding), performed data 
- Try to do data scaling for Kilometers driven
- Done train test  split
- Apply different ML regression Algorithms
    1. Linear Regression
    2. Logistic Regression
    3. KNN 
- calculated error metrics for each model
    1. mean_absolute_error
    2. mean_squared_error
    3. root_mean_sqaured_error
