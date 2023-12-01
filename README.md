# NoSQL_Challenge

# The Challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# The Process

In this project, the analysis began with the setup of a MongoDB database named uk_food and a collection named establishments, importing data from the provided establishments.json file. The database was verified, and a sample document was displayed to ensure successful data import. The subsequent section focused on updating the database, adding a new halal restaurant, updating its information, removing establishments in Dover, and converting relevant data types. The exploratory analysis consisted of addressing specific questions using MongoDB queries. Notably, establishments with a hygiene score of 20 and those in London with a RatingValue of 4 or higher were identified and presented in Pandas DataFrames. Additionally, the top 5 establishments with a RatingValue of 5, sorted by hygiene score and proximity to "Penang Flavours," were determined. The final question involved an aggregation pipeline to count establishments with a hygiene score of 0 in each Local Authority, with results displayed in a Pandas DataFrame. Throughout the analysis, the code demonstrated effective data manipulation, adherence to instructions, and clear presentation of results using MongoDB and Python.


# What’s included?
Within this repo you will find in the Starter_Files folder my two Jupyter Notebook codes named NoSQL_setup_starter.ipynb, NoSQL_analysis_starter.ipynb as well as my resources folder. Within the Resources folder you will find the establishments.json file.

# Sources
For this challenge I utilized ChatGPT, fellow students, Jupyter Notebook, MongoDBCompass, Google/Google Chrome, Stack Overflow, and Class recordings.
