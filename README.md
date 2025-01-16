# Crowdfunding_ETL

## Table of Contents
- [Introduction](#introduction)
- [ERD](#erd)
- [Installation](#installation)
- [Usage](#usage)
- [Contributers](#contributers)

## Introduction
In this project, my team and I developed an ETL (Extract, Transform, Load) pipeline to process and analyze crowdfunding data from multiple sources. Using Python, we collaboratively extracted data from CSV and Excel files containing information about crowdfunding campaigns, categories, subcategories, and contacts. We transformed the data by cleaning, standardizing, and merging datasets while addressing missing values. This ensured consistency and improved data quality for subsequent analysis. Finally, we loaded the transformed data into a structured format, making it ready for further analysis and insights. This project highlights our collective ability to build an ETL pipeline, manage data from various sources, and prepare it for meaningful analysis.

## ERD
![image](https://github.com/user-attachments/assets/b8474333-ece9-4da4-9e3e-fcd44ba4702f) 

My team and I utilized QuickDB to design a relational database tailored for storing and managing crowdfunding data. The schema consists of four primary tables: `contacts`, `campaign`, `category`, and `subcategory`. Each campaign is associated with its organizer (contacts) and categorized into distinct categories and subcategories. This structured approach ensures efficient data organization and facilitates seamless retrieval for analysis.

## Installation
- pandas: Essential for reading, cleaning, transforming, and saving data from CSV and Excel files.
- matplotlib: Used for creating data visualizations, helpful for analyzing data during the ETL process.
- openpyxl: Required for reading and writing Excel (.xlsx) files.
- jupyter notebook: Provides an interactive environment to run the ETL process step-by-step in a notebook.
- numpy: Supports Pandas with numerical operations and handling missing data, used behind the scenes for efficient data 
  processing.

## Usage
Environment Setup:
- Ensure you have Python installed.
- Install the required libraries:
```bash
pip install pandas
pip install openpyxl
```
Prepare Datasets:
- Place the following datasets in the same directory as your Jupyter notebook:

    -> campaign.csv
  
    -> category.csv
  
    -> subcategory.csv
  
    -> crowdfunding.xlsx
  
    -> contacts.csv
  
- Alternatively, modify the file paths in the code accordingly.
Start Jupyter Notebook by running:
```bash
jupyter notebook
```
- Or in our case, we opened it with Visuual Studio Code.
- Navigate to ETL_Mini_Project.ipynb and execute the cells sequentially.
ETL Process:
The notebook will extract data from the CSV and Excel files, clean and transform the data for consistency, and load the cleaned data into a structured format.
After running the notebook, inspect the processed data, which will be saved as a new CSV or Excel file for further analysis or visualization.

## Contributers
- M. Sahane
- E. Garcia
- J. Naum









