## 02456 Deep Learning - Natural Language Processing

***Authors: Julie Maria Petersen & Lise Styve*** <br /> <br />

### Word-Level Language Modelling Using an LSTM Neural Network

***Abstract*** <br /> <br />

In this paper, word-level language modelling is considered with a simple objective, which is predicting the next word given the previous words within some text. This Natural Language Processing (NLP) task is approached with supervised learning using a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) cells. The model is sought optimized and regularized using weight decay and dropout. A validation perplexity of 88.2 is achieved on the task specific data set Penn Treebank (PTB). When trained on other data sets, the language model enables to adapt to the style and content of the conditioning text, however the generated sequences are not sufficiently realistic and coherent. This can be due to a continued need for regularization and larger amounts of data.

***Introduction*** <br /> <br />

Language models have increased in importance as they continuously improve performance in NLP tasks, e.g. by generating coherent and human-like pieces of text. They are used for many purposes such as machine translation, summarization, spelling correction and in text generation which is the area of interest in this paper. RNN’s are especially popular for this task and have been used to generate text in several different domains.
The objective of this paper was to build a word-level LSTM language model that when trained on textual data was able to generate similar text sequences. This was sought accomplished with inspiration from previous research in the field.
