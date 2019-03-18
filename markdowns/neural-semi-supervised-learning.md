# Awesome Neural Semi-Supervised Learning

A curated list of resources for Neural Semi-Supervised Learning (NSSL). The choice of what I have initially include was subjectively made based on what I have come across and my research interests. Additionally, some of the subtopics may overlap with related areas such as domain adaptation and transfer learning. If you have any questions or want to contribute to this list to make it more comprehensive, please feel free to email me at alexander.fabbri@yale.edu. 

## Table of Contents

- [Blogs / Tutorials / Surveys / Code](#tutorials)
- [Papers](#papers)
  - [Generative Models](#generative-models)
  - [Pretraining for NLP](#pretraining-for-nlp)
  - [Additional NLP Applicadtions](#additional-nlp-applications)
  - [Miscellaneous](#miscellaneous)

## Tutorials
#### Semi-Supervised Learning
* [Awesome Semi-Supervised Learning](https://github.com/jason718/awesome-self-supervised-learning)
* [A Simple Explanation of Semi-Supervised Learning and Pseudo-Labeling](https://towardsdatascience.com/simple-explanation-of-semi-supervised-learning-and-pseudo-labeling-c2218e8c769b)
* [An overview of proxy-label approaches for semi-supervised learning](http://ruder.io/semi-supervised/)
* [Semi-Supervised Learning and GANS](https://towardsdatascience.com/semi-supervised-learning-and-gans-f23bbf4ac683)
* [Introduction to Semi-Supervised Learning with Ladder Networks](http://rinuboney.github.io/2016/01/19/ladder-network.html)
#### Semi-Supervised Learning for NLP
* [Semi-Supervised Learning for NLP](https://web.stanford.edu/class/cs224n/lectures/lecture17.pdf)
* [Unsupervised machine translation: A novel approach to provide fast, accurate translations for more languages](https://code.fb.com/ai-research/unsupervised-machine-translation-a-novel-approach-to-provide-fast-accurate-translations-for-more-languages/)
* [Semi-Supervised Pytorch](https://github.com/wohlert/semi-supervised-pytorch)
## Papers
#### Generative Models
* [Semi-supervised Learning with Deep Generative Models](https://arxiv.org/pdf/1406.5298.pdf) (2014) **[CODE](https://github.com/wohlert/semi-supervised-pytorch)**
* [Semi-Supervised Learning with Ladder Networks](https://arxiv.org/pdf/1507.02672.pdf) (2015) **[CODE](https://github.com/CuriousAI/ladder)**
* [Adversarial Autoencoders](https://arxiv.org/pdf/1511.05644.pdf) (2015)
* [Ladder Variational Autoencoders](http://papers.nips.cc/paper/6275-ladder-variational-autoencoders)  (2016) **[CODE](https://github.com/casperkaae/LVAE)**
* [Learning Loss Functions for Semi-supervised Learning via Discriminative Adversarial Networks](https://lld-workshop.github.io/papers/LLD_2017_paper_38.pdf) (2017)



#### Pretraining for NLP
* [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf) (2013)
* [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/pdf/1310.4546.pdf) (2013)
* [Semi-supervised Sequence Learning](https://arxiv.org/pdf/1511.01432.pdf) (2015)
* [Learned in Translation: Contextualized Word Vectors](https://arxiv.org/pdf/1708.00107.pdf) (2018)  **[CODE](https://github.com/salesforce/cove)**
* [Deep contextualized word representations](https://arxiv.org/pdf/1802.05365.pdf) (2018) **[HOW TO](https://github.com/allenai/allennlp/blob/master/tutorials/how_to/elmo.md)**
* [Universal Language Model Fine-tuning for Text Classification](https://arxiv.org/pdf/1801.06146.pdf) (2018) **[CODE](https://github.com/fastai/fastai/tree/master/courses/dl2/imdb_scripts)**
* [Improving Language Understanding by Generative Pre-Training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) (2018) **[CODE](https://github.com/openai/finetune-transformer-lm)**
* [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf) (2018) **[CODE](https://github.com/google-research/bert)**
* [Unsupervised Neural Multi-Document Abstractive Summarization](https://arxiv.org/pdf/1810.05739.pdf) (2018)

#### Additional NLP Applications
* [Semi-Supervised Learning for Neural Machine Translation](https://arxiv.org/pdf/1606.04596.pdf) (2016)
* [Adversarial Training Methods for Semi-Supervised Text Classification](https://arxiv.org/pdf/1605.07725.pdf) (2017) **[CODE](https://github.com/tensorflow/models/tree/master/research/adversarial_text)**
* [Semi-Supervised QA with Generative Domain-Adaptive Nets](https://arxiv.org/pdf/1702.02206.pdf) (2017)
* [Semi-Supervised Sequence Modeling with Cross-View Training](https://arxiv.org/pdf/1809.08370.pdf) (2018) **[CODE](https://github.com/tensorflow/models/tree/master/research/cvt_text)**
* [Strong Baselines for Neural Semi-supervised Learning under Domain Shift](https://arxiv.org/pdf/1804.09530.pdf) (2018) **[CODE](https://github.com/bplank/semi-supervised-baselines)**
* [Injecting Relational Structural Representation in Neural Networks for Question Similarity](https://arxiv.org/pdf/1806.08009.pdf)  (2018)
* [Semi-Supervised Learning for Neural Keyphrase Generation](https://arxiv.org/pdf/1808.06773.pdf) (2018)
* [Toward Controlled Generation of Text](https://arxiv.org/pdf/1703.00955.pdf) (2018) **[CODE](https://github.com/asyml/texar/tree/master/examples/text_style_transfer)**
* [Phrase-Based & Neural Unsupervised Machine Translation](https://arxiv.org/pdf/1804.07755.pdf) (2018) **[CODE](https://github.com/facebookresearch/UnsupervisedMT)**

#### MISC
* [Deep Learning via Semi-Supervised Embedding](http://www.thespermwhale.com/jaseweston/papers/deep_embed.pdf) (2008)
* [Pseudo-Label : The Simple and Efficient Semi-Supervised Learning Method for Deep Neural Networks](http://deeplearning.net/wp-content/uploads/2013/03/pseudo_label_final.pdf) (2013)
* [SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS](https://arxiv.org/pdf/1609.02907.pdf) (2017) **[CODE](https://github.com/tkipf/gcn)**
* [Temporal Ensembling for Semi-Supervised Learning](https://arxiv.org/pdf/1610.02242.pdf) (2017)  **[CODE](https://github.com/smlaine2/tempens)**
* [Realistic Evaluation of Deep Semi-Supervised Learning Algorithms](https://arxiv.org/pdf/1804.09170.pdf)  (2018)  **[CODE](https://github.com/brain-research/realistic-ssl-evaluation)**
* [Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning](https://arxiv.org/pdf/1704.03976.pdf) (2018) **[CODE](https://github.com/takerum/vat_tf)**

