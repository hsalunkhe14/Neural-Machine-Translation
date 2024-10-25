# Neural Machine Translation with Attention

## Description
This project implements a sequence-to-sequence Neural Machine Translation (NMT) model using an encoder-decoder architecture with attention mechanisms. Utilizing LSTM networks, the model translates sentences from Spanish to English. The project was developed for ESE 577: Deep Learning Algorithms and Software at Stony Brook University during Spring 2024.

## Dataset
The dataset, "spa-eng," contains parallel text data in Spanish and English. It is publicly available at [TensorFlow Dataset](http://storage.googleapis.com/download.tensorflow.org/data/spa-eng.zip).

## Technologies Used
- **Python:** Core programming language
- **TensorFlow and Keras:** For model building and training
- **NumPy:** For data manipulation
- **Scikit-learn:** For data splitting

## Features
- **Data Cleaning:** Removes punctuation and normalizes text to lowercase.
- **Tokenization:** Converts text to sequences of tokens.
- **Word Embedding:** Uses CBOW model for mapping tokens to vectors.
- **Attention Mechanism:** Improves model focus on relevant parts of the input sequence.
- **LSTM Networks:** Utilized for both encoder and decoder layers.

## Model Architecture
The model comprises two main components: an encoder and a decoder with LSTM layers, supplemented by an attention layer to enhance translation accuracy by focusing on relevant input parts for each output step.

## Results
The model achieves approximately 80% accuracy on unseen test data. It translates Spanish sentences to English with reasonable accuracy, considering context and grammar.

## Future Work
- **Improving Generalization:** Integrate dropout layers to mitigate overfitting.
- **Expanding Dataset:** Increase the dataset size to improve model robustness.

## References
- Deep Learning by Ian Goodfellow, et al., MIT Press, 2016.
- Various academic papers and online resources on neural machine translation and word embeddings.
