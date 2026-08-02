DATASET OVERVIEW:

This project uses a Road Traffic Accident Dataset containing records of traffic accidents along with information about drivers, vehicles, road conditions, environmental factors, and casualties. The dataset is intended for exploratory data analysis (EDA) to identify accident patterns, contributing factors, and trends.

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

.

Handled Missing Values

Categorical columns (Age_band_of_driver, Sex_of_driver, Educational_level, Vehicle_driver_relation, Driving_experience, Type_of_vehicle, Owner_of_vehicle, Service_year_of_vehicle, Defect_of_vehicle, Area_accident_occured, Lanes_or_Medians, Road_allignment, Types_of_Junction, Road_surface_type, Road_surface_conditions, Light_conditions, Weather_conditions, Type_of_collision, Vehicle_movement, Cause_of_accident) → Replaced missing values with "Unknown".


 Owner_of_vehicle, Fitness_of_casualty, and Casualty_severity  → Filled misiing values using the mode.


Conditional Imputation → Defect_of_vehicle filled using Service_year_of_vehicle values

<img width="384" height="617" alt="Screenshot 2026-08-03 003353" src="https://github.com/user-attachments/assets/b43c9021-e9a1-4ba3-a341-2057e27d1648" />


<img width="781" height="398" alt="Screenshot 2026-08-03 003414" src="https://github.com/user-attachments/assets/e6878162-6bcc-41c8-8858-7af05a4ff766" />


<img width="627" height="242" alt="Screenshot 2026-08-03 003451" src="https://github.com/user-attachments/assets/252c38e5-451b-4e8c-a936-f83063c706a7" />


<img width="640" height="87" alt="Screenshot 2026-08-03 003506" src="https://github.com/user-attachments/assets/7d960831-2468-4b23-8d41-b609680bdefb" />


<img width="1114" height="520" alt="Screenshot 2026-08-03 003538" src="https://github.com/user-attachments/assets/6ebef60f-d309-450f-bc1b-e0da058c3cdd" />

<img width="530" height="198" alt="Screenshot 2026-08-03 003526" src="https://github.com/user-attachments/assets/23379cff-8a24-492d-90b1-e547d11eeae6" />


<img width="333" height="609" alt="Screenshot 2026-08-03 004637" src="https://github.com/user-attachments/assets/cddd4eca-c6cf-48b5-8664-dc4c7df5a06d" />











