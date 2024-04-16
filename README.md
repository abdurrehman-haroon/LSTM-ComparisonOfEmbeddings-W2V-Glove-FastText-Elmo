# Urdu Sentiment Analysis with Deep Learning Models and Embeddings

This repository contains implementations of various deep learning models for sentiment analysis in Urdu language, along with experiments using different word embeddings for vector representation. The dataset used for this task is the Urdu Sentiment Corpus.

## Dataset
The dataset can be accessed from the following link:
[Urdu Sentiment Corpus](https://github.com/MuhammadYaseenKhan/Urdu-Sentiment-Corpus/blob/master/urdu-sentiment-corpus-v1.tsv)

## Models Implemented
The following sequence-based deep learning models have been implemented for sentiment analysis:
1. Recurrent Neural Network (RNN)
2. Gated Recurrent Unit (GRU)
3. Long Short-Term Memory (LSTM)
4. Bidirectional LSTM (BiLSTM)

## Embeddings Used
The following word embeddings have been experimented with:
1. WordToVec: [Tutorial](https://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/)
2. Glove: [Tutorial](https://medium.com/analytics-vidhya/basics-of-using-pre-trained-glove-vectors-in-python-d38905f356db)
3. Fasttext: [Tutorial](https://blogs.sap.com/2019/07/03/glove-and-fasttext-two-popular-word-vector-models-in-nlp/)
4. Elmo: [Github](https://github.com/HIT-SCIR/ELMoForManyLangs)

## Results
The results of different models with various embeddings are summarized in the following table:

Model       | Accuracy | Precision | Recall   | F1-score |
------------|----------|-----------|----------|----------|
LSTM        | 0.628571 | 0.620000  | 0.539130 | 0.576744 |
LSTM_W2V    | 0.473469 | 0.471311  | 1.000000 | 0.640669 |
LSTM_FT     | 0.461224 | 0.464135  | 0.956522 | 0.625000 |
LSTM_G      | 0.497959 | 0.453488  | 0.339130 | 0.388060 |

These results help in understanding the performance of different models with different embeddings for sentiment analysis in Urdu language.




