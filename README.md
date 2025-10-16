# ResultExtractor
This Python script is an automated web scraper designed to fetch the H.S.C. exam results for a specific list of students from the Dinajpur Education Board (result.dinajpurboard.gov.bd)'s result portal. It extracts detailed information for each student, including their personal details, GPA, and a full list of subject-wise marks. The data is then stored in a local SQlite database aka "dinajpur_board_results.db".

# Dependencies (Automatically downloaded when the script is executed)
-Python3: The script is written using Python3. You need it installed on your system and on PATH.
-requests: To send HTTP requests to the website and download the result pages.
-BeautifulSoup (from bs4): The primary library for parsing HTML documents and making them easy to search and navigate.
-lxml: A high-performance parser that BeautifulSoup uses under the hood to process the HTML content quickly and reliably.
-sqlite3: A built-in Python library for creating and interacting with the SQLite database file.
-pandas: Used at the end to display the data from the database in a clean, user-friendly table format.

Use beiow command to install all the requirements after Python is installed
>pip install requests beautifulsoup4 lxml pandas
