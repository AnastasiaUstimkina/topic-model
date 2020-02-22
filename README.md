# topic-model
## PLSA (Probabilistic Latent Semantic Analysis)
This is a python implementation of Probabilistic Latent Semantic Analysis using EM algorithm.

#### The meaning of params are given as following:

| param	|description 
| :-------------: |:------------------:| 
| datasetFilePath	|the file path of dataset
| stopwordsFilePath|	the file path of stopwords
| K	|the number of topic|
| maxIteration	|the max number of iteration of EM algorithm
| topicWordsNum|	the number of top words of each topic
| docTopicDisFilePath	|the file path to output document-topic distribution
| topicWordDistributionthe |file path to output topic-word distribution
| dictionaryFilePa	|the file path to output dictionary
| topicsFilePathe |file path to output top words of each topic

#### Format of inputs:
In the dataset file, each line represents a document.

In the stopwords file, each line represents a stopword.
