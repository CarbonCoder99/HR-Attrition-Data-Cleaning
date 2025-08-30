# HR Employee Attrition Data Cleaning Project

## Overview
This repository contains a comprehensive data cleaning and preprocessing project on a dataset of HR employee attrition. The primary goal was to transform the raw data into a clean, structured format suitable for analysis to identify potential factors contributing to employee attrition.

## Dataset
 The project utilizes the `HR-Employee-Attrition.csv` dataset.  The cleaned version of the dataset is available as `HR-Employee-Attrition-Cleaned.csv`.

## Data Cleaning Process
The data cleaning and preprocessing workflow is detailed step-by-step in the `Notebook.ipynb` file. Key cleaning steps performed include:
*  Converting the `Attrition` column from a string (`Yes`/`No`) to a boolean (`True`/`False`).
*  Standardizing the format of the `BusinessTravel` column from `Travel_Rarely` to `travel rarely`.
*  Selecting a subset of relevant columns for the final cleaned dataset, such as `age`, `job_role`, and `years_at_company`.
* Handling missing values and ensuring consistent data types.

## Repository Contents
* `RawData/`: Contains the original raw dataset .
* `ProcessedData/`: Contains the cleaned dataset .
* `notebook/`: Contains the Jupyter Notebook that details the data cleaning process.

## How to Use
1.  Clone this repository to your local machine.
2.  Navigate to the `notebook/` directory and open `Notebook.ipynb` to view the full data cleaning process.

3.  The `data/processed/` directory contains the final cleaned dataset, `HR-Employee-Attrition-Cleaned.csv`, ready for use in any data analysis or visualization project.
