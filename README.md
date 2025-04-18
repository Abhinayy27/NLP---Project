## Textual Data Extraction & Analysis Project
# Objective
The objective of this project is to extract textual article data from a list of provided URLs and perform comprehensive text analysis to compute various linguistic metrics.

This project is executed entirely in Python using popular web scraping and text processing libraries.

# Workflow

# Data Extraction
Input: Input.xlsx — contains a list of article URLs with their URL_ID.

For each URL:

Extract the article title and article text.

Ignore non-essential elements like headers, footers, advertisements, etc.

Save the clean article text in a .txt file named after its URL_ID.

# Tech Used:
BeautifulSoup

requests

(Optional) Selenium or Scrapy for handling dynamic content


# Data Analysis
Input: Extracted article text files.

Perform text analysis based on definitions provided in Text Analysis.docx.

Compute the following variables for each article:


📏 Metric	📄 Description
POSITIVE SCORE	                  Count of positive words
NEGATIVE SCORE	                  Count of negative words
POLARITY SCORE	                  Overall sentiment polarity
SUBJECTIVITY SCORE	              Degree of subjectivity in the text
AVG SENTENCE LENGTH	              Average number of words per sentence
PERCENTAGE OF COMPLEX WORDS     	Percentage of words with more than 2 syllables
FOG INDEX                         Readability score based on sentence length & complex words
AVG NUMBER OF WORDS PER SENTENCE	Self-explanatory
COMPLEX WORD COUNT	              Number of complex words
WORD COUNT	                      Total word count
SYLLABLE PER WORD	                Average syllables per word
PERSONAL PRONOUNS                	Number of personal pronouns used
AVG WORD LENGTH                  	Average word length in characters

