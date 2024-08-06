# Sentiment-Analysis-of-App-Reviews-using-DistilBERT
## Overview
This project focuses on developing a sentiment analysis model to classify app reviews from the Google Play Store. Utilizing the DistilBERT model, the project aims to achieve efficient and accurate sentiment classification. The model is optimized for performance on CPU-only environments, leveraging advanced NLP techniques and the PyTorch deep learning framework.

## Dataset
The dataset consists of 6000 app reviews, each with around 150 tokens. The reviews are labeled with sentiment scores ranging from 1 to 5. For the purpose of classification, these scores can be mapped to positive, neutral or negative sentiments. The dataset is split into training, validation, and test sets.

## Obtaining the Dataset
The dataset was collected using web scraping techniques from the Google Play Store. The google-play-scraper Python package was used to scrape app reviews, which were then preprocessed and labeled for sentiment analysis.

## Features
- Data Collection: Reviews collected from multiple applications on the Google Play Store.
- Data Preprocessing: Cleaned and tokenized text data for efficient model training.
- Model Implementation: Utilized DistilBERT for sentiment analysis, implemented with PyTorch.
- Performance Optimization: Techniques to ensure the model runs efficiently on CPU-only environments.
- Evaluation: Achieved high accuracy in sentiment classification.

## Usage
Follow these steps to use the sentiment analysis model:

- Collect Reviews: The project includes scripts to collect app reviews from the Google Play Store using the google-play-scraper library.
- Preprocess Data: Preprocess the collected reviews using the provided data cleaning and tokenization scripts.
- Train Model: Train the DistilBERT model using the preprocessed data.
- Evaluate Model: Evaluate the model's performance on a test dataset.
- Get Predictions: Use the trained model to predict the sentiment of new reviews.
  
## Results
- Accuracy: Achieved high accuracy in classifying the sentiment of app reviews.
- Evaluation Metrics: Precision, recall, and F1 score used to validate model performance.
- Inference Speed: Optimized for fast inference on CPU-only environments, suitable for large-scale deployment.

## Source Code
The source code for this project is maintained in a private repository. For access, please contact kmahali2@asu.edu.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any bugs, feature requests, or improvements.
