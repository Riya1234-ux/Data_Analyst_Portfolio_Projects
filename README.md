# 🧹 Data Cleaning Project using MySQL

This project focuses on cleaning raw and messy data using SQL queries in *MySQL*. The goal is to transform unstructured and inconsistent data into a clean and structured format that is ready for analysis or further processing.

## 📂 Project Overview

* *Dataset*: [Nashville Housing Dataset](https://github.com/Riya1234-ux/Data_CLeaning_Project/blob/main/Nashville%20Housing%20Data%20for%20Data%20Cleaning.csv)
* *Tools Used*: MySQL, SQL Queries, Joins, String Functions, Data Type Conversion, CTEs, Temp Tables
* *Key Tasks*:

  * Standardizing date formats
  * Populating missing data
  * Removing duplicates
  * Breaking down data into atomic units
  * Formatting and refining values

## 📌 Objectives

* Learn practical data cleaning techniques using SQL.
* Improve the quality and consistency of data.
* Prepare data for visualization or machine learning workflows.

## 🧰 Technologies Used

* *MySQL*: For writing and executing SQL queries.
* *DBMS Tools*: MySQL Workbench or any SQL editor.
* *CSV Data*: Imported and used for SQL operations.

## 📊 Dataset Description

The dataset contains property sales data from Nashville, Tennessee, including columns such as:

* Parcel ID
* Property Address
* Sale Date
* Sale Price
* Owner Name
* Legal Reference
* Sold As Vacant
* Year Built
* Property Land Use
* etc.

## 🔧 Data Cleaning Steps

1. *Standardizing Date Format*
   Convert SaleDate to DATE type for consistency.

2. *Populating Missing Property Address*
   Fill missing property addresses using data with the same ParcelID.

3. *Breaking Address into Components*
   Split PropertyAddress into Address, City.

4. *Breaking Owner Address*
   Use SUBSTRING_INDEX() to split into OwnerAddress, City, and State.

5. *Converting 'Y'/'N' to 'Yes'/'No'*
   Clean up the SoldAsVacant column for readability.

6. *Removing Duplicates*
   Identify and remove duplicate rows based on key columns.

7. *Dropping Unused Columns*
   Remove unnecessary columns to simplify the dataset.

## 📁 File Structure


📦Data_Cleaning_Project
 ┣ 📄 Nashville Housing Data for Data Cleaning.csv
 ┣ 📄 data_cleaning_queries.sql
 ┣ 📄 README.md


## 🚀 How to Use

1. Clone the repository:

   bash
   git clone https://github.com/Riya1234-ux/Data_CLeaning_Project.git
   

2. Import the CSV into MySQL.

3. Run the SQL queries in data_cleaning_queries.sql sequentially.

4. Verify the cleaned dataset using SELECT queries.

## 📝 Learnings

* Real-world data is messy and inconsistent.
* SQL is powerful for handling and transforming structured data.
* Data cleaning is an essential step before any meaningful analysis.

## 📌 Author

* 👩‍💻 Riya Paul
* 🔗 [GitHub Profile](https://github.com/Riya1234-ux)
