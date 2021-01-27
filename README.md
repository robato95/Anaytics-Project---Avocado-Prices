# Anaytics Project - Avocado Prices
The data set was obtained from Kaggle and details weekly retail data for retail volume(units) and price of avocados. The data starts in 2015 and contains various details related to the logistics of avocados shipped for each week up until the end of Q1 2018. Using the following packages, I explored the logistic details in the data and use this information to create a multiple linear regression model to predict avocado prices
```bash
import os
import pandas as pd
import numpy as np
from matplotlib import pyplot as plt
import sklearn
from sklearn import *
from sklearn.model_selection import train_test_split
from sklearn.metrics import *
```



![](/graphs/Forecast.png)
