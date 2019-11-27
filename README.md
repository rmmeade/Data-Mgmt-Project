# Data-Mgmt-Project

### File Structure: 
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
  - primary_person.ipynb
      - creates "primary_person.csv" and "primary_person_clean.csv" 
         - primary_person.csv is the compiled 10 years of "charges" files
         - primary_person_clean.csv is reduced columns to those used in analysis
  - unit.ipynb
      - creates "unit.csv" and "unit_clean.csv" 
         - unit.csv is the compiled 10 years of "charges" files
         - unit_clean.csv is the compiled 10 years of "charges" files, reduced columns to those used
#### - Cleaned Data
  - \_cleaned.csv
  - \_cleaned.csv
      - Reduced columns 
