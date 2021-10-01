# array-to-series
## converting a numpy array into a series in python

 ~~~ python
# importing the modules
import numpy as np
import pandas as pd
  
# creating an NumPy array
array = np.array([10, 20, 1, 2, 
                   3, 4, 5, 6, 7])
  
  
# converting the NumPy array 
# to a Pandas series
series = pd.Series(array) 
~~~ 
