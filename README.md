# squiral
![](https://img.shields.io/pypi/v/squiral) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) ![]( https://img.shields.io/pypi/pyversions/squiral.svg )
### Install
````pip install squiral````

#### Usage
```
>>> import squiral as sq
>>> sq.printout(sq.produce(5))
21 22 23 24 25
20  7  8  9 10
19  6  1  2 11
18  5  4  3 12
17 16 15 14 13
>>>
```
**squ**are sp**iral**

```
Welcome to Squiral!
Here is an example:
21 22 23 24 25
20  7  8  9 10
19  6  1  2 11
18  5  4  3 12
17 16 15 14 13
```

The basic idea behind printing this matrix is to start from the middle of the matrix and then moving :
```right```>> ```down```>>``` left```>>``` up```
and not returning to the same row again
