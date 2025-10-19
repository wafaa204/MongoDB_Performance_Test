This project declare using MongoDB to see thier performance .
You will to install the MongoDB using this command !pip install pymongo ,import random lib , time lib , string lib.
So ,First we will import MongoClient from pymongo that help use to connect with local database ,
Second we will create a database that named as 'test' then we will create a collection that named as 'test_data' ,
Third we delete the whole previous data to ensure that the database empty .
Now create function for generate documents .. we generate 10000 document then use the time lib to know how much takes for generating 10000 document .

We are using Jupyter Notebook for testing and training thhe code .
