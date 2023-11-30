# Louisville Metro Crime Data Analysis

by Tyriesha Doyle 

### Overview
This data anaysis is a mock project. Over the last couple of year the Louiville, KY area has a experienced a rise in the crime rate. The Louiville metro Police Department has implemented a task force to think of way to improve the problem. My task is to perform a data anaysis so that can have a better understand of the crime data collected over the years. This project explores the data collect from the Louisville Metro Police Department over the years 2020, 2021, 2022. 

This project utilizes three CSV flies from the Louisville Metro Open Data website. https://data.louisvilleky.gov 
Noted That the year is based on the date that the crime was reported and not the date it occured.The Raw_Data folder contains the CSV fls as originally download. The new_data folder contains CSV flies after the data cleaning process.

### Primary Files
1. data_Analysis: In this file the CSV flies are read in to python using pandas. Pandas is also use the drop and rename columns. SQL is use to join the CSV files together and query the data. 

2. data_Dictionary: This dictionary is only contain the columns used after the data cleaning process. 

3. data_Vizualization: In this file matplotlib was used to create charts that show the finding in the data analysis.

### Virutal enviroment/Instrution
1. Clone repo to your machine. Then change into the project folder in GitBash/Terminal.
2. Create a virtual enviroment. 
    - python3 -m venv venv 
3. Activate the virtual enviroment.
    - Linux/Mac - source venv/bin/activate   - GitBash - source venv/Scripts/activate  
4.Install the requirment packages.
    - pip istall -r requirement.txt
5. Deactivate the virtual enviroment when you are done with repo.
    - deactivate 

### Features
1. Loading Data - Reading in a CSV file 
2. Cleaning Data - Droping columns, renamed columns, and merging dataset together 
3. Visualize Data - Made 3 different visualizations on the data 
4. Best Practices - Included instructions on virtual environment setup, built a custom data dictionary 
5. Interpretation - Included a final anaylsis in the data_visalization file
