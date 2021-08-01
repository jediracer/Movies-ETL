# Movies-ETL

## Project Overview
Create a database for the Amazing Prime Hackathon.
	- Clean data from multiple sources
		- Wikipedia web scrap
		- Kaggle download
	- Merge data
	- Insert data into PostgreSQL database
	- Create a reusable process to update data in database
	
## Resources
- Data Sources: 
	- movies_metadata.csv
	- ratings.csv
	- wikipedia-movies.json
- Software: 
	- Python 3.8.8
	- Visual Studio Code 1.57.1
	- PostgreSQL 13 
	- pgAdmin4 v5.2

## Summary
- After the movie data was cleaned a total of 6,052 records were inserted into the 'movies' table.   
	- Movies
	![Movies](https://github.com/jediracer/Movies-ETL/blob/main/Resources/movies_query.png)
- After the movie ratings data was cleaned a total of 26,024,289 records were inserted into the 'ratings' table.
	- Ratings
	![Ratings](https://github.com/jediracer/Movies-ETL/blob/main/Resources/ratings_query.png)