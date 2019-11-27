# Data-Mgmt-Project
##### Link to Slide Deck for Presentation: https://docs.google.com/presentation/d/1vByxupPbw71KWEbYRZtFBpxnVZsEWIN_vJ5G1plcRL8/

### How to Replicate Analysis: 
All Python Notebooks used to generate insights are located in the "Cleaned Data and Source Code" folder. Other files used in generating inights include the Databricks Archive used in EDA and to gain some peliminary insights into the data. The file structure is detailed below to facilitate navigation. 

### File Structure: 
#### - Cleaned Data and Source Code
  - Visualizations folder includes pictures of graphs (.png & .jpg) and python outputs
  - Main folder includes copies of all the "clean" csv's generated from the full data
  - SQL_queries.dbc
      - Databricks Archive file with SQL queries on data
  - Yearly and Monthly Population Estimates for the City of Austin 
      - AustinMonthlyPop.csv
      - AustinPop.csv
  - Time_period_and_demo_segments.ipynb
      - Python notebook with analysis on time periods and demographics of incidents
  - demo_output.csv, demographic.csv, demooutput2.csv
      - output csv file from Time_period_and_demo_segments Python notebook
  - driving_alcohol_result.ipynb
      - Python notebook to investigate ridesharing's effect on Drunk Driving incidents in Austin
  - drunk driving analysis and regression.ipynb
      - Python notebook used in investigation of ridesharing & Drunk Driving incidents
  - location_analysis.ipynb
      - location analysis for heatmap
#### - TXDOT Traffic Incident Data
  - Original Data from the Texas Department of Transportation
  - "publicextractfilespecification" provides documentation regarding column names and categorical variable definitions
  - Files were downloaded from TXDot in one-year increments using the CRIS Query tool 
  - Within each file for one year of crash data there are the following files: 
      - charges
      - crash
      - damages
      - endorsements
      - lookup
      - person
      - primary person
      - restrictions
      - unit
      - manifest (XML)
  - Charges.ipynb
      - creates "charges.csv" and "charges_clean.csv" 
         - charges.csv is the compiled 10 years of "charges" files
         - charges_clean.csv is reduced columns to those used in analysis
  - crash.ipynb
      - creates "crash.csv" and "crash_clean.csv" 
         - crash.csv is the compiled 10 years of "charges" files
         - crash.csv is reduced columns to those used in analysis
  - damages.ipynb
      - creates "damages.csv" 
         - damages.csv is the compiled 10 years of "charges" files, reduced columns to those used
  - person.ipynb
      - creates "person.csv" 
         - primary_person.csv is the compiled 10 years of "charges" files
  - primary_person.ipynb
      - creates "primary_person.csv" and "primary_person_clean.csv" 
         - primary_person.csv is the compiled 10 years of "charges" files
         - primary_person_clean.csv is reduced columns to those used in analysis
  - unit.ipynb
      - creates "unit.csv" and "unit_clean.csv" 
         - unit.csv is the compiled 10 years of "charges" files
         - unit_clean.csv is the compiled 10 years of "charges" files, reduced columns to those used
