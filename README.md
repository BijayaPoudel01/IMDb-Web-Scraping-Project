# IMDb-Web-Scraping-Project
My first web scraping project using Python and Selenium (IMDb Top 250)

# Overview
This project scrapes data from the IMDb Top 250 Movies list (https://www.imdb.com/chart/top/) using Python and Selenium. The extracted data includes movie titles, release years, runtimes, IMDb ratings, and review counts. The data is then saved into CSV and JSON formats for further analysis.

# Project Structure
Jupyter Notebook: movies_webscrapping.ipynb contains the complete web scraping code.

# Data Files:
movies_imdb.csv: CSV file containing the scraped movie data.
movies_imdb.json: JSON file containing the same data in JSON format.

# Data Extracted
For each of the top 250 movies on IMDb, the following details are collected:

Title: Movie title with its rank (e.g., "1. The Shawshank Redemption").

Released Year: The year the movie was released.

Runtime: Duration of the movie (Note: In the current output, this field incorrectly shows the release year due to an XPATH issue).

IMDb Rating: The movie's rating on IMDb (e.g., "9.3").

Reviews Count: Approximate number of reviews (e.g., "(3M)" for 3 million reviews).

# Libraries Used
Selenium: For web scraping and automating browser interactions.

Pandas: For data manipulation and saving to CSV/JSON.


