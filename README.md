# Non-Intrusive Chiller Load Monitoring Using XGBoost and Weather Data

This project implements a virtual sensor for monitoring a university building chiller using aggregate building energy consumption and meteorological context.

The work is based on a real Building Energy Management System dataset from the Faculty of Building Services building at the Technical University of Cluj-Napoca.

## Main idea

Physical sub-meters can fail silently. This project uses machine learning to estimate the chiller consumption from the main building meter and weather data.

## Methods used

- Contextual data cleaning
- Frozen sensor detection
- Isolation Forest anomaly detection
- PELT change-point detection
- SAX symbolic analysis
- XGBoost regression
- ON/OFF chiller state detection
- Carbon-aware analysis

## Results

- R2 = 0.939
- MAE = 0.040 kW
- F1 = 0.937
- AUC = 0.999

## Repository structure

paper/      - research paper PDF  
notebooks/  - main analysis notebook  
src/        - future Python scripts  
figures/    - exported plots and figures  

## Security note

API keys and raw private datasets are not included in this repository.
Use .env.example as a template and create a local .env file if needed.
