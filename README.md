# Sentiment Analysis and Visualization of Web Content
## Overview
This project provides a powerful tool to perform sentiment analysis on any website, blog, or web page. By simply inputting the URL, this tool scrapes the content, analyzes the sentiment of the text using VADER and TextBlob, and visualizes the results using various interactive charts and dashboards. The project is designed to give deep insights into the sentiment trends and allows users to interactively explore the data.

## Features
#### Sentiment Analysis: 
Analyze sentiment for any website content using VADER (Valence Aware Dictionary for Sentiment Reasoning) and TextBlob.
#### Visualization:
##### Bar Chart: 
Display the distribution of positive, negative, and neutral sentiments.
##### Donut Chart: 
Show sentiment distribution as a donut chart for easy interpretation.
##### Violin Chart: 
Visualize the density and distribution of sentiment scores.
##### Word Cloud: 
Generate a word cloud from the website's content with interactive controls for the number of words and background color.
##### Sentiment Trend Over Time: 
Plot sentiment trends over the length of the content to identify shifts in tone.
##### Interactive Dashboards: 
Utilize ipywidgets to create interactive dashboards where users can dynamically adjust parameters and explore different visualizations.
##### Sentence-Level Sentiment Analysis: 
Identify reasons why particular sentences are classified as positive, negative, or neutral.
#### Model Testing and Evaluation: 
Test the sentiment analysis model on 100+ sentences, calculate a confusion matrix, and achieve an accuracy of 77.42%.

## Required Libraries:

requests
BeautifulSoup4
nltk
matplotlib
seaborn
pandas
ipywidgets
wordcloud
TextBlob
plotly
VADER
sklearn
## Download NLTK Data: 
Download the required NLTK data (like VADER lexicon):


import nltk
nltk.download('vader_lexicon')
## Usage
### Scrape Website Content:

Enter the URL of the website you want to analyze.
The tool will automatically scrape the text content from the website.
### Perform Sentiment Analysis:

Analyze the sentiment using VADER and TextBlob.
The sentiment scores for each sentence will be calculated and categorized.
### Visualize the Results:

Interactive Dashboards: Explore the sentiment analysis results with interactive controls. Adjust parameters like the number of words in the word cloud or change the background color dynamically.
### Sentiment Distribution: 
View bar charts, donut charts, and violin plots to understand the sentiment distribution.
### Sentiment Trend Over Time: 
Plot the sentiment trend to observe changes in sentiment throughout the content.
### Evaluate Model Performance:

Test the model on a dataset of 100+ sentences.
Generate a confusion matrix and evaluate the model's accuracy, achieving 77.42%.

## Contributing
Contributions are welcome! If you have ideas for improvements or new features, feel free to submit a pull request or open an issue.
