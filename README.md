# Trump-Twitter-Text-Analytics
This project performs text analytics and sentiment analysis on tweets posted by Donald Trump between 2009 and 2020. The main objective is to study how Trump used Twitter before and during his presidency, especially analyzing tweet content, activity patterns, audience engagement (retweets &amp; favorites), and sentiment trends.

## Problem Statement ##
The project aims to:
 - Analyze every tweet sent by Donald Trump before and during his presidency.
 - Explore patterns in content, posting time, engagement (retweets/favorites), and sentiment.
 - Apply text preprocessing steps (tokenization, stopword removal, lemmatization, etc.) on tweet content for clean analysis.
 - Investigate sentiment polarity (positive vs. negative tweets) and activity patterns.
 - Gain insights into Trump’s communication style and how it changed over the years.

## Dataset Information ##
Source: Tweets from Donald Trump (2009–2020).

Columns:
 - content: text of the tweet
 - date: timestamp
 - retweets: number of retweets
 - favorites: number of likes
 - Sentiment: pre-labeled (Positive/Negative)

Additional features were engineered such as year, month, day, and hour for time-based analysis.

## Approach & Methodology ##

**1. Data Cleaning & Preprocessing**
 - Removed unnecessary characters, punctuation, and URLs.
 - Tokenized tweet text into words.
 - Removed stopwords and applied lemmatization.
 - Extracted temporal features (year, month, day, hour).

**2. Exploratory Data Analysis (EDA)**
 - Tweet distribution across years and months.
 - Engagement trends (retweets & favorites).
 - Word frequency and common terms visualization.
 - Sentiment distribution across time.

**3. Sentiment Analysis**
 - Used the pre-labeled sentiment column.
 - Compared positive vs. negative tweets.
 - Identified shifts in sentiment before and during presidency.

**4. Results & Findings**
 - Trump’s tweeting frequency increased during presidency.
 - Negative tweets spiked around politically charged events.
 - Certain words and hashtags were heavily repeated.
 - Tweets posted late at night had distinct sentiment/engagement patterns.

## Outcomes ##

- A clear understanding of Trump’s communication style over time.
- Evidence that tweet volume, tone, and sentiment shifted during presidency.
- Insights into how Trump used Twitter as a political tool and a means of direct communication.
- Preprocessed dataset is now structured for further ML applications (e.g., topic modeling, deeper sentiment classification).

## Tech Stack ##
 - python
 - libraries used:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - wordcloud
    - nltk
