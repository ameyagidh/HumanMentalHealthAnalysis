# Human Mental Health Analysis

This repository contains code for classifying the severity of Reddit posts using LSTM (Long Short-Term Memory) neural networks. The severity classification is based on the topics discussed in the posts, focusing on mental health-related subreddits such as depression, anxiety, and suicide watch.

Overview
The project aims to automatically classify the severity of Reddit posts based on the topics discussed within them. It involves the following steps:

Data Preprocessing: The raw Reddit posts are preprocessed, including text cleaning, stop-word removal, and lemmatization.

Topic Modeling: Topic modeling techniques such as Latent Dirichlet Allocation (LDA) are used to extract topics from the Reddit posts.

Data Preparation: The preprocessed data is split into train and test sets. Word tokens and tags are converted into integers, and padding is applied to ensure uniform input sizes.

Model Building: An LSTM neural network model is constructed using Keras, a high-level neural networks API. The model is trained on the training data to learn the severity classification patterns.

Model Evaluation: The trained model's performance is evaluated using the test data, and metrics such as accuracy are computed to assess its effectiveness.

Requirements
Python 3
TensorFlow
Keras
Gensim
NLTK
Pandas
NumPy
Matplotlib
Seaborn
Usage
Clone the repository:
bash
Copy code
git clone [https://github.com/yourusername/repo.git](https://github.com/ameyagidh/HumanMentalHealthAnalysis.git)
Install the required dependencies:
Copy code
pip install -r requirements.txt
Run the main script to preprocess data, build the LSTM model, and train it:
css
Copy code
python main.py
Evaluate the model's performance and visualize results using the provided Jupyter Notebook:
Copy code
jupyter notebook
Results
The trained model achieves an accuracy of X% on the test dataset, demonstrating its effectiveness in classifying the severity of Reddit posts.

Future Improvements
Explore more advanced text preprocessing techniques to further enhance data quality.
Incorporate additional features such as user metadata or post engagement metrics for better classification.
