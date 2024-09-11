# ✈️ Airline Sentiment Analysis 🌍

This project is a web application that performs sentiment analysis on tweets about airlines. Using Naive Bayes and Random Forest classifiers, the app predicts whether a given tweet about an airline is **positive**, **neutral**, or **negative**. The goal is to help airlines understand customer feedback by analyzing the sentiment of tweets.

## 🛠 Features

- **Naive Bayes Classifier**: A probabilistic model trained to predict tweet sentiment.
- **Random Forest Classifier**: A more complex ensemble model used for sentiment prediction.
- **TF-IDF Vectorization**: Converts text data into numerical form, which the models use to learn and make predictions.
- **User Input**: Users can input any tweet, and the app will predict the sentiment using both models.
- **Emoji-based Sentiment Display**: Predictions are displayed with relevant emojis for a more engaging user experience:
  - 😊 🎉: Positive sentiment
  - 😐: Neutral sentiment
  - 😞 ❌: Negative sentiment
- **Image Gallery**: A carousel of images showcasing airlines.

## 🚀 How it Works

1. The user enters a tweet in the text box.
2. The app preprocesses the tweet using techniques like tokenization, stop word removal, and stemming.
3. The cleaned tweet is transformed using **TF-IDF vectorization**.
4. The tweet is then passed through two models:
   - **Multinomial Naive Bayes**
   - **Random Forest Classifier**
5. Both models predict the sentiment, and the results are shown to the user along with emojis representing the sentiment.
6. The app also displays the accuracy of both models based on the test set.

## 🔍 Dataset

The app uses the **Tweets.csv** dataset, which contains:
- `airline_sentiment`: The sentiment of the tweet (positive, neutral, negative).
- `text`: The actual tweet content.

The dataset was cleaned and preprocessed before training the models.

## 📊 Models

### Naive Bayes Classifier
- A simple probabilistic model based on Bayes' theorem.
- It works well with text data and is fast to train and predict.

### Random Forest Classifier
- An ensemble model that builds multiple decision trees and merges them together for better predictions.
- It typically provides more robust results compared to simpler models.

## 💻 Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/airline-sentiment-analysis.git
    cd airline-sentiment-analysis
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app**:
    ```bash
    streamlit run app.py
    ```

4. **Open the app**:
   - The app will be available at `http://localhost:8501` in your web browser.

## 🎨 User Interface

The web app is designed with a light and minimalistic theme, featuring:
- A blue and white background to provide a calming visual experience.
- Emojis to make the sentiment analysis results more relatable and fun.
- A slider to navigate through the image gallery of airlines.

## 📷 Screenshots

![sen2](https://github.com/user-attachments/assets/013bfd9b-7bd4-458a-9e35-600a0eb55775)
![sen3](https://github.com/user-attachments/assets/533391aa-f249-44b5-b582-9e84ecf5aa38)

## 🤖 Technologies Used

- **Python**
- **Streamlit** for building the web interface.
- **Scikit-learn** for machine learning models.
- **NLTK** for natural language processing.
- **Pandas** for data manipulation.
- **TF-IDF** for feature extraction from text.

## 📚 Future Enhancements

- Add more models to compare performance.
- Integrate with a live Twitter API for real-time sentiment analysis.
- Improve text preprocessing by using more advanced NLP techniques like lemmatization.

## 📞 Contact

For any questions, please feel free to reach out:

- **Email**: thirudilak131@gmail.com
- **LinkedIn**: [Dilaksan Thirugnanaselvam](https://www.linkedin.com/in/dilaksan-thirugnanaselvam)
  
