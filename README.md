# Intern Details

Name: Riya Chauhan

Intern ID:CTIS2027

Domain: Data Analytics

Duration-12 weeks

Mentor: Neela Santhosh Kumar

# Project Overview

This project focuses on performing sentiment analysis on textual data from Yelp reviews using Natural Language Processing (NLP). The main objective is to analyze customer feedback, identify positive, negative, and neutral sentiments, and visualize overall trends in the reviews.

The dataset used contains Yelp reviews in textual format. Each review is analyzed using TextBlob, a Python library for NLP, which calculates the sentiment polarity of each text. Polarity indicates whether the text expresses a positive, negative, or neutral opinion. By applying sentiment analysis, the project transforms unstructured textual data into meaningful insights.

This project demonstrates the real-world application of NLP in understanding customer opinions. Businesses can use these insights to evaluate product performance, identify areas for improvement, and enhance customer satisfaction. The project also includes visualization of sentiment distribution using an attractive bar chart, making the results easy to interpret.

# Dataset

File: yelp.csv

Key column: text – containing Yelp review text

Dataset cleaned and ready for analysis

# Analysis Performed

Imported required libraries: pandas, matplotlib, and TextBlob

Loaded the dataset successfully and inspected sample data

Defined a sentiment function that classifies reviews as Positive, Negative, or Neutral based on polarity

Applied the sentiment function to all reviews to generate a new column Sentiment

Calculated count of each sentiment category

Created a bar chart visualization showing the number of Positive, Negative, and Neutral reviews

Added numeric labels on bars for better readability

Used gridlines and customized titles to make the graph visually appealing

This process converts textual feedback into structured sentiment data and provides a clear visual overview of customer opinions.

# Key Insights

The majority of Yelp reviews are typically Positive, reflecting customer satisfaction

A smaller portion of reviews are Negative, highlighting areas where improvement is needed

Neutral reviews indicate opinions that are neither strongly positive nor negative

Visual representation of sentiment distribution makes it easier for businesses to understand trends and take action

Sentiment analysis can be applied to other textual data sources for customer feedback, social media, or product reviews

These insights help businesses make data-driven decisions to enhance services, products, and customer engagement.

# Tools & Technologies Used

Python

Pandas – for data manipulation

TextBlob – for NLP and sentiment analysis

Matplotlib – for data visualization

Jupyter Notebook / Google Colab – for running the project

# Project Files

sentiment_analysis using npl.ipynb → Python script with full code

yelp.csv → dataset of Yelp reviews

SENTIMENT ANALYSIS.png → bar chart showing sentiment distribution

README.md → project description

# How to Run

Open sentiment_analysis using npl.ipynb in Python IDE, Jupyter Notebook, or Google Colab

Install required libraries if not already installed:

pip install pandas matplotlib textblob

Run the script to:

Load the dataset

Apply sentiment analysis

Generate sentiment counts and bar graph

Output includes classified reviews and the visual sentiment distribution chart
