 🦋🌟👗🧣🏙🐍💘🍷🥂 
"We're happy, free, confused and lonely at the same time."
-22

# Taylor Swift's Daily Top 10 Most Played Songs

This project uses Spotify data to track the daily streaming metrics of Taylor Swift's most-played songs!!

The project is an auto-updating, data-driven website. 

Using GitHub Actions and Spotipy, the workflow unfolds across two key steps:

1. I used Jupyter Notebook to access the public Spotify data. Through the Spotipy API, I am able to extract the latest data  every evening and append it to a CSV file for continuous record-keeping. 
2. Subsequently, the process is automated through GitHub Actions, using environment variables for its execution and keeping the API key a secret.
3. Finally, the result is a cute Taylor Swift-themed website, with graphics created using DataWrapper.

This website employs web scraping techniques through Beautiful Soup and Playwright to extract information from Spotipy, which is then stored in a CSV file. The file showcases the constantly changing Taylor Swift's most-streamed songs on a day-to-day basis. Using HTML and DataWrapper, I created a website to visualize the information from the CSV file. 
