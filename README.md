

**YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit**

We're interested in building a project that involves harvesting and warehousing YouTube data using various technologies like Python, Google API client, Streamlit, MongoDB, and MySQL. 
This is a bit complex project, so I'll break down the steps you can follow to accomplish it.

**1. Set up Google API Access:**

Create a Google Cloud project and enable the YouTube Data API.
Obtain API credentials (API key or OAuth 2.0 credentials) for accessing the API.

**2. Python Script for Data Harvesting:**

Use the googleapiclient library in Python to interact with the YouTube Data API.
Write a Python script that uses the API to retrieve YouTube data, such as videos, channels, comments, etc.
Store the harvested data in memory or write it to files temporarily.

**3. Data Storage:**

Choose between MongoDB and MySQL for data warehousing, based on our project requirements.
Install the appropriate Python drivers (pymongo for MongoDB, mysql-connector-python for MySQL).
Design the data schema for our chosen database system and create the necessary tables or collections.

**4. Storing Data:**

Modify our Python script to insert the harvested data into the chosen database.
Ensure that the data is structured properly according to our database schema.

**5. Streamlit Web App:**

Install the Streamlit library using pip install streamlit.
Create a Streamlit web app that interacts with the stored YouTube data.
Use Streamlit's interface components to allow users to query and visualize the data.

**6. Data Retrieval in Streamlit:**

Implement functions in our Streamlit app that retrieve data from the database.
Display the retrieved data using Streamlit components such as tables, charts, and text.

**7. Enhancements:**

Implement search and filter functionality in our Streamlit app to allow users to find specific videos, channels, or comments.



**Features**

* Extracts information on a YouTube channel using the Google API

* Stores the extracted data in a MongoDB database

* Migrates the data from MongoDB to a SQL data warehouse

* Enables users to search for channel details

* Provides the ability to join tables and view data in the Streamlit app


**Visualize**

* Open the Streamlit application in your browser

* Enter the YouTube channel ID(s)

* Click on the "Search" button to extract information from the YouTube channel

* Click 'Upload to MongoDB' button to store the fetched data to MongoDB database

* Next from the multiselect dropdown select the channel(s) whose details you want to migrate to SQL DB

* Click 'Migrate to SQL DB' to migrate

* After migrating, you can select your desired query from the query dropdown

* Click the 'Get Report' button to get the result in the form of table




