# STWA
# Requirements
python 3.8.2 
scipy==1.7.1  
pytorch==1.10.0  
scikit-learn==1.0.1  
# How to use
## Dataset
The main directory contains the directories of two Twitter datasets: twitter15 and twitter16. In each directory, there are:  
ind.twitter1*.label files: the labels of all nodes in the source tweet-word graph.  
ind.twitter1*.features_index files: the index of words that nodes in the  source tweet-word graph. contained.  
ind.twitter1*.adj files: the weight adjacency matrix of the  source tweet-word graph.
ind.twitter1*.train files: the index of the training set in the  source tweet-word graph.
ind.twitter1*.dev files: the index of the validation set in the source tweet-word graph.
ind.twitter1*.test files: the index of the testing set in the  source tweet-word graph.  

## Training & Testing
sh run.sh 0 twitter15\[twitter16\]
