# KerasDemonstration
The purpose of this notebook is to highlight my competence with Keras and TensorFlow. I complete 3 short projects in the notebook:

1. Titanic dataset on Kaggle using a basic feed forward Sequential model. I scored 75.12% accuarcy, which is 3 points up from my previous attempt without using neural networks
2. Handwritten Digit Recognizer using Convolution Neural Networks. I scored 98.18% accuracy, which is 2 points up from my previous attempt without neural nets.
3. Dota 2 Last Pick Predictor. Dota 2 is a competetive online game that starts with a 'draft' in which 20 picks are made sequentially. I used a LSTM model to try to predict the last pick of the draft given the first 19 picks. This is challenging data to work with since picks are often random and there is a lot of noise. There are 113 different possible outcomes. I used a metric of top-10 accuracy. When compared to a baseline of random guess of 8% and always guessing the top 10 most popular heroes at 23%, I was able to score 30.7% using LSTM and no additional feature engineering.

Notebook cleaning and better markdown to come.
