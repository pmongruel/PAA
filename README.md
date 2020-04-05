# PAA

#on importe ce qu'il nous faut en termes de librairies 
import time
import random

import numpy as np
import pandas as pd
import seaborn as sns
from matplotlib import pyplot as plt
from IPython.display import Markdown, display
from sklearn import metrics
from sklearn.preprocessing import LabelEncoder, OneHotEncoder, MinMaxScaler
from sklearn.model_selection import train_test_split
from sklearn import linear_model, svm

%matplotlib inline
rnd_seed_state = 1

#on importe les données et on les place dans un tableau 
fundamentals_file_price = '/Users/preparation/Desktop/nyse/fundamentals.csv'
fundamentals_data = pd.read_csv(fundamentals_file_price)

fundamentals_data.head()
#ici on teste pour voir si le tableau fonctionne

