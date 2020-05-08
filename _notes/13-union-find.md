## Bitwise


3 prerequisite
- Sorted
- Bounded
- Accessiable by index


## Template 1: []
```
  left = 0
  right = len(array) - 1

  while (left <= right>)
    mid = (left + right) / 2
    if (array[mid] == target)
      return result
    else if (array[mid] < target)
      left = mid + 1
    else
      right = mid -1
```

## Template 2: [)
```
  left = 0
  right = len(array) - 1

  while (left <= right>)
    mid = (left + right) / 2
    if (array[mid] == target)
      return result
    else if (array[mid] < target)
      left = mid + 1
    else
      right = mid -1
```


## Problems
- Leetcode 69: sqrt(x)