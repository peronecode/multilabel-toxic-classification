# Multi-label Toxic Comment Classification
## Overview
This project aims to build a multi-label toxic comment classification model using a neural network with LSTM layers. The model is trained on a dataset of comments with labels such as toxic, severe_toxic, obscene, threat, insult, and identity_hate. The primary goal is to identify and classify toxic comments with multiple labels.

Check the entire explanation and results in [this Medium post](https://medium.com/@luccas.perone/multi-label-toxic-comment-classification-ad884a0745b0).

## Instructions
These are the requirements to run the Python code.<br>
The project depends on the GloVe pre-trained weights.<br>
You can download it using the script or manually if preferred.<br><br>
PS: _You also can find the same script on Notebook file._

    git clone https://github.com/peronecode/multilabel-toxic-classification.git
    cd multilabel-toxic-classification
    unzip data.zip
    wget https://nlp.stanford.edu/data/glove.6B.zip
    unzip -p glove.6B.zip glove.6B.100d.txt > data/glove.6B.100d.txt

## Python - Used Libraries
- Python 3.6+
- matplotlib==3.7.1
- seaborn==0.12.2
- pandas==2.0.1
- nltk==3.8.1
- swifter==1.3.4
- tensorflow==2.12.0

## File Desction
- **requirements.txt** - Py installation requirements
- **toxic.ipynb** - Jupyter Notebook containing all the code
- **toxic.html** - Html version of the Notebooks - Easy read
- **data.zip** - Toxic comments datasets

## Licensing, Author and Acknowledgements
- Author: [Luccas Perone](https://github.com/peronecode)
- License: [MIT License](https://opensource.org/license/mit/)
- Data Source: [Toxic Comment Classification Challenge - Data](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data)
- Pre-Trained Embedding Weights: [GloVe](https://nlp.stanford.edu/projects/glove/)