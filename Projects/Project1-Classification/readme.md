## Authors
- [Gaurav Singh](https://github.com/gauravSingh30) 

# News Articles Classification
For classifying Sports and Climate news articles and to further sub classifiy them.

# Description
Text news articles are privided in dataset. The task is to classify each article into it's broad category: "Sports" or "Climate".

Further classify them into their sub-categories:
Sports -> Cricket, Football, Soccer, Chess
Climate -> Flood, Forest Fire, Drought, Earthquake

# Installation
To run these files you will need Jupyter Notebook.

Before start using these scripts run -

pip install -r requirements.txt

After installation run below in jupyter notebook -
import nltk
nltk.download()

# Downloads

There are two variants of word2vec model that you can use:

1). The dataset can be downloaded from here: [dataset](https://drive.google.com/file/d/12VLfuWtCS3NiGLsHyn0YiWqD-mZvBu4z/view?usp=sharing)

2). Download pretrained GLoVE embeddings from hre: [GLoVE](http://nlp.stanford.edu/data/glove.6B.zip)

# Usage
    - Make necessary installations and downloads.
    - Change the paths in the .ipynb file where ever there is a import such as pd.read_csv
    - Run each cell in notebook to get the detailed results.