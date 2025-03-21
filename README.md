# Movie_sentiment_Analysis

This project is a deep learning-based sentiment analysis model trained to classify movie reviews as positive or negative. It uses an LSTM (Long Short-Term Memory) network with an Embedding layer for text representation.

### Features

Pretrained word embeddings to convert text into vector representations.

LSTM model to capture sequential dependencies in text.

Binary classification (Positive vs. Negative sentiment).

Trained on IMDB movie reviews dataset.

### Dataset

The model is trained using the IMDB dataset available on Kaggle.
To download -: 
```
 !kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
```

Then, extract:
```
!unzip imdb-dataset-of-50k-movie-reviews.zip -d ./imdb_data
```

### Improvements

Implement Bidirectional LSTM for better context understanding.

Fine-tune pretrained word embeddings like GloVe or Word2Vec.

Add attention mechanism for improved feature importance weighting.
