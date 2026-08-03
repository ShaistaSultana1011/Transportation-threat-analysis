TRANSPORTATION THREAT ANALYSIS


DATASET OVERVIEW:

This project uses a Road Traffic Accident Dataset containing records of traffic accidents along with information about drivers, vehicles, road conditions, environmental factors, and casualties. It is used to analyze accident patterns, identify contributing factors, and support data-driven road safety insights. 

Key features include:

Driver information (age band, sex, educational level, driving experience)

Vehicle details (type, ownership, service year, defect of vehicle)

Road information (road surface type, road surface condition, junction type, area, lanes)

Environmental conditions (weather, light conditions)

Casualty information (casualty class, severity, work of casualty)

Accident-related details (number of vehicles, number of casualties, cause of accident)


DATA CLEANING:

1.Checking duplicates

<img width="399" height="75" alt="Screenshot 2026-08-03 003316" src="https://github.com/user-attachments/assets/a6733578-431b-4269-aa39-7190375dd752" />


2.Handled missing vakues


Categorical columns (Age_band_of_driver, Sex_of_driver, Educational_level, Vehicle_driver_relation, Driving_experience, Type_of_vehicle, Owner_of_vehicle, Service_year_of_vehicle, Defect_of_vehicle, Area_accident_occured, Lanes_or_Medians, Road_allignment, Types_of_Junction, Road_surface_type, Road_surface_conditions, Light_conditions, Weather_conditions, Type_of_collision, Vehicle_movement, Cause_of_accident) → Replaced missing values with "Unknown".


 Owner_of_vehicle, Fitness_of_casualty, and Casualty_severity  → Filled misiing values using the mode.


Conditional Imputation → Defect_of_vehicle filled using Service_year_of_vehicle values

<img width="384" height="617" alt="Screenshot 2026-08-03 003353" src="https://github.com/user-attachments/assets/b43c9021-e9a1-4ba3-a341-2057e27d1648" />


<img width="333" height="609" alt="Screenshot 2026-08-03 004637" src="https://github.com/user-attachments/assets/cddd4eca-c6cf-48b5-8664-dc4c7df5a06d" />











