## Reshape Data

In some occasions, you need to reshape the data from wide to long. You can use the reshape function for this. The syntax is
```python3
numpy.reshape(a, newShape, order='C')
```
Here,
```python3
a: Array that you want to reshape
 ```
newShape: The new desires shape

Order: Default is C which is an essential row style.

Exampe of Reshape
Primis Player Placeholder
```python3
import numpy as np
e  = np.array([(1,2,3), (4,5,6)])
print(e)
e.reshape(3,2)
    ```
Output:
```python3
 // Before reshape
[[1 2 3] 
 [4 5 6]]			

//After Reshape
array([[1, 2],       
	[3, 4],       
	[5, 6]])			
```
Flatten Data

When you deal with some neural network like convnet, you need to flatten the array. You can use flatten(). The syntax is
```python3
numpy.flatten(order='C')
```
Here,

Order: Default is C which is an essential row style.

Exampe of Flatten
```python3
e.flatten()			
```
Output:
```python3
array([1, 2, 3, 4, 5, 6])			
```
