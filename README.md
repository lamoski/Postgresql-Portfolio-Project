# SQL-Project 1

This project was executed using PostgreSQL, it includes 
the use of a housing data table. The purpose of the project is to 
clean the details of the housing data and to improve my data querying skills 
in PostgreSQL.




## Lessons Learned


This project made me understand how to implement my PostgreSQL query skills into a real life 
project and the steps of cleaning the data was:
- Removing the time from the salesprice(timestamp) column.
- Populating propertyaddress column where the address is NULL using ParcelID as reference.
- Splitting Propertaddress into Address and City column.
- Splitting Owneraddress into Address, City and State.
- Changing the Soldasvacant column to be Boolean using Yes and No Boolean.
- Deleting the duplicate rows.
