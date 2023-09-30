# Google-Product-Reviews-Scrape-Analyse
App to Scrape Google for reviews of an item (product, movie, etc.) and runs sentiment analysis on the result.
## What it uses
 - *Huggingface* for sentiment analysis
 - AutoTokenizer, AutoModelForSequenceClassification for the sentiment analysis pipeline
    - Uses `LiYuan/amazon-review-sentiment-analysis` for 1 - 5 star rating
    - Uses `cardiffnlp/twitter-roberta-base-sentiment-latest` for positive/neutral/negative sentiment
 - *Apify* for scraping Google
 - *Streamlit* for hosting the website
 - *WordCloud* for word clouds

## Demo
Run on Google Colab






## References
 - Inspired by [nus-sentiment](https://github.com/nus-sentiment/nus-sentiment)
