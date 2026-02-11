Sentiment Analysis on Swiggy Reviews using RNN
A deep learning project that classifies customer reviews from Swiggy food delivery platform as positive or negative using Recurrent Neural Networks (RNN).
Overview
This project uses TensorFlow to build a Simple RNN model that analyzes customer reviews and predicts sentiment based on text content. The model achieves approximately 72% accuracy on test data.
Technologies

Python 3.x
TensorFlow/Keras
Pandas
NumPy
scikit-learn

Dataset
Swiggy customer reviews dataset containing restaurant information, ratings, food details, delivery time, and customer review text.
Model Architecture

Embedding Layer (5000 words → 16 dimensions)
Simple RNN (64 units, tanh activation)
Dense Layer (1 unit, sigmoid activation)

Installation
bashpip install pandas numpy tensorflow scikit-learn
Usage
python# Load and train the model
python sentiment_analysis.py

# Make predictions
sample_review = "The food was great."
print(predict_sentiment(sample_review))
# Output: Positive (Probability: 0.85)
Results

Test Accuracy: ~72%
Binary Classification (Positive/Negative)
Threshold: 0.5 probability

License
MIT License
