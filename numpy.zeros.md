## What is numpy.zeros()?

np.zeros() function is used to create a matrix full of zeroes. It can be used when you initialize the weights during the first iteration in TensorFlow and other statistic tasks.

The syntax is
```python3
numpy.zeros(shape, dtype=float, order='C')
```
Here,
```
    Shape: is the shape of the array
    Dtype: is the datatype. It is optional. The default value is float64
    Order: Default is C which is an essential row style.
```
Example numpy zero
```python3
import numpy as np
np.zeros((2,2))
```
Output:
```python3
array([[0., 0.],
          [0., 0.]])
```
Example numpy zero with datatype
```python3
 import numpy as np
np.zeros((2,2), dtype=np.int16)
```
Output:
```python3
array([[0, 0],
         [0, 0]], dtype=int16)
```
#### What is numpy.ones()?

np.ones() function is used to create a matrix full of ones. It can be used when you initialize the weights during the first iteration in TensorFlow and other statistic tasks.
