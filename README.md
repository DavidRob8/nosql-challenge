Dependencies: 
from pymongo import MongoClient
import pandas as pd
from pprint import pprint

There were three parts to this module challenge:
Part 1: Database and Jupyter Notebook Set Up
  - Import Json file using MongoImport from the terminal
  - Use collection "establishments" from "uk_food" database

Part 2: Update the Database
  - Add "Penang Flavours" restaurant data as a new document in the "establishments" collection
  - Add a "BusinessID" for "Penang Flavours"
  - Remove establishments within the Dover Local Authority
  - Convert data types of some of the number values
    
Part 3:Exploratory Analysis
  - Display number of documents, pretty print the first document, and convert to Pandas DataFrame for each of the following questions:
    1) Which establishments have a hygiene score equal to 20?
    2) Which establishments in London have a RatingValue greater than or equal to 4?
    3) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    4) How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
       
Code Source:

I received assistance from a Tutor in Part 3 of the module.
