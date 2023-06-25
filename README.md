# nosql-challenge

## Description
_Module 12 Challenge - University of Adelaide - Data Analytics BootCamp_

Welcome to my analysis of establishments across the United Kingdom. This analysis will be used by the editors of Eat Safe, Love magazie to evaluate some of the ata to assit journalists and food ciritics decide where to focus future articles. 

The analysis was performed using the following Jupyter Notebooks.

The data is provided in the [..//Resources/establishments.json](establishments.json) file under resources.  This is first imported using Terminal with _mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json_

Part 1 - [NoSQL_setup_starter.ipynb](NoSQL_Start.ipynb) . Sets up and updates the database.

Part 2 - [NoSQL_analysis_starter.ipynb](NoSQL_analysis_starter.ipynb). Queries the relevant information to provide the analyses and converts the results into Pandas DataFrames for further analysis as required.

## How to Install and Run the Project

Please clone the repository to your local drive. Once cloned, please import the data as per the above code line (_mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json_). Then run Part 1 to setup the databse and then Part 2 to run the queries to assist with analysing the data. Part 1 and 2 are run via Jupyter Notebook.

## How to Use the Project

This project can be used to find some information about establishments across the United Kingdom.

## Credits

Code used was drawn from in class and google searches to find why code wasn't working.
The coding followed similar to in class activities.
https://www.geeksforgeeks.org/python-mongodb-update_one/
https://stackoverflow.com/questions/15171622/mongoimport-of-json-file
