# Midterm Project
This is my ds2002 midterm project. This document explains background of the ETL process shown. The project uses the Sakila database to practice the ETL process. I use SQL methods to extract the date dimension. I use MongoDB to extract the customer dimension. I use a file system to extract the staff dimension. Then several transformations are done using python and Pandas dataframes. These dimensions are then uploaded to an SQL datamart named Sakila_dw. 

A fact table is then created by combining the rental and payments table. This table contains columns that each point to the primary key of the respective dimension tables. The business problem is looking at purchasing. For example the example statement at the bottom looks at rental information by staff member.
