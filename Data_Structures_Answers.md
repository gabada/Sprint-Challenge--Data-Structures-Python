Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method?

```
O(1) - Constant. There are no loops. It will have the same run time no matter how many
items are in the buffer.
```

2. What is the space complexity of your ring buffer's `append` function?

```
O(1) - Constant its never using more space
```

3. What is the runtime complexity of your ring buffer's `get` method?

```
O(n) - I am using a for loop (list comprehension) to loop over the items and return all that are not None.
```

4. What is the space complexity of your ring buffer's `get` method?

```
O(n) - In the list comprehension its creating a new list, as the items grow the list grows.
```

5. What is the runtime complexity of the provided code in `names.py`?

```
for name_1 in names_1: # O(n)
    for name_2 in names_2: # O(n)
        if name_1 == name_2: # O(1)
            duplicates.append(name_1) # O(1)
```
```
O(n^2)- Since there are two for loops that are each O(n) and O(n) * O(n) is 0(n^2)
```

6. What is the space complexity of the provided code in `names.py`?

```
O(n) - The more duplicates you have the more appends will be needed and more space will be taken.
```

7. What is the runtime complexity of your optimized code in `names.py`?

```
O(1) - constant - runtime complexity of set is O(1) and I do this twice and then compare.
```

8. What is the space complexity of your optimized code in `names.py`?

```
O(n) - The more duplicates you have the more space will be needed
```
