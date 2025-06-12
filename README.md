# STAT 31613-Group 04
Predicting Used Car Prices Using Multiple Regression Analysis: A Study on Automotive Features and Ownership History

Overview
  This dataset contains 10,000 realistic entries of used cars with various features such as mileage, engine size, number of previous owners, fuel type, and more. 


Target Variable
  price_usd – the car's selling price (continuous variable).

Feature Classification
*Numerical Features
  make_year         :Year the car was manufactured (between 1995 and 2023).
  mileage_kmpl      :Mileage of the car in kilometers per liter (kmpl).
  engine_cc         :Engine capacity in cubic centimeters (e.g., 1200 cc, 2000 cc).
  owner_count       :Number of previous owners (1 to 5).
  accidents_reported:Number of accidents reported for the vehicle (typically 0–5).

*Categorical Features
  fuel_type (e.g., Petrol, Diesel)  :Type of fuel used: Petrol, Diesel, or Electric.
  brand (e.g., Honda, BMW)          :Car brand name
  transmission (Manual, Automatic)  :Type of transmission: Manual or Automatic.
  color (e.g., White, Black)        :Exterior color of the car.
  service_history (None, Full)      :Maintenance history: Full, Partial, or None.
  insurance_valid (Yes, No)         :Indicates whether insurance is currently valid: Yes or No.
