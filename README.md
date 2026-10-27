# Prediction-of-title-paper-Seq2Seq-Attention-Lay
Prediction of title paper Seq2Seq &amp; Attention Lay

seq2seq is a general-purpose encoder-decoder framework for Tensorflow that can be used for Machine Translation, Text Summarization, Conversational Modeling, Image Captioning, and more.

In this notebook, we made a prediction for the title of the paper based on the Abstract, We follow the following steps:

* **Read Data Set**
* **Drop Duplicates and NA values**
* **Text Cleaning**
* **Split Data**
* **Preparing the Tokenizer, sequences & padding**
* **Upload attention Layer**
* **Load libraries**
* **Build the encoder-decoder model**
* **Train the model**
* **Visualize training results**
* **Inference**
* **Test Data and BLUE Score**

# Tech stack
Python · TensorFlow / Keras (LSTM encoder–decoder) · Bahdanau attention · NLTK (BLEU) · Jupyter

# Files
- [`prediction-of-title-paper-seq2seq-attention-lay.ipynb`](prediction-of-title-paper-seq2seq-attention-lay.ipynb) — full pipeline
- [`attention.py`](attention.py) — Bahdanau attention layer used by the decoder

# Usage
Open the notebook in Jupyter, Kaggle or Google Colab, point the data path to an arXiv-style dataset with `abstract` and `title` columns, and run all cells.

# License
MIT
