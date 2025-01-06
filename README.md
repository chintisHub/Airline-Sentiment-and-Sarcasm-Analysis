# Sentiment and Sarcasm Detection Project

## Overview

This project focuses on detecting sarcasm and analyzing sentiments from text data. It uses two datasets: one for sarcasm detection and another for sentiment analysis of airline tweets. The project includes a Jupyter Notebook for data analysis and a PDF report outlining the findings.

## Project Structure

```
├── Sarcasm_Headlines_Dataset.json   # Dataset for sarcasm detection
├── Sentiment Analysis of Airline Tweets.pdf   # Project report
├── DIC_PHASE2.ipynb   # Jupyter Notebook with the project code
├── Tweets.csv   # Dataset containing airline tweets for sentiment analysis
└── README.md   # Project documentation
```

## Datasets

1. **Sarcasm\_Headlines\_Dataset.json**: This dataset contains headlines from news articles. The labels indicate whether the headline is sarcastic or not.
2. **Tweets.csv**: This dataset contains tweets directed at airlines with sentiment labels (positive, neutral, negative).

## Files and Purpose

| File Name                                | Description                                |
| ---------------------------------------- | ------------------------------------------ |
| Sarcasm\_Headlines\_Dataset.json         | Dataset used for sarcasm detection         |
| Sentiment Analysis of Airline Tweets.pdf | PDF report with insights from the project  |
| DIC\_PHASE2.ipynb                        | Jupyter Notebook for analysis and modeling |
| Tweets.csv                               | Dataset for sentiment analysis             |

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-sarcasm-detection.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook DIC_PHASE2.ipynb
   ```
3. Run the cells to load datasets, preprocess data, and train models.

## Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

Install the required packages using:

```bash
pip install -r requirements.txt
```

## Project Insights

- **Sarcasm Detection**: Uses a dataset of news headlines labeled for sarcasm. The model aims to predict whether a given headline is sarcastic.
- **Sentiment Analysis**: Analyzes sentiments of tweets directed at airlines. The model classifies tweets into positive, neutral, or negative sentiments.

## Next Steps

- Improve the models by experimenting with different algorithms and tuning hyperparameters.
- Integrate the models into a web-based interface for real-time detection.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the MIT License.

