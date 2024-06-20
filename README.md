Stock Sentiment Analysis Project

Overview:
This project focuses on analyzing sentiment from news articles to predict stock market trends using natural language processing techniques. The goal is to develop a model that can accurately classify sentiment as positive, negative, or neutral based on the content of news articles related to specific stocks.

Tools and Techniques Used:
Web Scraping: Beautiful Soup library was utilized to scrape news articles from various financial news websites.
Sentiment Analysis: Vader (Valence Aware Dictionary and sentiment Reasoner) and Text blob were employed to compute sentiment scores for each article.
Model Evaluation: AUC-ROC curve (Area Under the Receiver Operating Characteristic Curve),Accuracy and precision was used to assess the accuracy of the sentiment analysis model.
Ensemble Method: A Voting Classifier ensemble method was implemented to combine multiple classification algorithms and improve prediction performance.

Project Structure:
The project is organized as follows;
dataset creation: Contains web scraped news headlines related to specific stocks.
sentiment analysis: Sentiment analysis using Vader and text blob.
Model training: Training and evaluating the Voting Classifier ensemble model.
Model testing:  The ensemble model was tested on new stocks.
Evaluation metrics: Sharpe Ratio,Maximum drawdowns,Number of trades executed and win ratio was calculated.

Dependencies:
Ensure you have the following Python libraries installed:
beautifulsoup4 for web scraping.
vaderSentiment and TextBlob for sentiment analysis.
scikit-learn for model evaluation and ensemble methods.


Results:
The project aims to achieve high accuracy in predicting sentiment from news articles, thereby providing insights into potential stock market trends. Results of model evaluation, including AUC-ROC curves and classification metrics, will be detailed in the notebook and summarized in report.

Future Enhancements:
Future iterations of this project could include-
Incorporating more sophisticated NLP techniques for sentiment analysis.
Expanding the scope of scraped sources to include social media platforms.
Implementing real-time sentiment analysis for more dynamic predictions.
