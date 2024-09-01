# financial-news-sentiment-correlation-analysis

## Overview
This project is designed to enhance Nova Financial Solutions' predictive analytics by analyzing financial news. The main goals are:

1. **Sentiment Analysis**: Utilize NLP to analyze news headlines and quantify sentiment.
2. **Correlation Analysis**: Identify correlations between news sentiment and stock price movements.

## Dataset
- **headline**: News article title.
- **url**: Link to the full article.
- **publisher**: Article author.
- **date**: Publication date and time (UTC-4).
- **stock**: Stock ticker symbol (e.g., AAPL for Apple).

## Setup Instructions
###To set up the project locally, follow these steps:
1. **Clone the repository**:
   ```
   git clone : https://github.com/EstifanosAschalew/financial-news-sentiment-correlation-analysis.git
   cd ffinancial-news-sentiment-correlation-analysis

2. **Create a virtual environment**:
   ```
   python -m venv project-venv
   source project-venv/bin/activate   # On Windows: project-venv\Scripts\activate

3. **Install dependencies:**
   ```
   pip install -r requirements.txt
4. **Set up Git:**
   ```
   Create a new branch for each task (e.g., task-1):
     git checkout -b task-1

   Commit your changes regularly with descriptive messages:
    git commit -m "Descriptive message about the changes"
   Push your branch to GitHub:
     git push origin task-1
