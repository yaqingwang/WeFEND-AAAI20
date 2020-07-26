# WeFEND-AAAI20
To be updated: Dataset for paper "Weak Supervision for Fake News Detection via Reinforcement Learning" published in AAAI'2020.

[Weak Supervision for Fake News Detection via Reinforcement Learning](https://arxiv.org/abs/1912.12520)  
 [Yaqing Wang](http://www.acsu.buffalo.edu/~yaqingwa/),
 Weifeng Yang,
 [Fenglong Ma](http://www.personal.psu.edu/ffm5105/), 
  Jin Xu, Bin Zhong, Qiang Deng,
 [Jing Gao](https://cse.buffalo.edu/~jing/)
 
 SUNY Buffalo. AAAI, 2020.
 
 
 
 ## Main Idea
 ### Challenge: 
Due to the __dynamic nature__ of news, annotated samples may become __outdated__ quickly and cannot represent the news articles on newly emerged events. Therefore, how to obtain __fresh and
high-quality labeled samples__ is the major challenge in employing deep learning models for fake news detection.

### Solution: 
We propose a reinforced weaklysupervised fake news detection framework, i.e., WeFEND,
which can __leverage users’ reports as weak supervision__ to enlarge the amount of training data for fake news detection.

## Experiment
We aim to answer two important questions:
  * Does the distribution of news change with time?
  * why should we use the reports to annotate the fake
news?

<img src="https://github.com/yaqingwang/WeFEND-AAAI20/blob/master/figs/current_fake_real.jpg" width="300">  <img src="https://github.com/yaqingwang/WeFEND-AAAI20/blob/master/figs/future_fake_real.jpg" width="300">



<img src="https://github.com/yaqingwang/WeFEND-AAAI20/blob/master/figs/fake_news.jpg" width="256">  <img src="https://github.com/yaqingwang/WeFEND-AAAI20/blob/master/figs/fake_reports.jpg" width="256">
 



