To create a Streamlit application for accessing and analyzing data from multiple YouTube channels. Features include:

Input a YouTube channel ID to retrieve data (Channel name, subscribers, video count, playlist ID, video ID, likes, dislikes, comments).
Store data in MongoDB as a data lake.
Collect data for up to 10 channels and store it in the data lake.
Migrate selected channel data from the data lake to a SQL database as tables.
Search and retrieve data from the SQL database with various search options, including table joins for channel details.
Approach:

Set up a Streamlit app to create a user-friendly interface.
Connect to the YouTube API using the Google API client library for Python.
Store data in MongoDB for its flexibility with unstructured data.
Migrate collected data to a SQL data warehouse (MySQL/PostgreSQL).
Query the SQL data warehouse using SQLAlchemy for interaction.
Display data in the Streamlit app with data visualization capabilities for analysis.
In summary, this approach involves UI development with Streamlit, YouTube API data retrieval, MongoDB data lake storage, SQL data warehouse migration, SQL querying, and data display in the Streamlit app.
