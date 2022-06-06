# Movies-ETL
Module 8

## Overview of the Project
This project is to prepare data for our hack-a-thon. We will be pulling three different sources of data
in three differing formats. Analyze the data in each file, clean up the data in each. Remove duplicates if
necessary and merge the data into one single SQL database.

## Results
Taking in data from differing sources produced three files that we needed to extract data and clean.
Some of the challenges we faced were:
	- similar data type with differing formats
	- missing data
	- duplicate data
	- unformatted date/time data
	- irrelevant data
	
As a result, our plan was to:
	- reformat data types into one readable format.
	- fill in missing data with zeroes or delete records with missing data
	- reconcile duplicate data into one column
	- uniform format for date/time
	- delete irrelavent data.
	
Cleaning process took several rounds of inspecting the data from each source until the data
was uniform and correct. Then we merged the data from all three sources into one database where 
the data can be easily queried.