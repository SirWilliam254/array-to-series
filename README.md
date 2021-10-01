# array-to-series
## converting a numpy array into a series in python

 ~~~ python
# importing the modules
import numpy as np
import pandas as pd
  
# creating an NumPy array
array = np.array([0.6110171,
       0.48824037,
       0.43682726,
       0.25956369,
       0.34325678,
       0.42574109,
       0.58201807,
       0.44945605,
       0.33745467,
       0.26719622,
       0.31969148])
  
  
# converting the NumPy array to a Pandas series
series = pd.Series(array) 
~~~ 
## multidimentional array to a single dimension array

~~~ python
ary = np.array([[1,2,3], [4,5,6]])
~~~

We can use two methods , ravel or flatten
## Ravel

~~~ python
singl = ary.ravel()
~~~

## Flatten

~~~ python
singl2 = ary.flatten()
~~~
