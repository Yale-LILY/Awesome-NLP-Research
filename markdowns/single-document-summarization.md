# Awesome Single Document Summarization

A curated list of resources for Single Document Summarization. The GitHub repository link is [here](https://github.com/tanyichern/awesome-summ).

## Contributing
Please feel free to email Yi Chern Tan (yichern.tan *at* yale.edu)

## Table of Contents

- [Tutorials and Blogs](#tutorials-and-blogs)
- [Papers](#papers)
  - [Metrics](#metrics)
  - [Classical Methods](#classical-methods)
  - [Extractive Methods](#extractive-methods)
  - [Abstractive Methods](#abstractive-methods)
  - [Hybrid and Other Methods](#hybrid-and-other-methods)
- [Other Papers](#other-papers)
  - [Sentence Compression](#sentence-compression)
  - [Code Summarization](#code-summarization)
- [Datasets](#datasets)

## Tutorials and Blogs
* Text Summarization with Gensim[[link](https://rare-technologies.com/text-summarization-with-gensim/)]
* How to Prepare News Articles for Text Summarization[[link](https://machinelearningmastery.com/prepare-news-articles-text-summarization/)]
* LEX-Rank and Textrank based document summarization system (Interactive tutorial + Java code)[[link](https://www.linkedin.com/pulse/lex-rank-textrank-based-document-summarization-system-niraj-kumar/)]
* Text summarization with TensorFlow[[link](https://ai.googleblog.com/2016/08/text-summarization-with-tensorflow.html?m=1)]
* Text Summarization in Python: Extractive vs. Abstractive techniques revisited[[link](https://rare-technologies.com/text-summarization-in-python-extractive-vs-abstractive-techniques-revisited/)]
* How to Run Text Summarization with TensorFlow[[link](https://hackernoon.com/how-to-run-text-summarization-with-tensorflow-d4472587602d)]
* Taming Recurrent Neural Networks for Better Summarization[[link](http://www.abigailsee.com/2017/04/16/taming-rnns-for-better-summarization.html)]

## Papers

### Metrics
* Automatic Evaluation of Summaries Using N-gram Co-Occurrence Statistics (HLT-NAACL 2003)[[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/naacl2003.pdf)]
* ROUGE: A Package for Automatic Evaluation of Summaries (ACL 2004)[[paper](http://www.aclweb.org/anthology/W04-1013)][[code](https://pypi.org/project/pyrouge/)]
* METEOR: An Automatic Metric for MT Evaluation with Improved Correlation with Human Judgments (ACL 2005)[[paper](https://www.cs.cmu.edu/~alavie/papers/BanerjeeLavie2005-final.pdf)][[code](https://www.cs.cmu.edu/~alavie/METEOR/README.html)]
* Automated Summarization Evaluation with Basic Elements[[paper](https://www.semanticscholar.org/paper/Automated-Summarization-Evaluation-with-Basic-Hovy-Lin/45fc709a2fb8cd3cc71462c65e3d5e1bcb23c444)]
* Automated Pyramid Scoring of Summaries using Distributional Semantics (ACL 2013)[[paper](https://pdfs.semanticscholar.org/67fc/461fac073d0669f5a56ec96f9df35e050429.pdf)][[code](https://github.com/six5532one/automate-pyramid-method)]
* Better Summarization Evaluation with Word Embeddings for ROUGE (EMNLP 2015)[[paper](https://arxiv.org/abs/1508.06034)][[code](https://github.com/ng-j-p/rouge-we)]
* A semantically motivated approach to compute ROUGE scores (EMNLP 2018)[[paper](https://arxiv.org/abs/1710.07441)]
* Summarization Evaluation in the Absence of Human Model Summaries Using the Compositionality of Word Embeddings (COLING 2018)[[paper](http://aclweb.org/anthology/C18-1077)][[code]()]
* A Graph-theoretic Summary Evaluation for ROUGE (ACL 2018)[[paper](http://aclweb.org/anthology/D18-1085)][[code]()]

### Classical Methods
* The Use of MMR, Diversity-Based Reranking for Reordering Documents and Producing Summaries (SIGIR 1998)[[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.188.3982&rep=rep1&type=pdf)]
* TextRank: Bringing Order into Texts (EMNLP 2004)[[paper](https://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf)][[code](https://github.com/summanlp/textrank)]
* LexRank: Graph-based Lexical Centrality as Salience in Text Summarization (AAAI 2004)[[paper](https://www.aaai.org/Papers/JAIR/Vol22/JAIR-2214.pdf)][[code](https://cran.r-project.org/web/packages/lexRankr/index.html)][[code](https://github.com/jtan25/LexRank)]
* A Study of Global Inference Algorithms in Multi-Document Summarization (ECIR 2007)[[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.94.4583&rep=rep1&type=pdf)]
* A Class of Submodular Functions for Document Summarization (ACL 2011)[[paper](http://www.aclweb.org/anthology/P11-1052)]

### Extractive Methods
* Neural Summarization by Extracting Sentences and Words (ACL 2016)[[paper](https://arxiv.org/pdf/1603.07252)][[code](https://github.com/cheng6076/NeuralSum)]
* SummaRuNNer: A Recurrent Neural Network based Sequence Model for Extractive Summarization of Documents (AAAI 2017)[[paper](https://arxiv.org/pdf/1611.04230.pdf)][[code](https://github.com/hpzhao/SummaRuNNer)]
* Neural Document Summarization by Jointly Learning to Score and Select Sentences (ACL 2018)[[paper](http://aclweb.org/anthology/P18-1061)][[code](https://github.com/magic282/NeuSum)]
* Ranking Sentences for Extractive Summarization with Reinforcement Learning (NAACL 2018)[[paper](http://aclweb.org/anthology/N18-1158)][[code](https://github.com/EdinburghNLP/Refresh)]
* Learning to Extract Coherent Summary via Deep Reinforcement Learning (AAAI 2018)[[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16838/16118)]
* Extractive Summarization with SWAP-NET: Sentences and Words from Alternating Pointer Networks (ACL 2018)[[paper](http://aclweb.org/anthology/P18-1014)][[code]()]

### Abstractive Methods
* Abstractive Text Summarization using Sequence-to-sequence RNNs and Beyond (CoNLL 2016)[[paper](http://www.aclweb.org/anthology/K16-1028)][[code](https://github.com/alesee/abstractive-text-summarization)]
* Incorporating Copying Mechanism in Sequence-to-Sequence Learning (ACL 2016)[[paper](http://aclweb.org/anthology/P16-1154)][[code](https://github.com/lspvic/CopyNet)]
* Get To The Point: Summarization with Pointer-Generator Networks (ACL 2017)[[paper](https://arxiv.org/pdf/1704.04368.pdf)][[code](https://github.com/abisee/pointer-generator)]
* Bottom-Up Abstractive Summarization (EMNLP 2018)[[paper](https://arxiv.org/abs/1808.10792)][[code](https://github.com/sebastianGehrmann/bottom-up-summary)]
* Improving Neural Abstractive Document Summarization with Structural Regulation (EMNLP 2018)[[paper](http://aclweb.org/anthology/D18-1441)]
* Deep Communicating Agents for Abstractive Summarization (ACL 2018)[[paper](http://aclweb.org/anthology/N18-1150)]
* On the Abstractiveness of Neural Document Summarization (EMNLP 2018)[[paper](http://aclweb.org/anthology/D18-1089)]
* Improving Abstraction in Text Summarization (EMNLP 2018)[[paper](http://aclweb.org/anthology/D18-1207)]
* Generative Adversarial Network for Abstractive Text Summarization (AAAI 2018)[[paper](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16238/16492)][[code](https://github.com/iwangjian/textsum-gan)]
* A Discourse-Aware Attention Model for Abstractive Summarization of Long Documents (NAACL 2018)[[paper](http://aclweb.org/anthology/N18-2097)][[code](https://github.com/acohan/long-summarization)]

### Hybrid and Other Methods
* Guiding Generation for Abstractive Text Summarization based on Key Information Guide Network (NAACL 2018)[[paper](http://aclweb.org/anthology/N18-2009)]
* Abstractive Document Summarization with a Graph-Based Attentional Neural Model (ACL 2018)[[paper](http://aclweb.org/anthology/P17-1108)][[code](https://github.com/tanjiwei/summ)]
* Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting (ACL 2018)[[paper](http://aclweb.org/anthology/P18-1063)][[code](https://github.com/ChenRocks/fast_abs_rl)]
* Structured Neural Summarization (pending review)[[paper](https://arxiv.org/pdf/1811.01824.pdf)]

## Other Papers

### Sentence Compression
* A Neural Attention Model for Sentence Summarization (ACL 2015)[[paper](https://www.aclweb.org/anthology/D/D15/D15-1044.pdf)][[code](https://github.com/facebookarchive/NAMAS)]
* Sentence Compression by Deletion with LSTMs (ACL 2015)[[paper](http://aclweb.org/anthology/D15-1042)]
* Abstractive Sentence Summarization with Attentive Recurrent Neural Networks (ACL 2016)[[paper](http://aclweb.org/anthology/N16-1012)]
* Can Syntax Help? Improving an LSTM-based Sentence Compression Model for New Domains (ACL 2017)[[paper](http://www.aclweb.org/anthology/P17-1127)]
* A Language Model based Evaluator for Sentence Compression (ACL 2018)[[paper](https://aclweb.org/anthology/P18-2028)][[code](https://github.com/code4conference/code4sc)]

### Code Summarization
* Learning to Represent Programs with Graphs (ICLR 2018)[[paper](https://arxiv.org/abs/1711.00740)]
* code2seq: Generating Sequences from Structured Representations of Code (pending review)[[paper](https://arxiv.org/abs/1808.01400)]
* Structured Neural Summarization (pending review)[[paper](https://arxiv.org/pdf/1811.01824.pdf)]

## Datasets
* Spreadsheet of Summarization Corpora[[link](https://docs.google.com/spreadsheets/d/1b1-NpM1jDK7KVHd_CwrxhpNZ1zAE8m-7M0pZ0gfZTMQ/edit#gid=0)]
* DUC[[data](https://www-nlpir.nist.gov/projects/duc/data.html)]
* TAC[[data](https://tac.nist.gov/data/index.html)]
* Gigaword[[data](https://catalog.ldc.upenn.edu/LDC2003T05)]
* Scientific Summarization[[data](https://github.com/WING-NUS/scisumm-corpus)]
* Live Blogs[[data](https://arxiv.org/abs/1802.09884v1)]
* Legal Cases[[data](https://archive.ics.uci.edu/ml/datasets/Legal+Case+Reports)]
* BBC News Summary[[data](https://www.kaggle.com/sunnysai12345/news-summary)]
* Opinosis[[data](http://kavita-ganesan.com/opinosis-opinion-dataset/#.XBJs8i2p22U)]
* Wikihow[[data](https://github.com/mahnazkoupaee/WikiHow-Dataset)]
* Sentence Compression[[data](https://github.com/google-research-datasets/sentence-compression)]
* Method2Name[[code](https://github.com/mast-group/convolutional-attention)]
* Method2Doc[[code](https://github.com/EdinburghNLP/code-docstring-corpus)]
