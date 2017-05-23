

```python
# pandas Series
import numpy as np
import pandas as pd
```


```python
s = pd.Series(np.random.randn(5), index=['a', 'b', 'c', 'd', 'e'])
s
```




    a    0.912206
    b    0.159562
    c    0.275342
    d   -0.163825
    e    0.680719
    dtype: float64




```python
s*(-1)
```




    a   -0.912206
    b   -0.159562
    c   -0.275342
    d    0.163825
    e   -0.680719
    dtype: float64




```python
d = {'a' : "apple", 'b' : 1, 'c' : 2}
d=pd.Series(d)
d
```




    a    apple
    b        1
    c        2
    dtype: object




```python
s[0]
```




    0.91220640184398494




```python
s[:3]
```




    a    0.912206
    b    0.159562
    c    0.275342
    dtype: float64




```python
s[2:3]
```




    c    0.275342
    dtype: float64




```python
s[[4, 3, 1]]
```




    e    0.680719
    d   -0.163825
    b    0.159562
    dtype: float64




```python
c =s[1:3] + d[1:]
c
```




    b    1.15956
    c    2.27534
    dtype: object




```python

```


```python

```
