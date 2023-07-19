# UK Restaurants Analysis
## Module 12 Challenge (NoSQL)

On behalf of food magazine, *Eat Safe, Love*, data provided by the UK Food Standards Agency was evaluated in order to help their journalists and food critics decide where to focus future articles.</br>
</br>
In the **Eat_Safe_Love_analysis** folder you will find one code for setting up and updating our database, and another for analysis.

## Part 1: Establishing Database and Jupyter Notebook Set Up
Data from the establishments.json file located in the **Resources** folder was imported into the terminal.</br>
The database and collection were then given variables name, **uk_food** and **establishments**, respectively, to more easily inspect the data. 

## Part 2: Updating the Database
Data for a new restaurant called Penang Flowers was added to the collection.</br>
Any data from Dover was removed.</br>
Longitude and Latitude entries were converted from strings to Decimal types.

## Part 3: Exploratory Analysis
The following questions were answered through data analysis to provide to the magazine editors:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
