
# Stock Sentiment Analysis using headlines

Begginer project to understand concepts of NLP.

### Project Overview:

This project in sentiment analysis on stock market data using news headlines is done with the goal of predicting which sentiment label—positive or negative—corresponds to each day according to headlines that help to gauge market movements.

### Project Structure

The project consists of the following key components:

- Data Preprocessing: Clean and prepare the dataset for analysis.
- Feature Engineering: Create Bag of Words (BoW) representation from the headlines using bigrams.
- Modeling: Train a RandomForestClassifier on the preprocessed data.
- Evaluation: Evaluate model performance using a confusion matrix, accuracy score, and classification report.

### Dataset
The dataset used contains daily news headlines with corresponding sentiment labels (0 or 1). It includes:

- Date: The date the headlines were published.
- Headlines: Multiple columns containing the headlines for each day.
- Label: The sentiment label indicating the market sentiment (0 for negative, 1 for positive)

### Libraries Used
- nltk: For natural language processing tasks.
- pandas: For data manipulation and analysis.
- sklearn: For machine learning modeling and evaluation.
- CountVectorizer: For creating the Bag of Words representation.

### How to Run the Project
- Clone the repository.
- Install the required libraries using:
```javascript
pip install pandas scikit-learn nltk
```
- Place your dataset in the ***./Data.csv*** file path.
- Run the Python script to see the model predictions and evaluation metrics:
```javascript
python stock_sentiment_analysis.py
```