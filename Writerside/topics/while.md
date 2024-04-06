# while

## else
```Python
i = 1
while i < 42:
  i += 1
else:
  print('i is no longer less than 42')
```

## continue
```Python
i = 1
while i < 50:
  i += 1
    
  if i == 42:
    continue
    
  print(i)
```

## break
```Python
i = 1
while i < 42:
  i += 1
  
  if i == 23:
    break
    
  print(i)
else:
  print('i is no longer less than 42') # never reachs
```