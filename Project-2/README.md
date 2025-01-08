This project implements an ETL (Extract, Transform, Load) pipeline to acquire and process data from the "List of Largest Banks" URL. 
The extracted data, initially in USD (billion), is transformed by applying exchange rate conversion to EUR, INR, and GBP using a predefined exchange rate CSV and corresponding columns were created. 
The transformed data is then loaded into a CSV file.
Additionally, a SQLite database is created to store the table containing the attributes and content of the CSV file. 
A logging function is implemented to capture all activities within the ETL process. 
Key libraries used include BeautifulSoup and requests for web scraping, datetime for logging timestamps, sqlite3 for database interactions, Pandas and Numpy for data manipulation and numerical interactions respectively.
