# Awesome Cross-lingual Information Retrieval

A curated list of resources for Cross-lingual Information Retrieval (CLIR).

## Contributing
Please feel free to email Rui Zhang (r.zhang@yale.edu).

## Table of Contents

- [Tutorial / Survey / Book](#tutorials)
- [Blogs](#blogs)
- [Papers](#papers)
  - [Neural CLIR](#neural-clir)
  - [Crosslingual Word Embeddings](#crosslingual-word-embeddings)
  - [Cross-lingual Learning](#cross-lingual-learning)
  - [Miscellaneous](#miscellaneous)
- [Datasets](#datasets)


## Tutorials
### CLIR
* Cross-Language Information Retrieval [[book](http://www.iro.umontreal.ca/~nie/IFT6255/Books/CLIR.pdf)]

### Cross-lingual Word Embeddings
* Cross-Lingual Word Representations: Induction and Evaluation (EMNLP 2017 Tutorial) [[slides](http://people.ds.cam.ac.uk/iv250/tutorial/xlingrep-tutorial.pdf)]
* A Survey of Cross-lingual Word Embedding Models (JAIR) ([paper](https://arxiv.org/pdf/1706.04902.pdf))

### Neural Networks for IR
* Neural Networks for Information Retrieval (SIGIR 2017, ECIR 2018, WSDM 2018 Tutorial) [[slides](http://nn4ir.com/wsdm2018/slides/NN4IR.pdf)]
* Neural Models for Information Retrieval [[video](https://www.youtube.com/watch?v=g1Pgo5yTIKg)][[paper](https://arxiv.org/pdf/1705.01509.pdf)]
* An Introduction to Neural Information Retrieval [[paper](https://www.microsoft.com/en-us/research/uploads/prod/2017/06/fntir2018-neuralir-mitra.pdf)]
* Neural Text Embeddings for Information Retrieval (WSDM 2017) [[slides](https://www.slideshare.net/BhaskarMitra3/neural-text-embeddings-for-information-retrieval-wsdm-2017)]
* Neural Information Retrieval: At the End of the Early Years (Information Retrieval Journal 2018) [[slides](https://link.springer.com/content/pdf/10.1007%2Fs10791-017-9321-y.pdf)]
* Neural Information Retrieval: A Literature Review [[paper](https://arxiv.org/abs/1611.06792)]
* Deep Learning for Information Retrieval (SIGIR 2016 Tutorial) [[paper](http://www.hangli-hl.com/uploads/3/4/4/6/34465961/sigir_tutorial.pdf)]
* Learning to Rank for Information Retrieval and Natural Language Processing [[book](http://www.iro.umontreal.ca/~nie/IFT6255/Books/Learning-to-rank.pdf)]

## Blogs
* [A survey of cross-lingual word embedding models](http://ruder.io/cross-lingual-embeddings/)
* [Under the hood: Multilingual embeddings](https://code.fb.com/ml-applications/under-the-hood-multilingual-embeddings/)

## Papers
### Neural CLIR

* Unsupervised Cross-Lingual Information Retrieval using Monolingual Data Only (SIGIR 2018) [[paper](https://arxiv.org/pdf/1805.00879.pdf)][[code](https://github.com/rlitschk/UnsupCLIR)]
* Monolingual and Cross-Lingual Information Retrieval Models Based on (Bilingual) Word Embeddings (SIGIR 2015) [[paper](https://dl.acm.org/citation.cfm?id=2767752)]
* Entity-Duet Neural Ranking: Understanding the Role of Knowledge Graph Semantics in Neural Information Retrieval (ACL 2018) [[paper](https://arxiv.org/pdf/1805.07591.pdf)][[code](https://github.com/thunlp/EntityDuetNeuralRanking)]
* Cross-lingual Learning-to-Rank with Shared Representations (NAACL 2018) [[paper](http://aclweb.org/anthology/N18-2073)][[data](http://www.cs.jhu.edu/~kevinduh/a/wikiclir2018/)]
* Learning to Match using Local and Distributed Representations of Text for Web Search (WWW 2017) [[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/wwwfp0192-mitra.pdf)][[code](https://github.com/faneshion/MatchZoo)]
* PACRR: A Position-Aware Neural IR Model for Relevance Matching (EMNLP 2017) [[paper](https://arxiv.org/pdf/1704.03940.pdf)][[code](https://github.com/khui/copacrr)]
* Co-PACRR: A Context-Aware Neural IR Model for Ad-hoc Retrieval (WSDM 2018) [[paper](https://arxiv.org/pdf/1706.10192.pdf)][[code](https://github.com/khui/copacrr)]
* Learning to Translate: A Query-Specific Combination Approach for Cross-Lingual Information Retrieval (EMNLP 2014) [[paper](http://www.aclweb.org/anthology/D14-1064)]
* Representation Learning Using Multi-Task Deep Neural Networks for Semantic Classification and Information Retrieval (NAACL 2015)[[paper](http://www.aclweb.org/anthology/N15-1092)]
* A Dual Embedding Space Model for Document Ranking (WWW 2016)[[paper](https://arxiv.org/pdf/1602.01137.pdf)]
* Query Expansion with Locally-Trained Word Embeddings (ACL 2016)[[paper](http://www.aclweb.org/anthology/P16-1035)]
* A Latent Semantic Model with Convolutional-Pooling Structure for Information Retrieval (CIKM 2014)[[paper](http://www.iro.umontreal.ca/~lisa/pointeurs/ir0895-he-2.pdf)]
* Toward Incorporation of Relevant Documents in word2vec (NeuIR-SIGIR 2017)[[paper](https://arxiv.org/pdf/1707.06598.pdf)]
* Using Word Embeddings for Automatic Query Expansion (NeuIR-SIGIR 2016)[[paper](https://arxiv.org/pdf/1606.07608.pdf)]
* Query Expansion Using Word Embeddings (CIKM 2016)[[paper](https://dl.acm.org/citation.cfm?id=2983876)]
* Improved Cross-Language Retrieval using Backoff Translation (HLT 2001)[[paper](http://www.aclweb.org/anthology/H01-1033)]

### Crosslingual Word Embeddings

* (MUSE) Word Translation Without Parallel Data (ICLR 2018) [[paper](https://arxiv.org/abs/1710.04087)][[github](https://github.com/facebookresearch/MUSE)][[blog](https://code.fb.com/ml-applications/under-the-hood-multilingual-embeddings/)]
* (Babylon - fastText_multilingual) Offline bilingual word vectors, orthogonal transformations and the inverted softmax (ICLR 2017) [[paper](https://arxiv.org/pdf/1702.03859.pdf)][[github](https://github.com/Babylonpartners/fastText_multilingual)]
* Learning Crosslingual Word Embeddings without Bilingual Corpora (EMNLP 2016) [[paper](https://www.aclweb.org/anthology/D16-1136.pdf)][[github](https://github.com/longdt219/XlingualEmb)]
* Multilingual Training of Crosslingual Word Embeddings (EACL 2017)[[paper](http://www.aclweb.org/anthology/E17-1084)]
* Unsupervised Multilingual Word Embeddings (EMNLP 2018)[[paper](https://arxiv.org/pdf/1808.08933.pdf)][[code](https://github.com/ccsasuke/umwe)]
* (multiCluster and multiCCA) Massively Multilingual Word Embeddings [[paper](https://arxiv.org/pdf/1602.01925.pdf)]
* (bivec) Bilingual Word Representations with Monolingual Quality in Mind (NAACL 2015 workshop)[[paper](http://www.aclweb.org/anthology/W15-1521)][[github](https://github.com/lmthang/bivec)]
* Cross-lingual Models of Word Embeddings: An Empirical Comparison (ACL 2016) [[paper](http://www.aclweb.org/anthology/P16-1157)]
* Bilingual Embeddings with Random Walks over Multilingual Wordnets (Knowledge-Based Systems, 2018) [[paper](https://arxiv.org/pdf/1804.08316.pdf)]
* Cross-lingual Word Clusters for Direct Transfer of Linguistic Structure (NAACL 2012) [[paper](http://delivery.acm.org/10.1145/2390000/2382096/p477-tackstrom.pdf?ip=130.132.173.188&id=2382096&acc=OPEN&key=AA86BE8B6928DDC7%2E25D92BB326E6095D%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1536335661_d8878fb5bf0ea86c483a98915f378c6b)]
* Improving Cross-Lingual Word Embeddings by Meeting in the Middle (EMNLP 2018) [[paper](https://arxiv.org/pdf/1808.08780.pdf)]
* CLUSE: Cross-Lingual Unsupervised Sense Embedding (EMNLP 2018) [[paper](http://aclweb.org/anthology/D18-1025)][[code](https://github.com/MiuLab/CLUSE)]
* Unsupervised Cross-lingual Transfer of Word Embedding Spaces (EMNLP 2018) [[paper](https://arxiv.org/pdf/1809.03633.pdf)]

### Cross-lingual Learning

* Cross-Lingual Morphological Tagging for Low-Resource Languages (ACL 2016) [[paper](http://www.aclweb.org/anthology/P16-1184)]
* Phrase-Based & Neural Unsupervised Machine Translation (EMNLP 2018) [[paper](https://arxiv.org/pdf/1804.07755.pdf)]
* Joint Representation Learning of Cross-lingual Words and Entities via Attentive Distant Supervision (EMNLP 2018) [[paper](http://aclweb.org/anthology/D18-1021)]
* XL-NBT: A Cross-lingual Neural Belief Tracking Framework (EMNLP 2018) [[paper](https://arxiv.org/pdf/1808.06244.pdf)]
* Adversarial Propagation and Zero-Shot Cross-Lingual Transfer of Word Vector Specialization (EMNLP 2018) [[paper](https://arxiv.org/pdf/1809.04163.pdf)]
* Cross-lingual Lexical Sememe Prediction (EMNLP 2018) [[paper](http://aclweb.org/anthology/D18-1033)]
* Joint Multilingual Supervision for Cross-lingual Entity Linking (EMNLP 2018) [[paper](https://arxiv.org/pdf/1809.07657.pdf)]
* Cross-lingual Knowledge Graph Alignment via Graph Convolutional Networks (EMNLP 2018) [[paper](http://aclweb.org/anthology/D18-1032)]
* Neural Cross-lingual Named Entity Recognition with Minimal Resources (EMNLP 2018) [[paper](https://arxiv.org/pdf/1808.09861.pdf)]
* Multi-lingual Common Semantic Space Construction via Cluster-Consistent Word Embedding (EMNLP 2018) [[paper](https://arxiv.org/pdf/1804.07875.pdf)]
* XNLI: Evaluating Cross-lingual Sentence Representations (EMNLP 2018) [[paper](https://arxiv.org/abs/1809.05053)]

### Miscellaneous

* Morphological Word-Embeddings (NAACL 2015) [[paper](http://www.aclweb.org/anthology/N15-1140)]
* Discriminative Reranking for Machine Translation (NAACL 2004) [[paper](http://www.aclweb.org/anthology/N04-1023)]
* Discriminative Reranking for Natural Language Parsing (Computational Linguistics) [[paper](https://www.mitpressjournals.org/doi/abs/10.1162/0891201053630273)]
* Probabilistic Structured Query Methods (SIGIR 2003) [[paper](https://dl.acm.org/citation.cfm?id=860497)]
* Strong Baselines for Neural Semi-supervised Learning under Domain Shift (ACL 2018) [[paper](https://arxiv.org/abs/1804.09530)]
* Transfer Learning for Low-Resource Neural Machine Translation (EMNLP 2016) [[paper](https://aclweb.org/anthology/D16-1163.pdf)]
* Meta-Learning for Semi-Supervised Few-Shot Classification (ICLR 2018) [[paper](https://arxiv.org/pdf/1803.00676.pdf)]
* One-shot Learning with Memory-Augmented Neural Networks [[paper](https://arxiv.org/pdf/1605.06065.pdf)]
* Low-Resource Semantic Role Labeling (ACL 2014) [[paper](http://www.aclweb.org/anthology/P14-1111)]
* Universal Neural Machine Translation for Extremely Low Resource Languages (NAACL 2018) [[paper](https://arxiv.org/pdf/1802.05368.pdf)]
* An Unsupervised Word Sense Disambiguation System for Under-Resourced Languages (LREC 2018) [[paper](https://arxiv.org/pdf/1804.10686.pdf)]