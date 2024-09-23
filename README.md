Webscraping Billboard 100 and connecting to spotify API

Developed a Python-based web scraper that collects historical Top 100 songs from a specific date on Spotify. The program allows users to input any date and then creates a custom playlist of the most popular songs from that period.


Here are two README files for your projects:

Spotify Top 100 Time Machine
Project Overview: This project uses web scraping and the Spotify API to create a playlist of the top 100 Billboard songs from any given date. Users can input a date, and the project scrapes the Billboard Hot 100 website for that date, retrieves the song titles, and creates a custom Spotify playlist.

Technologies Used:

Python: For scripting and logic.
BeautifulSoup: For web scraping Billboard Hot 100 song titles.
Spotify API (Spotipy): To search for songs and create playlists on Spotify.
Requests: To make HTTP requests for fetching the Billboard page.
How It Works:

The user inputs a date in the format YYYY-MM-DD.
The script scrapes the Billboard Hot 100 page for that date and retrieves the song titles.
The script searches for these songs on Spotify and retrieves their URIs.
It creates a new private playlist on Spotify containing those songs.
Setup Instructions:

Clone this repository.
Install the required Python packages:

bash
pip install requests beautifulsoup4 spotipy

Set up a Spotify developer account and create a new app to get your client_id and client_secret.
Replace the placeholders for client_id and client_secret in the script with your credentials.
Run the script:
bash

python spotify_project.py
Usage:
When prompted, enter a date (e.g., YYYY-MM-DD).
The script will create a playlist of the Billboard Hot 100 songs from that date on your Spotify account.
