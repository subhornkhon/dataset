# useful dataset for text analytic class

##import dataset from github to use in colab notebook

! git clone https://github.com/subhornkhon/dataset.git

import pandas as pd

dataset = pd.read_csv('dataset/Billboard Hot-100 Songs.csv')


dataset.head()
