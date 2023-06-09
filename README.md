## Project Overview: 

I acted as a contractor of a food magazine, Eat Safe, Love, to evaluate some of the ratings data provided by the UK Food Standards Agency. The goal was to help their journalists and food critics decide where to focus future articles.

### Technologies and Methods: 

I used PyMongo to interact with the MongoDB database and Pretty Print (pprint) to display the data in a readable format. I also used Pandas to convert query results to DataFrames.

I started by importing the data provided in the establishments.json file to a MongoDB database named uk_food and a collection named establishments. I confirmed that the database and data were loaded correctly by listing the databases and collections in MongoDB, finding and displaying one document using find_one and pprint, and assigning the establishments collection to a variable.

Next, I made the requested modifications to the establishments collection using update_one, update_many, and delete_many. I added information for a new halal restaurant in Greenwich, found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen", removed establishments within the Dover Local Authority, and converted latitude and longitude to decimal numbers.

Finally, I explored the dataset and answered specific questions for Eat Safe, Love using count_documents, find, regex, and aggregation pipelines. 

Author: Lacey Morgan






