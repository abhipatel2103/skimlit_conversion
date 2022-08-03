# SkimLit Conversion using Deep Learning and NLP (TensorFlow)

Problem statement

Model takes an abstract of any Reseach Paper and convert it into easily readable format by classifying and formating sequences of the abstract into five categories.

1)Background 2)Objactives 3)Method 4)Conclusion 5) Result


## Method 📜: -
Replicated the deep learning model mentioned in paper : [Deep Learning Model for joint sentence classification in medical paper abstracts.](https://arxiv.org/abs/1710.06071)

## Dataset 📚: -

Data taken from : [PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts.](https://arxiv.org/abs/1710.06071)
Data can be downloaded from github of author : [Link to download dataset](https://github.com/Franck-Dernoncourt/pubmed-rct) 

## Experiment 🧪: -
Total 5 Experiments is implemented which are list below: -

1) model 0: Baseline model - TFIDF + Naive Bayes

2) model 1: custom token embeddings (TensorFlow Embedding Layer)

3) model 2: pretrained token embeddings (Universal Sentence Encoder, TensorFlow-hub)

4) model 3: custom Character embeddings (TensorFlow Embedding Layer)

5) model 4: Multi-input model (Token + Character Embedding)

6) model 5: Multi-input model (Positional Embedding + Token-char Embedding)


## Required Libraries

The following libraries are required to be installed in the machine to run the python scripts. 
pip3 install tensorflow numpy pandas  seaborn keras 


## Run file
skimlit_nlp.ipynb


