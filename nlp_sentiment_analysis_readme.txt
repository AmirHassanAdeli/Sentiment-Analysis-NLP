# Sentiment Analysis with NLP

## Overview
This project implements a sentiment analysis tool using Hugging Face Transformers to classify Twitter texts as positive or negative. It uses the Sentiment140 dataset for demonstration.

## Tools and Technologies
- **Python**: Core programming language
- **Hugging Face Transformers**: For sentiment analysis
- **Pandas**: For data preprocessing
- **Matplotlib/Seaborn**: For visualization

## Methodology
1. **Data Preprocessing**: Loaded the Sentiment140 dataset and selected sample tweets.
2. **Model Selection**: Used the pre-trained `distilbert-base-uncased-finetuned-sst-2-english` model.
3. **Text Analysis**: Processed texts to predict sentiment labels and confidence scores.
4. **Visualization**: Created a bar plot to display sentiment results.

## Results
- Accurately classified texts as Positive or Negative with high confidence scores.
- The bar plot (`sentiment_analysis.png`) visualizes the sentiment distribution.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install transformers pandas matplotlib seaborn`
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140).
4. Update the dataset path and run: `python nlp_sentiment_analysis.py`

## Mockup
![Sentiment Analysis](sentiment_analysis.png)