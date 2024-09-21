# Podcast Transcription App

This repository contains the code for the Podcast Transcription App, which allows users to search for podcasts featuring specific individuals, select an episode, and receive a transcription of the audio.

## Features

- Search for podcasts by person name.
- Display a list of recent podcasts featuring the specified individual.
- Select a podcast to transcribe.
- Download the audio of the selected podcast for transcription.
- View the full transcription in the app.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Streamlit: [Installation Guide](https://docs.streamlit.io/library/getting-started/installation)
- Requests: Install with `pip install requests`
- Dotenv: Install with `pip install python-dotenv`

### Installation

1. Clone the repository:
   git clone https://github.com/yourusername/podcast-transcription-app.git
   cd podcast-transcription-app
2. Create a .env file in the root directory and add your Spotify and Groq API credentials:
    - SPOTIFY_CLIENT_ID = your_spotify_client_id
    - SPOTIFY_CLIENT_SECRET = your_spotify_client_secret
    - GROQ_API_KEY = your_groq_api_key
3.  Install dependencies:
    pip install -r requirements.txt
4.  Run the app:
    streamlit run app.py


### Folder Structure
- app.py: Main application file.
- .env: Contains sensitive credentials (not included in version control).
- requirements.txt: Lists all dependencies for the project.


### Usage
- Open the app in your web browser.
- Enter the name of the person whose podcasts you want to search for.
- Click the "Search Podcasts" button to fetch relevant podcasts.
- Select a podcast from the list and click on it to transcribe the audio.
- View the transcription directly in the app.


### Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
