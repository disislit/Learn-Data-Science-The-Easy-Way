You can install NumPy using Anaconda:

`conda install -c anaconda numpy		`

In Jupyter Notebook : 

```python3
import sys
!conda install --yes --prefix {sys.prefix} numpy
```

#### Import NumPy and Check Version

The command to import numpy is

`import numpy as np			`

Above code renames the Numpy namespace to np. This permits us to prefix Numpy function, methods, and attributes with " np " instead of typing " numpy." It is the standard shortcut you will find in the numpy literature

To check your installed version of Numpy use the command

 `print (np.__version__)`

Output

`1.18.0`
