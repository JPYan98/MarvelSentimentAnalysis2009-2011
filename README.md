# Marvel Universe Sentiment Analysis 2009-2011

This repository contains a comprehensive Python code to perform text and sentiment analysis on dialogues from Marvel Cinematic Universe movies released between 2008 and 2011. The analysis provides insights into the popularity and sentiment associated with the top characters in the Marvel franchise during this period. The repository also includes sentiment analysis on a Twitter dataset to validate the performance of various machine-learning models.

Source of mcu.csv is: https://www.kaggle.com/datasets/pdunton/marvel-cinematic-universe-dialogue?select=mcu.csv

Link to twits.csv file: https://www.dropbox.com/scl/fi/rjh157s4dc3ct5u86kd2s/twits.csv?rlkey=7d3cxl6nfzytskizafhi5fzyp&dl=0

This file is too large for GitHub to upload; it contains many Twitter feeds from 2009 to 2011.

## Libraries Used:

Pandas

NumPy

Seaborn

Matplotlib

NLTK

TextBlob

Scikit-Learn

WordCloud

## Features:

Data Exploration and Preprocessing: Importing and exploring the dataset, filtering out the data for the desired years, and evaluating basic statistics.

Character Analysis: Analyzing the popularity and verbosity of characters, visualizing the top characters based on their appearance and word count.

Text Mining: Implementing text preprocessing steps like tokenization, stopword removal, stemming, and lemmatization.

Word Clouds: Generating word clouds for individual characters to visualize the frequency of words used by them.

Sentiment Analysis: Conducting sentiment analysis on Twitter data to build and validate predictive models. Then, applying the best-performing model to predict sentiments for the Marvel dialogues.

Visualization: Visualizing the sentiment analysis results for individual characters and across different years of the franchise.

## Files:

mcu.csv: Contains the dialogues, character, and year information from Marvel movies.

twits.csv: Contains a dataset of Twitter tweets with labels indicating positive or negative sentiments.

Marvel_Sentiment_Analysis.ipynb: Jupyter Notebook containing all the code.

## Setup and Execution:
Clone the repository to your local machine.

Ensure you have all the required libraries installed.

Download the datasets mcu.csv and twits.csv, and place them in the same directory as the Jupyter Notebook.

Open and run the Marvel_Sentiment_Analysis.ipynb notebook to see the analysis and visualizations.

## Results:

The analysis and visualizations provide interesting insights into the Marvel Universe characters' popularity and sentiments associated with them during the early phase of the franchise. The analysis further extends to evaluating the sentiment trend across different years.

## License:

This project is licensed under the MIT License - see the LICENSE.md file for details

Feel free to explore the code and use it for your own projects! If you have any questions or suggestions, feel free to open an issue or make a pull request.

