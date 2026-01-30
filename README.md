# Data-Crawl-on-X
This repository contains a data crawling script for collecting Twitter/X data related to flood disasters and volunteer activities using Tweet-Harvest. The crawling process is executed in Google Colab and leverages a Twitter/X authentication token to retrieve recent tweets based on specific keywords.

The script collects up to 2,000 tweets using keyword-based search queries (e.g., “relawan banjir” OR “banjir”) within a defined time range and language filter. The output data is stored in CSV format and loaded into a Pandas DataFrame for further data analysis, preprocessing, or visualization.

This dataset can be used for sentiment analysis, social network analysis, disaster response studies, and public discourse analysis related to natural disasters.

Tech Stack:

Python

Tweet-Harvest (Node.js)

Pandas

Google Colab

Twitter/X API
