# Data-Immersion-Wrangling

🎯 Objective

The objective of this phase is to clean, standardize, and prepare a raw sales dataset for accurate analysis and business decision-making.

Raw datasets often contain missing values, incorrect data types, duplicates, and inconsistent formats.

This step ensures that the data is reliable, structured, and analysis-ready before performing any exploratory analysis or hypothesis testing.



📌 Folder Description
data/

Contains both the raw dataset and the final cleaned dataset.

scripts/

Contains the Jupyter Notebook used to clean, transform, and validate the dataset.

data_dictionary.md

Describes each column, its data type, and its business meaning.

README.md

Explains the purpose, tools, and outcomes of this project.



🛠️ Tools & Technologies Used

Python – Core programming language for data manipulation

Pandas – Data cleaning, transformation, and validation

Jupyter Notebook – Interactive environment for step-by-step execution and documentation



🔄 Data Cleaning Process

The following steps were performed to ensure data quality and consistency:

1️⃣ Data Loading

Imported the raw sales dataset using Pandas
Verified column names and structure

2️⃣ Data Type Conversion

Converted columns into appropriate data types for analysis:
Date column → DateTime format
Price and weight → Numeric format

3️⃣ Handling Missing Values

Identified missing values
Removed or handled them based on business relevance

4️⃣ Duplicate Removal

Checked for duplicate records
Removed duplicates to avoid incorrect aggregation

5️⃣ Data Validation

Verified cleaned dataset shape
Ensured no null values remained
Confirmed correct data types

