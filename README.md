# News Categorizer

This application collects news articles from various RSS feeds, categorizes them, and displays them in a Streamlit web interface.

## Setup

1. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

2. Create a `.env` file in the project directory with the following content:
   ```
   DATABASE_URL=sqlite:///news.db
   ```

3. Download the required NLTK data:
   ```
   python setup_nltk.py
   ```

## Running the Application

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501` to view the application.

## Features

- Fetches news articles from multiple RSS feeds
- Categorizes articles using natural language processing
- Stores articles in a SQLite database
- Displays articles in a user-friendly web interface
- Allows filtering of articles by category
- Automatically updates news every hour
- Provides a manual refresh button for immediate updates