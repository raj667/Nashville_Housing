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
1. Total count of properties sold in each city

![Total_count_of_properties_sold_in_each_city](https://github.com/raj667/Nashville_Housing/assets/30209480/8ade666b-fb45-47ab-8143-7147941cb14f)

2. Total count of different property types sold

![pgAdmin 4 11_5_2023 8_41_26 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/8b6a3166-f18f-414d-a0bd-d9b49588a6d6)

3. Count of property type sold most in each city

![pgAdmin 4 11_5_2023 8_44_38 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/70e670c6-5cbf-4499-b7b2-fee3ec7df4d4)

4. Average sale price of property in each city

![pgAdmin 4 11_5_2023 8_46_21 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/814515d4-952c-4379-b077-0109445f5343)

5. Average saleprice of the most sold property type in each city

![pgAdmin 4 11_5_2023 8_47_47 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/f317bd3b-52e2-4aef-8938-bf6b7eac6ecb)

6. Count of 'SINGLE FAMILY' properties in the top 20% of Sale Price sold in each city

![pgAdmin 4 11_5_2023 8_50_38 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/2792b3c1-efcc-4ce6-936d-232d27011deb)

7. Count of 'SINGLE FAMILY' properties in the bottom 20% of Sale Price sold in each city

![pgAdmin 4 11_5_2023 8_52_29 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/444064d1-1585-460f-82ba-358fcc7ea310)

8. Average sale price of 'SINGLE FAMILY' properties in the top 20% of Sale Price sold in each city

![pgAdmin 4 11_5_2023 8_58_12 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/2792bc4e-877a-4efb-818f-a97c541a1b4e)

9. Average sale price of 'SINGLE FAMILY' properties in the bottom 20% of Sale Price sold in each city

![pgAdmin 4 11_5_2023 8_57_05 PM](https://github.com/raj667/Nashville_Housing/assets/30209480/9498e6d1-a75e-4648-9e38-381f1a0885a9)
