# Sentiment-analysis

<h2>Overview</h2>
This project utilizes various natural language processing (NLP) tools and libraries to analyze text data extracted from a given URL. The analysis includes tokenizing words and sentences, extracting key linguistic features, and computing various linguistic metrics. The goal is to gain insights into the sentiment, complexity, and structure of the text.<br>
<h3>Dependencies</h3>
Make sure you have the following Python libraries installed:<br>

goose3<br>
nltk<br>
spacy<br><br>
You can install them using the following command:<br>
pip install goose3 nltk spacy<br>

<h3>Usage</h3>
Import the necessary libraries:<br>
from goose3 import Goose<br>
import string<br>
import nltk<br>
from nltk.tokenize import sent_tokenize, word_tokenize<br>
from nltk.corpus import cmudict<br>
import spacy<br>
import re<br><br><br>

Define the URL you want to analyze.<br><br>

Use the provided functions to extract various linguistic features and metrics:<br>

tokenize_words(text): Tokenizes words from the given text.<br>
tokenize_sentences(text): Tokenizes sentences from the given text.<br>
get_stop_words(): Retrieves a list of stop words.<br>
calculate_final_words_len(text): Calculates the length of the final words after removing stop words.<br>
... (Add more functions as needed for your analysis)<br><br>
Perform your analysis and use the extracted features to calculate metrics such as Positive Score, Negative Score, Polarity Score, Subjectivity Score, Average Sentence Length, Percentage of Complex Words, Fog Index, Average Number of Words Per Sentence, Complex Word Count, Word Count, Syllables per Word, Personal Pronoun, Average Word Length, etc.<br>

