# YouTube Comment Summarizer

## Overview
The **YouTube Comment Summarizer** is a web-based tool built using **Streamlit** that allows users to extract comments from any YouTube video and generate a concise summary using **Google Gemini** and **LangChain** models. It leverages the YouTube API to fetch comments and uses Natural Language Processing (NLP) techniques to summarize the extracted text.

## Features
- **YouTube API Integration**: Fetches comments from any public YouTube video.
- **Summarization**: Uses Google Gemini model paired with LangChain to generate meaningful summaries.
- **Streamlit Interface**: Provides a simple, interactive web app to input a YouTube video URL and view the summary.

## Project Structure
- `comments.py`: Handles fetching comments from YouTube via YouTube Data API.
- `app.py`: Main Streamlit app to interact with the user and display the summarized comments.
- `util.py`: Contains the logic for tokenization and summarization using Google Gemini via LangChain.
