## Improving-Customer-Satisfaction-using-Tweets
Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service"). The data was provided by Kaggle in both CSV and SQLite database here. In this project, I used the SQLite database as the source and analyze the airline tweets to find trends and predict sentiments from reviews. This analysis will help airlines understand what makes their customers happy as well as bring their focus on the services which need improvements/changes. This will help them improve their service, increase customer satisfaction and in turn increase business.

We will analyze the below points:

Airline sentiment analysis
Popular words used for positive & negative tweets
Top 10 most frequent positive & negative words
Reasons for negative tweets
Predicting airline sentiments from reviews
Summary of Results
United and US Airways are more popular than American and Southwest airlines as more number of people have tweeted about them. Delta and Virgin America airlines have fewer tweets in comparison.
Out of the total sentiment count, United, US Airways and American airlines have substantial negative sentiments. These airlines need to address concerns and take steps to improve their customer satisfaction. Virgin America's sentiments are more balanced, with almost equal number of negative, neutral and positive sentiments.
Airlines need to improve their customer services, handle flight cancellations and delays, handle bag issues promptly. On the other hand, airlines seem to be doing great by responding promptly, arriving early, good in-flight services, good customer service, providing help and giving upgrades.
Except Delta, the main reason for negative tweets for all other airlines is 'Customer Service' followed by 'late flight'. 'Late flight' is the main reason for Delta. This analysis gives direction to airlines to increase customer satisfaction and hence improve business.
Dataset has a higher number of negative tweets indicting that many customers have encountered some problems while traveling. This also indicates that airlines need to take immediate actions to improve customer experience and in turn grow their business.
After balancing data with SMOTE, accuracy, precision, recall and f1 scores have improved.
To view the code and graphs accurately, please click here as some of the Plotly graphs are not displayed directly on Github.

Installation
Download the .ipynb (Jupyter file).
Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
Download the source files and place them in the same folder as the Jupyter file.