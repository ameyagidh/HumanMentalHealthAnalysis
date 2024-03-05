# Human Mental Health Analysis

This repository contains code for classifying the severity of Reddit posts related to mental health using LSTM (Long Short-Term Memory) neural networks. The severity classification is based on the topics discussed in the posts, focusing on subreddits such as depression, anxiety, and suicide watch.

## Overview
The project aims to automatically classify the severity of Reddit posts based on the topics discussed within them. It involves the following steps:

### 1. Data Preprocessing
The raw Reddit posts undergo preprocessing, including text cleaning, stop-word removal, and lemmatization to prepare them for analysis.

### 2. Topic Modeling
Topic modeling techniques such as Latent Dirichlet Allocation (LDA) are employed to extract key topics from the Reddit posts, providing insights into the prevalent themes.

### 3. Data Preparation
The preprocessed data is split into training and testing sets. Word tokens and tags are converted into integers, and padding is applied to ensure uniform input sizes for the LSTM model.

### 4. Model Building
An LSTM neural network model is constructed using Keras, a high-level neural networks API. The model is trained on the training data to learn patterns for severity classification.

### 5. Model Evaluation
The trained model's performance is evaluated using the test data, with metrics such as accuracy computed to assess its effectiveness in classifying the severity of Reddit posts.

## Requirements
- Python 3
- TensorFlow
- Keras
- Gensim
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Usage
1. Clone the repository:
```
git clone [https://github.com/yourusername/repo.git](https://github.com/ameyagidh/HumanMentalHealthAnalysis.git)
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the main script to preprocess data, build the LSTM model, and train it:
```
python main.py
```
4. Evaluate the model's performance and visualize results using the provided Jupyter Notebook:
```
jupyter notebook
```

## Results
The trained model achieves an accuracy of X% on the test dataset, demonstrating its effectiveness in classifying the severity of Reddit posts related to mental health.

## Future Improvements
- Explore advanced text preprocessing techniques to further enhance data quality and model performance.
- Incorporate additional features such as user metadata or post engagement metrics for more comprehensive severity classification.
