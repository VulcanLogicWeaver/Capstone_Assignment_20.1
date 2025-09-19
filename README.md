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

# Visualization
Based on the plot of vehicle sales of ICE (Internal combustion Engine) vs. ZEV (Zero Emission Vehicles), seems like ZEV have a long way to go. We need approximately 3x - 4x the sales of current ZEV sold to just to catchup and meet the current demands.
<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/18025902-8ec7-4df7-8da8-7fb4e93c8de3" />

As expected, this clearly indicates the most popular vehicle type in the ZEV category is Fully Electric vehicles. The second best
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/453299c6-2638-46f0-80ee-9b421e478116" />

Again, clearly not a surprse the most popular vehicle sold (in-fact the top 3) are Tesla. Infact the top 2 are close to 5 times the sales of any other vehicle type sold.
<img width="1389" height="690" alt="image" src="https://github.com/user-attachments/assets/f7bec567-9e7d-4432-a6f5-e3ae99a6611b" />

# Interpretation of evaluation metrics
R-squared: Represents the variance in the dependent variable (ZEV Sales) that is predictable from the independent variable (Data Year). The low value in this case indicates that 'Year' alone is not a good fit and is a poor predictor of ZEV sales.

Mean Absolute Error: The average of the absolute differences between the actual and predicted values. This simple metric indicates the average model's predictions for ZEV sales are off by approximately 49 vehicles.

Mean Squared Error: The average of the squared differences between the actual and predicted values. The high values indicates larger prediction errors, as this model penalizes larger more heavely as the errors are squared.

Root Mean Squared Error: The square root of the Mean Squared Error. This metric indicates the average model's predictions for ZEV sales are off by approximately 189 vehicles. This is much higher than MAE, further indicating larger errors in the model prediction.
