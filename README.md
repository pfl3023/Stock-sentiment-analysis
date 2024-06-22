<h1>Stock Sentiment Analysis Project</h1>

<b>Overview:</b><br>
This project focuses on analyzing sentiment from news articles to predict stock market trends using natural language processing techniques. The goal is to develop a model that can accurately classify sentiment as positive, negative, or neutral based on the content of news articles related to specific stocks.<br>

<b>Tools and Techniques Used:</b><br>
Web Scraping: Beautiful Soup library was utilized to scrape news articles from various financial news websites.<br>
Sentiment Analysis: Vader (Valence Aware Dictionary and sentiment Reasoner) and Text blob were employed to compute sentiment scores for each article.<br>
Model Evaluation: AUC-ROC curve (Area Under the Receiver Operating Characteristic Curve),Accuracy and precision was used to assess the accuracy of the sentiment analysis model.<br>
Ensemble Method: A Voting Classifier ensemble method was implemented to combine multiple classification algorithms and improve prediction performance.<br>

<b>Project Structure:</b><br>
The project is organized as follows;<br>
dataset creation: Contains web scraped news headlines related to specific stocks.<br>
sentiment analysis: Sentiment analysis using Vader and text blob.<br>
Model training: Training and evaluating the Voting Classifier ensemble model.<br>
Model testing:  The ensemble model was tested on new stocks.<br>
Evaluation metrics: Sharpe Ratio,Maximum drawdowns,Number of trades executed and win ratio was calculated.<br>

<b>Dependencies:</b><br>
Ensure you have the following Python libraries installed:<br>
beautifulsoup4 for web scraping.<br>
vaderSentiment and TextBlob for sentiment analysis.<br>
scikit-learn for model evaluation and ensemble methods.<br>


<b>Results:</b><br>
The project aims to achieve high accuracy in predicting sentiment from news articles, thereby providing insights into potential stock market trends. Results of model evaluation, including AUC-ROC curves and classification metrics, will be detailed in the notebook and summarized in report.<br>

<b>Future Enhancements:<b><br>
Future iterations of this project could include-<br>
Incorporating more sophisticated NLP techniques for sentiment analysis.<br>
Expanding the scope of scraped sources to include social media platforms.<br>
Implementing real-time sentiment analysis for more dynamic predictions.<br>
