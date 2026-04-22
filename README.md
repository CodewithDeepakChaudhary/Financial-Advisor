# Financial Investment Recommendation System

An advanced financial investment recommendation platform that leverages machine learning to generate personalized investment strategies. The system integrates real-time market data, historical stock data, user preferences, and predictive analytics to provide intelligent investment guidance.

## Features

- Personalized stock recommendations based on user preferences
- Portfolio management and performance tracking
- Real-time market data integration
- Historical stock price data and visualization
- News sentiment analysis
- Interactive dashboard with charts and analytics

## Database Options

This project uses PostgreSQL as the database.

## Initial Setup Steps

1. Register a new user account
2. Set up your investment preferences
3. Navigate to `/test/generate-recommendations` to populate sample stocks and recommendations
4. Add stocks to your portfolio
5. Explore the dashboard, recommendations, and news features

## Project Structure

- `main.py`: Entry point for the application
- `app.py`: Flask app configuration
- `models.py`: Database models
- `routes.py`: Application routes and views
- `data_fetcher.py`: Functions to fetch stock and news data
- `recommendation.py`: Recommendation engine
- `sentiment_analysis.py`: News sentiment analysis
- `templates/`: HTML templates
- `static/`: CSS, JavaScript, and other static files

## Technologies Used

- **Backend**: Python, Flask, SQLAlchemy
- **Database**: PostgreSQL
- **Data Processing**: Pandas, NumPy, scikit-learn
- **Natural Language Processing**: NLTK
- **Frontend**: HTML, CSS, Bootstrap, Chart.js
- **APIs**: Yahoo Finance, News API, Alpha Vantage
