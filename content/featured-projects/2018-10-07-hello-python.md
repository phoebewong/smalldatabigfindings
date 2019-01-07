---
title: Hello Python
author: Phoebe Wong
date: '2018-10-07'
slug: hello-python
categories: []
tags: []
---



```python
import numpy as np
import pandas as pd
import matplotlib
import matplotlib.pyplot as plt

import statsmodels.api as sm
from statsmodels.api import OLS

from sklearn import preprocessing
from sklearn.preprocessing import PolynomialFeatures
from sklearn.metrics import r2_score
from sklearn.model_selection import train_test_split

from pandas.plotting import scatter_matrix

import seaborn as sns


%matplotlib inline
```


```python
x = np.random.rand(10)
```


```python
x
```




    array([0.73277206, 0.07437201, 0.70124754, 0.45990054, 0.09517716,
           0.53841431, 0.79865311, 0.59982175, 0.43122864, 0.18456968])




```python
plt.hist(x)
```




    (array([2., 1., 0., 0., 1., 1., 1., 1., 1., 2.]),
     array([0.07437201, 0.14680012, 0.21922823, 0.29165634, 0.36408445,
            0.43651256, 0.50894067, 0.58136878, 0.65379689, 0.726225  ,
            0.79865311]),
     <a list of 10 Patch objects>)




![png](python/Python-for-website_files/Python-for-website_3_1.png)

