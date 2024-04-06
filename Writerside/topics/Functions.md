# Functions

```Python
def my_function(name):
  print(f'Hello, {name}')

my_function('Marty')
```

## Arbitrary arguments, *args
```Python
def my_function(*names):
    for name in names:
        print(f'Hello, {name}')

my_function('Marty', 'Doc')
```

## lambda
```Python
x = lambda a, b : a * b
print(x(6, 7))
```