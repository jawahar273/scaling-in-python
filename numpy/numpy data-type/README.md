

```python

>>> hetegen = np.array([1, 2., '3', [10, 20.],(30, 40. )]).dtype
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: setting an array element with a sequence
```
You should always set arrays in the sequence(iteration) manner not a single element manner

```python

>>> hetegen = np.array([(1, 2, 3), [1, 2, 3, 4], 33]).dtype
>>> hetegen
dtype('O')


```
