# Project: Capstone_Assignment_20.1

Author: Rohit Kamath

Datasource: https://www.energy.ca.gov/files/zev-and-infrastructure-stats-data

Python Jupiter notebook:  https://github.com/VulcanLogicWeaver/Capstone_Assignment_20.1/blob/main/Capstone_Project.ipynb

Project Overview:
- Assess the projected rate of EV adoption in California
- Assess the impact on electricity demand as a result of EV adoption
- Assess if the rate of deployment of EV charging stations meets the projected needs

Dataset Information:
- Light-duty vehicle sales data 
  (total light-duty vehicle sales for both ZEV and Non-ZEV by county.)
- Zero emission vehicle sales data
  (Zero Emission Vehicles (ZEV) sales are updated on a quarterly basis by examining the DMV Vehicle Registration database)
- Electric charging stations data
  (Charger counts are updated on a semi-annual basis by conducting analysis of data from the following sources:)
- Hydrogen refueling stations data
  (Hydrogen refueling station counts are updated quarterly by the California Energy Commission staff administering the Clean Transportation Program funding for these stations.)

# Interpretation of evaluation metrics
R-squared: Represents the variance in the dependent variable (ZEV Sales) that is predictable from the independent variable (Data Year). The low value in this case indicates that 'Year' alone is not a good fit and is a poor predictor of ZEV sales.

Mean Absolute Error: The average of the absolute differences between the actual and predicted values. This simple metric indicates the average model's predictions for ZEV sales are off by approximately 49 vehicles.

Mean Squared Error: The average of the squared differences between the actual and predicted values. The high values indicates larger prediction errors, as this model penalizes larger more heavely as the errors are squared.

Root Mean Squared Error: The square root of the Mean Squared Error. This metric indicates the average model's predictions for ZEV sales are off by approximately 189 vehicles. This is much higher than MAE, further indicating larger errors in the model prediction.
