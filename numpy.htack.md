## What is hstack?

With hstack you can appened data horizontally. This is a very convinient function in Numpy. Lets study it with an example:
```python3
## Horitzontal Stack
import numpy as np
f = np.array([1,2,3])
g = np.array([4,5,6])

print('Horizontal Append:', np.hstack((f, g)))
```
Output:
```python3
Horizontal Append: [1 2 3 4 5 6]
```
What is vstack?

With vstack you can appened data vertically. Lets study it with an example:
```python3
## Vertical Stack
import numpy as np
f = np.array([1,2,3])
g = np.array([4,5,6])

print('Vertical Append:', np.vstack((f, g)))
```
Output:
```python3
Vertical Append: [[1 2 3]
 [4 5 6]]
```
Generate Random Numbers

To generate random numbers for Gaussian distribution use
```python3
numpy.random.normal(loc, scale, size)
```
Here

    Loc: the mean. The center of distribution
    scale: standard deviation.
    Size: number of returns

## Generate random nmber from normal distribution
```python3
normal_array = np.random.normal(5, 0.5, 10)
print(normal_array)			
[5.56171852 4.84233558 4.65392767 4.946659   4.85165567 5.61211317 4.46704244 5.22675736 4.49888936 4.68731125]			
```
