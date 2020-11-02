# SMS-Spam-Classifier


**Overview** : Implementing a Spam classifier in python using Natural Language Processing.

**Technologies used** : Jupyter Notebook - To use JupyterNotebook, first, download Anaconda. By downloading Anaconda, you get conda, Python, Jupyter Notebook and hundreds of other open source packages.

**Libraries used** : 
```pythonscript
import pandas as pd
import re
import nltk
nltk.download('stopwords')
from nltk.corpus import stopwords
from nltk.stem.porter import PorterStemmer
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.model_selection import train_test_split
from sklearn.naive_bayes import MultinomialNB
from sklearn.metrics import confusion_matrix, accuracy_score
```

**Dataset Info** :
You can download this dataset from here : https://archive.ics.uci.edu/ml/datasets/sms+spam+collection
