# YouTube Data Analysis with Python

This repository contains Python code to gather and analyze YouTube channel and video data using the YouTube Data API.

## Overview

The code in this repository demonstrates how to use the YouTube Data API to retrieve information about YouTube channels and their videos, perform analysis, and visualize the results. The provided functions cover tasks such as:

- Fetching channel statistics and creating a DataFrame
- Retrieving video IDs from a playlist
- Gathering video details (views, likes, duration, etc.) and storing them in a DataFrame
- Performing various data cleaning and manipulation tasks
- Creating visualizations like bar plots, scatter plots, and word clouds

## Code Explanation

The main parts of the code are:

1. **API Key Setup**: Replace `'YOUR_API_KEY'` with your actual YouTube Data API key.

2. **Fetching Channel Stats**: The `get_channel_stats` function fetches channel statistics and stores them in a DataFrame.

3. **Fetching Video IDs**: The `get_video_ids` function retrieves video IDs from a given playlist.

4. **Fetching Video Details**: The `get_video_details` function collects details for each video, including views, likes, and duration.

5. **Data Cleaning**: The code cleans and processes data, converting some columns to numeric and calculating video duration in seconds.

6. **Data Analysis**: The code performs basic data analysis, such as plotting views against comments and likes, and generating a word cloud from video titles.

7. **Publishing Day Analysis**: The code analyzes which days of the week have the most published videos.
