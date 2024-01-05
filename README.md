# Taylor Swift's Daily Top 10 Most Played Song-
This project uses Spotify data to track the daily streaming metrics of Taylor Swift's most-played songs!! 

Using GitHub Actions and Spotipy, the workflow unfolds across two key steps:

1. A Jupyter Notebook is employed to interface with the Spotipy API, extracting the latest data  every evening and appending it to a CSV file for continuous record-keeping. 
2. Subsequently, the process is automated through GitHub Actions, facilitated by environment variables for seamless execution.

The project extends its scope by integrating an auto-updating, data-driven website. This website employs web scraping techniques through Beautiful Soup and Playwright to extract information from Spotipy, which is then stored in a CSV file. The file showcases the constantly changing Taylor Swift's most-streamed songs on a day-to-day basis.
