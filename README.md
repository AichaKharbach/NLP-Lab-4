### Lab 4 Overview

This lab focuses on familiarizing with various NLP models using the PyTorch library. The lab is divided into three main parts:

### Part 1: Classification Regression

- **Objective**: Scrape Arabic text data, preprocess it, and train models to perform classification regression.
- **Tasks**:
  1. Use Scrapy or BeautifulSoup to collect Arabic text data.
  2. Preprocess the data using tokenization, stemming, lemmatization, and discretization.
  3. Train models using RNN, Bidirectional RNN, GRU, and LSTM architectures.
  4. Evaluate the models using standard metrics and BLEU score.

### Part 2: Transformer (Text Generation)

- **Objective**: Fine-tune a pre-trained GPT-2 model and generate text.
- **Tasks**:
  1. Install `pytorch-transformers` and load the GPT-2 model.
  2. Fine-tune the GPT-2 model on a custom dataset.
  3. Generate text based on a given input sentence.

### Part 3: BERT

- **Objective**: Use a pre-trained BERT model for text classification.
- **Tasks**:
  1. Load and adapt the `bert-base-uncased` model.
  2. Prepare the dataset from the Amazon review dataset available [here](https://nijianmo.github.io/amazon/index.html).
  3. Fine-tune and train the BERT model.
  4. Evaluate the model using accuracy, loss, F1 score, and other relevant metrics.
  5. Provide a general conclusion on the use of the pre-trained BERT model.

## Tools

- Google Colab or Kaggle
- GitLab/GitHub
- SpaCy, NLTK, PyTorch

## Additional Resources

- [GPT-2 Fine-tuning Tutorial](https://gist.github.com/mf1024/3df214d2f17f3dcc56450ddf0d5a4cd7)
