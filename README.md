# Nashville_Housing
The Nashville Housing dataset contains information about housing sales in Nashville, TN such as property address, property type, sale price, acreage, number of bedrooms, number of bathrooms etc.

This repository contains 2 files - Data Cleaning and Data Analysis.

# Data Cleaning:
This file consists of SQL queries executed on PostgreSQL which solve problems in the dataset mentioned below:
1. Check "PropertyAddress" column for NULL Values ant then populate and update the table.
2. Breaking addresses into individual columns (Address, City, State) and updating the table.
3. Check "SoldAsVacant" column and change "N" to "NO", and "Y" to "YES".
4. Remove and delete unused columns.

# Data Analysis:
This file consists of SQL queries executed on PostgreSQL analyzing the updated dataset after the Data Cleaning Process.
