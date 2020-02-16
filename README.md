# Python Interview Study Guide
Review of Python syntax/data structures for interviews

## Loops

## Lists
- Mutable, ordered sequence
- O(n) to search, add, delete
  - Except when at end: O(1)
  
### Making Lists
foo = = ['a', 'b', 'c']

Can use constructor function, list()

`letters = list("apple")   # ['a', 'p', 'p', 'l', 'e']`

### Membership
- Can check for membership with in:
```python
if "taco" in foods:
    print("Yum!")

if "cheese" not in foods:
    print("Oh no!")
```

### Retrieving By Index
- Can retrieve/mutate item with [n]:
```python
print(fav_foods[0])
fav_foods[0] = "taco"
```
```python
fav_foods[-1]   # last item
fav_foods[-3]   # third from end
```

## 


