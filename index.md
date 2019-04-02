# Arrays

## Problem

#### [HackerRank](www.hackerrank.com)

> Given an array, A, of N integers, print A's elements in reverse order as a single line of space-separated numbers. - [HackerRank](www.hackerrank.com)

## Pseudo Code

```python
# Reverse Array
# Turn array into a string
# Join array
# Print results
```

## Code

#### Reverse Array

```python
arr[::-1]
```

#### Turn array into a string

```python
[str(i) for i in arr[::-1]]
```

#### Join array

```python
" ".join(str(i) for i in arr[::-1])
```

#### Print results

```python
print(" ".join(str(i) for i in arr[::-1]))
```

## Full Code

```python
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input())

    arr = list(map(int, input().rstrip().split()))

    print(" ".join(str(i) for i in arr[::-1]))
```

## Conclusion

Probably the most simple solution but still fun and a good reminder of how to reverse an array and turn it into a string while joining it.
