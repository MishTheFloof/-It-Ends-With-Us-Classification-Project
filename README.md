 This project focuses on sentiment analysis of YouTube comments from the official trailer of It Ends With Us. Using comments scraped from the trailer's video, various machine learning models are employed to classify comments as Positive, Negative, or Neutral. The goal is to identify the general sentiment towards the trailer using traditional machine learning models like Naive Bayes, Random Forest, and Logistic Regression.

# Features
Data Collection: YouTube comments were scraped using Selenium.

Preprocessing: Text preprocessing included tokenization, stop word removal, number-to-word conversion, and the handling of emojis and special characters.

Sentiment Analysis: Sentiments were analyzed using the VADER sentiment analyzer, with compound scores used to label comments as Positive, Negative, or Neutral.

Model Training & Evaluation: Three different machine learning models (Naive Bayes, Random Forest, and Logistic Regression) were trained, evaluated, and compared based on accuracy and confusion matrices.

Visualization: Visualizations, including sentiment distribution, confusion matrices, and word clouds, provide insight into model performance and comment patterns.

Technologies Used

Selenium: Web scraping of YouTube comments.

Pandas & NumPy: Data manipulation and analysis.

Scikit-learn: Model building, training, and evaluation.

Natural Language Toolkit (nltk): Text preprocessing and sentiment analysis using VADER.

Matplotlib & Seaborn: Data visualization.

WordCloud: Visualization of frequent words in comments.

