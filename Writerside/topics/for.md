# for

## with data structures
```Python
my_list = [1, 2, 'some string', True, 2]

for item in my_list:
    print(item)
```

## with range
```Python
for i in range(42):
  print(i)
```

## else
```Python
for i in range(42):
    print(i)
else:
    print("Finally!")
```

## continue
```Python
for i in range(42):
    if i == 23:
        continue
        
    print(i)
```

## break
```Python
for i in range(42):
    if i == 23:
        break
        
    print(i)
else:
    print("Finally!") # never reachs
```
