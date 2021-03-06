# Natural-Language-Processing

State-of-the-art NLP principles and methods for toxic comment classification<br />
The links below display the above notebooks via nbviewer, because Github sometimes fails to display .ipynb-files properly. 



### Data preparation:
* [Basic NLP-Preprocessing Techniques (Python Code Snippets) ](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Data_Preparation.ipynb)<br />
* [Data Exploration - Quora Kaggle Competition](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Data_Exploration.ipynb)

## Modeling:
* [Custom Keras NN-Model](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Finaler_Prototyp.ipynb) 
* [ELMO via TensorflowHub showcase for the Quora Dataset](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Transfer_Learning_ELMO_mit_TensorflowHub.ipynb)
   * *Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, Luke Zettlemoyer. [Deep contextualized word representations](https://arxiv.org/abs/1802.05365). arXiv preprint arXiv:1802.05365, 2018.*
* [BERT via TensorflowHub showcase for the Quora Dataset](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Transfer%20Learning_BERT_mit_TensorflowHub.ipynb)
  * *Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova: ["BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"](https://arxiv.org/abs/1810.04805), 2018.*
* [XLNET with SpaCy-Pytorch Transformers showcase for the Quora Dataset](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Transfer%20Learning_XLNet_mit_SpaCy.ipynb)
  * *Zhilin Yang and Zihang Dai and Yiming Yang and Jaime Carbonell and Ruslan Salakhutdinov and Quoc V. Le.[XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237). arXiv preprint arXiv:1906.08237, 2019*
* [BERT with SpaCy-Pytorch-Transformers showcase for the Quora Dataset](https://nbviewer.jupyter.org/github/TheWoops/Natural-Language-Processing/blob/master/Transfer%20Learning_BERT_mit_%20SpaCy.ipynb)
  * *Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova: ["BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"](https://arxiv.org/abs/1810.04805), 2018.*

## Resources

* #### Deep Learning 
  * https://www.d2l.ai/chapter_attention-mechanism/attention.html
  * https://course.fast.ai/index.html
  * http://nlp.fast.ai/category/classification.html GREAT!
  * https://en.d2l.ai/d2l-en.pdf

* #### NLP
  * ##### Preprocessing & Embeddings
    * [SpaCy Cheatsheet](http://datacamp-community-prod.s3.amazonaws.com/29aa28bf-570a-4965-8f54-d6a541ae4e06)
    * [SpaCy Matcher](https://github.com/explosion/spaCy/blob/master/website/docs/usage/rule-based-matching.md) and [Matcher Demo](https://explosion.ai/demos/matcher)
    * http://textmining.wp.hs-hannover.de/Preprocessing.html respectively http://textmining.wp.hs-hannover.de/tutorials.html
    * [Nice Article about Embeddings and Language Models](https://towardsdatascience.com/from-word-embeddings-to-pretrained-language-models-a-new-age-in-nlp-part-2-e9af9a0bdcd9)
  * ##### Modeling
    * https://github.com/explosion/spacy-pytorch-transformers (spaCy pipelines for BERT, XLNet and GPT-2)
    * [How to Fine Tune BERT](https://arxiv.org/pdf/1905.05583.pdf)
  * ##### Evaluation
    * [AI Fairness 360 - Bias, Fairness Testing](https://github.com/IBM/AIF360)
    
  * ##### NLP:  [nltk book](http://www.nltk.org/book/) and [nlp.stanford 1](https://web.stanford.edu/~jurafsky/slp3/) / [nlp.standford 2](https://nlp.stanford.edu/fsnlp/)


* #### State-of-the-Art Approaches (Paper Overview)
  * http://www.arxiv-sanity.com/ (AI-papers  in general)
  * https://www.aclweb.org/anthology (papers on the study of computational linguistics and NLP)
  * https://github.com/sebastianruder/NLP-progress/blob/master/english/sentiment_analysis.md
  * https://github.com/keon/awesome-nlp#research-summaries-and-trends
  
## Natural Language Processing

*Libraries for working with human languages.*

- General
    * [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modeling for Humans.
    * [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
    * [nltk](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
    * [pattern](https://github.com/clips/pattern) - A web mining module for the Python.
    * [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages.
    * [pytext](https://github.com/facebookresearch/pytext) - A natural language modeling framework based on PyTorch.
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - A toolkit enabling rapid deep learning NLP prototyping for research.
    * [spacy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
    * [stanfordnlp](https://github.com/stanfordnlp/stanfordnlp) - The Stanford NLP Group's official Python library, supporting 50+ 
    * [flair](https://github.com/zalandoresearch/flair) - library for state-of-the-art NLP by zalandoresearch
    * [fastai](https://github.com/fastai/fastai) - well documented NLP library for transfer learning
      * [fastai V2 latest paper](https://arxiv.org/pdf/2002.04688)
