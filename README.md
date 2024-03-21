# Stock Sentiment Analysis

This project is a Flask web application that performs sentiment analysis on news articles related to a given stock symbol. The sentiment analysis is used to predict whether the stock price is likely to go up, down, or remain neutral based on the overall sentiment of the news.

## Features

- Retrieve news articles related to a given stock symbol using the News API
- Perform sentiment analysis on the retrieved news articles using TextBlob
- Aggregate the sentiment scores to determine the overall sentiment
- Predict the stock price direction (up, down, or neutral) based on the overall sentiment
- Simple web interface to input the stock symbol and view the prediction

## Requirements

- Python 3.x
- Flask
- TextBlob
- NewsAPI-Python

## Installation

1. Clone the repository:
2.Navigate to the project directory
3.Obtain a News API key from [https://newsapi.org/](https://newsapi.org/) and replace the placeholder API key in `app.py`.

## Usage

1. Run the Flask application:
2. Open your web browser and navigate to `http://localhost:5000`.

3. Enter a stock symbol in the input field and click the "Predict" button.

4. The prediction result will be displayed on the next page.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).
