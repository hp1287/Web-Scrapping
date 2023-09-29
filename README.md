# IMDb Web Scraping Project

This project demonstrates web scraping techniques to extract information from IMDb's list of the top 100 movies. The data includes movie names, release years, runtime, ratings, metascores, votes, gross collections, descriptions, directors, and star casts.

## Dependencies

- `pandas`: Used to create and manipulate data in the form of a DataFrame.
- `requests`: Sends HTTP requests to the IMDb website to fetch data.
- `BeautifulSoup`: Parses the HTML content of the IMDb page.
- `numpy`: Used for counting values.

## Data Collected

- **Name of Movie**: The title of the movie.
- **Year of Release**: The year when the movie was released.
- **Watchtime**: The duration of the movie in minutes.
- **Movie Rating**: IMDb user rating for the movie.
- **Metascore**: Metacritic score (if available) for critical reviews.
- **Votes**: The number of votes/ratings on IMDb.
- **Gross Collection**: Gross collection (if available) in USD.
- **Description**: A brief description of the movie.
- **Director**: The director of the movie.
- **Star**: A list of the movie's main cast members.

## Note

This project is for educational purposes and showcases web scraping techniques using Python. Be mindful of IMDb's terms of service and respect their data usage policies when scraping their website.

Happy web scraping!
