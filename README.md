# my_sql_create_tables

1. Write an SQL statement to create a simple country table with the columns country_id, country_name and region_id.

   CREATE TABLE country( 
COUNTRY_ID varchar(2),
COUNTRY_NAME varchar(40),
REGION_ID decimal(10,0)
);

3. Write an SQL statement to create a simple country table with the country_id, country_name and region_id columns that already exist.

   CREATE TABLE IF NOT EXISTS countries ( 
COUNTRY_ID varchar(2),
COUNTRY_NAME varchar(40),
REGION_ID decimal(10,0)
);

