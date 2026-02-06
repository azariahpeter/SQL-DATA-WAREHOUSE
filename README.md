# SQL-DATA-WAREHOUSE
Creating a data warehouse with SQL server, including ETL server and data modelling
--------------------------------------------------------------------------------------------------------------------------
There are three layers to this Data Warehouse
-Bronze
-Silver
-Gold
--------------------------------------------------------------------------------------------------------------------------

FUNCTIONS OF EACH LAYER:
- Bronze - In this layer we are only concerned with creating the DDL scripts for the Bronze layer and ensuring correct transfer of data from the csv file to the SQL server
- Silver - This layer deals with data cleansing techniques such as normalisation, handling missing values, removing duplicates etc
- Gold - Here, we concern ourselves with creating a data schema(This project uses the star schema), and creating views which connect all the tables to each other. 
