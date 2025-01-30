### README for "Twitter Sentiment Analysis"

# Twitter Sentiment Analysis

This project analyzes public sentiment from tweets related to specific topics or keywords. The analysis helps categorize tweets as Positive, Neutral, or Negative by preprocessing the text, extracting features, and using machine learning models.

---

## Features

- **Data Preprocessing:**
  - Handles text cleaning (removes URLs, mentions, hashtags, and special characters).
  - Tokenization, stopword removal, and stemming.
- **Sentiment Analysis:**
  - Assigns sentiment scores using TextBlob.
  - Categorizes tweets into Positive, Neutral, and Negative sentiments.
- **Visualizations:**
  - Word clouds for most frequent words in positive, neutral, and negative tweets.
  - Sentiment distribution charts (bar and pie charts).
- **Machine Learning Models:**
  - Logistic Regression and SVM for classification.
  - Hyperparameter tuning using GridSearchCV.
  - Accuracy evaluation through classification reports and confusion matrices.
- **Twitter API Integration:**
  - Fetch live tweets for real-time analysis using Tweepy.

---

## Installation

1. Clone the repository.
   ```bash
   git clone <repository-link>
   ```
2. Install required libraries.
   ```bash
   pip install -r requirements.txt
   ```
3. Add your Twitter API keys in the `consumerKey`, `consumerSecret`, `accessToken`, and `accessTokenSecret` variables.

---

## Usage

1. Preprocess the dataset:
   - Add the dataset (e.g., `vaccination_tweets.csv`) in the project directory.
   - Run the preprocessing steps in the notebook.
2. Train the models:
   - Logistic Regression and SVM are implemented; evaluate performance using the test set.
3. Analyze results:
   - Use visualizations to understand trends and insights from the data.
4. Fetch live tweets (optional):
   - Use the provided Tweepy code to analyze real-time data.

---

## Results

- **Accuracy:**
  - Logistic Regression: Achieved ~85% test accuracy.
  - SVM: Achieved ~87% test accuracy with optimized hyperparameters.
- **Insights:**
  - Sentiment distribution of tweets is visually represented.
  - Word clouds highlight frequent terms across sentiments.

---

## Tools & Libraries

- **Libraries:** TextBlob, NLTK, Matplotlib, Seaborn, WordCloud, Tweepy, Scikit-learn
- **API:** Twitter API for fetching live tweets.

---

## Future Scope

- Integration with a live dashboard.
- Support for multilingual sentiment analysis.
- Advanced deep learning models like LSTM or BERT.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- Inspiration from publicly available datasets.
- Resources from the NLTK and Scikit-learn documentation.

---
