# Netflix movie recommendation

Netflix is one of the biggest platforms of entertainment consumption that we have around us and therefore it only makes sense that Netflix employs a highly effficient system of content recommendation. According to sources, the recommendation systems bring in about $1Bn worth of value through cutomer retention. The recommending systems at Netflix include various algorithms like reinforcement learning, neural networks, causal modelling, probabilistic graphical models, matrix factorization, ensembles, bandits.

This notebook, obviously is not as sophisticatd as those models. This is a simpler model based on Pearson's correlation coefficient. The top 10 movies with the highest correlation coefficent to the movies that you suggested are shown.

This project started when I came across a competition organsised by Netflix. View the competition [here](https://www.netflixprize.com/). The associated dataset for this implemenatation is a whooping 2GB in size. Therefore, I'm including a link for the same. Click [here](https://www.kaggle.com/netflix-inc/netflix-prize-data) for the dataset.

## Prerequisites
This notebook requires the following libraries:
* pandas
* numpy
* math
* regex*
* scipy
* matplotlib
* seaborn
* surprise*

The installation of the star-marked libraries can be done on Jupyter through:
```sh
$ conda install -c conda-forge regex
$ conda install -c conda-forge scikit-surprise
```



#### License
---
Apache 2.0

