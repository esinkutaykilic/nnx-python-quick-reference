# Python quick reference

## Basic data structures
<a href="List.md">...go to Basic data structures</a>

### List
Ordered, changeable, allows duplication
```Python
my_list = [1, 2, 'some string', True, 2]
```
<a href="List.md">...details (List)</a>

### Tuple
Ordered, **unchangeable**, allows duplication
```Python
my_tuple = (1, 2, 'some string', True, 2)
```
<a href="Tuple.md">...details (Tuple)</a>

### Set
**Unordered**, **unchangeable**, **not allows duplication**
```Python
my_list = {1, 2, 'some string', False}
```
<a href="Set.md">...details (Set)</a>

### Dictionary
Ordered, changeable, **not allows duplication**
```Python
my_dictionary = {
    "name": "Marty"
    "surname": "McFly"
    "travel_to": 2015 
}
```
<a href="Dictionary.md">...details (Dictionary)</a>


## Control flows
<a href="Control-flows.md">...go to Control flows</a>


### if and else
```Python
a = 42
if a == 42:
    print("Answer to the ultimate question of life, the universe, and everything.")
elif a = 2015:
    print("Welcome to the future.")
else:
    print("I have come here to chew bubblegum and kick ass… and I’m all out of bubblegum.")
```
<a href="if-and-else.md">...details (if and else)</a>

### while
```Python
i = 1
while i < 42:
  i += 1
```
<a href="while.md">...details (while)</a>

### for
```Python
for i in range(42):
  print(i)
```
<a href="for.md">...details (for)</a>

## Functions
```Python
def my_function(name):
  print(f'Hello, {name}')

my_function('Marty')
```
<a href="Functions.md">...go to Functions</a>