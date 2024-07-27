# YouTube Comment Sentiment Analysis with Streamlit

## Overview

This Streamlit application performs sentiment analysis on YouTube video comments. It uses the Hugging Face `transformers` library for sentiment analysis and NLTK for text preprocessing. The app allows users to fetch comments from a YouTube video and analyze their sentiment.

![App Screenshot](https://github.com/Tejasnyadav/LLM-APP/blob/main/Screenshot%202024-07-27%20153326.png)

## Features

- Fetch comments from a YouTube video using the YouTube Data API.
- Preprocess comments to remove punctuation, stopwords, and apply lemmatization.
- Perform sentiment analysis on the preprocessed comments using a pre-trained DistilBERT model.
- Visualize the sentiment analysis results with a bar chart.

## Prerequisites

- Python 3.7+
- Streamlit
- Requests
- Pandas
- NLTK
- Transformers
- Seaborn

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository

2.**Create and Activate a Virtual Environment:**
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

3.**Install Dependencies**
pip install -r requirements.txt

4.**Run the Streamlit App**
streamlit run app.py

