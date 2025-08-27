# Restaurant_review_dataset_cleaning
This project involved comprehensive preprocessing of a restaurant review dataset characterized by missing values, inconsistent data types, duplicates, and multi-valued fields. The raw data was systematically cleaned through data imputation, normalization, deduplication, and parsing techniques to ensure structural consistency and data integrity. After rigorous validation, the processed dataset was loaded into a MySQL relational database, establishing a robust infrastructure for efficient querying and advanced analytical workflows. This foundation will enable accurate in-depth data analysis, support actionable, data-driven insights to enhance decision-making within the restaurant industry.

## Objective:
To leverage data cleaning, preprocessing, and database management skills to transform raw datasets into accurate, consistent, and analysis-ready resources. Aim to enable insightful, data-driven decision-making by establishing robust data infrastructure and delivering high-quality, reliable datasets

This project uses the dataset from Kaggle: Zomato_EDA (https://www.kaggle.com/datasets/pranavuikey/zomato-eda/data)

## Key Features
- Jupyer Notebook - Python
- MySQL Database

### Database
[View Database](https://github.com/BOAMAH-99/Restaurant_review_analysis/tree/main/Database)

### Tools and Skills Used
- MySQL Client and MySQL Workbench
- Database Schema Design
-	Data Integrity
-	Querying and Data Manipulation
-	Python (sqlalchemy, pandas, missingno, matplotlib, seaborn)

## End to End Data Cleaning and Preparation
- Defined clear project goals and success criteria to ensure data quality and readiness for analysis
- Conducted a thorough review of raw datasets to understand their structure, completeness, and consistency
- Standardized the dataset by normalizing column names, fixing date formats, and enforcing consistent data types
- Handled missing data using targeted imputation where possible and excluded records that could not be reliably recovered
- Removed duplicate records and ensured entity consistency using rule-based matching and deduplication
- Cleaned text fields by trimming whitespace, standardizing casing, and removing unwanted characters
- Identified and addressed outliers using statistical methods and domain knowledge to improve analysis accuracy
- Engineered new features including time-based variables and aggregated metrics to enhance data understanding and management
- Split and restructured multi-value fields into usable formats while maintaining relational integrity using indexing
- Validated the final dataset through summary statistics and spot checks, delivering comprehensive documentation for easy handoff
- Restructured and exploded multi-value columns: Dish_liked, Rest_type and Cuisines, into usable formats while maintaining relationships with primary table utilizing pandas index as primary key
- Validated the final dataset with reproducible summary statistics and spot checks to ensure accuracy, consistency, and readiness for analysis or database integration

### This project successfully designed and implemented a relational database with well-defined primary and foreign keys to ensure data integrity. The schema efficiently organizes data with enforced relationships, supporting reliable and scalable data management.
