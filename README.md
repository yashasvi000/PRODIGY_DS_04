# PRODIGY_DS_04
Task 4 – Sentiment Analysis on Social Media Data

📌 Task Number & Title

Task 4: Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

⸻

📌 Short Description

In this task, I performed sentiment analysis on a Twitter dataset to understand public opinion. The dataset contains tweets with labels such as Positive, Negative, Neutral, or Irrelevant.
The goal was to analyze text data, apply a sentiment classifier, and visualize the overall sentiment trends.

⸻

📌 Approach / Steps Followed
	1.	Dataset Preparation
	•	Used twitter_training.csv containing tweets and their sentiment labels.
	•	Cleaned text data (removed links, hashtags, mentions, special characters, converted to lowercase).
	2.	Sentiment Analysis
	•	Applied VADER SentimentIntensityAnalyzer from NLTK to assign sentiment scores.
	•	Classified tweets into Positive, Negative, Neutral using compound score.
	•	Compared given dataset labels (if available) vs VADER predictions.
	3.	Visualization
	•	Countplot showing sentiment distribution.
	•	WordClouds for each sentiment to highlight frequently used words.
	4.	Insights
	•	Observed the dominant sentiment (positive/negative/neutral).
	•	Identified common keywords associated with each sentiment group.

 📌 How to Run the Project/Code
	1.	Upload twitter_training.csv in Google Colab.
	2.	Install dependencies (if not already installed):

    pip install pandas matplotlib seaborn nltk wordcloud

  3.	Download NLTK VADER lexicon:

     import nltk 
     nltk.download('vader_lexicon')

  4.	Run the notebook step by step:
	•	Load dataset
	•	Clean text data
	•	Perform VADER sentiment analysis
	•	Visualize results (countplot & wordclouds)



