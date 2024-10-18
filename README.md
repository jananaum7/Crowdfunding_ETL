# Crowdfunding_ETL

## Table of Contents
- [Introduction]
- [ERD]
- [Installation]
- [Usage]
- [Contributers]

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
To use this ETL project, start by ensuring you have Python installed, along with the necessary libraries. Install the required dependencies, including pandas for data manipulation and openpyxl for handling Excel files, using the following command: pip install pandas openpyxl. Next, ensure all datasets (campaign.csv, category.csv, subcategory.csv, crowdfunding.xlsx, and optionally contacts.csv) are placed in the same directory as the Jupyter notebook, or modify the file paths in the code accordingly.  Once your environment is set up, open the Jupyter notebook by running jupyter notebook in your terminal and navigate to the notebook file (ETL_Mini_Project.ipynb). Execute the cells in the notebook sequentially to walk through the ETL process. The notebook will extract data from the CSV and Excel files, clean and transform the data to ensure consistency, and finally load the cleaned data into a structured format for analysis. After the notebook finishes running, you can inspect the processed data, which will be saved as a new CSV or Excel file, ready for further analysis or visualization.  This process allows you to integrate and transform crowdfunding data, making it easy to analyze and draw insights from.

## Contributers
- M. Sahane
- E. Garcia
- J. Naum









