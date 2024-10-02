# BernabeuBuzz
A website designed using python, streamlit, RestApi, Pyspark and PostgresDB functionalities

Real Madrid Fan Page with Streamlit
We want to build a Real Madrid fan webpage using Python. Here's a breakdown of the functionalities:

Data Acquisition:

Source: Football-api.org (we'll use this website to collect data)
Data Processing:
Use Python with requests library to call the Football-api.org endpoints for Real Madrid data.
Consider using a library like pyfootball (a wrapper for the API) to simplify interaction.
We'll likely need Spark (a big data processing framework) if the data volume is significant.
Storage:
Load the processed data into a PostgreSQL database for efficient storage and retrieval.
Webpage Creation:

Framework: Streamlit (a Python library for creating interactive web apps)
Layout:
Implement a vertical navigation bar on the left side.
Each navigation bar item will link to a separate page within the Streamlit app.
Content:
Club Details: Static information about Real Madrid (e.g., history, stadium, trophies).
News: Fetch and display latest news articles related to Real Madrid.
Fixtures: Allow users to select a season and display upcoming or past fixtures.
Stats: Display various statistics (e.g., goals scored, player rankings) based on user-selected season.
Players: Show a list of players with options to filter by season.
Club History: Provide historical information about the club (e.g., past managers, significant events).
Transfers: Display transfer information (incoming and outgoing players) with season selection.
Key Points:

The webpage will be interactive, allowing users to choose specific seasons for most sections.
We'll leverage Python libraries like requests, pyfootball (optional), psycopg2 (for PostgreSQL), and Streamlit.
