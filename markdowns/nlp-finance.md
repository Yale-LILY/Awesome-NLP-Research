# Annotated Bibliography for Natural Language Processing in Finance

Gaurav Pathak
gaurav.pathak@yale.edu

## General Background Information
These articles cover some basic terminology when using natural language processing to try to generate returns by predicting the movement of the stock market.
- [Efficient MarketHypothesis](http://web.mit.edu/Alo/www/Papers/EMH_Final.pdf)
- [Alpha](https://www.investopedia.com/terms/a/alpha.asp)
- [Beta](https://www.investopedia.com/terms/b/beta.asp)

How these metrics may somtimes be inadequate/misleading while measuring performance is discussed in this paper [paper](https://www.researchgate.net/publication/228203525_The_ABCs_of_hedge_funds_Alphas_betas_and_costs) 


## Papers discussing NLP for Alpha generation
- [Twitter mood predicts the stock market](https://www.sciencedirect.com/science/article/pii/S187775031100007X?via%3Dihub)
In this paper the authors use twitter sentiment to predict the value of the Dow Jones Industrial Average. They classify tweets on pure positive/negative scores as well as scores for categories like happy, calm, vital etc. They find that the "calm" category gives good results when trying to precict directional accuracy (86%)
- [Causality Analysis of Twitter Sentiments and Stock Market Returns](http://aclweb.org/anthology/W18-3102)
This paper uses Amazon mechanical turk workers to classify tweets as positive or negative and use that as well as a classifier to do a granger causality analysis on prices and sentiment.
- [Textual Analysis of Stock Market Prediction Using Breaking Financial News: The AZFinText System](http://delivery.acm.org/10.1145/1470000/1462204/a12-schumaker.pdf?ip=130.132.173.74&id=1462204&acc=ACTIVE%20SERVICE&key=AA86BE8B6928DDC7%2E25D92BB326E6095D%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1544393609_408cd80f97db97609e7c21d3171faa75)
The authors build a system that uses various textual representations of breaking news to predict stock prices 20 mins into the future from the time of article release. The best performing model take in the price of a security at article release and the representation of the article as inputs to give a price estimate 20 mins into the future. When using a simulated trading engine that trades $1000 whenever the model predicts a price 1% different form the price at article release, their trading profits were positive 2%

However, when evaluating these results, baselines need to be carefully chosen. A signal can be considered successful only if it generated true "alpha", i.e. performance that is beyond what can be achieved by simply holding a benchmark set of securities in a risk adjusted basis. Thus, when evaluating the 2\% return of the trading engine in the breaking financial news paper, it is difficult to quantify its success without knowing how correlated that return was to the stock market benchmark.
Similarly, from a random walk hypothesis perspective, doing anything above a 50 \% prediction accuracy is a success for a system for one like in the 1st paper. However, it is important to realize that there is a certain degree of auto-correlation in market prices due to a variety of reasons, meaning that it is not uncommon for a market to "rally" for short periods of time. This is a further problem for the 1st paper which uses a test period of only 14 days to make its predictions. Rather than a 50 \% baseline, a better baseline could have been something along the lines of predicting the most frequent occurrence. 
## Other applications of NLP in finance
- [Deciphering Fedspeak: The Information Content of FOMC Meetings](https://poseidon01.ssrn.com/delivery.php?ID=315114126008086108120083078108118074098024084080093050120001085105069106119027114014013002025014022099108099105126090088107003021008057043054083007069110079096105094050008085020084088005113028099000092086003121093017122125102107072070124067095031086121&EXT=pdf)
Here, the Authors use LDA to see what topics are talked about the FOMC meetings and what proportion is each talked about across time.
- [Sentence Classification for Investment Rules Detection](http://aclweb.org/anthology/W18-3106)
Various methods such as logistic regression, CNNs and LSTMs are used to classify whether sentences in a fund's investment prospectus is related to an investment rule/mandate of the fund or not.

- [From word to financial time series embeddings](https://poseidon01.ssrn.com/delivery.php?ID=764097064115115095107027108080073029057062017031026026005090109067007086028083021031101007022041026027017101027076085020003069041034005023078069009107101080101078064065078040074030091071005113000089068093090112095070030118085072087086109080106105120067&EXT=pdf)
The author creates vector representation of various securities. The algorithm drawns on Word2Vec and GloVe. These vectors are visualized using T-SNE.







