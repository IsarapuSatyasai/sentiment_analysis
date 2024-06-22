# Sentiment-Analysis Project
Sentiment Analysis is a text classification task aimed at understanding human behavior to enhance business or organizational strategies. This repository presents a comprehensive end-to-end project along with various experimental analyses.

<img src="data/sentiment_analysis.jpg" alt="screenshot of the sentiment-rating" />

In this project, we employ three distinct techniques for conducting sentiment analysis:
1. TextBlob
2. VADER
3. Transformers

### 1. TextBlob Sentiment Analysis

TextBlob is a Python library that makes it easy to perform sentiment analysis, which is the process of determining the emotion or opinion expressed in a piece of text. It uses a pre-built dictionary of words with associated sentiment scores to analyze the text and assign a polarity score ranging from -1 (negative) to +1 (positive), and a subjectivity score ranging from 0 (objective) to 1 (subjective). This allows users to quickly gauge the sentiment and subjectivity of any given text, making TextBlob a handy tool for tasks like analyzing customer reviews or social media posts.

### 2. VADER Sentiment Analysis
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a tool designed for sentiment analysis that works particularly well with social media text. It uses a predefined list of words with assigned sentiment scores and applies rules to account for context, such as the impact of negations, punctuation, and intensity modifiers (like "very" or "extremely"). VADER quickly calculates whether a text is positive, neutral, or negative, making it ideal for real-time sentiment assessment. Its efficiency and accuracy with informal language make it especially useful for analyzing tweets, reviews, and other online content.

### 3. Transformers Sentiment Analysis
Transformers Sentiment Analysis involves using advanced deep learning models called transformers to understand the sentiment expressed in text. These models are capable of learning intricate patterns and relationships within language, making them highly effective for tasks like sentiment analysis. In this approach, the transformer model is trained on a large dataset containing text samples labeled with their corresponding sentiment (positive, negative, or neutral). During training, the model learns to capture the subtle nuances and context-dependent meanings of words and phrases, enabling it to accurately predict the sentiment of unseen text. Once trained, the transformer model can analyze new text inputs and classify them into different sentiment categories. This method has gained popularity due to its ability to outperform traditional rule-based approaches and achieve state-of-the-art performance on various natural language processing tasks, including sentiment analysis.

### How It Works:
1. Input your opinion or review sourced from any website.
2. Choose a model from the available options to analyze the entered text.
3. Receive the sentiment analysis output, indicating whether the content is positive or negative along with a corresponding score.
4. Opt to visualize the model's true or predicted labels using a heatmap, based on your preference.

## Installation
Install all streamlit requirements by run the following command
> pip install requirements.txt
## Run Streamlit

To access and use the application, download or clone the repository and then run the command below.
> streamlit run app.py

Finally browse the link provided in your browser.
